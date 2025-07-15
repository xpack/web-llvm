---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-localstackslotallocation-cpp-/localstackslotimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LocalStackSlotImpl` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{LocalStackSlotAllocation.cpp}::LocalStackSlotImpl { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8410a9af77c19a1392e7b1283ebbafb">StackObjSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; int, 8 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>StackObjSet - A set of stack object indexes. <a href="#ad8410a9af77c19a1392e7b1283ebbafb">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a044a92fface1cc13bc3b807c2370e9f0">runOnMachineFunction</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a138d0bf92405369653bb8cfb8947dc0c">AdjustStackOffset</a> (MachineFrameInfo &amp;MFI, int FrameIdx, int64_t &amp;Offset, bool StackGrowsDown, Align &amp;MaxAlign)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AdjustStackOffset - Helper function used to adjust the stack frame offset. <a href="#a138d0bf92405369653bb8cfb8947dc0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c093ad816d4a9999099bca169138d3f">AssignProtectedObjSet</a> (const StackObjSet &amp;UnassignedObjs, SmallSet&lt; int, 16 &gt; &amp;ProtectedObjs, MachineFrameInfo &amp;MFI, bool StackGrowsDown, int64_t &amp;Offset, Align &amp;MaxAlign)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AssignProtectedObjSet - Helper function to assign large stack objects (i.e., those required to be close to the Stack Protector) to stack offsets. <a href="#a6c093ad816d4a9999099bca169138d3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac61741e687f16942048198313d270b41">calculateFrameObjectOffsets</a> (MachineFunction &amp;Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>calculateFrameObjectOffsets - Calculate actual frame offsets for all of the abstract stack objects. <a href="#ac61741e687f16942048198313d270b41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af351add367d956fa145ab31cabc31ebc">insertFrameReferenceRegisters</a> (MachineFunction &amp;Fn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int64_t, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adacbf80139f1167d832f044a8592908b">LocalOffsets</a></td>
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


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/localstackslotallocation-cpp">LocalStackSlotAllocation.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### StackObjSet {#ad8410a9af77c19a1392e7b1283ebbafb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{LocalStackSlotAllocation.cpp}::LocalStackSlotImpl::StackObjSet =  SmallSetVector&lt;int, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>StackObjSet - A set of stack object indexes.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/localstackslotallocation-cpp">LocalStackSlotAllocation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runOnMachineFunction() {#a044a92fface1cc13bc3b807c2370e9f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LocalStackSlotAllocation.cpp}::LocalStackSlotImpl::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/localstackslotallocation-cpp">LocalStackSlotAllocation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-localstackslotallocation-cpp-/localstackslotpass/#adb8521759c7ff655bc7bcce0b0d78d5b">anonymous{LocalStackSlotAllocation.cpp}::LocalStackSlotPass::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AdjustStackOffset() {#a138d0bf92405369653bb8cfb8947dc0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LocalStackSlotImpl::AdjustStackOffset (<a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> &amp; MFI, int FrameIdx, int64_t &amp; Offset, bool StackGrowsDown, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp; MaxAlign)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AdjustStackOffset - Helper function used to adjust the stack frame offset.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/localstackslotallocation-cpp">LocalStackSlotAllocation.cpp</a>.</p>

</div>
</div>

### AssignProtectedObjSet() {#a6c093ad816d4a9999099bca169138d3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LocalStackSlotImpl::AssignProtectedObjSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">StackObjSet</a> &amp; UnassignedObjs, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; int, 16 &gt; &amp; ProtectedObjs, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> &amp; MFI, bool StackGrowsDown, int64_t &amp; Offset, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp; MaxAlign)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AssignProtectedObjSet - Helper function to assign large stack objects (i.e., those required to be close to the Stack Protector) to stack offsets.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/localstackslotallocation-cpp">LocalStackSlotAllocation.cpp</a>.</p>

</div>
</div>

### calculateFrameObjectOffsets() {#ac61741e687f16942048198313d270b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LocalStackSlotImpl::calculateFrameObjectOffsets (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>calculateFrameObjectOffsets - Calculate actual frame offsets for all of the abstract stack objects.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/localstackslotallocation-cpp">LocalStackSlotAllocation.cpp</a>.</p>

</div>
</div>

### insertFrameReferenceRegisters() {#af351add367d956fa145ab31cabc31ebc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LocalStackSlotImpl::insertFrameReferenceRegisters (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/localstackslotallocation-cpp">LocalStackSlotAllocation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LocalOffsets {#adacbf80139f1167d832f044a8592908b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;int64_t, 16&gt; anonymous{LocalStackSlotAllocation.cpp}::LocalStackSlotImpl::LocalOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/localstackslotallocation-cpp">LocalStackSlotAllocation.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/localstackslotallocation-cpp">LocalStackSlotAllocation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
