---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machineframeinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineFrameInfo` Class

<p>The <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> class represents an abstract stack frame until prolog/epilog code is inserted. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineFrameInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SSPLayoutKind { <a href="#a3df888d2d0447ad8ff7b616b080d9f13">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stack Smashing Protection (SSP) rules require that vulnerable stack allocations are located close the stack protector. <a href="#a3df888d2d0447ad8ff7b616b080d9f13">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22785bee142f66d053d8a7742d12820f">MachineFrameInfo</a> (Align StackAlignment, bool StackRealignable, bool ForcedRealign)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad37b5d2eaee40945fb9318e8d9ae7d73">MachineFrameInfo</a> (const MachineFrameInfo &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad41610633e45748a267b67f6062e8b1d">isStackRealignable</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb35f7f6a131a64e636d936246ebd37f">hasStackObjects</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there are any stack objects in this function. <a href="#acb35f7f6a131a64e636d936246ebd37f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0509430713d587eba74220a8375948a8">hasVarSizedObjects</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be called any time after instruction selection is complete to determine if the stack frame for this function contains any variable sized objects. <a href="#a0509430713d587eba74220a8375948a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ee88eb786413b2cf541122aa749392c">getStackProtectorIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index for the stack protector object. <a href="#a5ee88eb786413b2cf541122aa749392c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79ce969f0376bbc0a6f06966ce274167">setStackProtectorIndex</a> (int I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7c993678733273ea9d16db7ff87b2c6">hasStackProtectorIndex</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afca388351fa4893f6e67476db9350983">getFunctionContextIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index for the function context object. <a href="#afca388351fa4893f6e67476db9350983">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe5772922837eb92e41c2d397809c9eb">setFunctionContextIndex</a> (int I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2c878d38ca7ead514ef744f46e05779">hasFunctionContextIndex</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32125253541ab2e7ec5bbe550ecc2d0c">isFrameAddressTaken</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be called any time after instruction selection is complete to determine if there is a call to @llvm.frameaddress in this function. <a href="#a32125253541ab2e7ec5bbe550ecc2d0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9a38005d95189db3246e0e4ec6088d">setFrameAddressIsTaken</a> (bool T)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20fde7903c3d7ad21cc5825bb886e360">isReturnAddressTaken</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be called any time after instruction selection is complete to determine if there is a call to @llvm.returnaddress in this function. <a href="#a20fde7903c3d7ad21cc5825bb886e360">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81b01652144140bfb79c6ffdaff923f9">setReturnAddressIsTaken</a> (bool s)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7d9e2f26e4c8b32f51c455b220ce13c">hasStackMap</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be called any time after instruction selection is complete to determine if there is a call to builtin @llvm.experimental.stackmap. <a href="#aa7d9e2f26e4c8b32f51c455b220ce13c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a516c061efff162d3443801359559aa65">setHasStackMap</a> (bool s=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a503a8cb169aa29ac907c218692087db3">hasPatchPoint</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be called any time after instruction selection is complete to determine if there is a call to builtin @llvm.experimental.patchpoint. <a href="#a503a8cb169aa29ac907c218692087db3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24116ef8cbdb5ac84d8b39da3123a2ba">setHasPatchPoint</a> (bool s=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00d2c6aab11836fcd2116ef07924253e">needsSplitStackProlog</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this function requires a split stack prolog, even if it uses no stack space. <a href="#a00d2c6aab11836fcd2116ef07924253e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae70474766f2a88bab5b2b77bcb22212b">getObjectIndexBegin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the minimum frame object index. <a href="#ae70474766f2a88bab5b2b77bcb22212b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac51e2d34abb79b72afef355fac525c76">getObjectIndexEnd</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return one past the maximum frame object index. <a href="#ac51e2d34abb79b72afef355fac525c76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ccc7c575c4513731612b1d73b4bac0">getNumFixedObjects</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of fixed objects. <a href="#ad8ccc7c575c4513731612b1d73b4bac0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4b44bc5aa744df4f8b70f971e8dcbf1">getNumObjects</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of objects. <a href="#ab4b44bc5aa744df4f8b70f971e8dcbf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a853b47f34cdca978a18d7120e64bd4a1">mapLocalFrameObject</a> (int ObjectIndex, int64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a frame index into the local object block. <a href="#a853b47f34cdca978a18d7120e64bd4a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; int, int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4987e73cba3f5835d640322be09d98bd">getLocalFrameObjectMap</a> (int i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the local offset mapping for a for an object. <a href="#a4987e73cba3f5835d640322be09d98bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23eb9fb6560e43fa6164b4ef35654628">getLocalFrameObjectCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of objects allocated into the local object block. <a href="#a23eb9fb6560e43fa6164b4ef35654628">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e8a5cc0ba7568b8e0584139d97c0cc">setLocalFrameSize</a> (int64_t sz)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the size of the local object blob. <a href="#a39e8a5cc0ba7568b8e0584139d97c0cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa306e1d00f65a9bb1030e66e9d195a69">getLocalFrameSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size of the local object blob. <a href="#aa306e1d00f65a9bb1030e66e9d195a69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cdc7b3a76eaab70c6fabdf4ca3dd7e5">setLocalFrameMaxAlign</a> (Align Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Required alignment of the local object blob, which is the strictest alignment of any object in it. <a href="#a5cdc7b3a76eaab70c6fabdf4ca3dd7e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38a536a09e7b29b14de24d3a0cb6f1b3">getLocalFrameMaxAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the required alignment of the local object blob. <a href="#a38a536a09e7b29b14de24d3a0cb6f1b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5990b78705882c9de507550bc81c40cb">getUseLocalStackAllocationBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get whether the local allocation blob should be allocated together or let PEI allocate the locals in it directly. <a href="#a5990b78705882c9de507550bc81c40cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37cfdca2465d899059663518672882b0">setUseLocalStackAllocationBlock</a> (bool v)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setUseLocalStackAllocationBlock - Set whether the local allocation blob should be allocated together or let PEI allocate the locals in it directly. <a href="#a37cfdca2465d899059663518672882b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11d6e0b1aa8f7709f0330318b2cc5f1b">isObjectPreAllocated</a> (int ObjectIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the object was pre-allocated into the local block. <a href="#a11d6e0b1aa8f7709f0330318b2cc5f1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9284fd53296d2a2f8ae654d000971000">getObjectSize</a> (int ObjectIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size of the specified object. <a href="#a9284fd53296d2a2f8ae654d000971000">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b1c146aac2536b62f73bd01e36c3e9">setObjectSize</a> (int ObjectIdx, int64_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the size of the specified stack object. <a href="#a65b1c146aac2536b62f73bd01e36c3e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8320a54de0a273478de910ac3795058b">getObjectAlign</a> (int ObjectIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the alignment of the specified stack object. <a href="#a8320a54de0a273478de910ac3795058b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b207734207bd39ae7cc1b287e915160">contributesToMaxAlignment</a> (uint8_t StackID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should this stack <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> be considered in MaxAlignment. <a href="#a4b207734207bd39ae7cc1b287e915160">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4c34648ca4596767ff0c3409fc3f2d9">setObjectAlignment</a> (int ObjectIdx, Align Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setObjectAlignment - Change the alignment of the specified stack object. <a href="#af4c34648ca4596767ff0c3409fc3f2d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a171600b1de399e1d60976508ffb38ea3">getObjectAllocation</a> (int ObjectIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the underlying Alloca of the specified stack object if it exists. <a href="#a171600b1de399e1d60976508ffb38ea3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09a2f9ee42204ff9d368f62c61a06bf1">clearObjectAllocation</a> (int ObjectIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the underlying Alloca of the specified stack object if it exists. <a href="#a09a2f9ee42204ff9d368f62c61a06bf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf98860d7f42290f873c82a981eb0ea6">getObjectOffset</a> (int ObjectIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the assigned stack offset of the specified object from the incoming stack pointer. <a href="#adf98860d7f42290f873c82a981eb0ea6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a850b4b75082cdacb4c1c692856248d84">isObjectZExt</a> (int ObjectIdx) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0baf8d3feb99247cc5341a3612fef165">setObjectZExt</a> (int ObjectIdx, bool IsZExt)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa42be2b24be8e5c8a5037d4b0ef20855">isObjectSExt</a> (int ObjectIdx) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58f8798e1a5673018d0877282f893a69">setObjectSExt</a> (int ObjectIdx, bool IsSExt)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cd29e7edbcaceb5834eaa7d089a5bc4">setObjectOffset</a> (int ObjectIdx, int64_t SPOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the stack frame offset of the specified object. <a href="#a3cd29e7edbcaceb5834eaa7d089a5bc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3df888d2d0447ad8ff7b616b080d9f13">SSPLayoutKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e63dce45e27f16d0fe42d473c9598c8">getObjectSSPLayout</a> (int ObjectIdx) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5938f9d0441c7b989d3e08e4dbd81ddf">setObjectSSPLayout</a> (int ObjectIdx, SSPLayoutKind Kind)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14c39a24bf6ebbe339ae8a453c7fdd11">getStackSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bytes that must be allocated to hold all of the fixed size frame objects. <a href="#a14c39a24bf6ebbe339ae8a453c7fdd11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4d51e9e70d6a7fb366f2a09d10a0945">setStackSize</a> (uint64_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the size of the stack. <a href="#ae4d51e9e70d6a7fb366f2a09d10a0945">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66046fdf8661d5276f951337b0cf892d">estimateStackSize</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate and return the size of the stack frame. <a href="#a66046fdf8661d5276f951337b0cf892d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60679e554cbf7092c8a0ae6c5db2661a">getOffsetAdjustment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the correction for frame offsets. <a href="#a60679e554cbf7092c8a0ae6c5db2661a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af941923e75bebb485321894b2ddbeb0a">setOffsetAdjustment</a> (int64_t Adj)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the correction for frame offsets. <a href="#af941923e75bebb485321894b2ddbeb0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3836203fac855ac3c5718b701bd13ffd">getMaxAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the alignment in bytes that this function must be aligned to, which is greater than the default stack alignment provided by the target. <a href="#a3836203fac855ac3c5718b701bd13ffd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f09e99062be1101e3a2cf3ff88878f7">ensureMaxAlignment</a> (Align Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make sure the function is at least <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> bytes aligned. <a href="#a1f09e99062be1101e3a2cf3ff88878f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f3c466a5b43fe5ca61db322b5dcac0d">shouldRealignStack</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if stack realignment is forced by function attributes or if the stack alignment. <a href="#a4f3c466a5b43fe5ca61db322b5dcac0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19e260b3bbf8fad8480d151e11919836">adjustsStack</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this function adjusts the stack – e.g., when calling another function. <a href="#a19e260b3bbf8fad8480d151e11919836">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14ca8f1aa1c62b860504b766ad3b15f9">setAdjustsStack</a> (bool V)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc8bb867c8949943ca7d88f1db31fde">hasCalls</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the current function has any function calls. <a href="#a2cc8bb867c8949943ca7d88f1db31fde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bb88f5f9d77d753e87c256950f16955">setHasCalls</a> (bool V)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51773b6c05f392988bf6395ccd1788ce">hasOpaqueSPAdjustment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the function contains opaque dynamic stack adjustments. <a href="#a51773b6c05f392988bf6395ccd1788ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1c21b032c9a8c45eed19c74c40e9999">setHasOpaqueSPAdjustment</a> (bool B)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac901643b9a98a52b1c323b79f28b8dcc">hasCopyImplyingStackAdjustment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the function contains operations which will lower down to instructions which manipulate the stack pointer. <a href="#ac901643b9a98a52b1c323b79f28b8dcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab445176256051725bc6d3e543af5029a">setHasCopyImplyingStackAdjustment</a> (bool B)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab512cf99651d9d49323b0ac9a25c7f8d">hasVAStart</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the function calls the llvm.va_start intrinsic. <a href="#ab512cf99651d9d49323b0ac9a25c7f8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae52ff27f281ac6f032b78b0d95bc7d24">setHasVAStart</a> (bool B)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7819a781e436c677ed1613c7739ee53e">hasMustTailInVarArgFunc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the function is variadic and contains a musttail call. <a href="#a7819a781e436c677ed1613c7739ee53e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef2320fad6df35f6fca25cd93720da60">setHasMustTailInVarArgFunc</a> (bool B)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a763b7a1e7127b495f396b30f0d9c95f1">hasTailCall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the function contains a tail call. <a href="#a763b7a1e7127b495f396b30f0d9c95f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a701abf47478571dfb8c619678b7ce7d7">setHasTailCall</a> (bool V=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12da92f702a20d5337a5258038968d09">computeMaxCallFrameSize</a> (MachineFunction &amp;MF, std::vector&lt; MachineBasicBlock::iterator &gt; *FrameSDOps=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the maximum size of a callframe. <a href="#a12da92f702a20d5337a5258038968d09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f335273c28b17552a7cfd802f42be2a">getMaxCallFrameSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximum size of a call frame that must be allocated for an outgoing function call. <a href="#a4f335273c28b17552a7cfd802f42be2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99cdf1b99c0f1b7e1bf2111aa7d2eaa3">isMaxCallFrameSizeComputed</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02a7503d1af1782b35b3683e173cb5f0">setMaxCallFrameSize</a> (uint64_t S)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab64be7aad4478fdbd1c73f0ec4dabaf8">getCVBytesOfCalleeSavedRegisters</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how many bytes of callee-saved registers the target pushed in the prologue. <a href="#ab64be7aad4478fdbd1c73f0ec4dabaf8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ed62fb6fd245cb4efd8ea1bb4d56856">setCVBytesOfCalleeSavedRegisters</a> (unsigned S)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03cf34252938b54f7e86c736f9fd7dc1">CreateFixedObject</a> (uint64_t Size, int64_t SPOffset, bool IsImmutable, bool isAliased=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new object at a fixed location on the stack. <a href="#a03cf34252938b54f7e86c736f9fd7dc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2270087c6b8d7061c3a5e83fb61c0a6">CreateFixedSpillStackObject</a> (uint64_t Size, int64_t SPOffset, bool IsImmutable=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a spill slot at a fixed location on the stack. <a href="#ad2270087c6b8d7061c3a5e83fb61c0a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6e7e975f7a4e5d535be32068a7c67df">isFixedObjectIndex</a> (int ObjectIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified index corresponds to a fixed stack object. <a href="#ae6e7e975f7a4e5d535be32068a7c67df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe20684ee4170df6085d75ef85f0124a">isAliasedObjectIndex</a> (int ObjectIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified index corresponds to an object that might be pointed to by an LLVM IR value. <a href="#afe20684ee4170df6085d75ef85f0124a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dfc119c1adb845f7eea8851a7c6a69c">setIsAliasedObjectIndex</a> (int ObjectIdx, bool IsAliased)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set "maybe pointed to by an LLVM IR value" for an object. <a href="#a7dfc119c1adb845f7eea8851a7c6a69c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eab840dac82571e53cc5f1c05643e2a">isImmutableObjectIndex</a> (int ObjectIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified index corresponds to an immutable object. <a href="#a5eab840dac82571e53cc5f1c05643e2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d6c9ad6ad96f64b2fe861339c192f68">setIsImmutableObjectIndex</a> (int ObjectIdx, bool IsImmutable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marks the immutability of an object. <a href="#a0d6c9ad6ad96f64b2fe861339c192f68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91b0115deec3489d7e082a4a13f022ff">isSpillSlotObjectIndex</a> (int ObjectIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified index corresponds to a spill slot. <a href="#a91b0115deec3489d7e082a4a13f022ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e9c6f5b0faff7f4a53c3c7ab8b2dd07">isStatepointSpillSlotObjectIndex</a> (int ObjectIdx) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad718aae0ce2a188fa35cb2781024ffc0">getStackID</a> (int ObjectIdx) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba514594eb802f087046edbe201f8f4">setStackID</a> (int ObjectIdx, uint8_t ID)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5302d38d9a16eee93f13a1579c8773d">isDeadObjectIndex</a> (int ObjectIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified index corresponds to a dead object. <a href="#af5302d38d9a16eee93f13a1579c8773d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab86af583f3ac779bb3f74071d36b5923">isVariableSizedObjectIndex</a> (int ObjectIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified index corresponds to a variable sized object. <a href="#ab86af583f3ac779bb3f74071d36b5923">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477686b0d65454f32799cb86f406104c">markAsStatepointSpillSlotObjectIndex</a> (int ObjectIdx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae307f415a8989475e3f7ddd6eefc8b">CreateStackObject</a> (uint64_t Size, Align Alignment, bool isSpillSlot, const AllocaInst *Alloca=nullptr, uint8_t ID=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new statically sized stack object, returning a nonnegative identifier to represent it. <a href="#a1ae307f415a8989475e3f7ddd6eefc8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61960903871aa95a7161074c6f1eec8f">CreateSpillStackObject</a> (uint64_t Size, Align Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new statically sized stack object that represents a spill slot, returning a nonnegative identifier to represent it. <a href="#a61960903871aa95a7161074c6f1eec8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab356eaffcc04362671e727900a65ac52">RemoveStackObject</a> (int ObjectIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove or mark dead a statically sized stack object. <a href="#ab356eaffcc04362671e727900a65ac52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9af51d42f8f27a88d68ee1d1deb5eb7">CreateVariableSizedObject</a> (Align Alignment, const AllocaInst *Alloca)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notify the <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> object that a variable sized object has been created. <a href="#ab9af51d42f8f27a88d68ee1d1deb5eb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad474502cac7b22b83e74de089f8c81d">getCalleeSavedInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to call saved info vector for the current function. <a href="#aad474502cac7b22b83e74de089f8c81d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33dad8b95476ec43b925a0d78ecdd583">getCalleeSavedInfo</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3f912e64e60536d8369f1414b7ef380">setCalleeSavedInfo</a> (std::vector&lt; CalleeSavedInfo &gt; CSI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used by prolog/epilog inserter to set the function's callee saved information. <a href="#ab3f912e64e60536d8369f1414b7ef380">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81504f733d0491a446a16ef1ba0a5c2a">isCalleeSavedInfoValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has the callee saved info been calculated yet? <a href="#a81504f733d0491a446a16ef1ba0a5c2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e65d5ed1e6c20323a0d723c43a9f264">setCalleeSavedInfoValid</a> (bool v)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5ba92668c96fb23e8d5fa9add3daab6">getSavePoint</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc98dd738845a40c876cbbf6f5e51f09">setSavePoint</a> (MachineBasicBlock *NewSave)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b92dc4f379813174c0942c8d1d8e241">getRestorePoint</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b15f54419f33a561a4b6959b2d0969">setRestorePoint</a> (MachineBasicBlock *NewRestore)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac08fc384e90a861a5934987272675ecc">getUnsafeStackSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecbf301c7010f06b304aa10365e2b91a">setUnsafeStackSize</a> (uint64_t Size)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa42c3828ac3f788f2ef3ff6fa46e4926">getPristineRegs</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a set of physical registers that are pristine. <a href="#aa42c3828ac3f788f2ef3ff6fa46e4926">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab49a74c3c0e9f35a453eb0db340424e7">print</a> (const MachineFunction &amp;MF, raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used by the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> printer to print information about stack objects. <a href="#ab49a74c3c0e9f35a453eb0db340424e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac42b489f21274bae5d397b8ae8ddd0cf">dump</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dump - Print the function to stderr. <a href="#ac42b489f21274bae5d397b8ae8ddd0cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f6558ee33cbd213c2e8f65456c0ca2a">StackAlignment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The alignment of the stack. <a href="#a5f6558ee33cbd213c2e8f65456c0ca2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56909a798a584b26bbc78e829ab85d75">StackRealignable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Can the stack be realigned. <a href="#a56909a798a584b26bbc78e829ab85d75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02a39dc379f899e79a0443e70ad7419e">ForcedRealign</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the function has the <span class="doxyComputerOutput">alignstack</span> attribute. <a href="#a02a39dc379f899e79a0443e70ad7419e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; StackObject &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff9424c694e902d27b25595762306fbe">Objects</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of stack objects allocated. <a href="#aff9424c694e902d27b25595762306fbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a724d6e9b7d17e02038e7b3cff288c701">NumFixedObjects</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This contains the number of fixed objects contained on the stack. <a href="#a724d6e9b7d17e02038e7b3cff288c701">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87a9eedd78b034d3f10c641c214d3fae">HasVarSizedObjects</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This boolean keeps track of whether any variable sized objects have been allocated yet. <a href="#a87a9eedd78b034d3f10c641c214d3fae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1bd4f8bc99f9c9d3e0ebce9e7ec8e76">FrameAddressTaken</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This boolean keeps track of whether there is a call to builtin @llvm.frameaddress. <a href="#af1bd4f8bc99f9c9d3e0ebce9e7ec8e76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a018f958f0f234ca0d11ea854ae628c2f">ReturnAddressTaken</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This boolean keeps track of whether there is a call to builtin @llvm.returnaddress. <a href="#a018f958f0f234ca0d11ea854ae628c2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab94b2efe4b22474f66d48b2730e8b4c9">HasStackMap</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This boolean keeps track of whether there is a call to builtin @llvm.experimental.stackmap. <a href="#ab94b2efe4b22474f66d48b2730e8b4c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4fb3ea5454851cae5333dfd6a0d03f3">HasPatchPoint</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This boolean keeps track of whether there is a call to builtin @llvm.experimental.patchpoint. <a href="#af4fb3ea5454851cae5333dfd6a0d03f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fad43d5b2aba0a5827cbf40c5e64fa0">StackSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The prolog/epilog code inserter calculates the final stack offsets for all of the fixed size objects, updating the Objects list above. <a href="#a6fad43d5b2aba0a5827cbf40c5e64fa0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b262ea7da36885332a727434e0e2783">OffsetAdjustment</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The amount that a frame offset needs to be adjusted to have the actual offset from the stack/frame pointer. <a href="#a1b262ea7da36885332a727434e0e2783">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad283c4b55d2343c426d1ef3ba43b9322">MaxAlignment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The prolog/epilog code inserter may process objects that require greater alignment than the default alignment the target provides. <a href="#ad283c4b55d2343c426d1ef3ba43b9322">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab944fbcaea791e49c2365b083a4da6f1">AdjustsStack</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to true if this function adjusts the stack – e.g., when calling another function. <a href="#ab944fbcaea791e49c2365b083a4da6f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c185e69bf0d1852e788721aa35b0620">HasCalls</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to true if this function has any function calls. <a href="#a4c185e69bf0d1852e788721aa35b0620">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5692108667d80a25c8fd4ed4258a7e">StackProtectorIdx</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The frame index for the stack protector. <a href="#aab5692108667d80a25c8fd4ed4258a7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347c67d70fbcc35e68fb27d22c1402ed">FunctionContextIdx</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The frame index for the function context. Used for SjLj exceptions. <a href="#a347c67d70fbcc35e68fb27d22c1402ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82fbd0176ea84c953243e8b10533bfd6">MaxCallFrameSize</a> = ~UINT64_C(0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This contains the size of the largest call frame if the target uses frame setup/destroy pseudo instructions (as defined in the TargetFrameInfo class). <a href="#a82fbd0176ea84c953243e8b10533bfd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa623ac77c2a3c3109568e03dae8455ff">CVBytesOfCalleeSavedRegisters</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bytes of callee saved registers that the target wants to report for the current function in the CodeView S_FRAMEPROC record. <a href="#aa623ac77c2a3c3109568e03dae8455ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04abe16273570412452077008a63cc25">CSInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The prolog/epilog code inserter fills in this vector with each callee saved register saved in either the frame or a different register. <a href="#a04abe16273570412452077008a63cc25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eda63f11bcedd9f2d8cd9aeacdbb57a">CSIValid</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has CSInfo been set yet? <a href="#a7eda63f11bcedd9f2d8cd9aeacdbb57a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; int, int64_t &gt;, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee2b6e9566815515a5762320cdabf7c9">LocalFrameObjects</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>References to frame indices which are mapped into the local frame allocation block. <a href="#aee2b6e9566815515a5762320cdabf7c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04f98738c2347869d2c21a6ad56d1c39">LocalFrameSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of the pre-allocated local frame block. <a href="#a04f98738c2347869d2c21a6ad56d1c39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a165c88931366076a33dbc69dbb2a841c">LocalFrameMaxAlign</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Required alignment of the local object blob, which is the strictest alignment of any object in it. <a href="#a165c88931366076a33dbc69dbb2a841c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada495f42ebe7565aafb567a01bc8f762">UseLocalStackAllocationBlock</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the local object blob needs to be allocated together. <a href="#ada495f42ebe7565aafb567a01bc8f762">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfbdba4b57a070dff011e21b9dd8da8d">HasOpaqueSPAdjustment</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the function dynamically adjusts the stack pointer through some opaque mechanism like inline assembly or Win32 EH. <a href="#abfbdba4b57a070dff011e21b9dd8da8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbde54f61eb0eefe290d1c766510b7c9">HasCopyImplyingStackAdjustment</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the function contains operations which will lower down to instructions which manipulate the stack pointer. <a href="#abbde54f61eb0eefe290d1c766510b7c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc80a3d853d4ea6d6b7129610bed0306">HasVAStart</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the function contains a call to the llvm.vastart intrinsic. <a href="#abc80a3d853d4ea6d6b7129610bed0306">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a706c186c4c6967664e4ee052a3f4d28e">HasMustTailInVarArgFunc</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is a varargs function that contains a musttail call. <a href="#a706c186c4c6967664e4ee052a3f4d28e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f348952ada90a5d94155dc87247d560">HasTailCall</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this function contains a tail call. <a href="#a7f348952ada90a5d94155dc87247d560">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a242ff5704d42e44d632ebb6dc0a5a570">Save</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Not null, if shrink-wrapping found a better place for the prologue. <a href="#a242ff5704d42e44d632ebb6dc0a5a570">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac432932b106d6b7eec3570d4e07fbc5a">Restore</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Not null, if shrink-wrapping found a better place for the epilogue. <a href="#ac432932b106d6b7eec3570d4e07fbc5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3be7d7e0d8435d4a3fc7190b4923af24">UnsafeStackSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of the UnsafeStack Frame. <a href="#a3be7d7e0d8435d4a3fc7190b4923af24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> class represents an abstract stack frame until prolog/epilog code is inserted.</p>


<p>This class is key to allowing stack frame representation optimizations, such as frame pointer elimination. It also allows more mundane (but still important) optimizations, such as reordering of abstract objects on the stack frame.</p>


<p>To support this, the class assigns unique integer identifiers to stack objects requested clients. These identifiers are negative integers for fixed stack objects (such as arguments passed on the stack) or nonnegative for objects that may be reordered. Instructions which refer to stack objects use a special MO_FrameIndex operand to represent these frame indexes.</p>


<p>Because this class keeps track of all references to the stack frame, it knows when a variable sized object is allocated on the stack. This is the sole condition which prevents frame pointer elimination, which is an important optimization on register-poor architectures. Because original variable sized alloca's in the source program are the only source of variable sized stack objects, it is safe to decide whether there will be any variable sized objects before all stack objects are known (for example, register allocator spill code never needs variable sized objects).</p>


<p>When prolog/epilog code emission is performed, the final stack frame is built and the machine instructions are modified to refer to the actual stack offsets of the object, eliminating all MO_FrameIndex operands from the program.</p>


<p>Abstract Stack Frame Information</p>


<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### SSPLayoutKind {#a3df888d2d0447ad8ff7b616b080d9f13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MachineFrameInfo::SSPLayoutKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stack Smashing Protection (SSP) rules require that vulnerable stack allocations are located close the stack protector.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSPLK_None<a id="a3df888d2d0447ad8ff7b616b080d9f13ae58c4225f24cd64ac3846a49952e48e1"></a></td>
<td class="doxyEnumItemDescription">Did not trigger a stack protector</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSPLK_LargeArray<a id="a3df888d2d0447ad8ff7b616b080d9f13a76435b76764cc940002d104e49c49c26"></a></td>
<td class="doxyEnumItemDescription">Array or nested array &gt;= SSP-buffer-size</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSPLK_SmallArray<a id="a3df888d2d0447ad8ff7b616b080d9f13a647d449df7ecda0f9add6d04209380ed"></a></td>
<td class="doxyEnumItemDescription">Array or nested array &lt; SSP-buffer-size</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSPLK_AddrOf<a id="a3df888d2d0447ad8ff7b616b080d9f13adec9480be1bffa4bb7a4ff2352b371f0"></a></td>
<td class="doxyEnumItemDescription">The address of this allocation is exposed and triggered protection</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachineFrameInfo() {#a22785bee142f66d053d8a7742d12820f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineFrameInfo::MachineFrameInfo (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> StackAlignment, bool StackRealignable, bool ForcedRealign)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="#ad37b5d2eaee40945fb9318e8d9ae7d73">MachineFrameInfo</a>.</p>

</div>
</div>

### MachineFrameInfo() {#ad37b5d2eaee40945fb9318e8d9ae7d73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineFrameInfo::MachineFrameInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> &amp;)</td>
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



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="#a22785bee142f66d053d8a7742d12820f">MachineFrameInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### adjustsStack() {#a19e260b3bbf8fad8480d151e11919836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::adjustsStack ()</td>
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

<p>Return true if this function adjusts the stack – e.g., when calling another function.</p>


<p>This is only valid during and after prolog/epilog code insertion.</p>


<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#adf86b81af5da74aea6a11c36eadf41be">llvm::AArch64RegisterInfo::cannotEliminateFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#aa0eb9ad617a055468d105965502662c5">llvm::ARMBaseRegisterInfo::cannotEliminateFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac2efa5f4dacdde70f912da43c1f8ffcf">llvm::PPCFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#affe78904b64f71286945c438ebf31bc7">llvm::Mips16FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a198d0eb07bb9ae2ff6dba28a16264342">llvm::SparcFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="#a66046fdf8661d5276f951337b0cf892d">estimateStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#aec1517c8d806609cb368f431ddab1bc7">llvm::VEInstrInfo::expandGetStackTopPseudo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#ab7e47514d5ce433432975dac4df8e7e7">isXPLeafCandidate</a>.</p>

</div>
</div>

### clearObjectAllocation() {#a09a2f9ee42204ff9d368f62c61a06bf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::clearObjectAllocation (int ObjectIdx)</td>
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

<p>Remove the underlying Alloca of the specified stack object if it exists.</p>


<p>This generally should not be used and is for reduction tooling.</p>


<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### computeMaxCallFrameSize() {#a12da92f702a20d5337a5258038968d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineFrameInfo::computeMaxCallFrameSize (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &gt; * FrameSDOps=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes the maximum size of a callframe.</p>


<p>This only works for targets defining <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a83870b05e73f275887a1e20baa621475">TargetInstrInfo::getCallFrameSetupOpcode()</a>, getCallFrameDestroyOpcode(), and getFrameSize(). This is usually computed by the prologue epilogue inserter but some targets may call this to compute it earlier. If FrameSDOps is passed, the frame instructions in the MF will be inserted into it.</p>


<p>Declaration at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp">MachineFrameInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a35198b01162433a12919d5a5947fbe83">llvm::ARMTargetLowering::finalizeLowering</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a917a79b56742eaac2db61e2a221d3011">llvm::AArch64Subtarget::mirFileLoaded</a>.</p>

</div>
</div>

### contributesToMaxAlignment() {#a4b207734207bd39ae7cc1b287e915160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::contributesToMaxAlignment (uint8_t StackID)</td>
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

<p>Should this stack <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> be considered in MaxAlignment.</p>

<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5af2af9eb94ff1bc08308bc738d744ee85">llvm::TargetStackID::Default</a> and <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a3c6a2a8f3cda71661a17a0df700e8f9c">llvm::TargetStackID::ScalableVector</a>.</p>


<p>Referenced by <a href="#a1ae307f415a8989475e3f7ddd6eefc8b">CreateStackObject</a> and <a href="#af4c34648ca4596767ff0c3409fc3f2d9">setObjectAlignment</a>.</p>

</div>
</div>

### CreateFixedObject() {#a03cf34252938b54f7e86c736f9fd7dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MachineFrameInfo::CreateFixedObject (uint64_t Size, int64_t SPOffset, bool IsImmutable, bool isAliased=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new object at a fixed location on the stack.</p>


<p>All fixed objects should be created before other objects are created for efficiency. By default, fixed objects are not pointed to by LLVM IR values. This returns an index with a negative value.</p>


<p>Declaration at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp">MachineFrameInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp/#a045293c9d11301dfb0f8b047fc9a78d7">clampStackAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd6aa057934751aaac54e5c18bcc18eb">llvm::commonAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a24d6b4ddc639fabd7fed767dbedfecc2">CalculateTailCallArgDest</a>, <a href="/web-llvm/docs/api/classes/llvm/xcorefunctioninfo/#a75dfee78519833f2ad7e210c5e471f5d">llvm::XCoreFunctionInfo::createLRSpillSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiframelowering/#af9008c34cdebe84ae9252952470f0599">llvm::LanaiFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a16d9aef1065a0997fe2ac4b560ca9cce">llvm::M68kFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a88484d585ecc86920ebee6396946eae2">llvm::PPCFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#acca11c9d64a646da497e82dcf6e9636e">EmitTailCallStoreFPAndRetAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#aa3e32d9a4b0cb160ffd67dfdf53f7fa6">EmitTailCallStoreRetAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a1ae53e898b0dee354e1b6e38d302d071">getOrCreateFixedStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a23acc2efffdbd8d4592f6c70004b958a">llvm::SystemZELFFrameLowering::getOrCreateFramePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a44f850288e925f301a01218710e88254">llvm::SystemZXPLINKFrameLowering::getOrCreateFramePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a05a6b99eac75ab2bb04130e0abf6340b">llvm::MSP430TargetLowering::getReturnAddressFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adc0b03138cc7b455d625146b7091345d">llvm::X86TargetLowering::getReturnAddressFrameIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a11c07e0125e7cd5df9cd7747977f9638">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingarghandler/#a6901759e2aab843e39497ccb23a0c3cd">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a2cc4d384d22ddae8f252b9cbb9313949">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#af4e7be374a3346400a32967d91108c3e">llvm::LoongArchTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abae2fc34bf7e289e53e0abf82feea144">llvm::RISCVTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#abd42e7de94d28ca6667b61e1bcba6dce">llvm::VETargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a405578f0decf5610edec9f350a54e81f">llvm::SparcTargetLowering::LowerFormalArguments_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ae87be78c50d3026c58e203aa8f0b9164">llvm::SparcTargetLowering::LowerFormalArguments_64</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a9462cc875c5c343ff7ae9b3d68ce6305">llvm::AArch64FrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#ad267cb394a330a7705c10be5609d02bf">llvm::MSP430FrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a4fe763745add3c357f272b8f41264d6a">unpack64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae3c73a05257120f8a564e40826d20ace">unpackF64OnRV32DSoftABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>.</p>

</div>
</div>

### CreateFixedSpillStackObject() {#ad2270087c6b8d7061c3a5e83fb61c0a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MachineFrameInfo::CreateFixedSpillStackObject (uint64_t Size, int64_t SPOffset, bool IsImmutable=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a spill slot at a fixed location on the stack.</p>


<p>Returns an index with a negative value.</p>


<p>Declaration at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp">MachineFrameInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp/#a045293c9d11301dfb0f8b047fc9a78d7">clampStackAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd6aa057934751aaac54e5c18bcc18eb">llvm::commonAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#abde55543f0bbb31306a6cd2af297fe9f">assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#af79b8bdd9826c6c96dd238e32520fc94">llvm::ARCFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#adc3de6cf6278fe59671bbdd02e4c1516">llvm::HexagonFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a3b9c6a6d8deeb4b38fe15c4bbfcfaced">llvm::M68kFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a0c9359d4e969f68a7c7643fc3fcb5c">llvm::RISCVFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#af8195925dae80a73b2c6101290b5962b">llvm::SystemZXPLINKFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### CreateSpillStackObject() {#a61960903871aa95a7161074c6f1eec8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MachineFrameInfo::CreateSpillStackObject (uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new statically sized stack object that represents a spill slot, returning a nonnegative identifier to represent it.</p>

<p>Declaration at line 792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp">MachineFrameInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp/#a045293c9d11301dfb0f8b047fc9a78d7">clampStackAlignment</a>, <a href="#a1ae307f415a8989475e3f7ddd6eefc8b">CreateStackObject</a>, <a href="#a1f09e99062be1101e3a2cf3ff88878f7">ensureMaxAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac65455efc149d81b4d1418acae7596b3">llvm::PPCFrameLowering::addScavengingSpillSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a1e0aa89e6577318443a666796f159a30">llvm::SIMachineFunctionInfo::allocateWWMSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a058c4d3a1147ae3ec1098c3031fe32cb">llvm::CSKYFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a878a2b864e18e3d074d75b426ea7912d">llvm::HexagonFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a27b8c40891bfea8db2ad3b9fa25cba0f">llvm::MipsSEFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a230b654eb7319d9e7a6d9d62afa2d5f8">llvm::ARCFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#ae380dabb206877f151fa2c3c39f9585a">llvm::RISCVFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a24b80d6d36821f80675874283190f291">llvm::SIFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ae45b5d3065cf62a7eac0053f27cb8103">llvm::SystemZELFFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#acd8f0ca7af8321ea32072c40fe93619e">llvm::SystemZXPLINKFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#ad1c7f63bd41f376ebc594e3f8440d1ad">llvm::XCoreFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a0c261e12c68fb10f3ab5532c07ad30c9">llvm::XtensaFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86argumentstackslotrebase-cpp-/x86argumentstackslotpass/#af787e4cab9e64467b9aa0a253171fa88">anonymous{X86ArgumentStackSlotRebase.cpp}::X86ArgumentStackSlotPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86lowertilecopy-cpp-/x86lowertilecopy/#aa17be634e24513ab263db157b226268b">anonymous{X86LowerTileCopy.cpp}::X86LowerTileCopy::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/scopedscavengeorspill/#ab0ac2a9aa1075f3e566bf2e74dafa8b7">ScopedScavengeOrSpill::ScopedScavengeOrSpill</a>.</p>

</div>
</div>

### CreateStackObject() {#a1ae307f415a8989475e3f7ddd6eefc8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MachineFrameInfo::CreateStackObject (uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool isSpillSlot, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * Alloca=nullptr, uint8_t ID=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new statically sized stack object, returning a nonnegative identifier to represent it.</p>

<p>Declaration at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp">MachineFrameInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp/#a045293c9d11301dfb0f8b047fc9a78d7">clampStackAlignment</a>, <a href="#a4b207734207bd39ae7cc1b287e915160">contributesToMaxAlignment</a>, <a href="#a1f09e99062be1101e3a2cf3ff88878f7">ensureMaxAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#abde55543f0bbb31306a6cd2af297fe9f">assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ad2f0da8ab6518a9d252876e7b996b10b">llvm::AArch64FrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a0c9359d4e969f68a7c7643fc3fcb5c">llvm::RISCVFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#af8195925dae80a73b2c6101290b5962b">llvm::SystemZXPLINKFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a168f3532cb1605bbc91fcc079892e357">llvm::X86TargetLowering::BuildFILD</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#abc6950c9642cee4a3149ee5e1afbf5fe">llvm::MipsFunctionInfo::createEhDataRegsFI</a>, <a href="/web-llvm/docs/api/classes/llvm/xcorefunctioninfo/#a3ed9b1830a33b388d26b73a324b8503f">llvm::XCoreFunctionInfo::createEHSpillSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcorefunctioninfo/#aaf7ccbc0c4ee11882e3e2835d84b90d2">llvm::XCoreFunctionInfo::createFPSpillSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#ae45b4d95be1f419bfa32ece88b82ed6f">llvm::MipsFunctionInfo::createISRRegFI</a>, <a href="/web-llvm/docs/api/classes/llvm/xcorefunctioninfo/#a75dfee78519833f2ad7e210c5e471f5d">llvm::XCoreFunctionInfo::createLRSpillSlot</a>, <a href="#a61960903871aa95a7161074c6f1eec8f">CreateSpillStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae83b3d8e9a944b5d818e80524a5003e2">llvm::SelectionDAG::CreateStackTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a576b964fe2d7d8750601681e04f05a9c">llvm::LegalizerHelper::createStackTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a94b8d8925deffd735f51d36b77d3f9ca">getAddressForMemoryInput</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#acb7e46109d46687db88c4e4f3f4f314d">llvm::RISCVMachineFunctionInfo::getMoveF64FrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#a4354515685ca31a2583e246f54977aee">llvm::MipsFunctionInfo::getMoveF64ViaSpillFI</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a3b564776c915bd764fdcaa5e36525953">llvm::SIMachineFunctionInfo::getScavengeFI</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a1b22f5dbcd629f145563ba79bcb7ce9b">llvm::CallLowering::insertSRetOutgoingArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a525e9355bccd735cf648afbde45acfc5">llvm::SparcTargetLowering::LowerF128_LibCallArg</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a85b82d7c69a744603ea8eccd2c40d52e">llvm::SparcTargetLowering::LowerF128Op</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25a5e94166cf78354826b46e402ebcd9">LowerINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvextract-cpp-/hexagonvextract/#ae163c69bb53c3aa811348aa9547a4ebb">anonymous{HexagonVExtract.cpp}::HexagonVExtract::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a0f3fc21d30eef606c68c9882dd8a97b0">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a5d1d05840235d52ee7fb4b0ce9a63b76">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a27a647930b9f60f83868035dcd46fca8">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::spillCalleeSavedRegs</a>.</p>

</div>
</div>

### CreateVariableSizedObject() {#ab9af51d42f8f27a88d68ee1d1deb5eb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MachineFrameInfo::CreateVariableSizedObject (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * Alloca)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Notify the <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> object that a variable sized object has been created.</p>


<p>This must be created whenever a variable sized object is created, whether or not the index returned is actually used.</p>


<p>Declaration at line 803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp">MachineFrameInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp/#a045293c9d11301dfb0f8b047fc9a78d7">clampStackAlignment</a> and <a href="#a1f09e99062be1101e3a2cf3ff88878f7">ensureMaxAlignment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab812d774aa563ffc2c67030a9ba1be39">llvm::AArch64TargetLowering::EmitAllocateSMESaveBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab9a65a8c0739a72de196022849b4ee67">llvm::AArch64TargetLowering::EmitAllocateZABuffer</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### dump() {#ac42b489f21274bae5d397b8ae8ddd0cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MachineFrameInfo::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>dump - Print the function to stderr.</p>

<p>Declaration at line 846 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp">MachineFrameInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#ab49a74c3c0e9f35a453eb0db340424e7">print</a>.</p>

</div>
</div>

### ensureMaxAlignment() {#a1f09e99062be1101e3a2cf3ff88878f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineFrameInfo::ensureMaxAlignment (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make sure the function is at least <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> bytes aligned.</p>

<p>Declaration at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp">MachineFrameInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>, <a href="#a61960903871aa95a7161074c6f1eec8f">CreateSpillStackObject</a>, <a href="#a1ae307f415a8989475e3f7ddd6eefc8b">CreateStackObject</a>, <a href="#ab9af51d42f8f27a88d68ee1d1deb5eb7">CreateVariableSizedObject</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#ae380dabb206877f151fa2c3c39f9585a">llvm::RISCVFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6a8d1523f211998978b3fa0bfe8818a1">llvm::X86FrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="#af4c34648ca4596767ff0c3409fc3f2d9">setObjectAlignment</a>.</p>

</div>
</div>

### estimateStackSize() {#a66046fdf8661d5276f951337b0cf892d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachineFrameInfo::estimateStackSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Estimate and return the size of the stack frame.</p>

<p>Declaration at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp">MachineFrameInfo.cpp</a>.</p>


<p>References <a href="#a19e260b3bbf8fad8480d151e11919836">adjustsStack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5af2af9eb94ff1bc08308bc738d744ee85">llvm::TargetStackID::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ac83b44e69c9f9f4f9d60be2d72f4a5df">llvm::TargetSubtargetInfo::getFrameLowering</a>, <a href="#a3836203fac855ac3c5718b701bd13ffd">getMaxAlign</a>, <a href="#a4f335273c28b17552a7cfd802f42be2a">getMaxCallFrameSize</a>, <a href="#a8320a54de0a273478de910ac3795058b">getObjectAlign</a>, <a href="#ae70474766f2a88bab5b2b77bcb22212b">getObjectIndexBegin</a>, <a href="#ac51e2d34abb79b72afef355fac525c76">getObjectIndexEnd</a>, <a href="#adf98860d7f42290f873c82a981eb0ea6">getObjectOffset</a>, <a href="#a9284fd53296d2a2f8ae654d000971000">getObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="#ad718aae0ce2a188fa35cb2781024ffc0">getStackID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a258e7041d4a768f291a4023db2b898b5">llvm::TargetFrameLowering::getTransientStackAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a238c4b47777d9678c89b6ccfa9db504c">llvm::TargetFrameLowering::hasReservedCallFrame</a>, <a href="#a0509430713d587eba74220a8375948a8">hasVarSizedObjects</a>, <a href="#af5302d38d9a16eee93f13a1579c8773d">isDeadObjectIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a058c4d3a1147ae3ec1098c3031fe32cb">llvm::CSKYFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#aaabcdae312538836cccf2ed4e8069999">llvm::XCoreFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac2efa5f4dacdde70f912da43c1f8ffcf">llvm::PPCFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering/#a7c45383cd53ee8ccfeceafc1daed18d3">llvm::MipsFrameLowering::estimateStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/xcorefunctioninfo/#a557a933450cbb8ad68f408171112efc5">llvm::XCoreFunctionInfo::isLargeFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#ab7e47514d5ce433432975dac4df8e7e7">isXPLeafCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#ae380dabb206877f151fa2c3c39f9585a">llvm::RISCVFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ae45b5d3065cf62a7eac0053f27cb8103">llvm::SystemZELFFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#acd8f0ca7af8321ea32072c40fe93619e">llvm::SystemZXPLINKFrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a0c261e12c68fb10f3ab5532c07ad30c9">llvm::XtensaFrameLowering::processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

### getCalleeSavedInfo() {#aad474502cac7b22b83e74de089f8c81d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; CalleeSavedInfo &gt; &amp; llvm::MachineFrameInfo::getCalleeSavedInfo ()</td>
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

<p>Returns a reference to call saved info vector for the current function.</p>

<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp/#a09c3edd4c226f6af4965320fa45f574d">addCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#ab22bacf399a5964155b56e9be835a6b3">llvm::LivePhysRegs::addLiveOutsNoPristines</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaregisterinfo/#a6411a92c3a3ac8af31ab80b05b0b24fe">llvm::XtensaRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a66fceb6b28377362e963e250c5c865c1">llvm::MSP430FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6c1f3151b66ea2dfd6a8b9cef815d51c">llvm::X86FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a035d6de6da7186bb6a0a180c617c8a83">emitCalleeSavedRestores</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aac8f5d5c66c21056b3144508e8142639">llvm::ARCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a586e88416ae37cf1579986caeb97a9fa">llvm::LoongArchFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#aeb6b320000ce736d5ac68e606fcc3519">llvm::MipsSEFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a6289c3b215e791396217e90177ad28a5">llvm::Thumb1FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a0461f7f7e4e1f408963beca04c51c6d4">llvm::XtensaFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a5a25bb817d51790574c718d2a39bfafc">llvm::SystemZAsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a851a237b27ce366221fcb1daf2f0d119">llvm::HexagonFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#affe78904b64f71286945c438ebf31bc7">llvm::Mips16FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#adcff3487a7ab24e32ed892aedf767cf1">emitSCSEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#acf179a5b6cfdcd80b458b93d503e0ed0">emitSCSPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a217c3db3b137e03bd6ade29bb9999ac9">llvm::AArch64FunctionInfo::getCalleeSavedStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a647fbf2c5d5bb2fe4f4b5b9af7e0ab00">llvm::TargetFrameLowering::getCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a3290bcbb58f1e5d0c6006373c1e55053">llvm::LoongArchFrameLowering::getFirstSPAdjustAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a0f71a92dc6f774b7059d9490a29d52ad">llvm::LoongArchFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a>, <a href="#aa42c3828ac3f788f2ef3ff6fa46e4926">getPristineRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#aada6bb4af36a2736480f0c51fced2d58">llvm::ARMSubtarget::getPushPopSplitVariation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#acede596c16f946c19dacb339e25ff978">getSVECalleeSaveSlotRange</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#a1ae314e6d4d78cd50108dbe69ad317b0">llvm::Mips16InstrInfo::makeFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a2f9c9ef300cdd17a112e9760aaf73e82">llvm::MipsAsmPrinter::printSavedRegsBitmask</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3f176ff8abd35fbe2f043c22d088302e">llvm::PPCFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#ae380dabb206877f151fa2c3c39f9585a">llvm::RISCVFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#acd8f0ca7af8321ea32072c40fe93619e">llvm::SystemZXPLINKFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa323e6c0586d706279d7e764fc18d1ba">llvm::recomputeLivenessFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a454cc7f0c0075624df31b3ae121c3506">llvm::PPCRegisterInfo::requiresFrameIndexScavenging</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a5c22366d9b2f68fba8285148c794a74d">llvm::AArch64FrameLowering::resetCFIToInitialState</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#aa742ec29cd5bc4d080c170cb881d050b">llvm::Mips16InstrInfo::restoreFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#ab462c5bbf745633740ccfb2920040000">updateLiveness</a> and <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2b5bce8095abd7b08536e0e2aa91db54">llvm::ARMFrameLowering::updateLRRestored</a>.</p>

</div>
</div>

### getCalleeSavedInfo() {#a33dad8b95476ec43b925a0d78ecdd583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; CalleeSavedInfo &gt; &amp; llvm::MachineFrameInfo::getCalleeSavedInfo ()</td>
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



<p>Definition at line 810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### getCVBytesOfCalleeSavedRegisters() {#ab64be7aad4478fdbd1c73f0ec4dabaf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineFrameInfo::getCVBytesOfCalleeSavedRegisters ()</td>
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

<p>Returns how many bytes of callee-saved registers the target pushed in the prologue.</p>


<p>Only used for debug info.</p>


<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>.</p>

</div>
</div>

### getFunctionContextIndex() {#afca388351fa4893f6e67476db9350983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MachineFrameInfo::getFunctionContextIndex ()</td>
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

<p>Return the index for the function context object.</p>


<p>This object is used for SjLj exceptions.</p>


<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a>.</p>

</div>
</div>

### getLocalFrameMaxAlign() {#a38a536a09e7b29b14de24d3a0cb6f1b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineFrameInfo::getLocalFrameMaxAlign ()</td>
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

<p>Return the required alignment of the local object blob.</p>

<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#ae7508374329448fb4210c15d9cc79ad7">llvm::ARMBaseRegisterInfo::needsFrameBaseReg</a>.</p>

</div>
</div>

### getLocalFrameObjectCount() {#a23eb9fb6560e43fa6164b4ef35654628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MachineFrameInfo::getLocalFrameObjectCount ()</td>
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

<p>Return the number of objects allocated into the local object block.</p>

<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>.</p>

</div>
</div>

### getLocalFrameObjectMap() {#a4987e73cba3f5835d640322be09d98bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; int, int64_t &gt; llvm::MachineFrameInfo::getLocalFrameObjectMap (int i)</td>
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

<p>Get the local offset mapping for a for an object.</p>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>.</p>

</div>
</div>

### getLocalFrameSize() {#aa306e1d00f65a9bb1030e66e9d195a69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MachineFrameInfo::getLocalFrameSize ()</td>
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

<p>Get the size of the local object blob.</p>

<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/structs/llvm/arcregisterinfo/#aaf69a259c2c354f83b367585a37bb14d">llvm::ARCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#acafe750c425c834b596416c311715d8c">llvm::AArch64RegisterInfo::hasBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a0e2ca33d941092c36d88209114f6fa8f">llvm::ARMBaseRegisterInfo::hasBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a83f94d5dd8793554e6f3be24bc75eea5">llvm::AArch64RegisterInfo::needsFrameBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#ae7508374329448fb4210c15d9cc79ad7">llvm::ARMBaseRegisterInfo::needsFrameBaseReg</a> and <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a019cd64618c63f99af8a18d51edd11e6">llvm::RISCVRegisterInfo::needsFrameBaseReg</a>.</p>

</div>
</div>

### getMaxAlign() {#a3836203fac855ac3c5718b701bd13ffd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineFrameInfo::getMaxAlign ()</td>
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

<p>Return the alignment in bytes that this function must be aligned to, which is greater than the default stack alignment provided by the target.</p>

<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac65455efc149d81b4d1418acae7596b3">llvm::PPCFrameLowering::addScavengingSpillSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac2efa5f4dacdde70f912da43c1f8ffcf">llvm::PPCFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a3046f0367b644d6feafcc16f8da39967">emitAlignedDPRCS2Spills</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ace1de8acc8ac15962f04832273df87b1">llvm::SIFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a9c2ee381172db4d044e61d3438031d6b">llvm::HexagonDAGToDAGISel::emitFunctionEntryCode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#af5c6e03e6ac66b0eb9389a951593985b">llvm::SIFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a198d0eb07bb9ae2ff6dba28a16264342">llvm::SparcFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#ab3c8272ea0652d9ab75b889488f2717f">llvm::VEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="#a66046fdf8661d5276f951337b0cf892d">estimateStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a4d0bcb536bd3b6491c535f206275ad89">llvm::PPCRegisterInfo::lowerDynamicAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a355a1f30be913f4dc74c51af277fd74a">llvm::PPCRegisterInfo::prepareDynamicAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a8b67fcf985704c812d104989a617a939">llvm::HexagonFrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ac57730efce0c1f82628bcdeb5ae42ce9">llvm::HexagonDAGToDAGISel::SelectFrameIndex</a>.</p>

</div>
</div>

### getMaxCallFrameSize() {#a4f335273c28b17552a7cfd802f42be2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MachineFrameInfo::getMaxCallFrameSize ()</td>
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

<p>Return the maximum size of a call frame that must be allocated for an outgoing function call.</p>


<p>This is only available if CallFrameSetup/Destroy pseudo instructions are used by the target, and then only during or after prolog/epilog code insertion.</p>


<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="#a99cdf1b99c0f1b7e1bf2111aa7d2eaa3">isMaxCallFrameSizeComputed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac2efa5f4dacdde70f912da43c1f8ffcf">llvm::PPCFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a198d0eb07bb9ae2ff6dba28a16264342">llvm::SparcFrameLowering::emitPrologue</a>, <a href="#a66046fdf8661d5276f951337b0cf892d">estimateStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#aec1517c8d806609cb368f431ddab1bc7">llvm::VEInstrInfo::expandGetStackTopPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#acd3876e593314b23ed0679279ee31dfe">llvm::X86FrameLowering::getWin64EHFrameIndexRef</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a97643b28151d68d2cec55176e739205d">llvm::AArch64FrameLowering::getWinEHFuncletFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a38fe3f67034841400e749f75768348a2">llvm::RISCVFrameLowering::hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a52626eda66484fc0cadb0d956483888b">llvm::AArch64FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a7d1c91b20625d31982210d6fc381104d">llvm::ARMFrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#ab242e5924ca5ef32768676a9e81b248f">llvm::Mips16FrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a7e8bd93c19af3e257293630169b1c165">llvm::MipsSEFrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#ab6578ac15aab22a10a00e231e45ff9cb">llvm::Thumb1FrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a4d0bcb536bd3b6491c535f206275ad89">llvm::PPCRegisterInfo::lowerDynamicAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a4b9f5c287ed918ba764f534b79876702">llvm::PPCRegisterInfo::lowerDynamicAreaOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#acd8f0ca7af8321ea32072c40fe93619e">llvm::SystemZXPLINKFrameLowering::processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

### getNumFixedObjects() {#ad8ccc7c575c4513731612b1d73b4bac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineFrameInfo::getNumFixedObjects ()</td>
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

<p>Return the number of fixed objects.</p>

<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/frameindex/#acfd0cda41dbca93baa38169e7cfdc7a4">llvm::yaml::FrameIndex::getFI</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/machinesanitizerbinarymetadata/#a937f0d635f382c2a5befe696ddd43770">anonymous{SanitizerBinaryMetadata.cpp}::MachineSanitizerBinaryMetadata::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/llvm/avrframeanalyzer/#a854b8ec11315be5c7771d9aca8762e51">llvm::AVRFrameAnalyzer::runOnMachineFunction</a>.</p>

</div>
</div>

### getNumObjects() {#ab4b44bc5aa744df4f8b70f971e8dcbf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineFrameInfo::getNumObjects ()</td>
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

<p>Return the number of objects.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a69dafe1f45af554b1b82bcde2503a3c4">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::emitStackFrameLayoutRemarks</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/frameindex/#acfd0cda41dbca93baa38169e7cfdc7a4">llvm::yaml::FrameIndex::getFI</a>, <a href="/web-llvm/docs/api/classes/llvm/r600framelowering/#a7829220a3eab94d3ec786598ab48da83">llvm::R600FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a2666dab43798128db9f7c436090e2d64">llvm::R600InstrInfo::getIndirectIndexBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a6963ee4846a440960af3393b33d4e8b0">llvm::R600InstrInfo::getIndirectIndexEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a72a70493afafbf4374226300289c04b9">llvm::AArch64InstrInfo::getOutliningTypeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abffddc65a79eca0830b7dd232ff74dc5">llvm::ARMBaseInstrInfo::getOutliningTypeImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/avrframeanalyzer/#a854b8ec11315be5c7771d9aca8762e51">llvm::AVRFrameAnalyzer::runOnMachineFunction</a>.</p>

</div>
</div>

### getObjectAlign() {#a8320a54de0a273478de910ac3795058b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineFrameInfo::getObjectAlign (int ObjectIdx)</td>
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

<p>Return the alignment of the specified stack object.</p>

<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensainstrinfo-cpp/#afb2753bad8eb2a132f72925416a0ac4c">addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24df964fef5537043b85294a38037ca1">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb2d11e8b17ef23a86d57b4105fba8e1">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#a67931ef18efe0f1710e3f2e39ddfb8f6">llvm::M68k::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#a40fe21a4879ff8f132c4fb676738c5b1">llvm::M68k::addMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a7a72b426a146f931681039777ba2bbc5">AdjustStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxprologepilogpass-cpp/#a7a72b426a146f931681039777ba2bbc5">AdjustStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a122720c6c9f5c3fd65169c6d123d2516">buildEpilogRestore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a4e6b353116922112b1b470ce15adb2fd">buildPrologSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aee68072e1038a895a2998d78395db856">llvm::SIRegisterInfo::buildVGPRSpillLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a56db9c3cbc621caf7d84f6982f095392">determineSVEStackObjectOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a396c2d76e8e7c09d638a32cab9ea94bf">llvm::MipsRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="#a66046fdf8661d5276f951337b0cf892d">estimateStackSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aa45779e6cfae9dac4c65a6aa4bbdab74">fixupFuncForFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a08517d2919480dbf25deba8c5306dd39">foldInlineAsmMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6a733ae5364b0de2225af33223f383a5">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a7cfc0ecfec922ebf19bd023f3b675604">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a1d4b2effd4fbebb40f0d10cb1ed6c577">getFrameIndexMMO</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a7a7d0ca18a51d0d4829fb467deed15e9">llvm::M68kFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/r600framelowering/#a7829220a3eab94d3ec786598ab48da83">llvm::R600FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a84fbe17f451c957c67de546c98f2b79b">llvm::X86FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a3f25c09896b601cbe577cc8a814ac748">llvm::MipsInstrInfo::GetMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff719a7221f395b1b3849c9675ca32dd">llvm::inferAlignFromPtrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8d72d0dbb6d5ab8b970a32519122d85c">llvm::SelectionDAG::InferPtrAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a3b4c369d3a5ee9fcd1b68218728b5951">llvm::SelectionDAGISel::isOrEquivalentToAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aef098c9f09dc6ea1e32e64d79091a237">llvm::AArch64InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#ad96e959009cbe91d2814bcdfe4fcd51c">llvm::ARCInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a81fe15801547c074b2c33034c00df067">llvm::ARMBaseInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#aa3221ba2a1b01836c1f02c48d2bd2c4e">llvm::AVRInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad3b3220844622daec97aeb14080a66e4">llvm::HexagonInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#afa83048a6e09247f7f6310ffc0681909">llvm::LoongArchInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#a3a04d16772e68de8d911d305070f0e0b">llvm::MSP430InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab4a6a57aa863f068433ba056f15c61b1">llvm::RISCVInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a38be8eeeb68d45e0a914cd8f3237ce83">llvm::SparcInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a1eeb397bafd16951ce8898c83f21c5e4">llvm::Thumb1InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a6d4af3948133ad97770947f7d1242561">llvm::VEInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a541a292af69ae4be75a66b7994e89abb">llvm::XCoreInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a4f5aa6feffe52b80166f0d252cf354cb">llvm::PPCInstrInfo::loadRegFromStackSlotNoUpd</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a897d513f6255e5eeaba5074ca4095230">llvm::HexagonFrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#adee8390bf727c3086a7b864de6c6913e">llvm::X86FrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/machinesanitizerbinarymetadata/#a937f0d635f382c2a5befe696ddd43770">anonymous{SanitizerBinaryMetadata.cpp}::MachineSanitizerBinaryMetadata::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a23de116e7a75d0aaae35a539d6a6118e">scavengeStackSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a01be2a14188ac612c910c9043ae037e1">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a310a2b4f7197b620ecb3babef5637cc2">setAlignFlagsForFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#afb9b4b3ff97e290070f42849b51a13a5">spillIncomingStatepointValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aeba4e73d60d1b4cedc120d06114c0620">llvm::AArch64InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a687fecaf502080080ba5069e6b211a65">llvm::ARCInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a8a7868df2562a3b48d08d24c9db87b98">llvm::ARMBaseInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a90829bf41a9e8e4c4e4ad59eab490719">llvm::AVRInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a9644f3506784b55b500d2f73f94d79e0">llvm::HexagonInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#aed611129b85082f7e6459907b50a8cd5">llvm::LoongArchInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#ae215353a37be6d2f533a4858bd96be74">llvm::MSP430InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a23e6d76b3b763236213c20fdd08718ed">llvm::RISCVInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#abc124725b4afa4a9d9449c6e2cfb3d73">llvm::SparcInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a952f199f7cb8a257a40193bcd67a976d">llvm::Thumb1InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3e0753735e274deee756f4b8961b88b2">llvm::Thumb2InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a2132749e515b00c60255bdb4acfba223">llvm::VEInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a915259afe54d2619524ed03c9c273c57">llvm::XCoreInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a97de15cd29255b90b2ce510e967340bf">llvm::PPCInstrInfo::storeRegToStackSlotNoUpd</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#ae8ee5af33e0f1b85755cf5a1e4951793">tryToElideArgumentCopy</a>.</p>

</div>
</div>

### getObjectAllocation() {#a171600b1de399e1d60976508ffb38ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AllocaInst * llvm::MachineFrameInfo::getObjectAllocation (int ObjectIdx)</td>
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

<p>Return the underlying Alloca of the specified stack object if it exists.</p>


<p>Returns 0 if none exists.</p>


<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/ssplayoutinfo/#a2068b15b4ae5d41ac05efbc9dd9dc48c">llvm::SSPLayoutInfo::copyToMachineFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ae8c531c36381ca6a666ca73f740335cb">llvm::WebAssemblyFrameLowering::getLocalForStackObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#af70c8631842f164543c4c32149b97759">getMMOFrameID</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a294946bd7b49d5ef31f4f42120f75b92">printFrameIndex</a>.</p>

</div>
</div>

### getObjectIndexBegin() {#ae70474766f2a88bab5b2b77bcb22212b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MachineFrameInfo::getObjectIndexBegin ()</td>
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

<p>Return the minimum frame object index.</p>

<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a96067c42b682fd10d4696fb1c0091592">allSGPRSpillsAreDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a3a45e8bba1a335538a222c1809626753">allStackObjectsAreDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#af01033da46e9a33a66573433a81eaad0">computeFreeStackSlots</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-bpfmipeephole-cpp-/#a6a294b4a511b694d1eb7a6358de71cdd">anonymous{BPFMIPeephole.cpp}::computeMinFixedObjOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a6447282533aad4f054c9bfcf8df8028f">llvm::SystemZXPLINKFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a56db9c3cbc621caf7d84f6982f095392">determineSVEStackObjectOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a69dafe1f45af554b1b82bcde2503a3c4">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::emitStackFrameLayoutRemarks</a>, <a href="#a66046fdf8661d5276f951337b0cf892d">estimateStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering/#a7c45383cd53ee8ccfeceafc1daed18d3">llvm::MipsFrameLowering::estimateStackSize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/frameindex/#a81e39b7570fe76aab90fa59359af7a41">llvm::yaml::FrameIndex::FrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/frameindex/#acfd0cda41dbca93baa38169e7cfdc7a4">llvm::yaml::FrameIndex::getFI</a>, <a href="/web-llvm/docs/api/classes/llvm/r600framelowering/#a7829220a3eab94d3ec786598ab48da83">llvm::R600FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#af70c8631842f164543c4c32149b97759">getMMOFrameID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a1ae53e898b0dee354e1b6e38d302d071">getOrCreateFixedStackObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a294946bd7b49d5ef31f4f42120f75b92">printFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#ad267cb394a330a7705c10be5609d02bf">llvm::MSP430FrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ae45b5d3065cf62a7eac0053f27cb8103">llvm::SystemZELFFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#acd8f0ca7af8321ea32072c40fe93619e">llvm::SystemZXPLINKFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a97509f8c54ec54df287f62902fd2c472">llvm::SIMachineFunctionInfo::removeDeadFrameIndices</a> and <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>.</p>

</div>
</div>

### getObjectIndexEnd() {#ac51e2d34abb79b72afef355fac525c76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MachineFrameInfo::getObjectIndexEnd ()</td>
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

<p>Return one past the maximum frame object index.</p>

<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a96067c42b682fd10d4696fb1c0091592">allSGPRSpillsAreDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a3a45e8bba1a335538a222c1809626753">allStackObjectsAreDead</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-bpfmipeephole-cpp-/#a6a294b4a511b694d1eb7a6358de71cdd">anonymous{BPFMIPeephole.cpp}::computeMinFixedObjOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/ssplayoutinfo/#a2068b15b4ae5d41ac05efbc9dd9dc48c">llvm::SSPLayoutInfo::copyToMachineFrameInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a56db9c3cbc621caf7d84f6982f095392">determineSVEStackObjectOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a69dafe1f45af554b1b82bcde2503a3c4">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::emitStackFrameLayoutRemarks</a>, <a href="#a66046fdf8661d5276f951337b0cf892d">estimateStackSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#af70c8631842f164543c4c32149b97759">getMMOFrameID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/localstackslotallocation-cpp/#a4fb27fac71c41b0d9873024cbbd12bc6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp/#a4976393743e516294356ec7fe7b5500b">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a897d513f6255e5eeaba5074ca4095230">llvm::HexagonFrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a420e13f932ebcdd50a90e807d5e5674f">llvm::SystemZELFFrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#adee8390bf727c3086a7b864de6c6913e">llvm::X86FrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a24b80d6d36821f80675874283190f291">llvm::SIFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a97509f8c54ec54df287f62902fd2c472">llvm::SIMachineFunctionInfo::removeDeadFrameIndices</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#aea20ccef4ad810aac64b6a0ac6571d3b">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/avrframeanalyzer/#a854b8ec11315be5c7771d9aca8762e51">llvm::AVRFrameAnalyzer::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a026d7ee38d907cccbeb812b0747f957c">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyStackProtector</a>.</p>

</div>
</div>

### getObjectOffset() {#adf98860d7f42290f873c82a981eb0ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MachineFrameInfo::getObjectOffset (int ObjectIdx)</td>
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

<p>Return the assigned stack offset of the specified object from the incoming stack pointer.</p>

<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af5302d38d9a16eee93f13a1579c8773d">isDeadObjectIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a5275881bd107ea2567bbcc6170773d4a">llvm::AMDGPUTargetLowering::addTokenForArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#adc3de6cf6278fe59671bbdd02e4c1516">llvm::HexagonFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#af01033da46e9a33a66573433a81eaad0">computeFreeStackSlots</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-bpfmipeephole-cpp-/#a6a294b4a511b694d1eb7a6358de71cdd">anonymous{BPFMIPeephole.cpp}::computeMinFixedObjOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a6447282533aad4f054c9bfcf8df8028f">llvm::SystemZXPLINKFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aa24149b04083669797095c1473b14f3a">llvm::AArch64RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/arcregisterinfo/#aaf69a259c2c354f83b367585a37bb14d">llvm::ARCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo/#a5846a629f1d7d7cc33ecf2a63319e14a">llvm::AVRRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/bpfregisterinfo/#a849e9ef6e1cc9fdb4a18b27bf6eadef7">llvm::BPFRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/lanairegisterinfo/#acd4d1d9eb28b9bca2ca401487bdf529e">llvm::LanaiRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#abf7147087fcf4414651e62ff5de5234e">llvm::M68kRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a396c2d76e8e7c09d638a32cab9ea94bf">llvm::MipsRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430registerinfo/#a1ae0b9564ca66a61628084c4bb858ea8">llvm::MSP430RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxregisterinfo/#a682aaf1662c79a3be4911c51eebd8cdf">llvm::NVPTXRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a91da910cd583aea849621cbf8147fe28">llvm::PPCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoreregisterinfo/#a135008911313eaf0a75d1f7a960fe915">llvm::XCoreRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaregisterinfo/#a6411a92c3a3ac8af31ab80b05b0b24fe">llvm::XtensaRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a66fceb6b28377362e963e250c5c865c1">llvm::MSP430FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6c1f3151b66ea2dfd6a8b9cef815d51c">llvm::X86FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a756acce5a5adef291dc50593ce6d56a4">llvm::XCoreFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#affe78904b64f71286945c438ebf31bc7">llvm::Mips16FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#aa1ef43d8b6e30020194591f4e5a914ac">emitVGSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/baseindexoffset/#aef9ef68102c424ca44367d30b16ac65e">llvm::BaseIndexOffset::equalBaseIndex</a>, <a href="#a66046fdf8661d5276f951337b0cf892d">estimateStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering/#a7c45383cd53ee8ccfeceafc1daed18d3">llvm::MipsFrameLowering::estimateStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6a733ae5364b0de2225af33223f383a5">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a217c3db3b137e03bd6ade29bb9999ac9">llvm::AArch64FunctionInfo::getCalleeSavedStackSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#af91c6a7b6d4486c1fb8fc021b55d240d">GetEHSpillList</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a75d48c8917ed2a09d85cf46fcda67002">llvm::HexagonFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a0f71a92dc6f774b7059d9490a29d52ad">llvm::LoongArchFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a7a7d0ca18a51d0d4829fb467deed15e9">llvm::M68kFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a46adda2adcecd14a8c1ef28661069805">llvm::MipsSEFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxframelowering/#acafaf5b04f0664b35c2b2c3d83f2de27">llvm::NVPTXFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a1d2fa221d761f2dbaeb65823e305b8d7">llvm::SIFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#ac3af49ca4a1c47f7c01abaae4e8092bf">llvm::SparcFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#af88a8f2328543f94aea3ba85d954fafa">llvm::TargetFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#a77083d402f6deba15f8ccf39ffff370e">llvm::VEFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a84fbe17f451c957c67de546c98f2b79b">llvm::X86FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#adea691938e0e44353858c07a39a5d0a6">llvm::TargetFrameLowering::getFrameIndexReferenceFromSP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ad6591055c1ba6d0a1033510f7a4eab65">llvm::AArch64FrameLowering::getFrameIndexReferencePreferSP</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a79ebbed1ceecae3f74214e33fc8c533f">llvm::X86FrameLowering::getFrameIndexReferenceSP</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ae8c531c36381ca6a666ca73f740335cb">llvm::WebAssemblyFrameLowering::getLocalForStackObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a1ae53e898b0dee354e1b6e38d302d071">getOrCreateFixedStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a94d2a07e589c43e48e5b591dd520760e">llvm::AArch64FrameLowering::getSEHFrameIndexOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a474e976fb6ef9964e16389ba57edde96">GetSpillList</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a15018e8dce8929d06d5b0e67b3ac424b">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::getStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a7d9494014ff9dbd992928542dee2e477">isConsecutiveLSLoc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64framelowering-cpp-/#af1c75104c60cd95ff2cf30d870874639">anonymous{AArch64FrameLowering.cpp}::isMergeableStackTaggingInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#ab268a162e6da94b8012d8366563ae9f7">MatchingStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a313bdf934f1f8454b6800d8d997801d2">MatchingStackOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3f176ff8abd35fbe2f043c22d088302e">llvm::PPCFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ae45b5d3065cf62a7eac0053f27cb8103">llvm::SystemZELFFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#acd8f0ca7af8321ea32072c40fe93619e">llvm::SystemZXPLINKFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#ab4bf72d745b01eea298759754c9efeba">llvm::ARMFrameLowering::ResolveFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/machinesanitizerbinarymetadata/#a937f0d635f382c2a5befe696ddd43770">anonymous{SanitizerBinaryMetadata.cpp}::MachineSanitizerBinaryMetadata::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86argumentstackslotrebase-cpp-/x86argumentstackslotpass/#af787e4cab9e64467b9aa0a253171fa88">anonymous{X86ArgumentStackSlotRebase.cpp}::X86ArgumentStackSlotPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ac6785462ddb955dc6a9a79d592dd9718">shouldClusterFI</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a026d7ee38d907cccbeb812b0747f957c">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyStackProtector</a>.</p>

</div>
</div>

### getObjectSize() {#a9284fd53296d2a2f8ae654d000971000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MachineFrameInfo::getObjectSize (int ObjectIdx)</td>
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

<p>Return the size of the specified object.</p>

<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensainstrinfo-cpp/#afb2753bad8eb2a132f72925416a0ac4c">addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24df964fef5537043b85294a38037ca1">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb2d11e8b17ef23a86d57b4105fba8e1">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#a67931ef18efe0f1710e3f2e39ddfb8f6">llvm::M68k::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#a40fe21a4879ff8f132c4fb676738c5b1">llvm::M68k::addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a5275881bd107ea2567bbcc6170773d4a">llvm::AMDGPUTargetLowering::addTokenForArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a7a72b426a146f931681039777ba2bbc5">AdjustStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxprologepilogpass-cpp/#a7a72b426a146f931681039777ba2bbc5">AdjustStackOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a4841be2489ba10321338a1874b53f249">llvm::StatepointLoweringState::allocateStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a592045324d9ab5a208ce36932f3a7c2d">llvm::SIMachineFunctionInfo::allocateVGPRSpillToAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a122720c6c9f5c3fd65169c6d123d2516">buildEpilogRestore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a4e6b353116922112b1b470ce15adb2fd">buildPrologSpill</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#af01033da46e9a33a66573433a81eaad0">computeFreeStackSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a56db9c3cbc621caf7d84f6982f095392">determineSVEStackObjectOffsets</a>, <a href="/web-llvm/docs/api/structs/llvm/arcregisterinfo/#aaf69a259c2c354f83b367585a37bb14d">llvm::ARCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aac8f5d5c66c21056b3144508e8142639">llvm::ARCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="#a66046fdf8661d5276f951337b0cf892d">estimateStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering/#a7c45383cd53ee8ccfeceafc1daed18d3">llvm::MipsFrameLowering::estimateStackSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a08517d2919480dbf25deba8c5306dd39">foldInlineAsmMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6a733ae5364b0de2225af33223f383a5">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a7cfc0ecfec922ebf19bd023f3b675604">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a217c3db3b137e03bd6ade29bb9999ac9">llvm::AArch64FunctionInfo::getCalleeSavedStackSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a1d4b2effd4fbebb40f0d10cb1ed6c577">getFrameIndexMMO</a>, <a href="/web-llvm/docs/api/classes/llvm/r600framelowering/#a7829220a3eab94d3ec786598ab48da83">llvm::R600FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a3f25c09896b601cbe577cc8a814ac748">llvm::MipsInstrInfo::GetMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a1ae53e898b0dee354e1b6e38d302d071">getOrCreateFixedStackObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a7d9494014ff9dbd992928542dee2e477">isConsecutiveLSLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a3e7bad47b8a800607f8e872e3305f878">llvm::SystemZInstrInfo::isStackSlotCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aef098c9f09dc6ea1e32e64d79091a237">llvm::AArch64InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#ad96e959009cbe91d2814bcdfe4fcd51c">llvm::ARCInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a81fe15801547c074b2c33034c00df067">llvm::ARMBaseInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#aa3221ba2a1b01836c1f02c48d2bd2c4e">llvm::AVRInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad3b3220844622daec97aeb14080a66e4">llvm::HexagonInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#afa83048a6e09247f7f6310ffc0681909">llvm::LoongArchInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a239b76db482ddf927605d2df0345f32c">llvm::M68kInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#a3a04d16772e68de8d911d305070f0e0b">llvm::MSP430InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab4a6a57aa863f068433ba056f15c61b1">llvm::RISCVInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a38be8eeeb68d45e0a914cd8f3237ce83">llvm::SparcInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a1eeb397bafd16951ce8898c83f21c5e4">llvm::Thumb1InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a6d4af3948133ad97770947f7d1242561">llvm::VEInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a00e20eba7b1f0d10d7094c146a00a705">llvm::X86InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a541a292af69ae4be75a66b7994e89abb">llvm::XCoreInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a4f5aa6feffe52b80166f0d252cf354cb">llvm::PPCInstrInfo::loadRegFromStackSlotNoUpd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#ab268a162e6da94b8012d8366563ae9f7">MatchingStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a313bdf934f1f8454b6800d8d997801d2">MatchingStackOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a897d513f6255e5eeaba5074ca4095230">llvm::HexagonFrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a420e13f932ebcdd50a90e807d5e5674f">llvm::SystemZELFFrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#adee8390bf727c3086a7b864de6c6913e">llvm::X86FrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#ae380dabb206877f151fa2c3c39f9585a">llvm::RISCVFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ae45b5d3065cf62a7eac0053f27cb8103">llvm::SystemZELFFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#acd8f0ca7af8321ea32072c40fe93619e">llvm::SystemZXPLINKFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/machinesanitizerbinarymetadata/#a937f0d635f382c2a5befe696ddd43770">anonymous{SanitizerBinaryMetadata.cpp}::MachineSanitizerBinaryMetadata::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/avrframeanalyzer/#a854b8ec11315be5c7771d9aca8762e51">llvm::AVRFrameAnalyzer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a23de116e7a75d0aaae35a539d6a6118e">scavengeStackSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a01be2a14188ac612c910c9043ae037e1">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#afb9b4b3ff97e290070f42849b51a13a5">spillIncomingStatepointValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aeba4e73d60d1b4cedc120d06114c0620">llvm::AArch64InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a687fecaf502080080ba5069e6b211a65">llvm::ARCInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a8a7868df2562a3b48d08d24c9db87b98">llvm::ARMBaseInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a90829bf41a9e8e4c4e4ad59eab490719">llvm::AVRInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a9644f3506784b55b500d2f73f94d79e0">llvm::HexagonInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#aed611129b85082f7e6459907b50a8cd5">llvm::LoongArchInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acc65122fa06b8871a427abbbd700b22a">llvm::M68kInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#ae215353a37be6d2f533a4858bd96be74">llvm::MSP430InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a23e6d76b3b763236213c20fdd08718ed">llvm::RISCVInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#abc124725b4afa4a9d9449c6e2cfb3d73">llvm::SparcInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a952f199f7cb8a257a40193bcd67a976d">llvm::Thumb1InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3e0753735e274deee756f4b8961b88b2">llvm::Thumb2InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a2132749e515b00c60255bdb4acfba223">llvm::VEInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aa424b646f1bed0832f4eb126081e6fe5">llvm::X86InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a915259afe54d2619524ed03c9c273c57">llvm::XCoreInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a97de15cd29255b90b2ce510e967340bf">llvm::PPCInstrInfo::storeRegToStackSlotNoUpd</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#ae8ee5af33e0f1b85755cf5a1e4951793">tryToElideArgumentCopy</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a026d7ee38d907cccbeb812b0747f957c">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyStackProtector</a>.</p>

</div>
</div>

### getObjectSSPLayout() {#a0e63dce45e27f16d0fe42d473c9598c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SSPLayoutKind llvm::MachineFrameInfo::getObjectSSPLayout (int ObjectIdx)</td>
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



<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getOffsetAdjustment() {#a60679e554cbf7092c8a0ae6c5db2661a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MachineFrameInfo::getOffsetAdjustment ()</td>
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

<p>Return the correction for frame offsets.</p>

<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a0f71a92dc6f774b7059d9490a29d52ad">llvm::LoongArchFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a46adda2adcecd14a8c1ef28661069805">llvm::MipsSEFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a> and <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#af88a8f2328543f94aea3ba85d954fafa">llvm::TargetFrameLowering::getFrameIndexReference</a>.</p>

</div>
</div>

### getPristineRegs() {#aa42c3828ac3f788f2ef3ff6fa46e4926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector MachineFrameInfo::getPristineRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a set of physical registers that are pristine.</p>


<p>Pristine registers hold a value that is useless to the current function, but that must be preserved - they are callee saved registers that are not saved.</p>


<p>Before the PrologueEpilogueInserter has placed the CSR spill code, this method always returns an empty set.</p>


<p>Declaration at line 839 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp">MachineFrameInfo.cpp</a>.</p>


<p>References <a href="#aad474502cac7b22b83e74de089f8c81d">getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a81504f733d0491a446a16ef1ba0a5c2a">isCalleeSavedInfoValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a168122d6ac4ed2a8b722e01b592ad289">llvm::BitVector::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a51c3d43bee1dec655ecaec65afc94c82">llvm::ARMFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker/#abd095bb58a0243946704d20d3559d420">llvm::AggressiveAntiDepBreaker::StartBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#adb4573a84f25279673e3906914132a39">llvm::CriticalAntiDepBreaker::StartBlock</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#afa06aa56938cd078f6e40733f5406dab">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineBasicBlockBefore</a>.</p>

</div>
</div>

### getRestorePoint() {#a5b92dc4f379813174c0942c8d1d8e241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::MachineFrameInfo::getRestorePoint ()</td>
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



<p>Definition at line 825 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a5647b98ce7f0b4ad6fedc71a993e9979">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::calculateSaveRestoreBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3f176ff8abd35fbe2f043c22d088302e">llvm::PPCFrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#ab462c5bbf745633740ccfb2920040000">updateLiveness</a>.</p>

</div>
</div>

### getSavePoint() {#af5ba92668c96fb23e8d5fa9add3daab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::MachineFrameInfo::getSavePoint ()</td>
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



<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a5647b98ce7f0b4ad6fedc71a993e9979">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::calculateSaveRestoreBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3f176ff8abd35fbe2f043c22d088302e">llvm::PPCFrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#ab462c5bbf745633740ccfb2920040000">updateLiveness</a>.</p>

</div>
</div>

### getStackID() {#ad718aae0ce2a188fa35cb2781024ffc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MachineFrameInfo::getStackID (int ObjectIdx)</td>
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




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>StackID</p></dd>
</dl>


<p>Definition at line 750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a96067c42b682fd10d4696fb1c0091592">allSGPRSpillsAreDead</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aee68072e1038a895a2998d78395db856">llvm::SIRegisterInfo::buildVGPRSpillLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#af01033da46e9a33a66573433a81eaad0">computeFreeStackSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a6447282533aad4f054c9bfcf8df8028f">llvm::SystemZXPLINKFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a56db9c3cbc621caf7d84f6982f095392">determineSVEStackObjectOffsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a035d6de6da7186bb6a0a180c617c8a83">emitCalleeSavedRestores</a>, <a href="#a66046fdf8661d5276f951337b0cf892d">estimateStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a217c3db3b137e03bd6ade29bb9999ac9">llvm::AArch64FunctionInfo::getCalleeSavedStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ae8c531c36381ca6a666ca73f740335cb">llvm::WebAssemblyFrameLowering::getLocalForStackObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a857ca8ebd4e64059aa8774f14445e414">getRVVCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#af59f353dd1adb78d8e0187803c5edb83">getScavSlotsNumForRVV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ae435b1b5b5ed85a029acf53fe157d437">getUnmanagedCSI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#ae380dabb206877f151fa2c3c39f9585a">llvm::RISCVFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a97509f8c54ec54df287f62902fd2c472">llvm::SIMachineFunctionInfo::removeDeadFrameIndices</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#aea20ccef4ad810aac64b6a0ac6571d3b">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a0e48eed8c71f1e31ececec593aa98908">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexedSVE</a>, <a href="#af4c34648ca4596767ff0c3409fc3f2d9">setObjectAlignment</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/slotdata/#a5366dad88d5f63bc1c27ffc54d351201">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::SlotData::SlotData</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a026d7ee38d907cccbeb812b0747f957c">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyStackProtector</a>.</p>

</div>
</div>

### getStackProtectorIndex() {#a5ee88eb786413b2cf541122aa749392c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MachineFrameInfo::getStackProtectorIndex ()</td>
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

<p>Return the index for the stack protector object.</p>

<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a56db9c3cbc621caf7d84f6982f095392">determineSVEStackObjectOffsets</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a69dafe1f45af554b1b82bcde2503a3c4">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::emitStackFrameLayoutRemarks</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/slotdata/#a5366dad88d5f63bc1c27ffc54d351201">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::SlotData::SlotData</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a026d7ee38d907cccbeb812b0747f957c">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyStackProtector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a8c767945c41931c388e691c9ef5e5cd2">WindowsRequiresStackProbe</a>.</p>

</div>
</div>

### getStackSize() {#a14c39a24bf6ebbe339ae8a453c7fdd11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MachineFrameInfo::getStackSize ()</td>
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

<p>Return the number of bytes that must be allocated to hold all of the fixed size frame objects.</p>


<p>This is only valid after Prolog/Epilog code insertion has finalized the stack frame layout.</p>


<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac2efa5f4dacdde70f912da43c1f8ffcf">llvm::PPCFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a6447282533aad4f054c9bfcf8df8028f">llvm::SystemZXPLINKFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aa24149b04083669797095c1473b14f3a">llvm::AArch64RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/arcregisterinfo/#aaf69a259c2c354f83b367585a37bb14d">llvm::ARCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo/#a5846a629f1d7d7cc33ecf2a63319e14a">llvm::AVRRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/lanairegisterinfo/#acd4d1d9eb28b9bca2ca401487bdf529e">llvm::LanaiRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a396c2d76e8e7c09d638a32cab9ea94bf">llvm::MipsRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430registerinfo/#a1ae0b9564ca66a61628084c4bb858ea8">llvm::MSP430RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a91da910cd583aea849621cbf8147fe28">llvm::PPCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoreregisterinfo/#a135008911313eaf0a75d1f7a960fe915">llvm::XCoreRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaregisterinfo/#a6411a92c3a3ac8af31ab80b05b0b24fe">llvm::XtensaRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a702408ee868bae14b0de2b8a28c8058d">llvm::SIFrameLowering::emitEntryFunctionPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aac8f5d5c66c21056b3144508e8142639">llvm::ARCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a51c3d43bee1dec655ecaec65afc94c82">llvm::ARMFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a487d00503c99000990bb90458b08702c">llvm::AVRFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a586e88416ae37cf1579986caeb97a9fa">llvm::LoongArchFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a27812f7473acb8b3398abc5a297ea082">llvm::M68kFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#a21570eb2eb8c108f04a8cd089489d34f">llvm::Mips16FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#aeb6b320000ce736d5ac68e606fcc3519">llvm::MipsSEFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a3a9df23d95cdadc6a77b12dc3377a331">llvm::MSP430FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ace1de8acc8ac15962f04832273df87b1">llvm::SIFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a675f8b6bd946c7c1a04bee42ff2a0598">llvm::SparcFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a6289c3b215e791396217e90177ad28a5">llvm::Thumb1FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#ab1be113dfec8a96458235eea8ac0797f">llvm::VEFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#adbe9a36b5d064d3fe4667e4c1b47af85">llvm::WebAssemblyFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a756acce5a5adef291dc50593ce6d56a4">llvm::XCoreFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a0461f7f7e4e1f408963beca04c51c6d4">llvm::XtensaFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a5a25bb817d51790574c718d2a39bfafc">llvm::SystemZAsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a2b9b845d1b6461c8c99fbeed9984f757">llvm::AVRFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiframelowering/#a1cc86e82857e8ff7bceddf8838830577">llvm::LanaiFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#affe78904b64f71286945c438ebf31bc7">llvm::Mips16FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a921a457b786497c2309b9f63abd9c951">llvm::MSP430FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#af5c6e03e6ac66b0eb9389a951593985b">llvm::SIFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a198d0eb07bb9ae2ff6dba28a16264342">llvm::SparcFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#ab3c8272ea0652d9ab75b889488f2717f">llvm::VEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a9985b2dd892ea5c7888c199fc8b3b9e7">llvm::AsmPrinter::emitStackSizeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aaf0263a348d44245abd76df0d07af9ea">llvm::AsmPrinter::emitStackUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aca49f4bdff5eb8f32e4b650f33d6f98e">llvm::X86FrameLowering::getDwarfFrameBase</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a3290bcbb58f1e5d0c6006373c1e55053">llvm::LoongArchFrameLowering::getFirstSPAdjustAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a75d48c8917ed2a09d85cf46fcda67002">llvm::HexagonFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a0f71a92dc6f774b7059d9490a29d52ad">llvm::LoongArchFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a7a7d0ca18a51d0d4829fb467deed15e9">llvm::M68kFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a46adda2adcecd14a8c1ef28661069805">llvm::MipsSEFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#ac3af49ca4a1c47f7c01abaae4e8092bf">llvm::SparcFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#af88a8f2328543f94aea3ba85d954fafa">llvm::TargetFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#a77083d402f6deba15f8ccf39ffff370e">llvm::VEFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a84fbe17f451c957c67de546c98f2b79b">llvm::X86FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afb20caf4eb8695705452f25d78a18a06">llvm::X86FrameLowering::getFrameIndexReferencePreferSP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a72a70493afafbf4374226300289c04b9">llvm::AArch64InstrInfo::getOutliningTypeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abffddc65a79eca0830b7dd232ff74dc5">llvm::ARMBaseInstrInfo::getOutliningTypeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#afc745007e032dc7daac0eb03fbd9f0f1">llvm::RISCVFrameLowering::getStackSizeWithRVVPadding</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a484c3893b6ffdebaa29296c58fc366a1">llvm::HexagonFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3fdbbb3f732425b06a8a7526b1e49e7a">llvm::PPCFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a9011fd4dec97b74c665033f7a42d485a">llvm::SIFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ac345b7d27b1e29825f2b86adbfdd0cd5">llvm::WebAssemblyFrameLowering::hasFPImpl</a>, <a href="#a00d2c6aab11836fcd2116ef07924253e">needsSplitStackProlog</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a355a1f30be913f4dc74c51af277fd74a">llvm::PPCRegisterInfo::prepareDynamicAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a230b654eb7319d9e7a6d9d62afa2d5f8">llvm::ARCFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a454cc7f0c0075624df31b3ae121c3506">llvm::PPCRegisterInfo::requiresFrameIndexScavenging</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#ab4bf72d745b01eea298759754c9efeba">llvm::ARMFrameLowering::ResolveFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/gcmachinecodeanalysis/#a82b0862f6017d073489a4971d43ecf3a">anonymous{GCRootLowering.cpp}::GCMachineCodeAnalysis::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoreframetoargsoffsetelim-cpp-/xcoreftaoelim/#a2ef5edc1bc3d0736ef24263d9e6b0d69">anonymous{XCoreFrameToArgsOffsetElim.cpp}::XCoreFTAOElim::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a026d7ee38d907cccbeb812b0747f957c">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyStackProtector</a>.</p>

</div>
</div>

### getUnsafeStackSize() {#ac08fc384e90a861a5934987272675ecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MachineFrameInfo::getUnsafeStackSize ()</td>
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



<p>Definition at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a9985b2dd892ea5c7888c199fc8b3b9e7">llvm::AsmPrinter::emitStackSizeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aaf0263a348d44245abd76df0d07af9ea">llvm::AsmPrinter::emitStackUsage</a> and <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>.</p>

</div>
</div>

### getUseLocalStackAllocationBlock() {#a5990b78705882c9de507550bc81c40cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::getUseLocalStackAllocationBlock ()</td>
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

<p>Get whether the local allocation blob should be allocated together or let PEI allocate the locals in it directly.</p>

<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64stacktaggingprera-cpp/#a64436bd8236dbb5902aa21b3ee02b2e1">isSlotPreAllocated</a>.</p>

</div>
</div>

### hasCalls() {#a2cc8bb867c8949943ca7d88f1db31fde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::hasCalls ()</td>
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

<p>Return true if the current function has any function calls.</p>

<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#af79b8bdd9826c6c96dd238e32520fc94">llvm::ARCFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ace3b0eb52be3988997a7f6e4a5b59aab">llvm::PPCFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a81242a6cd5fbec123c8ed582bab0f26c">llvm::AArch64FrameLowering::canUseRedZone</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a058c4d3a1147ae3ec1098c3031fe32cb">llvm::CSKYFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a9eb6f3247260b906218068229b8d5b67">llvm::SystemZELFFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ac5bebf636fd9c3f6c9b7484f3244fb67">llvm::SIFrameLowering::determineCalleeSavesSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a0ad5cb616fdce8d90db0927dbdf0533c">llvm::SIFrameLowering::determinePrologEpilogSGPRSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#aad0fc1de8197ddf2c49346c5d92a2bec">llvm::TargetOptions::DisableFramePointerElim</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a702408ee868bae14b0de2b8a28c8058d">llvm::SIFrameLowering::emitEntryFunctionPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aac8f5d5c66c21056b3144508e8142639">llvm::ARCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a84fbe17f451c957c67de546c98f2b79b">llvm::X86FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a484c3893b6ffdebaa29296c58fc366a1">llvm::HexagonFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a9011fd4dec97b74c665033f7a42d485a">llvm::SIFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#ab7e47514d5ce433432975dac4df8e7e7">isXPLeafCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#a3b2bec8faee9b97ef8c297fb0cedabdb">llvm::WebAssemblyFrameLowering::needsPrologForEH</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a5eafea62423808eaf1bec18900ec929e">llvm::SIRegisterInfo::requiresRegisterScavenging</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a572f7d3a80aeaedcf8eec0b7872e6c89">llvm::SIFrameLowering::requiresStackPointerReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a049dfdf656884a9d492cb2bc7a664dbf">reservePrivateMemoryRegs</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfopropagate-cpp-/regusageinfopropagation/#a69819f2acbe4f8a2cd38c871d3c9b96f">anonymous{RegUsageInfoPropagate.cpp}::RegUsageInfoPropagation::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a024479869943dfba001bb5701d62a243">llvm::SIMachineFunctionInfo::usesAGPRs</a>.</p>

</div>
</div>

### hasCopyImplyingStackAdjustment() {#ac901643b9a98a52b1c323b79f28b8dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::hasCopyImplyingStackAdjustment ()</td>
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

<p>Returns true if the function contains operations which will lower down to instructions which manipulate the stack pointer.</p>

<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a493d9a8215b5ec117b32762217d66f80">llvm::X86FrameLowering::hasFPImpl</a>.</p>

</div>
</div>

### hasFunctionContextIndex() {#ae2c878d38ca7ead514ef744f46e05779}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::hasFunctionContextIndex ()</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>.</p>

</div>
</div>

### hasMustTailInVarArgFunc() {#a7819a781e436c677ed1613c7739ee53e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::hasMustTailInVarArgFunc ()</td>
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

<p>Returns true if the function is variadic and contains a musttail call.</p>

<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a133ddcbd001fd6de4f055542a6a95595">handleMustTailForwardedRegisters</a>.</p>

</div>
</div>

### hasOpaqueSPAdjustment() {#a51773b6c05f392988bf6395ccd1788ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::hasOpaqueSPAdjustment ()</td>
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

<p>Returns true if the function contains opaque dynamic stack adjustments.</p>

<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#a73e723a22ad556552ca99f7e7a90a780">llvm::RegsForValue::AddInlineAsmOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kregisterinfo-cpp/#af9f0dd8cdc378cede742f2ce618fb45f">CantUseSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86registerinfo-cpp/#af9f0dd8cdc378cede742f2ce618fb45f">CantUseSP</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a493d9a8215b5ec117b32762217d66f80">llvm::X86FrameLowering::hasFPImpl</a>.</p>

</div>
</div>

### hasPatchPoint() {#a503a8cb169aa29ac907c218692087db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::hasPatchPoint ()</td>
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

<p>This method may be called any time after instruction selection is complete to determine if there is a call to builtin @llvm.experimental.patchpoint.</p>

<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a5c1f72ef80dbbf61d84dc5373b18b598">frameTriviallyRequiresSP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a52626eda66484fc0cadb0d956483888b">llvm::AArch64FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ac345b7d27b1e29825f2b86adbfdd0cd5">llvm::WebAssemblyFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a493d9a8215b5ec117b32762217d66f80">llvm::X86FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a11b74a0fb5ceb4340d1d7a6f809e0a28">llvm::PPCFrameLowering::needsFP</a> and <a href="/web-llvm/docs/api/classes/anonymous-stackmaplivenessanalysis-cpp-/stackmapliveness/#ab6f8a5390b954d2509fa4c304344eb53">anonymous{StackMapLivenessAnalysis.cpp}::StackMapLiveness::runOnMachineFunction</a>.</p>

</div>
</div>

### hasStackMap() {#aa7d9e2f26e4c8b32f51c455b220ce13c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::hasStackMap ()</td>
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

<p>This method may be called any time after instruction selection is complete to determine if there is a call to builtin @llvm.experimental.stackmap.</p>

<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a5c1f72ef80dbbf61d84dc5373b18b598">frameTriviallyRequiresSP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a52626eda66484fc0cadb0d956483888b">llvm::AArch64FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ac345b7d27b1e29825f2b86adbfdd0cd5">llvm::WebAssemblyFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a493d9a8215b5ec117b32762217d66f80">llvm::X86FrameLowering::hasFPImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a11b74a0fb5ceb4340d1d7a6f809e0a28">llvm::PPCFrameLowering::needsFP</a>.</p>

</div>
</div>

### hasStackObjects() {#acb35f7f6a131a64e636d936246ebd37f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::hasStackObjects ()</td>
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

<p>Return true if there are any stack objects in this function.</p>

<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxframelowering/#aad707aff5fcbdc8180deb9e6695f0c32">llvm::NVPTXFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a69dafe1f45af554b1b82bcde2503a3c4">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::emitStackFrameLayoutRemarks</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ae2302943b6df3e0fcd2007a2f06e3c08">llvm::M68kFrameLowering::needsFrameIndexResolution</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6add5d4c2104f4ae4794984d3c256834">llvm::TargetFrameLowering::needsFrameIndexResolution</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a0d66887ade3ca46870e0921376f86fd1">llvm::X86FrameLowering::needsFrameIndexResolution</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a230b654eb7319d9e7a6d9d62afa2d5f8">llvm::ARCFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a29ab56a48816c54d3db51d4724304663">llvm::SIRegisterInfo::requiresFrameIndexReplacementScavenging</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a5eafea62423808eaf1bec18900ec929e">llvm::SIRegisterInfo::requiresRegisterScavenging</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a049dfdf656884a9d492cb2bc7a664dbf">reservePrivateMemoryRegs</a> and <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#aea20ccef4ad810aac64b6a0ac6571d3b">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::run</a>.</p>

</div>
</div>

### hasStackProtectorIndex() {#ac7c993678733273ea9d16db7ff87b2c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::hasStackProtectorIndex ()</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a56db9c3cbc621caf7d84f6982f095392">determineSVEStackObjectOffsets</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/slotdata/#a5366dad88d5f63bc1c27ffc54d351201">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::SlotData::SlotData</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a026d7ee38d907cccbeb812b0747f957c">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyStackProtector</a>.</p>

</div>
</div>

### hasTailCall() {#a763b7a1e7127b495f396b30f0d9c95f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::hasTailCall ()</td>
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

<p>Returns true if the function contains a tail call.</p>

<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a1e0aa89e6577318443a666796f159a30">llvm::SIMachineFunctionInfo::allocateWWMSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a7865e2cad3030c3c48b64c9cf1243d46">llvm::SIFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a26a2097fa7f267ce29202d37048c4a1c">getUnderlyingObjectsForInstr</a>, <a href="#a00d2c6aab11836fcd2116ef07924253e">needsSplitStackProlog</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3f176ff8abd35fbe2f043c22d088302e">llvm::PPCFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfopropagate-cpp-/regusageinfopropagation/#a69819f2acbe4f8a2cd38c871d3c9b96f">anonymous{RegUsageInfoPropagate.cpp}::RegUsageInfoPropagation::run</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a96dd72f1aba111c3927d4c600a643618">llvm::RISCVMachineFunctionInfo::useSaveRestoreLibCalls</a>.</p>

</div>
</div>

### hasVarSizedObjects() {#a0509430713d587eba74220a8375948a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::hasVarSizedObjects ()</td>
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

<p>This method may be called any time after instruction selection is complete to determine if the stack frame for this function contains any variable sized objects.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac65455efc149d81b4d1418acae7596b3">llvm::PPCFrameLowering::addScavengingSpillSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#adf86b81af5da74aea6a11c36eadf41be">llvm::AArch64RegisterInfo::cannotEliminateFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#aa0eb9ad617a055468d105965502662c5">llvm::ARMBaseRegisterInfo::cannotEliminateFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a5a1aad4b6babbb473d1b342d32125d14">llvm::ARMFrameLowering::canSimplifyCallFramePseudos</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kregisterinfo-cpp/#af9f0dd8cdc378cede742f2ce618fb45f">CantUseSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86registerinfo-cpp/#af9f0dd8cdc378cede742f2ce618fb45f">CantUseSP</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a27b8c40891bfea8db2ad3b9fa25cba0f">llvm::MipsSEFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac2efa5f4dacdde70f912da43c1f8ffcf">llvm::PPCFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a27a80b2fc0f8820ecab9d99312bb4607">llvm::AArch64FrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aa24149b04083669797095c1473b14f3a">llvm::AArch64RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a6f318a4b1d38e66b324c0748304e60de">llvm::ARMBaseRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a8fbe3f2774ccaaf41bd80a092a9f73e5">llvm::ThumbRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a487d00503c99000990bb90458b08702c">llvm::AVRFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a586e88416ae37cf1579986caeb97a9fa">llvm::LoongArchFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a27812f7473acb8b3398abc5a297ea082">llvm::M68kFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a3a9df23d95cdadc6a77b12dc3377a331">llvm::MSP430FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a5a25bb817d51790574c718d2a39bfafc">llvm::SystemZAsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiframelowering/#a1cc86e82857e8ff7bceddf8838830577">llvm::LanaiFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a9985b2dd892ea5c7888c199fc8b3b9e7">llvm::AsmPrinter::emitStackSizeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aaf0263a348d44245abd76df0d07af9ea">llvm::AsmPrinter::emitStackUsage</a>, <a href="#a66046fdf8661d5276f951337b0cf892d">estimateStackSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a5c1f72ef80dbbf61d84dc5373b18b598">frameTriviallyRequiresSP</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a75d48c8917ed2a09d85cf46fcda67002">llvm::HexagonFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ad6591055c1ba6d0a1033510f7a4eab65">llvm::AArch64FrameLowering::getFrameIndexReferencePreferSP</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a6963ee4846a440960af3393b33d4e8b0">llvm::R600InstrInfo::getIndirectIndexEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#aada6bb4af36a2736480f0c51fced2d58">llvm::ARMSubtarget::getPushPopSplitVariation</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#ab03f0084e766f3636a1eb7832061fd94">llvm::MipsRegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#acafe750c425c834b596416c311715d8c">llvm::AArch64RegisterInfo::hasBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a0e2ca33d941092c36d88209114f6fa8f">llvm::ARMBaseRegisterInfo::hasBasePointer</a>, <a href="/web-llvm/docs/api/structs/llvm/lanairegisterinfo/#a40e518a82dbb0c60127edda3a20c5e0e">llvm::LanaiRegisterInfo::hasBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a9311a5f8e1b024ff1f6c65341fc3cdfc">llvm::CSKYFrameLowering::hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af5822132e0c77a924c92cd4bbedf9c97">llvm::LoongArchFrameLowering::hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering/#a454a61d9ff61d6d4402ce57c16f40fc3">llvm::MipsFrameLowering::hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a38fe3f67034841400e749f75768348a2">llvm::RISCVFrameLowering::hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#a4762e4f2c447b020abc88c3bd501c407">llvm::VEFrameLowering::hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a52626eda66484fc0cadb0d956483888b">llvm::AArch64FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a3ca8ff16a3bd8d5f7c682180151eb3fc">llvm::ARCFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a895b02ce6ba256348e2eef839e1ef780">llvm::ARMFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#ac6a1476342ef948ac5c1d67d0ea7f795">llvm::AVRFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a57e521638750a8eafb3e5b985cad6cb2">llvm::CSKYFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a484c3893b6ffdebaa29296c58fc366a1">llvm::HexagonFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#adae83dd896dd68667b344defbc9c5381">llvm::LoongArchFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a0467fb31b542da4b9672b69ae002cf97">llvm::M68kFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering/#acc03bc4b3fe668894a31738a4f03269b">llvm::MipsFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a1b2778e918ea09d5b0f6e0d4ec0f3bc5">llvm::MSP430FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a6257e7a03156ea3018b555f0aff4b2">llvm::RISCVFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#abc1f60525acaf9f05557ea0d4bc1d339">llvm::SparcFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a639478d440d115bb94fd83bf9054da98">llvm::SystemZELFFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a845c852c1b1e54f803079f5b52a5319c">llvm::SystemZXPLINKFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#aa1d1f569ffb5db8f2cbb0bc8fdf7515c">llvm::VEFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ac345b7d27b1e29825f2b86adbfdd0cd5">llvm::WebAssemblyFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a493d9a8215b5ec117b32762217d66f80">llvm::X86FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#ada8a1c1bcf75dee1d45143d3b8500d16">llvm::XCoreFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a130ce842392b2b6a8051ccfdf70b3d5a">llvm::XtensaFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a6d15a3346f663d13e5b9061da4d56ddc">llvm::AArch64FrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a7d1c91b20625d31982210d6fc381104d">llvm::ARMFrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a779aa3690fe35425d031e2d1826c8c8d">llvm::AVRFrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a36d78f4110d8b48e727f620fbeb60e05">llvm::CSKYFrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#aefc7a2b4a075a4e455a257da734d4097">llvm::LoongArchFrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a3e5e130e3af325c9671f8d20ce8fa7ad">llvm::M68kFrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#ab242e5924ca5ef32768676a9e81b248f">llvm::Mips16FrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a7e8bd93c19af3e257293630169b1c165">llvm::MipsSEFrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#ac7ab006a473080cd8a645765f3edd500">llvm::MSP430FrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a682ca2f9a07f1d42cf4b7aa0e62fc569">llvm::RISCVFrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#affd012d89ae3f8bcec123c8923269fb4">llvm::SparcFrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#ab6578ac15aab22a10a00e231e45ff9cb">llvm::Thumb1FrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#a6ac032ff4fb3914f8f6f29bc9b8f2cb0">llvm::WebAssemblyFrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6696e7a9f36d7983d3593e5f4a17831f">llvm::X86FrameLowering::hasReservedCallFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#ab7e47514d5ce433432975dac4df8e7e7">isXPLeafCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#adb7726ddd215999f695aec70200b9d01">llvm::HexagonFrameLowering::needsAligna</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a11b74a0fb5ceb4340d1d7a6f809e0a28">llvm::PPCFrameLowering::needsFP</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#ae7508374329448fb4210c15d9cc79ad7">llvm::ARMBaseRegisterInfo::needsFrameBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a8b67fcf985704c812d104989a617a939">llvm::HexagonFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#abcb33f3f153c050bf1a63bcd8223e836">llvm::PPCFrameLowering::replaceFPWithRealFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/gcmachinecodeanalysis/#a82b0862f6017d073489a4971d43ecf3a">anonymous{GCRootLowering.cpp}::GCMachineCodeAnalysis::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ac57730efce0c1f82628bcdeb5ae42ce9">llvm::HexagonDAGToDAGISel::SelectFrameIndex</a>.</p>

</div>
</div>

### hasVAStart() {#ab512cf99651d9d49323b0ac9a25c7f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::hasVAStart ()</td>
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

<p>Returns true if the function calls the llvm.va_start intrinsic.</p>

<p>Definition at line 638 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>.</p>

</div>
</div>

### isAliasedObjectIndex() {#afe20684ee4170df6085d75ef85f0124a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isAliasedObjectIndex (int ObjectIdx)</td>
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

<p>Returns true if the specified index corresponds to an object that might be pointed to by an LLVM IR value.</p>

<p>Definition at line 706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a> and <a href="/web-llvm/docs/api/classes/llvm/fixedstackpseudosourcevalue/#a310c11a3a05119a593927ad66b7aa0b8">llvm::FixedStackPseudoSourceValue::isAliased</a>.</p>

</div>
</div>

### isCalleeSavedInfoValid() {#a81504f733d0491a446a16ef1ba0a5c2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isCalleeSavedInfoValid ()</td>
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

<p>Has the callee saved info been calculated yet?</p>

<p>Definition at line 819 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#ab4fff7ad3de452b1b1d20de5afd986a3">llvm::LiveRegUnits::addLiveOuts</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#ab22bacf399a5964155b56e9be835a6b3">llvm::LivePhysRegs::addLiveOutsNoPristines</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a217c3db3b137e03bd6ade29bb9999ac9">llvm::AArch64FunctionInfo::getCalleeSavedStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a647fbf2c5d5bb2fe4f4b5b9af7e0ab00">llvm::TargetFrameLowering::getCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a72a70493afafbf4374226300289c04b9">llvm::AArch64InstrInfo::getOutliningTypeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abffddc65a79eca0830b7dd232ff74dc5">llvm::ARMBaseInstrInfo::getOutliningTypeImpl</a>, <a href="#aa42c3828ac3f788f2ef3ff6fa46e4926">getPristineRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#acede596c16f946c19dacb339e25ff978">getSVECalleeSaveSlotRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa323e6c0586d706279d7e764fc18d1ba">llvm::recomputeLivenessFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a454cc7f0c0075624df31b3ae121c3506">llvm::PPCRegisterInfo::requiresFrameIndexScavenging</a> and <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2b5bce8095abd7b08536e0e2aa91db54">llvm::ARMFrameLowering::updateLRRestored</a>.</p>

</div>
</div>

### isDeadObjectIndex() {#af5302d38d9a16eee93f13a1579c8773d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isDeadObjectIndex (int ObjectIdx)</td>
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

<p>Returns true if the specified index corresponds to a dead object.</p>

<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a96067c42b682fd10d4696fb1c0091592">allSGPRSpillsAreDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a3a45e8bba1a335538a222c1809626753">allStackObjectsAreDead</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-bpfmipeephole-cpp-/#a6a294b4a511b694d1eb7a6358de71cdd">anonymous{BPFMIPeephole.cpp}::computeMinFixedObjOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/ssplayoutinfo/#a2068b15b4ae5d41ac05efbc9dd9dc48c">llvm::SSPLayoutInfo::copyToMachineFrameInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a56db9c3cbc621caf7d84f6982f095392">determineSVEStackObjectOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a69dafe1f45af554b1b82bcde2503a3c4">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::emitStackFrameLayoutRemarks</a>, <a href="#a66046fdf8661d5276f951337b0cf892d">estimateStackSize</a>, <a href="#adf98860d7f42290f873c82a981eb0ea6">getObjectOffset</a>, <a href="#a3cd29e7edbcaceb5834eaa7d089a5bc4">setObjectOffset</a>, <a href="#a5938f9d0441c7b989d3e08e4dbd81ddf">setObjectSSPLayout</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a026d7ee38d907cccbeb812b0747f957c">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyStackProtector</a>.</p>

</div>
</div>

### isFixedObjectIndex() {#ae6e7e975f7a4e5d535be32068a7c67df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isFixedObjectIndex (int ObjectIdx)</td>
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

<p>Returns true if the specified index corresponds to a fixed stack object.</p>

<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/giseladdressing/#a140cb977d5598588fb9e0079cd1aabf9">llvm::GISelAddressing::aliasIsKnownForLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aee68072e1038a895a2998d78395db856">llvm::SIRegisterInfo::buildVGPRSpillLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/baseindexoffset/#abceb615c6b3c238ec35d098d6925bcea">llvm::BaseIndexOffset::computeAliasing</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a2e94eaf8bec0e356a92dc822d30de554">llvm::X86RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/baseindexoffset/#aef9ef68102c424ca44367d30b16ac65e">llvm::BaseIndexOffset::equalBaseIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/frameindex/#a81e39b7570fe76aab90fa59359af7a41">llvm::yaml::FrameIndex::FrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a75d48c8917ed2a09d85cf46fcda67002">llvm::HexagonFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a0f71a92dc6f774b7059d9490a29d52ad">llvm::LoongArchFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a46adda2adcecd14a8c1ef28661069805">llvm::MipsSEFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#a77083d402f6deba15f8ccf39ffff370e">llvm::VEFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a84fbe17f451c957c67de546c98f2b79b">llvm::X86FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afb20caf4eb8695705452f25d78a18a06">llvm::X86FrameLowering::getFrameIndexReferencePreferSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a00e20eba7b1f0d10d7094c146a00a705">llvm::X86InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8679ab19e5fd70f2011394a4923d7c43">LowerAsSplatVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#ab268a162e6da94b8012d8366563ae9f7">MatchingStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a313bdf934f1f8454b6800d8d997801d2">MatchingStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a294946bd7b49d5ef31f4f42120f75b92">printFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a24b80d6d36821f80675874283190f291">llvm::SIFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a454cc7f0c0075624df31b3ae121c3506">llvm::PPCRegisterInfo::requiresFrameIndexScavenging</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#ab4bf72d745b01eea298759754c9efeba">llvm::ARMFrameLowering::ResolveFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#aea20ccef4ad810aac64b6a0ac6571d3b">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86argumentstackslotrebase-cpp-/x86argumentstackslotpass/#af787e4cab9e64467b9aa0a253171fa88">anonymous{X86ArgumentStackSlotRebase.cpp}::X86ArgumentStackSlotPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/avrframeanalyzer/#a854b8ec11315be5c7771d9aca8762e51">llvm::AVRFrameAnalyzer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#aa5ffc8ad80e12c7f12a3ce994c083691">llvm::HexagonDAGToDAGISel::SelectAddrFI</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a01be2a14188ac612c910c9043ae037e1">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ac6785462ddb955dc6a9a79d592dd9718">shouldClusterFI</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/slotdata/#a5366dad88d5f63bc1c27ffc54d351201">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::SlotData::SlotData</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aa424b646f1bed0832f4eb126081e6fe5">llvm::X86InstrInfo::storeRegToStackSlot</a>.</p>

</div>
</div>

### isFrameAddressTaken() {#a32125253541ab2e7ec5bbe550ecc2d0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isFrameAddressTaken ()</td>
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

<p>This method may be called any time after instruction selection is complete to determine if there is a call to @llvm.frameaddress in this function.</p>

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#adf86b81af5da74aea6a11c36eadf41be">llvm::AArch64RegisterInfo::cannotEliminateFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#aa0eb9ad617a055468d105965502662c5">llvm::ARMBaseRegisterInfo::cannotEliminateFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac2efa5f4dacdde70f912da43c1f8ffcf">llvm::PPCFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a52626eda66484fc0cadb0d956483888b">llvm::AArch64FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a3ca8ff16a3bd8d5f7c682180151eb3fc">llvm::ARCFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a895b02ce6ba256348e2eef839e1ef780">llvm::ARMFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a57e521638750a8eafb3e5b985cad6cb2">llvm::CSKYFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#adae83dd896dd68667b344defbc9c5381">llvm::LoongArchFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a0467fb31b542da4b9672b69ae002cf97">llvm::M68kFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering/#acc03bc4b3fe668894a31738a4f03269b">llvm::MipsFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a1b2778e918ea09d5b0f6e0d4ec0f3bc5">llvm::MSP430FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a6257e7a03156ea3018b555f0aff4b2">llvm::RISCVFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a9011fd4dec97b74c665033f7a42d485a">llvm::SIFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#abc1f60525acaf9f05557ea0d4bc1d339">llvm::SparcFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#aa1d1f569ffb5db8f2cbb0bc8fdf7515c">llvm::VEFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ac345b7d27b1e29825f2b86adbfdd0cd5">llvm::WebAssemblyFrameLowering::hasFPImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a493d9a8215b5ec117b32762217d66f80">llvm::X86FrameLowering::hasFPImpl</a>.</p>

</div>
</div>

### isImmutableObjectIndex() {#a5eab840dac82571e53cc5f1c05643e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isImmutableObjectIndex (int ObjectIdx)</td>
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

<p>Returns true if the specified index corresponds to an immutable object.</p>

<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedstackpseudosourcevalue/#ae6363f984399088a8b068503783f3cf1">llvm::FixedStackPseudoSourceValue::isConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ab671544f7af287b25a5e612f6e919975">llvm::TargetInstrInfo::isReallyTriviallyReMaterializable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a313bdf934f1f8454b6800d8d997801d2">MatchingStackOffset</a>.</p>

</div>
</div>

### isMaxCallFrameSizeComputed() {#a99cdf1b99c0f1b7e1bf2111aa7d2eaa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isMaxCallFrameSizeComputed ()</td>
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



<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="#a4f335273c28b17552a7cfd802f42be2a">getMaxCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#afe522c5b4605ba12fa3167e7959b6645">llvm::ARMBaseRegisterInfo::getRegPressureLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a38fe3f67034841400e749f75768348a2">llvm::RISCVFrameLowering::hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a52626eda66484fc0cadb0d956483888b">llvm::AArch64FrameLowering::hasFPImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a917a79b56742eaac2db61e2a221d3011">llvm::AArch64Subtarget::mirFileLoaded</a>.</p>

</div>
</div>

### isObjectPreAllocated() {#a11d6e0b1aa8f7709f0330318b2cc5f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isObjectPreAllocated (int ObjectIdx)</td>
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

<p>Return true if the object was pre-allocated into the local block.</p>

<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a75d48c8917ed2a09d85cf46fcda67002">llvm::HexagonFrameLowering::getFrameIndexReference</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64stacktaggingprera-cpp/#a64436bd8236dbb5902aa21b3ee02b2e1">isSlotPreAllocated</a>.</p>

</div>
</div>

### isObjectSExt() {#aa42be2b24be8e5c8a5037d4b0ef20855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isObjectSExt (int ObjectIdx)</td>
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



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#ab268a162e6da94b8012d8366563ae9f7">MatchingStackOffset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a313bdf934f1f8454b6800d8d997801d2">MatchingStackOffset</a>.</p>

</div>
</div>

### isObjectZExt() {#a850b4b75082cdacb4c1c692856248d84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isObjectZExt (int ObjectIdx)</td>
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



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#ab268a162e6da94b8012d8366563ae9f7">MatchingStackOffset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a313bdf934f1f8454b6800d8d997801d2">MatchingStackOffset</a>.</p>

</div>
</div>

### isReturnAddressTaken() {#a20fde7903c3d7ad21cc5825bb886e360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isReturnAddressTaken ()</td>
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

<p>This method may be called any time after instruction selection is complete to determine if there is a call to @llvm.returnaddress in this function.</p>

<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#a2eb8fb675dfceaccbf3a2dbdfee2e9a3">llvm::Mips16FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a8eced7de6aa2268fa96f3580b9ef01bf">llvm::MipsSEFrameLowering::spillCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a757685f42fe19ad1375d53c7e5aa95b1">llvm::XtensaFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### isSpillSlotObjectIndex() {#a91b0115deec3489d7e082a4a13f022ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isSpillSlotObjectIndex (int ObjectIdx)</td>
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

<p>Returns true if the specified index corresponds to a spill slot.</p>

<p>Definition at line 737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a592045324d9ab5a208ce36932f3a7c2d">llvm::SIMachineFunctionInfo::allocateVGPRSpillToAGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a54d1bd4ee7e40a15f8d22acca228dbc3">llvm::MachineInstr::getRestoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#acf7a2f3baa7050ba9f95be0c1b71339f">llvm::MachineInstr::getSpillSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a213eed2958a020a3cb8a92627acd4577">getSpillSlotSize</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedstackpseudosourcevalue/#aa8d4b42ebb293145cc783cb738fe13b8">llvm::FixedStackPseudoSourceValue::mayAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/slotdata/#a5366dad88d5f63bc1c27ffc54d351201">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::SlotData::SlotData</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a026d7ee38d907cccbeb812b0747f957c">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyStackProtector</a>.</p>

</div>
</div>

### isStackRealignable() {#ad41610633e45748a267b67f6062e8b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isStackRealignable ()</td>
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



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a242c8591b53ef3b0846119dc1a70df2c">llvm::TargetRegisterInfo::canRealignStack</a>.</p>

</div>
</div>

### isStatepointSpillSlotObjectIndex() {#a7e9c6f5b0faff7f4a53c3c7ab8b2dd07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isStatepointSpillSlotObjectIndex (int ObjectIdx)</td>
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



<p>Definition at line 743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a> and <a href="#a477686b0d65454f32799cb86f406104c">markAsStatepointSpillSlotObjectIndex</a>.</p>

</div>
</div>

### isVariableSizedObjectIndex() {#ab86af583f3ac779bb3f74071d36b5923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::isVariableSizedObjectIndex (int ObjectIdx)</td>
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

<p>Returns true if the specified index corresponds to a variable sized object.</p>

<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a23de116e7a75d0aaae35a539d6a6118e">scavengeStackSlot</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/slotdata/#a5366dad88d5f63bc1c27ffc54d351201">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::SlotData::SlotData</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a026d7ee38d907cccbeb812b0747f957c">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyStackProtector</a>.</p>

</div>
</div>

### mapLocalFrameObject() {#a853b47f34cdca978a18d7120e64bd4a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::mapLocalFrameObject (int ObjectIndex, int64_t Offset)</td>
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

<p>Map a frame index into the local object block.</p>

<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### markAsStatepointSpillSlotObjectIndex() {#a477686b0d65454f32799cb86f406104c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::markAsStatepointSpillSlotObjectIndex (int ObjectIdx)</td>
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



<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7e9c6f5b0faff7f4a53c3c7ab8b2dd07">isStatepointSpillSlotObjectIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a4841be2489ba10321338a1874b53f249">llvm::StatepointLoweringState::allocateStackSlot</a>.</p>

</div>
</div>

### needsSplitStackProlog() {#a00d2c6aab11836fcd2116ef07924253e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::needsSplitStackProlog ()</td>
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

<p>Return true if this function requires a split stack prolog, even if it uses no stack space.</p>


<p>This is only meaningful for functions where <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab499fb31e894a900402d0871eee39b75">MachineFunction::shouldSplitStack()</a> returns true.</p>


<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>References <a href="#a14c39a24bf6ebbe339ae8a453c7fdd11">getStackSize</a> and <a href="#a763b7a1e7127b495f396b30f0d9c95f1">hasTailCall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>.</p>

</div>
</div>

### print() {#ab49a74c3c0e9f35a453eb0db340424e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineFrameInfo::print (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used by the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> printer to print information about stack objects.</p>


<p>Implemented in <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>Declaration at line 843 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp">MachineFrameInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ac83b44e69c9f9f4f9d60be2d72f4a5df">llvm::TargetSubtargetInfo::getFrameLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6521d4d5560c03b2e6490883558b882c">llvm::TargetFrameLowering::getOffsetOfLocalArea</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#ac42b489f21274bae5d397b8ae8ddd0cf">dump</a>.</p>

</div>
</div>

### RemoveStackObject() {#ab356eaffcc04362671e727900a65ac52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::RemoveStackObject (int ObjectIdx)</td>
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

<p>Remove or mark dead a statically sized stack object.</p>

<p>Definition at line 795 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a2ed887f0677d391bc6f9d7e77b761695">llvm::AArch64TargetLowering::EmitInitTPIDR2Object</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a233876a8dfa07f6566cbaa28f64d6e6f">getVGPRSpillLaneOrTempRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a97509f8c54ec54df287f62902fd2c472">llvm::SIMachineFunctionInfo::removeDeadFrameIndices</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#ae8ee5af33e0f1b85755cf5a1e4951793">tryToElideArgumentCopy</a>.</p>

</div>
</div>

### setAdjustsStack() {#a14ca8f1aa1c62b860504b766ad3b15f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setAdjustsStack (bool V)</td>
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



<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a33c0ea764b5da70fb2f5263babf1e5ae">llvm::HexagonTargetLowering::GetDynamicTLSAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25a5e94166cf78354826b46e402ebcd9">LowerINTRINSIC_W_CHAIN</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/finalizeisel-cpp/#a6395b072c4fb781dca4789de8aba1f55">runImpl</a>.</p>

</div>
</div>

### setCalleeSavedInfo() {#ab3f912e64e60536d8369f1414b7ef380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setCalleeSavedInfo (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; CSI)</td>
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

<p>Used by prolog/epilog inserter to set the function's callee saved information.</p>

<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#abde55543f0bbb31306a6cd2af297fe9f">assignCalleeSavedSpillSlots</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### setCalleeSavedInfoValid() {#a7e65d5ed1e6c20323a0d723c43a9f264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setCalleeSavedInfoValid (bool v)</td>
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



<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a> and <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a27a647930b9f60f83868035dcd46fca8">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::spillCalleeSavedRegs</a>.</p>

</div>
</div>

### setCVBytesOfCalleeSavedRegisters() {#a5ed62fb6fd245cb4efd8ea1bb4d56856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setCVBytesOfCalleeSavedRegisters (unsigned S)</td>
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



<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### setFrameAddressIsTaken() {#a4b9a38005d95189db3246e0e4ec6088d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setFrameAddressIsTaken (bool T)</td>
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



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a13f1c4a0ad3bb43fd704953f000211b9">getFRAMEADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a01abd6ee65d18598e642413f18d92c46">llvm::HexagonTargetLowering::LowerFRAMEADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a89766efe92cf27e505a5df2023c31fc3">llvm::LanaiTargetLowering::LowerFRAMEADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a805ffe0d00d785307d8ed9e740390900">llvm::MSP430TargetLowering::LowerFRAMEADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#aa5d558f15e85ff1bdd92f481212ed368">lowerFRAMEADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25a5e94166cf78354826b46e402ebcd9">LowerINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#ac69a3f91240dad866f77cfe6d22ad277">LowerVASTART</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#adec44526647f646a3803627881ed611e">llvm::VETargetLowering::lowerVASTART</a>.</p>

</div>
</div>

### setFunctionContextIndex() {#afe5772922837eb92e41c2d397809c9eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setFunctionContextIndex (int I)</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### setHasCalls() {#a5bb88f5f9d77d753e87c256950f16955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setHasCalls (bool V)</td>
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



<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a145b3f6dbbafb7b1e7644c3c90fdaf3f">GetTLSADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ab44a5ddbc927f9b63731bf050dee8048">llvm::SparcTargetLowering::LowerGlobalTLSAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#afe0e23691695d8248375255976aa5aaf">llvm::VETargetLowering::lowerToTLSGeneralDynamicModel</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a8c1423d81607a5548a57bf11a3ab447c">llvm::SparcTargetLowering::makeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a>.</p>

</div>
</div>

### setHasCopyImplyingStackAdjustment() {#ab445176256051725bc6d3e543af5029a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setHasCopyImplyingStackAdjustment (bool B)</td>
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



<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25a5e94166cf78354826b46e402ebcd9">LowerINTRINSIC_W_CHAIN</a>.</p>

</div>
</div>

### setHasMustTailInVarArgFunc() {#aef2320fad6df35f6fca25cd93720da60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setHasMustTailInVarArgFunc (bool B)</td>
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



<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### setHasOpaqueSPAdjustment() {#aa1c21b032c9a8c45eed19c74c40e9999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setHasOpaqueSPAdjustment (bool B)</td>
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



<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### setHasPatchPoint() {#a24116ef8cbdb5ac84d8b39da3123a2ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setHasPatchPoint (bool s=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### setHasStackMap() {#a516c061efff162d3443801359559aa65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setHasStackMap (bool s=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### setHasTailCall() {#a701abf47478571dfb8c619678b7ce7d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setHasTailCall (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>.</p>

</div>
</div>

### setHasVAStart() {#ae52ff27f281ac6f032b78b0d95bc7d24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setHasVAStart (bool B)</td>
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



<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### setIsAliasedObjectIndex() {#a7dfc119c1adb845f7eea8851a7c6a69c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setIsAliasedObjectIndex (int ObjectIdx, bool IsAliased)</td>
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

<p>Set "maybe pointed to by an LLVM IR value" for an object.</p>

<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#ae8ee5af33e0f1b85755cf5a1e4951793">tryToElideArgumentCopy</a>.</p>

</div>
</div>

### setIsImmutableObjectIndex() {#a0d6c9ad6ad96f64b2fe861339c192f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setIsImmutableObjectIndex (int ObjectIdx, bool IsImmutable)</td>
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

<p>Marks the immutability of an object.</p>

<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#ae8ee5af33e0f1b85755cf5a1e4951793">tryToElideArgumentCopy</a>.</p>

</div>
</div>

### setLocalFrameMaxAlign() {#a5cdc7b3a76eaab70c6fabdf4ca3dd7e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setLocalFrameMaxAlign (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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

<p>Required alignment of the local object blob, which is the strictest alignment of any object in it.</p>

<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### setLocalFrameSize() {#a39e8a5cc0ba7568b8e0584139d97c0cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setLocalFrameSize (int64_t sz)</td>
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

<p>Set the size of the local object blob.</p>

<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### setMaxCallFrameSize() {#a02a7503d1af1782b35b3683e173cb5f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setMaxCallFrameSize (uint64_t S)</td>
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



<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ad5bca3a5e9c1e69593d1f15b4cb1c44c">llvm::PPCFrameLowering::determineFrameLayoutAndUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#acd8f0ca7af8321ea32072c40fe93619e">llvm::SystemZXPLINKFrameLowering::processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

### setObjectAlignment() {#af4c34648ca4596767ff0c3409fc3f2d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setObjectAlignment (int ObjectIdx, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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

<p>setObjectAlignment - Change the alignment of the specified stack object.</p>

<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b207734207bd39ae7cc1b287e915160">contributesToMaxAlignment</a>, <a href="#a1f09e99062be1101e3a2cf3ff88878f7">ensureMaxAlignment</a> and <a href="#ad718aae0ce2a188fa35cb2781024ffc0">getStackID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a3046f0367b644d6feafcc16f8da39967">emitAlignedDPRCS2Spills</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8679ab19e5fd70f2011394a4923d7c43">LowerAsSplatVectorLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a> and <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a01be2a14188ac612c910c9043ae037e1">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeSP</a>.</p>

</div>
</div>

### setObjectOffset() {#a3cd29e7edbcaceb5834eaa7d089a5bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setObjectOffset (int ObjectIdx, int64_t SPOffset)</td>
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

<p>Set the stack frame offset of the specified object.</p>


<p>The offset is relative to the stack pointer on entry to the function.</p>


<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af5302d38d9a16eee93f13a1579c8773d">isDeadObjectIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a7a72b426a146f931681039777ba2bbc5">AdjustStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxprologepilogpass-cpp/#a7a72b426a146f931681039777ba2bbc5">AdjustStackOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#af79b8bdd9826c6c96dd238e32520fc94">llvm::ARCFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a6447282533aad4f054c9bfcf8df8028f">llvm::SystemZXPLINKFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a56db9c3cbc621caf7d84f6982f095392">determineSVEStackObjectOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ae8c531c36381ca6a666ca73f740335cb">llvm::WebAssemblyFrameLowering::getLocalForStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3f176ff8abd35fbe2f043c22d088302e">llvm::PPCFrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a23de116e7a75d0aaae35a539d6a6118e">scavengeStackSlot</a>.</p>

</div>
</div>

### setObjectSExt() {#a58f8798e1a5673018d0877282f893a69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setObjectSExt (int ObjectIdx, bool IsSExt)</td>
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



<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### setObjectSize() {#a65b1c146aac2536b62f73bd01e36c3e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setObjectSize (int ObjectIdx, int64_t Size)</td>
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

<p>Change the size of the specified stack object.</p>

<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ae8c531c36381ca6a666ca73f740335cb">llvm::WebAssemblyFrameLowering::getLocalForStackObject</a>.</p>

</div>
</div>

### setObjectSSPLayout() {#a5938f9d0441c7b989d3e08e4dbd81ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setObjectSSPLayout (int ObjectIdx, <a href="#a3df888d2d0447ad8ff7b616b080d9f13">SSPLayoutKind</a> Kind)</td>
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



<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af5302d38d9a16eee93f13a1579c8773d">isDeadObjectIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ssplayoutinfo/#a2068b15b4ae5d41ac05efbc9dd9dc48c">llvm::SSPLayoutInfo::copyToMachineFrameInfo</a>.</p>

</div>
</div>

### setObjectZExt() {#a0baf8d3feb99247cc5341a3612fef165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setObjectZExt (int ObjectIdx, bool IsZExt)</td>
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



<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### setOffsetAdjustment() {#af941923e75bebb485321894b2ddbeb0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setOffsetAdjustment (int64_t Adj)</td>
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

<p>Set the correction for frame offsets.</p>

<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a921a457b786497c2309b9f63abd9c951">llvm::MSP430FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#acd8f0ca7af8321ea32072c40fe93619e">llvm::SystemZXPLINKFrameLowering::processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

### setRestorePoint() {#a17b15f54419f33a561a4b6959b2d0969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setRestorePoint (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewRestore)</td>
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



<p>Definition at line 826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-shrinkwrap-cpp-/shrinkwrap/#a0b77b3bd867840460e8de5e83245240e">anonymous{ShrinkWrap.cpp}::ShrinkWrap::runOnMachineFunction</a>.</p>

</div>
</div>

### setReturnAddressIsTaken() {#a81b01652144140bfb79c6ffdaff923f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setReturnAddressIsTaken (bool s)</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ac34b44e6d66ff1778af7b93db6d3cf23">llvm::HexagonTargetLowering::LowerRETURNADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a1fadb53c3bdb5b803ea10b85a510b321">llvm::LanaiTargetLowering::LowerRETURNADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a94ec50da525b52281c1d4bbde196c520">llvm::MSP430TargetLowering::LowerRETURNADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afa7dd71b99cc3f038bc3f91104cf66ee">LowerRETURNADDR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#ae6503e6c0724d0ae0cb7854ba5c5a9f6">lowerRETURNADDR</a>.</p>

</div>
</div>

### setSavePoint() {#abc98dd738845a40c876cbbf6f5e51f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setSavePoint (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewSave)</td>
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



<p>Definition at line 824 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-shrinkwrap-cpp-/shrinkwrap/#a0b77b3bd867840460e8de5e83245240e">anonymous{ShrinkWrap.cpp}::ShrinkWrap::runOnMachineFunction</a>.</p>

</div>
</div>

### setStackID() {#a6ba514594eb802f087046edbe201f8f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setStackID (int ObjectIdx, uint8_t ID)</td>
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




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>StackID</p></dd>
</dl>


<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a0c9359d4e969f68a7c7643fc3fcb5c">llvm::RISCVFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#af8195925dae80a73b2c6101290b5962b">llvm::SystemZXPLINKFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ae8c531c36381ca6a666ca73f740335cb">llvm::WebAssemblyFrameLowering::getLocalForStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a44f850288e925f301a01218710e88254">llvm::SystemZXPLINKFrameLowering::getOrCreateFramePointerSaveIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aef098c9f09dc6ea1e32e64d79091a237">llvm::AArch64InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab4a6a57aa863f068433ba056f15c61b1">llvm::RISCVInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a97509f8c54ec54df287f62902fd2c472">llvm::SIMachineFunctionInfo::removeDeadFrameIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aeba4e73d60d1b4cedc120d06114c0620">llvm::AArch64InstrInfo::storeRegToStackSlot</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a23e6d76b3b763236213c20fdd08718ed">llvm::RISCVInstrInfo::storeRegToStackSlot</a>.</p>

</div>
</div>

### setStackProtectorIndex() {#a79ce969f0376bbc0a6f06966ce274167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setStackProtectorIndex (int I)</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### setStackSize() {#ae4d51e9e70d6a7fb366f2a09d10a0945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setStackSize (uint64_t Size)</td>
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

<p>Set the size of the stack.</p>

<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a6447282533aad4f054c9bfcf8df8028f">llvm::SystemZXPLINKFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ad5bca3a5e9c1e69593d1f15b4cb1c44c">llvm::PPCFrameLowering::determineFrameLayoutAndUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a198d0eb07bb9ae2ff6dba28a16264342">llvm::SparcFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#ab3c8272ea0652d9ab75b889488f2717f">llvm::VEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>.</p>

</div>
</div>

### setUnsafeStackSize() {#aecbf301c7010f06b304aa10365e2b91a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setUnsafeStackSize (uint64_t Size)</td>
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



<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp/#adfbf235872b70098310f84ace07f312a">setUnsafeStackSize</a>.</p>

</div>
</div>

### setUseLocalStackAllocationBlock() {#a37cfdca2465d899059663518672882b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineFrameInfo::setUseLocalStackAllocationBlock (bool v)</td>
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

<p>setUseLocalStackAllocationBlock - Set whether the local allocation blob should be allocated together or let PEI allocate the locals in it directly.</p>

<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/localstackslotallocation-cpp/#a4fb27fac71c41b0d9873024cbbd12bc6">INITIALIZE_PASS</a>.</p>

</div>
</div>

### shouldRealignStack() {#a4f3c466a5b43fe5ca61db322b5dcac0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::shouldRealignStack ()</td>
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

<p>Return true if stack realignment is forced by function attributes or if the stack alignment.</p>

<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ab5e5e73c5c13ca2211e1d365363e4170">llvm::TargetRegisterInfo::shouldRealignStack</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AdjustsStack {#ab944fbcaea791e49c2365b083a4da6f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::AdjustsStack = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set to true if this function adjusts the stack – e.g., when calling another function.</p>


<p>This is only valid during and after prolog/epilog code insertion.</p>


<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### CSInfo {#a04abe16273570412452077008a63cc25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CalleeSavedInfo&gt; llvm::MachineFrameInfo::CSInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The prolog/epilog code inserter fills in this vector with each callee saved register saved in either the frame or a different register.</p>


<p>Beyond its use by the prolog/ epilog code inserter, this data is used for debug info and exception handling.</p>


<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### CSIValid {#a7eda63f11bcedd9f2d8cd9aeacdbb57a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::CSIValid = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has CSInfo been set yet?</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### CVBytesOfCalleeSavedRegisters {#aa623ac77c2a3c3109568e03dae8455ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineFrameInfo::CVBytesOfCalleeSavedRegisters = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of bytes of callee saved registers that the target wants to report for the current function in the CodeView S_FRAMEPROC record.</p>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### ForcedRealign {#a02a39dc379f899e79a0443e70ad7419e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::ForcedRealign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the function has the <span class="doxyComputerOutput">alignstack</span> attribute.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### FrameAddressTaken {#af1bd4f8bc99f9c9d3e0ebce9e7ec8e76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::FrameAddressTaken = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This boolean keeps track of whether there is a call to builtin @llvm.frameaddress.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### FunctionContextIdx {#a347c67d70fbcc35e68fb27d22c1402ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MachineFrameInfo::FunctionContextIdx = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The frame index for the function context. Used for SjLj exceptions.</p>

<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### HasCalls {#a4c185e69bf0d1852e788721aa35b0620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::HasCalls = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set to true if this function has any function calls.</p>

<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### HasCopyImplyingStackAdjustment {#abbde54f61eb0eefe290d1c766510b7c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::HasCopyImplyingStackAdjustment = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the function contains operations which will lower down to instructions which manipulate the stack pointer.</p>

<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### HasMustTailInVarArgFunc {#a706c186c4c6967664e4ee052a3f4d28e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::HasMustTailInVarArgFunc = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this is a varargs function that contains a musttail call.</p>

<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### HasOpaqueSPAdjustment {#abfbdba4b57a070dff011e21b9dd8da8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::HasOpaqueSPAdjustment = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the function dynamically adjusts the stack pointer through some opaque mechanism like inline assembly or Win32 EH.</p>

<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### HasPatchPoint {#af4fb3ea5454851cae5333dfd6a0d03f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::HasPatchPoint = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This boolean keeps track of whether there is a call to builtin @llvm.experimental.patchpoint.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### HasStackMap {#ab94b2efe4b22474f66d48b2730e8b4c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::HasStackMap = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This boolean keeps track of whether there is a call to builtin @llvm.experimental.stackmap.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### HasTailCall {#a7f348952ada90a5d94155dc87247d560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::HasTailCall = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this function contains a tail call.</p>


<p>If so immutable objects like function arguments are no longer so. A tail call <em>can</em> override fixed stack objects like arguments so we can't treat them as immutable.</p>


<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### HasVarSizedObjects {#a87a9eedd78b034d3f10c641c214d3fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::HasVarSizedObjects = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This boolean keeps track of whether any variable sized objects have been allocated yet.</p>

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### HasVAStart {#abc80a3d853d4ea6d6b7129610bed0306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::HasVAStart = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the function contains a call to the llvm.vastart intrinsic.</p>

<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### LocalFrameMaxAlign {#a165c88931366076a33dbc69dbb2a841c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineFrameInfo::LocalFrameMaxAlign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Required alignment of the local object blob, which is the strictest alignment of any object in it.</p>

<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### LocalFrameObjects {#aee2b6e9566815515a5762320cdabf7c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;int, int64_t&gt;, 32&gt; llvm::MachineFrameInfo::LocalFrameObjects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>References to frame indices which are mapped into the local frame allocation block.</p>


<p>&lt;FrameIdx, LocalOffset&gt;</p>


<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### LocalFrameSize {#a04f98738c2347869d2c21a6ad56d1c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MachineFrameInfo::LocalFrameSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of the pre-allocated local frame block.</p>

<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### MaxAlignment {#ad283c4b55d2343c426d1ef3ba43b9322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineFrameInfo::MaxAlignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The prolog/epilog code inserter may process objects that require greater alignment than the default alignment the target provides.</p>


<p>To handle this, MaxAlignment is set to the maximum alignment needed by the objects on the current frame. If this is greater than the native alignment maintained by the compiler, dynamic alignment code will be needed.</p>


<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### MaxCallFrameSize {#a82fbd0176ea84c953243e8b10533bfd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MachineFrameInfo::MaxCallFrameSize = ~UINT64_C(0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This contains the size of the largest call frame if the target uses frame setup/destroy pseudo instructions (as defined in the TargetFrameInfo class).</p>


<p>This information is important for frame pointer elimination. It is only valid during and after prolog/epilog code insertion.</p>


<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### NumFixedObjects {#a724d6e9b7d17e02038e7b3cff288c701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineFrameInfo::NumFixedObjects = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This contains the number of fixed objects contained on the stack.</p>


<p>Because fixed objects are stored at a negative index in the Objects list, this is also the index to the 0th object in the list.</p>


<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### Objects {#aff9424c694e902d27b25595762306fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;StackObject&gt; llvm::MachineFrameInfo::Objects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of stack objects allocated.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### OffsetAdjustment {#a1b262ea7da36885332a727434e0e2783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MachineFrameInfo::OffsetAdjustment = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The amount that a frame offset needs to be adjusted to have the actual offset from the stack/frame pointer.</p>


<p>The exact usage of this is target-dependent, but it is typically used to adjust between SP-relative and FP-relative offsets. E.G., if objects are accessed via SP then OffsetAdjustment is zero; if FP is used, OffsetAdjustment is set to the distance between the initial SP and the value in FP. For many targets, this value is only used when generating debug info (via TargetRegisterInfo::getFrameIndexReference); when generating code, the corresponding adjustments are performed directly.</p>


<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### Restore {#ac432932b106d6b7eec3570d4e07fbc5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::MachineFrameInfo::Restore = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Not null, if shrink-wrapping found a better place for the epilogue.</p>

<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### ReturnAddressTaken {#a018f958f0f234ca0d11ea854ae628c2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::ReturnAddressTaken = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This boolean keeps track of whether there is a call to builtin @llvm.returnaddress.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### Save {#a242ff5704d42e44d632ebb6dc0a5a570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::MachineFrameInfo::Save = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Not null, if shrink-wrapping found a better place for the prologue.</p>

<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### StackAlignment {#a5f6558ee33cbd213c2e8f65456c0ca2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineFrameInfo::StackAlignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The alignment of the stack.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### StackProtectorIdx {#aab5692108667d80a25c8fd4ed4258a7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MachineFrameInfo::StackProtectorIdx = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The frame index for the stack protector.</p>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### StackRealignable {#a56909a798a584b26bbc78e829ab85d75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::StackRealignable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Can the stack be realigned.</p>


<p>This can be false if the target does not support stack realignment, or if the user asks us not to realign the stack. In this situation, overaligned allocas are all treated as dynamic allocations and the target must handle them as part of DYNAMIC_STACKALLOC lowering. All non-alloca stack objects have their alignment clamped to the base ABI stack alignment. FIXME: There is room for improvement in this case, in terms of grouping overaligned allocas into a "secondary stack frame" and then only use a single alloca to allocate this frame and only a single virtual register to access it. Currently, without such an optimization, each such alloca gets its own dynamic realignment.</p>


<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### StackSize {#a6fad43d5b2aba0a5827cbf40c5e64fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MachineFrameInfo::StackSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The prolog/epilog code inserter calculates the final stack offsets for all of the fixed size objects, updating the Objects list above.</p>


<p>It then updates StackSize to contain the number of bytes that need to be allocated on entry to the function.</p>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### UnsafeStackSize {#a3be7d7e0d8435d4a3fc7190b4923af24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MachineFrameInfo::UnsafeStackSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of the UnsafeStack Frame.</p>

<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

### UseLocalStackAllocationBlock {#ada495f42ebe7565aafb567a01bc8f762}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineFrameInfo::UseLocalStackAllocationBlock = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the local object blob needs to be allocated together.</p>


<p>If not, PEI should ignore the isPreAllocated flags on the stack objects and just allocate them normally.</p>


<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">MachineFrameInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineframeinfo-cpp">MachineFrameInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
