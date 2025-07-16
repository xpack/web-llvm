---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/systemzselectiondaginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SystemZSelectionDAGInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SystemZSelectionDAGInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">Target/SystemZ/SystemZSelectionDAGInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can subclass this to parameterize the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> lowering and instruction selection process. <a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53d68091326d36cd635904e77346c37c">SystemZSelectionDAGInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8168ae8efe34024194a776e87860081">isTargetMemoryOpcode</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a node with the given target-specific opcode has a memory operand. <a href="#af8168ae8efe34024194a776e87860081">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a867b83a990ab9fa0f43a7130bf6136af">isTargetStrictFPOpcode</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a node with the given target-specific opcode has strict floating-point semantics. <a href="#a867b83a990ab9fa0f43a7130bf6136af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea4188595d6c22a178c85d5b67971dd2">EmitTargetCodeForMemcpy</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Chain, SDValue Dst, SDValue Src, SDValue Size, Align Alignment, bool IsVolatile, bool AlwaysInline, MachinePointerInfo DstPtrInfo, MachinePointerInfo SrcPtrInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific code that performs a memcpy. <a href="#aea4188595d6c22a178c85d5b67971dd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13c6fa8f5d32e17789ce621593b356e0">EmitTargetCodeForMemset</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Chain, SDValue Dst, SDValue Byte, SDValue Size, Align Alignment, bool IsVolatile, bool AlwaysInline, MachinePointerInfo DstPtrInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific code that performs a memset. <a href="#a13c6fa8f5d32e17789ce621593b356e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd52870827d3865048a34de253e7890e">EmitTargetCodeForMemcmp</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Chain, SDValue Src1, SDValue Src2, SDValue Size, MachinePointerInfo Op1PtrInfo, MachinePointerInfo Op2PtrInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific code that performs a memcmp/bcmp, in cases where that is faster than a libcall. <a href="#afd52870827d3865048a34de253e7890e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1451ff2e7eeaaf042e0e2b557bcaf242">EmitTargetCodeForMemchr</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Chain, SDValue Src, SDValue Char, SDValue Length, MachinePointerInfo SrcPtrInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific code that performs a memchr, in cases where that is faster than a libcall. <a href="#a1451ff2e7eeaaf042e0e2b557bcaf242">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adec77c8a24d9d1b33fc560cf51556661">EmitTargetCodeForStrcpy</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Chain, SDValue Dest, SDValue Src, MachinePointerInfo DestPtrInfo, MachinePointerInfo SrcPtrInfo, bool isStpcpy) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific code that performs a strcpy or stpcpy, in cases where that is faster than a libcall. <a href="#adec77c8a24d9d1b33fc560cf51556661">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cb10805f70577c5734b2510dd285616">EmitTargetCodeForStrcmp</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Chain, SDValue Src1, SDValue Src2, MachinePointerInfo Op1PtrInfo, MachinePointerInfo Op2PtrInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific code that performs a strcmp, in cases where that is faster than a libcall. <a href="#a5cb10805f70577c5734b2510dd285616">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d841a39cc0b8f470a8347bb79d45ec7">EmitTargetCodeForStrlen</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Chain, SDValue Src, MachinePointerInfo SrcPtrInfo) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f20163a74746a3592d5a323eb28129f">EmitTargetCodeForStrnlen</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Chain, SDValue Src, SDValue MaxLength, MachinePointerInfo SrcPtrInfo) const override</td>
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


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">SystemZSelectionDAGInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SystemZSelectionDAGInfo() {#a53d68091326d36cd635904e77346c37c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SystemZSelectionDAGInfo::SystemZSelectionDAGInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">SystemZSelectionDAGInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### EmitTargetCodeForMemchr() {#a1451ff2e7eeaaf042e0e2b557bcaf242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; SystemZSelectionDAGInfo::EmitTargetCodeForMemchr (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Char, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Length, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> SrcPtrInfo)</td>
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

<p>Emit target-specific code that performs a memchr, in cases where that is faster than a libcall.</p>


<p>The first returned <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> is the result of the memchr and the second is the chain. Both SDValues can be null if a normal libcall should be used.</p>


