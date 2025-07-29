---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/nvptxdagtodagisel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `NVPTXDAGToDAGISel` Class



## Declaration

<div class="doxyDeclaration">
class llvm::NVPTXDAGToDAGISel { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">Target/NVPTX/NVPTXISelDAGToDAG.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a> - This is the common base class used for SelectionDAG-based pattern-matching instruction selectors. <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5efcf313253f5408450d3fd28d241688">NVPTXDAGToDAGISel</a> ()=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedfc9f42058f04ebd41215ac5459949d">NVPTXDAGToDAGISel</a> (NVPTXTargetMachine &amp;tm, CodeGenOptLevel OptLevel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f13fd2a351449d5d3c894ff7eae2bc">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a992873c33224fdcfbff83b24b9c01dee">SelectInlineAsmMemoryOperand</a> (const SDValue &amp;Op, InlineAsm::ConstraintCode ConstraintID, std::vector&lt; SDValue &gt; &amp;OutOps) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectInlineAsmMemoryOperand - Implement addressing mode selection for inline asm expressions. <a href="#a992873c33224fdcfbff83b24b9c01dee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a312a230dc9b6c2a3f442743baffe51">getDivF32Level</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec563e3328aef9926fa7f49784f06530">usePrecSqrtF32</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31f1efbb191fc0ec25a1b9b4b50a94c4">useF32FTZ</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5031bb0c47db3475151de0b44a6d3699">allowFMA</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69ab2757f8c1744f335d30a50a1a15d7">allowUnsafeFPMath</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60eb2ba8a08f87e410b1a07defb83765">doRsqrtOpt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb2ac9e196435e7136d351b7e9600dc">Select</a> (SDNode *N) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select - Select instructions not customized! <a href="#accb2ac9e196435e7136d351b7e9600dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6988d22ead6737eb21584585492a0999">tryIntrinsicNoChain</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a959b765446c9f3328b6592e258bbc0b7">tryIntrinsicChain</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79a71817e11f590d9c5a5fca88d9b256">tryIntrinsicVoid</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2105b3c48c5c3e75f66cfed32787627">SelectTexSurfHandle</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98eacf9aee5619492cc3020a65a317ec">tryLoad</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f04007c1595f89e1e9a84e77172290">tryLoadVector</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a406264e3b51df02920728b0ad1bc3cb1">tryLDGLDU</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ca79f171cb3c8a16bb88a5f4f4c847e">tryStore</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5f9bad73925e7883546f5070c6897ca">tryStoreVector</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af59b0036da7f617ef7609fa704ff0582">tryLoadParam</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcbd3a626d62d6ffd4577b6de92b8b49">tryStoreRetval</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adefff6addc5eb9163f132d8ecf83e561">tryStoreParam</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8daca2d259d7e535398ef20a7aac1b2">tryFence</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c266bdf75774b1480d25b97df53afec">SelectAddrSpaceCast</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73541a360588337ce025f2449e297f8b">tryBFE</a> (SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectBFE - Look for instruction sequences that can be made more efficient by using the 'bfe' (bit-field extract) PTX instruction. <a href="#a73541a360588337ce025f2449e297f8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41741cbad01426e7fa0de0cfa76d2a49">tryBF16ArithToFMA</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c5ad15e626579ab9f13010d65ad44a1">tryConstantFP</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86a4cb3a94ff11c5b4888f73fc6ccb1">SelectSETP_F16X2</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5737a3e8b050c99df7ce806841249f15">SelectSETP_BF16X2</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8015defed2fd63a6127fc7a6eab7d4a6">tryEXTRACT_VECTOR_ELEMENT</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29e45a742ea3a06aa34bd3d54834fbfe">SelectV2I64toI128</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b1d5582732934f398f87ced5158612">SelectI128toV2I64</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8cb412a9b5507afe61bf9154781ca2b">SelectCpAsyncBulkG2S</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765794ed7e43ef125b6ba2e3472072ba">SelectCpAsyncBulkS2G</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55edc7e681635fbddc9016228fb6095b">SelectCpAsyncBulkPrefetchL2</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7476107f769a3e19d3d023fbf3fee0b8">SelectCpAsyncBulkTensorG2SCommon</a> (SDNode *N, bool IsIm2Col=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a751faede98f80a1e5a198af28c178a">SelectCpAsyncBulkTensorS2GCommon</a> (SDNode *N, bool IsIm2Col=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae505c022ace235a5c5dda554410f2dd1">SelectCpAsyncBulkTensorPrefetchCommon</a> (SDNode *N, bool IsIm2Col=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeaeb64e76f8c37950fbb2589314fd88">SelectCpAsyncBulkTensorReduceCommon</a> (SDNode *N, unsigned RedOp, bool IsIm2Col=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af12338284a1c40b05536cb2a666b95ac">getI32Imm</a> (unsigned Imm, const SDLoc &amp;DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dfb786a32c83cec00b23d2bf27abd6b">SelectDirectAddr</a> (SDValue N, SDValue &amp;Address)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf783fc7407eb01adbef6546fda44d6c">SelectADDRri_imp</a> (SDNode *OpNode, SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset, MVT VT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f39a575823840ed06928f6e7ee6c75">SelectADDRri</a> (SDNode *OpNode, SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b4384bc492076227c6fdd79e36d3995">SelectADDRri64</a> (SDNode *OpNode, SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46b695cf0693eaae7271ee1abca0e6ad">SelectADDRsi_imp</a> (SDNode *OpNode, SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset, MVT VT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada37e46099456c37f3621649fcd60ffb">SelectADDRsi</a> (SDNode *OpNode, SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83570705b4922ed6b277e50806d366f2">SelectADDRsi64</a> (SDNode *OpNode, SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b6b2e14701a30e514f9afcf0eb016db">ChkMemSDNodeAddressSpace</a> (SDNode *N, unsigned int spN) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01">NVPTX::Ordering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#abd325b49b8e2f00c0370b1c68cf51557">NVPTX::Scope</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c42ba6f4d528f7a357f7d8355526eda">insertMemoryInstructionFence</a> (SDLoc DL, SDValue &amp;Chain, MemSDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#abd325b49b8e2f00c0370b1c68cf51557">NVPTX::Scope</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b5ef1b845f3e3faee21b6420e30344d">getOperationScope</a> (MemSDNode *N, NVPTX::Ordering O) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/nvptxsubtarget">NVPTXSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae30cd7169c6b8bea15d237b3f8c81ce7">Subtarget</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine">NVPTXTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c5f88079792a359c2d391244fc21ace">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fe2834322c809fcc38c59d40ee6ad38">doMulWide</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/nvptxscopes">NVPTXScopes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dfb96a735b8c1164f9613806a149877">Scopes</a> {}</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2093827c366dd806d3217fa46686bd89">GetConvertOpcode</a> (MVT DestTy, MVT SrcTy, LoadSDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetConvertOpcode - Returns the CVT_ instruction opcode that implements a conversion from <span class="doxyComputerOutput">SrcTy</span> to <span class="doxyComputerOutput">DestTy</span>. <a href="#a2093827c366dd806d3217fa46686bd89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NVPTXDAGToDAGISel() {#a5efcf313253f5408450d3fd28d241688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::NVPTXDAGToDAGISel::NVPTXDAGToDAGISel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>, <a href="#a5efcf313253f5408450d3fd28d241688">NVPTXDAGToDAGISel</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a5386ceeb71599848944185c0035e0e94">llvm::SelectionDAGISel::OptLevel</a> and <a href="#a35f13fd2a351449d5d3c894ff7eae2bc">runOnMachineFunction</a>.</p>


<p>Referenced by <a href="#a5efcf313253f5408450d3fd28d241688">NVPTXDAGToDAGISel</a> and <a href="#aedfc9f42058f04ebd41215ac5459949d">NVPTXDAGToDAGISel</a>.</p>

</div>
</div>

### NVPTXDAGToDAGISel() {#aedfc9f42058f04ebd41215ac5459949d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NVPTXDAGToDAGISel::NVPTXDAGToDAGISel (<a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine">NVPTXTargetMachine</a> &amp; tm, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OptLevel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="#a5efcf313253f5408450d3fd28d241688">NVPTXDAGToDAGISel</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a5386ceeb71599848944185c0035e0e94">llvm::SelectionDAGISel::OptLevel</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aeac54a65abd3a93279e58b0f474028fc">llvm::SelectionDAGISel::SelectionDAGISel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runOnMachineFunction() {#a35f13fd2a351449d5d3c894ff7eae2bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a> and <a href="#ae30cd7169c6b8bea15d237b3f8c81ce7">Subtarget</a>.</p>


<p>Referenced by <a href="#a5efcf313253f5408450d3fd28d241688">NVPTXDAGToDAGISel</a>.</p>

</div>
</div>

### SelectInlineAsmMemoryOperand() {#a992873c33224fdcfbff83b24b9c01dee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::SelectInlineAsmMemoryOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Op, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a> ConstraintID, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutOps)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SelectInlineAsmMemoryOperand - Implement addressing mode selection for inline asm expressions.</p>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2650 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a6f8f57715090da2632453988d9a1501b">llvm::InlineAsm::m</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### allowFMA() {#a5031bb0c47db3475151de0b44a6d3699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::allowFMA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### allowUnsafeFPMath() {#a69ab2757f8c1744f335d30a50a1a15d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::allowUnsafeFPMath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### ChkMemSDNodeAddressSpace() {#a9b6b2e14701a30e514f9afcf0eb016db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::ChkMemSDNodeAddressSpace (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned int spN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2633 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### doRsqrtOpt() {#a60eb2ba8a08f87e410b1a07defb83765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::doRsqrtOpt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getDivF32Level() {#a1a312a230dc9b6c2a3f442743baffe51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int NVPTXDAGToDAGISel::getDivF32Level ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getI32Imm() {#af12338284a1c40b05536cb2a666b95ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::NVPTXDAGToDAGISel::getI32Imm (unsigned Imm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>.</p>

</div>
</div>

### getOperationScope() {#a8b5ef1b845f3e3faee21b6420e30344d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NVPTX::Scope NVPTXDAGToDAGISel::getOperationScope (<a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a> * N, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01">NVPTX::Ordering</a> O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### insertMemoryInstructionFence() {#a8c42ba6f4d528f7a357f7d8355526eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; NVPTX::Ordering, NVPTX::Scope &gt; NVPTXDAGToDAGISel::insertMemoryInstructionFence (<a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### Select() {#accb2ac9e196435e7136d351b7e9600dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXDAGToDAGISel::Select (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Select - Select instructions not customized!</p>


<p>Used for expanded, promoted and normal instructions.</p>


<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectADDRri() {#a80f39a575823840ed06928f6e7ee6c75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::SelectADDRri (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * OpNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2622 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectADDRri\_imp() {#adf783fc7407eb01adbef6546fda44d6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::SelectADDRri_imp (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * OpNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2584 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectADDRri64() {#a9b4384bc492076227c6fdd79e36d3995}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::SelectADDRri64 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * OpNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2628 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectADDRsi() {#ada37e46099456c37f3621649fcd60ffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::SelectADDRsi (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * OpNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2572 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectADDRsi\_imp() {#a46b695cf0693eaae7271ee1abca0e6ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::SelectADDRsi_imp (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * OpNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2545 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectADDRsi64() {#a83570705b4922ed6b277e50806d366f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::SelectADDRsi64 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * OpNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2578 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectAddrSpaceCast() {#a3c266bdf75774b1480d25b97df53afec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXDAGToDAGISel::SelectAddrSpaceCast (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectCpAsyncBulkG2S() {#ab8cb412a9b5507afe61bf9154781ca2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXDAGToDAGISel::SelectCpAsyncBulkG2S (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 3127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectCpAsyncBulkPrefetchL2() {#a55edc7e681635fbddc9016228fb6095b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXDAGToDAGISel::SelectCpAsyncBulkPrefetchL2 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 3171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectCpAsyncBulkS2G() {#a765794ed7e43ef125b6ba2e3472072ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXDAGToDAGISel::SelectCpAsyncBulkS2G (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 3102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectCpAsyncBulkTensorG2SCommon() {#a7476107f769a3e19d3d023fbf3fee0b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXDAGToDAGISel::SelectCpAsyncBulkTensorG2SCommon (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, bool IsIm2Col=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2993 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectCpAsyncBulkTensorPrefetchCommon() {#ae505c022ace235a5c5dda554410f2dd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXDAGToDAGISel::SelectCpAsyncBulkTensorPrefetchCommon (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, bool IsIm2Col=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 3054 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectCpAsyncBulkTensorReduceCommon() {#aeeaeb64e76f8c37950fbb2589314fd88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXDAGToDAGISel::SelectCpAsyncBulkTensorReduceCommon (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned RedOp, bool IsIm2Col=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 3078 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectCpAsyncBulkTensorS2GCommon() {#a4a751faede98f80a1e5a198af28c178a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXDAGToDAGISel::SelectCpAsyncBulkTensorS2GCommon (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, bool IsIm2Col=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 3032 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectDirectAddr() {#a2dfb786a32c83cec00b23d2bf27abd6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::SelectDirectAddr (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2523 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectI128toV2I64() {#a93b1d5582732934f398f87ced5158612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXDAGToDAGISel::SelectI128toV2I64 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2702 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSETP\_BF16X2() {#a5737a3e8b050c99df7ce806841249f15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::SelectSETP_BF16X2 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSETP\_F16X2() {#ad86a4cb3a94ff11c5b4888f73fc6ccb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::SelectSETP_F16X2 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectTexSurfHandle() {#ac2105b3c48c5c3e75f66cfed32787627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXDAGToDAGISel::SelectTexSurfHandle (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectV2I64toI128() {#a29e45a742ea3a06aa34bd3d54834fbfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXDAGToDAGISel::SelectV2I64toI128 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2673 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryBF16ArithToFMA() {#a41741cbad01426e7fa0de0cfa76d2a49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryBF16ArithToFMA (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryBFE() {#a73541a360588337ce025f2449e297f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryBFE (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SelectBFE - Look for instruction sequences that can be made more efficient by using the 'bfe' (bit-field extract) PTX instruction.</p>

<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryConstantFP() {#a7c5ad15e626579ab9f13010d65ad44a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::NVPTXDAGToDAGISel::tryConstantFP (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>.</p>

</div>
</div>

### tryEXTRACT\_VECTOR\_ELEMENT() {#a8015defed2fd63a6127fc7a6eab7d4a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryEXTRACT_VECTOR_ELEMENT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryFence() {#ab8daca2d259d7e535398ef20a7aac1b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryFence (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2791 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryIntrinsicChain() {#a959b765446c9f3328b6592e258bbc0b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryIntrinsicChain (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryIntrinsicNoChain() {#a6988d22ead6737eb21584585492a0999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryIntrinsicNoChain (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryIntrinsicVoid() {#a79a71817e11f590d9c5a5fca88d9b256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryIntrinsicVoid (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 3190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryLDGLDU() {#a406264e3b51df02920728b0ad1bc3cb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryLDGLDU (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 1209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryLoad() {#a98eacf9aee5619492cc3020a65a317ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryLoad (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 874 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryLoadParam() {#af59b0036da7f617ef7609fa704ff0582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryLoadParam (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 1879 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryLoadVector() {#a95f04007c1595f89e1e9a84e77172290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryLoadVector (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 1004 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryStore() {#a1ca79f171cb3c8a16bb88a5f4f4c847e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryStore (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 1577 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryStoreParam() {#adefff6addc5eb9163f132d8ecf83e561}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryStoreParam (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryStoreRetval() {#afcbd3a626d62d6ffd4577b6de92b8b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryStoreRetval (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 1951 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryStoreVector() {#af5f9bad73925e7883546f5070c6897ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::tryStoreVector (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 1689 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### useF32FTZ() {#a31f1efbb191fc0ec25a1b9b4b50a94c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::useF32FTZ ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### usePrecSqrtF32() {#aec563e3328aef9926fa7f49784f06530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXDAGToDAGISel::usePrecSqrtF32 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Subtarget {#ae30cd7169c6b8bea15d237b3f8c81ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NVPTXSubtarget* llvm::NVPTXDAGToDAGISel::Subtarget = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>.</p>


<p>Referenced by <a href="#a35f13fd2a351449d5d3c894ff7eae2bc">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### doMulWide {#a9fe2834322c809fcc38c59d40ee6ad38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::NVPTXDAGToDAGISel::doMulWide</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>.</p>

</div>
</div>

### Scopes {#a2dfb96a735b8c1164f9613806a149877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NVPTXScopes llvm::NVPTXDAGToDAGISel::Scopes {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>.</p>

</div>
</div>

### TM {#a4c5f88079792a359c2d391244fc21ace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NVPTXTargetMachine&amp; llvm::NVPTXDAGToDAGISel::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### GetConvertOpcode() {#a2093827c366dd806d3217fa46686bd89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned NVPTXDAGToDAGISel::GetConvertOpcode (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> DestTy, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> SrcTy, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> * N)</td>
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

<p>GetConvertOpcode - Returns the CVT_ instruction opcode that implements a conversion from <span class="doxyComputerOutput">SrcTy</span> to <span class="doxyComputerOutput">DestTy</span>.</p>

<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a>, definition at line 2729 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-h">NVPTXISelDAGToDAG.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
