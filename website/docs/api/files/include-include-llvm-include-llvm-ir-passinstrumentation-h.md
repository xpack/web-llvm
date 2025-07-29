---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `PassInstrumentation.h` File

<p>This file defines the Pass Instrumentation classes that provide instrumentation points into the pass execution by PassManager. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/any-h">llvm/ADT/Any.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">llvm/ADT/FunctionExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include &lt;type_traits&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class manages callbacks registration, as well as provides a way for <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation">PassInstrumentation</a> to pass control to the registered callbacks. <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passinstrumentation">PassInstrumentation</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class provides instrumentation entry points for the <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager, doing calls to callbacks registered in <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a>. <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passinstrumentationanalysis">PassInstrumentationAnalysis</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pseudo-analysis pass that exposes the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/passinstrumentation">PassInstrumentation</a></span> to pass managers. <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationanalysis/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This file defines the Pass Instrumentation classes that provide instrumentation points into the pass execution by PassManager.</p>


<p>There are two main classes:</p>


<ul class="doxyList ">
<li>PassInstrumentation provides a set of instrumentation points for pass managers to call on.</li>
<li>PassInstrumentationCallbacks registers callbacks and provides access to them for PassInstrumentation.</li>
</ul>

<p>PassInstrumentation object is being used as a result of PassInstrumentationAnalysis (so it is intended to be easily copyable).</p>


<p>Intended scheme of use for Pass Instrumentation is as follows:</p>


<ul class="doxyList ">
<li>register instrumentation callbacks in PassInstrumentationCallbacks instance. PassBuilder provides helper for that.</li>
<li>register PassInstrumentationAnalysis with all the PassManagers. PassBuilder handles that automatically when registering analyses.</li>
<li>Pass Manager requests PassInstrumentationAnalysis from analysis manager and gets PassInstrumentation as its result.</li>
<li>Pass Manager invokes PassInstrumentation entry points appropriately, passing StringRef identification ("name") of the pass currently being executed and IRUnit it works on. There can be different schemes of providing names in future, currently it is just a <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name()</a> of the pass.</li>
<li>PassInstrumentation wraps address of IRUnit into <a href="/web-llvm/docs/api/classes/llvm/any">llvm::Any</a> and passes control to all the registered callbacks. Note that we specifically wrap 'const IRUnitT*' so as to avoid any accidental changes to IR in instrumenting callbacks.</li>
<li>Some instrumentation points (BeforePass) allow to control execution of a pass. For those callbacks returning false means pass will not be executed.</li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
