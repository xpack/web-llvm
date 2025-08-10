---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sdvtlist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SDVTList` Struct

<p>This represents a list of <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a>'s that has been intern'd by a <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::SDVTList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c22e4e105ab2aeee1ff4605e3a024a0">VTs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9acb0dfa28d030504ff28965e13cabc2">NumVTs</a></td>
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

<p>This represents a list of <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a>'s that has been intern'd by a <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a>.</p>


<p>Instances of this simple value class are returned by SelectionDAG::getVTList(...).</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### NumVTs {#a9acb0dfa28d030504ff28965e13cabc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::SDVTList::NumVTs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a74d7d9a331f1d1e05a16d9ae96e3f602">llvm::SelectionDAG::doesNodeExist</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a58bbff4d7e32f5dd0824bc62f221d7a6">FixupMMXIntrinsicTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8b513ea04feca0cb2a87cfc8f543396c">llvm::SelectionDAG::getMachineNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6fc57a7458164a2086dfee32a82530db">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae98be0c256c0d9f17ef7c7b53277d431">llvm::SelectionDAG::getNodeIfExists</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a29001ef492da795acb5f884dc9207ffa">llvm::HexagonTargetLowering::LowerUAddSubO</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5877bd47049087f890aed4f0f501ec3f">llvm::SelectionDAG::MorphNodeTo</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#af64f53af99d4ee7bbf57ea0aab719254">llvm::SDNode::SDNode</a>.</p>

</div>
</div>

### VTs {#a1c22e4e105ab2aeee1ff4605e3a024a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EVT* llvm::SDVTList::VTs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a489887586fe90dae736d77ef89c90fcd">AddNodeIDValueTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a74d7d9a331f1d1e05a16d9ae96e3f602">llvm::SelectionDAG::doesNodeExist</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a58bbff4d7e32f5dd0824bc62f221d7a6">FixupMMXIntrinsicTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8b513ea04feca0cb2a87cfc8f543396c">llvm::SelectionDAG::getMachineNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6fc57a7458164a2086dfee32a82530db">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae98be0c256c0d9f17ef7c7b53277d431">llvm::SelectionDAG::getNodeIfExists</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a29001ef492da795acb5f884dc9207ffa">llvm::HexagonTargetLowering::LowerUAddSubO</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5877bd47049087f890aed4f0f501ec3f">llvm::SelectionDAG::MorphNodeTo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