<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">SystemZSelectionDAGInfo.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp">SystemZSelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a1255c0721c391f699043d377fad5f385">llvm::SystemZ::CCMASK_SRST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a4bdd1364943002f89453bf957b7ec5da">llvm::SystemZ::CCMASK_SRST_FOUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad0c6f059b29535f2c790d1c4f92b7a93">llvm::SelectionDAG::getZExtOrTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7ea3dc1a332d83e53ff1697d24420fe81dd">llvm::SystemZISD::SEARCH_STRING</a> and <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7eaad70b711d89890454ad6cbae8669f02f">llvm::SystemZISD::SELECT_CCMASK</a>.</p>

</div>
</div>

### EmitTargetCodeForMemcmp() {#afd52870827d3865048a34de253e7890e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; SystemZSelectionDAGInfo::EmitTargetCodeForMemcmp (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op2, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op3, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> Op1PtrInfo, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> Op2PtrInfo)</td>
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

<p>Emit target-specific code that performs a memcmp/bcmp, in cases where that is faster than a libcall.</p>


<p>The first returned <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> is the result of the memcmp and the second is the chain. Both SDValues can be null if a normal libcall should be used.</p>


<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">SystemZSelectionDAGInfo.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp">SystemZSelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp/#ab7e94059fa0b2ff2d378604a55e4f893">addIPMSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7ea4bad211a26808864fb8f06f4e7d52035">llvm::SystemZISD::CLC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp/#ac6b884feaadf8cda62bf3e49a55c08e5">emitMemMemImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp/#a4b03c2924830e50b94c915849d427475">emitMemMemReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### EmitTargetCodeForMemcpy() {#aea4188595d6c22a178c85d5b67971dd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SystemZSelectionDAGInfo::EmitTargetCodeForMemcpy (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op2, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op3, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool isVolatile, bool AlwaysInline, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> DstPtrInfo, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> SrcPtrInfo)</td>
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

<p>Emit target-specific code that performs a memcpy.</p>


<p>This can be used by targets to provide code sequences for cases that don't fit the target's parameters for simple loads/stores and can be more efficient than using a library call. This function can return a null <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if the target declines to use custom code and a different lowering strategy should be used.</p>


<p>If AlwaysInline is true, the size is constant and the target should not emit any calls and is strongly encouraged to attempt to emit inline code even if it is beyond the usual threshold because this intrinsic is being expanded in a place where calls are not feasible (e.g. within the prologue for another call). If the target chooses to decline an AlwaysInline request here, legalize will resort to using simple loads and stores.</p>


<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">SystemZSelectionDAGInfo.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp">SystemZSelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp/#ac6b884feaadf8cda62bf3e49a55c08e5">emitMemMemImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp/#a4b03c2924830e50b94c915849d427475">emitMemMemReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7ead36cb2203fdbacca879ada09db0b0a85">llvm::SystemZISD::MVC</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### EmitTargetCodeForMemset() {#a13c6fa8f5d32e17789ce621593b356e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SystemZSelectionDAGInfo::EmitTargetCodeForMemset (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op2, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op3, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool isVolatile, bool AlwaysInline, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> DstPtrInfo)</td>
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

<p>Emit target-specific code that performs a memset.</p>


<p>This can be used by targets to provide code sequences for cases that don't fit the target's parameters for simple stores and can be more efficient than using a library call. This function can return a null <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if the target declines to use custom code and a different lowering strategy should be used. Note that if AlwaysInline is true the function has to return a valid <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>.</p>


<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">SystemZSelectionDAGInfo.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp">SystemZSelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae22967d11b695d268992470debfae4b2">llvm::bit_floor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp/#ac6b884feaadf8cda62bf3e49a55c08e5">emitMemMemImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp/#a4b03c2924830e50b94c915849d427475">emitMemMemReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aae7e97fa59261cc890aa2359971adfd4">llvm::SelectionDAG::getAnyExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a9459055a98e20980521289e8d20fcc7e">llvm::MachinePointerInfo::getWithOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7eae2c528e66350d03bf0fe7e2d40ab62cf">llvm::SystemZISD::MEMSET_MVC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp/#abc6d4a4dd3151e287e14385d00939be9">memsetStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7ea9cac76531875c59c8d879507bc72e282">llvm::SystemZISD::XC</a>.</p>

