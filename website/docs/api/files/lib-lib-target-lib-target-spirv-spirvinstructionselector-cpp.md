---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SPIRVInstructionSelector.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvbaseinfo-h">MCTargetDesc/SPIRVBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmctargetdesc-h">MCTargetDesc/SPIRVMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirv-h">SPIRV.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstrinfo-h">SPIRVInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvregisterbankinfo-h">SPIRVRegisterBankInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvregisterinfo-h">SPIRVRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-h">SPIRVTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvutils-h">SPIRVUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutorimpl-h">llvm/CodeGen/GlobalISel/GIMatchTableExecutorImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">llvm/CodeGen/GlobalISel/GenericMachineInstrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/instructionselector-h">llvm/CodeGen/GlobalISel/InstructionSelector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">llvm/CodeGen/MachineModuleInfoImpls.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">llvm/CodeGen/Register.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetopcodes-h">llvm/CodeGen/TargetOpcodes.h</a>"
#include "llvm/IR/IntrinsicsSPIRV.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "SPIRVGenGlobalISel.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-spirvinstructionselector-cpp-">anonymous{SPIRVInstructionSelector.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector">SPIRVInstructionSelector</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52c68b176e39f1fe9025ad7d6082b4b6">ExtInstList</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; std::pair&lt; SPIRV::InstructionSet::InstructionSet, uint32_t &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> (const MachineOperand &amp;MO, MachineRegisterInfo *MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9f91a5fc5778c118de4960dae29807">isTypeFoldingSupported</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af977af9be6319c90e0918cb38b4f045b">isDead</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f96d0dcf6fbd53defac3a80db42f2e4">mayApplyGenericSelection</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c62fedeccc54762c292a1a19fa7252b">addMemoryOperands</a> (MachineMemOperand *MemOp, MachineInstrBuilder &amp;MIB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33cabf82e98c7c5f94d04a12179356e3">addMemoryOperands</a> (uint64_t Flags, MachineInstrBuilder &amp;MIB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9801c4af4df2ad054da26d6c876c92f">isGenericCastablePtr</a> (SPIRV::StorageClass::StorageClass SC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a232376a756ffa704f61ea3ab09f696e6">isUSMStorageClass</a> (SPIRV::StorageClass::StorageClass SC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b733b024e23883f2c704c28b8ef2c2">isASCastInGVar</a> (MachineRegisterInfo *MRI, Register ResVReg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43f534628464a9944763e34e9a830791">getFCmpOpcode</a> (unsigned PredNum)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa54336ed85b633c9d2ace35c4b5f3ed6">getICmpOpcode</a> (unsigned PredNum)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0488c2d591bd660b539e54764c6099c">getPtrCmpOpcode</a> (unsigned Pred)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca3628f64d7aba96618cb3fc8f7fe70">getBoolCmpOpcode</a> (unsigned PredNum)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bdf014154b31cd5813672cbcd3af604">getZeroFP</a> (const Type *LLVMFloatTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d270f02c1f9186ea7961768be1269a7">getOneFP</a> (const Type *LLVMFloatTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af999ef1c23f3644af392a2b4633fa8f7">getArrayComponentCount</a> (MachineRegisterInfo *MRI, const SPIRVType *ResType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa737e66804d935143b89db74d5646610">isConstReg</a> (MachineRegisterInfo *MRI, SPIRVType *OpDef, SmallPtrSet&lt; SPIRVType *, 4 &gt; &amp;Visited)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0ba5a0fd02614fad2e3f1254d5d91c1">isConstReg</a> (MachineRegisterInfo *MRI, Register OpReg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac962fea3028517b39dcd1f4cff0c0112">foldImm</a> (const MachineOperand &amp;MO, MachineRegisterInfo *MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"spirv-isel"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aa5a7608a0e489065b260a1ec245b82">GET_GLOBALISEL_PREDICATE_BITSET</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e198bb37135fbb2ecffb49ce588dfaa">GET_GLOBALISEL_PREDICATES_DECL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ae8a4d3c9110554465fec97831b1dfd">GET_GLOBALISEL_TEMPORARIES_DECL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae706a3af700f8ed432e93918d7601d5a">GET_GLOBALISEL_IMPL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab538c256c3204b950075744d5b2b16">GET_GLOBALISEL_PREDICATES_INIT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cd36a579f079f7f4506d9d097b2f0a8">GET_GLOBALISEL_TEMPORARIES_INIT</a></td>
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

## Typedefs

