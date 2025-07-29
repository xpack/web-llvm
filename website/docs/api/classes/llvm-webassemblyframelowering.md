---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/webassemblyframelowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WebAssemblyFrameLowering` Class



## Declaration

<div class="doxyDeclaration">
class llvm::WebAssemblyFrameLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">Target/WebAssembly/WebAssemblyFrameLowering.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetframelowering">TargetFrameLowering</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Information about stack frame layout on the target. <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a074ebe9dba71f028e4f3f2ea8d7482ea">WebAssemblyFrameLowering</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab544417d50db46882a3a223233830dbc">eliminateCallFramePseudoInstr</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called during prolog/epilog code insertion to eliminate call frame setup and destroy pseudo instructions (but only if the <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> is using them). <a href="#ab544417d50db46882a3a223233830dbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78e4ff0f9a757b578b967d5bd1f70ee">emitPrologue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These methods insert prolog and epilog code into the function. <a href="#ac78e4ff0f9a757b578b967d5bd1f70ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbe9a36b5d064d3fe4667e4c1b47af85">emitEpilogue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ac032ff4fb3914f8f6f29bc9b8f2cb0">hasReservedCallFrame</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Under normal circumstances, when a frame pointer is not required, we reserve argument space for call sites in the function immediately on entry to the current function. <a href="#a6ac032ff4fb3914f8f6f29bc9b8f2cb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5beee39b61ea838c32196fc83536019">isSupportedStackID</a> (TargetStackID::Value ID) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase">DwarfFrameBase</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a940d2583242cbf51edf546963eaafdd9">getDwarfFrameBase</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the frame base information to be encoded in the DWARF subprogram debug info. <a href="#a940d2583242cbf51edf546963eaafdd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b2bec8faee9b97ef8c297fb0cedabdb">needsPrologForEH</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfa976b571bd6001d4e8f4ccba059162">writeSPToGlobal</a> (unsigned SrcReg, MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator &amp;InsertStore, const DebugLoc &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write SP back to __stack_pointer global. <a href="#acfa976b571bd6001d4e8f4ccba059162">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac345b7d27b1e29825f2b86adbfdd0cd5">hasFPImpl</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified function should have a dedicated frame pointer register. <a href="#ac345b7d27b1e29825f2b86adbfdd0cd5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabc99755558303881aa58229f6335c89">hasBP</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We need a base pointer in the case of having items on the stack that require stricter alignment than the stack pointer itself. <a href="#aabc99755558303881aa58229f6335c89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add9bf59914f9afd679766c8cfdcb0237">needsSPForLocalFrame</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80308da692e32540c4dffe9561b16938">needsSP</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this function needs a local user-space stack pointer. <a href="#a80308da692e32540c4dffe9561b16938">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8f6a5a50159b5a2b2251c37c459440f">needsSPWriteback</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the local user-space stack pointer needs to be written back to __stack_pointer global by this function (this is not meaningful if needsSP is false). <a href="#ac8f6a5a50159b5a2b2251c37c459440f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c531c36381ca6a666ca73f740335cb">getLocalForStackObject</a> (MachineFunction &amp;MF, int FrameIndex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73339b4209876d8da0ec0c2cfe98151b">getSPReg</a> (const MachineFunction &amp;MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c16ec43d7086c3a39f3f474c000d94b">getFPReg</a> (const MachineFunction &amp;MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba0d7486f2d7c012d4b0e285f93eba9e">getOpcConst</a> (const MachineFunction &amp;MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a181114de0ec299338f1ddf9bbecc7f44">getOpcAdd</a> (const MachineFunction &amp;MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24b0c55a235bb7d8b9da31d10f9493f">getOpcSub</a> (const MachineFunction &amp;MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f1aab334a212f3b5907411d19d0b0ca">getOpcAnd</a> (const MachineFunction &amp;MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff1665c518309dffd608991363b04b6">getOpcGlobGet</a> (const MachineFunction &amp;MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53be238571b9d7f4ea62d163dd86a6e3">getOpcGlobSet</a> (const MachineFunction &amp;MF)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae70515c96b13eefdcecc4597611cbe54">RedZoneSize</a> = 128</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of the red zone for the user stack (leaf functions can use this much space below the stack pointer without writing it back to __stack_pointer global). <a href="#ae70515c96b13eefdcecc4597611cbe54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WebAssemblyFrameLowering() {#a074ebe9dba71f028e4f3f2ea8d7482ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WebAssemblyFrameLowering::WebAssemblyFrameLowering ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a453c74e2daac0745b53f8b31c11fc50cad1fc7c9d0bae5bf76a67d2d26ce99c1a">llvm::TargetFrameLowering::StackGrowsDown</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6a6d31b2f1e5754f5824c5dec555eeac">llvm::TargetFrameLowering::TargetFrameLowering</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### eliminateCallFramePseudoInstr() {#ab544417d50db46882a3a223233830dbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator WebAssemblyFrameLowering::eliminateCallFramePseudoInstr (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
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

<p>This method is called during prolog/epilog code insertion to eliminate call frame setup and destroy pseudo instructions (but only if the <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> is using them).</p>


<p>It is responsible for eliminating these instructions, replacing them with concrete instructions. This method need only be implemented if using call frame setup/destroy pseudo instructions. Returns an iterator pointing to the instruction after the replaced one.</p>


<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a73339b4209876d8da0ec0c2cfe98151b">getSPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="#acfa976b571bd6001d4e8f4ccba059162">writeSPToGlobal</a>.</p>

</div>
</div>

### emitEpilogue() {#adbe9a36b5d064d3fe4667e4c1b47af85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyFrameLowering::emitEpilogue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a1c16ec43d7086c3a39f3f474c000d94b">getFPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="#a181114de0ec299338f1ddf9bbecc7f44">getOpcAdd</a>, <a href="#aba0d7486f2d7c012d4b0e285f93eba9e">getOpcConst</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="#a73339b4209876d8da0ec0c2cfe98151b">getSPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="#acfa976b571bd6001d4e8f4ccba059162">writeSPToGlobal</a>.</p>

</div>
</div>

### emitPrologue() {#ac78e4ff0f9a757b578b967d5bd1f70ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyFrameLowering::emitPrologue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>These methods insert prolog and epilog code into the function.</p>

<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a30a1feca92679c24a46b0b824a6de269">llvm::MachineInstrBuilder::addExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6af779d02be6e05e3315887e58e8ec35">llvm::MachineFunction::createExternalSymbolName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a1c16ec43d7086c3a39f3f474c000d94b">getFPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="#a6f1aab334a212f3b5907411d19d0b0ca">getOpcAnd</a>, <a href="#aba0d7486f2d7c012d4b0e285f93eba9e">getOpcConst</a>, <a href="#a7ff1665c518309dffd608991363b04b6">getOpcGlobGet</a>, <a href="#af24b0c55a235bb7d8b9da31d10f9493f">getOpcSub</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="#a73339b4209876d8da0ec0c2cfe98151b">getSPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a15296a1aa48a333f25583e31fd8f2a40">llvm::WebAssembly::isArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a> and <a href="#acfa976b571bd6001d4e8f4ccba059162">writeSPToGlobal</a>.</p>

</div>
</div>

### getDwarfFrameBase() {#a940d2583242cbf51edf546963eaafdd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetFrameLowering::DwarfFrameBase WebAssemblyFrameLowering::getDwarfFrameBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Return the frame base information to be encoded in the DWARF subprogram debug info.</p>

<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#a2f639b98c5e0f3f1a8ddf32de3ad4b28">llvm::WebAssemblyFunctionInfo::getFrameBaseLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#ae1ca17510f13868620c439a9681b7b97">llvm::WebAssemblyFunctionInfo::isFrameBaseVirtual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#afb0e38d707f5f5ed287dd43193a61f3ca11eb2918319786f66ec3b4d8f26dc1c3">llvm::WebAssembly::TI_GLOBAL_RELOC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#afb0e38d707f5f5ed287dd43193a61f3cabc43eac6d18b7525076da25407e68d5f">llvm::WebAssembly::TI_LOCAL</a>.</p>

</div>
</div>

### hasReservedCallFrame() {#a6ac032ff4fb3914f8f6f29bc9b8f2cb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyFrameLowering::hasReservedCallFrame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Under normal circumstances, when a frame pointer is not required, we reserve argument space for call sites in the function immediately on entry to the current function.</p>


<p>This eliminates the need for add/sub sp brackets around call sites. Returns true if the call frame is included as part of the stack frame.</p>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>.</p>

</div>
</div>

### isSupportedStackID() {#aa5beee39b61ea838c32196fc83536019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyFrameLowering::isSupportedStackID (<a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5">TargetStackID::Value</a> ID)</td>
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



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6e380efd1c5b2089017a2b2b04b2e95d">llvm::TargetFrameLowering::isSupportedStackID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5ab9b4a66e5478772af595c40fbce45c03">llvm::TargetStackID::WasmLocal</a>.</p>

</div>
</div>

### needsPrologForEH() {#a3b2bec8faee9b97ef8c297fb0cedabdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyFrameLowering::needsPrologForEH (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#af2741cb32381997a1e0f074f63d977ae">llvm::MCAsmInfo::getExceptionHandlingType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#afb72c5626afbc815284e2b26bb0663f8">llvm::TargetMachine::getMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a2cc8bb867c8949943ca7d88f1db31fde">llvm::MachineFrameInfo::hasCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a6a0f6312963ee6fb0969243607174949">llvm::Function::hasPersonalityFn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84af93da81fd23e2eeaf8de29b04bb2399f">llvm::Wasm</a>.</p>

</div>
</div>

### writeSPToGlobal() {#acfa976b571bd6001d4e8f4ccba059162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyFrameLowering::writeSPToGlobal (unsigned SrcReg, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; InsertStore, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write SP back to __stack_pointer global.</p>

<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a30a1feca92679c24a46b0b824a6de269">llvm::MachineInstrBuilder::addExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6af779d02be6e05e3315887e58e8ec35">llvm::MachineFunction::createExternalSymbolName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a53be238571b9d7f4ea62d163dd86a6e3">getOpcGlobSet</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#ab544417d50db46882a3a223233830dbc">eliminateCallFramePseudoInstr</a>, <a href="#adbe9a36b5d064d3fe4667e4c1b47af85">emitEpilogue</a> and <a href="#ac78e4ff0f9a757b578b967d5bd1f70ee">emitPrologue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### hasFPImpl() {#ac345b7d27b1e29825f2b86adbfdd0cd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyFrameLowering::hasFPImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified function should have a dedicated frame pointer register.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a503a8cb169aa29ac907c218692087db3">llvm::MachineFrameInfo::hasPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa7d9e2f26e4c8b32f51c455b220ce13c">llvm::MachineFrameInfo::hasStackMap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a32125253541ab2e7ec5bbe550ecc2d0c">llvm::MachineFrameInfo::isFrameAddressTaken</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### hasBP() {#aabc99755558303881aa58229f6335c89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyFrameLowering::hasBP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We need a base pointer in the case of having items on the stack that require stricter alignment than the stack pointer itself.</p>


<p>Because we need to shift the stack pointer by some unknown amount to force the alignment, we need to record the value of the stack pointer on entry to the function.</p>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>

</div>
</div>

### needsSP() {#a80308da692e32540c4dffe9561b16938}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyFrameLowering::needsSP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this function needs a local user-space stack pointer.</p>


<p>Unlike a machine stack pointer, the wasm user stack pointer is a global variable, so it is loaded into a register in the prolog.</p>


<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>

</div>
</div>

### needsSPForLocalFrame() {#add9bf59914f9afd679766c8cfdcb0237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyFrameLowering::needsSPForLocalFrame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>

</div>
</div>

### needsSPWriteback() {#ac8f6a5a50159b5a2b2251c37c459440f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyFrameLowering::needsSPWriteback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the local user-space stack pointer needs to be written back to __stack_pointer global by this function (this is not meaningful if needsSP is false).</p>


<p>If false, the stack red zone can be used and only a local SP is needed.</p>


<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getFPReg() {#a1c16ec43d7086c3a39f3f474c000d94b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned WebAssemblyFrameLowering::getFPReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>


<p>Referenced by <a href="#adbe9a36b5d064d3fe4667e4c1b47af85">emitEpilogue</a> and <a href="#ac78e4ff0f9a757b578b967d5bd1f70ee">emitPrologue</a>.</p>

</div>
</div>

### getLocalForStackObject() {#ae8c531c36381ca6a666ca73f740335cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; WebAssemblyFrameLowering::getLocalForStackObject (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, int FrameIndex)</td>
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



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#ad2fb148dfac3182fce33be95fc4e9159">llvm::AllocaInst::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a171600b1de399e1d60976508ffb38ea3">llvm::MachineFrameInfo::getObjectAllocation</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad718aae0ce2a188fa35cb2781024ffc0">llvm::MachineFrameInfo::getStackID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#af45a1b676eb96b330c6a5bb5dab029ae">llvm::WebAssembly::isWasmVarAddressSpace</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/globalmergefunctions-h/#a54f7429fa5826ff9909619b76d2bf319a509820290d57f333403f490dde7316f4">Local</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a3cd29e7edbcaceb5834eaa7d089a5bc4">llvm::MachineFrameInfo::setObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a65b1c146aac2536b62f73bd01e36c3e9">llvm::MachineFrameInfo::setObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a6ba514594eb802f087046edbe201f8f4">llvm::MachineFrameInfo::setStackID</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5ab9b4a66e5478772af595c40fbce45c03">llvm::TargetStackID::WasmLocal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp/#a4976393743e516294356ec7fe7b5500b">INITIALIZE_PASS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a3c9ce196b735c1a9c187408db0c1a987">IsWebAssemblyLocal</a>.</p>

</div>
</div>

### getOpcAdd() {#a181114de0ec299338f1ddf9bbecc7f44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned WebAssemblyFrameLowering::getOpcAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a> and <a href="#adbe9a36b5d064d3fe4667e4c1b47af85">emitEpilogue</a>.</p>

</div>
</div>

### getOpcAnd() {#a6f1aab334a212f3b5907411d19d0b0ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned WebAssemblyFrameLowering::getOpcAnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>


<p>Referenced by <a href="#ac78e4ff0f9a757b578b967d5bd1f70ee">emitPrologue</a>.</p>

</div>
</div>

### getOpcConst() {#aba0d7486f2d7c012d4b0e285f93eba9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned WebAssemblyFrameLowering::getOpcConst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a>, <a href="#adbe9a36b5d064d3fe4667e4c1b47af85">emitEpilogue</a> and <a href="#ac78e4ff0f9a757b578b967d5bd1f70ee">emitPrologue</a>.</p>

</div>
</div>

### getOpcGlobGet() {#a7ff1665c518309dffd608991363b04b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned WebAssemblyFrameLowering::getOpcGlobGet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>


<p>Referenced by <a href="#ac78e4ff0f9a757b578b967d5bd1f70ee">emitPrologue</a>.</p>

</div>
</div>

### getOpcGlobSet() {#a53be238571b9d7f4ea62d163dd86a6e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned WebAssemblyFrameLowering::getOpcGlobSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>


<p>Referenced by <a href="#acfa976b571bd6001d4e8f4ccba059162">writeSPToGlobal</a>.</p>

</div>
</div>

### getOpcSub() {#af24b0c55a235bb7d8b9da31d10f9493f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned WebAssemblyFrameLowering::getOpcSub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>


<p>Referenced by <a href="#ac78e4ff0f9a757b578b967d5bd1f70ee">emitPrologue</a>.</p>

</div>
</div>

### getSPReg() {#a73339b4209876d8da0ec0c2cfe98151b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned WebAssemblyFrameLowering::getSPReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>


<p>Referenced by <a href="#ab544417d50db46882a3a223233830dbc">eliminateCallFramePseudoInstr</a>, <a href="#adbe9a36b5d064d3fe4667e4c1b47af85">emitEpilogue</a> and <a href="#ac78e4ff0f9a757b578b967d5bd1f70ee">emitPrologue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### RedZoneSize {#ae70515c96b13eefdcecc4597611cbe54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t llvm::WebAssemblyFrameLowering::RedZoneSize = 128</td>
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

<p>Size of the red zone for the user stack (leaf functions can use this much space below the stack pointer without writing it back to __stack_pointer global).</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-cpp">WebAssemblyFrameLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyframelowering-h">WebAssemblyFrameLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
