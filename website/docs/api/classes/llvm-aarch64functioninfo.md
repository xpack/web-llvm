---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aarch64functioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64FunctionInfo` Class

<p><a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo">AArch64FunctionInfo</a> - This class is derived from <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> and contains private AArch64-specific information for each <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AArch64FunctionInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">Target/AArch64/AArch64MachineFunctionInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> - This class can be derived from and used by targets to hold private target-specific information for each <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>. <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abab64cb03995f26dc16c181412eedea8">SetOfInstructions</a> = <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 16 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82309f98f5a090fcf8661e69a2db43b3">MILOHArgs</a> = <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/milohdirective/#a8c14db030a4ebfb6ba901b70456b76b1">MILOHDirective::LOHArgs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46fb1f1d55a6ae41e58aa1aca1645eca">MILOHContainer</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/milohdirective">MILOHDirective</a>, 32 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd3cdd22c698232d4998d7b3ea7b21a">AArch64FunctionInfo</a> (const Function &amp;F, const AArch64Subtarget *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4cf5140a6baf36f029924fa4c592e64">clone</a> (BumpPtrAllocator &amp;Allocator, MachineFunction &amp;DestMF, const DenseMap&lt; MachineBasicBlock *, MachineBasicBlock * &gt; &amp;Src2DstMBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make a functionally equivalent copy of this <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> in <span class="doxyComputerOutput">MF</span>. <a href="#af4cf5140a6baf36f029924fa4c592e64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6085917e6c5f643ea01c715f90bf80f7">setPredicateRegForFillSpill</a> (unsigned Reg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4810ed3af6f235900d3417f70d143e4">getPredicateRegForFillSpill</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae50d6a3d63e6a9bd955965a39606db99">getSMESaveBufferAddr</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad046eec280d118d2c2b650be4425a6e4">setSMESaveBufferAddr</a> (Register Reg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef1ba3874d6358f607fe1b882312cd2f">isSMESaveBufferUsed</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8d6963b19204e698d4ca932e087402f">setSMESaveBufferUsed</a> (bool Used=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4585aeeb951dcbaa41a190908f1c54f">getPStateSMReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ecdb920d3ec70d949ec71672c9ca521">setPStateSMReg</a> (Register Reg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc80535a1cfd78ba171d991a15665c0c">getVGIdx</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a608e93e8987b7a2845867fb9e16f0a">setVGIdx</a> (unsigned Idx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2976aa2ecb71890f37e7ec9f8b880cb">getStreamingVGIdx</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a755f8c328cc1e0c201614b296c2259f2">setStreamingVGIdx</a> (unsigned FrameIdx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a093615ad7a3c3eac2dc8c8655d0ac00b">isSVECC</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22ad95b4993a4bf58f9f0583379fbb25">setIsSVECC</a> (bool s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/tpidr2object">TPIDR2Object</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434e2f6f33183ce02a92b09b088c8cb0">getTPIDR2Obj</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaf73d373f54aac1716146ed80e38b2d">initializeBaseYamlFields</a> (const yaml::AArch64FunctionInfo &amp;YamlMFI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3983ecc9903d3cb991aa6fa865f9419">getBytesInStackArgArea</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b6e1593f20bacc0f43b1254988ddd18">setBytesInStackArgArea</a> (unsigned bytes)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d962df55ff4ce124096ee9501e121c8">getArgumentStackToRestore</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa54f4f948a89516a5d77a58fb8a18d7">setArgumentStackToRestore</a> (unsigned bytes)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e887116bba8ca08bd717cbf2cbd1ac6">getTailCallReservedStack</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45c3e4d88953eccee2e33f9b7d18420f">setTailCallReservedStack</a> (unsigned bytes)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7bb9da1cdb51abc81f080b265948015">hasCalculatedStackSizeSVE</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1093619213bf0b465ab1d5fc1e44824">setStackSizeSVE</a> (uint64_t S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b316ba6e060bc850312c3d294130878">getStackSizeSVE</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a839720705cb2401eb2e9dd30001e4ad5">hasStackFrame</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bb844d18888aaa95f53360509017797">setHasStackFrame</a> (bool s)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab325d3abfa4e1b6a0aba6d6761203806">isStackRealigned</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5a3112b5a4dd39005325e09e523963b">setStackRealigned</a> (bool s)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbfedea21bb3ae3e646a4c2995e1f75e">hasCalleeSaveStackFreeSpace</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a476ff010131b70eb3cb38dd1477d01ae">setCalleeSaveStackHasFreeSpace</a> (bool s)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89194de9866090f36bd192e81aeb1e1a">isSplitCSR</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a538aa174513553563cbd28d78b7222df">setIsSplitCSR</a> (bool s)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4761d8d142e4f5eca20e2a37fbd1375a">setLocalStackSize</a> (uint64_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fded0dfc6857b39fcf1ed029ca145ef">getLocalStackSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a648d29a4010d7cc1be7785eab399d5fa">setOutliningStyle</a> (const std::string &amp;Style)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adda0b11bd1bc8d81e88218a69f78b309">getOutliningStyle</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75c0e90d15611f0111db4f66711886d3">setCalleeSavedStackSize</a> (unsigned Size)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a217c3db3b137e03bd6ade29bb9999ac9">getCalleeSavedStackSize</a> (const MachineFrameInfo &amp;MFI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa83a2fcc4197136c064fc194da783ea">getCalleeSavedStackSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbd6275072f7ab65915b763deb5952fc">setSVECalleeSavedStackSize</a> (unsigned Size)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef92fa2f6c53b6fda74605b0125d7667">getSVECalleeSavedStackSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa58eca8243bee935ada875a71acfafa">setMinMaxSVECSFrameIndex</a> (int Min, int Max)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeff5274f6e233895a572e4d6bc098516">getMinSVECSFrameIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52f519aabe90a43ea18e5939533a6a5d">getMaxSVECSFrameIndex</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65d272f48967ff5d6cb87e49a03b7e5c">incNumLocalDynamicTLSAccesses</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8613af92f6f5d07720aa5c10c7ecbed">getNumLocalDynamicTLSAccesses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac81232e8ac34e95d748e2e31e43482b5">hasRedZone</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81917a56aebf01a4df724caade1dfd80">setHasRedZone</a> (bool s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e56ab8686aecd83b84810e257d84b64">getVarArgsStackIndex</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3579b908528b4652650ed24f8c5044c3">setVarArgsStackIndex</a> (int Index)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a956af6c01008388fbc3e9db7257176ae">getVarArgsStackOffset</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bce000887a512db38a7918386165b11">setVarArgsStackOffset</a> (unsigned Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78ef05ed4db7991fa28264d76e8a5fc5">getVarArgsGPRIndex</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f581cfdb5a35bbcc3968b9ee7ffa4c6">setVarArgsGPRIndex</a> (int Index)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae1cc37c03dc88bd71db86b6180b9d71">getVarArgsGPRSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5aaf1970a8d2d5cbe00aacabb37e011">setVarArgsGPRSize</a> (unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a887b26a707f64e1188ebb84e3f2e30">getVarArgsFPRIndex</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3d5db606772049b0fc898bbfc34cf73">setVarArgsFPRIndex</a> (int Index)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a258b3288d244094217895ed0150a65d5">getVarArgsFPRSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91c58dd5b17822ae117072fdc3ca6c84">setVarArgsFPRSize</a> (unsigned Size)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29ee8562c33732a42e2894f5db67874">hasStackHazardSlotIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f68e3671f98f25c18b29b7f14a13ed8">getStackHazardSlotIndex</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac58b635e8d3494e5a97d6c8de5be18bf">setStackHazardSlotIndex</a> (int Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83fb05995d77e69e671f741020f223af">getStackHazardCSRSlotIndex</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfcebd83a34e4304e6cdfab40e6f9244">setStackHazardCSRSlotIndex</a> (int Index)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0a89286bc67d60002c353f80503e8cd">getSRetReturnReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca78815d0b439cadb992c6436df5d72b">setSRetReturnReg</a> (unsigned Reg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5bb23b4f732fe77fee2cba281aa218f">getJumpTableEntrySize</a> (int Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1eea0099521259e014a19f926ad9668">getJumpTableEntryPCRelSymbol</a> (int Idx) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedc3f83fd9f38499f104d6c4a782df7d">setJumpTableEntryInfo</a> (int Idx, unsigned Size, MCSymbol *PCRelSym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#abab64cb03995f26dc16c181412eedea8">SetOfInstructions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ad1c8eb92bcb0cc7e14c2ebd5a2b1dc">getLOHRelated</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a46fb1f1d55a6ae41e58aa1aca1645eca">MILOHContainer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebeb489e565baf5a8403bcc1901788ea">getLOHContainer</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03324cd61d637f496c9f19984b59df94">addLOHDirective</a> (MCLOHType Kind, MILOHArgs Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a LOH directive of this <span class="doxyComputerOutput">Kind</span> and this <span class="doxyComputerOutput">Args</span>. <a href="#a03324cd61d637f496c9f19984b59df94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/forwardedregister">ForwardedRegister</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e173b1457c01a05c1200c2624478b0b">getForwardedMustTailRegParms</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92b18d1bf9d1db22ceb01054ebe94983">getTaggedBasePointerIndex</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6cfc93683b52a3179bca019b1b2bc71">setTaggedBasePointerIndex</a> (int Index)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f8cb59d120af794be129a54a0343fb">getTaggedBasePointerOffset</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac585fc64555950b121905c6d28306107">setTaggedBasePointerOffset</a> (unsigned Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf50af86f6d1f7d2dcf35e0ee18d1d3">getCalleeSaveBaseToFrameRecordOffset</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26df76f51f398bf4954036667563e2be">setCalleeSaveBaseToFrameRecordOffset</a> (int Offset)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a606dce8fc572cecd6eab6f419f11aa6d">shouldSignReturnAddress</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a805799c2737c33d9f64de8d5348dfac0">shouldSignReturnAddress</a> (bool SpillsLR) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a6cffdcc5341dcc150620c684528de6">needsShadowCallStackPrologueEpilogue</a> (MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd791302f998513ddb029c191f550232">shouldSignWithBKey</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4df127df519885541003937cde4f22d6">hasELFSignedGOT</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6e80daebbb83fe475e3aca10a41599b">getSigningInstrLabel</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ac6a6e00198488a151eb5d1fb3e911e">setSigningInstrLabel</a> (MCSymbol *Label)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1fb12997102391efd9333742ae324b0">isMTETagged</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13ec8ba54ec7daae44e617496a3f74d6">branchTargetEnforcement</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e0d34e679046b3b27cddbb69c1f985a">branchProtectionPAuthLR</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc2e4041e3018454afab435e28be39b">setHasSwiftAsyncContext</a> (bool HasContext)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe26a416b693ebc37154faaded2cdfc9">hasSwiftAsyncContext</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf1ee0c8e45ead80ed78b4866d9cbee">setSwiftAsyncContextFrameIdx</a> (int FI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3cba3aa9b7b65f2db15e631bbd27f08">getSwiftAsyncContextFrameIdx</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa6625e357c6806a89b36759ae16b630">needsDwarfUnwindInfo</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1bf187d995b982c232e7c73bb45c832">needsAsyncDwarfUnwindInfo</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f85995f165e15b5c4ce247e5580fefe">hasStreamingModeChanges</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa7a17dc76056b610a1935e582ae19e6">setHasStreamingModeChanges</a> (bool HasChanges)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fa17036c1831538491a34f3715ca4a7">hasStackProbing</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79cb24e9f1731f9f49f84400acf9b738">getStackProbeSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58703260f466ae0d91a79e2cf7cbf2d4">BytesInStackArgArea</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of bytes of arguments this function has on the stack. <a href="#a58703260f466ae0d91a79e2cf7cbf2d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e84fd402eb0e5b00f9aaacd68628bf3">ArgumentStackToRestore</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bytes to restore to deallocate space for incoming arguments. <a href="#a0e84fd402eb0e5b00f9aaacd68628bf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad630a9675c3e9d86f352cf8002b38007">TailCallReservedStack</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Space just below incoming stack pointer reserved for arguments being passed on the stack during a tail call. <a href="#ad630a9675c3e9d86f352cf8002b38007">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3491ab50edcdf5c5254c168aba15ca3">HasStackFrame</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HasStackFrame - True if this function has a stack frame. <a href="#aa3491ab50edcdf5c5254c168aba15ca3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9d72456d49216fcccf3d0c8ea27bad6">LocalStackSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Amount of stack frame size, not including callee-saved registers. <a href="#ab9d72456d49216fcccf3d0c8ea27bad6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa357658054f0f317490b05be25974c73">MinSVECSFrameIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The start and end frame indices for the SVE callee saves. <a href="#aa357658054f0f317490b05be25974c73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b25b07744a6ab1038e88cb184f0701b">MaxSVECSFrameIndex</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcaa97f6e7e5c8d736c6ca5911c2f567">CalleeSavedStackSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Amount of stack frame size used for saving callee-saved registers. <a href="#afcaa97f6e7e5c8d736c6ca5911c2f567">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c4f3bd4101ea12629999b58ed66f4d4">SVECalleeSavedStackSize</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6e1791eaa5eff185a2ce5eb58c4f15d">HasCalleeSavedStackSize</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7572557678506721412fa237ffc2a04d">NumLocalDynamicTLSAccesses</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of TLS accesses using the special (combinable) <em>TLS_MODULE_BASE</em> symbol. <a href="#a7572557678506721412fa237ffc2a04d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53afd4629d43ffabce76a6aabc4d90e4">VarArgsStackIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FrameIndex for start of varargs area for arguments passed on the stack. <a href="#a53afd4629d43ffabce76a6aabc4d90e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af29b1fa16125fe684ad3ed7639fdebe0">VarArgsStackOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset of start of varargs area for arguments passed on the stack. <a href="#af29b1fa16125fe684ad3ed7639fdebe0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83e0d9c1d8b7b806d759a65748260a58">VarArgsGPRIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FrameIndex for start of varargs area for arguments passed in general purpose registers. <a href="#a83e0d9c1d8b7b806d759a65748260a58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb95de0ee1b30dd97cd1cb2eca124976">VarArgsGPRSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of the varargs area for arguments passed in general purpose registers. <a href="#afb95de0ee1b30dd97cd1cb2eca124976">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a586390d03a4bbdc8d16e48efb8149d40">VarArgsFPRIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FrameIndex for start of varargs area for arguments passed in floating-point registers. <a href="#a586390d03a4bbdc8d16e48efb8149d40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47be76c15edc026c4422083e879a3413">VarArgsFPRSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of the varargs area for arguments passed in floating-point registers. <a href="#a47be76c15edc026c4422083e879a3413">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52baf0c55b705d3442d037c7f6ffd29e">StackHazardSlotIndex</a> = std::numeric_limits&lt;int&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The stack slots used to add space between FPR and GPR accesses when using hazard padding. <a href="#a52baf0c55b705d3442d037c7f6ffd29e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65577e1cd9c6eb28ebb645118ac3fa93">StackHazardCSRSlotIndex</a> = std::numeric_limits&lt;int&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d522314c7549004403d9e58b77437d1">IsSplitCSR</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this function has a subset of CSRs that is handled explicitly via copies. <a href="#a3d522314c7549004403d9e58b77437d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a508dc03acc88be62d6d94db3d9be3f17">StackRealigned</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True when the stack gets realigned dynamically because the size of stack frame is unknown at compile time. <a href="#a508dc03acc88be62d6d94db3d9be3f17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afafc0621143fdbe09eeb03b9e794f93c">CalleeSaveStackHasFreeSpace</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True when the callee-save stack area has unused gaps that may be used for other stack allocations. <a href="#afafc0621143fdbe09eeb03b9e794f93c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a120414f7823be1f39e6882836a0118">SRetReturnReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SRetReturnReg - sret lowering includes returning the value of the returned struct in a register. <a href="#a3a120414f7823be1f39e6882836a0118">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0551d1a7842076eb9cc071933dfa283a">StackSizeSVE</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SVE stack size (for predicates and data vectors) are maintained here rather than in FrameInfo, as the placement and Stack IDs are target specific. <a href="#a0551d1a7842076eb9cc071933dfa283a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45c681b558643514688047b44c12d08a">HasCalculatedStackSizeSVE</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HasCalculatedStackSizeSVE indicates whether StackSizeSVE is valid. <a href="#a45c681b558643514688047b44c12d08a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6800da1b590d7aea61dd05726525de74">HasRedZone</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has a value when it is known whether or not the function uses a redzone, and no value otherwise. <a href="#a6800da1b590d7aea61dd05726525de74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/forwardedregister">ForwardedRegister</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a535ac4b567bb34d7715fc6aae53e7038">ForwardedMustTailRegParms</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ForwardedMustTailRegParms - A list of virtual and physical registers that must be forwarded to every musttail call. <a href="#a535ac4b567bb34d7715fc6aae53e7038">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a627503a4914378cd3dbccccad95233c1">TaggedBasePointerIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FrameIndex for the tagged base pointer. <a href="#a627503a4914378cd3dbccccad95233c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefbc57d8f869d47b5e76e437a252f563">TaggedBasePointerOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset from SP-at-entry to the tagged base pointer. <a href="#aefbc57d8f869d47b5e76e437a252f563">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470a6f17af1e08e00f00b192f456dfd0">OutliningStyle</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OutliningStyle denotes, if a function was outined, how it was outlined, e.g. <a href="#a470a6f17af1e08e00f00b192f456dfd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36a8052eea6fc0eca77afb0b13a08e6d">CalleeSaveBaseToFrameRecordOffset</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96e803bdc8a9722cfc11f228dca75e98">SignReturnAddress</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SignReturnAddress is true if PAC-RET is enabled for the function with defaults being sign non-leaf functions only, with the B key. <a href="#a96e803bdc8a9722cfc11f228dca75e98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77bec87c61af57a81abf8acf69568e89">SignReturnAddressAll</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SignReturnAddressAll modifies the default PAC-RET mode to signing leaf functions as well. <a href="#a77bec87c61af57a81abf8acf69568e89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6365cf34c46b4fc7f932a49fe44ed653">SignWithBKey</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SignWithBKey modifies the default PAC-RET mode to signing with the B key. <a href="#a6365cf34c46b4fc7f932a49fe44ed653">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78810a1c89098ed79460e9203cff03c2">HasELFSignedGOT</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HasELFSignedGOT is true if the target binary format is <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> and the IR module containing the corresponding function has "ptrauth-elf-got" flag set to 1. <a href="#a78810a1c89098ed79460e9203cff03c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6884c391afe1cba372770022b74fde">SignInstrLabel</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SigningInstrOffset captures the offset of the PAC-RET signing instruction within the prologue, so it can be re-used for authentication in the epilogue when using PC as a second salt (FEAT_PAuth_LR) <a href="#abe6884c391afe1cba372770022b74fde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99a4b697ebc206fd05d20fd2165c028b">BranchTargetEnforcement</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BranchTargetEnforcement enables placing BTI instructions at potential indirect branch destinations. <a href="#a99a4b697ebc206fd05d20fd2165c028b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f104c2ad2622585d5fc3ed382d40de6">BranchProtectionPAuthLR</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates that SP signing should be diversified with PC as-per PAuthLR. <a href="#a5f104c2ad2622585d5fc3ed382d40de6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb57cd6a42715716faca96505a38c0fe">HasSwiftAsyncContext</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this function has an extended frame record [Ctx, FP, LR]. <a href="#aeb57cd6a42715716faca96505a38c0fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5567d64b531237284fdd7883135d7fbb">SwiftAsyncContextFrameIdx</a> = std::numeric_limits&lt;int&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The stack slot where the Swift asynchronous context is stored. <a href="#a5567d64b531237284fdd7883135d7fbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645b33772fd89e7a24564e66040e07fc">IsMTETagged</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e16bd0cc17ce91581f469255e2fad12">IsSVECC</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function has Scalable Vector or Scalable <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> register argument or return type. <a href="#a5e16bd0cc17ce91581f469255e2fad12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/tpidr2object">TPIDR2Object</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21fefc8bd17a8233a86b86ae917153b9">TPIDR2</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The frame-index for the TPIDR2 object used for lazy saves. <a href="#a21fefc8bd17a8233a86b86ae917153b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c4ac42003d880b5cfed0ca3a6d258e1">HasStreamingModeChanges</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this function changes streaming mode within the function. <a href="#a6c4ac42003d880b5cfed0ca3a6d258e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a148c1b911ff78e07de7cd77bd6041d1d">NeedsDwarfUnwindInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the function need unwind information. <a href="#a148c1b911ff78e07de7cd77bd6041d1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac94dcfff6fa3d33b7c457a38157d728c">NeedsAsyncDwarfUnwindInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the function need asynchronous unwind information. <a href="#ac94dcfff6fa3d33b7c457a38157d728c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d4cad5aefc49719371fe3b770ce5334">StackProbeSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b858c1e5cdbe8b9573116ccf4670936">PStateSMReg</a> = <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a4aa6aac0f36c1123df3686f7b4150d2c">MCRegister::NoRegister</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a038a97c8fc086da556e4ba6b6f87c5ea">SMESaveBufferAddr</a> = <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a4aa6aac0f36c1123df3686f7b4150d2c">MCRegister::NoRegister</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65be06223c61b2238dcd8d008c12da21">SMESaveBufferUsed</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67266cd4e22914b772aae4b2726023c4">PredicateRegForFillSpill</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35e3469cd4741b490ea87586329b3851">VGIdx</a> = std::numeric_limits&lt;int&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58f93a077f91d648c660a469d5f67206">StreamingVGIdx</a> = std::numeric_limits&lt;int&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a46fb1f1d55a6ae41e58aa1aca1645eca">MILOHContainer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af71d14c7834e07b37c6c9ba603e7e05e">LOHContainerSet</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abab64cb03995f26dc16c181412eedea8">SetOfInstructions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0543bc83e041960e9140e1bcbb3ad631">LOHRelated</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38bebfe203d8a5e555fb9229974ffc5a">JumpTableEntryInfo</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo">AArch64FunctionInfo</a> - This class is derived from <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> and contains private AArch64-specific information for each <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### MILOHArgs {#a82309f98f5a090fcf8661e69a2db43b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AArch64FunctionInfo::MILOHArgs =  MILOHDirective::LOHArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### MILOHContainer {#a46fb1f1d55a6ae41e58aa1aca1645eca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AArch64FunctionInfo::MILOHContainer =  SmallVector&lt;MILOHDirective, 32&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### SetOfInstructions {#abab64cb03995f26dc16c181412eedea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AArch64FunctionInfo::SetOfInstructions =  SmallPtrSet&lt;const MachineInstr *, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AArch64FunctionInfo() {#a9fd3cdd22c698232d4998d7b3ea7b21a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64FunctionInfo::AArch64FunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp">AArch64MachineFunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a86397deb1d9d25f7a17ce22c4d66482f">llvm::mdconst::extract_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#afe1204d0641bf774be3ad6d95483af02">llvm::AArch64Subtarget::getFrameLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp/#a44c6c20fa83221edf83c14760e2878f4">GetSignReturnAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a258e7041d4a768f291a4023db2b898b5">llvm::TargetFrameLowering::getTransientStackAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp/#a94b61556b849102cdcace07d0a404434">hasELFSignedGOTHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a05fb81a3747dd4f76894a66c574cf99e">llvm::AArch64Subtarget::isTargetWindows</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp/#a7010c624fdaf139f8efa60219c3b56bf">ShouldSignWithBKey</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#af4cf5140a6baf36f029924fa4c592e64">clone</a> and <a href="#af1bf187d995b982c232e7c73bb45c832">needsAsyncDwarfUnwindInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addLOHDirective() {#a03324cd61d637f496c9f19984b59df94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::addLOHDirective (<a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5">MCLOHType</a> Kind, <a href="#a82309f98f5a090fcf8661e69a2db43b3">MILOHArgs</a> Args)</td>
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

<p>Add a LOH directive of this <span class="doxyComputerOutput">Kind</span> and this <span class="doxyComputerOutput">Args</span>.</p>

<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a897e4640c14c6556e0b1bc06eca81134">handleADRP</a>.</p>

</div>
</div>

### branchProtectionPAuthLR() {#a7e0d34e679046b3b27cddbb69c1f985a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::branchProtectionPAuthLR ()</td>
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



<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-cpp/#a181216377a992592ea7e30fc0ce07f0d">emitPACCFI</a>.</p>

</div>
</div>

### branchTargetEnforcement() {#a13ec8ba54ec7daae44e617496a3f74d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::branchTargetEnforcement ()</td>
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



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64branchtargets-cpp-/aarch64branchtargets/#a79c9d520bc085013e33ec2b361a213f4">anonymous{AArch64BranchTargets.cpp}::AArch64BranchTargets::runOnMachineFunction</a>.</p>

</div>
</div>

### clone() {#af4cf5140a6baf36f029924fa4c592e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionInfo * AArch64FunctionInfo::clone (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; DestMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; Src2DstMBB)</td>
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

<p>Make a functionally equivalent copy of this <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> in <span class="doxyComputerOutput">MF</span>.</p>


<p>This requires remapping <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> references from the original parent to values in the new function. Targets may assume that virtual register and frame index values are preserved in the new function.</p>


<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp">AArch64MachineFunctionInfo.cpp</a>.</p>


<p>References <a href="#a9fd3cdd22c698232d4998d7b3ea7b21a">AArch64FunctionInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac31b21febeefe69aaddea3541dae45e1">llvm::MachineFunction::cloneInfo</a>.</p>

</div>
</div>

### getArgumentStackToRestore() {#a3d962df55ff4ce124096ee9501e121c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getArgumentStackToRestore ()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a01f6c42979a72dd229c03417e00f7f96">getArgumentStackToRestore</a>.</p>

</div>
</div>

### getBytesInStackArgArea() {#ae3983ecc9903d3cb991aa6fa865f9419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getBytesInStackArgArea ()</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getCalleeSaveBaseToFrameRecordOffset() {#a4bf50af86f6d1f7d2dcf35e0ee18d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::getCalleeSaveBaseToFrameRecordOffset ()</td>
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



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a1886741049357a9b7cea7f8e8784a818">emitDefineCFAWithFP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#abc7410daace72818d9ce654814a67892">getFPOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ac8934ae6c8b97148ebb1db39bd978b03">llvm::AArch64FrameLowering::resolveFrameOffsetReference</a>.</p>

</div>
</div>

### getCalleeSavedStackSize() {#a217c3db3b137e03bd6ade29bb9999ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getCalleeSavedStackSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> &amp; MFI)</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5af2af9eb94ff1bc08308bc738d744ee85">llvm::TargetStackID::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="#afa83a2fcc4197136c064fc194da783ea">getCalleeSavedStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad718aae0ce2a188fa35cb2781024ffc0">llvm::MachineFrameInfo::getStackID</a>, <a href="#ad3cba3aa9b7b65f2db15e631bbd27f08">getSwiftAsyncContextFrameIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a81504f733d0491a446a16ef1ba0a5c2a">llvm::MachineFrameInfo::isCalleeSavedInfoValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a1886741049357a9b7cea7f8e8784a818">emitDefineCFAWithFP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#abc7410daace72818d9ce654814a67892">getFPOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a454562a019aeae43ffd6a8ce7f894ed3">llvm::AArch64FrameLowering::getFrameIndexReferenceFromSP</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ac8934ae6c8b97148ebb1db39bd978b03">llvm::AArch64FrameLowering::resolveFrameOffsetReference</a>.</p>

</div>
</div>

### getCalleeSavedStackSize() {#afa83a2fcc4197136c064fc194da783ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getCalleeSavedStackSize ()</td>
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



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a217c3db3b137e03bd6ade29bb9999ac9">getCalleeSavedStackSize</a>.</p>

</div>
</div>

### getForwardedMustTailRegParms() {#a4e173b1457c01a05c1200c2624478b0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; ForwardedRegister &gt; &amp; llvm::AArch64FunctionInfo::getForwardedMustTailRegParms ()</td>
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



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getJumpTableEntryPCRelSymbol() {#ab1eea0099521259e014a19f926ad9668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::AArch64FunctionInfo::getJumpTableEntryPCRelSymbol (int Idx)</td>
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



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getJumpTableEntrySize() {#aa5bb23b4f732fe77fee2cba281aa218f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getJumpTableEntrySize (int Idx)</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getLocalStackSize() {#a9fded0dfc6857b39fcf1ed029ca145ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64FunctionInfo::getLocalStackSize ()</td>
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



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a81242a6cd5fbec123c8ed582bab0f26c">llvm::AArch64FrameLowering::canUseRedZone</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ac8934ae6c8b97148ebb1db39bd978b03">llvm::AArch64FrameLowering::resolveFrameOffsetReference</a>.</p>

</div>
</div>

### getLOHContainer() {#aebeb489e565baf5a8403bcc1901788ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MILOHContainer &amp; llvm::AArch64FunctionInfo::getLOHContainer ()</td>
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



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getLOHRelated() {#a6ad1c8eb92bcb0cc7e14c2ebd5a2b1dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SetOfInstructions &amp; llvm::AArch64FunctionInfo::getLOHRelated ()</td>
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



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getMaxSVECSFrameIndex() {#a52f519aabe90a43ea18e5939533a6a5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::getMaxSVECSFrameIndex ()</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getMinSVECSFrameIndex() {#aeff5274f6e233895a572e4d6bc098516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::getMinSVECSFrameIndex ()</td>
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



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getNumLocalDynamicTLSAccesses() {#ab8613af92f6f5d07720aa5c10c7ecbed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getNumLocalDynamicTLSAccesses ()</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64cleanuplocaldynamictlspass-cpp-/ldtlscleanup/#ab7fe307733ec8e501f180b78fe879980">anonymous{AArch64CleanupLocalDynamicTLSPass.cpp}::LDTLSCleanup::runOnMachineFunction</a>.</p>

</div>
</div>

### getOutliningStyle() {#adda0b11bd1bc8d81e88218a69f78b309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::string &gt; llvm::AArch64FunctionInfo::getOutliningStyle ()</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a8acc616b7a053eae35f4e286905561e6">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitFunctionHeaderComment</a>.</p>

</div>
</div>

### getPredicateRegForFillSpill() {#ad4810ed3af6f235900d3417f70d143e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getPredicateRegForFillSpill ()</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a3fc78aa19b9e30af7cb534f1a58e22de">llvm::AArch64FrameLowering::restoreCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### getPStateSMReg() {#ab4585aeeb951dcbaa41a190908f1c54f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::AArch64FunctionInfo::getPStateSMReg ()</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getSigningInstrLabel() {#af6e80daebbb83fe475e3aca10a41599b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::AArch64FunctionInfo::getSigningInstrLabel ()</td>
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



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getSMESaveBufferAddr() {#ae50d6a3d63e6a9bd955965a39606db99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::AArch64FunctionInfo::getSMESaveBufferAddr ()</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getSRetReturnReg() {#ab0a89286bc67d60002c353f80503e8cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getSRetReturnReg ()</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getStackHazardCSRSlotIndex() {#a83fb05995d77e69e671f741020f223af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::getStackHazardCSRSlotIndex ()</td>
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



<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getStackHazardSlotIndex() {#a6f68e3671f98f25c18b29b7f14a13ed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::getStackHazardSlotIndex ()</td>
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



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa2b80c1201a1baeb6ee4466e970957ba">llvm::AArch64FrameLowering::orderFrameObjects</a>.</p>

</div>
</div>

### getStackProbeSize() {#a79cb24e9f1731f9f49f84400acf9b738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AArch64FunctionInfo::getStackProbeSize ()</td>
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



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getStackSizeSVE() {#a7b316ba6e060bc850312c3d294130878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64FunctionInfo::getStackSizeSVE ()</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ad6591055c1ba6d0a1033510f7a4eab65">llvm::AArch64FrameLowering::getFrameIndexReferencePreferSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a7a40dfef81dda9948bcafa33022d0fb5">getSVEStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#acafe750c425c834b596416c311715d8c">llvm::AArch64RegisterInfo::hasBasePointer</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#add6176251034fbacf30f8e906db5f347">llvm::AArch64RegisterInfo::useFPForScavengingIndex</a>.</p>

</div>
</div>

### getStreamingVGIdx() {#af2976aa2ecb71890f37e7ec9f8b880cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AArch64FunctionInfo::getStreamingVGIdx ()</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#aa1ef43d8b6e30020194591f4e5a914ac">emitVGSaveRestore</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### getSVECalleeSavedStackSize() {#aef92fa2f6c53b6fda74605b0125d7667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getSVECalleeSavedStackSize ()</td>
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



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a469793f0416704ca132c5c91f73adbdd">produceCompactUnwindFrame</a>.</p>

</div>
</div>

### getSwiftAsyncContextFrameIdx() {#ad3cba3aa9b7b65f2db15e631bbd27f08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::getSwiftAsyncContextFrameIdx ()</td>
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



<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="#a217c3db3b137e03bd6ade29bb9999ac9">getCalleeSavedStackSize</a>.</p>

</div>
</div>

### getTaggedBasePointerIndex() {#a92b18d1bf9d1db22ceb01054ebe94983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int &gt; llvm::AArch64FunctionInfo::getTaggedBasePointerIndex ()</td>
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



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa2b80c1201a1baeb6ee4466e970957ba">llvm::AArch64FrameLowering::orderFrameObjects</a>.</p>

</div>
</div>

### getTaggedBasePointerOffset() {#a73f8cb59d120af794be129a54a0343fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getTaggedBasePointerOffset ()</td>
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



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aa24149b04083669797095c1473b14f3a">llvm::AArch64RegisterInfo::eliminateFrameIndex</a>.</p>

</div>
</div>

### getTailCallReservedStack() {#a1e887116bba8ca08bd717cbf2cbd1ac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getTailCallReservedStack ()</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#af917fe9cdb70db029cf2ddd236fae738">getFixedObjectSize</a>.</p>

</div>
</div>

### getTPIDR2Obj() {#a434e2f6f33183ce02a92b09b088c8cb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TPIDR2Object &amp; llvm::AArch64FunctionInfo::getTPIDR2Obj ()</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getVarArgsFPRIndex() {#a5a887b26a707f64e1188ebb84e3f2e30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::getVarArgsFPRIndex ()</td>
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



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getVarArgsFPRSize() {#a258b3288d244094217895ed0150a65d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getVarArgsFPRSize ()</td>
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



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getVarArgsGPRIndex() {#a78ef05ed4db7991fa28264d76e8a5fc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::getVarArgsGPRIndex ()</td>
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



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getVarArgsGPRSize() {#aae1cc37c03dc88bd71db86b6180b9d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getVarArgsGPRSize ()</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#af917fe9cdb70db029cf2ddd236fae738">getFixedObjectSize</a>.</p>

</div>
</div>

### getVarArgsStackIndex() {#a6e56ab8686aecd83b84810e257d84b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::getVarArgsStackIndex ()</td>
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



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getVarArgsStackOffset() {#a956af6c01008388fbc3e9db7257176ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::getVarArgsStackOffset ()</td>
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



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getVGIdx() {#acc80535a1cfd78ba171d991a15665c0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AArch64FunctionInfo::getVGIdx ()</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#aa1ef43d8b6e30020194591f4e5a914ac">emitVGSaveRestore</a>.</p>

</div>
</div>

### hasCalculatedStackSizeSVE() {#ad7bb9da1cdb51abc81f080b265948015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::hasCalculatedStackSizeSVE ()</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#acafe750c425c834b596416c311715d8c">llvm::AArch64RegisterInfo::hasBasePointer</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#add6176251034fbacf30f8e906db5f347">llvm::AArch64RegisterInfo::useFPForScavengingIndex</a>.</p>

</div>
</div>

### hasCalleeSaveStackFreeSpace() {#afbfedea21bb3ae3e646a4c2995e1f75e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::hasCalleeSaveStackFreeSpace ()</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a362113d81c98925d063d3ad6602a1e17">llvm::AArch64FrameLowering::enableStackSlotScavenging</a>.</p>

</div>
</div>

### hasELFSignedGOT() {#a4df127df519885541003937cde4f22d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::hasELFSignedGOT ()</td>
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



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>.</p>

</div>
</div>

### hasRedZone() {#ac81232e8ac34e95d748e2e31e43482b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; llvm::AArch64FunctionInfo::hasRedZone ()</td>
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



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a538e94fb7d7a71910f3cbb5cd97aae0c">llvm::AArch64InstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a8e7ea4a37a21caeb8c336ef3e95f8ee0">llvm::AArch64InstrInfo::isFunctionSafeToOutlineFrom</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aab2bb29af5f95ecde069091fc13e0dd9">llvm::AArch64InstrInfo::isFunctionSafeToSplit</a>.</p>

</div>
</div>

### hasStackFrame() {#a839720705cb2401eb2e9dd30001e4ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::hasStackFrame ()</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a9462cc875c5c343ff7ae9b3d68ce6305">llvm::AArch64FrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ac8934ae6c8b97148ebb1db39bd978b03">llvm::AArch64FrameLowering::resolveFrameOffsetReference</a>.</p>

</div>
</div>

### hasStackHazardSlotIndex() {#ac29ee8562c33732a42e2894f5db67874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::hasStackHazardSlotIndex ()</td>
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



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ad2f0da8ab6518a9d252876e7b996b10b">llvm::AArch64FrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a362113d81c98925d063d3ad6602a1e17">llvm::AArch64FrameLowering::enableStackSlotScavenging</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa2b80c1201a1baeb6ee4466e970957ba">llvm::AArch64FrameLowering::orderFrameObjects</a>.</p>

</div>
</div>

### hasStackProbing() {#a2fa17036c1831538491a34f3715ca4a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::hasStackProbing ()</td>
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



<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a2be9d35aaace9716441da5714f048af9">llvm::AArch64FrameLowering::canUseAsPrologue</a>.</p>

</div>
</div>

### hasStreamingModeChanges() {#a5f85995f165e15b5c4ce247e5580fefe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::hasStreamingModeChanges ()</td>
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



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a362113d81c98925d063d3ad6602a1e17">llvm::AArch64FrameLowering::enableStackSlotScavenging</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a8e7ea4a37a21caeb8c336ef3e95f8ee0">llvm::AArch64InstrInfo::isFunctionSafeToOutlineFrom</a>, <a href="#af1bf187d995b982c232e7c73bb45c832">needsAsyncDwarfUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a3def849b8e45d0b1fb07e36644e2920e">requiresGetVGCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#af7b36ff0cf5c71f306b50c0fc3072434">requiresSaveVG</a>.</p>

</div>
</div>

### hasSwiftAsyncContext() {#abe26a416b693ebc37154faaded2cdfc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::hasSwiftAsyncContext ()</td>
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



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ad2f0da8ab6518a9d252876e7b996b10b">llvm::AArch64FrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a2be9d35aaace9716441da5714f048af9">llvm::AArch64FrameLowering::canUseAsPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>.</p>

</div>
</div>

### incNumLocalDynamicTLSAccesses() {#a65d272f48967ff5d6cb87e49a03b7e5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::incNumLocalDynamicTLSAccesses ()</td>
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



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### initializeBaseYamlFields() {#aeaf73d373f54aac1716146ed80e38b2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64FunctionInfo::initializeBaseYamlFields (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/aarch64functioninfo">yaml::AArch64FunctionInfo</a> &amp; YamlMFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp">AArch64MachineFunctionInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/yaml/aarch64functioninfo/#a0352abfd17d72d4c1be77f2b52971815">llvm::yaml::AArch64FunctionInfo::HasRedZone</a>.</p>

</div>
</div>

### isMTETagged() {#ae1fb12997102391efd9333742ae324b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::isMTETagged ()</td>
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



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#acb65d960d9bd3f0ca3d49937d12affe4">isMergeableLdStUpdate</a>.</p>

</div>
</div>

### isSMESaveBufferUsed() {#aef1ba3874d6358f607fe1b882312cd2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::isSMESaveBufferUsed ()</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### isSplitCSR() {#a89194de9866090f36bd192e81aeb1e1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::isSplitCSR ()</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a35e0d4e10fc033d23cb665a9f6ef4bc6">llvm::AArch64RegisterInfo::getCalleeSavedRegsViaCopy</a>.</p>

</div>
</div>

### isStackRealigned() {#ab325d3abfa4e1b6a0aba6d6761203806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::isStackRealigned ()</td>
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



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>.</p>

</div>
</div>

### isSVECC() {#a093615ad7a3c3eac2dc8c8655d0ac00b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::isSVECC ()</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aed12387a77f0d475d9cb9b247580257b">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ac26dae5c257bfaab5aa15cab7255f107">llvm::AArch64RegisterInfo::getCalleeSavedRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aaab57b42c1306819f384fbc8917e728b">llvm::AArch64RegisterInfo::getDarwinCalleeSavedRegs</a>.</p>

</div>
</div>

### needsAsyncDwarfUnwindInfo() {#af1bf187d995b982c232e7c73bb45c832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64FunctionInfo::needsAsyncDwarfUnwindInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp">AArch64MachineFunctionInfo.cpp</a>.</p>


<p>References <a href="#a9fd3cdd22c698232d4998d7b3ea7b21a">AArch64FunctionInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8a24aa4117da86c41684ad25742832dfa6">llvm::Async</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="#a5f85995f165e15b5c4ce247e5580fefe">hasStreamingModeChanges</a> and <a href="#aaa6625e357c6806a89b36759ae16b630">needsDwarfUnwindInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a02cddefc96e08fba507c3d0eac7f6c1f">emitShadowCallStackEpilogue</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64framelowering-cpp-/#ab1cb1e5a0ad356f946b7001f0f133cf9">anonymous{AArch64FrameLowering.cpp}::tryMergeAdjacentSTG</a>.</p>

</div>
</div>

### needsDwarfUnwindInfo() {#aaa6625e357c6806a89b36759ae16b630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64FunctionInfo::needsDwarfUnwindInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp">AArch64MachineFunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#afb72c5626afbc815284e2b26bb0663f8">llvm::TargetMachine::getMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4f117e439113383ea819a6f7beb8ff0b">llvm::MachineFunction::needsFrameMoves</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac158349781823fe8ff9e02d3a3533d55">llvm::MCAsmInfo::usesWindowsCFI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9b0a622dbae74cb8a4b9b87a8b559b25">llvm::AArch64InstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a> and <a href="#af1bf187d995b982c232e7c73bb45c832">needsAsyncDwarfUnwindInfo</a>.</p>

</div>
</div>

### needsShadowCallStackPrologueEpilogue() {#a0a6cffdcc5341dcc150620c684528de6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64FunctionInfo::needsShadowCallStackPrologueEpilogue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp">AArch64MachineFunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp/#ad8d9de20a2440d472786e299fc96a97e">isLRSpilled</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#abebf776aea4ae4a420fd4a2c5f02cbbd">llvm::AArch64Subtarget::isXRegisterReserved</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>.</p>

</div>
</div>

### setArgumentStackToRestore() {#afa54f4f948a89516a5d77a58fb8a18d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setArgumentStackToRestore (unsigned bytes)</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setBytesInStackArgArea() {#a6b6e1593f20bacc0f43b1254988ddd18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setBytesInStackArgArea (unsigned bytes)</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setCalleeSaveBaseToFrameRecordOffset() {#a26df76f51f398bf4954036667563e2be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setCalleeSaveBaseToFrameRecordOffset (int Offset)</td>
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



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>.</p>

</div>
</div>

### setCalleeSavedStackSize() {#a75c0e90d15611f0111db4f66711886d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setCalleeSavedStackSize (unsigned Size)</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### setCalleeSaveStackHasFreeSpace() {#a476ff010131b70eb3cb38dd1477d01ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setCalleeSaveStackHasFreeSpace (bool s)</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setHasRedZone() {#a81917a56aebf01a4df724caade1dfd80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setHasRedZone (bool s)</td>
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



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>.</p>

</div>
</div>

### setHasStackFrame() {#a1bb844d18888aaa95f53360509017797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setHasStackFrame (bool s)</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setHasStreamingModeChanges() {#afa7a17dc76056b610a1935e582ae19e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setHasStreamingModeChanges (bool HasChanges)</td>
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



<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smepeepholeopt-cpp/#aed0d70e55a261450cb76cb7f615977dc">INITIALIZE_PASS</a>.</p>

</div>
</div>

### setHasSwiftAsyncContext() {#a7bc2e4041e3018454afab435e28be39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setHasSwiftAsyncContext (bool HasContext)</td>
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



<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setIsSplitCSR() {#a538aa174513553563cbd28d78b7222df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setIsSplitCSR (bool s)</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a15bcdc727d8a841f1bc89a276b7eab72">llvm::AArch64TargetLowering::initializeSplitCSR</a>.</p>

</div>
</div>

### setIsSVECC() {#a22ad95b4993a4bf58f9f0583379fbb25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setIsSVECC (bool s)</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setJumpTableEntryInfo() {#aedc3f83fd9f38499f104d6c4a782df7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setJumpTableEntryInfo (int Idx, unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * PCRelSym)</td>
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



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### setLocalStackSize() {#a4761d8d142e4f5eca20e2a37fbd1375a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setLocalStackSize (uint64_t Size)</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>.</p>

</div>
</div>

### setMinMaxSVECSFrameIndex() {#afa58eca8243bee935ada875a71acfafa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setMinMaxSVECSFrameIndex (int Min, int Max)</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a9462cc875c5c343ff7ae9b3d68ce6305">llvm::AArch64FrameLowering::processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

### setOutliningStyle() {#a648d29a4010d7cc1be7785eab399d5fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setOutliningStyle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Style)</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9b0a622dbae74cb8a4b9b87a8b559b25">llvm::AArch64InstrInfo::buildOutlinedFrame</a>.</p>

</div>
</div>

### setPredicateRegForFillSpill() {#a6085917e6c5f643ea01c715f90bf80f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setPredicateRegForFillSpill (unsigned Reg)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>.</p>

</div>
</div>

### setPStateSMReg() {#a7ecdb920d3ec70d949ec71672c9ca521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setPStateSMReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### setSigningInstrLabel() {#a7ac6a6e00198488a151eb5d1fb3e911e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setSigningInstrLabel (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label)</td>
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



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setSMESaveBufferAddr() {#ad046eec280d118d2c2b650be4425a6e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setSMESaveBufferAddr (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### setSMESaveBufferUsed() {#ac8d6963b19204e698d4ca932e087402f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setSMESaveBufferUsed (bool Used=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setSRetReturnReg() {#aca78815d0b439cadb992c6436df5d72b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setSRetReturnReg (unsigned Reg)</td>
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



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### setStackHazardCSRSlotIndex() {#acfcebd83a34e4304e6cdfab40e6f9244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setStackHazardCSRSlotIndex (int Index)</td>
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



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ad2f0da8ab6518a9d252876e7b996b10b">llvm::AArch64FrameLowering::assignCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### setStackHazardSlotIndex() {#ac58b635e8d3494e5a97d6c8de5be18bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setStackHazardSlotIndex (int Index)</td>
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



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### setStackRealigned() {#aa5a3112b5a4dd39005325e09e523963b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setStackRealigned (bool s)</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>.</p>

</div>
</div>

### setStackSizeSVE() {#ab1093619213bf0b465ab1d5fc1e44824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setStackSizeSVE (uint64_t S)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a9462cc875c5c343ff7ae9b3d68ce6305">llvm::AArch64FrameLowering::processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

### setStreamingVGIdx() {#a755f8c328cc1e0c201614b296c2259f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setStreamingVGIdx (unsigned FrameIdx)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### setSVECalleeSavedStackSize() {#adbd6275072f7ab65915b763deb5952fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setSVECalleeSavedStackSize (unsigned Size)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### setSwiftAsyncContextFrameIdx() {#a1cf1ee0c8e45ead80ed78b4866d9cbee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setSwiftAsyncContextFrameIdx (int FI)</td>
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



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ad2f0da8ab6518a9d252876e7b996b10b">llvm::AArch64FrameLowering::assignCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### setTaggedBasePointerIndex() {#af6cfc93683b52a3179bca019b1b2bc71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setTaggedBasePointerIndex (int Index)</td>
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



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setTaggedBasePointerOffset() {#ac585fc64555950b121905c6d28306107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setTaggedBasePointerOffset (unsigned Offset)</td>
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



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>.</p>

</div>
</div>

### setTailCallReservedStack() {#a45c3e4d88953eccee2e33f9b7d18420f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setTailCallReservedStack (unsigned bytes)</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setVarArgsFPRIndex() {#af3d5db606772049b0fc898bbfc34cf73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setVarArgsFPRIndex (int Index)</td>
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



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setVarArgsFPRSize() {#a91c58dd5b17822ae117072fdc3ca6c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setVarArgsFPRSize (unsigned Size)</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### setVarArgsGPRIndex() {#a6f581cfdb5a35bbcc3968b9ee7ffa4c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setVarArgsGPRIndex (int Index)</td>
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



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setVarArgsGPRSize() {#af5aaf1970a8d2d5cbe00aacabb37e011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setVarArgsGPRSize (unsigned Size)</td>
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



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### setVarArgsStackIndex() {#a3579b908528b4652650ed24f8c5044c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setVarArgsStackIndex (int Index)</td>
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



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setVarArgsStackOffset() {#a2bce000887a512db38a7918386165b11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setVarArgsStackOffset (unsigned Offset)</td>
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



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### setVGIdx() {#a4a608e93e8987b7a2845867fb9e16f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AArch64FunctionInfo::setVGIdx (unsigned Idx)</td>
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



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### shouldSignReturnAddress() {#a606dce8fc572cecd6eab6f419f11aa6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64FunctionInfo::shouldSignReturnAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>, definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp">AArch64MachineFunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp/#ad8d9de20a2440d472786e299fc96a97e">isLRSpilled</a> and <a href="#a606dce8fc572cecd6eab6f419f11aa6d">shouldSignReturnAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9b0a622dbae74cb8a4b9b87a8b559b25">llvm::AArch64InstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ac15c0fdff1ea78da81fb615670cbd7c1">outliningCandidatesSigningScopeConsensus</a> and <a href="#a606dce8fc572cecd6eab6f419f11aa6d">shouldSignReturnAddress</a>.</p>

</div>
</div>

### shouldSignReturnAddress() {#a805799c2737c33d9f64de8d5348dfac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64FunctionInfo::shouldSignReturnAddress (bool SpillsLR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp">AArch64MachineFunctionInfo.cpp</a>.</p>

</div>
</div>

### shouldSignWithBKey() {#afd791302f998513ddb029c191f550232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::shouldSignWithBKey ()</td>
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



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#abc2a85d6828b45938a55cce5ea029d72">outliningCandidatesSigningKeyConsensus</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ArgumentStackToRestore {#a0e84fd402eb0e5b00f9aaacd68628bf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::ArgumentStackToRestore = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of bytes to restore to deallocate space for incoming arguments.</p>


<p>Canonically 0 in the C calling convention, but non-zero when callee is expected to pop the args.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### BranchProtectionPAuthLR {#a5f104c2ad2622585d5fc3ed382d40de6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::BranchProtectionPAuthLR = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicates that SP signing should be diversified with PC as-per PAuthLR.</p>


<p>This is set by -mbranch-protection and will emit NOP instructions unless the subtarget feature +pauthlr is also used (in which case non-NOP instructions are emitted).</p>


<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### BranchTargetEnforcement {#a99a4b697ebc206fd05d20fd2165c028b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::BranchTargetEnforcement = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BranchTargetEnforcement enables placing BTI instructions at potential indirect branch destinations.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### BytesInStackArgArea {#a58703260f466ae0d91a79e2cf7cbf2d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::BytesInStackArgArea = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of bytes of arguments this function has on the stack.</p>


<p>If the callee is expected to restore the argument stack this should be a multiple of 16, all usable during a tail call.</p>


<p>The alternative would forbid tail call optimisation in some cases: if we want to transfer control from a function with 8-bytes of stack-argument space to a function with 16-bytes then misalignment of this value would make a stack adjustment necessary, which could not be undone by the callee.</p>


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### CalleeSaveBaseToFrameRecordOffset {#a36a8052eea6fc0eca77afb0b13a08e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::CalleeSaveBaseToFrameRecordOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### CalleeSavedStackSize {#afcaa97f6e7e5c8d736c6ca5911c2f567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::CalleeSavedStackSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Amount of stack frame size used for saving callee-saved registers.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### CalleeSaveStackHasFreeSpace {#afafc0621143fdbe09eeb03b9e794f93c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::CalleeSaveStackHasFreeSpace = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True when the callee-save stack area has unused gaps that may be used for other stack allocations.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### ForwardedMustTailRegParms {#a535ac4b567bb34d7715fc6aae53e7038}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ForwardedRegister, 1&gt; llvm::AArch64FunctionInfo::ForwardedMustTailRegParms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ForwardedMustTailRegParms - A list of virtual and physical registers that must be forwarded to every musttail call.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasCalculatedStackSizeSVE {#a45c681b558643514688047b44c12d08a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::HasCalculatedStackSizeSVE = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HasCalculatedStackSizeSVE indicates whether StackSizeSVE is valid.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasCalleeSavedStackSize {#af6e1791eaa5eff185a2ce5eb58c4f15d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::HasCalleeSavedStackSize = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasELFSignedGOT {#a78810a1c89098ed79460e9203cff03c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::HasELFSignedGOT = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HasELFSignedGOT is true if the target binary format is <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> and the IR module containing the corresponding function has "ptrauth-elf-got" flag set to 1.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasRedZone {#a6800da1b590d7aea61dd05726525de74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::AArch64FunctionInfo::HasRedZone</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has a value when it is known whether or not the function uses a redzone, and no value otherwise.</p>


<p>Initialized during frame lowering, unless the function has the noredzone attribute, in which case it is set to false at construction.</p>


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasStackFrame {#aa3491ab50edcdf5c5254c168aba15ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::HasStackFrame = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HasStackFrame - True if this function has a stack frame.</p>


<p>Set by determineCalleeSaves().</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasStreamingModeChanges {#a6c4ac42003d880b5cfed0ca3a6d258e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::HasStreamingModeChanges = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this function changes streaming mode within the function.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasSwiftAsyncContext {#aeb57cd6a42715716faca96505a38c0fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::HasSwiftAsyncContext = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this function has an extended frame record [Ctx, FP, LR].</p>


<p>If so, bit 60 of the in-memory FP will be 1 to enable other tools to detect the extended record.</p>


<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### IsMTETagged {#a645b33772fd89e7a24564e66040e07fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::IsMTETagged = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### IsSplitCSR {#a3d522314c7549004403d9e58b77437d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::IsSplitCSR = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this function has a subset of CSRs that is handled explicitly via copies.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### IsSVECC {#a5e16bd0cc17ce91581f469255e2fad12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::IsSVECC = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The function has Scalable Vector or Scalable <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> register argument or return type.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### JumpTableEntryInfo {#a38bebfe203d8a5e555fb9229974ffc5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;unsigned, MCSymbol *&gt;, 2&gt; llvm::AArch64FunctionInfo::JumpTableEntryInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### LocalStackSize {#ab9d72456d49216fcccf3d0c8ea27bad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64FunctionInfo::LocalStackSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Amount of stack frame size, not including callee-saved registers.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### LOHContainerSet {#af71d14c7834e07b37c6c9ba603e7e05e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MILOHContainer llvm::AArch64FunctionInfo::LOHContainerSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### LOHRelated {#a0543bc83e041960e9140e1bcbb3ad631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetOfInstructions llvm::AArch64FunctionInfo::LOHRelated</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### MaxSVECSFrameIndex {#a4b25b07744a6ab1038e88cb184f0701b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::MaxSVECSFrameIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### MinSVECSFrameIndex {#aa357658054f0f317490b05be25974c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::MinSVECSFrameIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The start and end frame indices for the SVE callee saves.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### NeedsAsyncDwarfUnwindInfo {#ac94dcfff6fa3d33b7c457a38157d728c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::AArch64FunctionInfo::NeedsAsyncDwarfUnwindInfo</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the function need asynchronous unwind information.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### NeedsDwarfUnwindInfo {#a148c1b911ff78e07de7cd77bd6041d1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::AArch64FunctionInfo::NeedsDwarfUnwindInfo</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the function need unwind information.</p>

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### NumLocalDynamicTLSAccesses {#a7572557678506721412fa237ffc2a04d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::NumLocalDynamicTLSAccesses = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of TLS accesses using the special (combinable) <em>TLS_MODULE_BASE</em> symbol.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### OutliningStyle {#a470a6f17af1e08e00f00b192f456dfd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::string&gt; llvm::AArch64FunctionInfo::OutliningStyle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OutliningStyle denotes, if a function was outined, how it was outlined, e.g.</p>


<p>Tail Call, Thunk, or <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> if none apply.</p>


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### PredicateRegForFillSpill {#a67266cd4e22914b772aae4b2726023c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::PredicateRegForFillSpill = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### PStateSMReg {#a3b858c1e5cdbe8b9573116ccf4670936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::AArch64FunctionInfo::PStateSMReg = <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a4aa6aac0f36c1123df3686f7b4150d2c">MCRegister::NoRegister</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### SignInstrLabel {#abe6884c391afe1cba372770022b74fde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::AArch64FunctionInfo::SignInstrLabel = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SigningInstrOffset captures the offset of the PAC-RET signing instruction within the prologue, so it can be re-used for authentication in the epilogue when using PC as a second salt (FEAT_PAuth_LR)</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### SignReturnAddress {#a96e803bdc8a9722cfc11f228dca75e98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::SignReturnAddress = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SignReturnAddress is true if PAC-RET is enabled for the function with defaults being sign non-leaf functions only, with the B key.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### SignReturnAddressAll {#a77bec87c61af57a81abf8acf69568e89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::SignReturnAddressAll = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SignReturnAddressAll modifies the default PAC-RET mode to signing leaf functions as well.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### SignWithBKey {#a6365cf34c46b4fc7f932a49fe44ed653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::SignWithBKey = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SignWithBKey modifies the default PAC-RET mode to signing with the B key.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### SMESaveBufferAddr {#a038a97c8fc086da556e4ba6b6f87c5ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::AArch64FunctionInfo::SMESaveBufferAddr = <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a4aa6aac0f36c1123df3686f7b4150d2c">MCRegister::NoRegister</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### SMESaveBufferUsed {#a65be06223c61b2238dcd8d008c12da21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::SMESaveBufferUsed = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### SRetReturnReg {#a3a120414f7823be1f39e6882836a0118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::AArch64FunctionInfo::SRetReturnReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SRetReturnReg - sret lowering includes returning the value of the returned struct in a register.</p>


<p>This field holds the virtual register into which the sret argument is passed.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### StackHazardCSRSlotIndex {#a65577e1cd9c6eb28ebb645118ac3fa93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::StackHazardCSRSlotIndex = std::numeric_limits&lt;int&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### StackHazardSlotIndex {#a52baf0c55b705d3442d037c7f6ffd29e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::StackHazardSlotIndex = std::numeric_limits&lt;int&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The stack slots used to add space between FPR and GPR accesses when using hazard padding.</p>


<p>StackHazardCSRSlotIndex is added between GPR and FPR CSRs. StackHazardSlotIndex is added between (sorted) stack objects.</p>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### StackProbeSize {#a7d4cad5aefc49719371fe3b770ce5334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AArch64FunctionInfo::StackProbeSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### StackRealigned {#a508dc03acc88be62d6d94db3d9be3f17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64FunctionInfo::StackRealigned = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True when the stack gets realigned dynamically because the size of stack frame is unknown at compile time.</p>


<p>e.g., in case of VLAs.</p>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### StackSizeSVE {#a0551d1a7842076eb9cc071933dfa283a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AArch64FunctionInfo::StackSizeSVE = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SVE stack size (for predicates and data vectors) are maintained here rather than in FrameInfo, as the placement and Stack IDs are target specific.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### StreamingVGIdx {#a58f93a077f91d648c660a469d5f67206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AArch64FunctionInfo::StreamingVGIdx = std::numeric_limits&lt;int&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### SVECalleeSavedStackSize {#a8c4f3bd4101ea12629999b58ed66f4d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::SVECalleeSavedStackSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### SwiftAsyncContextFrameIdx {#a5567d64b531237284fdd7883135d7fbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::SwiftAsyncContextFrameIdx = std::numeric_limits&lt;int&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The stack slot where the Swift asynchronous context is stored.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### TaggedBasePointerIndex {#a627503a4914378cd3dbccccad95233c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;int&gt; llvm::AArch64FunctionInfo::TaggedBasePointerIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FrameIndex for the tagged base pointer.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### TaggedBasePointerOffset {#aefbc57d8f869d47b5e76e437a252f563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::TaggedBasePointerOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset from SP-at-entry to the tagged base pointer.</p>


<p>Tagged base pointer is set up to point to the first (lowest address) tagged stack slot.</p>


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### TailCallReservedStack {#ad630a9675c3e9d86f352cf8002b38007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::TailCallReservedStack = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Space just below incoming stack pointer reserved for arguments being passed on the stack during a tail call.</p>


<p>This will be the difference between the largest tail call argument space needed in this function and what's already available by reusing space of incoming arguments.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### TPIDR2 {#a21fefc8bd17a8233a86b86ae917153b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TPIDR2Object llvm::AArch64FunctionInfo::TPIDR2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The frame-index for the TPIDR2 object used for lazy saves.</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### VarArgsFPRIndex {#a586390d03a4bbdc8d16e48efb8149d40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::VarArgsFPRIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FrameIndex for start of varargs area for arguments passed in floating-point registers.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### VarArgsFPRSize {#a47be76c15edc026c4422083e879a3413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::VarArgsFPRSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of the varargs area for arguments passed in floating-point registers.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### VarArgsGPRIndex {#a83e0d9c1d8b7b806d759a65748260a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::VarArgsGPRIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FrameIndex for start of varargs area for arguments passed in general purpose registers.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### VarArgsGPRSize {#afb95de0ee1b30dd97cd1cb2eca124976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::VarArgsGPRSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of the varargs area for arguments passed in general purpose registers.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### VarArgsStackIndex {#a53afd4629d43ffabce76a6aabc4d90e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64FunctionInfo::VarArgsStackIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FrameIndex for start of varargs area for arguments passed on the stack.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### VarArgsStackOffset {#af29b1fa16125fe684ad3ed7639fdebe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64FunctionInfo::VarArgsStackOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset of start of varargs area for arguments passed on the stack.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

### VGIdx {#a35e3469cd4741b490ea87586329b3851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AArch64FunctionInfo::VGIdx = std::numeric_limits&lt;int&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp">AArch64MachineFunctionInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
