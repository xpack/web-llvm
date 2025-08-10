---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpregionblock
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VPRegionBlock` Class

<p><a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> represents a collection of VPBasicBlocks and VPRegionBlocks which form a Single-Entry-Single-Exiting subgraph of the output IR CFG. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPRegionBlock { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">Transforms/Vectorize/VPlan.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> is the building block of the Hierarchical Control-Flow Graph. <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7d3e451ebdc58b7a1ae06950281e6d4">VPlan</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf1dec79e91e7a45df50dd421115ffa2">VPRegionBlock</a> (VPBlockBase *Entry, VPBlockBase *Exiting, const std::string &amp;Name="", bool IsReplicator=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="/web-llvm/docs/api/classes/llvm/vplan/#a229a878bb15506314b99639e3d6dca41">VPlan::createVPRegionBlock</a> to create VPRegionBlocks. <a href="#abf1dec79e91e7a45df50dd421115ffa2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6652afba0448f86136d493f82eafb1">VPRegionBlock</a> (const std::string &amp;Name="", bool IsReplicator=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee4df15508229a84ef9d102bd71e83a3">~VPRegionBlock</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae2cb3c63b4d67324ddc947fb9696fc">getEntry</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2eff5aca291e3185f5e8c2b1bd350ec">getEntry</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9798204f943ee8fc7c6efd2ab0f7c3d6">setEntry</a> (VPBlockBase *EntryBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set <span class="doxyComputerOutput">EntryBlock</span> as the entry <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> of this <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a>. <a href="#a9798204f943ee8fc7c6efd2ab0f7c3d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add3be1d1d9e5b1ee2014c32d21bf2b5b">getExiting</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a431480e4d503947a4dd06763a2b7e705">getExiting</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a414a617643992b9d0e5b70df5fd423d5">setExiting</a> (VPBlockBase *ExitingBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set <span class="doxyComputerOutput">ExitingBlock</span> as the exiting <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> of this <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a>. <a href="#a414a617643992b9d0e5b70df5fd423d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae74f6f8bac76399d081c42c4a216c2af">getPreheaderVPBB</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the pre-header <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> of the loop region. <a href="#ae74f6f8bac76399d081c42c4a216c2af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24555c6ed92715d80348f0991a6d55df">isReplicator</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An indicator whether this region is to generate multiple replicated instances of output IR corresponding to its VPBlockBases. <a href="#a24555c6ed92715d80348f0991a6d55df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac503442fd011b1b4a03ab40ad3f9402e">execute</a> (VPTransformState *State) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The method which generates the output IR instructions that correspond to this <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a>, thereby "executing" the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#ac503442fd011b1b4a03ab40ad3f9402e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa948ba905ff37c533b3c85068f94fd24">cost</a> (ElementCount VF, VPCostContext &amp;Ctx) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of the block. <a href="#aa948ba905ff37c533b3c85068f94fd24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02924e690f0a12f4b58c4e40e4ead42">print</a> (raw_ostream &amp;O, const Twine &amp;Indent, VPSlotTracker &amp;SlotTracker) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> to <span class="doxyComputerOutput">O</span> (recursively), prefixing all lines with <span class="doxyComputerOutput">Indent</span>. <a href="#ab02924e690f0a12f4b58c4e40e4ead42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0001ec4686be34ad7e56cb0798bef1b0">clone</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone all blocks in the single-entry single-exit region of the block and their recipes without updating the operands of the cloned recipes. <a href="#a0001ec4686be34ad7e56cb0798bef1b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f26339b06942e3219569b4c5b738495">print</a> (raw_ostream &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print plain-text dump of this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> to <span class="doxyComputerOutput">O</span>. <a href="#a5f26339b06942e3219569b4c5b738495">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a378251ec617b13ba9b81c2d0e0acffda">Entry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hold the Single Entry of the SESE region modelled by the <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a>. <a href="#a378251ec617b13ba9b81c2d0e0acffda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36cacdca7416e9ce1ce69a3b424ab172">Exiting</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hold the Single Exiting block of the SESE region modelled by the <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a>. <a href="#a36cacdca7416e9ce1ce69a3b424ab172">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abef4154d73ece13816610dc0344d5139">IsReplicator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An indicator whether this region is to generate multiple replicated instances of output IR corresponding to its VPBlockBases. <a href="#abef4154d73ece13816610dc0344d5139">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe5f86d6b56efdddce5ca7baaf5d417b">classof</a> (const VPBlockBase *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method to support type inquiry through isa, cast, and dyn_cast. <a href="#afe5f86d6b56efdddce5ca7baaf5d417b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> represents a collection of VPBasicBlocks and VPRegionBlocks which form a Single-Entry-Single-Exiting subgraph of the output IR CFG.</p>


<p>A <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> may indicate that its contents are to be replicated several times. This is designed to support predicated scalarization, in which a scalar if-then code structure needs to be generated VF * UF times. Having this replication indicator helps to keep a single model for multiple candidate VF's. The actual replication takes place only once the desired VF and UF have been determined.</p>


<p>Definition at line 3716 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Friends

### VPlan {#af7d3e451ebdc58b7a1ae06950281e6d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 3717 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad435a0e2dd67fef67f3169c288480063">llvm::VPBlockBase::VPBlockBase</a> and <a href="#af7d3e451ebdc58b7a1ae06950281e6d4">VPlan</a>.</p>


<p>Referenced by <a href="#af7d3e451ebdc58b7a1ae06950281e6d4">VPlan</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### VPRegionBlock() {#abf1dec79e91e7a45df50dd421115ffa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPRegionBlock::VPRegionBlock (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * Entry, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * Exiting, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name="", bool IsReplicator=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="/web-llvm/docs/api/classes/llvm/vplan/#a229a878bb15506314b99639e3d6dca41">VPlan::createVPRegionBlock</a> to create VPRegionBlocks.</p>

<p>Definition at line 3731 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### VPRegionBlock() {#abe6652afba0448f86136d493f82eafb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPRegionBlock::VPRegionBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name="", bool IsReplicator=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3740 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VPRegionBlock() {#aee4df15508229a84ef9d102bd71e83a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPRegionBlock::~VPRegionBlock ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3745 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#a0001ec4686be34ad7e56cb0798bef1b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPRegionBlock * VPRegionBlock::clone ()</td>
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

<p>Clone all blocks in the single-entry single-exit region of the block and their recipes without updating the operands of the cloned recipes.</p>

<p>Declaration at line 3807 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 701 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#ac1ac18b9f807acbc9846d923ea874524">cloneFrom</a>, <a href="#a1ae2cb3c63b4d67324ddc947fb9696fc">getEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a8d57e2fe646928a51e97714005eefdc7">llvm::VPBlockBase::getPlan</a>, <a href="#a24555c6ed92715d80348f0991a6d55df">isReplicator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4474bfb1e0ca062e5bfe2a35980e7d19">llvm::vp_depth_first_shallow</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad435a0e2dd67fef67f3169c288480063">llvm::VPBlockBase::VPBlockBase</a>.</p>

</div>
</div>

### cost() {#aa948ba905ff37c533b3c85068f94fd24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost VPRegionBlock::cost (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; Ctx)</td>
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

<p>Return the cost of the block.</p>

<p>Declaration at line 3791 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a5eae6074e6a1bb62e365ef65f3e26196">ForceTargetInstructionCost</a>, <a href="#a1ae2cb3c63b4d67324ddc947fb9696fc">getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a57207993e2fe6ec98912e8072e4600bc">llvm::InstructionCost::getInvalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb5d7cdf62c5d24e421899cd74c4550d">llvm::getReciprocalPredBlockProb</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aeccf6a036968755c6d86e2d2bb17673a">llvm::VPBlockBase::getSuccessors</a>, <a href="#a24555c6ed92715d80348f0991a6d55df">isReplicator</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#adeaf44a788c3e001582a71790894b78d">llvm::VPTransformState::VF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4474bfb1e0ca062e5bfe2a35980e7d19">llvm::vp_depth_first_shallow</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad435a0e2dd67fef67f3169c288480063">llvm::VPBlockBase::VPBlockBase</a>.</p>

</div>
</div>

### execute() {#ac503442fd011b1b4a03ab40ad3f9402e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRegionBlock::execute (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> * State)</td>
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

<p>The method which generates the output IR instructions that correspond to this <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a>, thereby "executing" the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>

<p>Declaration at line 3788 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a990a86b0de7a84a9f489d2034878e330">llvm::LoopBase&lt; BlockT, LoopT &gt;::addChildLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vplane/#afb4648a83781e7ee62f34771ea338c29a7fb55ed0b7a30342ba6da306428cae04">llvm::VPLane::First</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#ae74f6f8bac76399d081c42c4a216c2af">getPreheaderVPBB</a>, <a href="#a24555c6ed92715d80348f0991a6d55df">isReplicator</a>, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#a96b2bb4032a684ffc2081371a58c3036">llvm::VPTransformState::Lane</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#adeaf44a788c3e001582a71790894b78d">llvm::VPTransformState::VF</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad435a0e2dd67fef67f3169c288480063">llvm::VPBlockBase::VPBlockBase</a>.</p>

</div>
</div>

### getEntry() {#a1ae2cb3c63b4d67324ddc947fb9696fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPBlockBase * llvm::VPRegionBlock::getEntry ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3752 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad435a0e2dd67fef67f3169c288480063">llvm::VPBlockBase::VPBlockBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae64d6953a1334207d9e7d9cd2587ee9f">llvm::VPlanTransforms::adjustFixedOrderRecurrences</a>, <a href="#a0001ec4686be34ad7e56cb0798bef1b0">clone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62219a4c97e27d64593245e4e9187cd1">llvm::collectEphemeralRecipesForVPlan</a>, <a href="#aa948ba905ff37c533b3c85068f94fd24">cost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp/#a85f42ae734efbd570ae873ab9aa8edc0">isHeaderVPBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#afd081c92500bd333555e7bd6102b4d3e">licm</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a696283c30308704d020a9d86065aa3ae">planContainsAdditionalSimplifications</a>, <a href="/web-llvm/docs/api/classes/anonymous-vplanunroll-cpp-/unrollstate/#a9965cb8e010ad82f02434a0762cddf1e">anonymous{VPlanUnroll.cpp}::UnrollState::unrollBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-vplanverifier-cpp-/vplanverifier/#a4140274aee97c60c4a26d1ecd4234a78">anonymous{VPlanVerifier.cpp}::VPlanVerifier::verify</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af378bb1e037306d9cfd4bb0b49ba55f9">willGenerateVectors</a>.</p>

</div>
</div>

### getEntry() {#ae2eff5aca291e3185f5e8c2b1bd350ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlockBase * llvm::VPRegionBlock::getEntry ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3753 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad435a0e2dd67fef67f3169c288480063">llvm::VPBlockBase::VPBlockBase</a>.</p>

</div>
</div>

### getExiting() {#add3be1d1d9e5b1ee2014c32d21bf2b5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPBlockBase * llvm::VPRegionBlock::getExiting ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3764 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad435a0e2dd67fef67f3169c288480063">llvm::VPBlockBase::VPBlockBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a36d6728b8c3cfca0a9bd02c3f0273477">llvm::LoopVectorizationPlanner::buildVPlans</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a> and <a href="/web-llvm/docs/api/classes/anonymous-vplanverifier-cpp-/vplanverifier/#a4140274aee97c60c4a26d1ecd4234a78">anonymous{VPlanVerifier.cpp}::VPlanVerifier::verify</a>.</p>

</div>
</div>

### getExiting() {#a431480e4d503947a4dd06763a2b7e705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlockBase * llvm::VPRegionBlock::getExiting ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3765 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad435a0e2dd67fef67f3169c288480063">llvm::VPBlockBase::VPBlockBase</a>.</p>

</div>
</div>

### getPreheaderVPBB() {#ae74f6f8bac76399d081c42c4a216c2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock * llvm::VPRegionBlock::getPreheaderVPBB ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the pre-header <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> of the loop region.</p>

<p>Definition at line 3777 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a28da654f916bf44da5513b6f1788835c">llvm::VPBlockBase::getExitingBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aa1bb4808c7a5db9f8ed3f479c78c4b5e">llvm::VPBlockBase::getSinglePredecessor</a> and <a href="#a24555c6ed92715d80348f0991a6d55df">isReplicator</a>.</p>


<p>Referenced by <a href="#ac503442fd011b1b4a03ab40ad3f9402e">execute</a> and <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/cfgstate/#aabeafaaaee1bdb12f5e2aeac9a1c2c32">llvm::VPTransformState::CFGState::getPreheaderBBFor</a>.</p>

</div>
</div>

### isReplicator() {#a24555c6ed92715d80348f0991a6d55df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPRegionBlock::isReplicator ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An indicator whether this region is to generate multiple replicated instances of output IR corresponding to its VPBlockBases.</p>

<p>Definition at line 3784 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a0001ec4686be34ad7e56cb0798bef1b0">clone</a>, <a href="#aa948ba905ff37c533b3c85068f94fd24">cost</a>, <a href="#ac503442fd011b1b4a03ab40ad3f9402e">execute</a>, <a href="#ae74f6f8bac76399d081c42c4a216c2af">getPreheaderVPBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#a8bc6161a466df7dcd1b7bcf8661e667a">hasConditionalTerminator</a>, <a href="#ab02924e690f0a12f4b58c4e40e4ead42">print</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a4690286163882c35068b1908f4d752fd">llvm::InnerLoopVectorizer::scalarizeInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-vplanunroll-cpp-/unrollstate/#a9965cb8e010ad82f02434a0762cddf1e">anonymous{VPlanUnroll.cpp}::UnrollState::unrollBlock</a>.</p>

</div>
</div>

### print() {#ab02924e690f0a12f4b58c4e40e4ead42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRegionBlock::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Indent, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; SlotTracker)</td>
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

<p>Print this <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> to <span class="doxyComputerOutput">O</span> (recursively), prefixing all lines with <span class="doxyComputerOutput">Indent</span>.</p>


<p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a></span> is used to print unnamed <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>'s using consequtive numbers.</p>


<p>Note that the numbering is applied to the whole <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>, so printing individual regions is consistent with the whole <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> printing.</p>


<p>Declaration at line 3800 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="#a24555c6ed92715d80348f0991a6d55df">isReplicator</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a44ac4d968960d46c6c4d93cb35369b39">llvm::VPBlockBase::printSuccessors</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4474bfb1e0ca062e5bfe2a35980e7d19">llvm::vp_depth_first_shallow</a>.</p>

</div>
</div>

### print() {#a5f26339b06942e3219569b4c5b738495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBlockBase::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print plain-text dump of this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> to <span class="doxyComputerOutput">O</span>.</p>

<p>Definition at line 3802 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### setEntry() {#a9798204f943ee8fc7c6efd2ab0f7c3d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPRegionBlock::setEntry (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * EntryBlock)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set <span class="doxyComputerOutput">EntryBlock</span> as the entry <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> of this <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a>.</p>


<p><span class="doxyComputerOutput">EntryBlock</span> must have no predecessors.</p>


<p>Definition at line 3757 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a73370de0db181ec55a9ad0b7a3a78a88">llvm::VPBlockBase::getPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ae2be49bdbbda0aeadd51549f4b88c839">llvm::VPBlockBase::setParent</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad435a0e2dd67fef67f3169c288480063">llvm::VPBlockBase::VPBlockBase</a>.</p>

</div>
</div>

### setExiting() {#a414a617643992b9d0e5b70df5fd423d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPRegionBlock::setExiting (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * ExitingBlock)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set <span class="doxyComputerOutput">ExitingBlock</span> as the exiting <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> of this <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a>.</p>


<p><span class="doxyComputerOutput">ExitingBlock</span> must have no successors.</p>


<p>Definition at line 3769 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aeccf6a036968755c6d86e2d2bb17673a">llvm::VPBlockBase::getSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ae2be49bdbbda0aeadd51549f4b88c839">llvm::VPBlockBase::setParent</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad435a0e2dd67fef67f3169c288480063">llvm::VPBlockBase::VPBlockBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Entry {#a378251ec617b13ba9b81c2d0e0acffda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlockBase* llvm::VPRegionBlock::Entry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hold the Single Entry of the SESE region modelled by the <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a>.</p>

<p>Definition at line 3720 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### Exiting {#a36cacdca7416e9ce1ce69a3b424ab172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlockBase* llvm::VPRegionBlock::Exiting</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hold the Single Exiting block of the SESE region modelled by the <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a>.</p>

<p>Definition at line 3724 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### IsReplicator {#abef4154d73ece13816610dc0344d5139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPRegionBlock::IsReplicator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An indicator whether this region is to generate multiple replicated instances of output IR corresponding to its VPBlockBases.</p>

<p>Definition at line 3728 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#afe5f86d6b56efdddce5ca7baaf5d417b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPRegionBlock::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Method to support type inquiry through isa, cast, and dyn_cast.</p>

<p>Definition at line 3748 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad435a0e2dd67fef67f3169c288480063">llvm::VPBlockBase::VPBlockBase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
