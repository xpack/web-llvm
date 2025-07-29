---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aarch64subtarget
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64Subtarget` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AArch64Subtarget { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">Target/AArch64/AArch64Subtarget.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/aarch64gensubtargetinfo">AArch64GenSubtargetInfo</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ARMProcFamilyEnum : uint8_t { <a href="#a2908c571a60104989fdef613e8c57cae">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> (const Triple &amp;TT, StringRef CPU, StringRef TuneCPU, StringRef FS, const TargetMachine &amp;TM, bool LittleEndian, unsigned MinSVEVectorSizeInBitsOverride=0, unsigned MaxSVEVectorSizeInBitsOverride=0, bool IsStreaming=false, bool IsStreamingCompatible=false, bool HasMinSize=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructor initializes the data members to match that of the specified triple. <a href="#a033ed3ccb4d48ca276a60b87127b344d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc204cbb4d2c7b9c5364d89a40deea5b">getHwModeSet</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64selectiondaginfo">AArch64SelectionDAGInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a039ee1fe628086a2c2a4a10db94e0758">getSelectionDAGInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering">AArch64FrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe1204d0641bf774be3ad6d95483af02">getFrameLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering">AArch64TargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66b26e824dd1b4bb346cd20278651032">getTargetLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo">AArch64InstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36aaf68c65aa593a22066976ee02810a">getInstrInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo">AArch64RegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3ed7e8a5fa2d4df05bf0fdf51a6550">getRegisterInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b6950acd6b80c51ff290beb2470f158">getCallLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering">InlineAsmLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a504a8c9446c716da678f5ad52e8b04b7">getInlineAsmLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9366f20b119180f1c68debd2555392e8">getInstructionSelector</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6960168c46441c38715c4afb3aa968a">getLegalizerInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2f55f16e39b3b5b9047278790c2cb15">getRegBankInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8166a906911a7c72d63b98512ced2d52">getTargetTriple</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6be9b10aadaa64c1ad2f8b010622131">enableMachineScheduler</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e340f77602b4248bed8322471749a8">enablePostRAScheduler</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a234fe3a4d41cb72f556a13a13f302b">enableSubRegLiveness</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ae68c51441a9d5bee1595e019de2b91">enableMachinePipeliner</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1b8466c3267e2b9aa33a626aa8fcad2">useDFAforSMS</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2908c571a60104989fdef613e8c57cae">ARMProcFamilyEnum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cbd2c43522cb4157a9c6853aefc438c">getProcFamily</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> processor family. <a href="#a5cbd2c43522cb4157a9c6853aefc438c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6a1ae5f8163866313335fec2b2c5bf">isXRaySupported</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b858c387cda4e1e520889efd26b0f6">isStreaming</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the function has a streaming body. <a href="#ab6b858c387cda4e1e520889efd26b0f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a85664508522995fb677504d8571feb">isStreamingCompatible</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the function has a streaming-compatible body. <a href="#a8a85664508522995fb677504d8571feb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83086cbbcef2fd09005f6e175f7f14f4">getStreamingHazardSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of memory region that if accessed by both the CPU and the SME unit could result in a hazard. <a href="#a83086cbbcef2fd09005f6e175f7f14f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a170e8cc4496759d9540c7a66a72a1696">isNeonAvailable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target has NEON and the function at runtime is known to have NEON enabled (e.g. <a href="#a170e8cc4496759d9540c7a66a72a1696">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb89e6f4c6ca2a39eafb64bb0a01a596">isSVEAvailable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target has SVE and can use the full range of SVE instructions, for example because it knows the function is known not to be in streaming-SVE mode or when the target has FEAT_FA64 enabled. <a href="#afb89e6f4c6ca2a39eafb64bb0a01a596">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a660a50ad59da76566ff9f0ab83de6cb3">isStreamingSVEAvailable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target has access to the streaming-compatible subset of SVE instructions. <a href="#a660a50ad59da76566ff9f0ab83de6cb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97be195ccbb061fd0e4170a81e066108">isSVEorStreamingSVEAvailable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target has access to either the full range of SVE instructions, or the streaming-compatible subset of SVE instructions. <a href="#a97be195ccbb061fd0e4170a81e066108">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad3af6253d4e150e55f987eadad56627">getMinVectorRegisterBitWidth</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abebf776aea4ae4a420fd4a2c5f02cbbd">isXRegisterReserved</a> (size_t i) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60b99c1daa52f651e107fb381e3433f9">isXRegisterReservedForRA</a> (size_t i) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b3a50936d453ae4dcadc704958bb35">getNumXRegisterReserved</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18bccbc1eec80c28e26095f1adfc62e8">isLRReservedForRA</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e92c78c91c9a864b7902df1502fb029">isXRegCustomCalleeSaved</a> (size_t i) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd4bb75fec521c3addcd5ac9d85fdce1">hasCustomCallingConv</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dcd3f2b4734cb1363b93048216267db">hasFusion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the CPU supports any kind of instruction fusion. <a href="#a3dcd3f2b4734cb1363b93048216267db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae351e859f15d75e7db99f9b238b4cee5">getEpilogueVectorizationMinVF</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b5e15aa57baa83db726cee3338c25b7">getMaxInterleaveFactor</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59fa8edbdb0dcf971dccf48d88b36dab">getVectorInsertExtractBaseCost</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5529884a7035031f480f0f80842380b4">getCacheLineSize</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad83719661ffe575e99f4d697357696ef">getScatterOverhead</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a603ec68113d25d526bd2ac979f3aecc0">getGatherOverhead</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff68da1da5bbabd26f8d31500855f330">getPrefetchDistance</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1993d88329db5bf42d3d1956c47cb946">getMinPrefetchStride</a> (unsigned NumMemAccesses, unsigned NumStridedMemAccesses, unsigned NumPrefetches, bool HasCall) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac353afb8233313c3b15ae5a6e61136ab">getMaxPrefetchIterationsAhead</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b171f93524a8d0d1c0772479a1703c5">getPrefFunctionAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66c91211a6770a537c3cfc057cabd1fa">getPrefLoopAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d48d262c4d851861f24550fb1014164">getMaxBytesForLoopAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a428f4cfc3de60a3999ac03dc56072bf6">getMaximumJumpTableSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29ca38d13438677838d19993b810757c">getMinimumJumpTableEntries</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76fdf3d877571240f3d86a7a9af696e7">supportsAddressTopByteIgnored</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CPU has TBI (top byte of addresses is ignored during HW address translation) and OS enables it. <a href="#a76fdf3d877571240f3d86a7a9af696e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ebfcf378eb3c7d2ad24c4269b3d42a">isLittleEndian</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d2e6b50d2d120966b45253b1ad825b4">isTargetDarwin</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5ac334e783091cab6709db26f80ac6e">isTargetIOS</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae958bc5e804978a9be305c1b6f3cd63b">isTargetLinux</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05fb81a3747dd4f76894a66c574cf99e">isTargetWindows</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7db9992896c0e7723b498325dd3f4ddb">isTargetAndroid</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accbba019f8f5efce76ec4b6b8df113b1">isTargetFuchsia</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab11ed6ee239ab7c9328927b7327fc8f1">isWindowsArm64EC</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9cfdf718223ce9f4a8df0d2d7ea0f8f">isTargetCOFF</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4010b1841b5e6ade2f4ad494cc2169b0">isTargetELF</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d2ea0d87e248160e202c25124c91fa9">isTargetMachO</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59137b132e07516767761d5decf7e252">isTargetILP32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64cb9803bb305e47d2e8ef2e8994aae0">useAA</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c9e373390ff89618b21550fd86ef93d">addrSinkUsingGEPs</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37379906f66f96e9ab4e9e087d2aa12f">useSmallAddressing</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa63814918548c7c1b928af6385155712">ParseSubtargetFeatures</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options. <a href="#aa63814918548c7c1b928af6385155712">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2bf24e995494a7c64d8f3e02818ad30">ClassifyGlobalReference</a> (const GlobalValue *GV, const TargetMachine &amp;TM) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ClassifyGlobalReference - Find the target operand flags that describe how a global value should be referenced for the current subtarget. <a href="#aa2bf24e995494a7c64d8f3e02818ad30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b99558b55ac0e86169e5b7eb6ad193">classifyGlobalFunctionReference</a> (const GlobalValue *GV, const TargetMachine &amp;TM) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f39dfc885f21dfc2e968dd89b74f7cd">classifyGlobalFunctionReference</a> (const GlobalValue *GV) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is design to compatible with the function def in other targets and escape build error about the virtual function def in base class <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a>. <a href="#a7f39dfc885f21dfc2e968dd89b74f7cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba514719cbb75b668499574cd6f238e">overrideSchedPolicy</a> (MachineSchedPolicy &amp;Policy, unsigned NumRegionInstrs) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9027a59d16b066e9f8549b9a9c50b60b">adjustSchedDependency</a> (SUnit *Def, int DefOpIdx, SUnit *Use, int UseOpIdx, SDep &amp;Dep, const TargetSchedModel *SchedModel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f1b97ad9a816b42a7f12ca65c76313d">enableEarlyIfConversion</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pbqpraconstraint">PBQPRAConstraint</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae280b5e0f70bc3cee1dbcb85aaf1c788">getCustomPBQPConstraints</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5185becf2e4a0ecfb059a5ce69da205">isCallingConvWin64</a> (CallingConv::ID CC, bool IsVarArg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe7a4a37a90fa94396e12c3543339d15">swiftAsyncContextIsDynamicallySet</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether FrameLowering should always set the "extended frame
present" bit in FP, or set it based on a symbol in the runtime. <a href="#afe7a4a37a90fa94396e12c3543339d15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a917a79b56742eaac2db61e2a221d3011">mirFileLoaded</a> (MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3c0b17cadd04099c074dadd7bf3349b">getMaxSVEVectorSizeInBits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af011282932f20754ceb5a48038f4f5a6">getMinSVEVectorSizeInBits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa24d6e3c045459131ced627a0ed30dcc">useSVEForFixedLengthVectors</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f7ac4b96278419769d4bd3caa6fcf26">useSVEForFixedLengthVectors</a> (EVT VT) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6608e44f816255878f5e180f4330641">getVScaleForTuning</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eaf">TailFoldingOpts</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cc5a7590a9f8f14eb1d58d3fc57c7e2">getSVETailFoldingDefaultOpts</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad13aab0ab8d5a27a2669c863ac0cf9c2">useScalarIncVL</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true to use the addvl/inc/dec instructions, as opposed to separate add + cnt instructions. <a href="#ad13aab0ab8d5a27a2669c863ac0cf9c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e30069ba148ef377a6c59f68d3b8969">getChkStkName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a423d256c34effdf9184779a14b2174c8">getSecurityCheckCookieName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">AArch64PAuth::AuthCheckMethod</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11871b65a6cfc7ce8fc20403e18ab40">getAuthenticatedLRCheckMethod</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Choose a method of checking LR before performing a tail call. <a href="#af11871b65a6cfc7ce8fc20403e18ab40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ecc0bb5ee3eac043a66ce779ad05747">getPtrAuthBlockAddressDiscriminatorIfEnabled</a> (const Function &amp;ParentFn) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the integer discriminator for a given <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> constant, if blockaddress signing is enabled, or std::nullopt otherwise. <a href="#a5ecc0bb5ee3eac043a66ce779ad05747">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a225878209bbc8cbcdc573403754ba950">initializeSubtargetDependencies</a> (StringRef FS, StringRef CPUString, StringRef TuneCPUString, bool HasMinSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>initializeSubtargetDependencies - Initializes using CPUString and the passed in feature string so that we can use initializer lists for subtarget initialization. <a href="#a225878209bbc8cbcdc573403754ba950">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9aa6058fd886ec04adfbfbf409b97b5">initializeProperties</a> (bool HasMinSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize properties based on the selected processor family. <a href="#aa9aa6058fd886ec04adfbfbf409b97b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2908c571a60104989fdef613e8c57cae">ARMProcFamilyEnum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a283b368e24b91ca9b4a3960d4fee4876">ARMProcFamily</a> = <a href="#a2908c571a60104989fdef613e8c57caea0893fc2470e30fda5ddf6a8c26f4561c">Generic</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ARMProcFamily - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> processor family: Cortex-A53, Cortex-A57, and others. <a href="#a283b368e24b91ca9b4a3960d4fee4876">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a837e4a0338312af979138355d05834b1">MinVectorRegisterBitWidth</a> = 64</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ae33846ba3a76325d59ba6a1c74fa4e">EpilogueVectorizationMinVF</a> = 16</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae35348ac382b7f2b970cbd32e051f829">MaxInterleaveFactor</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a663b081baf6a1824b31a9bff266a6f8a">VectorInsertExtractBaseCost</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b3933070c0c7cd93e57df1a4795da26">CacheLineSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9fc63fa8f564800eadb3fd11e811451">ScatterOverhead</a> = 10</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa4482559c05721935e3268644f866c">GatherOverhead</a> = 10</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7436edeb320ea803a853a7c0d161a188">PrefetchDistance</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a949048c787f5a5f0539c405c5530d687">MinPrefetchStride</a> = 1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53802a9885c8d3715a584e87d5b58e47">MaxPrefetchIterationsAhead</a> = UINT_MAX</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e2b15fbec6c266f7444ab03d8d9230f">PrefFunctionAlignment</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f8c75c233bb1f77e3535e8038630f8b">PrefLoopAlignment</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8014e78305810558e44e9b9194b563f">MaxBytesForLoopAlignment</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5c87833696cd728e1abfe0995ccf43d">MinimumJumpTableEntries</a> = 4</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8e488c0af0ac3b5b3804c9ba2e882b1">MaxJumpTableSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082079e75474f048dbc714c42f7d5189">ReserveXRegister</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0729bd502584fc2e92ead492e9b462af">ReserveXRegisterForRA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aa7d773a419978d3a2d7746a8d33b52">CustomCallSavedXRegs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2110152d7d81909a815bc64687c3b3f2">IsLittle</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa593225d2cd30e1d2f7b045372151ef">IsStreaming</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dce20f668ef47c27dc3dd31e2c2858a">IsStreamingCompatible</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46a039a63380cfb0a407ebbf01cb0f8e">StreamingHazardSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab773b1501fea6965ed8f896ba2e71468">MinSVEVectorSizeInBits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf5d5f04e136fcc8888ff37491c264a">MaxSVEVectorSizeInBits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a313cf778d3a8a4702205f48795d2dbf3">VScaleForTuning</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eaf">TailFoldingOpts</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192bbbe8fa7ae7351f69e7c07119ef81">DefaultSVETFOpts</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafab9f5c797ebbf55adccdd8539a65a0241">TailFoldingOpts::Disabled</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0f9271b5e0c76b7eed6f7d761b91ee9">EnableSubregLiveness</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TargetTriple - What processor and OS we're targeting. <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering">AArch64FrameLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4becb54f5d6a9482ab6a57bf299446d9">FrameLowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo">AArch64InstrInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1e1c6731e7afd31d2084082b15d458a">InstrInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64selectiondaginfo">AArch64SelectionDAGInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e7e95e8e39f20c2cb2965a84b41ab26">TSInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering">AArch64TargetLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2b6b36547a598d0c25501aad09e6433">TLInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5deed214062763eccdb97587cd61e431">CallLoweringInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GlobalISel related APIs. <a href="#a5deed214062763eccdb97587cd61e431">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering">InlineAsmLowering</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af89b6dde02852af95a1cf25a09364489">InlineAsmLoweringInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c4bbc27d200153fd3580d02fb0f720">InstSelector</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6242f2929d57d293b14ba19afc09e78">Legalizer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a7d4e12e33fb717fc55dd5ff6f9ad05">RegBankInfo</a></td>
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


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ARMProcFamilyEnum {#a2908c571a60104989fdef613e8c57cae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64Subtarget::ARMProcFamilyEnum : uint8_t</td>
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
<td class="doxyEnumItemName">Generic<a id="a2908c571a60104989fdef613e8c57caea0893fc2470e30fda5ddf6a8c26f4561c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AArch64Subtarget() {#a033ed3ccb4d48ca276a60b87127b344d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64Subtarget::AArch64Subtarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, bool LittleEndian, unsigned MinSVEVectorSizeInBitsOverride=0, unsigned MaxSVEVectorSizeInBitsOverride=0, bool IsStreaming=false, bool IsStreamingCompatible=false, bool HasMinSize=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This constructor initializes the data members to match that of the specified triple.</p>

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#ad210c499e848202f1fabb9fdddc89387">AArch64StreamingHazardSize</a>, <a href="#a5deed214062763eccdb97587cd61e431">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a9846bb2bc5672e7627011260772b8d09">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e0a0c8e3606bf98ea3d0c7053763097">llvm::createAArch64InstructionSelector</a>, <a href="#a1aa7d773a419978d3a2d7746a8d33b52">CustomCallSavedXRegs</a>, <a href="#ae0f9271b5e0c76b7eed6f7d761b91ee9">EnableSubregLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#a822c5f2181439c6942d190206300928d">EnableSubregLivenessTracking</a>, <a href="#a0c3ed7e8a5fa2d4df05bf0fdf51a6550">getRegisterInfo</a>, <a href="#a66b26e824dd1b4bb346cd20278651032">getTargetLowering</a>, <a href="#af89b6dde02852af95a1cf25a09364489">InlineAsmLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stringset/#add93efa62e06c599f1734f3b206232a0">llvm::StringSet&lt; AllocatorTy &gt;::insert</a>, <a href="#af1e1c6731e7afd31d2084082b15d458a">InstrInfo</a>, <a href="#a20c4bbc27d200153fd3580d02fb0f720">InstSelector</a>, <a href="#a2110152d7d81909a815bc64687c3b3f2">IsLittle</a>, <a href="#afa593225d2cd30e1d2f7b045372151ef">IsStreaming</a>, <a href="#a1dce20f668ef47c27dc3dd31e2c2858a">IsStreamingCompatible</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a15ff6f0c7a140c2854291d3671b26686">llvm::AArch64::isX18ReservedByDefault</a>, <a href="#af6242f2929d57d293b14ba19afc09e78">Legalizer</a>, <a href="#adbf5d5f04e136fcc8888ff37491c264a">MaxSVEVectorSizeInBits</a>, <a href="#ab773b1501fea6965ed8f896ba2e71468">MinSVEVectorSizeInBits</a>, <a href="#a2a7d4e12e33fb717fc55dd5ff6f9ad05">RegBankInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#af563183167da8f02154765192c6449ac">ReservedRegsForRA</a>, <a href="#a082079e75474f048dbc714c42f7d5189">ReserveXRegister</a>, <a href="#a0729bd502584fc2e92ead492e9b462af">ReserveXRegisterForRA</a>, <a href="#a46a039a63380cfb0a407ebbf01cb0f8e">StreamingHazardSize</a>, <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a>, <a href="#af2b6b36547a598d0c25501aad09e6433">TLInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addrSinkUsingGEPs() {#a1c9e373390ff89618b21550fd86ef93d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::addrSinkUsingGEPs ()</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="#a59137b132e07516767761d5decf7e252">isTargetILP32</a> and <a href="#a64cb9803bb305e47d2e8ef2e8994aae0">useAA</a>.</p>

</div>
</div>

### adjustSchedDependency() {#a9027a59d16b066e9f8549b9a9c50b60b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64Subtarget::adjustSchedDependency (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Def, int DefOpIdx, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Use, int UseOpIdx, <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; Dep, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> * SchedModel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#abe764852febe90b22412f1acf299fb9e">llvm::TargetSchedModel::computeOperandLatency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b2720d4f12a870348c3949a78e4a6f9">llvm::const_mi_bundle_ops</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a055c65558a3e0f7d48f1ed3dde061199">llvm::SDep::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a8b51361656ac436c2c02a20e6196cff1">llvm::SDep::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a148b76c8f993d4a3d95ac19c60e2ebe0">llvm::SDep::setLatency</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>

</div>
</div>

### classifyGlobalFunctionReference() {#a61b99558b55ac0e86169e5b7eb6ad193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64Subtarget::classifyGlobalFunctionReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>References <a href="#aa2bf24e995494a7c64d8f3e02818ad30">ClassifyGlobalReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a8166a906911a7c72d63b98512ced2d52">getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a66501d6d43642a526ab769458d700aa4">llvm::GlobalValue::hasDLLImportStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a1847e956a0087fefdb49e2a9583c7d18">llvm::GlobalValue::hasExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a7bc292fc6d075e3ed6e68b0866ec3524">llvm::GlobalValue::hasInternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aba930e0564c4207f112d9243eb2fc13a">llvm::Type::isFunctionTy</a>, <a href="#a6d2ea0d87e248160e202c25124c91fa9">isTargetMachO</a>, <a href="#ab11ed6ee239ab7c9328927b7327fc8f1">isWindowsArm64EC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#a47546b8467e7d7c6556f998b034fe863">MachOUseNonLazyBind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a7e1a1b36a7d8530c6b92c03b605b8372">llvm::AArch64II::MO_ARM64EC_CALLMANGLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a014aa77d177f925047f52c27d6dec14e">llvm::AArch64II::MO_DLLIMPORT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a4144c2ee93286fba09bd8f14fb11f27a">llvm::AArch64II::MO_GOT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a48b42f4ac550b5ae203477aad0eb5e75">llvm::AArch64II::MO_NO_FLAG</a>.</p>

</div>
</div>

### classifyGlobalFunctionReference() {#a7f39dfc885f21dfc2e968dd89b74f7cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::AArch64Subtarget::classifyGlobalFunctionReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
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

<p>This function is design to compatible with the function def in other targets and escape build error about the virtual function def in base class <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a>.</p>


<p>Updeate me if <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> target need to use it.</p>


<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>

</div>
</div>

### ClassifyGlobalReference() {#aa2bf24e995494a7c64d8f3e02818ad30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64Subtarget::ClassifyGlobalReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ClassifyGlobalReference - Find the target operand flags that describe how a global value should be referenced for the current subtarget.</p>


<p>Find the target operand flags that describe how a global value should be referenced for the current subtarget.</p>


<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>References <a href="#a8166a906911a7c72d63b98512ced2d52">getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a66501d6d43642a526ab769458d700aa4">llvm::GlobalValue::hasDLLImportStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a51af265dc931258cdb8ffb37ee6decee">llvm::GlobalValue::hasExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a40631ccf8ca06c1942f13f4872ed8e86">llvm::GlobalValue::isTagged</a>, <a href="#a6d2ea0d87e248160e202c25124c91fa9">isTargetMachO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71afacfcdd80d8095ce952ab919979f1d2f">llvm::AArch64II::MO_COFFSTUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a014aa77d177f925047f52c27d6dec14e">llvm::AArch64II::MO_DLLIMPORT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a4144c2ee93286fba09bd8f14fb11f27a">llvm::AArch64II::MO_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a028a4adc46c746ba1501e1e6fefb54cc">llvm::AArch64II::MO_NC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a48b42f4ac550b5ae203477aad0eb5e75">llvm::AArch64II::MO_NO_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71aefb2c1834e49df9715967d4a2c9c99e8">llvm::AArch64II::MO_TAGGED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa686bcdfaefdfe3f49acbfe6f680bc22d">llvm::CodeModel::Tiny</a> and <a href="#a37379906f66f96e9ab4e9e087d2aa12f">useSmallAddressing</a>.</p>


<p>Referenced by <a href="#a61b99558b55ac0e86169e5b7eb6ad193">classifyGlobalFunctionReference</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#aad04adafa0e888033fe358c61e3bdc69">anonymous{AArch64PreLegalizerCombiner.cpp}::matchFoldGlobalOffset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a40c243011cdda005e97448378d575096">performGlobalAddressCombine</a>.</p>

</div>
</div>

### enableEarlyIfConversion() {#a4f1b97ad9a816b42a7f12ca65c76313d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64Subtarget::enableEarlyIfConversion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#ab43de97739917d586616937123ef0fbf">EnableEarlyIfConvert</a>.</p>

</div>
</div>

### enableMachinePipeliner() {#a5ae68c51441a9d5bee1595e019de2b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64Subtarget::enableMachinePipeliner ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>

</div>
</div>

### enableMachineScheduler() {#ad6be9b10aadaa64c1ad2f8b010622131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::enableMachineScheduler ()</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>

</div>
</div>

### enablePostRAScheduler() {#ad8e340f77602b4248bed8322471749a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::enablePostRAScheduler ()</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>

</div>
</div>

### enableSubRegLiveness() {#a9a234fe3a4d41cb72f556a13a13f302b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::enableSubRegLiveness ()</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#ae0f9271b5e0c76b7eed6f7d761b91ee9">EnableSubregLiveness</a>.</p>

</div>
</div>

### getAuthenticatedLRCheckMethod() {#af11871b65a6cfc7ce8fc20403e18ab40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64PAuth::AuthCheckMethod AArch64Subtarget::getAuthenticatedLRCheckMethod (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Choose a method of checking LR before performing a tail call.</p>

<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#a702a1c7df390854ca66dd8b7607c3844">AuthenticatedLRCheckMethod</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a1bf38b3bbe867377cde6e530a0256b29">llvm::AArch64InstrInfo::getInstSizeInBytes</a>.</p>

</div>
</div>

### getCacheLineSize() {#a5529884a7035031f480f0f80842380b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getCacheLineSize ()</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a9b3933070c0c7cd93e57df1a4795da26">CacheLineSize</a>.</p>

</div>
</div>

### getCallLowering() {#a0b6950acd6b80c51ff290beb2470f158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallLowering * AArch64Subtarget::getCallLowering ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Reference <a href="#a5deed214062763eccdb97587cd61e431">CallLoweringInfo</a>.</p>

</div>
</div>

### getChkStkName() {#a8e30069ba148ef377a6c59f68d3b8969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::AArch64Subtarget::getChkStkName ()</td>
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



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#ab11ed6ee239ab7c9328927b7327fc8f1">isWindowsArm64EC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>.</p>

</div>
</div>

### getCustomPBQPConstraints() {#ae280b5e0f70bc3cee1dbcb85aaf1c788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PBQPRAConstraint &gt; AArch64Subtarget::getCustomPBQPConstraints ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>

</div>
</div>

### getEpilogueVectorizationMinVF() {#ae351e859f15d75e7db99f9b238b4cee5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getEpilogueVectorizationMinVF ()</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a3ae33846ba3a76325d59ba6a1c74fa4e">EpilogueVectorizationMinVF</a>.</p>

</div>
</div>

### getFrameLowering() {#afe1204d0641bf774be3ad6d95483af02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64FrameLowering * llvm::AArch64Subtarget::getFrameLowering ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a4becb54f5d6a9482ab6a57bf299446d9">FrameLowering</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a9fd3cdd22c698232d4998d7b3ea7b21a">llvm::AArch64FunctionInfo::AArch64FunctionInfo</a>.</p>

</div>
</div>

### getGatherOverhead() {#a603ec68113d25d526bd2ac979f3aecc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getGatherOverhead ()</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a2aa4482559c05721935e3268644f866c">GatherOverhead</a>.</p>

</div>
</div>

### getHwModeSet() {#acc204cbb4d2c7b9c5364d89a40deea5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64Subtarget::getHwModeSet ()</td>
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



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#af522e637a0ed824a6ecabe4814c0c03b">EnableZPRPredicateSpills</a>, <a href="#ab6b858c387cda4e1e520889efd26b0f6">isStreaming</a>, <a href="#a8a85664508522995fb677504d8571feb">isStreamingCompatible</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a842e49a58fb3eba4e42a8dadad77745b">llvm::to_underlying</a>.</p>

</div>
</div>

### getInlineAsmLowering() {#a504a8c9446c716da678f5ad52e8b04b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InlineAsmLowering * AArch64Subtarget::getInlineAsmLowering ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Reference <a href="#af89b6dde02852af95a1cf25a09364489">InlineAsmLoweringInfo</a>.</p>

</div>
</div>

### getInstrInfo() {#a36aaf68c65aa593a22066976ee02810a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64InstrInfo * llvm::AArch64Subtarget::getInstrInfo ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#af1e1c6731e7afd31d2084082b15d458a">InstrInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-cpp/#a2f84e624e7227bb33f6c14fe98f36715">BuildPACM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a1886741049357a9b7cea7f8e8784a818">emitDefineCFAWithFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-cpp/#a181216377a992592ea7e30fc0ce07f0d">emitPACCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="#a0c3ed7e8a5fa2d4df05bf0fdf51a6550">getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64pointerauth-cpp-/aarch64pointerauth/#aa8ea77f095d6c1c056af51e7a652e5bd">anonymous{AArch64PointerAuth.cpp}::AArch64PointerAuth::runOnMachineFunction</a>.</p>

</div>
</div>

### getInstructionSelector() {#a9366f20b119180f1c68debd2555392e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector * AArch64Subtarget::getInstructionSelector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Reference <a href="#a20c4bbc27d200153fd3580d02fb0f720">InstSelector</a>.</p>

</div>
</div>

### getLegalizerInfo() {#ad6960168c46441c38715c4afb3aa968a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LegalizerInfo * AArch64Subtarget::getLegalizerInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Reference <a href="#af6242f2929d57d293b14ba19afc09e78">Legalizer</a>.</p>

</div>
</div>

### getMaxBytesForLoopAlignment() {#a6d48d262c4d851861f24550fb1014164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getMaxBytesForLoopAlignment ()</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#af8014e78305810558e44e9b9194b563f">MaxBytesForLoopAlignment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acf8f1219dc8b656e8e11c4b08edc8979">llvm::AArch64TargetLowering::AArch64TargetLowering</a>.</p>

</div>
</div>

### getMaximumJumpTableSize() {#a428f4cfc3de60a3999ac03dc56072bf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getMaximumJumpTableSize ()</td>
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



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#aa8e488c0af0ac3b5b3804c9ba2e882b1">MaxJumpTableSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acf8f1219dc8b656e8e11c4b08edc8979">llvm::AArch64TargetLowering::AArch64TargetLowering</a>.</p>

</div>
</div>

### getMaxInterleaveFactor() {#a7b5e15aa57baa83db726cee3338c25b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getMaxInterleaveFactor ()</td>
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



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#ae35348ac382b7f2b970cbd32e051f829">MaxInterleaveFactor</a>.</p>

</div>
</div>

### getMaxPrefetchIterationsAhead() {#ac353afb8233313c3b15ae5a6e61136ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getMaxPrefetchIterationsAhead ()</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a53802a9885c8d3715a584e87d5b58e47">MaxPrefetchIterationsAhead</a>.</p>

</div>
</div>

### getMaxSVEVectorSizeInBits() {#ae3c0b17cadd04099c074dadd7bf3349b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getMaxSVEVectorSizeInBits ()</td>
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



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a97be195ccbb061fd0e4170a81e066108">isSVEorStreamingSVEAvailable</a> and <a href="#adbf5d5f04e136fcc8888ff37491c264a">MaxSVEVectorSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64348c468485ac9fa8aaf382307061fb">findMoreOptimalIndexType</a>.</p>

</div>
</div>

### getMinimumJumpTableEntries() {#a29ca38d13438677838d19993b810757c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getMinimumJumpTableEntries ()</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#ad5c87833696cd728e1abfe0995ccf43d">MinimumJumpTableEntries</a>.</p>

</div>
</div>

### getMinPrefetchStride() {#a1993d88329db5bf42d3d1956c47cb946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getMinPrefetchStride (unsigned NumMemAccesses, unsigned NumStridedMemAccesses, unsigned NumPrefetches, bool HasCall)</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a949048c787f5a5f0539c405c5530d687">MinPrefetchStride</a>.</p>

</div>
</div>

### getMinSVEVectorSizeInBits() {#af011282932f20754ceb5a48038f4f5a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getMinSVEVectorSizeInBits ()</td>
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



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a97be195ccbb061fd0e4170a81e066108">isSVEorStreamingSVEAvailable</a> and <a href="#ab773b1501fea6965ed8f896ba2e71468">MinSVEVectorSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a68a18462f9529b0e75812794eeedbb5f">getPredicateForFixedLengthVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a33354bc388aab299f6dca5b75bbe2238">isAllActivePredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a758290c5743d18768a64d96539070fd1">optimizeIncrementingWhile</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8b803a5cecda412b4f4984ad8db7201e">performFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac1e566876b6ec934e149faae1a9b6f74">performMSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad19eb01bd287efda27e7bc5ba67cd144">performSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a47e64a2f9eb3ade81edd0d1e20034ec1">performUnpackCombine</a> and <a href="#aa24d6e3c045459131ced627a0ed30dcc">useSVEForFixedLengthVectors</a>.</p>

</div>
</div>

### getMinVectorRegisterBitWidth() {#aad3af6253d4e150e55f987eadad56627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getMinVectorRegisterBitWidth ()</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="#a170e8cc4496759d9540c7a66a72a1696">isNeonAvailable</a>, <a href="#afb89e6f4c6ca2a39eafb64bb0a01a596">isSVEAvailable</a> and <a href="#a837e4a0338312af979138355d05834b1">MinVectorRegisterBitWidth</a>.</p>

</div>
</div>

### getNumXRegisterReserved() {#a61b3a50936d453ae4dcadc704958bb35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getNumXRegisterReserved ()</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a568ff706b8c5991bd299c8c00b803897">llvm::BitVector::count</a>, <a href="#a082079e75474f048dbc714c42f7d5189">ReserveXRegister</a> and <a href="#a0729bd502584fc2e92ead492e9b462af">ReserveXRegisterForRA</a>.</p>

</div>
</div>

### getPrefetchDistance() {#aff68da1da5bbabd26f8d31500855f330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getPrefetchDistance ()</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a7436edeb320ea803a853a7c0d161a188">PrefetchDistance</a>.</p>

</div>
</div>

### getPrefFunctionAlignment() {#a6b171f93524a8d0d1c0772479a1703c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::AArch64Subtarget::getPrefFunctionAlignment ()</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a7e2b15fbec6c266f7444ab03d8d9230f">PrefFunctionAlignment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acf8f1219dc8b656e8e11c4b08edc8979">llvm::AArch64TargetLowering::AArch64TargetLowering</a>.</p>

</div>
</div>

### getPrefLoopAlignment() {#a66c91211a6770a537c3cfc057cabd1fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::AArch64Subtarget::getPrefLoopAlignment ()</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a5f8c75c233bb1f77e3535e8038630f8b">PrefLoopAlignment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acf8f1219dc8b656e8e11c4b08edc8979">llvm::AArch64TargetLowering::AArch64TargetLowering</a>.</p>

</div>
</div>

### getProcFamily() {#a5cbd2c43522cb4157a9c6853aefc438c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMProcFamilyEnum llvm::AArch64Subtarget::getProcFamily ()</td>
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

<p>Returns <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> processor family.</p>


<p>Avoid this function! CPU specifics should be kept local to this class and preferably modeled with <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> or properties in initializeProperties().</p>


<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a283b368e24b91ca9b4a3960d4fee4876">ARMProcFamily</a>.</p>

</div>
</div>

### getPtrAuthBlockAddressDiscriminatorIfEnabled() {#a5ecc0bb5ee3eac043a66ce779ad05747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint16_t &gt; AArch64Subtarget::getPtrAuthBlockAddressDiscriminatorIfEnabled (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; ParentFn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the integer discriminator for a given <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> constant, if blockaddress signing is enabled, or std::nullopt otherwise.</p>


<p>Blockaddress signing is controlled by the function attribute "ptrauth-indirect-gotos" on the parent function. Note that this assumes the discriminator is independent of the indirect goto branch site itself, i.e., it's the same for all BlockAddresses in a function.</p>


<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95bf65a141564e084f6fac52c00b6a6d">llvm::getPointerAuthStableSipHash</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>.</p>

</div>
</div>

### getRegBankInfo() {#af2f55f16e39b3b5b9047278790c2cb15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo * AArch64Subtarget::getRegBankInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Reference <a href="#a2a7d4e12e33fb717fc55dd5ff6f9ad05">RegBankInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>.</p>

</div>
</div>

### getRegisterInfo() {#a0c3ed7e8a5fa2d4df05bf0fdf51a6550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64RegisterInfo * llvm::AArch64Subtarget::getRegisterInfo ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="#a36aaf68c65aa593a22066976ee02810a">getInstrInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a616fc69908b11c1c62addae537191ad4">llvm::AArch64InstrInfo::getRegisterInfo</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9a7f5712e4a4603a0bdd87cc08e9b1d6">llvm::AArch64InstrInfo::buildClearRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a2be9d35aaace9716441da5714f048af9">llvm::AArch64FrameLowering::canUseAsPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a1886741049357a9b7cea7f8e8784a818">emitDefineCFAWithFP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a8705d5d3c895b6ddc6502220cbe3a965">findScratchNonCalleeSaveRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a7f43397146b3eee4bcd4ff73ec27335f">InsertSEH</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>.</p>

</div>
</div>

### getScatterOverhead() {#ad83719661ffe575e99f4d697357696ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getScatterOverhead ()</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#ae9fc63fa8f564800eadb3fd11e811451">ScatterOverhead</a>.</p>

</div>
</div>

### getSecurityCheckCookieName() {#a423d256c34effdf9184779a14b2174c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::AArch64Subtarget::getSecurityCheckCookieName ()</td>
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



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#ab11ed6ee239ab7c9328927b7327fc8f1">isWindowsArm64EC</a>.</p>

</div>
</div>

### getSelectionDAGInfo() {#a039ee1fe628086a2c2a4a10db94e0758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64SelectionDAGInfo * llvm::AArch64Subtarget::getSelectionDAGInfo ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a3e7e95e8e39f20c2cb2965a84b41ab26">TSInfo</a>.</p>

</div>
</div>

### getStreamingHazardSize() {#a83086cbbcef2fd09005f6e175f7f14f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getStreamingHazardSize ()</td>
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

<p>Returns the size of memory region that if accessed by both the CPU and the SME unit could result in a hazard.</p>


<p>0 = disabled.</p>


<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a46a039a63380cfb0a407ebbf01cb0f8e">StreamingHazardSize</a>.</p>

</div>
</div>

### getSVETailFoldingDefaultOpts() {#a9cc5a7590a9f8f14eb1d58d3fc57c7e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TailFoldingOpts llvm::AArch64Subtarget::getSVETailFoldingDefaultOpts ()</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a192bbbe8fa7ae7351f69e7c07119ef81">DefaultSVETFOpts</a>.</p>

</div>
</div>

### getTargetLowering() {#a66b26e824dd1b4bb346cd20278651032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64TargetLowering * llvm::AArch64Subtarget::getTargetLowering ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#af2b6b36547a598d0c25501aad09e6433">TLInfo</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a2be9d35aaace9716441da5714f048af9">llvm::AArch64FrameLowering::canUseAsPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a81242a6cd5fbec123c8ed582bab0f26c">llvm::AArch64FrameLowering::canUseRedZone</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64selectiondaginfo/#a4f4d5344fa41e237eb9a60c7b62975b8">llvm::AArch64SelectionDAGInfo::EmitStreamingCompatibleMemLibCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#a0d6af68066457ccc3a8ddcd68d142853">finishStackBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ac26dae5c257bfaab5aa15cab7255f107">llvm::AArch64RegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a2a4f0d74a9e54517b5009c2ac31503b5">llvm::AArch64RegisterInfo::getCallPreservedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aaab57b42c1306819f384fbc8917e728b">llvm::AArch64RegisterInfo::getDarwinCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ace1d2fbafd80bd71d27a949593da97f7">llvm::AArch64RegisterInfo::getDarwinCallPreservedMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a469793f0416704ca132c5c91f73adbdd">produceCompactUnwindFrame</a>.</p>

</div>
</div>

### getTargetTriple() {#a8166a906911a7c72d63b98512ced2d52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple &amp; llvm::AArch64Subtarget::getTargetTriple ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a>.</p>


<p>Referenced by <a href="#a61b99558b55ac0e86169e5b7eb6ad193">classifyGlobalFunctionReference</a>, <a href="#aa2bf24e995494a7c64d8f3e02818ad30">ClassifyGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp/#a94b61556b849102cdcace07d0a404434">hasELFSignedGOTHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp/#a7010c624fdaf139f8efa60219c3b56bf">ShouldSignWithBKey</a> and <a href="#afe7a4a37a90fa94396e12c3543339d15">swiftAsyncContextIsDynamicallySet</a>.</p>

</div>
</div>

### getVectorInsertExtractBaseCost() {#a59fa8edbdb0dcf971dccf48d88b36dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64Subtarget::getVectorInsertExtractBaseCost ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#af81369e40408bddbf3c1c4b06ebc48c4">OverrideVectorInsertExtractBaseCost</a> and <a href="#a663b081baf6a1824b31a9bff266a6f8a">VectorInsertExtractBaseCost</a>.</p>

</div>
</div>

### getVScaleForTuning() {#ae6608e44f816255878f5e180f4330641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::getVScaleForTuning ()</td>
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



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a313cf778d3a8a4702205f48795d2dbf3">VScaleForTuning</a>.</p>

</div>
</div>

### hasCustomCallingConv() {#afd4bb75fec521c3addcd5ac9d85fdce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::hasCustomCallingConv ()</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a1aa7d773a419978d3a2d7746a8d33b52">CustomCallSavedXRegs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>.</p>

</div>
</div>

### hasFusion() {#a3dcd3f2b4734cb1363b93048216267db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::hasFusion ()</td>
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

<p>Return true if the CPU supports any kind of instruction fusion.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>

</div>
</div>

### isCallingConvWin64() {#ae5185becf2e4a0ecfb059a5ce69da205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isCallingConvWin64 (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, bool IsVarArg)</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="#a05fb81a3747dd4f76894a66c574cf99e">isTargetWindows</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad5385f408f537fc279d485c77d2463ce">llvm::CallingConv::PreserveNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca2740493172a4ce246941c8cff95e0f83">llvm::CallingConv::Swift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae41511c1ad4197da36cef403f34bac72">llvm::CallingConv::Win64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bf014c51371fcfb7c32e932c2d3b1d6">analyzeCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ae01246dc7ecdd8a082730860cd3166a1">llvm::AArch64RegisterInfo::isArgumentRegister</a>.</p>

</div>
</div>

### isLittleEndian() {#aa2ebfcf378eb3c7d2ad24c4269b3d42a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isLittleEndian ()</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a2110152d7d81909a815bc64687c3b3f2">IsLittle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abee0476f2cd1449e29bfca26702bd865">combineI8TruncStore</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae60f4de0d1e0dac32141edcacb8d20c3">performLOADCombine</a>.</p>

</div>
</div>

### isLRReservedForRA() {#a18bccbc1eec80c28e26095f1adfc62e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isLRReservedForRA ()</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a366a7f426707271b798b4355c12ce57d">llvm::AArch64RegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### isNeonAvailable() {#a170e8cc4496759d9540c7a66a72a1696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isNeonAvailable ()</td>
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

<p>Returns true if the target has NEON and the function at runtime is known to have NEON enabled (e.g.</p>


<p>the function is known not to be in streaming-SVE mode, which disables NEON instructions).</p>


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="#ab6b858c387cda4e1e520889efd26b0f6">isStreaming</a> and <a href="#a8a85664508522995fb677504d8571feb">isStreamingCompatible</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9a7f5712e4a4603a0bdd87cc08e9b1d6">llvm::AArch64InstrInfo::buildClearRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a81242a6cd5fbec123c8ed582bab0f26c">llvm::AArch64FrameLowering::canUseRedZone</a>, <a href="#aad3af6253d4e150e55f987eadad56627">getMinVectorRegisterBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad6bb7ee72f79badd15b563bf112de6e5">performBuildVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa7054eb07a4962c7516115555800c017">performFpToIntCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03b14e6aca1277bdee37639aec700ba7">performIntToFpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3cce50ef77513b8bd1cbeb48b4d9339d">tryAdvSIMDModImm16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed120dd6850080b309b6054efd2b142b">tryAdvSIMDModImm32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af27372c25a294d5d3b8ba864de3419b7">tryLowerPartialReductionToDot</a>, <a href="#aa24d6e3c045459131ced627a0ed30dcc">useSVEForFixedLengthVectors</a>, <a href="#a2f7ac4b96278419769d4bd3caa6fcf26">useSVEForFixedLengthVectors</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1fad5ec2eef05d1c11eec0ee147eabab">vectorToScalarBitmask</a>.</p>

</div>
</div>

### isStreaming() {#ab6b858c387cda4e1e520889efd26b0f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isStreaming ()</td>
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

<p>Returns true if the function has a streaming body.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#afa593225d2cd30e1d2f7b045372151ef">IsStreaming</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a3e52e7f7caf22b1bab8a06cbe8c387bf">enableMultiVectorSpillFill</a>, <a href="#acc204cbb4d2c7b9c5364d89a40deea5b">getHwModeSet</a>, <a href="#a170e8cc4496759d9540c7a66a72a1696">isNeonAvailable</a>, <a href="#a660a50ad59da76566ff9f0ab83de6cb3">isStreamingSVEAvailable</a>, <a href="#afb89e6f4c6ca2a39eafb64bb0a01a596">isSVEAvailable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aaca8ed79bbc4fe36c9285bea57d72906">tryToReplaceScalarFPConversionWithSVE</a>.</p>

</div>
</div>

### isStreamingCompatible() {#a8a85664508522995fb677504d8571feb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isStreamingCompatible ()</td>
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

<p>Returns true if the function has a streaming-compatible body.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a1dce20f668ef47c27dc3dd31e2c2858a">IsStreamingCompatible</a>.</p>


<p>Referenced by <a href="#acc204cbb4d2c7b9c5364d89a40deea5b">getHwModeSet</a>, <a href="#a170e8cc4496759d9540c7a66a72a1696">isNeonAvailable</a>, <a href="#afb89e6f4c6ca2a39eafb64bb0a01a596">isSVEAvailable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aaca8ed79bbc4fe36c9285bea57d72906">tryToReplaceScalarFPConversionWithSVE</a>.</p>

</div>
</div>

### isStreamingSVEAvailable() {#a660a50ad59da76566ff9f0ab83de6cb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isStreamingSVEAvailable ()</td>
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

<p>Returns true if the target has access to the streaming-compatible subset of SVE instructions.</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#ab6b858c387cda4e1e520889efd26b0f6">isStreaming</a>.</p>


<p>Referenced by <a href="#a97be195ccbb061fd0e4170a81e066108">isSVEorStreamingSVEAvailable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a11ecac3a9729434713c118b4e1a6f52f">tryLowerPartialReductionToWideAdd</a>.</p>

</div>
</div>

### isSVEAvailable() {#afb89e6f4c6ca2a39eafb64bb0a01a596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isSVEAvailable ()</td>
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

<p>Returns true if the target has SVE and can use the full range of SVE instructions, for example because it knows the function is known not to be in streaming-SVE mode or when the target has FEAT_FA64 enabled.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="#ab6b858c387cda4e1e520889efd26b0f6">isStreaming</a> and <a href="#a8a85664508522995fb677504d8571feb">isStreamingCompatible</a>.</p>


<p>Referenced by <a href="#aad3af6253d4e150e55f987eadad56627">getMinVectorRegisterBitWidth</a>.</p>

</div>
</div>

### isSVEorStreamingSVEAvailable() {#a97be195ccbb061fd0e4170a81e066108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isSVEorStreamingSVEAvailable ()</td>
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

<p>Returns true if the target has access to either the full range of SVE instructions, or the streaming-compatible subset of SVE instructions.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a660a50ad59da76566ff9f0ab83de6cb3">isStreamingSVEAvailable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9a7f5712e4a4603a0bdd87cc08e9b1d6">llvm::AArch64InstrInfo::buildClearRegister</a>, <a href="#ae3c0b17cadd04099c074dadd7bf3349b">getMaxSVEVectorSizeInBits</a>, <a href="#af011282932f20754ceb5a48038f4f5a6">getMinSVEVectorSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af27372c25a294d5d3b8ba864de3419b7">tryLowerPartialReductionToDot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aaca8ed79bbc4fe36c9285bea57d72906">tryToReplaceScalarFPConversionWithSVE</a> and <a href="#aa24d6e3c045459131ced627a0ed30dcc">useSVEForFixedLengthVectors</a>.</p>

</div>
</div>

### isTargetAndroid() {#a7db9992896c0e7723b498325dd3f4ddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isTargetAndroid ()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a>.</p>

</div>
</div>

### isTargetCOFF() {#af9cfdf718223ce9f4a8df0d2d7ea0f8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isTargetCOFF ()</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a>.</p>

</div>
</div>

### isTargetDarwin() {#a4d2e6b50d2d120966b45253b1ad825b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isTargetDarwin ()</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ac26dae5c257bfaab5aa15cab7255f107">llvm::AArch64RegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a2a4f0d74a9e54517b5009c2ac31503b5">llvm::AArch64RegisterInfo::getCallPreservedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aaab57b42c1306819f384fbc8917e728b">llvm::AArch64RegisterInfo::getDarwinCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ace1d2fbafd80bd71d27a949593da97f7">llvm::AArch64RegisterInfo::getDarwinCallPreservedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a1e901d70774581088feef3ee1d967ff1">llvm::AArch64RegisterInfo::getThisReturnPreservedMask</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ae01246dc7ecdd8a082730860cd3166a1">llvm::AArch64RegisterInfo::isArgumentRegister</a>.</p>

</div>
</div>

### isTargetELF() {#a4010b1841b5e6ade2f4ad494cc2169b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isTargetELF ()</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a>.</p>

</div>
</div>

### isTargetFuchsia() {#accbba019f8f5efce76ec4b6b8df113b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isTargetFuchsia ()</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a>.</p>

</div>
</div>

### isTargetILP32() {#a59137b132e07516767761d5decf7e252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isTargetILP32 ()</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a0a05a130bb4b1c97244ff98d64e0de5d">llvm::Triple::GNUILP32</a> and <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a>.</p>


<p>Referenced by <a href="#a1c9e373390ff89618b21550fd86ef93d">addrSinkUsingGEPs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ae01246dc7ecdd8a082730860cd3166a1">llvm::AArch64RegisterInfo::isArgumentRegister</a>.</p>

</div>
</div>

### isTargetIOS() {#af5ac334e783091cab6709db26f80ac6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isTargetIOS ()</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a>.</p>

</div>
</div>

### isTargetLinux() {#ae958bc5e804978a9be305c1b6f3cd63b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isTargetLinux ()</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ac46af6be29759c071896093e8a5ec220">llvm::AArch64RegisterInfo::getCustomEHPadPreservedMask</a>.</p>

</div>
</div>

### isTargetMachO() {#a6d2ea0d87e248160e202c25124c91fa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isTargetMachO ()</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a>, <a href="#a61b99558b55ac0e86169e5b7eb6ad193">classifyGlobalFunctionReference</a>, <a href="#aa2bf24e995494a7c64d8f3e02818ad30">ClassifyGlobalReference</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a469793f0416704ca132c5c91f73adbdd">produceCompactUnwindFrame</a>.</p>

</div>
</div>

### isTargetWindows() {#a05fb81a3747dd4f76894a66c574cf99e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isTargetWindows ()</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a9fd3cdd22c698232d4998d7b3ea7b21a">llvm::AArch64FunctionInfo::AArch64FunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab812d774aa563ffc2c67030a9ba1be39">llvm::AArch64TargetLowering::EmitAllocateSMESaveBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab9a65a8c0739a72de196022849b4ee67">llvm::AArch64TargetLowering::EmitAllocateZABuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ac26dae5c257bfaab5aa15cab7255f107">llvm::AArch64RegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ae01246dc7ecdd8a082730860cd3166a1">llvm::AArch64RegisterInfo::isArgumentRegister</a>, <a href="#ae5185becf2e4a0ecfb059a5ce69da205">isCallingConvWin64</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a635e26839ab9a565d13a4a538d797b68">windowsRequiresStackProbe</a>.</p>

</div>
</div>

### isWindowsArm64EC() {#ab11ed6ee239ab7c9328927b7327fc8f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isWindowsArm64EC ()</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a>.</p>


<p>Referenced by <a href="#a61b99558b55ac0e86169e5b7eb6ad193">classifyGlobalFunctionReference</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#af05862d6eaf49d6ca3a5ddac9231fd0d">llvm::AArch64RegisterInfo::explainReservedReg</a>, <a href="#a8e30069ba148ef377a6c59f68d3b8969">getChkStkName</a>, <a href="#a423d256c34effdf9184779a14b2174c8">getSecurityCheckCookieName</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a135ff03665f8746c89e91d3b802a1017">llvm::AArch64RegisterInfo::getStrictlyReservedRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>.</p>

</div>
</div>

### isXRaySupported() {#afa6a1ae5f8163866313335fec2b2c5bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isXRaySupported ()</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>

</div>
</div>

### isXRegCustomCalleeSaved() {#a8e92c78c91c9a864b7902df1502fb029}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isXRegCustomCalleeSaved (size_t i)</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a1aa7d773a419978d3a2d7746a8d33b52">CustomCallSavedXRegs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a776852734c11ae705971ee8d39e589c6">llvm::AArch64RegisterInfo::UpdateCustomCalleeSavedRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ae0d8a95e0be5b8b7c9e31abc8ead009d">llvm::AArch64RegisterInfo::UpdateCustomCallPreservedMask</a>.</p>

</div>
</div>

### isXRegisterReserved() {#abebf776aea4ae4a420fd4a2c5f02cbbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isXRegisterReserved (size_t i)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a082079e75474f048dbc714c42f7d5189">ReserveXRegister</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a135ff03665f8746c89e91d3b802a1017">llvm::AArch64RegisterInfo::getStrictlyReservedRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a0a6cffdcc5341dcc150620c684528de6">llvm::AArch64FunctionInfo::needsShadowCallStackPrologueEpilogue</a>.</p>

</div>
</div>

### isXRegisterReservedForRA() {#a60b99c1daa52f651e107fb381e3433f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::isXRegisterReservedForRA (size_t i)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Reference <a href="#a0729bd502584fc2e92ead492e9b462af">ReserveXRegisterForRA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a366a7f426707271b798b4355c12ce57d">llvm::AArch64RegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### mirFileLoaded() {#a917a79b56742eaac2db61e2a221d3011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64Subtarget::mirFileLoaded (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a12da92f702a20d5337a5258038968d09">llvm::MachineFrameInfo::computeMaxCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a99cdf1b99c0f1b7e1bf2111aa7d2eaa3">llvm::MachineFrameInfo::isMaxCallFrameSizeComputed</a>.</p>

</div>
</div>

### overrideSchedPolicy() {#a4ba514719cbb75b668499574cd6f238e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64Subtarget::overrideSchedPolicy (<a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy">MachineSchedPolicy</a> &amp; Policy, unsigned NumRegionInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#a2600398bcf6d98dea6035e652870b41a">llvm::MachineSchedPolicy::DisableLatencyHeuristic</a>, <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#a47ee8ec29daa3551f798ff4449fbf4d5">llvm::MachineSchedPolicy::OnlyBottomUp</a> and <a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy/#a0f609dd4ed94ea69ab680a7228f8786b">llvm::MachineSchedPolicy::OnlyTopDown</a>.</p>

</div>
</div>

### ParseSubtargetFeatures() {#aa63814918548c7c1b928af6385155712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64Subtarget::ParseSubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options.</p>


<p>Definition of function is auto generated by tblgen.</p>


<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>

</div>
</div>

### supportsAddressTopByteIgnored() {#a76fdf3d877571240f3d86a7a9af696e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64Subtarget::supportsAddressTopByteIgnored ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CPU has TBI (top byte of addresses is ignored during HW address translation) and OS enables it.</p>

<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>References <a href="#a934ad41b9b85827a52c2d7995f2f1bb1">TargetTriple</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#a14e78c6fbaa1fcab5d5fa0ad8f7c46d8">UseAddressTopByteIgnored</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae60f4de0d1e0dac32141edcacb8d20c3">performLOADCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad19eb01bd287efda27e7bc5ba67cd144">performSTORECombine</a>.</p>

</div>
</div>

### swiftAsyncContextIsDynamicallySet() {#afe7a4a37a90fa94396e12c3543339d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::swiftAsyncContextIsDynamicallySet ()</td>
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

<p>Return whether FrameLowering should always set the "extended frame
present" bit in FP, or set it based on a symbol in the runtime.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda0824a8c56de913d60c6f55edc0ac3148">llvm::Triple::Darwin</a>, <a href="#a8166a906911a7c72d63b98512ced2d52">getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243">llvm::Triple::IOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">llvm::Triple::MacOSX</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda2838cf6df0f09591c50d752d46c4350d">llvm::Triple::TvOS</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad">llvm::Triple::WatchOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>.</p>

</div>
</div>

### useAA() {#a64cb9803bb305e47d2e8ef2e8994aae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64Subtarget::useAA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#ad59a2062ef349882aa9c631277e37a74">UseAA</a>.</p>


<p>Referenced by <a href="#a1c9e373390ff89618b21550fd86ef93d">addrSinkUsingGEPs</a>.</p>

</div>
</div>

### useDFAforSMS() {#ad1b8466c3267e2b9aa33a626aa8fcad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::useDFAforSMS ()</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>

</div>
</div>

### useScalarIncVL() {#ad13aab0ab8d5a27a2669c863ac0cf9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64Subtarget::useScalarIncVL ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true to use the addvl/inc/dec instructions, as opposed to separate add + cnt instructions.</p>

<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#aea447642b4be61e253ef3add45801812">UseScalarIncVL</a>.</p>

</div>
</div>

### useSmallAddressing() {#a37379906f66f96e9ab4e9e087d2aa12f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::useSmallAddressing ()</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa6a2e45ae404e3f797d2d7e9f3a48949">llvm::CodeModel::Kernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a> and <a href="#af2b6b36547a598d0c25501aad09e6433">TLInfo</a>.</p>


<p>Referenced by <a href="#aa2bf24e995494a7c64d8f3e02818ad30">ClassifyGlobalReference</a>.</p>

</div>
</div>

### useSVEForFixedLengthVectors() {#aa24d6e3c045459131ced627a0ed30dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::useSVEForFixedLengthVectors ()</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="#af011282932f20754ceb5a48038f4f5a6">getMinSVEVectorSizeInBits</a>, <a href="#a170e8cc4496759d9540c7a66a72a1696">isNeonAvailable</a> and <a href="#a97be195ccbb061fd0e4170a81e066108">isSVEorStreamingSVEAvailable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8b803a5cecda412b4f4984ad8db7201e">performFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad19eb01bd287efda27e7bc5ba67cd144">performSTORECombine</a> and <a href="#a2f7ac4b96278419769d4bd3caa6fcf26">useSVEForFixedLengthVectors</a>.</p>

</div>
</div>

### useSVEForFixedLengthVectors() {#a2f7ac4b96278419769d4bd3caa6fcf26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::useSVEForFixedLengthVectors (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a7712dd4392b7eb944b709ac8442634d9">llvm::EVT::getFixedSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a920f0719057d7352f9da10908859368d">llvm::EVT::isFixedLengthVector</a>, <a href="#a170e8cc4496759d9540c7a66a72a1696">isNeonAvailable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#aab727392cab1f48b15483374f8251375">llvm::AArch64::SVEBitsPerBlock</a> and <a href="#aa24d6e3c045459131ced627a0ed30dcc">useSVEForFixedLengthVectors</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### initializeProperties() {#aa9aa6058fd886ec04adfbfbf409b97b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64Subtarget::initializeProperties (bool HasMinSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize properties based on the selected processor family.</p>

<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>

</div>
</div>

### initializeSubtargetDependencies() {#a225878209bbc8cbcdc573403754ba950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64Subtarget &amp; AArch64Subtarget::initializeSubtargetDependencies (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPUString, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPUString, bool HasMinSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>initializeSubtargetDependencies - Initializes using CPUString and the passed in feature string so that we can use initializer lists for subtarget initialization.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ARMProcFamily {#a283b368e24b91ca9b4a3960d4fee4876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMProcFamilyEnum llvm::AArch64Subtarget::ARMProcFamily = <a href="#a2908c571a60104989fdef613e8c57caea0893fc2470e30fda5ddf6a8c26f4561c">Generic</a></td>
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

<p>ARMProcFamily - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> processor family: Cortex-A53, Cortex-A57, and others.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a5cbd2c43522cb4157a9c6853aefc438c">getProcFamily</a>.</p>

</div>
</div>

### CacheLineSize {#a9b3933070c0c7cd93e57df1a4795da26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AArch64Subtarget::CacheLineSize = 0</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a5529884a7035031f480f0f80842380b4">getCacheLineSize</a>.</p>

</div>
</div>

### CallLoweringInfo {#a5deed214062763eccdb97587cd61e431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;CallLowering&gt; llvm::AArch64Subtarget::CallLoweringInfo</td>
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

<p>GlobalISel related APIs.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> and <a href="#a0b6950acd6b80c51ff290beb2470f158">getCallLowering</a>.</p>

</div>
</div>

### CustomCallSavedXRegs {#a1aa7d773a419978d3a2d7746a8d33b52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::AArch64Subtarget::CustomCallSavedXRegs</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a>, <a href="#afd4bb75fec521c3addcd5ac9d85fdce1">hasCustomCallingConv</a> and <a href="#a8e92c78c91c9a864b7902df1502fb029">isXRegCustomCalleeSaved</a>.</p>

</div>
</div>

### DefaultSVETFOpts {#a192bbbe8fa7ae7351f69e7c07119ef81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TailFoldingOpts llvm::AArch64Subtarget::DefaultSVETFOpts = <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafab9f5c797ebbf55adccdd8539a65a0241">TailFoldingOpts::Disabled</a></td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a9cc5a7590a9f8f14eb1d58d3fc57c7e2">getSVETailFoldingDefaultOpts</a>.</p>

</div>
</div>

### EnableSubregLiveness {#ae0f9271b5e0c76b7eed6f7d761b91ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::EnableSubregLiveness</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> and <a href="#a9a234fe3a4d41cb72f556a13a13f302b">enableSubRegLiveness</a>.</p>

</div>
</div>

### EpilogueVectorizationMinVF {#a3ae33846ba3a76325d59ba6a1c74fa4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::EpilogueVectorizationMinVF = 16</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#ae351e859f15d75e7db99f9b238b4cee5">getEpilogueVectorizationMinVF</a>.</p>

</div>
</div>

### FrameLowering {#a4becb54f5d6a9482ab6a57bf299446d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64FrameLowering llvm::AArch64Subtarget::FrameLowering</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#afe1204d0641bf774be3ad6d95483af02">getFrameLowering</a>.</p>

</div>
</div>

### GatherOverhead {#a2aa4482559c05721935e3268644f866c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::GatherOverhead = 10</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a603ec68113d25d526bd2ac979f3aecc0">getGatherOverhead</a>.</p>

</div>
</div>

### InlineAsmLoweringInfo {#af89b6dde02852af95a1cf25a09364489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InlineAsmLowering&gt; llvm::AArch64Subtarget::InlineAsmLoweringInfo</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> and <a href="#a504a8c9446c716da678f5ad52e8b04b7">getInlineAsmLowering</a>.</p>

</div>
</div>

### InstrInfo {#af1e1c6731e7afd31d2084082b15d458a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64InstrInfo llvm::AArch64Subtarget::InstrInfo</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> and <a href="#a36aaf68c65aa593a22066976ee02810a">getInstrInfo</a>.</p>

</div>
</div>

### InstSelector {#a20c4bbc27d200153fd3580d02fb0f720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InstructionSelector&gt; llvm::AArch64Subtarget::InstSelector</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> and <a href="#a9366f20b119180f1c68debd2555392e8">getInstructionSelector</a>.</p>

</div>
</div>

### IsLittle {#a2110152d7d81909a815bc64687c3b3f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::IsLittle</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> and <a href="#aa2ebfcf378eb3c7d2ad24c4269b3d42a">isLittleEndian</a>.</p>

</div>
</div>

### IsStreaming {#afa593225d2cd30e1d2f7b045372151ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::IsStreaming</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> and <a href="#ab6b858c387cda4e1e520889efd26b0f6">isStreaming</a>.</p>

</div>
</div>

### IsStreamingCompatible {#a1dce20f668ef47c27dc3dd31e2c2858a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64Subtarget::IsStreamingCompatible</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> and <a href="#a8a85664508522995fb677504d8571feb">isStreamingCompatible</a>.</p>

</div>
</div>

### Legalizer {#af6242f2929d57d293b14ba19afc09e78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LegalizerInfo&gt; llvm::AArch64Subtarget::Legalizer</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> and <a href="#ad6960168c46441c38715c4afb3aa968a">getLegalizerInfo</a>.</p>

</div>
</div>

### MaxBytesForLoopAlignment {#af8014e78305810558e44e9b9194b563f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::MaxBytesForLoopAlignment = 0</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a6d48d262c4d851861f24550fb1014164">getMaxBytesForLoopAlignment</a>.</p>

</div>
</div>

### MaxInterleaveFactor {#ae35348ac382b7f2b970cbd32e051f829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64Subtarget::MaxInterleaveFactor = 2</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a7b5e15aa57baa83db726cee3338c25b7">getMaxInterleaveFactor</a>.</p>

</div>
</div>

### MaxJumpTableSize {#aa8e488c0af0ac3b5b3804c9ba2e882b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::MaxJumpTableSize = 0</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a428f4cfc3de60a3999ac03dc56072bf6">getMaximumJumpTableSize</a>.</p>

</div>
</div>

### MaxPrefetchIterationsAhead {#a53802a9885c8d3715a584e87d5b58e47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::MaxPrefetchIterationsAhead = UINT_MAX</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#ac353afb8233313c3b15ae5a6e61136ab">getMaxPrefetchIterationsAhead</a>.</p>

</div>
</div>

### MaxSVEVectorSizeInBits {#adbf5d5f04e136fcc8888ff37491c264a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::MaxSVEVectorSizeInBits</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> and <a href="#ae3c0b17cadd04099c074dadd7bf3349b">getMaxSVEVectorSizeInBits</a>.</p>

</div>
</div>

### MinimumJumpTableEntries {#ad5c87833696cd728e1abfe0995ccf43d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::MinimumJumpTableEntries = 4</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a29ca38d13438677838d19993b810757c">getMinimumJumpTableEntries</a>.</p>

</div>
</div>

### MinPrefetchStride {#a949048c787f5a5f0539c405c5530d687}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AArch64Subtarget::MinPrefetchStride = 1</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a1993d88329db5bf42d3d1956c47cb946">getMinPrefetchStride</a>.</p>

</div>
</div>

### MinSVEVectorSizeInBits {#ab773b1501fea6965ed8f896ba2e71468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::MinSVEVectorSizeInBits</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> and <a href="#af011282932f20754ceb5a48038f4f5a6">getMinSVEVectorSizeInBits</a>.</p>

</div>
</div>

### MinVectorRegisterBitWidth {#a837e4a0338312af979138355d05834b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::MinVectorRegisterBitWidth = 64</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#aad3af6253d4e150e55f987eadad56627">getMinVectorRegisterBitWidth</a>.</p>

</div>
</div>

### PrefetchDistance {#a7436edeb320ea803a853a7c0d161a188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::AArch64Subtarget::PrefetchDistance = 0</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#aff68da1da5bbabd26f8d31500855f330">getPrefetchDistance</a>.</p>

</div>
</div>

### PrefFunctionAlignment {#a7e2b15fbec6c266f7444ab03d8d9230f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::AArch64Subtarget::PrefFunctionAlignment</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a6b171f93524a8d0d1c0772479a1703c5">getPrefFunctionAlignment</a>.</p>

</div>
</div>

### PrefLoopAlignment {#a5f8c75c233bb1f77e3535e8038630f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::AArch64Subtarget::PrefLoopAlignment</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a66c91211a6770a537c3cfc057cabd1fa">getPrefLoopAlignment</a>.</p>

</div>
</div>

### RegBankInfo {#a2a7d4e12e33fb717fc55dd5ff6f9ad05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;RegisterBankInfo&gt; llvm::AArch64Subtarget::RegBankInfo</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> and <a href="#af2f55f16e39b3b5b9047278790c2cb15">getRegBankInfo</a>.</p>

</div>
</div>

### ReserveXRegister {#a082079e75474f048dbc714c42f7d5189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::AArch64Subtarget::ReserveXRegister</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a>, <a href="#a61b3a50936d453ae4dcadc704958bb35">getNumXRegisterReserved</a> and <a href="#abebf776aea4ae4a420fd4a2c5f02cbbd">isXRegisterReserved</a>.</p>

</div>
</div>

### ReserveXRegisterForRA {#a0729bd502584fc2e92ead492e9b462af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::AArch64Subtarget::ReserveXRegisterForRA</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a>, <a href="#a61b3a50936d453ae4dcadc704958bb35">getNumXRegisterReserved</a> and <a href="#a60b99c1daa52f651e107fb381e3433f9">isXRegisterReservedForRA</a>.</p>

</div>
</div>

### ScatterOverhead {#ae9fc63fa8f564800eadb3fd11e811451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::ScatterOverhead = 10</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#ad83719661ffe575e99f4d697357696ef">getScatterOverhead</a>.</p>

</div>
</div>

### StreamingHazardSize {#a46a039a63380cfb0a407ebbf01cb0f8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::AArch64Subtarget::StreamingHazardSize</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a> and <a href="#a83086cbbcef2fd09005f6e175f7f14f4">getStreamingHazardSize</a>.</p>

</div>
</div>

### TargetTriple {#a934ad41b9b85827a52c2d7995f2f1bb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::AArch64Subtarget::TargetTriple</td>
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

<p>TargetTriple - What processor and OS we're targeting.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a>, <a href="#a8166a906911a7c72d63b98512ced2d52">getTargetTriple</a>, <a href="#a7db9992896c0e7723b498325dd3f4ddb">isTargetAndroid</a>, <a href="#af9cfdf718223ce9f4a8df0d2d7ea0f8f">isTargetCOFF</a>, <a href="#a4d2e6b50d2d120966b45253b1ad825b4">isTargetDarwin</a>, <a href="#a4010b1841b5e6ade2f4ad494cc2169b0">isTargetELF</a>, <a href="#accbba019f8f5efce76ec4b6b8df113b1">isTargetFuchsia</a>, <a href="#a59137b132e07516767761d5decf7e252">isTargetILP32</a>, <a href="#af5ac334e783091cab6709db26f80ac6e">isTargetIOS</a>, <a href="#ae958bc5e804978a9be305c1b6f3cd63b">isTargetLinux</a>, <a href="#a6d2ea0d87e248160e202c25124c91fa9">isTargetMachO</a>, <a href="#a05fb81a3747dd4f76894a66c574cf99e">isTargetWindows</a>, <a href="#ab11ed6ee239ab7c9328927b7327fc8f1">isWindowsArm64EC</a> and <a href="#a76fdf3d877571240f3d86a7a9af696e7">supportsAddressTopByteIgnored</a>.</p>

</div>
</div>

### TLInfo {#af2b6b36547a598d0c25501aad09e6433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64TargetLowering llvm::AArch64Subtarget::TLInfo</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a033ed3ccb4d48ca276a60b87127b344d">AArch64Subtarget</a>, <a href="#a66b26e824dd1b4bb346cd20278651032">getTargetLowering</a> and <a href="#a37379906f66f96e9ab4e9e087d2aa12f">useSmallAddressing</a>.</p>

</div>
</div>

### TSInfo {#a3e7e95e8e39f20c2cb2965a84b41ab26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64SelectionDAGInfo llvm::AArch64Subtarget::TSInfo</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a039ee1fe628086a2c2a4a10db94e0758">getSelectionDAGInfo</a>.</p>

</div>
</div>

### VectorInsertExtractBaseCost {#a663b081baf6a1824b31a9bff266a6f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AArch64Subtarget::VectorInsertExtractBaseCost = 2</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#a59fa8edbdb0dcf971dccf48d88b36dab">getVectorInsertExtractBaseCost</a>.</p>

</div>
</div>

### VScaleForTuning {#a313cf778d3a8a4702205f48795d2dbf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64Subtarget::VScaleForTuning = 1</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>.</p>


<p>Referenced by <a href="#ae6608e44f816255878f5e180f4330641">getVScaleForTuning</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
