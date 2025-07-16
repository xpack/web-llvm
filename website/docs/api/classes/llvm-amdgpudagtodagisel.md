---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpudagtodagisel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUDAGToDAGISel` Class Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> specific code to select <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> machine instructions for <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> operations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUDAGToDAGISel { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">Target/AMDGPU/AMDGPUISelDAGToDAG.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-r600iseldagtodag-cpp-/r600dagtodagisel">R600DAGToDAGISel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a902b69968026e292a115616b07ae111d">AMDGPUDAGToDAGISel</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a011d178de3bdc4e89a133c0d85d47b44">AMDGPUDAGToDAGISel</a> (TargetMachine &amp;TM, CodeGenOptLevel OptLevel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60a7288af24c5de74d432973163470ac">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdcf01d7d3527e56cd6cc217975aac68">matchLoadD16FromBuildVector</a> (SDNode *N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a5d4f323744a3d4f3356493836cc59b">PreprocessISelDAG</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PreprocessISelDAG - This hook allows targets to hack on the graph before instruction selection starts. <a href="#a8a5d4f323744a3d4f3356493836cc59b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e1374fde17218f949e94ee57e18dc2c">Select</a> (SDNode *N) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main hook for targets to transform nodes into machine nodes. <a href="#a4e1374fde17218f949e94ee57e18dc2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9daed7c8ced0a5b7318d1679457ce200">PostprocessISelDAG</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a9daed7c8ced0a5b7318d1679457ce200">PostprocessISelDAG()</a> - This hook allows the target to hack on the graph right after selection. <a href="#a9daed7c8ced0a5b7318d1679457ce200">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a278bc9f5720547f5e171d0a62290d69f">SelectBuildVector</a> (SDNode *N, unsigned RegClassID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7003b5e44eb73177e8c26b4a91247e57">SelectVectorShuffle</a> (SDNode *N)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab60af3966b918e2d1849d50ecf17a960">fp16SrcZerosHighBits</a> (unsigned Opc) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b13efda691fd0b31fc63ccef05b2d62">foldFrameIndex</a> (SDValue N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24aa6c8f3b9c785240476e49bc111b00">isInlineImmediate</a> (const SDNode *N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c78e755229982c46a60f4dad3af230a">isInlineImmediate</a> (const APInt &amp;Imm) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7881f38d9e07a42b0d3fba4aeeed94e1">isInlineImmediate</a> (const APFloat &amp;Imm) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8176d4b8003c72f189d327f9334d26f6">isVGPRImm</a> (const SDNode *N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad13d5fd6aaec573637bc994bedfcf6eb">isUniformLoad</a> (const SDNode *N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad32a10ed1c870bbc22a236676a52c0ed">isUniformBr</a> (const SDNode *N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57b24588720108032857b8fecfe69042">isUnneededShiftMask</a> (const SDNode *N, unsigned ShAmtBits) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4792660ce933c0e5014a76879acd54ad">isBaseWithConstantOffset64</a> (SDValue Addr, SDValue &amp;LHS, SDValue &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinesdnode">MachineSDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac653a223cd1b3fdb01ec0cedd1974c2">buildSMovImm64</a> (SDLoc &amp;DL, uint64_t Val, EVT VT) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b33071934666b2ae80c571d66c5c734">glueCopyToOp</a> (SDNode *N, SDValue NewChain, SDValue Glue) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03078c7c19bed851ef3ef4916d68baed">glueCopyToM0</a> (SDNode *N, SDValue Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60494beaa7805d113eecff1c68da5f8e">glueCopyToM0LDSInit</a> (SDNode *N) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d05ff14632487ac49b9de656566d14a">getOperandRegClass</a> (SDNode *N, unsigned OpNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the register class for <span class="doxyComputerOutput">OpNo</span>. <a href="#a8d05ff14632487ac49b9de656566d14a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb51c862d1ff99e59ffec7db3f8c95b">SelectADDRVTX_READ</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a12a635a20dc82ad44775ec9d742b66">SelectADDRIndirect</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5939902c9658c18304df4dd31d9c2fa">isDSOffsetLegal</a> (SDValue Base, unsigned Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a617111537ae65e8b9c984a5278d28e22">isDSOffset2Legal</a> (SDValue Base, unsigned Offset0, unsigned Offset1, unsigned Size) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e6e795a4197dee00ebce49bd6e1da7b">isFlatScratchBaseLegal</a> (SDValue Addr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b3fb7a76e404a945dae2160de593fa">isFlatScratchBaseLegalSV</a> (SDValue Addr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaed6abc1382a990de2e6a9a358536bc">isFlatScratchBaseLegalSVImm</a> (SDValue Addr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2fd359d23436d9b79d76e2475184732">isSOffsetLegalWithImmOffset</a> (SDValue *SOffset, bool Imm32Only, bool IsBuffer, int64_t ImmOffset=0) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add8072c99d8bb7980ccd2ea125389079">SelectDS1Addr1Offset</a> (SDValue Ptr, SDValue &amp;Base, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d352c87fc784e3d1921639d2ebe0fd6">SelectDS64Bit4ByteAligned</a> (SDValue Ptr, SDValue &amp;Base, SDValue &amp;Offset0, SDValue &amp;Offset1) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc8bcb99e48332a4c82d578070a6b4e">SelectDS128Bit8ByteAligned</a> (SDValue Ptr, SDValue &amp;Base, SDValue &amp;Offset0, SDValue &amp;Offset1) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a631b2c9c919004626efdcfef12474600">SelectDSReadWrite2</a> (SDValue Ptr, SDValue &amp;Base, SDValue &amp;Offset0, SDValue &amp;Offset1, unsigned Size) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af27a81d638506056a3d769702c5f3954">SelectMUBUF</a> (SDValue Addr, SDValue &amp;SRsrc, SDValue &amp;VAddr, SDValue &amp;SOffset, SDValue &amp;Offset, SDValue &amp;Offen, SDValue &amp;Idxen, SDValue &amp;Addr64) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2b4bbe2c596da1432cc7b03db0e1667">SelectMUBUFAddr64</a> (SDValue Addr, SDValue &amp;SRsrc, SDValue &amp;VAddr, SDValue &amp;SOffset, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce3a5f25aa305c09209486608535dbf">SelectMUBUFScratchOffen</a> (SDNode *Parent, SDValue Addr, SDValue &amp;RSrc, SDValue &amp;VAddr, SDValue &amp;SOffset, SDValue &amp;ImmOffset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f01f50adfc97642500f2353c94544d6">SelectMUBUFScratchOffset</a> (SDNode *Parent, SDValue Addr, SDValue &amp;SRsrc, SDValue &amp;Soffset, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accd13e80a48c8c64701e2cf76b7b39dc">SelectMUBUFOffset</a> (SDValue Addr, SDValue &amp;SRsrc, SDValue &amp;Soffset, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c487f2953ba83a2906640c9f5790f9c">SelectBUFSOffset</a> (SDValue Addr, SDValue &amp;SOffset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a832bfd332cf958f615937ccd5b20c2">SelectFlatOffsetImpl</a> (SDNode *N, SDValue Addr, SDValue &amp;VAddr, SDValue &amp;Offset, uint64_t FlatVariant) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6770c26e9264c3ab437e78979ab2d6b7">SelectFlatOffset</a> (SDNode *N, SDValue Addr, SDValue &amp;VAddr, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b03f39a4d32d0a1ae2b53b88a07ef8">SelectGlobalOffset</a> (SDNode *N, SDValue Addr, SDValue &amp;VAddr, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a4b783574bddde89806147f8c12189a">SelectScratchOffset</a> (SDNode *N, SDValue Addr, SDValue &amp;VAddr, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a3c9314a8212123e372232b57a4ad3e">SelectGlobalSAddr</a> (SDNode *N, SDValue Addr, SDValue &amp;SAddr, SDValue &amp;VOffset, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac38383078fe446fa29c1311ffe4f1191">SelectScratchSAddr</a> (SDNode *N, SDValue Addr, SDValue &amp;SAddr, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0849455539f99b66f901f74ced1caa2f">checkFlatScratchSVSSwizzleBug</a> (SDValue VAddr, SDValue SAddr, uint64_t ImmOffset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6b4f735a3abfb913ab390bb12cef324">SelectScratchSVAddr</a> (SDNode *N, SDValue Addr, SDValue &amp;VAddr, SDValue &amp;SAddr, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa38e3390ae04d3a64ca7187c7b50152d">SelectSMRDOffset</a> (SDValue ByteOffsetNode, SDValue *SOffset, SDValue *Offset, bool Imm32Only=false, bool IsBuffer=false, bool HasSOffset=false, int64_t ImmOffset=0) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a865cbbc300cd8829b7801221227975">Expand32BitAddress</a> (SDValue Addr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21d17bc745af03db24f0ddb77fd6b3f5">SelectSMRDBaseOffset</a> (SDValue Addr, SDValue &amp;SBase, SDValue *SOffset, SDValue *Offset, bool Imm32Only=false, bool IsBuffer=false, bool HasSOffset=false, int64_t ImmOffset=0) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add69c77c790fb2db4dd5433238b44761">SelectSMRD</a> (SDValue Addr, SDValue &amp;SBase, SDValue *SOffset, SDValue *Offset, bool Imm32Only=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2259b9071a6ba70fda0512cfe111406">SelectSMRDImm</a> (SDValue Addr, SDValue &amp;SBase, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ed615cc4fa220eaa0d131dbb25b137">SelectSMRDImm32</a> (SDValue Addr, SDValue &amp;SBase, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8e69e7ae016fc384a1031f8b69c7506">SelectSMRDSgpr</a> (SDValue Addr, SDValue &amp;SBase, SDValue &amp;SOffset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33d0e5658647dc11c2613fd4a47a48a5">SelectSMRDSgprImm</a> (SDValue Addr, SDValue &amp;SBase, SDValue &amp;SOffset, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d28a509b02a62a3915bdd641ff1fcf6">SelectSMRDBufferImm</a> (SDValue N, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dd303a7fdb537930a32a68d855e79e0">SelectSMRDBufferImm32</a> (SDValue N, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac32ac47cff72836a06fa255420a774cf">SelectSMRDBufferSgprImm</a> (SDValue N, SDValue &amp;SOffset, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af296fa8e1a1f1b3c1d560b8118fa9ba5">SelectSMRDPrefetchImm</a> (SDValue Addr, SDValue &amp;SBase, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ad81db1a46ff58296d1445e2da8955">SelectMOVRELOffset</a> (SDValue Index, SDValue &amp;Base, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3175135ff66d16dceca1bebb24dc9b04">SelectVOP3ModsImpl</a> (SDValue In, SDValue &amp;Src, unsigned &amp;SrcMods, bool IsCanonicalizing=true, bool AllowAbs=true) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cae40b13a7f42c3876ac231631848e4">SelectVOP3Mods</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a38193abb93e6c8f32acca32d7d23d9">SelectVOP3ModsNonCanonicalizing</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f364c02f0d34d06c674ccfabb16769">SelectVOP3BMods</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f4762d04ab668afcfa6d375743a335">SelectVOP3NoMods</a> (SDValue In, SDValue &amp;Src) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a055d951f05661a0322e100011f938574">SelectVOP3Mods0</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods, SDValue &amp;Clamp, SDValue &amp;Omod) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76d3464e6649bb3f3ef062dad87268da">SelectVOP3BMods0</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods, SDValue &amp;Clamp, SDValue &amp;Omod) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b50ee45ea3fee79cbb81b9431f47f3">SelectVOP3NoMods0</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods, SDValue &amp;Clamp, SDValue &amp;Omod) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6034852611224657cf5bf6c1bb90260">SelectVINTERPModsImpl</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods, bool OpSel) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36dd33c6a2a3f1e82b572303fd54f381">SelectVINTERPMods</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae474d2c8e34599ac83ef274adff63f2b">SelectVINTERPModsHi</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06441b610ce63b1c48c2cff104d84d2c">SelectVOP3OMods</a> (SDValue In, SDValue &amp;Src, SDValue &amp;Clamp, SDValue &amp;Omod) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2c5ef357b94439fd81cf1a0a54bf8b9">SelectVOP3PMods</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods, bool IsDOT=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07bb5c63db2e3be62db2183ecfde3bc2">SelectVOP3PModsDOT</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ec8daee37972b63857c2c7dace59af">SelectVOP3PModsNeg</a> (SDValue In, SDValue &amp;Src) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2053d0ea22b74653b58c9d1a5f5876">SelectWMMAOpSelVOP3PMods</a> (SDValue In, SDValue &amp;Src) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ede471b0bb787906c348835b81294c8">SelectWMMAModsF32NegAbs</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a9884a69cf02e68613f052e072d9d3d">SelectWMMAModsF16Neg</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb2fad22c2fbd9653761e6676eaaec99">SelectWMMAModsF16NegAbs</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a924d267973ac6751575de30c85d4c6c2">SelectWMMAVISrc</a> (SDValue In, SDValue &amp;Src) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0af8937ba8d84ebe2abc3b440a5ea86">SelectSWMMACIndex8</a> (SDValue In, SDValue &amp;Src, SDValue &amp;IndexKey) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a695e70d16c044c267215099732a9ac33">SelectSWMMACIndex16</a> (SDValue In, SDValue &amp;Src, SDValue &amp;IndexKey) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f5eef28adbb60ccf83a36f3ebde9a4f">SelectVOP3OpSel</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f541ef5c9ba74a859ae96ed6b34fba2">SelectVOP3OpSelMods</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35716908b265ee42507938762ed1c8a">SelectVOP3PMadMixModsImpl</a> (SDValue In, SDValue &amp;Src, unsigned &amp;Mods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1df9d4bad8ff0d3766d8a08bce746937">SelectVOP3PMadMixModsExt</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af25f7034e3b9c4ba368e0987917fce56">SelectVOP3PMadMixMods</a> (SDValue In, SDValue &amp;Src, SDValue &amp;SrcMods) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa8c259c66b0844c7f77407a9e26b08f">SelectBITOP3</a> (SDValue In, SDValue &amp;Src0, SDValue &amp;Src1, SDValue &amp;Src2, SDValue &amp;Tbl) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09f8c836b8a945642affe9428cd18b65">getHi16Elt</a> (SDValue In) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3531916055489a6066862a81adf8df2">getMaterializedScalarImm32</a> (int64_t Val, const SDLoc &amp;DL) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a012a62195ad975ef90b67d57a232b457">SelectADD_SUB_I64</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76d036e81cf004269b247a3b809d06dd">SelectAddcSubb</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2d44d4f02608e18b06909d4e9b4365c">SelectUADDO_USUBO</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27ed435936c1330cd2dc7b796c202bf7">SelectDIV_SCALE</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d751ea7004ab05b535d0820322e5091">SelectMAD_64_32</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0360039e73c5c24a56b1358bb49e1103">SelectMUL_LOHI</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1ebb9e6b13e1ec98c39a35148c92e64">SelectFMA_W_CHAIN</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae78e4eb1ac548de270f0c098e7e6d5">SelectFMUL_W_CHAIN</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d788b3416f603a1db1baccb52599a3">getBFE32</a> (bool IsSigned, const SDLoc &amp;DL, SDValue Val, uint32_t Offset, uint32_t Width)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a471cd7ac6801ab5499068c14f2f91087">SelectS_BFEFromShifts</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdc65875cb79bd6c2818ae5f367f8c4a">SelectS_BFE</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5790076ab910b131ba034509469264dd">isCBranchSCC</a> (const SDNode *N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af22962cdd13139fe1ca9e684765bed2a">SelectBRCOND</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6d279bbd3c19e5e39f13dda8a01cb50">SelectFMAD_FMA</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6d2a884390fd30572d341eafe950e7a">SelectFP_EXTEND</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2d0878dde3e46e1d65d4e628266bdb7">SelectDSAppendConsume</a> (SDNode *N, unsigned IntrID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd5ad458ccd4c1279fc105b52dc5a4d7">SelectDSBvhStackIntrinsic</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af946f222fff9665b520bc6e61a3ccedf">SelectDS_GWS</a> (SDNode *N, unsigned IntrID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e9cb0570b21d7ac4430fcef2378ad3d">SelectInterpP1F16</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bdffab2d2ac8d8ac784ff49f3d01a1e">SelectINTRINSIC_W_CHAIN</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ee128fbc23f915a6e112549b239da0e">SelectINTRINSIC_WO_CHAIN</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a665d74f7540d86532e1a59285f031b59">SelectINTRINSIC_VOID</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6760aa9d1ca74741eb558cb4c6c306e">SelectWAVE_ADDRESS</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e5ac1a729e2baf1ea94d7757351c62">SelectSTACKRESTORE</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345b4e58031e7492f38fac7ebb21ec21">Subtarget</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults">SIModeRegisterDefaults</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac58cedbae2aa64c6bf90190d3784882d">Mode</a></td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> specific code to select <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> machine instructions for <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> operations.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUDAGToDAGISel() {#a902b69968026e292a115616b07ae111d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPUDAGToDAGISel::AMDGPUDAGToDAGISel ()</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a5386ceeb71599848944185c0035e0e94">llvm::SelectionDAGISel::OptLevel</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a0ead78650333eefc4d5591ca3db9ed4b">llvm::SelectionDAGISel::TM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600iseldagtodag-cpp-/r600dagtodagisel/#a7b384d32725b747a54d21bb0e27d3ded">anonymous{R600ISelDAGToDAG.cpp}::R600DAGToDAGISel::R600DAGToDAGISel</a>.</p>

</div>
</div>

### AMDGPUDAGToDAGISel() {#a011d178de3bdc4e89a133c0d85d47b44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUDAGToDAGISel::AMDGPUDAGToDAGISel (<a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OptLevel)</td>
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



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a5386ceeb71599848944185c0035e0e94">llvm::SelectionDAGISel::OptLevel</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aeac54a65abd3a93279e58b0f474028fc">llvm::SelectionDAGISel::SelectionDAGISel</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a0ead78650333eefc4d5591ca3db9ed4b">llvm::SelectionDAGISel::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### matchLoadD16FromBuildVector() {#afdcf01d7d3527e56cd6cc217975aac68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::matchLoadD16FromBuildVector (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#a20fd5ba47db6a4cc8ad9d197fc1bbbee">llvm::LoadSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ab858661e16a61c4fc6b27b6b26aac17b">llvm::MemSDNode::getChain</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#ad85ec82447c2f1824538de9b449ffed0">llvm::LoadSDNode::getExtensionType</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aa078a60d1127b9daad580b6d2ba7ef91">llvm::MemSDNode::getMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aee0e58997cd08983518f051e79b855d9">llvm::MemSDNode::getMemoryVT</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#aaf99b3ee1d9577ac86d3bf072c7bc789">llvm::SDNode::isPredecessorOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0eaaf3ef4daab9db871926a727d7cca444a">llvm::AMDGPUISD::LOAD_D16_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0ea8a604d758e44ad80fc6c79fdcfde3424">llvm::AMDGPUISD::LOAD_D16_HI_I8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0ea76dae89c9d37a7d4a007589e236d7579">llvm::AMDGPUISD::LOAD_D16_HI_U8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0ea9d9d3af4d64c8851bed302606264cf64">llvm::AMDGPUISD::LOAD_D16_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0ea62d5df7316428469ea4d31d893d2bffe">llvm::AMDGPUISD::LOAD_D16_LO_I8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0eac344911a086691a209bc2cfa6a7d29ee">llvm::AMDGPUISD::LOAD_D16_LO_U8</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>.</p>


<p>Referenced by <a href="#a8a5d4f323744a3d4f3356493836cc59b">PreprocessISelDAG</a>.</p>

</div>
</div>

### PostprocessISelDAG() {#a9daed7c8ced0a5b7318d1679457ce200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::PostprocessISelDAG ()</td>
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

<p><a href="#a9daed7c8ced0a5b7318d1679457ce200">PostprocessISelDAG()</a> - This hook allows the target to hack on the graph right after selection.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3940 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af5bffbb8254140e8679a9b7c0766f9e2">llvm::SelectionDAGISel::getTargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4981871ea1a597d1b8aa1a8ac9326e76a29d4416121b20dd5ccd9ffca40c05524">llvm::Lowering</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a84e771c0f56c984d8ee4a85c0cb46ed3">llvm::SelectionDAGISel::ReplaceUses</a>.</p>

</div>
</div>

### PreprocessISelDAG() {#a8a5d4f323744a3d4f3356493836cc59b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::PreprocessISelDAG ()</td>
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

<p>PreprocessISelDAG - This hook allows targets to hack on the graph before instruction selection starts.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#afdcf01d7d3527e56cd6cc217975aac68">matchLoadD16FromBuildVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a60a7288af24c5de74d432973163470ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#af54ef9f214b4b023adbc4a66e2305666">llvm::GCNSubtarget::checkSubtargetFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>.</p>

</div>
</div>

### Select() {#a4e1374fde17218f949e94ee57e18dc2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::Select (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Main hook for targets to transform nodes into machine nodes.</p>

<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a20084f62caecb0db80ad71bdabda73c2">llvm::ISD::ADDC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad116e32876f2275acf60ffb1651c9256">llvm::ISD::ADDE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0ea9d8dde2474ce68109f2472f204072c80">llvm::AMDGPUISD::BFE_I32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0eacb028e9739d033de026de0a3b2ac9f9e">llvm::AMDGPUISD::BFE_U32</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aad0b781d8b8a804437e919429069fcd7">llvm::EVT::bitsEq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a41bd84b853e2c03fb1af1f4ca9ebdcaf">llvm::ISD::BUILD_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aac2f0a84dd2aa5ee4c3f1385e9565f5e">llvm::ISD::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1be4c8da7c68a4c683de1a98b5cc5b9d">llvm::ISD::ConstantFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93bc27ca4d9e211c54b0d9efb660f080">llvm::ISD::CopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0ea9326abce64225b1fcaf656b06d5819ad">llvm::AMDGPUISD::CVT_PK_I16_I32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0ea61c1f4bb39a8d5172f7a4f2b50d8b290">llvm::AMDGPUISD::CVT_PK_U16_U32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0ea39c851d59f2dedcf582022a24daf1cf5">llvm::AMDGPUISD::CVT_PKNORM_I16_F32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0eaf372b02c7f2eb214586b79418da259d3">llvm::AMDGPUISD::CVT_PKNORM_U16_F32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0ea05e199d247b019380b4c5a6f24d95381">llvm::AMDGPUISD::CVT_PKRTZ_F16_F32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0ea0819f8cbdd0851cea7a14606204c92fa">llvm::AMDGPUISD::DIV_SCALE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0ea6ea93bd531619261a61f34eb59c5e7d2">llvm::AMDGPUISD::FMA_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0eaa9b6b15abc704da34341aa029217d8a5">llvm::AMDGPUISD::FMUL_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a7d8aef424553a9b93de21ced693f0b09">llvm::SIRegisterInfo::getSGPRClassForBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af5bffbb8254140e8679a9b7c0766f9e2">llvm::SelectionDAGISel::getTargetLowering</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a5cb49674ec65724b4d9aecb48588a13a">llvm::ConstantSDNode::getZExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4dbb64e9d316b0b56b74d3364cb601da">llvm::AMDGPU::isValid32BitLiteral</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4981871ea1a597d1b8aa1a8ac9326e76a29d4416121b20dd5ccd9ffca40c05524">llvm::Lowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0eae110f734779ea7435c1f89a1b019e8e9">llvm::AMDGPUISD::MAD_I64_I32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0ea760ece3c08b02521b09f90ee5a5e4fdb">llvm::AMDGPUISD::MAD_U64_U32</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94b1e36afbaf95cc035249a6267f9472">llvm::packConstantV2I16</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="#a278bc9f5720547f5e171d0a62290d69f">SelectBuildVector</a>, <a href="#a7003b5e44eb73177e8c26b4a91247e57">SelectVectorShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1354c6f8508d6cd697dc89a5d9a52dfd">llvm::ISD::SMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a023a9de787026fe61b024476bf9c32cb">llvm::ISD::STACKRESTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2ab6db512a611d1ef4ff8069e2bbfd0d">llvm::ISD::SUBC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac9246c101c0cc9232e37b3941194bb13">llvm::ISD::SUBE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ddf36330110b4abea43fe390bea9ef9">llvm::ISD::UADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0f1e3ed26108fec69eb97209c0e39bf">llvm::ISD::UADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a79c959df09509d7ff66d9b04bc40d18d">llvm::ISD::UMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4ffc75d65231b55461c0ba4f36a3e500">llvm::ISD::USUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac81ebcd59d629d8680e50ffba9855255">llvm::ISD::USUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuisd/#a739d53294bc38cd6b0b23332f9994c0eafc9e8f6f7cbd326bc7d7456f711ea223">llvm::AMDGPUISD::WAVE_ADDRESS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### SelectBuildVector() {#a278bc9f5720547f5e171d0a62290d69f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectBuildVector (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned RegClassID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">llvm::Triple::amdgcn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/r600registerinfo/#a9769d7d0cd244192d98524db21e2f3c2">llvm::R600RegisterInfo::getSubRegFromChannel</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a1be43761db2568933db89648201ab15c">llvm::SIRegisterInfo::getSubRegFromChannel</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600iseldagtodag-cpp-/r600dagtodagisel/#a526fd2710d7457e09c2b4715b2367638">anonymous{R600ISelDAGToDAG.cpp}::R600DAGToDAGISel::Select</a> and <a href="#a4e1374fde17218f949e94ee57e18dc2c">Select</a>.</p>

</div>
</div>

### SelectVectorShuffle() {#a7003b5e44eb73177e8c26b4a91247e57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectVectorShuffle (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aad0b781d8b8a804437e919429069fcd7">llvm::EVT::bitsEq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a18feaba13b7b787025cbd0027e79cc85">llvm::SISrcMods::NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a3b095994a942145ccaaed4f175c7172a">llvm::SISrcMods::OP_SEL_0</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442af0e8126187c47c5b74a1bdc635158144">llvm::SISrcMods::OP_SEL_1</a>.</p>


<p>Referenced by <a href="#a4e1374fde17218f949e94ee57e18dc2c">Select</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildSMovImm64() {#aac653a223cd1b3fdb01ec0cedd1974c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSDNode * AMDGPUDAGToDAGISel::buildSMovImm64 (<a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, uint64_t Val, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### checkFlatScratchSVSSwizzleBug() {#a0849455539f99b66f901f74ced1caa2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::checkFlatScratchSVSSwizzleBug (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> VAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> SAddr, uint64_t ImmOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2011 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### Expand32BitAddress() {#a1a865cbbc300cd8829b7801221227975}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AMDGPUDAGToDAGISel::Expand32BitAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### foldFrameIndex() {#a7b13efda691fd0b31fc63ccef05b2d62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; AMDGPUDAGToDAGISel::foldFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1544 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### fp16SrcZerosHighBits() {#ab60af3966b918e2d1849d50ecf17a960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::fp16SrcZerosHighBits (unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getBFE32() {#ab0d788b3416f603a1db1baccb52599a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * AMDGPUDAGToDAGISel::getBFE32 (bool IsSigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, uint32_t Offset, uint32_t Width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getHi16Elt() {#a09f8c836b8a945642affe9428cd18b65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AMDGPUDAGToDAGISel::getHi16Elt (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3847 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getMaterializedScalarImm32() {#ab3531916055489a6066862a81adf8df2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AMDGPUDAGToDAGISel::getMaterializedScalarImm32 (int64_t Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 922 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getOperandRegClass() {#a8d05ff14632487ac49b9de656566d14a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * AMDGPUDAGToDAGISel::getOperandRegClass (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned OpNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the register class for <span class="doxyComputerOutput">OpNo</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The register class of the virtual register that will be used for the given operand number \OpNo or NULL if the register class cannot be determined.</p></dd>
</dl>


<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### glueCopyToM0() {#a03078c7c19bed851ef3ef4916d68baed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * AMDGPUDAGToDAGISel::glueCopyToM0 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### glueCopyToM0LDSInit() {#a60494beaa7805d113eecff1c68da5f8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * AMDGPUDAGToDAGISel::glueCopyToM0LDSInit (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### glueCopyToOp() {#a0b33071934666b2ae80c571d66c5c734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * AMDGPUDAGToDAGISel::glueCopyToOp (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> NewChain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Glue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isBaseWithConstantOffset64() {#a4792660ce933c0e5014a76879acd54ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::isBaseWithConstantOffset64 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isCBranchSCC() {#a5790076ab910b131ba034509469264dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::isCBranchSCC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2469 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isDSOffset2Legal() {#a617111537ae65e8b9c984a5278d28e22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::isDSOffset2Legal (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Base, unsigned Offset0, unsigned Offset1, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isDSOffsetLegal() {#ab5939902c9658c18304df4dd31d9c2fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::isDSOffsetLegal (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Base, unsigned Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isFlatScratchBaseLegal() {#a5e6e795a4197dee00ebce49bd6e1da7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::isFlatScratchBaseLegal (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isFlatScratchBaseLegalSV() {#a98b3fb7a76e404a945dae2160de593fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::isFlatScratchBaseLegalSV (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isFlatScratchBaseLegalSVImm() {#adaed6abc1382a990de2e6a9a358536bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::isFlatScratchBaseLegalSVImm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isInlineImmediate() {#a24aa6c8f3b9c785240476e49bc111b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::isInlineImmediate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isInlineImmediate() {#a5c78e755229982c46a60f4dad3af230a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUDAGToDAGISel::isInlineImmediate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>.</p>

</div>
</div>

### isInlineImmediate() {#a7881f38d9e07a42b0d3fba4aeeed94e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUDAGToDAGISel::isInlineImmediate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Imm)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>.</p>

</div>
</div>

### isSOffsetLegalWithImmOffset() {#aa2fd359d23436d9b79d76e2475184732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::isSOffsetLegalWithImmOffset (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * SOffset, bool Imm32Only, bool IsBuffer, int64_t ImmOffset=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isUniformBr() {#ad32a10ed1c870bbc22a236676a52c0ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::isUniformBr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isUniformLoad() {#ad13d5fd6aaec573637bc994bedfcf6eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::isUniformLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3920 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isUnneededShiftMask() {#a57b24588720108032857b8fecfe69042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::isUnneededShiftMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned ShAmtBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isVGPRImm() {#a8176d4b8003c72f189d327f9334d26f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::isVGPRImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3869 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectADD\_SUB\_I64() {#a012a62195ad975ef90b67d57a232b457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectADD_SUB_I64 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 931 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectAddcSubb() {#a76d036e81cf004269b247a3b809d06dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectAddcSubb (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectADDRIndirect() {#a5a12a635a20dc82ad44775ec9d742b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectADDRIndirect (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 898 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectADDRVTX\_READ() {#a0eb51c862d1ff99e59ffec7db3f8c95b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectADDRVTX_READ (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectBITOP3() {#aaa8c259c66b0844c7f77407a9e26b08f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectBITOP3 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src2, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Tbl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3797 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectBRCOND() {#af22962cdd13139fe1ca9e684765bed2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectBRCOND (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2524 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectBUFSOffset() {#a6c487f2953ba83a2906640c9f5790f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectBUFSOffset (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1704 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectDIV\_SCALE() {#a27ed435936c1330cd2dc7b796c202bf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectDIV_SCALE (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1089 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectDS\_GWS() {#af946f222fff9665b520bc6e61a3ccedf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectDS_GWS (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned IntrID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2698 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectDS128Bit8ByteAligned() {#a3cc8bcb99e48332a4c82d578070a6b4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectDS128Bit8ByteAligned (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Ptr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectDS1Addr1Offset() {#add8072c99d8bb7980ccd2ea125389079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectDS1Addr1Offset (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Ptr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectDS64Bit4ByteAligned() {#a1d352c87fc784e3d1921639d2ebe0fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectDS64Bit4ByteAligned (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Ptr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectDSAppendConsume() {#af2d0878dde3e46e1d65d4e628266bdb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectDSAppendConsume (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned IntrID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2626 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectDSBvhStackIntrinsic() {#abd5ad458ccd4c1279fc105b52dc5a4d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectDSBvhStackIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectDSReadWrite2() {#a631b2c9c919004626efdcfef12474600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectDSReadWrite2 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Ptr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset1, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectFlatOffset() {#a6770c26e9264c3ab437e78979ab2d6b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectFlatOffset (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; VAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1824 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectFlatOffsetImpl() {#a2a832bfd332cf958f615937ccd5b20c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectFlatOffsetImpl (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; VAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, uint64_t FlatVariant)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1729 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectFMA\_W\_CHAIN() {#ad1ebb9e6b13e1ec98c39a35148c92e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectFMA_W_CHAIN (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1053 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectFMAD\_FMA() {#ab6d279bbd3c19e5e39f13dda8a01cb50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPUDAGToDAGISel::SelectFMAD_FMA (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>.</p>

</div>
</div>

### SelectFMUL\_W\_CHAIN() {#afae78e4eb1ac548de270f0c098e7e6d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectFMUL_W_CHAIN (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1074 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectFP\_EXTEND() {#ac6d2a884390fd30572d341eafe950e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectFP_EXTEND (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2610 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectGlobalOffset() {#a74b03f39a4d32d0a1ae2b53b88a07ef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectGlobalOffset (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; VAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1830 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectGlobalSAddr() {#a0a3c9314a8212123e372232b57a4ad3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectGlobalSAddr (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; VOffset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1853 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectInterpP1F16() {#a7e9cb0570b21d7ac4430fcef2378ad3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectInterpP1F16 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2764 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectINTRINSIC\_VOID() {#a665d74f7540d86532e1a59285f031b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectINTRINSIC_VOID (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2918 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectINTRINSIC\_W\_CHAIN() {#a1bdffab2d2ac8d8ac784ff49f3d01a1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectINTRINSIC_W_CHAIN (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2822 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectINTRINSIC\_WO\_CHAIN() {#a2ee128fbc23f915a6e112549b239da0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectINTRINSIC_WO_CHAIN (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2845 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectMAD\_64\_32() {#a5d751ea7004ab05b535d0820322e5091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectMAD_64_32 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectMOVRELOffset() {#a83ad81db1a46ff58296d1445e2da8955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectMOVRELOffset (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectMUBUF() {#af27a81d638506056a3d769702c5f3954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectMUBUF (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SRsrc, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; VAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SOffset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offen, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Idxen, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Addr64)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectMUBUFAddr64() {#af2b4bbe2c596da1432cc7b03db0e1667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectMUBUFAddr64 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SRsrc, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; VAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SOffset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1517 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectMUBUFOffset() {#accd13e80a48c8c64701e2cf76b7b39dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectMUBUFOffset (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SRsrc, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Soffset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1679 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectMUBUFScratchOffen() {#a3ce3a5f25aa305c09209486608535dbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectMUBUFScratchOffen (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; RSrc, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; VAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SOffset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; ImmOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectMUBUFScratchOffset() {#a3f01f50adfc97642500f2353c94544d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectMUBUFScratchOffset (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SRsrc, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Soffset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectMUL\_LOHI() {#a0360039e73c5c24a56b1358bb49e1103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectMUL_LOHI (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectS\_BFE() {#abdc65875cb79bd6c2818ae5f367f8c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectS_BFE (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectS\_BFEFromShifts() {#a471cd7ac6801ab5499068c14f2f91087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectS_BFEFromShifts (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectScratchOffset() {#a8a4b783574bddde89806147f8c12189a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectScratchOffset (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; VAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1836 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectScratchSAddr() {#ac38383078fe446fa29c1311ffe4f1191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectScratchSAddr (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1967 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectScratchSVAddr() {#ad6b4f735a3abfb913ab390bb12cef324}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectScratchSVAddr (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; VAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2029 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSMRD() {#add69c77c790fb2db4dd5433238b44761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectSMRD (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SBase, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * SOffset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * Offset, bool Imm32Only=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSMRDBaseOffset() {#a21d17bc745af03db24f0ddb77fd6b3f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectSMRDBaseOffset (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SBase, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * SOffset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * Offset, bool Imm32Only=false, bool IsBuffer=false, bool HasSOffset=false, int64_t ImmOffset=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSMRDBufferImm() {#a2d28a509b02a62a3915bdd641ff1fcf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectSMRDBufferImm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSMRDBufferImm32() {#a3dd303a7fdb537930a32a68d855e79e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectSMRDBufferImm32 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSMRDBufferSgprImm() {#ac32ac47cff72836a06fa255420a774cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectSMRDBufferSgprImm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SOffset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSMRDImm() {#ac2259b9071a6ba70fda0512cfe111406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectSMRDImm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SBase, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSMRDImm32() {#a64ed615cc4fa220eaa0d131dbb25b137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectSMRDImm32 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SBase, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSMRDOffset() {#aa38e3390ae04d3a64ca7187c7b50152d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectSMRDOffset (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ByteOffsetNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * SOffset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * Offset, bool Imm32Only=false, bool IsBuffer=false, bool HasSOffset=false, int64_t ImmOffset=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSMRDPrefetchImm() {#af296fa8e1a1f1b3c1d560b8118fa9ba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUDAGToDAGISel::SelectSMRDPrefetchImm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SBase, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>.</p>

</div>
</div>

### SelectSMRDSgpr() {#aa8e69e7ae016fc384a1031f8b69c7506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectSMRDSgpr (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SBase, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSMRDSgprImm() {#a33d0e5658647dc11c2613fd4a47a48a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectSMRDSgprImm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SBase, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SOffset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSTACKRESTORE() {#a04e5ac1a729e2baf1ea94d7757351c62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectSTACKRESTORE (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2943 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSWMMACIndex16() {#a695e70d16c044c267215099732a9ac33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectSWMMACIndex16 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; IndexKey)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3584 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectSWMMACIndex8() {#ac0af8937ba8d84ebe2abc3b440a5ea86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectSWMMACIndex8 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; IndexKey)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3565 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectUADDO\_USUBO() {#aa2d44d4f02608e18b06909d4e9b4365c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectUADDO_USUBO (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 1020 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVINTERPMods() {#a36dd33c6a2a3f1e82b572303fd54f381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVINTERPMods (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3064 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVINTERPModsHi() {#ae474d2c8e34599ac83ef274adff63f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVINTERPModsHi (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3069 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVINTERPModsImpl() {#ad6034852611224657cf5bf6c1bb90260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVINTERPModsImpl (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods, bool OpSel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3048 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3BMods() {#a80f364c02f0d34d06c674ccfabb16769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3BMods (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3027 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3BMods0() {#a76d3464e6649bb3f3ef062dad87268da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3BMods0 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Clamp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Omod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3084 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3Mods() {#a6cae40b13a7f42c3876ac231631848e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3Mods (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3003 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3Mods0() {#a055d951f05661a0322e100011f938574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3Mods0 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Clamp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Omod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3074 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3ModsImpl() {#a3175135ff66d16dceca1bebb24dc9b04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3ModsImpl (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, unsigned &amp; SrcMods, bool IsCanonicalizing=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool AllowAbs=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2975 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3ModsNonCanonicalizing() {#a1a38193abb93e6c8f32acca32d7d23d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3ModsNonCanonicalizing (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3015 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3NoMods() {#a54f4762d04ab668afcfa6d375743a335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3NoMods (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3040 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3NoMods0() {#a26b50ee45ea3fee79cbb81b9431f47f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUDAGToDAGISel::SelectVOP3NoMods0 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Clamp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Omod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>.</p>

</div>
</div>

### SelectVOP3OMods() {#a06441b610ce63b1c48c2cff104d84d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3OMods (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Clamp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Omod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3094 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3OpSel() {#a1f5eef28adbb60ccf83a36f3ebde9a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3OpSel (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3OpSelMods() {#a3f541ef5c9ba74a859ae96ed6b34fba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3OpSelMods (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3611 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3PMadMixMods() {#af25f7034e3b9c4ba368e0987917fce56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3PMadMixMods (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3669 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3PMadMixModsExt() {#a1df9d4bad8ff0d3766d8a08bce746937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3PMadMixModsExt (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3PMadMixModsImpl() {#ac35716908b265ee42507938762ed1c8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3PMadMixModsImpl (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, unsigned &amp; Mods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3619 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3PMods() {#ab2c5ef357b94439fd81cf1a0a54bf8b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3PMods (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods, bool IsDOT=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3PModsDOT() {#a07bb5c63db2e3be62db2183ecfde3bc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3PModsDOT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectVOP3PModsNeg() {#a83ec8daee37972b63857c2c7dace59af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectVOP3PModsNeg (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectWAVE\_ADDRESS() {#ae6760aa9d1ca74741eb558cb4c6c306e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDAGToDAGISel::SelectWAVE_ADDRESS (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 2936 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectWMMAModsF16Neg() {#a9a9884a69cf02e68613f052e072d9d3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectWMMAModsF16Neg (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectWMMAModsF16NegAbs() {#abb2fad22c2fbd9653761e6676eaaec99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectWMMAModsF16NegAbs (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectWMMAModsF32NegAbs() {#a0ede471b0bb787906c348835b81294c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectWMMAModsF32NegAbs (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SrcMods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3476 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectWMMAOpSelVOP3PMods() {#a4c2053d0ea22b74653b58c9d1a5f5876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectWMMAOpSelVOP3PMods (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectWMMAVISrc() {#a924d267973ac6751575de30c85d4c6c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDAGToDAGISel::SelectWMMAVISrc (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> In, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>, definition at line 3505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Mode {#ac58cedbae2aa64c6bf90190d3784882d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIModeRegisterDefaults llvm::AMDGPUDAGToDAGISel::Mode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>.</p>

</div>
</div>

### Subtarget {#a345b4e58031e7492f38fac7ebb21ec21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget* llvm::AMDGPUDAGToDAGISel::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp">AMDGPUISelDAGToDAG.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-h">AMDGPUISelDAGToDAG.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
