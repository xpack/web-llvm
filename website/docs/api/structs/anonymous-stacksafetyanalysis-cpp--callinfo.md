---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-stacksafetyanalysis-cpp-/callinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CallInfo` Struct Template Reference

<p>Describes use of address in as a function call argument. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename CalleeTy&gt;
struct anonymous{StackSafetyAnalysis.cpp}::CallInfo&lt;CalleeTy&gt; { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CalleeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad04ff55d436965d30cbae63efd3894f7">CallInfo</a> (const CalleeTy *Callee, size_t ParamNo)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CalleeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> CalleeTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a257dc09cbb9c09c33b3236556df111fd">Callee</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> being called. <a href="#a257dc09cbb9c09c33b3236556df111fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CalleeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a64d25fa44e26a572b977ae500a0bf6c1">ParamNo</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index of argument which pass address. <a href="#a64d25fa44e26a572b977ae500a0bf6c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Describes use of address in as a function call argument.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CallInfo() {#ad04ff55d436965d30cbae63efd3894f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CalleeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{StackSafetyAnalysis.cpp}::CallInfo&lt; CalleeTy &gt;::CallInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> CalleeTy * Callee, size_t ParamNo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<p>References <a href="#a257dc09cbb9c09c33b3236556df111fd">anonymous{StackSafetyAnalysis.cpp}::CallInfo&lt; CalleeTy &gt;::Callee</a> and <a href="#a64d25fa44e26a572b977ae500a0bf6c1">anonymous{StackSafetyAnalysis.cpp}::CallInfo&lt; CalleeTy &gt;::ParamNo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-stacksafetyanalysis-cpp-/callinfo/less/#a8e306ab69baa8472fd1ae05b4087a9d5">anonymous{StackSafetyAnalysis.cpp}::CallInfo&lt; CalleeTy &gt;::Less::operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Callee {#a257dc09cbb9c09c33b3236556df111fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CalleeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CalleeTy* anonymous{StackSafetyAnalysis.cpp}::CallInfo&lt; CalleeTy &gt;::Callee = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> being called.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#ad04ff55d436965d30cbae63efd3894f7">anonymous{StackSafetyAnalysis.cpp}::CallInfo&lt; CalleeTy &gt;::CallInfo</a>.</p>

</div>
</div>

### ParamNo {#a64d25fa44e26a572b977ae500a0bf6c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CalleeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{StackSafetyAnalysis.cpp}::CallInfo&lt; CalleeTy &gt;::ParamNo = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index of argument which pass address.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#ad04ff55d436965d30cbae63efd3894f7">anonymous{StackSafetyAnalysis.cpp}::CallInfo&lt; CalleeTy &gt;::CallInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp">StackSafetyAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