### ExtInstList {#a52c68b176e39f1fe9025ad7d6082b4b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ExtInstList = 
    std::vector&lt;std::pair&lt;SPIRV::InstructionSet::InstructionSet, uint32_t&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addMemoryOperands() {#a3c62fedeccc54762c292a1a19fa7252b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addMemoryOperands (<a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MemOp, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB)</td>
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



<p>Definition at line 1022 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>.</p>

</div>
</div>

### addMemoryOperands() {#a33cabf82e98c7c5f94d04a12179356e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addMemoryOperands (uint64_t Flags, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB)</td>
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



<p>Definition at line 1039 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda8d09c51969b0954512ed65ee26551081">llvm::MachineMemOperand::MONonTemporal</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8">llvm::MachineMemOperand::MOVolatile</a>.</p>

</div>
</div>

### foldImm() {#ac962fea3028517b39dcd1f4cff0c0112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t foldImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
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



<p>Definition at line 2730 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a29e05cd075864928ae65e1751fdc346e">llvm::MachineOperand::getCImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### getArrayComponentCount() {#af999ef1c23f3644af392a2b4633fa8f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getArrayComponentCount (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * ResType)</td>
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



<p>Definition at line 2242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a29e05cd075864928ae65e1751fdc346e">llvm::MachineOperand::getCImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#af7e1934ed72a405ef073ea5f9bbe828e">llvm::ConstantInt::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getBoolCmpOpcode() {#a9ca3628f64d7aba96618cb3fc8f7fe70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getBoolCmpOpcode (unsigned PredNum)</td>
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



<p>Definition at line 1706 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getFCmpOpcode() {#a43f534628464a9944763e34e9a830791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getFCmpOpcode (unsigned PredNum)</td>
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



<p>Definition at line 1630 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">llvm::CmpInst::FCMP_OEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">llvm::CmpInst::FCMP_OGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">llvm::CmpInst::FCMP_OGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">llvm::CmpInst::FCMP_OLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">llvm::CmpInst::FCMP_OLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">llvm::CmpInst::FCMP_ONE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">llvm::CmpInst::FCMP_ORD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">llvm::CmpInst::FCMP_UEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">llvm::CmpInst::FCMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">llvm::CmpInst::FCMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">llvm::CmpInst::FCMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">llvm::CmpInst::FCMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">llvm::CmpInst::FCMP_UNE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getICmpOpcode() {#aa54336ed85b633c9d2ace35c4b5f3ed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getICmpOpcode (unsigned PredNum)</td>
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



<p>Definition at line 1666 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getOneFP() {#a1d270f02c1f9186ea7961768be1269a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat getOneFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LLVMFloatTy)</td>
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



<p>Definition at line 1732 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a7f8802ce4f0a7839abb4c836cb52138a">llvm::APFloat::getOne</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac7b0ed5c6d30bad74769c6e87ab0edb8">llvm::Type::getTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa301c3a4cc2bfd399628cfd473f383ff9">llvm::Type::HalfTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86415bb448a78ef1fed893f9eb0f5d06">llvm::APFloatBase::IEEEhalf</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a0c5765e9acba977f6e462c2917276d8f">llvm::APFloatBase::IEEEsingle</a>.</p>

</div>
</div>

### getPtrCmpOpcode() {#af0488c2d591bd660b539e54764c6099c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getPtrCmpOpcode (unsigned Pred)</td>
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



<p>Definition at line 1694 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getZeroFP() {#a3bdf014154b31cd5813672cbcd3af604}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat getZeroFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LLVMFloatTy)</td>
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



<p>Definition at line 1718 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac7b0ed5c6d30bad74769c6e87ab0edb8">llvm::Type::getTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af591f8d18d0d9773192a0ffcca41796e">llvm::APFloat::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa301c3a4cc2bfd399628cfd473f383ff9">llvm::Type::HalfTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86415bb448a78ef1fed893f9eb0f5d06">llvm::APFloatBase::IEEEhalf</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a0c5765e9acba977f6e462c2917276d8f">llvm::APFloatBase::IEEEsingle</a>.</p>

</div>
</div>

### isASCastInGVar() {#a28b733b024e23883f2c704c28b8ef2c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isASCastInGVar (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ResVReg)</td>
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



<p>Definition at line 1476 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### isConstReg() {#aa737e66804d935143b89db74d5646610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isConstReg (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * OpDef, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> *, 4 &gt; &amp; Visited)</td>
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



<p>Definition at line 2260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9839b7e1d8811ea9d41f901ab6a0f23b">llvm::MachineInstr::getNumExplicitDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#aa737e66804d935143b89db74d5646610">isConstReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#ac0ba5a0fd02614fad2e3f1254d5d91c1">isConstReg</a> and <a href="#aa737e66804d935143b89db74d5646610">isConstReg</a>.</p>

</div>
</div>

### isConstReg() {#ac0ba5a0fd02614fad2e3f1254d5d91c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isConstReg (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OpReg)</td>
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



<p>Definition at line 2300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>References <a href="#aa737e66804d935143b89db74d5646610">isConstReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### isDead() {#af977af9be6319c90e0918cb38b4f045b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isDead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a4a8b881c0637c6f85c3eb6891abcfab4">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac185ac23ce865ff964fd0999a1bc346d">llvm::t1CondCodeOp</a> and <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a1c0f17f40e0399c6d151a50e99797e58">llvm::TailDuplicator::tailDuplicateAndUpdate</a>.</p>

</div>
</div>

### isGenericCastablePtr() {#ad9801c4af4df2ad054da26d6c876c92f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isGenericCastablePtr (SPIRV::StorageClass::StorageClass SC)</td>
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



<p>Definition at line 1454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>

</div>
</div>

### isImm() {#a6fe0144adffd7bad0aeca668f4468b28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
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



<p>Definition at line 2719 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a29b2705aeee49d31d232c5ab440f7877">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode3Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aeca538a61ece736dfa6ca68bfcebb401">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode5FP16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a6b2100e3595ebc052f71501e05bf9ef4">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode5Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af6a434a23522485bf0d986faf12ee9f8">anonymous{ARMAsmParser.cpp}::ARMOperand::addAdrLabelOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a72b37da283ebf9ecc9ef3b8468b9569d">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addFPImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a6dff62db50ccdfe98aff9cb203745a66">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemImm12OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9fb937acd028a5bf796c672a0d6c5f75">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemImm7s4OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a4301f3a2bb78f6f20862ba128f6f52f5">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemImm8s4OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9f7334fe4a405366c2e73604c925921f">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemUImm12OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a540ca19122e726ab4ca0c7a2f8a38ca8">anonymous{ARMAsmParser.cpp}::ARMOperand::addModImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a3be9193f261a65d4f60d619cd6caec18">anonymous{MipsAsmParser.cpp}::MipsOperand::addSImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a31a9eafb0a15b40afecf4445f06dc73e">anonymous{ARMAsmParser.cpp}::ARMOperand::addThumbMemPCOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#afc44730a9c17cc064aba9a4c2212f9da">anonymous{MipsAsmParser.cpp}::MipsOperand::addUImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a9b60466dac10eaf9d8a8b4f955b77b24">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingConstOffsetBackward</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a397a7d129e95cde7da2f0f4a33c82fd9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingInsn</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a6b4a3c0105d0c1835725eaa33867b526">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ae68bfb13f71bdc4b9daceb16565d5764">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode3OffsetOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a2d0dda09f20d0ebce689e4a66fb95336">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode3OpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a9be6a3c0e7c06fd610c52d9654ee3f59">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a1d808348ce3cfa75d655bb52da648a13">anonymous{ARMAsmParser.cpp}::ARMOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonhardwareloops-cpp-/countvalue/#a93eed61b595108fc5388cfacd905582c">anonymous{HexagonHardwareLoops.cpp}::CountValue::getImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a39f9673926289aecff3b7f94bdc3c0bb">anonymous{LanaiAsmParser.cpp}::LanaiOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a9f901d3b6a8c3b686d2f3408de0fb817">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getImmTy</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a83c5e95fb85aaef96207fc9e9ddfccc0">anonymous{AArch64AsmParser.cpp}::AArch64Operand::getShiftedVal</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a76f8dfae3796fd187aebe3f8f60643ec">llvm::HexagonInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a2bc4c29964a242a574a8e9b78df0bb31">llvm::RISCVInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad73e9b3e610bd8cac60e740a61fcf5bf">llvm::SIInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a8b7067629b6a083fe938e1e73d0b505b">llvm::VEInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad88bfb92ca2f7d419adc7e6645406a7c">llvm::SIInstrInfo::insertVectorSelect</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a95fb3115e000423d80403a44c72ee69e">anonymous{ARMAsmParser.cpp}::ARMOperand::isAddrMode3</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad3f46c5bd61fd5e5d5000d1ec84d2425">anonymous{ARMAsmParser.cpp}::ARMOperand::isAddrMode5</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad75e4458c88b2509c1766a84ce8073b4">anonymous{ARMAsmParser.cpp}::ARMOperand::isAddrMode5FP16</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ae40e6dd1a68e37d4348480f3c10858f8">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isAddSubImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aa1ceb39d04bc1c073d4dacdf7b5a6f04">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isAddSubImmNeg</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a80247423cff6ce10b85e83fe46850605">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isAdrLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a89dae2ca2d9a35776687bc7d8a49ce32">anonymous{ARMAsmParser.cpp}::ARMOperand::isAdrLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac4bea02bcb8b770deb2d6ea439c3f642">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isAdrpLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aaf6398f5fb1d5043b1f3da6149770bb4">anonymous{ARMAsmParser.cpp}::ARMOperand::isAM2OffsetImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a808a7e76a88a099fd53a082f96778acc">anonymous{ARMAsmParser.cpp}::ARMOperand::isAM3Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#aa1d6c1b96ed1220751cfd666e3b79a84">anonymous{MipsAsmParser.cpp}::MipsOperand::isAnyImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a08ea1066c3f3f6b30e2ab53b39054ec3">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isAnyReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad327a5e70b7461abf61f7e82094cb26b">anonymous{ARMAsmParser.cpp}::ARMOperand::isARMBranchTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a511c891e4ab14d75209124f166ba47dc">llvm::LoongArchInstrInfo::isAsCheapAsAMove</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a658bdb32cfdf7a3051a4221c15fc441f">llvm::RISCVInstrInfo::isAsCheapAsAMove</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a0f7cfaa1c472b36c995d6f95d9321e0a">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isBareSimmNLsb0</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a833cc28225e638366be9525d746e76c8">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isBareSymbol</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#ac8502fc60d43c787f067cf0a3d3aed2e">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isBareSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a6502fd15601fbefa6de9a3c3f2a15a0d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isBranchTarget</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#ab6b0c7909cd1c59c0450d9d1a8493bc9">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isBrImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a5042f1f9092dd0215e831229e55f8ebd">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isCallSymbol</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#af4bb149e137d775e094dac3c27fa2a12">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isCallTarget</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#a3bada0ae3fc1b0e8579ff1d4aa16fbde">anonymous{SparcAsmParser.cpp}::SparcOperand::isCallTarget</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#adfbb6e70817ddf44c690c812da1d300c">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isCLUIImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a512f38d8a6227cc7ebd485d3d46bc365">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isComplexRotation</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac5921ea14de5a5eba689134ae3c1f3d6">anonymous{ARMAsmParser.cpp}::ARMOperand::isComplexRotation</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#ae57fbd0e584ec2382b9940e01e19d768">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isCondCode</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfasmparser-cpp-/bpfoperand/#a926f5e3272131dc9492854e46d0581d5">anonymous{BPFAsmParser.cpp}::BPFOperand::isConstantImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a7a39457e87df232ee02fa8117ff636a3">anonymous{MipsAsmParser.cpp}::MipsOperand::isConstantImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#a9cb07869c134c15fbc0d6b48d827d0e7">anonymous{CSKYAsmParser.cpp}::CSKYOperand::isCSKYSymbol</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#a97a44db62cf1fc6e69f073dbf1e15c63">anonymous{CSKYAsmParser.cpp}::CSKYOperand::isExtImm6</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae5c3939a86ea8f12a6f26bda5057bb17">anonymous{ARMAsmParser.cpp}::ARMOperand::isFPImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#aebf98c08c7ee4d1244bbc1b9b89cd0ea">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isHiImm16</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a7a980e5bb4840109e1822c062cbfafa7">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isHiImm16And</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#adacd5aa310dc9ba5ba701d3e9adf11d8">anonymous{ARMAsmParser.cpp}::ARMOperand::isImm0_255Expr</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aca4a7cfc113efc52c1bd88608bb46ce8">anonymous{ARMAsmParser.cpp}::ARMOperand::isImm0_4095Neg</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a0d5b23b7b9ece3d436055bf02ebdc6c6">anonymous{ARMAsmParser.cpp}::ARMOperand::isImm0_508s4Neg</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a940623ec03dda9b46111d1ce1de1f848">anonymous{ARMAsmParser.cpp}::ARMOperand::isImm0_65535Expr</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#acb23248dfc6a00019f3f78d74a2b45b1">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isImm10</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae706f8783fb65c06115d47939e72a5a8">anonymous{ARMAsmParser.cpp}::ARMOperand::isImm256_65535Expr</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a32303eaaa310fc67f31e35bb0dae5aca">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isImm64</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrasmparser-cpp-/avroperand/#abda9653d5e03cbb948fc192863b69c14">anonymous{AVRAsmParser.cpp}::AVROperand::isImmCom8</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a31dc6d11a8c07395e1d0c38201df46a6">anonymous{ARMAsmParser.cpp}::ARMOperand::isImmediate</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af43a6853b57a2e7207df485bafbb58a1">anonymous{ARMAsmParser.cpp}::ARMOperand::isImmediateS2</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a0f65a3de546118692e8a061eadf55c25">anonymous{ARMAsmParser.cpp}::ARMOperand::isImmediateS4</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a0f6c1755e5ae566a87d87508d3cee9dc">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isImmInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a621031fa88ed3052303329e1d5f55c06">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isImmKindConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5329f028dc85cb9c189110eb90309790">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::IsImmKindLiteral</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#afb66e6b20daee99ff51c1de598caaeda">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::IsImmKindMandatoryLiteral</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#af02a39c837b571df2b4d3712264ca6c2">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isImmModifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a4a18544038561f8c08b8ea6d6da02784">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isImmScaled</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a3aaf84fd1fc76bb95d588ff92b53c672">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isImmShift</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a6a85de263ff8282b792ad4dd660a4016">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isImmTy</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a9a791d6b93becfa0221371554c45053e">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isImmXLenLI</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a45cda9866fff2598a0fbf13fc2c21735">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isImmXLenLI_Restricted</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a1505168c2edbb91f93e80adc33c2d604">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isImmZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab0a66bc2b3ab29a67123bb33aabe4d23">llvm::isLeaMem</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa835d8eaee9aef1f11f4a895ad9c6f3c">anonymous{ARMAsmParser.cpp}::ARMOperand::isLEOffset</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a65b07c2d3b33166b642509347647acee">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isLoadFPImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a9d689d56ccbeb5bad8afd84d615d31b7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isLogicalImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a6f72e54d11a94c9f7ed915863773bd69">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isLoImm16</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#ade0aa7301c37915069aa87297225d180">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isLoImm16And</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a1b070244459f6f10638b5980da6759de">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isLoImm16Signed</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a3debbf507853ab68544bd4ff00a54a33">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isLoImm21</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae2c4f2bc4edc54cc9f2dd5a84e1044de">anonymous{ARMAsmParser.cpp}::ARMOperand::isMemImm12Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a93dfa5f449ee8b6326e972ec99c316b5">anonymous{ARMAsmParser.cpp}::ARMOperand::isMemImm7s4Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a0a7161bb58f9feaedf215ea455a4d2a8">anonymous{ARMAsmParser.cpp}::ARMOperand::isMemImm8s4Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#acb65d960d9bd3f0ca3d49937d12affe4">isMergeableLdStUpdate</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a451967ce905a75f6dab090fe57a854d7">anonymous{ARMAsmParser.cpp}::ARMOperand::isModImmNeg</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a53ec133dbc14254b3990416b05e0e0a8">anonymous{ARMAsmParser.cpp}::ARMOperand::isModImmNot</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a018eb3f34b1fe02b8d60532cf5713ba7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMOVNMovAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a3802559d2c75d983cd9101cd12ac5c57">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMovWSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a21f95622afbe879f8b6fab324bb71a17">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMOVZMovAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a172409c3386b03800e592f0b86285788">anonymous{ARMAsmParser.cpp}::ARMOperand::isMVELongShift</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a60ed4a5e5e1b4d1a5fa7ecf0ada3b8a7">anonymous{ARMAsmParser.cpp}::ARMOperand::isMveSaturateOp</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a10607cb1536041b4d2c0790d63de12e8">anonymous{HexagonAsmParser.cpp}::HexagonOperand::isn1Const</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa4fdbad91ab26ac2fd497f3be95650a6">anonymous{ARMAsmParser.cpp}::ARMOperand::isNEONi16splat</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aabee712524ecfccb59100b57fe6983df">anonymous{ARMAsmParser.cpp}::ARMOperand::isNEONi16splatNot</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae4541e80f428c954ad89047fec95437a">anonymous{ARMAsmParser.cpp}::ARMOperand::isNEONi32splat</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a294a72efdd650ad80e5bb6eec16c8e86">anonymous{ARMAsmParser.cpp}::ARMOperand::isNEONi32splatNot</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac3ef475eb9e5949b2316b9773b011e9e">anonymous{ARMAsmParser.cpp}::ARMOperand::isNEONi32vmov</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a1c2eae039a7cca13ec6b5b69a3c1bcc9">anonymous{ARMAsmParser.cpp}::ARMOperand::isNEONi32vmovNeg</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a49342e5fcda43f3413252fdc9ad3af46">anonymous{ARMAsmParser.cpp}::ARMOperand::isNEONi64splat</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae9dd29bf4c1b27db78f53e164f6c867b">anonymous{ARMAsmParser.cpp}::ARMOperand::isNEONi8splat</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a1e507b7c4a038f8885b6321649b75428">anonymous{ARMAsmParser.cpp}::ARMOperand::isNEONReplicate</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#af8c034383cf8d9c5e91a4ed499c681a9">anonymous{CSKYAsmParser.cpp}::CSKYOperand::isOImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a894f447628559f53d2279c9f9fae0780">llvm::MachineInstr::isOperandSubregIdx</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a4f7622e49d7747dc8b2b9ee2f586a4c9">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isPAuthPCRelLabel16Operand</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a6cc8f9a132e886452920b90a493bc789">anonymous{ARMAsmParser.cpp}::ARMOperand::isPostIdxImm8</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a0b10f3f23c5ad8dc51e905531124699e">anonymous{ARMAsmParser.cpp}::ARMOperand::isPostIdxImm8s4</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a5c08b48ba7dd0e6d64e94f2140f491a3">anonymous{ARMAsmParser.cpp}::ARMOperand::isPowerTwoInRange</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#afd5b91c95fad7d6be2b9fbab33610982">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isPseudoJumpSymbol</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#a5519906431d13fc0c4cff7eb6ff8e809">anonymous{CSKYAsmParser.cpp}::CSKYOperand::isPSRFlag</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#ad2eb5ae7782040f081faca112c8751a4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a33c72952eddffc0cf8c0f301f9f75f9b">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isRnumArg</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a6d26cbdd8ca30a5d98afb728360f974c">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isRnumArg_0_7</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#ae0ad881e8c2b8a510e90ae491602b8a7">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isRnumArg_1_10</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a7d069740c7a0135792efbcfc07dfb574">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isRnumArg_2_14</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#abb2c248605ba77f19a9a643f33dea04a">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isS16Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#ac213ff697b1131d6d24cfcc7573330b3">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isS32Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a423f8aa0726e8d472ed64b404b623561">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isS8Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a492d7fa4373b50525b6e203c5c255792">anonymous{ARMAsmParser.cpp}::ARMOperand::isSetEndImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#a819233efe85cb2e524f7800855308111">anonymous{SparcAsmParser.cpp}::SparcOperand::isShiftAmtImm5</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#afabcf855a51992a0853e5d599ae1139d">anonymous{SparcAsmParser.cpp}::SparcOperand::isShiftAmtImm6</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#adf4e245df27183b762cf8b6b65e2c89d">anonymous{ARMAsmParser.cpp}::ARMOperand::isSignedOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aa1892421b1a924f86a66c28974d47c7d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSIMDImmType10</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#acdbc1487f391e78aa1b636227447099a">anonymous{CSKYAsmParser.cpp}::CSKYOperand::isSImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#ad4bcc7c632ba30551ac54adf68e20a99">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#ae2801af5327dd75bffd8c423a7f270a9">anonymous{MipsAsmParser.cpp}::MipsOperand::isSImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a881b29a20a1d8eb1ff76ee27c79ce4de">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm10Lsb0000NonZero</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#af093f69b028595df33edd1202e0cbc52">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm12</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a58fa85243ecc7987f30746b24e78814e">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm12addlike</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#aa0d77a04edcf0d4f6922b7588617bfdd">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm12Lsb00000</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a0cdd4f4fb1fb8021271baf9744fd9f97">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm12lu52id</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a616bedb534439b0fcf7af17daf289928">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm16lsl2</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#abecd6ad1bfa7d1c7cae4bc001ec0d6af">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm20lu12iw</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a76062d95e087f6d34c2342f7864d0375">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm20lu32id</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#ad045bbc3b96a4edfa9d6442e007ba60b">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm20pcaddi</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a593a4288b0b64c8ac07b9223f925e5b4">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm20pcaddu18i</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a4724f9de28ee2e6fc029afdb82429919">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm20pcalau12i</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#aabe6c9282287b819df475fc48ab35e59">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm21lsl2</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#adfe1704021f6026752f84192211fe503">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm26</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a51f664176dd5afd5051b83fa17e5cb2c">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm26Operand</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#afc37984bc54744b905e01edc0b594beb">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm5</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#abea18d9f8d1a819e45efc723be71dcb8">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm5Plus1</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#ad01a2bf5a8b48c76149ee03417626e12">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm6</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a6af949c7bbac35f257efa40174d553af">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm6NonZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a415117e2ad42c86e8b6c57069842f02c">anonymous{VEAsmParser.cpp}::VEOperand::isSImm7</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a88cac794786119f504d4a0c96540f2ea">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSOPPBrTarget</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a23b2900efc3dc7b9ab2e4655fd3874ca">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEAddSubImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a78d9bb4d126d1c4906dfee221ec64e5b">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVECpyImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#af6ede1b5501f32283fb6084a02528b20">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEPattern</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a5781cadb65dde47dd3d4fa07c5021091">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEVecLenSpecifier</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfasmparser-cpp-/bpfoperand/#a9f45ed60924831ef9cb7b4312ae98538">anonymous{BPFAsmParser.cpp}::BPFOperand::isSymbolRef</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af5ac50dd86f6113e4a16ebac72c0ddce">anonymous{ARMAsmParser.cpp}::ARMOperand::isT2SOImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aeaff465539f15d8e6657f5f424757374">anonymous{ARMAsmParser.cpp}::ARMOperand::isT2SOImmNeg</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a92682818cd914de0ab159350d30ccc50">anonymous{ARMAsmParser.cpp}::ARMOperand::isT2SOImmNot</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a5c384597724b5d6007275d66af948d76">anonymous{ARMAsmParser.cpp}::ARMOperand::isThumbBranchTarget</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae6e5f784a0126c865b6aac497adc486d">anonymous{ARMAsmParser.cpp}::ARMOperand::isThumbMemPC</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a151d137bbda190a83f16748aa8174966">anonymous{ARMAsmParser.cpp}::ARMOperand::isThumbModImmNeg1_7</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a8fb8471434ead3e41fb055a790c9525d">anonymous{ARMAsmParser.cpp}::ARMOperand::isThumbModImmNeg8_255</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#acfccb31cfbda65ecc1f98d308df407d2">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isTLSDESCCallSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a6d4a503d589ec40623d5d5d80acc9520">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isTPRelAddSymbol</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#afc0a8adb97fa110f25f96b03c0ddc590">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isTPRelAddSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#adf89a656cafe3f758650095b6a5a1aeb">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU12Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#ad799cf8502d62f862c5e6ec7747e07c4">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU16Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#ad12fccbe8d5ede1598deb9ded83cce70">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU1Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a6a9f26d0a1bccde30486a3924d3b671e">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU2Imm</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#aae0206914f9db22f97e82963e80d66a1">anonymous{HexagonAsmParser.cpp}::HexagonOperand::isu32_0MustExt</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a17c634554a01c0722a4af89e637f688b">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU32Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a475cc20a06283d7ee2ce7f21ac8a21a5">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU3Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#acfb2b12317fcbcbd4e1202887ad0852d">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU48Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a412c5fddd850e5f1ecdbf5264f007415">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU4Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#af7ae0d524a296f5a3901f762a8419332">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU8Imm</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#ad56527e41b356250baa3f977a0f23379">anonymous{RISCVAsmParser.cpp}::RISCVOperand::IsUImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#ad532c64ed131cfe08745e960e4c51746">anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#aed369dc44d69c66771b08d0d09b98273">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#af93768cbaa751193a411894ad982812c">anonymous{MipsAsmParser.cpp}::MipsOperand::isUImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a0c248d9d8c46154d6b0a71efa582facf">anonymous{VEAsmParser.cpp}::VEOperand::isUImm0to2</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a94a35ca24c165a98f33201ab12a6c8b7">anonymous{VEAsmParser.cpp}::VEOperand::isUImm1</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#ad40ce5b912f81fa907dc15a8fe418c50">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm10Lsb00NonZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a82e2a376717221b4993b1fc95415bde9">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isUImm12Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a76b0d1682d6c5d386162e94a79d02b3f">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm12ori</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#ac42b191a22c53fd485400b3f940f3aa0">anonymous{VEAsmParser.cpp}::VEOperand::isUImm2</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a7941ccc7f7bc6d6f518e1db11e581b9d">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm20AUIPC</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#aafcf3c2bb5b0550a74203b0c15648681">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm20LUI</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a311a899eaec9b7e7e0ecc3bcdb03bc92">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm2Lsb0</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a217ce68653e592e0fc0640ca36c6e066">anonymous{VEAsmParser.cpp}::VEOperand::isUImm3</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a21bde2572e09fde9a8adea664cc4ec4a">anonymous{VEAsmParser.cpp}::VEOperand::isUImm4</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a9d8c7238cf9ac3ee71e1bff04885275c">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm5GT3</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#afecb01e5f389e34cb6ff2193d429b50b">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm5Lsb0</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#ae99db1ae2ce5a2b14538903fed4cffdc">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm5NonZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a36d0b74dbf90ea3967907f05a88b06a2">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isUImm6</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#acb8846c3ff4f0be396f291ceee177ff4">anonymous{VEAsmParser.cpp}::VEOperand::isUImm6</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#ac2d5778b8d84d190f64085c330c49206">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm6Lsb0</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a712f18687c0a2df7428ef0108f4f93dd">anonymous{VEAsmParser.cpp}::VEOperand::isUImm7</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#accf08f0dc52b404b10f854884408cb43">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm7Lsb00</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#ac2784f59f188a8c871a9f0b30c87c925">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm7Lsb000</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a2a26a869a59be9ae11a98d9129fd331f">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm8GE32</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a2b303f3378e4f430ff52c7520317f7ed">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm8Lsb00</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a27b9f96bd235d2600a144430d35a2663">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm8Lsb000</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a8b003806c09ef35d160cfdb9a2865ff5">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm9Lsb000</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a8ea5baf20e0a1c77c77df4d599153e89">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImmLog2XLen</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a6f60201ed3b2c549f06fc69bb4e688be">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImmLog2XLenHalf</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a6c60dd71c23660c5f1f1a94b7f53137f">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImmLog2XLenNonZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af1f922d281d57228c7d7e8e904483f9f">anonymous{ARMAsmParser.cpp}::ARMOperand::isUnsignedOffset</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a6e51b20075aca7e72c747ebe4ce625b9">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isVTypeImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#ab2ce9cc62bb3cc784806f6e97b169f23">anonymous{VEAsmParser.cpp}::VEOperand::isZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonhardwareloops-cpp-/countvalue/#a8e2ee3bf4839fcec449ee3ef01bc914d">anonymous{HexagonHardwareLoops.cpp}::CountValue::print</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a5d95586ea588b8d6938a3e7679766688">llvm::HexagonInstrInfo::reverseBranchCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a4d8d351faef4293dcc8a164ce2f87d5c">llvm::SIInstrInfo::reverseBranchCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a4f0cc54c4806ee12ce6186629b182240">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::setImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a6a8d2feece61e3394cb02d59351ea70f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::setImmKindConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a3a0ff009144236a6532b574438a50a45">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::setImmKindLiteral</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa62444e32183814cbc01fb3c82c10eee">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::setImmKindMandatoryLiteral</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#adfa64c48e281a33a5607fc828e5ad626">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::setImmKindNone</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#aeeb834c778e7c58266e4e78bbaf2a703">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::tryToPromoteLoadFromStore</a>.</p>

</div>
</div>

### isTypeFoldingSupported() {#a4c9f91a5fc5778c118de4960dae29807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isTypeFoldingSupported (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp">SPIRVLegalizerInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp/#a25890802036e95dcac60b123783e089a">TypeFoldingSupportingOpcs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6bd6caf03c29de76c97c536f89349bd7">llvm::SPIRVLegalizerInfo::legalizeCustom</a>, <a href="#a2f96d0dcf6fbd53defac3a80db42f2e4">mayApplyGenericSelection</a> and <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a4a8b881c0637c6f85c3eb6891abcfab4">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::select</a>.</p>

</div>
</div>

### isUSMStorageClass() {#a232376a756ffa704f61ea3ab09f696e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isUSMStorageClass (SPIRV::StorageClass::StorageClass SC)</td>
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



<p>Definition at line 1465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>

</div>
</div>

### mayApplyGenericSelection() {#a2f96d0dcf6fbd53defac3a80db42f2e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool mayApplyGenericSelection (unsigned Opcode)</td>
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



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>


<p>Reference <a href="#a4c9f91a5fc5778c118de4960dae29807">isTypeFoldingSupported</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"spirv-isel"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>

</div>
</div>

### GET\_GLOBALISEL\_IMPL {#ae706a3af700f8ed432e93918d7601d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_GLOBALISEL_IMPL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>

</div>
</div>

### GET\_GLOBALISEL\_PREDICATE\_BITSET {#a9aa5a7608a0e489065b260a1ec245b82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_GLOBALISEL_PREDICATE_BITSET</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>

</div>
</div>

### GET\_GLOBALISEL\_PREDICATES\_DECL {#a2e198bb37135fbb2ecffb49ce588dfaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_GLOBALISEL_PREDICATES_DECL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>

</div>
</div>

### GET\_GLOBALISEL\_PREDICATES\_INIT {#a1ab538c256c3204b950075744d5b2b16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_GLOBALISEL_PREDICATES_INIT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>

</div>
</div>

### GET\_GLOBALISEL\_TEMPORARIES\_DECL {#a7ae8a4d3c9110554465fec97831b1dfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_GLOBALISEL_TEMPORARIES_DECL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>

</div>
</div>

### GET\_GLOBALISEL\_TEMPORARIES\_INIT {#a1cd36a579f079f7f4506d9d097b2f0a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_GLOBALISEL_TEMPORARIES_INIT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp">SPIRVInstructionSelector.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
