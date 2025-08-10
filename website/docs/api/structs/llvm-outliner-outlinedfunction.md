---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/outliner/outlinedfunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `OutlinedFunction` Struct

<p>The information necessary to create an outlined function for some class of candidate. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::outliner::OutlinedFunction { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">llvm/CodeGen/MachineOutliner.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/outliner/globaloutlinedfunction">GlobalOutlinedFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The information necessary to create an outlined function that is matched globally. <a href="/web-llvm/docs/api/structs/llvm/outliner/globaloutlinedfunction/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2f1c35acd04b812afdb550964c2eab2">OutlinedFunction</a> (std::vector&lt; Candidate &gt; &amp;Candidates, unsigned SequenceSize, unsigned FrameOverhead, unsigned FrameConstructionID)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5833702b0fcc4f18c00c362e95dca6b1">OutlinedFunction</a> ()=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae602839d12a4000e8c1a0d1db3d2865f">~OutlinedFunction</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0081f20622492dac85cd60d330e9673c">getOccurrenceCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of candidates for this <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">OutlinedFunction</a></span>. <a href="#a0081f20622492dac85cd60d330e9673c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a370a7f9867fa70385aa4ff45c65e7">getOutliningCost</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bytes it would take to outline this function. <a href="#a28a370a7f9867fa70385aa4ff45c65e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e59c1ce14ba2a7dda9f3423b659d558">getNotOutlinedCost</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size in bytes of the unoutlined sequences. <a href="#a2e59c1ce14ba2a7dda9f3423b659d558">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b7d852cc4d557d60abf54e6c67badd6">getBenefit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of instructions that would be saved by outlining this function. <a href="#a2b7d852cc4d557d60abf54e6c67badd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa25ba2c1c77be50fed1cacfd48b91215">getNumInstrs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of instructions in this sequence. <a href="#aa25ba2c1c77be50fed1cacfd48b91215">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate">Candidate</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa7ed984d2671729752893984eb85a3">Candidates</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c6c3c632ddf4fca7933bd1d2617187e">MF</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The actual outlined function created. <a href="#a6c6c3c632ddf4fca7933bd1d2617187e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73db622d8cc649f5d3f7f3dbba5398d">SequenceSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents the size of a sequence in bytes. <a href="#ad73db622d8cc649f5d3f7f3dbba5398d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac55fb9b4653cc5d1f1247eb015db5ed5">FrameOverhead</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-defined overhead of constructing a frame for this function. <a href="#ac55fb9b4653cc5d1f1247eb015db5ed5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ee605247fd32b2a6981444fd996825">FrameConstructionID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-defined identifier for constructing a frame for this function. <a href="#a83ee605247fd32b2a6981444fd996825">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The information necessary to create an outlined function for some class of candidate.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OutlinedFunction() {#ac2f1c35acd04b812afdb550964c2eab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::outliner::OutlinedFunction::OutlinedFunction (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate">Candidate</a> &gt; &amp; Candidates, unsigned SequenceSize, unsigned FrameOverhead, unsigned FrameConstructionID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#afaa7ed984d2671729752893984eb85a3">Candidates</a>, <a href="#a83ee605247fd32b2a6981444fd996825">FrameConstructionID</a>, <a href="#ac55fb9b4653cc5d1f1247eb015db5ed5">FrameOverhead</a>, <a href="#a2b7d852cc4d557d60abf54e6c67badd6">getBenefit</a> and <a href="#ad73db622d8cc649f5d3f7f3dbba5398d">SequenceSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/outliner/globaloutlinedfunction/#a463e885d11330185cf612f79fce97b71">llvm::outliner::GlobalOutlinedFunction::GlobalOutlinedFunction</a>.</p>

</div>
</div>

### OutlinedFunction() {#a5833702b0fcc4f18c00c362e95dca6b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::outliner::OutlinedFunction::OutlinedFunction ()</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~OutlinedFunction() {#ae602839d12a4000e8c1a0d1db3d2865f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::outliner::OutlinedFunction::~OutlinedFunction ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBenefit() {#a2b7d852cc4d557d60abf54e6c67badd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::outliner::OutlinedFunction::getBenefit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of instructions that would be saved by outlining this function.</p>

<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>References <a href="#a2e59c1ce14ba2a7dda9f3423b659d558">getNotOutlinedCost</a> and <a href="#a28a370a7f9867fa70385aa4ff45c65e7">getOutliningCost</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a9f5104a534795f587fc2e9ec2e6a0c03">anonymous{MachineOutliner.cpp}::MachineOutliner::emitOutlinedFunctionRemark</a> and <a href="#ac2f1c35acd04b812afdb550964c2eab2">OutlinedFunction</a>.</p>

</div>
</div>

### getNotOutlinedCost() {#a2e59c1ce14ba2a7dda9f3423b659d558}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::outliner::OutlinedFunction::getNotOutlinedCost ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the size in bytes of the unoutlined sequences.</p>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>References <a href="#a0081f20622492dac85cd60d330e9673c">getOccurrenceCount</a> and <a href="#ad73db622d8cc649f5d3f7f3dbba5398d">SequenceSize</a>.</p>


<p>Referenced by <a href="#a2b7d852cc4d557d60abf54e6c67badd6">getBenefit</a>.</p>

</div>
</div>

### getNumInstrs() {#aa25ba2c1c77be50fed1cacfd48b91215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::outliner::OutlinedFunction::getNumInstrs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of instructions in this sequence.</p>

<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>Reference <a href="#afaa7ed984d2671729752893984eb85a3">Candidates</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a9f5104a534795f587fc2e9ec2e6a0c03">anonymous{MachineOutliner.cpp}::MachineOutliner::emitOutlinedFunctionRemark</a>.</p>

</div>
</div>

### getOccurrenceCount() {#a0081f20622492dac85cd60d330e9673c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::outliner::OutlinedFunction::getOccurrenceCount ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of candidates for this <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">OutlinedFunction</a></span>.</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>Reference <a href="#afaa7ed984d2671729752893984eb85a3">Candidates</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a9f5104a534795f587fc2e9ec2e6a0c03">anonymous{MachineOutliner.cpp}::MachineOutliner::emitOutlinedFunctionRemark</a> and <a href="#a2e59c1ce14ba2a7dda9f3423b659d558">getNotOutlinedCost</a>.</p>

</div>
</div>

### getOutliningCost() {#a28a370a7f9867fa70385aa4ff45c65e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::outliner::OutlinedFunction::getOutliningCost ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of bytes it would take to outline this function.</p>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#afaa7ed984d2671729752893984eb85a3">Candidates</a>, <a href="#ac55fb9b4653cc5d1f1247eb015db5ed5">FrameOverhead</a> and <a href="#ad73db622d8cc649f5d3f7f3dbba5398d">SequenceSize</a>.</p>


<p>Referenced by <a href="#a2b7d852cc4d557d60abf54e6c67badd6">getBenefit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Candidates {#afaa7ed984d2671729752893984eb85a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Candidate&gt; llvm::outliner::OutlinedFunction::Candidates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aee485429210d9273f05a2ffc2d1f38d6">llvm::ARMBaseInstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a9f5104a534795f587fc2e9ec2e6a0c03">anonymous{MachineOutliner.cpp}::MachineOutliner::emitOutlinedFunctionRemark</a>, <a href="#aa25ba2c1c77be50fed1cacfd48b91215">getNumInstrs</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/globaloutlinedfunction/#a8e17727ea30aa97903c1a0c5785ea444">llvm::outliner::GlobalOutlinedFunction::getOccurrenceCount</a>, <a href="#a0081f20622492dac85cd60d330e9673c">getOccurrenceCount</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/globaloutlinedfunction/#aaa2c81688be51a0d2f4836630470b7f6">llvm::outliner::GlobalOutlinedFunction::getOutliningCost</a>, <a href="#a28a370a7f9867fa70385aa4ff45c65e7">getOutliningCost</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a8ce342d09daa9a2d58bad8dad2018e33">anonymous{MachineOutliner.cpp}::MachineOutliner::getSubprogramOrNull</a> and <a href="#ac2f1c35acd04b812afdb550964c2eab2">OutlinedFunction</a>.</p>

</div>
</div>

### FrameConstructionID {#a83ee605247fd32b2a6981444fd996825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::outliner::OutlinedFunction::FrameConstructionID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-defined identifier for constructing a frame for this function.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9b0a622dbae74cb8a4b9b87a8b559b25">llvm::AArch64InstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aee485429210d9273f05a2ffc2d1f38d6">llvm::ARMBaseInstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aa0ee8a29120b044f4c4668626e264393">llvm::RISCVInstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aecce6c4ade64d8c1cda4d66a35f74aa4">llvm::X86InstrInfo::buildOutlinedFrame</a> and <a href="#ac2f1c35acd04b812afdb550964c2eab2">OutlinedFunction</a>.</p>

</div>
</div>

### FrameOverhead {#ac55fb9b4653cc5d1f1247eb015db5ed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::outliner::OutlinedFunction::FrameOverhead = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-defined overhead of constructing a frame for this function.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/outliner/globaloutlinedfunction/#aaa2c81688be51a0d2f4836630470b7f6">llvm::outliner::GlobalOutlinedFunction::getOutliningCost</a>, <a href="#a28a370a7f9867fa70385aa4ff45c65e7">getOutliningCost</a> and <a href="#ac2f1c35acd04b812afdb550964c2eab2">OutlinedFunction</a>.</p>

</div>
</div>

### MF {#a6c6c3c632ddf4fca7933bd1d2617187e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::outliner::OutlinedFunction::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The actual outlined function created.</p>


<p>This is initialized after we go through and create the actual function.</p>


<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a9f5104a534795f587fc2e9ec2e6a0c03">anonymous{MachineOutliner.cpp}::MachineOutliner::emitOutlinedFunctionRemark</a>.</p>

</div>
</div>

### SequenceSize {#ad73db622d8cc649f5d3f7f3dbba5398d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::outliner::OutlinedFunction::SequenceSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents the size of a sequence in bytes.</p>


<p>(Some instructions vary widely in size, so just counting the instructions isn't very useful.)</p>


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>Referenced by <a href="#a2e59c1ce14ba2a7dda9f3423b659d558">getNotOutlinedCost</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/globaloutlinedfunction/#aaa2c81688be51a0d2f4836630470b7f6">llvm::outliner::GlobalOutlinedFunction::getOutliningCost</a>, <a href="#a28a370a7f9867fa70385aa4ff45c65e7">getOutliningCost</a> and <a href="#ac2f1c35acd04b812afdb550964c2eab2">OutlinedFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
