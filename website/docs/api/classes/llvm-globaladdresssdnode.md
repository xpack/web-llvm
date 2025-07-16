---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/globaladdresssdnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GlobalAddressSDNode` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::GlobalAddressSDNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents one node in the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a>. <a href="/web-llvm/docs/api/classes/llvm/sdnode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abee6174bd5baa733eeeaa269ca4e5f5a">GlobalAddressSDNode</a> (unsigned Opc, unsigned Order, const DebugLoc &amp;DL, const GlobalValue *GA, SDVTList VTs, int64_t o, unsigned TF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac749351927cd1732994a39d40fdd4f2">getGlobal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a0dd6ccd1cfe2a3d171685b02adab2">getOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa872c53c94e16365bccd1de26fda44a">getTargetFlags</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92c5f6f2c447c5979d74ac07b552ba1e">getAddressSpace</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1f3c065c7ff688464167c2235fa249e">TheGlobal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf5332399d291e5c4671a13c4ac41919">Offset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26797bb70336e0dfc740714acbd03afb">TargetFlags</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa61d0186a5eb8eb0bbcc5d1dd84faf5">classof</a> (const SDNode *N)</td>
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


<p>Definition at line 1876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


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


<p>Definition at line 1877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#af64f53af99d4ee7bbf57ea0aab719254">llvm::SDNode::SDNode</a> and <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>


<p>Referenced by <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### GlobalAddressSDNode() {#abee6174bd5baa733eeeaa269ca4e5f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalAddressSDNode::GlobalAddressSDNode (unsigned Opc, unsigned Order, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GA, <a href="/web-llvm/docs/api/structs/llvm/sdvtlist">SDVTList</a> VTs, int64_t o, unsigned TF)</td>
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



<p>Definition at line 1883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddressSpace() {#a92c5f6f2c447c5979d74ac07b552ba1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GlobalAddressSDNode::getAddressSpace ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13073 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a>, <a href="#aac749351927cd1732994a39d40fdd4f2">getGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a913a5d4b2cddde762446bd494e81a3f2">llvm::GlobalValue::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a0009b65fffe67f99ae742be1f7aaa6fa">llvm::SITargetLowering::isOffsetFoldingLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a8deafd57e22779c013b2225fa89866ce">IsWebAssemblyGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a2073b6225d4939c017d83fc7e725f166">llvm::NVPTXTargetLowering::LowerGlobalAddress</a>.</p>

</div>
</div>

### getGlobal() {#aac749351927cd1732994a39d40fdd4f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalValue * llvm::GlobalAddressSDNode::getGlobal ()</td>
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



<p>Definition at line 1890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#abd574741643b21b2db236255e18656db">AddNodeIDCustom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a2fc82b70727afff2c18b36c0a6c280cd">combineADDToMAT_PCREL_ADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a2a73ac8be22cfe2a7d10fd13e70d57e1">foldADDIForFasterLocalAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aec15e9006d3d3507d186d2f98525aecc">llvm::SelectionDAG::FoldSymbolOffset</a>, <a href="#a92c5f6f2c447c5979d74ac07b552ba1e">getAddressSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a5d70066b330f0860014d91d4974e56b0">getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a33c0ea764b5da70fb2f5263babf1e5ae">llvm::HexagonTargetLowering::GetDynamicTLSAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a145b3f6dbbafb7b1e7644c3c90fdaf3f">GetTLSADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a29ca9a2c296f3f458f12419d0fad2cc5">hasTocDataAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a23bdd93cc79ae6095f38f4bc4f7eec80">isEligibleToFoldADDIForFasterLocalAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a0009b65fffe67f99ae742be1f7aaa6fa">llvm::SITargetLowering::isOffsetFoldingLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af8cc1f957026a793e58fec505e47a7c5">llvm::X86TargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a2073b6225d4939c017d83fc7e725f166">llvm::NVPTXTargetLowering::LowerGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a36d79249249c0e44fe3450f4894fd732">llvm::HexagonTargetLowering::LowerGlobalTLSAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ab44a5ddbc927f9b63731bf050dee8048">llvm::SparcTargetLowering::LowerGlobalTLSAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7092b8371f80f3acf826e7bfc1e00d92">LowerToTLSExecModel</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a57d212a16cfd2e14e8b03f0b460010ef">llvm::HexagonTargetLowering::LowerToTLSGeneralDynamicModel</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a521a7e7403f755b2fc9fccd869eb4ed8">llvm::HexagonTargetLowering::LowerToTLSInitialExecModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afa38de8a6bc68bdfd3aea0e8900c7745">LowerToTLSLocalDynamicModel</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a69373902f35e4248d6e453e27daa4e80">llvm::HexagonTargetLowering::LowerToTLSLocalExecModel</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a40c243011cdda005e97448378d575096">performGlobalAddressCombine</a>.</p>

</div>
</div>

### getOffset() {#a28a0dd6ccd1cfe2a3d171685b02adab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::GlobalAddressSDNode::getOffset ()</td>
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



<p>Definition at line 1891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#abd574741643b21b2db236255e18656db">AddNodeIDCustom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a2fc82b70727afff2c18b36c0a6c280cd">combineADDToMAT_PCREL_ADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aec15e9006d3d3507d186d2f98525aecc">llvm::SelectionDAG::FoldSymbolOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a33c0ea764b5da70fb2f5263babf1e5ae">llvm::HexagonTargetLowering::GetDynamicTLSAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a145b3f6dbbafb7b1e7644c3c90fdaf3f">GetTLSADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7092b8371f80f3acf826e7bfc1e00d92">LowerToTLSExecModel</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a57d212a16cfd2e14e8b03f0b460010ef">llvm::HexagonTargetLowering::LowerToTLSGeneralDynamicModel</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a521a7e7403f755b2fc9fccd869eb4ed8">llvm::HexagonTargetLowering::LowerToTLSInitialExecModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afa38de8a6bc68bdfd3aea0e8900c7745">LowerToTLSLocalDynamicModel</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a69373902f35e4248d6e453e27daa4e80">llvm::HexagonTargetLowering::LowerToTLSLocalExecModel</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a40c243011cdda005e97448378d575096">performGlobalAddressCombine</a>.</p>

</div>
</div>

### getTargetFlags() {#aaa872c53c94e16365bccd1de26fda44a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalAddressSDNode::getTargetFlags ()</td>
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



<p>Definition at line 1892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#abd574741643b21b2db236255e18656db">AddNodeIDCustom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a2fc82b70727afff2c18b36c0a6c280cd">combineADDToMAT_PCREL_ADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a2a73ac8be22cfe2a7d10fd13e70d57e1">foldADDIForFasterLocalAccesses</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a23bdd93cc79ae6095f38f4bc4f7eec80">isEligibleToFoldADDIForFasterLocalAccesses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Offset {#acf5332399d291e5c4671a13c4ac41919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::GlobalAddressSDNode::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### TargetFlags {#a26797bb70336e0dfc740714acbd03afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalAddressSDNode::TargetFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### TheGlobal {#ae1f3c065c7ff688464167c2235fa249e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalValue* llvm::GlobalAddressSDNode::TheGlobal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aaa61d0186a5eb8eb0bbcc5d1dd84faf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalAddressSDNode::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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



<p>Definition at line 1896 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#af64f53af99d4ee7bbf57ea0aab719254">llvm::SDNode::SDNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a87b8176af163ee944af127081d24f4a2">llvm::ISD::TargetGlobalAddress</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc9ad7857b7faf49dcde3dcf434e22a6">llvm::ISD::TargetGlobalTLSAddress</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
