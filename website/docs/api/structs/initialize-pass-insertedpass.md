---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/initialize-pass/insertedpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `InsertedPass` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct INITIALIZE_PASS::InsertedPass { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2483522c3d3f70921560d0e78a1e340">InsertedPass</a> (AnalysisID TargetPassID, IdentifyingPassPtr InsertedPassID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6ddb800bea767194940505993f2e4b1">getInsertedPass</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2732374039817667021193416c0dd3ae">TargetPassID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/identifyingpassptr">IdentifyingPassPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a438881bc32893e78ef653e0560715af5">InsertedPassID</a></td>
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


<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InsertedPass() {#af2483522c3d3f70921560d0e78a1e340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS::InsertedPass::InsertedPass (<a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> TargetPassID, <a href="/web-llvm/docs/api/classes/llvm/identifyingpassptr">IdentifyingPassPtr</a> InsertedPassID)</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>References <a href="#a438881bc32893e78ef653e0560715af5">InsertedPassID</a> and <a href="#a2732374039817667021193416c0dd3ae">TargetPassID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInsertedPass() {#aa6ddb800bea767194940505993f2e4b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * INITIALIZE_PASS::InsertedPass::getInsertedPass ()</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a2ed7d79d79dffe7368c3d3cdf40dd80e">llvm::Pass::createPass</a> and <a href="#a438881bc32893e78ef653e0560715af5">InsertedPassID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### InsertedPassID {#a438881bc32893e78ef653e0560715af5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IdentifyingPassPtr INITIALIZE_PASS::InsertedPass::InsertedPassID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#aa6ddb800bea767194940505993f2e4b1">getInsertedPass</a> and <a href="#af2483522c3d3f70921560d0e78a1e340">InsertedPass</a>.</p>

</div>
</div>

### TargetPassID {#a2732374039817667021193416c0dd3ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisID INITIALIZE_PASS::InsertedPass::TargetPassID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<p>Referenced by <a href="#af2483522c3d3f70921560d0e78a1e340">InsertedPass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
