---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mccvfunctioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MCCVFunctionInfo` Struct Reference

<p>Information describing a function or inlined call site introduced by .cv_func_id or .cv_inline_site_id. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MCCVFunctionInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">llvm/MC/MCCodeView.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#a483f476cd95fc83549dce653648091bb">...</a> }</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa848840fee854639c25ef7f0535683e0">isUnallocatedFunctionInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is function info has not yet been used in a .cv_func_id or .cv_inline_site_id directive. <a href="#aa848840fee854639c25ef7f0535683e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b7e1edb7b7e785ed88dda2b58ebbaf">isInlinedCallSite</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this represents an inlined call site, meaning ParentFuncIdPlusOne is neither zero nor ~0U. <a href="#a18b7e1edb7b7e785ed88dda2b58ebbaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93576d7e8ccff5b51884e3202af7d991">getParentFuncId</a> () const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6501b119f7ba7b15237d1f43dd16ccbc">ParentFuncIdPlusOne</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this represents an inlined call site, then ParentFuncIdPlusOne will be the parent function id plus one. <a href="#a6501b119f7ba7b15237d1f43dd16ccbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo/lineinfo">LineInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a364d97d77cb1c191b75ad223b360ff28">InlinedAt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a57622bc8d3165baf9cae9606a20c33">Section</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The section of the first .cv_loc directive used for this function, or null if none has been seen yet. <a href="#a5a57622bc8d3165baf9cae9606a20c33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/structs/llvm/mccvfunctioninfo/lineinfo">LineInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae30c8d77d4c26d16cc60ebd3de0f3b26">InlinedAtMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from inlined call site id to the inlined at location to use for that call site. <a href="#ae30c8d77d4c26d16cc60ebd3de0f3b26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Information describing a function or inlined call site introduced by .cv_func_id or .cv_inline_site_id.</p>


<p>Accumulates information from .cv_loc directives used with this function's id or the id of an inlined call site within this function or inlined call site.</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a483f476cd95fc83549dce653648091bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FunctionSentinel<a id="a483f476cd95fc83549dce653648091bbab32b95a936d6a5df6c580b24b5a4b1f1"></a></td>
<td class="doxyEnumItemDescription"> (= ~0U)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getParentFuncId() {#a93576d7e8ccff5b51884e3202af7d991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCCVFunctionInfo::getParentFuncId ()</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a18b7e1edb7b7e785ed88dda2b58ebbaf">isInlinedCallSite</a> and <a href="#a6501b119f7ba7b15237d1f43dd16ccbc">ParentFuncIdPlusOne</a>.</p>

</div>
</div>

### isInlinedCallSite() {#a18b7e1edb7b7e785ed88dda2b58ebbaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCCVFunctionInfo::isInlinedCallSite ()</td>
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

<p>Returns true if this represents an inlined call site, meaning ParentFuncIdPlusOne is neither zero nor ~0U.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>


<p>References <a href="#a483f476cd95fc83549dce653648091bbab32b95a936d6a5df6c580b24b5a4b1f1">FunctionSentinel</a>, <a href="#aa848840fee854639c25ef7f0535683e0">isUnallocatedFunctionInfo</a> and <a href="#a6501b119f7ba7b15237d1f43dd16ccbc">ParentFuncIdPlusOne</a>.</p>


<p>Referenced by <a href="#a93576d7e8ccff5b51884e3202af7d991">getParentFuncId</a>.</p>

</div>
</div>

### isUnallocatedFunctionInfo() {#aa848840fee854639c25ef7f0535683e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCCVFunctionInfo::isUnallocatedFunctionInfo ()</td>
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

<p>Returns true if this is function info has not yet been used in a .cv_func_id or .cv_inline_site_id directive.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>


<p>Reference <a href="#a6501b119f7ba7b15237d1f43dd16ccbc">ParentFuncIdPlusOne</a>.</p>


<p>Referenced by <a href="#a18b7e1edb7b7e785ed88dda2b58ebbaf">isInlinedCallSite</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### InlinedAt {#a364d97d77cb1c191b75ad223b360ff28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineInfo llvm::MCCVFunctionInfo::InlinedAt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>

</div>
</div>

### InlinedAtMap {#ae30c8d77d4c26d16cc60ebd3de0f3b26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, LineInfo&gt; llvm::MCCVFunctionInfo::InlinedAtMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from inlined call site id to the inlined at location to use for that call site.</p>


<p>Call chains are collapsed, so for the call chain 'f -&gt; g -&gt; h', the InlinedAtMap of 'f' will contain entries for 'g' and 'h' that both list the line info for the 'g' call site.</p>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a2c00c11ef810b9f4ca1781a341de60d3">llvm::CodeViewContext::encodeInlineLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a959bbaf3c63e93e00c5f5c2df6a1af19">llvm::CodeViewContext::getFunctionLineEntries</a> and <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#ab789beed200191eaf4736b9ab5d734b1">llvm::CodeViewContext::getLineExtentIncludingInlinees</a>.</p>

</div>
</div>

### ParentFuncIdPlusOne {#a6501b119f7ba7b15237d1f43dd16ccbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCCVFunctionInfo::ParentFuncIdPlusOne = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this represents an inlined call site, then ParentFuncIdPlusOne will be the parent function id plus one.</p>


<p>If this represents a normal function, then there is no parent, and ParentFuncIdPlusOne will be FunctionSentinel. If this struct is an unallocated slot in the function info vector, then ParentFuncIdPlusOne will be zero.</p>


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>


<p>Referenced by <a href="#a93576d7e8ccff5b51884e3202af7d991">getParentFuncId</a>, <a href="#a18b7e1edb7b7e785ed88dda2b58ebbaf">isInlinedCallSite</a>, <a href="#aa848840fee854639c25ef7f0535683e0">isUnallocatedFunctionInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#aa4b7a64fbcdebe1bf6c4ad0bda073df4">llvm::CodeViewContext::recordInlinedCallSiteId</a>.</p>

</div>
</div>

### Section {#a5a57622bc8d3165baf9cae9606a20c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::MCCVFunctionInfo::Section = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The section of the first .cv_loc directive used for this function, or null if none has been seen yet.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a79e4fddfcfc0d5ed30a1b811fcd17a6e">llvm::MCStreamer::checkCVLocSection</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeview-h">MCCodeView.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
