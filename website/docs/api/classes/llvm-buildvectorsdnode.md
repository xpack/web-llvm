---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/buildvectorsdnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BuildVectorSDNode` Class

<p>A "pseudo-class" with methods for operating on BUILD_VECTORs. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BuildVectorSDNode { ... }
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c507b53ca61e5aad87f3d0733c91597">BuildVectorSDNode</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f89a07c015a54253416b726e352bdc4">isConstantSplat</a> (APInt &amp;SplatValue, APInt &amp;SplatUndef, unsigned &amp;SplatBitSize, bool &amp;HasAnyUndefs, unsigned MinSplatBits=0, bool isBigEndian=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a constant splat, and if so, find the smallest element size that splats the vector. <a href="#a6f89a07c015a54253416b726e352bdc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66b06a3a00ea8358c447658d398dc3f8">getSplatValue</a> (const APInt &amp;DemandedElts, BitVector *UndefElements=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the demanded splatted value or a null value if this is not a splat. <a href="#a66b06a3a00ea8358c447658d398dc3f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d322fa0d9ca562c6b20cac2d8a0a5dd">getSplatValue</a> (BitVector *UndefElements=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the splatted value or a null value if this is not a splat. <a href="#a1d322fa0d9ca562c6b20cac2d8a0a5dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28caa20d9fc8a395fd4253ccbfe7eb48">getRepeatedSequence</a> (const APInt &amp;DemandedElts, SmallVectorImpl&lt; SDValue &gt; &amp;Sequence, BitVector *UndefElements=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the shortest repeating sequence of values in the build vector. <a href="#a28caa20d9fc8a395fd4253ccbfe7eb48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf005731b7353e3224b7742a356ffb0e">getRepeatedSequence</a> (SmallVectorImpl&lt; SDValue &gt; &amp;Sequence, BitVector *UndefElements=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the shortest repeating sequence of values in the build vector. <a href="#acf005731b7353e3224b7742a356ffb0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a594eb8072e3372e2e9935ecc21fda">getConstantSplatNode</a> (const APInt &amp;DemandedElts, BitVector *UndefElements=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the demanded splatted constant or null if this is not a constant splat. <a href="#a72a594eb8072e3372e2e9935ecc21fda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e3de162f893dc03aef8a7153db605e8">getConstantSplatNode</a> (BitVector *UndefElements=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the splatted constant or null if this is not a constant splat. <a href="#a8e3de162f893dc03aef8a7153db605e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode">ConstantFPSDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b516cc3ba5f6ea48908ffc00cb3bf2">getConstantFPSplatNode</a> (const APInt &amp;DemandedElts, BitVector *UndefElements=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the demanded splatted constant FP or null if this is not a constant FP splat. <a href="#a31b516cc3ba5f6ea48908ffc00cb3bf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode">ConstantFPSDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ed4a0fdad49b05a29efff914a99abea">getConstantFPSplatNode</a> (BitVector *UndefElements=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the splatted constant FP or null if this is not a constant FP splat. <a href="#a1ed4a0fdad49b05a29efff914a99abea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5d7b750612b9a523ddd10c10c1faa4d">getConstantFPSplatPow2ToLog2Int</a> (BitVector *UndefElements, uint32_t BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a constant FP splat and the splatted constant FP is an exact power or 2, return the log base 2 integer value. <a href="#aa5d7b750612b9a523ddd10c10c1faa4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1713768600a9f5a62eb74a616aa73428">getConstantRawBits</a> (bool IsLittleEndian, unsigned DstEltSizeInBits, SmallVectorImpl&lt; APInt &gt; &amp;RawBitElements, BitVector &amp;UndefElements) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the raw bit data from a build vector of Undef, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> or <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> node elements. <a href="#a1713768600a9f5a62eb74a616aa73428">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7448e12bb2449435bddec7d9e00564a">isConstant</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ef62399dd4b7e5dbc8398704aaa79bc">isConstantSequence</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this BuildVector is constant and represents the numerical series "&lt;a, a+n, a+2n, a+3n, ...&gt;" where a is integer and n is a non-zero integer, the value "&lt;a,n&gt;" is returned. <a href="#a3ef62399dd4b7e5dbc8398704aaa79bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2387207e96faf525ff211b5d101f0918">recastRawBits</a> (bool IsLittleEndian, unsigned DstEltSizeInBits, SmallVectorImpl&lt; APInt &gt; &amp;DstBitElements, ArrayRef&lt; APInt &gt; SrcBitElements, BitVector &amp;DstUndefElements, const BitVector &amp;SrcUndefElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recast bit data <span class="doxyComputerOutput">SrcBitElements</span> to <span class="doxyComputerOutput">DstEltSizeInBits</span> wide elements. <a href="#a2387207e96faf525ff211b5d101f0918">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad44d0f0f1fddc11c4cf8b7566fdd33fd">classof</a> (const SDNode *N)</td>
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

<p>A "pseudo-class" with methods for operating on BUILD_VECTORs.</p>

<p>Definition at line 2107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BuildVectorSDNode() {#a0c507b53ca61e5aad87f3d0733c91597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BuildVectorSDNode::BuildVectorSDNode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#aad6842fbf58844d974611a4915a00aae">isBigEndian</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getConstantFPSplatNode() {#a31b516cc3ba5f6ea48908ffc00cb3bf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPSDNode * BuildVectorSDNode::getConstantFPSplatNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> * UndefElements=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the demanded splatted constant FP or null if this is not a constant FP splat.</p>


<p>The DemandedElts mask indicates the elements that must be in the splat. If passed a non-null UndefElements bitvector, it will resize it to match the vector width and set the bits where elements are undef.</p>


<p>Declaration at line 2193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13264 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a66b06a3a00ea8358c447658d398dc3f8">getSplatValue</a>.</p>

</div>
</div>

### getConstantFPSplatNode() {#a1ed4a0fdad49b05a29efff914a99abea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPSDNode * BuildVectorSDNode::getConstantFPSplatNode (<a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> * UndefElements=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the splatted constant FP or null if this is not a constant FP splat.</p>


<p>If passed a non-null UndefElements bitvector, it will resize it to match the vector width and set the bits where elements are undef.</p>


<p>Declaration at line 2202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13271 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a66b06a3a00ea8358c447658d398dc3f8">getSplatValue</a>.</p>

</div>
</div>

### getConstantFPSplatPow2ToLog2Int() {#aa5d7b750612b9a523ddd10c10c1faa4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t BuildVectorSDNode::getConstantFPSplatPow2ToLog2Int (<a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> * UndefElements, uint32_t BitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a constant FP splat and the splatted constant FP is an exact power or 2, return the log base 2 integer value.</p>


<p>Otherwise, return -1.</p>


<p>The BitWidth specifies the necessary bit precision.</p>


<p>Declaration at line 2209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13276 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aae1f09de4bf1aab27149a7d328715e30">llvm::APFloat::convertToInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a66b06a3a00ea8358c447658d398dc3f8">getSplatValue</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aa8092c6b52c0412d8198a63bc995761e9">llvm::APFloatBase::opOK</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a482d9cf95b588eb05cefeaa5c05be9a3">llvm::APFloatBase::rmTowardZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa7054eb07a4962c7516115555800c017">performFpToIntCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a179a8cd2adc83f28bc70fed3ee8fde0b">PerformVCVTCombine</a>.</p>

</div>
</div>

### getConstantRawBits() {#a1713768600a9f5a62eb74a616aa73428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BuildVectorSDNode::getConstantRawBits (bool IsLittleEndian, unsigned DstEltSizeInBits, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; &amp; RawBitElements, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; UndefElements)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the raw bit data from a build vector of Undef, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> or <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> node elements.</p>


<p>Each raw bit element will be <span class="doxyComputerOutput">DstEltSizeInBits</span> wide, undef elements are treated as zero, and entirely undefined elements are flagged in <span class="doxyComputerOutput">UndefElements</span>.</p>


<p>Declaration at line 2216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13293 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f311fcc2415eee3cb3694013b985304">llvm::SDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac0a534d63ac5c5b87f36acdade953fbe">llvm::SDNode::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ab7448e12bb2449435bddec7d9e00564a">isConstant</a>, <a href="#a2387207e96faf525ff211b5d101f0918">recastRawBits</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>.</p>

</div>
</div>

### getConstantSplatNode() {#a72a594eb8072e3372e2e9935ecc21fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantSDNode * BuildVectorSDNode::getConstantSplatNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> * UndefElements=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the demanded splatted constant or null if this is not a constant splat.</p>


<p>The DemandedElts mask indicates the elements that must be in the splat. If passed a non-null UndefElements bitvector, it will resize it to match the vector width and set the bits where elements are undef.</p>


<p>Declaration at line 2175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a66b06a3a00ea8358c447658d398dc3f8">getSplatValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a250b1e0899d6d01c60cb7af31cd2a2fd">combineGatherScatter</a>.</p>

</div>
</div>

### getConstantSplatNode() {#a8e3de162f893dc03aef8a7153db605e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantSDNode * BuildVectorSDNode::getConstantSplatNode (<a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> * UndefElements=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the splatted constant or null if this is not a constant splat.</p>


<p>If passed a non-null UndefElements bitvector, it will resize it to match the vector width and set the bits where elements are undef.</p>


<p>Declaration at line 2184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13259 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a66b06a3a00ea8358c447658d398dc3f8">getSplatValue</a>.</p>

</div>
</div>

### getRepeatedSequence() {#a28caa20d9fc8a395fd4253ccbfe7eb48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BuildVectorSDNode::getRepeatedSequence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Sequence, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> * UndefElements=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the shortest repeating sequence of values in the build vector.</p>


<p>e.g. { u, X, u, X, u, u, X, u } -&gt; { X } { X, Y, u, Y, u, u, X, u } -&gt; { X, Y }</p>


<p>Currently this must be a power-of-2 build vector. The DemandedElts mask indicates the elements that must be present, undemanded elements in Sequence may be null (SDValue()). If passed a non-null UndefElements bitvector, it will resize it to match the original vector width and set the bits where elements are undef. If result is false, Sequence will be empty.</p>


<p>Declaration at line 2152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13199 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a35bbc237e4a675c5332103ac6e7dcce1">llvm::BitVector::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f311fcc2415eee3cb3694013b985304">llvm::SDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ad29680b0f3d0427cab5a32e727f9f11a">llvm::SDNode::isUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a1c861a21f795c3108ab690f3a45c881a">llvm::SDValue::isUndef</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a32859a24aa7a3be269855b989d92a4b4">llvm::BitVector::resize</a>.</p>


<p>Referenced by <a href="#acf005731b7353e3224b7742a356ffb0e">getRepeatedSequence</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aae9ffc1cff57df706ebe6dcd34c56723">lowerBuildVectorAsBroadcast</a>.</p>

</div>
</div>

### getRepeatedSequence() {#acf005731b7353e3224b7742a356ffb0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BuildVectorSDNode::getRepeatedSequence (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Sequence, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> * UndefElements=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the shortest repeating sequence of values in the build vector.</p>


<p>e.g. { u, X, u, X, u, u, X, u } -&gt; { X } { X, Y, u, Y, u, u, X, u } -&gt; { X, Y }</p>


<p>Currently this must be a power-of-2 build vector. If passed a non-null UndefElements bitvector, it will resize it to match the original vector width and set the bits where elements are undef. If result is false, Sequence will be empty.</p>


<p>Declaration at line 2165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13245 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f311fcc2415eee3cb3694013b985304">llvm::SDNode::getNumOperands</a> and <a href="#a28caa20d9fc8a395fd4253ccbfe7eb48">getRepeatedSequence</a>.</p>

</div>
</div>

### getSplatValue() {#a66b06a3a00ea8358c447658d398dc3f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BuildVectorSDNode::getSplatValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> * UndefElements=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the demanded splatted value or a null value if this is not a splat.</p>


<p>The DemandedElts mask indicates the elements that must be in the splat. If passed a non-null UndefElements bitvector, it will resize it to match the vector width and set the bits where elements are undef.</p>


<p>Declaration at line 2132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a35bbc237e4a675c5332103ac6e7dcce1">llvm::BitVector::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f311fcc2415eee3cb3694013b985304">llvm::SDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ad29680b0f3d0427cab5a32e727f9f11a">llvm::SDNode::isUndef</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a32859a24aa7a3be269855b989d92a4b4">llvm::BitVector::resize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a71a49469d7d437afe471a050139f094f">createMMXBuildVector</a>, <a href="#a1ed4a0fdad49b05a29efff914a99abea">getConstantFPSplatNode</a>, <a href="#a31b516cc3ba5f6ea48908ffc00cb3bf2">getConstantFPSplatNode</a>, <a href="#aa5d7b750612b9a523ddd10c10c1faa4d">getConstantFPSplatPow2ToLog2Int</a>, <a href="#a8e3de162f893dc03aef8a7153db605e8">getConstantSplatNode</a>, <a href="#a72a594eb8072e3372e2e9935ecc21fda">getConstantSplatNode</a>, <a href="#a1d322fa0d9ca562c6b20cac2d8a0a5dd">getSplatValue</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a>.</p>

</div>
</div>

### getSplatValue() {#a1d322fa0d9ca562c6b20cac2d8a0a5dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BuildVectorSDNode::getSplatValue (<a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> * UndefElements=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the splatted value or a null value if this is not a splat.</p>


<p>If passed a non-null UndefElements bitvector, it will resize it to match the vector width and set the bits where elements are undef.</p>


<p>Declaration at line 2139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13194 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f311fcc2415eee3cb3694013b985304">llvm::SDNode::getNumOperands</a> and <a href="#a66b06a3a00ea8358c447658d398dc3f8">getSplatValue</a>.</p>

</div>
</div>

### isConstant() {#ab7448e12bb2449435bddec7d9e00564a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BuildVectorSDNode::isConstant ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13383 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aac2f0a84dd2aa5ee4c3f1385e9565f5e">llvm::ISD::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1be4c8da7c68a4c683de1a98b5cc5b9d">llvm::ISD::ConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a2bb043b87aa8cdef6d1e9e14329aec6a">llvm::SDNode::op_values</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c6d8f265e9e16e5debdb9a536b55d3d">llvm::ISD::UNDEF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a250b1e0899d6d01c60cb7af31cd2a2fd">combineGatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54b7a43507d8f339f806b8d1c9f12f29">combineVectorCompareAndMaskUnaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab60e9136a31f4054b79740f601cba282">detectExtMul</a>, <a href="#a1713768600a9f5a62eb74a616aa73428">getConstantRawBits</a> and <a href="/web-llvm/docs/api/structs/llvm/systemzvectorconstantinfo/#aa073d1e5ff2c5e5a53876841e1ff6fad">llvm::SystemZVectorConstantInfo::SystemZVectorConstantInfo</a>.</p>

</div>
</div>

### isConstantSequence() {#a3ef62399dd4b7e5dbc8398704aaa79bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; APInt, APInt &gt; &gt; BuildVectorSDNode::isConstantSequence ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this BuildVector is constant and represents the numerical series "&lt;a, a+n, a+2n, a+3n, ...&gt;" where a is integer and n is a non-zero integer, the value "&lt;a,n&gt;" is returned.</p>

<p>Declaration at line 2225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13393 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a9dfad184e37d97a10814cdce3d46c072">llvm::SDNode::getConstantOperandAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f311fcc2415eee3cb3694013b985304">llvm::SDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac0a534d63ac5c5b87f36acdade953fbe">llvm::SDNode::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a>.</p>

</div>
</div>

### isConstantSplat() {#a6f89a07c015a54253416b726e352bdc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BuildVectorSDNode::isConstantSplat (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; SplatValue, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; SplatUndef, unsigned &amp; SplatBitSize, bool &amp; HasAnyUndefs, unsigned MinSplatBits=0, bool isBigEndian=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a constant splat, and if so, find the smallest element size that splats the vector.</p>


<p>If MinSplatBits is nonzero, the element size must be at least that large. Note that the splat element may be the entire vector (i.e., a one element vector). Returns the splat element value in SplatValue. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> undefined bits in that value are zero, and the corresponding bits in the SplatUndef mask are set. The SplatBitSize value is set to the splat element size in bits. HasAnyUndefs is set to true if any bits in the vector are undefined. isBigEndian describes the endianness of the target.</p>


<p>Declaration at line 2121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13083 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adf997f1047734d3b47b8d5a9b2163f11">llvm::APInt::extractBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f311fcc2415eee3cb3694013b985304">llvm::SDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac0a534d63ac5c5b87f36acdade953fbe">llvm::SDNode::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aabe301a4f18d38478700ad44ba2245bc">llvm::APInt::insertBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a1c861a21f795c3108ab690f3a45c881a">llvm::SDValue::isUndef</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#acb95d5d8e87df053e1b53e2ec60de4b6">llvm::APInt::setBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a01bdf0d462d6df94d15c1763169f4cf1">EmitVectorComparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8488e7918427cbc59c4216e0249bc8ee">getVShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8488e7918427cbc59c4216e0249bc8ee">getVShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchiseldagtodag-cpp/#ad42177120fd9d2f2693b604658449116">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a6027bd69e80c1591deaf7dff0257fc5d">isVectorAllOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aae9ffc1cff57df706ebe6dcd34c56723">lowerBuildVectorAsBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aec3ab4d2802494bdb8b2c3c5343f8254">PerformANDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a1cb3d0ba0717491c0c28dcc2e4b3d152">performDSPShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab81a857a51f1d25a352fc51569f079a0">PerformORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5f4f153e2f8d9dd1c45d089ea3c7499f">resolveBuildVector</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzvectorconstantinfo/#aa073d1e5ff2c5e5a53876841e1ff6fad">llvm::SystemZVectorConstantInfo::SystemZVectorConstantInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aad0fb69928bec544ec83f90f26393521">tryCombineShiftImm</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ad44d0f0f1fddc11c4cf8b7566fdd33fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BuildVectorSDNode::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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



<p>Definition at line 2236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#af64f53af99d4ee7bbf57ea0aab719254">llvm::SDNode::SDNode</a>.</p>

</div>
</div>

### recastRawBits() {#a2387207e96faf525ff211b5d101f0918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BuildVectorSDNode::recastRawBits (bool IsLittleEndian, unsigned DstEltSizeInBits, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; &amp; DstBitElements, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; SrcBitElements, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; DstUndefElements, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; SrcUndefElements)</td>
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

<p>Recast bit data <span class="doxyComputerOutput">SrcBitElements</span> to <span class="doxyComputerOutput">DstEltSizeInBits</span> wide elements.</p>


<p>Undef elements are treated as zero, and entirely undefined elements are flagged in <span class="doxyComputerOutput">DstUndefElements</span>.</p>


<p>Declaration at line 2230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 13329 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::SmallVectorImpl&lt; T &gt;::assign</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a35bbc237e4a675c5332103ac6e7dcce1">llvm::BitVector::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adf997f1047734d3b47b8d5a9b2163f11">llvm::APInt::extractBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aabe301a4f18d38478700ad44ba2245bc">llvm::APInt::insertBits</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a168122d6ac4ed2a8b722e01b592ad289">llvm::BitVector::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a32859a24aa7a3be269855b989d92a4b4">llvm::BitVector::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#abf86e1383aec181a5a2d9967eb8070fd">llvm::BitVector::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a> and <a href="#a1713768600a9f5a62eb74a616aa73428">getConstantRawBits</a>.</p>

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
