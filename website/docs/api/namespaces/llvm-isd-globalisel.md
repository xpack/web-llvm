---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/isd/globalisel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `GlobalISel` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::ISD::GlobalISel { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a3dad35a0bab070e18a51b13b6479a5">getSetCCInverse</a> (CondCode Operation, bool isIntegerLike)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operation corresponding to !(X op Y), where 'op' is a valid SetCC operation. <a href="#a2a3dad35a0bab070e18a51b13b6479a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### getSetCCInverse() {#a2a3dad35a0bab070e18a51b13b6479a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::CondCode llvm::ISD::GlobalISel::getSetCCInverse (<a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a> Op, bool isIntegerLike)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the operation corresponding to !(X op Y), where 'op' is a valid SetCC operation.</p>


<p>The U bit of the condition code has different meanings between floating point and integer comparisons and <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>'s don't provide this distinction. As such we need to be told whether the comparison is floating point or integer-like. Pointers should use integer-like comparisons.</p>


<p>Declaration at line 1699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a75e7fd2ec2deeecb496f0ed8fb6fe462">getSetCCInverseImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
