---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ARCInstrInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-h">ARCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arc-h">ARC.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcmachinefunctioninfo-h">ARCMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcsubtarget-h">ARCSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinfo-h">MCTargetDesc/ARCInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">llvm/CodeGen/MachineMemOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "ARCGenInstrInfo.inc"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AddrIncType { <a href="#a5d6e37f3d036496321824378223ad718">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TSFlagsConstants { <a href="#a0e0724b35de88455dcc04b25058650fd">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab72d7b0e806780e0df6f6710f2a0c82a">isZeroImm</a> (const MachineOperand &amp;Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0daf17b9f0011e9a4c4c8f00644c12">isLoad</a> (int Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5329eaa9a958adfa2c8de4d24e16cc">isStore</a> (int Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006">ARCCC::CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d13488c30e49c98625c597b66abb4d4">getOppositeBranchCondition</a> (ARCCC::CondCode CC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the inverse of passed condition, i.e. turning COND_E to COND_NE. <a href="#a8d13488c30e49c98625c597b66abb4d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cc0df073e34014a2a8ad7f1919202d1">isUncondBranchOpcode</a> (int Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c6eb198e4a6fb0f4eb4dc6341f5c4ad">isCondBranchOpcode</a> (int Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb4b12597a4bc4f3910b449e77b3f825">isJumpOpcode</a> (int Opc)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d99008fb7e5cdc4774786d0743a2c4f">GET_INSTRINFO_CTOR_DTOR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"arc-inst-info"</td>
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


<div class="doxySectionDef">

## Enumerations

### AddrIncType {#a5d6e37f3d036496321824378223ad718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum AddrIncType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoAddInc<a id="a5d6e37f3d036496321824378223ad718af8f235a4b49b25c5d298cfcc92d0841b"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PreInc<a id="a5d6e37f3d036496321824378223ad718a69f3ed9414e01b94674fac41f27fb95b"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PostInc<a id="a5d6e37f3d036496321824378223ad718a1673ee57164ca23d9545b629b55e08d2"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Scaled<a id="a5d6e37f3d036496321824378223ad718a8009351707fa969013ab5d9126bab03e"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp">ARCInstrInfo.cpp</a>.</p>

</div>
</div>

### TSFlagsConstants {#a0e0724b35de88455dcc04b25058650fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum TSFlagsConstants </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TSF_AddrModeOff<a id="a0e0724b35de88455dcc04b25058650fdab8d6098b0b450549d5ea90f74451a1b2"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TSF_AddModeMask<a id="a0e0724b35de88455dcc04b25058650fda3b560020ab7e6ae260cdc4d97d7e0463"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp">ARCInstrInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getOppositeBranchCondition() {#a8d13488c30e49c98625c597b66abb4d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARCCC::CondCode getOppositeBranchCondition (<a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006">ARCCC::CondCode</a> CC)</td>
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

<p>Return the inverse of passed condition, i.e. turning COND_E to COND_NE.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp">ARCInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a06424d16ad2a930de1f57d6b564cbc1b">llvm::ARCCC::EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a815eaffff57498d8c26b03fb3510dec6">llvm::ARCCC::GE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006ad55c9ceb8b27f401f5d82c0ebd20d6be">llvm::ARCCC::GT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006ad072d903ed389a04331251bbbc069524">llvm::ARCCC::HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a4c1cec33829d627ebeeb767b3d2b2c36">llvm::ARCCC::HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006aadc05bce3350700bee41e8525d23acc1">llvm::ARCCC::LE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a01b7f88b89f69e354f814793602b2256">llvm::ARCCC::LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006ae0363d765d2cb82180e8db9332366d2b">llvm::ARCCC::LS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a1695055effb07e0e8e69ff10aff4756b">llvm::ARCCC::LT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a913770d7f2c3565cff9146efa0621b8d">llvm::ARCCC::NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a799e707160aac5ed5107d38155b69d69">llvm::ARCCC::NZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a6a9fb8f59362e12960359e5a55f777c8">llvm::ARCCC::VC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a8172a107e0d48ee61e1f7631ad071c37">llvm::ARCCC::VS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006aceb189306b941666e679bf556207c1e4">llvm::ARCCC::Z</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#ae4cfb4f973d03e59587f0fb1c078e08d">llvm::ARCInstrInfo::reverseBranchCondition</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a8b2d06a5adb70f217a01910738bcb044">llvm::RISCVInstrInfo::reverseBranchCondition</a>.</p>

</div>
</div>

### isCondBranchOpcode() {#a5c6eb198e4a6fb0f4eb4dc6341f5c4ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCondBranchOpcode (int Opc)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp">ARCInstrInfo.cpp</a>.</p>

</div>
</div>

### isJumpOpcode() {#afb4b12597a4bc4f3910b449e77b3f825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isJumpOpcode (int Opc)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp">ARCInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a5a2e063255e7f9ff6cbfab2dfcfeb5a1">llvm::ARCInstrInfo::analyzeBranch</a>.</p>

</div>
</div>

### isLoad() {#a6b0daf17b9f0011e9a4c4c8f00644c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isLoad (int Opcode)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp">ARCInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#ac1bfd4ec3ab2303f1f8e71e2314ed668">DecodeMem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#acf4b8b3fca77d10e530e004d716021b9">DecodeMemAS</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#afe71af95c1e795a56d13e488898d58f5">llvm::PPCHazardRecognizer970::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa5c238ef927795521aeb232b467a6cd1">llvm::MemoryDependenceResults::getDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#a930f5688f2bff088096f72a68000c94e">llvm::PPCHazardRecognizer970::getHazardType</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#ab46fb372d99dc0562d09cfdcd041d5ab">llvm::MemoryDependenceResults::getNonLocalPointerDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a3928622cecd7b474f1c959b50897fae4">llvm::MemoryDependenceResults::getPointerDependencyFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a2f2f5f9e9837f7f9010c8a26cbd04f6f">llvm::MemoryDependenceResults::getPointerDependencyFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a7e08a461c58c82e0564d2cd25c6d9990">llvm::PPCTargetLowering::getPreIndexedAddressParts</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a9bee3fb06f5a904f56f15b52fd71826b">llvm::ARCInstrInfo::isLoadFromStackSlot</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### isStore() {#aab5329eaa9a958adfa2c8de4d24e16cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isStore (int Opcode)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp">ARCInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa4c17cc7964441daaea8b4bee6c18f93">CombineBaseUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#afe71af95c1e795a56d13e488898d58f5">llvm::PPCHazardRecognizer970::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#a930f5688f2bff088096f72a68000c94e">llvm::PPCHazardRecognizer970::getHazardType</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a57a4c9ec10c3c1a796f9ca3363c5045f">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowOriginPtr</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a7480612cfe31fd07e5d1d5d45bf3c3b4">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowOriginPtrKernel</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#ad271462ad31f06423e02d373ce962cf1">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowOriginPtrKernelNoVec</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a530835407e7ef5968d1c039b9ca79fe2">llvm::ARCInstrInfo::isStoreToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a97d0066eae87ce228a58774409c88425">llvm::ARMInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a61d01252826372b1ec3aefc12e0c23d1">selectLoadStoreUIOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizer/#ac3d2e90831d5194eb239b21221205b59">anonymous{MemorySanitizer.cpp}::MemorySanitizer::VarArgGenericHelper</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### isUncondBranchOpcode() {#a4cc0df073e34014a2a8ad7f1919202d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isUncondBranchOpcode (int Opc)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp">ARCInstrInfo.cpp</a>.</p>

</div>
</div>

### isZeroImm() {#ab72d7b0e806780e0df6f6710f2a0c82a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isZeroImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp">ARCInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a9bee3fb06f5a904f56f15b52fd71826b">llvm::ARCInstrInfo::isLoadFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a72fff6a539f09169ea02ba7f91c6536b">llvm::XCoreInstrInfo::isLoadFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a530835407e7ef5968d1c039b9ca79fe2">llvm::ARCInstrInfo::isStoreToStackSlot</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a7713292f6f9820ba13b76dad96270343">llvm::XCoreInstrInfo::isStoreToStackSlot</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"arc-inst-info"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp">ARCInstrInfo.cpp</a>.</p>

</div>
</div>

### GET\_INSTRINFO\_CTOR\_DTOR {#a5d99008fb7e5cdc4774786d0743a2c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_CTOR_DTOR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp">ARCInstrInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
