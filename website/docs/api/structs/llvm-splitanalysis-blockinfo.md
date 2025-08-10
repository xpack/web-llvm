---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/splitanalysis/blockinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `BlockInfo` Struct

<p>Additional information about basic blocks where the current variable is live. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::SplitAnalysis::BlockInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">CodeGen/SplitKit.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a04f02eff679552af69729e22e8f1a2">isOneInstr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isOneInstr - Returns true when this <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo">BlockInfo</a> describes a single instruction. <a href="#a5a04f02eff679552af69729e22e8f1a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4bb4af61621d0136db231e398d23ff1">print</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca5dd3ea2419809d03649646c75d5ed4">dump</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d25ab70a5fda1310dad85ddb8ecaa22">MBB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc1d576ff2321f8f3a604808be1b6f5b">FirstInstr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>First instr accessing current reg. <a href="#afc1d576ff2321f8f3a604808be1b6f5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaae5e7f00635019260dd4d2506e2b58">LastInstr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Last instr accessing current reg. <a href="#abaae5e7f00635019260dd4d2506e2b58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ef80e68e8ebc6f8e778d811cc48f67f">FirstDef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>First non-phi valno-&gt;def, or SlotIndex(). <a href="#a2ef80e68e8ebc6f8e778d811cc48f67f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c7b9375634dd9b55f130ae4c428475c">LiveIn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current reg is live in. <a href="#a4c7b9375634dd9b55f130ae4c428475c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42e9b38c4f9bc0c0aca6f0c8c5cd1f80">LiveOut</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current reg is live out. <a href="#a42e9b38c4f9bc0c0aca6f0c8c5cd1f80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Additional information about basic blocks where the current variable is live.</p>


<p>Such a block will look like one of these templates:</p>


<ol class="doxyList" type="1">
<li>| o—x | Internal to block. Variable is only live in this block.</li>
<li>|—x | Live-in, kill.</li>
<li>| o—| Def, live-out.</li>
<li>|—x o—| Live-in, kill, def, live-out. Counted by NumGapBlocks.</li>
<li>|—o—o—| Live-through with uses or defs.</li>
<li>|--------—| Live-through without uses. Counted by NumThroughBlocks.</li>
</ol>

<p>Two <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo">BlockInfo</a> entries are created for template 4. One for the live-in segment, and one for the live-out segment. These entries look as if the block were split in the middle where the live range isn't live.</p>


<p>Live-through blocks without any uses don't get <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo">BlockInfo</a> entries. They are simply listed in ThroughBlocks instead.</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### dump() {#aca5dd3ea2419809d03649646c75d5ed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitAnalysis::BlockInfo::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1899 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>.</p>

</div>
</div>

### isOneInstr() {#a5a04f02eff679552af69729e22e8f1a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SplitAnalysis::BlockInfo::isOneInstr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isOneInstr - Returns true when this <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo">BlockInfo</a> describes a single instruction.</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>References <a href="#afc1d576ff2321f8f3a604808be1b6f5b">FirstInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a0b73244049319d841fd11a238f35b5d1">llvm::SlotIndex::isSameInstr</a> and <a href="#abaae5e7f00635019260dd4d2506e2b58">LastInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/splitanalysis/#af3bf010ee796ca57e04c495963fd49b7">llvm::SplitAnalysis::shouldSplitSingleBlock</a>.</p>

</div>
</div>

### print() {#ab4bb4af61621d0136db231e398d23ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitAnalysis::BlockInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1891 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="#a2ef80e68e8ebc6f8e778d811cc48f67f">FirstDef</a>, <a href="#afc1d576ff2321f8f3a604808be1b6f5b">FirstInstr</a>, <a href="#abaae5e7f00635019260dd4d2506e2b58">LastInstr</a>, <a href="#a4c7b9375634dd9b55f130ae4c428475c">LiveIn</a>, <a href="#a42e9b38c4f9bc0c0aca6f0c8c5cd1f80">LiveOut</a>, <a href="#a6d25ab70a5fda1310dad85ddb8ecaa22">MBB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FirstDef {#a2ef80e68e8ebc6f8e778d811cc48f67f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SplitAnalysis::BlockInfo::FirstDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>First non-phi valno-&gt;def, or SlotIndex().</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Referenced by <a href="#ab4bb4af61621d0136db231e398d23ff1">print</a>.</p>

