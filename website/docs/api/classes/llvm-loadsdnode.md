---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loadsdnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoadSDNode` Class Reference

<p>This class is used to represent <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">ISD::LOAD</a> nodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoadSDNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode">LSBaseSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for <a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> and <a href="/web-llvm/docs/api/classes/llvm/storesdnode">StoreSDNode</a>. <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode/#details">More...</a></p>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23683a61afd4ccabd55a0d2c95d50876">LoadSDNode</a> (unsigned Order, const DebugLoc &amp;dl, SDVTList VTs, ISD::MemIndexedMode AM, ISD::LoadExtType ETy, EVT MemVT, MachineMemOperand *MMO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7">ISD::LoadExtType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad85ec82447c2f1824538de9b449ffed0">getExtensionType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether this is a plain node, or one of the varieties of value-extending loads. <a href="#ad85ec82447c2f1824538de9b449ffed0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20fd5ba47db6a4cc8ad9d197fc1bbbee">getBasePtr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71689ed396153740b31ac1a182364651">getOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae15fae32303e714d9009b970bf02a46d">classof</a> (const SDNode *N)</td>
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

<p>This class is used to represent <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">ISD::LOAD</a> nodes.</p>

<p>Definition at line 2464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


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


<p>Definition at line 2465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a305e5de87d3873ae5ae1b8de12b631f7">llvm::SDNode::LoadSDNodeBits</a>, <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode/#a083785be56ad0ab8dbf81e50a6a761ac">llvm::LSBaseSDNode::LSBaseSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#a22cf4b7941bcfec9f5f5fe04d55627df">llvm::MemSDNode::MMO</a> and <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>


<p>Referenced by <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LoadSDNode() {#a23683a61afd4ccabd55a0d2c95d50876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoadSDNode::LoadSDNode (unsigned Order, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; dl, <a href="/web-llvm/docs/api/structs/llvm/sdvtlist">SDVTList</a> VTs, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31">ISD::MemIndexedMode</a> AM, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7">ISD::LoadExtType</a> ETy, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> MemVT, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO)</td>
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



<p>Definition at line 2467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBasePtr() {#a20fd5ba47db6a4cc8ad9d197fc1bbbee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDValue &amp; llvm::LoadSDNode::getBasePtr ()</td>
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



<p>Definition at line 2483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af8092b588e16c93a54d21da99af4814c">combineBVOfConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4d6ae8095a6353874359d5f5e886410c">combineMOVDQ2Q</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae9857fae8de3da5730d5b06aca182624">getIndexFromUnindexedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a283338e41cb41bbe6a59285c019a0415">llvm::RISCVTargetLowering::getTargetConstantFromLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a50de01231a46d2b82c41aebd0c413690">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a1c9b0061be648da87d7a9102c0179018">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#af5649d870c8560e39b54f41b8f5997fd">LowerF128Load</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a665ef5a5179d9d6112b5215fe27caa83">llvm::HexagonTargetLowering::LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a47413709ef916baf36607da462d93ccc">LowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a57a0d1b6cabb33defc1c9f2d2d82a7f8">llvm::VETargetLowering::lowerLOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a225dca8b49ddf9ae69266aa8448208d0">lowerLoadF128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a5a96f3df430878c8511972852cb08499">lowerLoadI1</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a39595844bf818c3700df1bd898912dcb">llvm::HexagonTargetLowering::LowerUnalignedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#afdcf01d7d3527e56cd6cc217975aac68">llvm::AMDGPUDAGToDAGISel::matchLoadD16FromBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#addb3e984dfd51a52d5ab5050a30cd4d4">narrowLoadToVZLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0048548b4f1cc9455cf3af293d2b52bf">performCONCAT_VECTORSCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a0101ddec6987012c164530ddbdcc307c">llvm::R600TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8b803a5cecda412b4f4984ad8db7201e">performFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03b14e6aca1277bdee37639aec700ba7">performIntToFpCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a40eb7d32bd58dfbdde6c632446a56828">PerformVMOVrhCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a16e6c862a36871c4f388c826ad65b07c">llvm::SparcTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#afa371a03066103bb85f89636e86686d7">llvm::RISCVDAGToDAGISel::tryIndexedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5d176b4adbcf9fd77cae6c4d43f13fb2">tryToFoldExtOfExtload</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a07529501831cc322901e5a24586b7720">tryToFoldExtOfLoad</a>.</p>

</div>
</div>

### getExtensionType() {#ad85ec82447c2f1824538de9b449ffed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::LoadExtType llvm::LoadSDNode::getExtensionType ()</td>
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

<p>Return whether this is a plain node, or one of the varieties of value-extending loads.</p>

<p>Definition at line 2479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a305e5de87d3873ae5ae1b8de12b631f7">llvm::SDNode::LoadSDNodeBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a8101c1f13bd0c6b60080e985987c9b92">checkValueWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a257c422be962af393f15b15dbc07b962">checkValueWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af8092b588e16c93a54d21da99af4814c">combineBVOfConsecutiveLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a665ef5a5179d9d6112b5215fe27caa83">llvm::HexagonTargetLowering::LowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#afdcf01d7d3527e56cd6cc217975aac68">llvm::AMDGPUDAGToDAGISel::matchLoadD16FromBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a16e6c862a36871c4f388c826ad65b07c">llvm::SparcTargetLowering::ReplaceNodeResults</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#afa371a03066103bb85f89636e86686d7">llvm::RISCVDAGToDAGISel::tryIndexedLoad</a>.</p>

</div>
</div>

### getOffset() {#a71689ed396153740b31ac1a182364651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDValue &amp; llvm::LoadSDNode::getOffset ()</td>
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



<p>Definition at line 2484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a50de01231a46d2b82c41aebd0c413690">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a1c9b0061be648da87d7a9102c0179018">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#af5649d870c8560e39b54f41b8f5997fd">LowerF128Load</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a665ef5a5179d9d6112b5215fe27caa83">llvm::HexagonTargetLowering::LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a225dca8b49ddf9ae69266aa8448208d0">lowerLoadF128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a5a96f3df430878c8511972852cb08499">lowerLoadI1</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#afa371a03066103bb85f89636e86686d7">llvm::RISCVDAGToDAGISel::tryIndexedLoad</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ae15fae32303e714d9009b970bf02a46d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoadSDNode::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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



<p>Definition at line 2486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

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