</div>
</div>

### EmitTargetCodeForStrcmp() {#a5cb10805f70577c5734b2510dd285616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; SystemZSelectionDAGInfo::EmitTargetCodeForStrcmp (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op2, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> Op1PtrInfo, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> Op2PtrInfo)</td>
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

<p>Emit target-specific code that performs a strcmp, in cases where that is faster than a libcall.</p>


<p>The first returned <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> is the result of the strcmp and the second is the chain. Both SDValues can be null if a normal libcall should be used.</p>


<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">SystemZSelectionDAGInfo.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp">SystemZSelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp/#ab7e94059fa0b2ff2d378604a55e4f893">addIPMSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a> and <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7ea911be528010d96a9935f856bd0bc4beb">llvm::SystemZISD::STRCMP</a>.</p>

</div>
</div>

### EmitTargetCodeForStrcpy() {#adec77c8a24d9d1b33fc560cf51556661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; SystemZSelectionDAGInfo::EmitTargetCodeForStrcpy (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Dest, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Src, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> DestPtrInfo, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> SrcPtrInfo, bool isStpcpy)</td>
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

<p>Emit target-specific code that performs a strcpy or stpcpy, in cases where that is faster than a libcall.</p>


<p>The first returned <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> is the result of the copy (the start of the destination string for strcpy, a pointer to the null terminator for stpcpy) and the second is the chain. Both SDValues can be null if a normal libcall should be used.</p>


<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">SystemZSelectionDAGInfo.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp">SystemZSelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a> and <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7eaafca0314124e4aa31b2d9c49a7f582d5">llvm::SystemZISD::STPCPY</a>.</p>

</div>
</div>

### EmitTargetCodeForStrlen() {#a2d841a39cc0b8f470a8347bb79d45ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; SystemZSelectionDAGInfo::EmitTargetCodeForStrlen (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Src, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> SrcPtrInfo)</td>
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



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">SystemZSelectionDAGInfo.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp">SystemZSelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp/#a67b6a4fb96a24958d4bf8e9ebcc5719a">getBoundedStrlen</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>.</p>

</div>
</div>

### EmitTargetCodeForStrnlen() {#a6f20163a74746a3592d5a323eb28129f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; SystemZSelectionDAGInfo::EmitTargetCodeForStrnlen (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> MaxLength, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> SrcPtrInfo)</td>
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



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">SystemZSelectionDAGInfo.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp">SystemZSelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp/#a67b6a4fb96a24958d4bf8e9ebcc5719a">getBoundedStrlen</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad0c6f059b29535f2c790d1c4f92b7a93">llvm::SelectionDAG::getZExtOrTrunc</a>.</p>

</div>
</div>

### isTargetMemoryOpcode() {#af8168ae8efe34024194a776e87860081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZSelectionDAGInfo::isTargetMemoryOpcode (unsigned Opcode)</td>
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

<p>Returns true if a node with the given target-specific opcode has a memory operand.</p>


<p>Nodes with such opcodes can only be created with <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">SelectionDAG::getMemIntrinsicNode</a></span>.</p>


<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">SystemZSelectionDAGInfo.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp">SystemZSelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7ea150e711c3247b64e333f71c3ae7447bb">llvm::SystemZISD::FIRST_MEMORY_OPCODE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7ea1da234b421f77ebf1ef82eb64c9719d1">llvm::SystemZISD::LAST_MEMORY_OPCODE</a>.</p>

</div>
</div>

### isTargetStrictFPOpcode() {#a867b83a990ab9fa0f43a7130bf6136af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZSelectionDAGInfo::isTargetStrictFPOpcode (unsigned Opcode)</td>
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

<p>Returns true if a node with the given target-specific opcode has strict floating-point semantics.</p>

<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">SystemZSelectionDAGInfo.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp">SystemZSelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7ea7f1cb1c62d0c00979a0a710510b1ff1a">llvm::SystemZISD::FIRST_STRICTFP_OPCODE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7ead16915efb4b00c9c30e3077ede3ec40f">llvm::SystemZISD::LAST_STRICTFP_OPCODE</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp">SystemZSelectionDAGInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-h">SystemZSelectionDAGInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