</div>
</div>

### FirstInstr {#afc1d576ff2321f8f3a604808be1b6f5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SplitAnalysis::BlockInfo::FirstInstr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>First instr accessing current reg.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Referenced by <a href="#a5a04f02eff679552af69729e22e8f1a2">isOneInstr</a>, <a href="#ab4bb4af61621d0136db231e398d23ff1">print</a>, <a href="/web-llvm/docs/api/classes/llvm/splitanalysis/#af3bf010ee796ca57e04c495963fd49b7">llvm::SplitAnalysis::shouldSplitSingleBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a9d2296ecca42f33ce641b7341fde67d9">llvm::SplitEditor::splitRegInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8534c37f85077c1dd9fc3468f70d4618">llvm::SplitEditor::splitRegOutBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#ae5f72acf075c54b8f8ca8783a5683b63">llvm::SplitEditor::splitSingleBlock</a>.</p>

</div>
</div>

### LastInstr {#abaae5e7f00635019260dd4d2506e2b58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SplitAnalysis::BlockInfo::LastInstr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Last instr accessing current reg.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Referenced by <a href="#a5a04f02eff679552af69729e22e8f1a2">isOneInstr</a>, <a href="#ab4bb4af61621d0136db231e398d23ff1">print</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a9d2296ecca42f33ce641b7341fde67d9">llvm::SplitEditor::splitRegInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8534c37f85077c1dd9fc3468f70d4618">llvm::SplitEditor::splitRegOutBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#ae5f72acf075c54b8f8ca8783a5683b63">llvm::SplitEditor::splitSingleBlock</a>.</p>

</div>
</div>

### LiveIn {#a4c7b9375634dd9b55f130ae4c428475c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SplitAnalysis::BlockInfo::LiveIn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current reg is live in.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Referenced by <a href="#ab4bb4af61621d0136db231e398d23ff1">print</a>, <a href="/web-llvm/docs/api/classes/llvm/splitanalysis/#af3bf010ee796ca57e04c495963fd49b7">llvm::SplitAnalysis::shouldSplitSingleBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a9d2296ecca42f33ce641b7341fde67d9">llvm::SplitEditor::splitRegInBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8534c37f85077c1dd9fc3468f70d4618">llvm::SplitEditor::splitRegOutBlock</a>.</p>

</div>
</div>

### LiveOut {#a42e9b38c4f9bc0c0aca6f0c8c5cd1f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SplitAnalysis::BlockInfo::LiveOut</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current reg is live out.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Referenced by <a href="#ab4bb4af61621d0136db231e398d23ff1">print</a>, <a href="/web-llvm/docs/api/classes/llvm/splitanalysis/#af3bf010ee796ca57e04c495963fd49b7">llvm::SplitAnalysis::shouldSplitSingleBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a9d2296ecca42f33ce641b7341fde67d9">llvm::SplitEditor::splitRegInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8534c37f85077c1dd9fc3468f70d4618">llvm::SplitEditor::splitRegOutBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#ae5f72acf075c54b8f8ca8783a5683b63">llvm::SplitEditor::splitSingleBlock</a>.</p>

</div>
</div>

### MBB {#a6d25ab70a5fda1310dad85ddb8ecaa22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::SplitAnalysis::BlockInfo::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Referenced by <a href="#ab4bb4af61621d0136db231e398d23ff1">print</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a9d2296ecca42f33ce641b7341fde67d9">llvm::SplitEditor::splitRegInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8534c37f85077c1dd9fc3468f70d4618">llvm::SplitEditor::splitRegOutBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#ae5f72acf075c54b8f8ca8783a5683b63">llvm::SplitEditor::splitSingleBlock</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
