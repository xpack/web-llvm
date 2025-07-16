---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/inorderissuestage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InOrderIssueStage` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::mca::InOrderIssueStage { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">llvm/MCA/Stages/InOrderIssueStage.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/stage">Stage</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab032f0ebf00aa77e5f430f5ec138cfb">InOrderIssueStage</a> (const MCSubtargetInfo &amp;STI, RegisterFile &amp;PRF, CustomBehaviour &amp;CB, LSUnitBase &amp;LSU)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c3b7b1bb68372adde8f0fe1b9b468a6">InOrderIssueStage</a> (const InOrderIssueStage &amp;Other)=delete</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/inorderissuestage">InOrderIssueStage</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92cd69726a57d7d3546eeb348dbf0e05">operator=</a> (const InOrderIssueStage &amp;Other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2bc80562a7d93ee7b0503f737bd57ab">getIssueWidth</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e67f693cb5334c23fbe575f055915a1">isAvailable</a> (const InstRef &amp;) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it can execute IR during this cycle. <a href="#a9e67f693cb5334c23fbe575f055915a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1089fc00ab39688bad5f3d0ae77c25a8">hasWorkToComplete</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if some instructions are still executing this stage. <a href="#a1089fc00ab39688bad5f3d0ae77c25a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de83f23b94fb81affc3528986eb9971">execute</a> (InstRef &amp;IR) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The primary action that this stage performs on instruction IR. <a href="#a8de83f23b94fb81affc3528986eb9971">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab18add1ebf835902d6a2dd4feaa80719">cycleStart</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called once at the start of each cycle. <a href="#ab18add1ebf835902d6a2dd4feaa80719">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1de1c3d02dec8939b72fe567b4c0b715">cycleEnd</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called once at the end of each cycle. <a href="#a1de1c3d02dec8939b72fe567b4c0b715">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca2ce603320d6244e3b3bd67c348306">canExecute</a> (const InstRef &amp;IR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if IR can execute during this cycle. <a href="#a6ca2ce603320d6244e3b3bd67c348306">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977d5c71aadebe4e14fe2936f0cc4ca7">tryIssue</a> (InstRef &amp;IR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Issue the instruction, or update the <a href="/web-llvm/docs/api/structs/llvm/mca/stallinfo">StallInfo</a>. <a href="#a977d5c71aadebe4e14fe2936f0cc4ca7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd5345995e26c7238f4bc6af4b741944">updateIssuedInst</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update status of instructions from IssuedInst. <a href="#abd5345995e26c7238f4bc6af4b741944">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60cdb423a178c29c6c1379951e6f39f4">updateCarriedOver</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Continue to issue the CarriedOver instruction. <a href="#a60cdb423a178c29c6c1379951e6f39f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53331b4f9463ab3af50a3103cdaba44">notifyStallEvent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notifies a stall event to the <a href="/web-llvm/docs/api/classes/llvm/mca/stage">Stage</a> listener. <a href="#ac53331b4f9463ab3af50a3103cdaba44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6525b513c39006ff1f059a680b2574">notifyInstructionIssued</a> (const InstRef &amp;IR, ArrayRef&lt; ResourceUse &gt; UsedRes)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a902906d84c27596529ca4ad45882ed0d">notifyInstructionDispatched</a> (const InstRef &amp;IR, unsigned Ops, ArrayRef&lt; unsigned &gt; UsedRegs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a049f98696142a5836b8833004be0de17">notifyInstructionExecuted</a> (const InstRef &amp;IR)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfb717b3caed2bf52298bd3251b13684">notifyInstructionRetired</a> (const InstRef &amp;IR, ArrayRef&lt; unsigned &gt; FreedRegs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fc09aa9b44d155a5d391a07bd883bd5">retireInstruction</a> (InstRef &amp;IR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retire instruction once it is executed. <a href="#a8fc09aa9b44d155a5d391a07bd883bd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ed054a5329b042aeeaa45a598c01f1d">STI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/registerfile">RegisterFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24e1f2ace88a9f56f6cfddd75388eef">PRF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager">ResourceManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f688d03f8d2b3f883da5fd1bf2b9ad9">RM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour">CustomBehaviour</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ddbd1c37b7d6d04bc99895838fdfef">CB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase">LSUnitBase</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad03c944eecc228378d3544582f00846a">LSU</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0851f98e2b559e80762532d05510d71">IssuedInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instructions that were issued, but not executed yet. <a href="#ab0851f98e2b559e80762532d05510d71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad43b727e42ce7190b692cee4904f0ea2">NumIssued</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of instructions issued in the current cycle. <a href="#ad43b727e42ce7190b692cee4904f0ea2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mca/stallinfo">StallInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4675df8b1cbc70d5adb22ce4fcd3a03a">SI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b23ba5292009f11cbe2f98a3227554e">CarriedOver</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mca/instruction">Instruction</a> that is issued in more than 1 cycle. <a href="#a3b23ba5292009f11cbe2f98a3227554e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f893ec0f3f407239d7adc9a6f2a5d7b">CarryOver</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of CarriedOver uops left to issue. <a href="#a7f893ec0f3f407239d7adc9a6f2a5d7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43a81ead337d71495aaacc9254dd5904">Bandwidth</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of instructions that can be issued in the current cycle. <a href="#a43a81ead337d71495aaacc9254dd5904">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cdcbbd75253a255129f83b97feba6b1">LastWriteBackCycle</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of cycles (counted from the current cycle) until the last write is committed. <a href="#a1cdcbbd75253a255129f83b97feba6b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InOrderIssueStage() {#aab032f0ebf00aa77e5f430f5ec138cfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::InOrderIssueStage::InOrderIssueStage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile">RegisterFile</a> &amp; PRF, <a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour">CustomBehaviour</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase">LSUnitBase</a> &amp; LSU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### InOrderIssueStage() {#a1c3b7b1bb68372adde8f0fe1b9b468a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::InOrderIssueStage::InOrderIssueStage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/inorderissuestage">InOrderIssueStage</a> &amp; Other)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#a92cd69726a57d7d3546eeb348dbf0e05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InOrderIssueStage &amp; llvm::mca::InOrderIssueStage::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/inorderissuestage">InOrderIssueStage</a> &amp; Other)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cycleEnd() {#a1de1c3d02dec8939b72fe567b4c0b715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error llvm::mca::InOrderIssueStage::cycleEnd ()</td>
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

<p>Called once at the end of each cycle.</p>

<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>

</div>
</div>

### cycleStart() {#ab18add1ebf835902d6a2dd4feaa80719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error llvm::mca::InOrderIssueStage::cycleStart ()</td>
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

<p>Called once at the start of each cycle.</p>


<p>This can be used as a setup phase to prepare for the executions during the cycle.</p>


<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#aa2bc80562a7d93ee7b0503f737bd57ab">getIssueWidth</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>

</div>
</div>

### execute() {#a8de83f23b94fb81affc3528986eb9971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error llvm::mca::InOrderIssueStage::execute (<a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
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

<p>The primary action that this stage performs on instruction IR.</p>

<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a67c179f1b0e96ef53a03966e4ee831fe">llvm::mca::InstructionBase::isMemOp</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/instruction/#abb66d9fd67e0ee7d09dec5b097683144">llvm::mca::Instruction::setLSUTokenID</a>.</p>

</div>
</div>

### getIssueWidth() {#aa2bc80562a7d93ee7b0503f737bd57ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::InOrderIssueStage::getIssueWidth ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>


<p>Referenced by <a href="#ab18add1ebf835902d6a2dd4feaa80719">cycleStart</a> and <a href="#a9e67f693cb5334c23fbe575f055915a1">isAvailable</a>.</p>

</div>
</div>

### hasWorkToComplete() {#a1089fc00ab39688bad5f3d0ae77c25a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::InOrderIssueStage::hasWorkToComplete ()</td>
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

<p>Returns true if some instructions are still executing this stage.</p>

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>

</div>
</div>

### isAvailable() {#a9e67f693cb5334c23fbe575f055915a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::InOrderIssueStage::isAvailable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
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

<p>Returns true if it can execute IR during this cycle.</p>

<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a8d8cf9187cd695bf101c7f481f528305">llvm::mca::InstructionBase::getBeginGroup</a>, <a href="#aa2bc80562a7d93ee7b0503f737bd57ab">getIssueWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a4087002e3862771c1973a3df268c97d3">llvm::mca::InstructionBase::getNumMicroOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canExecute() {#a6ca2ce603320d6244e3b3bd67c348306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::InOrderIssueStage::canExecute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if IR can execute during this cycle.</p>


<p>In case of stall, it updates <a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a> with information about the stalled instruction and the stall reason.</p>


<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>

</div>
</div>

### notifyInstructionDispatched() {#a902906d84c27596529ca4ad45882ed0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::InOrderIssueStage::notifyInstructionDispatched (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR, unsigned Ops, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; UsedRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>

</div>
</div>

### notifyInstructionExecuted() {#a049f98696142a5836b8833004be0de17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::InOrderIssueStage::notifyInstructionExecuted (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>

</div>
</div>

### notifyInstructionIssued() {#a2a6525b513c39006ff1f059a680b2574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::InOrderIssueStage::notifyInstructionIssued (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ab534e0b15e46245fd0eb31e7e7c2e863">ResourceUse</a> &gt; UsedRes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>

</div>
</div>

### notifyInstructionRetired() {#adfb717b3caed2bf52298bd3251b13684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::InOrderIssueStage::notifyInstructionRetired (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; FreedRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>

</div>
</div>

### notifyStallEvent() {#ac53331b4f9463ab3af50a3103cdaba44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::InOrderIssueStage::notifyStallEvent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Notifies a stall event to the <a href="/web-llvm/docs/api/classes/llvm/mca/stage">Stage</a> listener.</p>


<p>Stall information is obtained from the internal <a href="/web-llvm/docs/api/structs/llvm/mca/stallinfo">StallInfo</a> field.</p>


<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>

</div>
</div>

### retireInstruction() {#a8fc09aa9b44d155a5d391a07bd883bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::InOrderIssueStage::retireInstruction (<a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retire instruction once it is executed.</p>

<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>

</div>
</div>

### tryIssue() {#a977d5c71aadebe4e14fe2936f0cc4ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error llvm::mca::InOrderIssueStage::tryIssue (<a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Issue the instruction, or update the <a href="/web-llvm/docs/api/structs/llvm/mca/stallinfo">StallInfo</a>.</p>

<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>

</div>
</div>

### updateCarriedOver() {#a60cdb423a178c29c6c1379951e6f39f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::InOrderIssueStage::updateCarriedOver ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Continue to issue the CarriedOver instruction.</p>

<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>

</div>
</div>

### updateIssuedInst() {#abd5345995e26c7238f4bc6af4b741944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::InOrderIssueStage::updateIssuedInst ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update status of instructions from IssuedInst.</p>

<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Bandwidth {#a43a81ead337d71495aaacc9254dd5904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::InOrderIssueStage::Bandwidth</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of instructions that can be issued in the current cycle.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

### CarriedOver {#a3b23ba5292009f11cbe2f98a3227554e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstRef llvm::mca::InOrderIssueStage::CarriedOver</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/mca/instruction">Instruction</a> that is issued in more than 1 cycle.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

### CarryOver {#a7f893ec0f3f407239d7adc9a6f2a5d7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::InOrderIssueStage::CarryOver</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of CarriedOver uops left to issue.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

### CB {#a54ddbd1c37b7d6d04bc99895838fdfef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CustomBehaviour&amp; llvm::mca::InOrderIssueStage::CB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

### IssuedInst {#ab0851f98e2b559e80762532d05510d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;InstRef, 4&gt; llvm::mca::InOrderIssueStage::IssuedInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Instructions that were issued, but not executed yet.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

### LastWriteBackCycle {#a1cdcbbd75253a255129f83b97feba6b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::InOrderIssueStage::LastWriteBackCycle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of cycles (counted from the current cycle) until the last write is committed.</p>


<p>This is taken into account to ensure that writes commit in the program order.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

### LSU {#ad03c944eecc228378d3544582f00846a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LSUnitBase&amp; llvm::mca::InOrderIssueStage::LSU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

### NumIssued {#ad43b727e42ce7190b692cee4904f0ea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::InOrderIssueStage::NumIssued</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of instructions issued in the current cycle.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

### PRF {#af24e1f2ace88a9f56f6cfddd75388eef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterFile&amp; llvm::mca::InOrderIssueStage::PRF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

### RM {#a7f688d03f8d2b3f883da5fd1bf2b9ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceManager llvm::mca::InOrderIssueStage::RM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

### SI {#a4675df8b1cbc70d5adb22ce4fcd3a03a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StallInfo llvm::mca::InOrderIssueStage::SI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

### STI {#a3ed054a5329b042aeeaa45a598c01f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo&amp; llvm::mca::InOrderIssueStage::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/stages/inorderissuestage-h">InOrderIssueStage.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/stages/inorderissuestage-cpp">InOrderIssueStage.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
