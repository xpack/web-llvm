---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/optbisect-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `OptBisect.cpp` File Reference

<p>This file implements support for a bisecting optimizations based on a command line option. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/optbisect-h">llvm/IR/OptBisect.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/optbisect">OptBisect</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3b9bb4158a05960fa58efda838118b4">getOptBisector</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7450cb8edb7a3eb084e8dc7b13363da2">printPassMessage</a> (const StringRef &amp;Name, int PassNum, StringRef TargetDesc, bool Running)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0655eec735358b68e584c863036e665">OptBisectLimit</a>("opt-bisect-limit", cl::Hidden, cl::init(OptBisect::Disabled), cl::Optional, cl::cb< void, int >([](int Limit) { getOptBisector().setLimit(Limit);}), cl::desc("Maximum optimization to perform"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40d90826b6a4adc27d7a3e109538aa11">OptBisectVerbose</a>("opt-bisect-verbose", cl::desc("Show verbose output when opt-bisect-limit is set"), cl::Hidden, cl::init(true), cl::Optional)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This file implements support for a bisecting optimizations based on a command line option.</p>

<div class="doxySectionDef">

## Functions

### getOptBisector() {#ac3b9bb4158a05960fa58efda838118b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptBisect &amp; getOptBisector ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/optbisect-cpp">OptBisect.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a40dfa1d23e21383d154cb6905aaa8031">llvm::getGlobalPassGate</a>.</p>

</div>
</div>

### printPassMessage() {#a7450cb8edb7a3eb084e8dc7b13363da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printPassMessage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Name, int PassNum, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TargetDesc, bool Running)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/optbisect-cpp">OptBisect.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/optbisect/#a0f286bb86d244482b2f03ac4f1943423">llvm::OptBisect::shouldRunPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### OptBisectLimit {#ad0655eec735358b68e584c863036e665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; OptBisectLimit("opt-bisect-limit", cl::Hidden, cl::init(OptBisect::Disabled), cl::Optional, cl::cb&lt; void, int &gt;([](int Limit) { getOptBisector().setLimit(Limit); }), cl::desc("Maximum optimization to perform"))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/optbisect-cpp">OptBisect.cpp</a>.</p>

</div>
</div>

### OptBisectVerbose {#a40d90826b6a4adc27d7a3e109538aa11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; OptBisectVerbose("opt-bisect-verbose", cl::desc("Show verbose output when opt-bisect-limit is set"), cl::Hidden, cl::init(true), cl::Optional)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/optbisect-cpp">OptBisect.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/optbisect/#a0f286bb86d244482b2f03ac4f1943423">llvm::OptBisect::shouldRunPass</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
