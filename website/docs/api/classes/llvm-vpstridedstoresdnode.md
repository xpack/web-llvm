---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpstridedstoresdnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VPStridedStoreSDNode` Class

<p>This class is used to represent an EXPERIMENTAL_VP_STRIDED_STORE node. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPStridedStoreSDNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode">VPBaseLoadStoreSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This base class is used to represent VP_LOAD, VP_STORE, EXPERIMENTAL_VP_STRIDED_LOAD and EXPERIMENTAL_VP_STRIDED_STORE nodes. <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61e2e3de34d6d12b3f1c2d916d21d281">VPStridedStoreSDNode</a> (unsigned Order, const DebugLoc &amp;DL, SDVTList VTs, ISD::MemIndexedMode AM, bool IsTrunc, bool IsCompressing, EVT MemVT, MachineMemOperand *MMO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a460088a793f44c318224e6353f104e66">isTruncatingStore</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a truncating store. <a href="#a460088a793f44c318224e6353f104e66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adabdec5aa2dd92fc3bab62458dcb1b6d">isCompressingStore</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the op does a compression to the vector before storing. <a href="#adabdec5aa2dd92fc3bab62458dcb1b6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4391df42f8991101a5dce3ad295db4b1">getValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35124a6a1a9c430f877c0e16f747f042">getBasePtr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac587acbf76235ccaa2eecfdd254fedb8">getOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9aa523d72f8981dd688d59ba3d97b15">getStride</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c797c8bdf07aac08877287398229f32">getMask</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca5e63b5826019a0e1719ed4e67bd7b7">getVectorLength</a> () const</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad177f1b08449694744aefd1f1afcd081">classof</a> (const SDNode *N)</td>
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

<p>This class is used to represent an EXPERIMENTAL_VP_STRIDED_STORE node.</p>

<p>Definition at line 2695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<div class="doxySectionDef">

## Friends

### SelectionDAG {#a6398ba1604e154e21413ce15dd4a180e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 2697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>


<p>Referenced by <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VPStridedStoreSDNode() {#a61e2e3de34d6d12b3f1c2d916d21d281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPStridedStoreSDNode::VPStridedStoreSDNode (unsigned Order, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/sdvtlist">SDVTList</a> VTs, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31">ISD::MemIndexedMode</a> AM, bool IsTrunc, bool IsCompressing, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> MemVT, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO)</td>
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



<p>Definition at line 2699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#a22cf4b7941bcfec9f5f5fe04d55627df">llvm::MemSDNode::MMO</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a70ebb56a2ad697ea3d91bdddf419af1a">llvm::SDNode::StoreSDNodeBits</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#a7cdac375772f7b4e63f30cb6fd02a4c6">llvm::VPBaseLoadStoreSDNode::VPBaseLoadStoreSDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBasePtr() {#a35124a6a1a9c430f877c0e16f747f042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDValue &amp; llvm::VPStridedStoreSDNode::getBasePtr ()</td>
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



<p>Definition at line 2720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>.</p>

</div>
</div>

### getMask() {#a3c797c8bdf07aac08877287398229f32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDValue &amp; llvm::VPStridedStoreSDNode::getMask ()</td>
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



<p>Definition at line 2723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>.</p>

</div>
</div>

### getOffset() {#ac587acbf76235ccaa2eecfdd254fedb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDValue &amp; llvm::VPStridedStoreSDNode::getOffset ()</td>
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



<p>Definition at line 2721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>.</p>

</div>
</div>

### getStride() {#ad9aa523d72f8981dd688d59ba3d97b15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDValue &amp; llvm::VPStridedStoreSDNode::getStride ()</td>
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



<p>Definition at line 2722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>.</p>

</div>
</div>

### getValue() {#a4391df42f8991101a5dce3ad295db4b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDValue &amp; llvm::VPStridedStoreSDNode::getValue ()</td>
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



<p>Definition at line 2719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>.</p>

</div>
</div>

### getVectorLength() {#aca5e63b5826019a0e1719ed4e67bd7b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDValue &amp; llvm::VPStridedStoreSDNode::getVectorLength ()</td>
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



<p>Definition at line 2724 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>.</p>

</div>
</div>

### isCompressingStore() {#adabdec5aa2dd92fc3bab62458dcb1b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPStridedStoreSDNode::isCompressingStore ()</td>
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

<p>Returns true if the op does a compression to the vector before storing.</p>


<p>The node contiguously stores the active elements (integers or floats) in src (those with their respective bit set in writemask k) to unaligned memory at base_addr.</p>


<p>Definition at line 2717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a70ebb56a2ad697ea3d91bdddf419af1a">llvm::SDNode::StoreSDNodeBits</a>.</p>

</div>
</div>

### isTruncatingStore() {#a460088a793f44c318224e6353f104e66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPStridedStoreSDNode::isTruncatingStore ()</td>
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

<p>Return true if this is a truncating store.</p>


<p>For integers this is the same as doing a TRUNCATE and storing the result. For floats, it is the same as doing an FP_ROUND and storing the result.</p>


<p>Definition at line 2711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a70ebb56a2ad697ea3d91bdddf419af1a">llvm::SDNode::StoreSDNodeBits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ad177f1b08449694744aefd1f1afcd081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPStridedStoreSDNode::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
