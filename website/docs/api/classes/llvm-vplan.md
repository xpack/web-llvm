---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vplan
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VPlan` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> models a candidate for vectorization, encoding various decisions take to produce efficient output IR, including which branches, basic-blocks and output IR instructions to generate, and their cost. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPlan { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">Transforms/Vectorize/VPlan.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f9947d030a2675aa107469350c5d72">VPlanPrinter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ceea61a3de5b2f0ff70850f66c5fdc">VPSlotTracker</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e5cbede99134e89b34efded77cd3c4e">VPlan</a> (Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> for <span class="doxyComputerOutput">L</span>. <a href="#a9e5cbede99134e89b34efded77cd3c4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c68cb3d20000fcb178a8f0eb6454cfc">VPlan</a> (BasicBlock *ScalarHeaderBB, VPValue *TC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> with a new <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> as entry, a <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> wrapping <span class="doxyComputerOutput">ScalarHeaderBB</span> and a trip count of <span class="doxyComputerOutput">TC</span>. <a href="#a3c68cb3d20000fcb178a8f0eb6454cfc">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c7a498b8f88b2c448c1b88e1e2c4f75">VPlan</a> (VPBasicBlock *Entry, VPIRBasicBlock *ScalarHeader)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> with <span class="doxyComputerOutput">Entry</span> to the plan and with <span class="doxyComputerOutput">ScalarHeader</span> wrapping the original header of the scalar loop. <a href="#a6c7a498b8f88b2c448c1b88e1e2c4f75">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433f41155026be9f8f6fa880554286a9">~VPlan</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f311a1a101ba9ebbdafb31a67942b69">setEntry</a> (VPBasicBlock *VPBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a143bc5faeb35f7363570e97bccf76e53">prepareToExecute</a> (Value *TripCount, Value *VectorTripCount, VPTransformState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepare the plan for execution, setting up the required live-in values. <a href="#a143bc5faeb35f7363570e97bccf76e53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad80b94848142a7c633976aff96d4c408">execute</a> (VPTransformState *State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the IR code for this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#ad80b94848142a7c633976aff96d4c408">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d2ce995a1feaa7a65ff40f77f073db3">cost</a> (ElementCount VF, VPCostContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of this plan. <a href="#a8d2ce995a1feaa7a65ff40f77f073db3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c868dfd250ff9592c06dd61a7fb0bcf">getEntry</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a479b833fd70361a9b1bb9cb9f8a2e3ad">getEntry</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee894572833ce02ad06c067d44f65b48">getVectorPreheader</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the preheader of the vector loop region, if one exists, or null otherwise. <a href="#aee894572833ce02ad06c067d44f65b48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89f94c49b2cb5daaa93d19c89307c307">getVectorLoopRegion</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> of the vector loop. <a href="#a89f94c49b2cb5daaa93d19c89307c307">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af19b220ce9ea956afca867699a0581df">getVectorLoopRegion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a995b2a034ffc26dcd2f3a679f9d2feea">getMiddleBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the 'middle' block of the plan, that is the block that selects whether to execute the scalar tail loop or the exit block from the loop latch. <a href="#a995b2a034ffc26dcd2f3a679f9d2feea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cbce97074fc9cc4c7bc027adcf560af">getMiddleBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5f29ccf71b0494fc179323427eb1e11">getScalarPreheader</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> for the preheader of the scalar loop. <a href="#ad5f29ccf71b0494fc179323427eb1e11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56a6505c6bfa319e686fc23acd52495">getScalarHeader</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> wrapping the header of the scalar loop. <a href="#ae56a6505c6bfa319e686fc23acd52495">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85800ca7a821f540ad2d6d4d3c2d4208">getExitBlocks</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator range over the <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> wrapping the exit blocks of the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>, that is leaf nodes except the scalar header. <a href="#a85800ca7a821f540ad2d6d4d3c2d4208">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f5fc19caa67daeca8a1316c7e055e3c">getTripCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The trip count of the original loop. <a href="#a2f5fc19caa67daeca8a1316c7e055e3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bb77d906fd1ae7e241f0c95dcba094b">resetTripCount</a> (VPValue *NewTripCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resets the trip count for the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#a9bb77d906fd1ae7e241f0c95dcba094b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3732ef393569af17c44c36f4e22f2854">getOrCreateBackedgeTakenCount</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The backedge taken count of the original loop. <a href="#a3732ef393569af17c44c36f4e22f2854">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a233848f0bf7aef1aca22e6172e5d900d">getVectorTripCount</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The vector trip count. <a href="#a233848f0bf7aef1aca22e6172e5d900d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dffed680cc551f7ac6d92b3cd365d11">getVF</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the VF of the vector loop region. <a href="#a2dffed680cc551f7ac6d92b3cd365d11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d53ff30dd2a706e91c30d4f50982e3d">getVFxUF</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns VF * UF of the vector loop region. <a href="#a2d53ff30dd2a706e91c30d4f50982e3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2c6a16b2209e1709ee483b22b260849">addVF</a> (ElementCount VF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee6ab8541efab3e456a38d6c1fa1be2">setVF</a> (ElementCount VF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a633dd97e642c10e8aa1dff2bd2874edb">hasVF</a> (ElementCount VF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b96ac619241bd2248a355af718a192">hasScalableVF</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a>, 2 &gt;::iterator &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aac2593ea2eaac537de30053e8e05fd">vectorFactors</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator range over all VFs of the plan. <a href="#a3aac2593ea2eaac537de30053e8e05fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad30bf062f18fd6e56e36bfecefbbb386">hasScalarVFOnly</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e9c2a69cd9bc0e46626f5302a03d3da">hasUF</a> (unsigned UF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a532045d23e6f3efd21732fd342f99f09">getUF</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d539e508015e09e4b9fdb7d020da0e">setUF</a> (unsigned UF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13c80757c166e2959462fa447ed39649">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a string with the name of the plan and the applicable VFs and UFs. <a href="#a13c80757c166e2959462fa447ed39649">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a242fb01fcd9fab0be0f487b67fd94a0a">setName</a> (const Twine &amp;newName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac38d49d70b5f78779e83abdf4dcb4be0">getOrAddLiveIn</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the live-in <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> for <span class="doxyComputerOutput">V</span> or adds a new live-in (if none exists yet) for <span class="doxyComputerOutput">V</span>. <a href="#ac38d49d70b5f78779e83abdf4dcb4be0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae955de4cebaa654363ab0188e24ec19d">getLiveIn</a> (Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the live-in <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> for <span class="doxyComputerOutput">V</span>, if there is one or nullptr otherwise. <a href="#ae955de4cebaa654363ab0188e24ec19d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec866dc063fd3bc550e853938c4b5010">printLiveIns</a> (raw_ostream &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the live-ins of this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> to <span class="doxyComputerOutput">O</span>. <a href="#aec866dc063fd3bc550e853938c4b5010">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adef61e4746c6f7f0e2e75da307e77c42">print</a> (raw_ostream &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> to <span class="doxyComputerOutput">O</span>. <a href="#adef61e4746c6f7f0e2e75da307e77c42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a064c339f401589b34437e61d8108d8d8">printDOT</a> (raw_ostream &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> in <a href="/web-llvm/docs/api/namespaces/llvm/dot">DOT</a> format to <span class="doxyComputerOutput">O</span>. <a href="#a064c339f401589b34437e61d8108d8d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfa2ca2843601cd7a5f758e5d4014f84">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the plan to stderr (for debugging). <a href="#acfa2ca2843601cd7a5f758e5d4014f84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe">VPCanonicalIVPHIRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9053d6ed9627166c144b8895d1c1010">getCanonicalIV</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the canonical induction recipe of the vector loop. <a href="#ad9053d6ed9627166c144b8895d1c1010">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea17e1d416f9187542a9f87745c48e0a">getSCEVExpansion</a> (const SCEV *S) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65719da7ecac78c4b751d3dbb9f9f2a4">addSCEVExpansion</a> (const SCEV *S, VPValue *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afadf7ae5a5fad2c0bde13e8b72bf7a71">duplicate</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the current <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>, update all VPValues of the new <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> and cloned recipes to refer to the clones, and return it. <a href="#afadf7ae5a5fad2c0bde13e8b72bf7a71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1202b66a60b632b7adbdee13a20ad7e">createVPBasicBlock</a> (const Twine &amp;Name, VPRecipeBase *Recipe=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> with <span class="doxyComputerOutput">Name</span> and containing <span class="doxyComputerOutput">Recipe</span> if present. <a href="#aa1202b66a60b632b7adbdee13a20ad7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a229a878bb15506314b99639e3d6dca41">createVPRegionBlock</a> (VPBlockBase *Entry, VPBlockBase *Exiting, const std::string &amp;Name="", bool IsReplicator=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> with <span class="doxyComputerOutput">Entry</span>, <span class="doxyComputerOutput">Exiting</span> and <span class="doxyComputerOutput">Name</span>. <a href="#a229a878bb15506314b99639e3d6dca41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fff60ced31e949142816827e969220b">createVPRegionBlock</a> (const std::string &amp;Name="", bool IsReplicator=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> with <span class="doxyComputerOutput">Name</span> and entry and exiting blocks set to nullptr. <a href="#a7fff60ced31e949142816827e969220b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a624ea79a08dc5db0333a1f8dd0075936">createEmptyVPIRBasicBlock</a> (BasicBlock *IRBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> wrapping <span class="doxyComputerOutput">IRBB</span>, but do not create VPIRInstructions wrapping the instructions in t<span class="doxyComputerOutput">IRBB</span>. <a href="#a624ea79a08dc5db0333a1f8dd0075936">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa12c0d3acb3f625ee09d2919907d4067">createVPIRBasicBlock</a> (BasicBlock *IRBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> from <span class="doxyComputerOutput">IRBB</span> containing VPIRInstructions for all instructions in <span class="doxyComputerOutput">IRBB</span>, except its terminator which is managed by the successors of the block in <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#aa12c0d3acb3f625ee09d2919907d4067">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1b90fb992672520a22270f8f6bd32f0">Entry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> corresponding to the original preheader. <a href="#ad1b90fb992672520a22270f8f6bd32f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a020c90524f3268cadfb0cb03a6f350d8">ScalarHeader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> wrapping the header of the original scalar loop. <a href="#a020c90524f3268cadfb0cb03a6f350d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb43d7cfe07bcc38eb2638da45a15f49">VFs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the VFs applicable to this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#acb43d7cfe07bcc38eb2638da45a15f49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; unsigned, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eccac4ed0bb4c551e6e4ee286906a3e">UFs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the UFs applicable to this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#a7eccac4ed0bb4c551e6e4ee286906a3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b587f308f99954318dea76f0500dc8d">Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the name of the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>, for printing. <a href="#a9b587f308f99954318dea76f0500dc8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49cbc66e734c87ec1f94a6edf9a999c4">TripCount</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents the trip count of the original loop, for folding the tail. <a href="#a49cbc66e734c87ec1f94a6edf9a999c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb86f44bcdcd192ea29e209e0f1ea3f">BackedgeTakenCount</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents the backedge taken count of the original loop, for folding the tail. <a href="#a4fb86f44bcdcd192ea29e209e0f1ea3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55c4ae680bbb7c5b8dad14af25216b0b">VectorTripCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents the vector trip count. <a href="#a55c4ae680bbb7c5b8dad14af25216b0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a228158d5895f46519fb926cfc83b8a4f">VF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents the vectorization factor of the loop. <a href="#a228158d5895f46519fb926cfc83b8a4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51d3cce8183338e863e6ef269bd0f07d">VFxUF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents the loop-invariant VF * UF of the vector loop region. <a href="#a51d3cce8183338e863e6ef269bd0f07d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acec45693cb551d5e3f8714d496cf4fee">Value2VPValueTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8fc3cd5cfbe2026cef38440206951a1">Value2VPValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds a mapping between Values and their corresponding <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> inside <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#ae8fc3cd5cfbe2026cef38440206951a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5304850697f98f8a42826b4bca29fe03">VPLiveInsToFree</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Contains all the external definitions created for this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#a5304850697f98f8a42826b4bca29fe03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad157763ed381d7b447be5e4f784485df">SCEVToExpansion</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping from SCEVs to the VPValues representing their expansions. <a href="#ad157763ed381d7b447be5e4f784485df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49319e5fea946cbfe7371e9abe389d40">CreatedBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocks allocated and owned by the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#a49319e5fea946cbfe7371e9abe389d40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#aefc42f3cefc5a839ca925b4cb3ae4a7b">VPlanPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a956378c8f267d4b2afc6e036a08d42">createInitialVPlan</a> (Type *InductionTy, PredicatedScalarEvolution &amp;PSE, bool RequiresScalarEpilogueCheck, bool TailFolded, Loop *TheLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create initial <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>, having an "entry" <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> (wrapping original scalar pre-header) which contains <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expansions that need to happen before the CFG is modified (when executing a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> for the epilogue vector loop, the original entry needs to be replaced by a new one); a <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> for the vector pre-header, followed by a region for the vector loop, followed by the middle <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a>. <a href="#a5a956378c8f267d4b2afc6e036a08d42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> models a candidate for vectorization, encoding various decisions take to produce efficient output IR, including which branches, basic-blocks and output IR instructions to generate, and their cost.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> holds a Hierarchical-CFG of VPBasicBlocks and VPRegionBlocks rooted at an Entry <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a>.</p>


<p>Definition at line 3815 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Friends

### VPlanPrinter {#a49f9947d030a2675aa107469350c5d72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vplanprinter">VPlanPrinter</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 3816 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#a49f9947d030a2675aa107469350c5d72">VPlanPrinter</a>.</p>


<p>Referenced by <a href="#a064c339f401589b34437e61d8108d8d8">printDOT</a> and <a href="#a49f9947d030a2675aa107469350c5d72">VPlanPrinter</a>.</p>

</div>
</div>

### VPSlotTracker {#a12ceea61a3de5b2f0ff70850f66c5fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 3817 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#a12ceea61a3de5b2f0ff70850f66c5fdc">VPSlotTracker</a>.</p>


<p>Referenced by <a href="#adef61e4746c6f7f0e2e75da307e77c42">print</a>, <a href="#aec866dc063fd3bc550e853938c4b5010">printLiveIns</a> and <a href="#a12ceea61a3de5b2f0ff70850f66c5fdc">VPSlotTracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VPlan() {#a9e5cbede99134e89b34efded77cd3c4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlan::VPlan (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> for <span class="doxyComputerOutput">L</span>.</p>


<p>This will create VPIRBasicBlocks wrapping the original preheader and scalar header of <span class="doxyComputerOutput">L</span>, to be used as entry and scalar header blocks of the new <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>


<p>Declaration at line 3886 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 816 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="#aa12c0d3acb3f625ee09d2919907d4067">createVPIRBasicBlock</a> and <a href="#a9f311a1a101ba9ebbdafb31a67942b69">setEntry</a>.</p>

</div>
</div>

### VPlan() {#a3c68cb3d20000fcb178a8f0eb6454cfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPlan::VPlan (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ScalarHeaderBB, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * TC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> with a new <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> as entry, a <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> wrapping <span class="doxyComputerOutput">ScalarHeaderBB</span> and a trip count of <span class="doxyComputerOutput">TC</span>.</p>

<p>Definition at line 3890 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#aa1202b66a60b632b7adbdee13a20ad7e">createVPBasicBlock</a>, <a href="#aa12c0d3acb3f625ee09d2919907d4067">createVPIRBasicBlock</a> and <a href="#a9f311a1a101ba9ebbdafb31a67942b69">setEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### VPlan() {#a6c7a498b8f88b2c448c1b88e1e2c4f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPlan::VPlan (<a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * Entry, <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> * ScalarHeader)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> with <span class="doxyComputerOutput">Entry</span> to the plan and with <span class="doxyComputerOutput">ScalarHeader</span> wrapping the original header of the scalar loop.</p>

<p>Definition at line 3875 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VPlan() {#a433f41155026be9f8f6fa880554286a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlan::~VPlan ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 3896 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 821 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSCEVExpansion() {#a65719da7ecac78c4b751d3dbb9f9f2a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPlan::addSCEVExpansion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4086 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a064976a6c7458b10c24021b7334cec2a">llvm::vputils::getOrCreateVPValueForSCEVExpr</a>.</p>

</div>
</div>

### addVF() {#ae2c6a16b2209e1709ee483b22b260849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPlan::addVF (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3998 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### cost() {#a8d2ce995a1feaa7a65ff40f77f073db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost VPlan::cost (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the cost of this plan.</p>

<p>Declaration at line 3926 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1045 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>Reference <a href="#a89f94c49b2cb5daaa93d19c89307c307">getVectorLoopRegion</a>.</p>

</div>
</div>

### createEmptyVPIRBasicBlock() {#a624ea79a08dc5db0333a1f8dd0075936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPIRBasicBlock * VPlan::createEmptyVPIRBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * IRBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> wrapping <span class="doxyComputerOutput">IRBB</span>, but do not create VPIRInstructions wrapping the instructions in t<span class="doxyComputerOutput">IRBB</span>.</p>


<p>The returned block is owned by the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> and deleted once the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> is destroyed.</p>


<p>Declaration at line 4130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1245 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>Referenced by <a href="#aa12c0d3acb3f625ee09d2919907d4067">createVPIRBasicBlock</a>.</p>

</div>
</div>

### createVPBasicBlock() {#aa1202b66a60b632b7adbdee13a20ad7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock * llvm::VPlan::createVPBasicBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * Recipe=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> with <span class="doxyComputerOutput">Name</span> and containing <span class="doxyComputerOutput">Recipe</span> if present.</p>


<p>The returned block is owned by the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> and deleted once the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> is destroyed.</p>


<p>Definition at line 4098 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a5a956378c8f267d4b2afc6e036a08d42">createInitialVPlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ac967ad551e77554a15e20cac14877ac7">createReplicateRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a> and <a href="#a3c68cb3d20000fcb178a8f0eb6454cfc">VPlan</a>.</p>

</div>
</div>

### createVPIRBasicBlock() {#aa12c0d3acb3f625ee09d2919907d4067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPIRBasicBlock * VPlan::createVPIRBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * IRBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> from <span class="doxyComputerOutput">IRBB</span> containing VPIRInstructions for all instructions in <span class="doxyComputerOutput">IRBB</span>, except its terminator which is managed by the successors of the block in <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>


<p>The returned block is owned by the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> and deleted once the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> is destroyed.</p>


<p>Declaration at line 4136 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1251 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#a624ea79a08dc5db0333a1f8dd0075936">createEmptyVPIRBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="#a5a956378c8f267d4b2afc6e036a08d42">createInitialVPlan</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a3a8743a69fac5e7fa9c2b02604b2cf2f">replaceVPBBWithIRVPBB</a>, <a href="#a3c68cb3d20000fcb178a8f0eb6454cfc">VPlan</a> and <a href="#a9e5cbede99134e89b34efded77cd3c4e">VPlan</a>.</p>

</div>
</div>

### createVPRegionBlock() {#a229a878bb15506314b99639e3d6dca41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPRegionBlock * llvm::VPlan::createVPRegionBlock (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * Entry, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * Exiting, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name="", bool IsReplicator=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> with <span class="doxyComputerOutput">Entry</span>, <span class="doxyComputerOutput">Exiting</span> and <span class="doxyComputerOutput">Name</span>.</p>


<p>If <span class="doxyComputerOutput">IsReplicator</span> is true, the region is a replicate region. The returned block is owned by the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> and deleted once the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> is destroyed.</p>


<p>Definition at line 4108 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a5a956378c8f267d4b2afc6e036a08d42">createInitialVPlan</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ac967ad551e77554a15e20cac14877ac7">createReplicateRegion</a>.</p>

</div>
</div>

### createVPRegionBlock() {#a7fff60ced31e949142816827e969220b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPRegionBlock * llvm::VPlan::createVPRegionBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name="", bool IsReplicator=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> with <span class="doxyComputerOutput">Name</span> and entry and exiting blocks set to nullptr.</p>


<p>If <span class="doxyComputerOutput">IsReplicator</span> is true, the region is a replicate region. The returned block is owned by the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> and deleted once the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> is destroyed.</p>


<p>Definition at line 4120 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### dump() {#acfa2ca2843601cd7a5f758e5d4014f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void VPlan::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the plan to stderr (for debugging).</p>

<p>Declaration at line 4069 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1150 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>.</p>

</div>
</div>

### duplicate() {#afadf7ae5a5fad2c0bde13e8b72bf7a71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlan * VPlan::duplicate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone the current <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>, update all VPValues of the new <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> and cloned recipes to refer to the clones, and return it.</p>

<p>Declaration at line 4093 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1191 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#ac1ac18b9f807acbc9846d923ea874524">cloneFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a836d9cba6deced0bb1fa7333ce5afd3a">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="#ae56a6505c6bfa319e686fc23acd52495">getScalarHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#aaa122781f91b3e8bc730b2c5b7c07a05">remapOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4474bfb1e0ca062e5bfe2a35980e7d19">llvm::vp_depth_first_shallow</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### execute() {#ad80b94848142a7c633976aff96d4c408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlan::execute (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> * State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate the IR code for this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>


<p>Generate the code inside the preheader and body of the vectorized loop.</p>


<p>Assumes a single pre-header basic-block was created for this. Introduce additional basic-blocks as needed, and fill them all.</p>


<p>Declaration at line 3923 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 955 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a71c91cbbfc1c0ecf9a69e10ccf739bd7">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::Delete</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a03503773241005f01b090b9862aad304">llvm::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a28da654f916bf44da5513b6f1788835c">llvm::VPBlockBase::getExitingBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a79c007dcf9fff57e1569e778d7885b5e">llvm::BasicBlock::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="#a532045d23e6f3efd21732fd342f99f09">getUF</a>, <a href="#a89f94c49b2cb5daaa93d19c89307c307">getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af67d1f3a518964d80a109bb3d9d5cf1e">llvm::Instruction::moveBefore</a>, <a href="#a242fb01fcd9fab0be0f487b67fd94a0a">setName</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### getCanonicalIV() {#ad9053d6ed9627166c144b8895d1c1010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPCanonicalIVPHIRecipe * llvm::VPlan::getCanonicalIV ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the canonical induction recipe of the vector loop.</p>

<p>Definition at line 4073 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a4e30ea9d413dd86c802fee94aa8b5805">llvm::VPBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#aeb3dd295f833ecc508d7586df94a76f3">llvm::VPBasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aebc0e1a3379ed4fd614889e24b8ea48c">llvm::VPBlockBase::getSingleSuccessor</a> and <a href="#a89f94c49b2cb5daaa93d19c89307c307">getVectorLoopRegion</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae1d2d60cd9edd9f7ca98c50789747c95">llvm::VPlanTransforms::addActiveLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a453563e4ed7e249a7f3e92b98b9052df">addExitUsersForFirstOrderRecurrences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5a9cb34d61fa4930ff585649d1d5b2ed">addVPLaneMaskPhiAndUpdateExitBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a8d0c6052d21638f0a385e226db3bd92f">collectAllHeaderMasks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a3c91ec836b0d1e340e17bff8eec31390">createScalarIVSteps</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae3449b993cd1c459995c2fe13ef50892">llvm::VPlanTransforms::optimize</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a3a573419fed83f23b6bf70ac6731dbfa">llvm::VPlanTransforms::optimizeInductionExitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aefd03ef5fc77c520e27fe794e8ec93e9">removeRedundantCanonicalIVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad16bff9364e25351de81704fe81fd229">llvm::VPlanTransforms::tryAddExplicitVectorLength</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af378bb1e037306d9cfd4bb0b49ba55f9">willGenerateVectors</a>.</p>

</div>
</div>

### getEntry() {#a1c868dfd250ff9592c06dd61a7fb0bcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock * llvm::VPlan::getEntry ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3928 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6e46200e5b228c903356e02904987051">addReplicateRegions</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a63e564d621011fac5978d18138121e5c">llvm::VPlanTransforms::convertToConcreteRecipes</a>, <a href="#a5a956378c8f267d4b2afc6e036a08d42">createInitialVPlan</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa0f143b8d4693978b984f0639c90e508">llvm::VPlanTransforms::dropPoisonGeneratingRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreenodetraits-d6d05c8f661a084b01cd86951e97c77f/#a558c601f9ba5f1cb3bcdf5955984a79c">llvm::DomTreeNodeTraits&lt; VPBlockBase &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a064976a6c7458b10c24021b7334cec2a">llvm::vputils::getOrCreateVPValueForSCEVExpr</a>, <a href="#a89f94c49b2cb5daaa93d19c89307c307">getVectorLoopRegion</a>, <a href="#af19b220ce9ea956afca867699a0581df">getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a528aff11b730581c8d7cfae0e5fb6254">mergeBlocksIntoPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4b251734aba716917922f4ab216436c1">mergeReplicateRegionsIntoSuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>, <a href="#adef61e4746c6f7f0e2e75da307e77c42">print</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aaca9dd97d4c523d8c65274654abe4eb9">llvm::VPlanTransforms::removeDeadRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a8a0202a443a527ba17fcd111497feb7d">removeRedundantExpandSCEVRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a961946cf5fda7331e31bf343c79da2c3">llvm::VPBlockBase::setPlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a74cb3294789bc24526bcadbf6b466714">simplifyRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a7a1cca51bb9bce4efad1063dcf158967">llvm::VPlanTransforms::unrollByUF</a> and <a href="/web-llvm/docs/api/classes/anonymous-vplanverifier-cpp-/vplanverifier/#a4140274aee97c60c4a26d1ecd4234a78">anonymous{VPlanVerifier.cpp}::VPlanVerifier::verify</a>.</p>

</div>
</div>

### getEntry() {#a479b833fd70361a9b1bb9cb9f8a2e3ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPBasicBlock * llvm::VPlan::getEntry ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3929 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### getExitBlocks() {#a85800ca7a821f540ad2d6d4d3c2d4208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::VPlan::getExitBlocks ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an iterator range over the <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> wrapping the exit blocks of the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>, that is leaf nodes except the scalar header.</p>


<p>Defined in VPlanHCFG, as the definition of the type needs access to the definitions of <a href="/web-llvm/docs/api/classes/llvm/vpblockshallowtraversalwrapper">VPBlockShallowTraversalWrapper</a>.</p>


<p>Declaration at line 3966 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplancfg-h">VPlanCFG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a0360eea6cebcb1470f84b11f7ba51f16">llvm::VPBlockUtils::blocksOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a2c13ffed8c55e1b8dd38fedc7e71e7a8">llvm::VPBlockBase::getNumSuccessors</a>, <a href="#ae56a6505c6bfa319e686fc23acd52495">getScalarHeader</a>, <a href="#a89f94c49b2cb5daaa93d19c89307c307">getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4474bfb1e0ca062e5bfe2a35980e7d19">llvm::vp_depth_first_shallow</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a435b95efad7ea03299bd527b55b4708a">collectUsersInExitBlocks</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a3a573419fed83f23b6bf70ac6731dbfa">llvm::VPlanTransforms::optimizeInductionExitUsers</a>.</p>

</div>
</div>

### getLiveIn() {#ae955de4cebaa654363ab0188e24ec19d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPlan::getLiveIn (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the live-in <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> for <span class="doxyComputerOutput">V</span>, if there is one or nullptr otherwise.</p>

<p>Definition at line 4056 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### getMiddleBlock() {#a995b2a034ffc26dcd2f3a679f9d2feea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPBasicBlock * llvm::VPlan::getMiddleBlock ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the 'middle' block of the plan, that is the block that selects whether to execute the scalar tail loop or the exit block from the loop latch.</p>

<p>Definition at line 3947 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#ad5f29ccf71b0494fc179323427eb1e11">getScalarPreheader</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a453563e4ed7e249a7f3e92b98b9052df">addExitUsersForFirstOrderRecurrences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af34d746d08a380c672cae45176f9df87">addUsersInExitBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a435b95efad7ea03299bd527b55b4708a">collectUsersInExitBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a3a573419fed83f23b6bf70ac6731dbfa">llvm::VPlanTransforms::optimizeInductionExitUsers</a>.</p>

</div>
</div>

### getMiddleBlock() {#a9cbce97074fc9cc4c7bc027adcf560af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock * llvm::VPlan::getMiddleBlock ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3950 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#ad5f29ccf71b0494fc179323427eb1e11">getScalarPreheader</a>.</p>

</div>
</div>

### getName() {#a13c80757c166e2959462fa447ed39649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string VPlan::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a string with the name of the plan and the applicable VFs and UFs.</p>

<p>Declaration at line 4033 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1120 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>.</p>

</div>
</div>

### getOrAddLiveIn() {#ac38d49d70b5f78779e83abdf4dcb4be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPlan::getOrAddLiveIn (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets the live-in <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> for <span class="doxyComputerOutput">V</span> or adds a new live-in (if none exists yet) for <span class="doxyComputerOutput">V</span>.</p>

<p>Definition at line 4039 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#add6179d3564ac5ea4736366b93d23829">llvm::VPValue::isLiveIn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a4d2a943e39c98ccce6fd53e8df9c5c2b">addCanonicalIVRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a453563e4ed7e249a7f3e92b98b9052df">addExitUsersForFirstOrderRecurrences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a>, <a href="#a5a956378c8f267d4b2afc6e036a08d42">createInitialVPlan</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa88371693bc18186386b04e8c45a30e4">llvm::VPlanTransforms::createInterleaveGroups</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a064976a6c7458b10c24021b7334cec2a">llvm::vputils::getOrCreateVPValueForSCEVExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a3a573419fed83f23b6bf70ac6731dbfa">llvm::VPlanTransforms::optimizeInductionExitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad16bff9364e25351de81704fe81fd229">llvm::VPlanTransforms::tryAddExplicitVectorLength</a>.</p>

</div>
</div>

### getOrCreateBackedgeTakenCount() {#a3732ef393569af17c44c36f4e22f2854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPlan::getOrCreateBackedgeTakenCount ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The backedge taken count of the original loop.</p>

<p>Definition at line 3983 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a96c706ef30193e00ac057bf24cf5719d">llvm::vputils::isHeaderMask</a>.</p>

</div>
</div>

### getScalarHeader() {#ae56a6505c6bfa319e686fc23acd52495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPIRBasicBlock * llvm::VPlan::getScalarHeader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> wrapping the header of the scalar loop.</p>

<p>Definition at line 3960 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a>, <a href="#a5a956378c8f267d4b2afc6e036a08d42">createInitialVPlan</a>, <a href="#afadf7ae5a5fad2c0bde13e8b72bf7a71">duplicate</a>, <a href="#a85800ca7a821f540ad2d6d4d3c2d4208">getExitBlocks</a>, <a href="#ad5f29ccf71b0494fc179323427eb1e11">getScalarPreheader</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a>.</p>

</div>
</div>

### getScalarPreheader() {#ad5f29ccf71b0494fc179323427eb1e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock * llvm::VPlan::getScalarPreheader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> for the preheader of the scalar loop.</p>

<p>Definition at line 3955 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#ae56a6505c6bfa319e686fc23acd52495">getScalarHeader</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a453563e4ed7e249a7f3e92b98b9052df">addExitUsersForFirstOrderRecurrences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a>, <a href="#a9cbce97074fc9cc4c7bc027adcf560af">getMiddleBlock</a>, <a href="#a995b2a034ffc26dcd2f3a679f9d2feea">getMiddleBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a>.</p>

</div>
</div>

### getSCEVExpansion() {#aea17e1d416f9187542a9f87745c48e0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPlan::getSCEVExpansion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4082 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a064976a6c7458b10c24021b7334cec2a">llvm::vputils::getOrCreateVPValueForSCEVExpr</a>.</p>

</div>
</div>

### getTripCount() {#a2f5fc19caa67daeca8a1316c7e055e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPlan::getTripCount ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The trip count of the original loop.</p>

<p>Definition at line 3969 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae1d2d60cd9edd9f7ca98c50789747c95">llvm::VPlanTransforms::addActiveLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5a9cb34d61fa4930ff585649d1d5b2ed">addVPLaneMaskPhiAndUpdateExitBranch</a>, <a href="#a5a956378c8f267d4b2afc6e036a08d42">createInitialVPlan</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a96c706ef30193e00ac057bf24cf5719d">llvm::vputils::isHeaderMask</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad16bff9364e25351de81704fe81fd229">llvm::VPlanTransforms::tryAddExplicitVectorLength</a>.</p>

</div>
</div>

### getUF() {#a532045d23e6f3efd21732fd342f99f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VPlan::getUF ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4021 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ad80b94848142a7c633976aff96d4c408">execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a> and <a href="#a143bc5faeb35f7363570e97bccf76e53">prepareToExecute</a>.</p>

</div>
</div>

### getVectorLoopRegion() {#a89f94c49b2cb5daaa93d19c89307c307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPRegionBlock * VPlan::getVectorLoopRegion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> of the vector loop.</p>

<p>Declaration at line 3941 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1c868dfd250ff9592c06dd61a7fb0bcf">getEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4474bfb1e0ca062e5bfe2a35980e7d19">llvm::vp_depth_first_shallow</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a4d2a943e39c98ccce6fd53e8df9c5c2b">addCanonicalIVRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a453563e4ed7e249a7f3e92b98b9052df">addExitUsersForFirstOrderRecurrences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5a9cb34d61fa4930ff585649d1d5b2ed">addVPLaneMaskPhiAndUpdateExitBranch</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae64d6953a1334207d9e7d9cd2587ee9f">llvm::VPlanTransforms::adjustFixedOrderRecurrences</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a36d6728b8c3cfca0a9bd02c3f0273477">llvm::LoopVectorizationPlanner::buildVPlans</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ace9e1e6e7295914973dec18350b382ca">llvm::VPlanTransforms::clearReductionWrapFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a8d0c6052d21638f0a385e226db3bd92f">collectAllHeaderMasks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62219a4c97e27d64593245e4e9187cd1">llvm::collectEphemeralRecipesForVPlan</a>, <a href="#a8d2ce995a1feaa7a65ff40f77f073db3">cost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a3c91ec836b0d1e340e17bff8eec31390">createScalarIVSteps</a>, <a href="#ad80b94848142a7c633976aff96d4c408">execute</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="#ad9053d6ed9627166c144b8895d1c1010">getCanonicalIV</a>, <a href="#a85800ca7a821f540ad2d6d4d3c2d4208">getExitBlocks</a>, <a href="#aee894572833ce02ad06c067d44f65b48">getVectorPreheader</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#afd081c92500bd333555e7bd6102b4d3e">licm</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a696283c30308704d020a9d86065aa3ae">planContainsAdditionalSimplifications</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a>, <a href="#a143bc5faeb35f7363570e97bccf76e53">prepareToExecute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aefd03ef5fc77c520e27fe794e8ec93e9">removeRedundantCanonicalIVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a2ff7a57c84a06ee83b0a28763db85c3f">removeRedundantInductionCasts</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a4690286163882c35068b1908f4d752fd">llvm::InnerLoopVectorizer::scalarizeInstruction</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad16bff9364e25351de81704fe81fd229">llvm::VPlanTransforms::tryAddExplicitVectorLength</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a7a1cca51bb9bce4efad1063dcf158967">llvm::VPlanTransforms::unrollByUF</a>, <a href="/web-llvm/docs/api/classes/anonymous-vplanverifier-cpp-/vplanverifier/#a4140274aee97c60c4a26d1ecd4234a78">anonymous{VPlanVerifier.cpp}::VPlanVerifier::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleavedaccessinfo/#a24f3316a0caf6117d7447bda1023823f">llvm::VPInterleavedAccessInfo::VPInterleavedAccessInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af378bb1e037306d9cfd4bb0b49ba55f9">willGenerateVectors</a>.</p>

</div>
</div>

### getVectorLoopRegion() {#af19b220ce9ea956afca867699a0581df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPRegionBlock * VPlan::getVectorLoopRegion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 3942 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1059 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1c868dfd250ff9592c06dd61a7fb0bcf">getEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4474bfb1e0ca062e5bfe2a35980e7d19">llvm::vp_depth_first_shallow</a>.</p>

</div>
</div>

### getVectorPreheader() {#aee894572833ce02ad06c067d44f65b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock * llvm::VPlan::getVectorPreheader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the preheader of the vector loop region, if one exists, or null otherwise.</p>

<p>Definition at line 3933 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#aa1bb4808c7a5db9f8ed3f479c78c4b5e">llvm::VPBlockBase::getSinglePredecessor</a> and <a href="#a89f94c49b2cb5daaa93d19c89307c307">getVectorLoopRegion</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5a9cb34d61fa4930ff585649d1d5b2ed">addVPLaneMaskPhiAndUpdateExitBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#afd081c92500bd333555e7bd6102b4d3e">licm</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a>.</p>

</div>
</div>

### getVectorTripCount() {#a233848f0bf7aef1aca22e6172e5d900d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue &amp; llvm::VPlan::getVectorTripCount ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The vector trip count.</p>

<p>Definition at line 3990 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a4d2a943e39c98ccce6fd53e8df9c5c2b">addCanonicalIVRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a>, <a href="#a5a956378c8f267d4b2afc6e036a08d42">createInitialVPlan</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a>.</p>

</div>
</div>

### getVF() {#a2dffed680cc551f7ac6d92b3cd365d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue &amp; llvm::VPlan::getVF ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the VF of the vector loop region.</p>

<p>Definition at line 3993 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a9336eb7b4fbcee561dbb8c52d9eabe64">createWidenInductionRecipes</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a>.</p>

</div>
</div>

### getVFxUF() {#a2d53ff30dd2a706e91c30d4f50982e3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue &amp; llvm::VPlan::getVFxUF ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns VF * UF of the vector loop region.</p>

<p>Definition at line 3996 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a4d2a943e39c98ccce6fd53e8df9c5c2b">addCanonicalIVRecipes</a>.</p>

</div>
</div>

### hasScalableVF() {#a18b96ac619241bd2248a355af718a192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPlan::hasScalableVF ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4007 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a>.</p>

</div>
</div>

### hasScalarVFOnly() {#ad30bf062f18fd6e56e36bfecefbbb386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPlan::hasScalarVFOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4017 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>.</p>

</div>
</div>

### hasUF() {#a6e9c2a69cd9bc0e46626f5302a03d3da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPlan::hasUF (unsigned UF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4019 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a> and <a href="#af1d539e508015e09e4b9fdb7d020da0e">setUF</a>.</p>

</div>
</div>

### hasVF() {#a633dd97e642c10e8aa1dff2bd2874edb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPlan::hasVF (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4006 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a10f355c5a55dd7e98d31c2f7e0b590aa">llvm::LoopVectorizationPlanner::getPlanFor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a> and <a href="#a7ee6ab8541efab3e456a38d6c1fa1be2">setVF</a>.</p>

</div>
</div>

### prepareToExecute() {#a143bc5faeb35f7363570e97bccf76e53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlan::prepareToExecute (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TripCount, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * VectorTripCount, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prepare the plan for execution, setting up the required live-in values.</p>

<p>Declaration at line 3919 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#aa8a293d9d0bf609e45f591ce4bd55bb3">llvm::VPTransformState::Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4156fb8bcc6a7e29ee021b01d22551e">llvm::createStepForVF</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f777e2b1044ba7971766097fdd56579">llvm::getRuntimeVF</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a532045d23e6f3efd21732fd342f99f09">getUF</a> and <a href="#a89f94c49b2cb5daaa93d19c89307c307">getVectorLoopRegion</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### print() {#adef61e4746c6f7f0e2e75da307e77c42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void VPlan::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> to <span class="doxyComputerOutput">O</span>.</p>

<p>Declaration at line 4063 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1103 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="#a1c868dfd250ff9592c06dd61a7fb0bcf">getEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="#aec866dc063fd3bc550e853938c4b5010">printLiveIns</a> and <a href="#a12ceea61a3de5b2f0ff70850f66c5fdc">VPSlotTracker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8d7ecb4fa061e6d1b2e7448530e4c795">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#ac3a6a342405e61ad992020460a530dc4">llvm::LoopVectorizationPlanner::printPlans</a>.</p>

</div>
</div>

### printDOT() {#a064c339f401589b34437e61d8108d8d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void VPlan::printDOT (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> in <a href="/web-llvm/docs/api/namespaces/llvm/dot">DOT</a> format to <span class="doxyComputerOutput">O</span>.</p>

<p>Declaration at line 4066 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a> and <a href="#a49f9947d030a2675aa107469350c5d72">VPlanPrinter</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#ac3a6a342405e61ad992020460a530dc4">llvm::LoopVectorizationPlanner::printPlans</a>.</p>

</div>
</div>

### printLiveIns() {#aec866dc063fd3bc550e853938c4b5010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlan::printLiveIns (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the live-ins of this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> to <span class="doxyComputerOutput">O</span>.</p>

<p>Declaration at line 4060 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1067 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>Reference <a href="#a12ceea61a3de5b2f0ff70850f66c5fdc">VPSlotTracker</a>.</p>


<p>Referenced by <a href="#adef61e4746c6f7f0e2e75da307e77c42">print</a>.</p>

</div>
</div>

### resetTripCount() {#a9bb77d906fd1ae7e241f0c95dcba094b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPlan::resetTripCount (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * NewTripCount)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resets the trip count for the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>


<p>The caller must make sure all uses of the original trip count have been replaced.</p>


<p>Definition at line 3976 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#ac3acda1aa682fbb8f8b95b0816eea879">llvm::VPValue::getNumUsers</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>.</p>

</div>
</div>

### setEntry() {#a9f311a1a101ba9ebbdafb31a67942b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPlan::setEntry (<a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * VPBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3898 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a961946cf5fda7331e31bf343c79da2c3">llvm::VPBlockBase::setPlan</a>.</p>


<p>Referenced by <a href="#a3c68cb3d20000fcb178a8f0eb6454cfc">VPlan</a> and <a href="#a9e5cbede99134e89b34efded77cd3c4e">VPlan</a>.</p>

</div>
</div>

### setName() {#a242fb01fcd9fab0be0f487b67fd94a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPlan::setName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; newName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4035 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>


<p>Referenced by <a href="#ad80b94848142a7c633976aff96d4c408">execute</a>.</p>

</div>
</div>

### setUF() {#af1d539e508015e09e4b9fdb7d020da0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPlan::setUF (unsigned UF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4026 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a6e9c2a69cd9bc0e46626f5302a03d3da">hasUF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad16bff9364e25351de81704fe81fd229">llvm::VPlanTransforms::tryAddExplicitVectorLength</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a7a1cca51bb9bce4efad1063dcf158967">llvm::VPlanTransforms::unrollByUF</a>.</p>

</div>
</div>

### setVF() {#a7ee6ab8541efab3e456a38d6c1fa1be2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPlan::setVF (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4000 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a633dd97e642c10e8aa1dff2bd2874edb">hasVF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>.</p>

</div>
</div>

### vectorFactors() {#a3aac2593ea2eaac537de30053e8e05fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; SmallSetVector&lt; ElementCount, 2 &gt;::iterator &gt; llvm::VPlan::vectorFactors ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an iterator range over all VFs of the plan.</p>

<p>Definition at line 4013 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a4adc69fc8f74164e990cce6afc1e061b">llvm::LoopVectorizationPlanner::computeBestVF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BackedgeTakenCount {#a4fb86f44bcdcd192ea29e209e0f1ea3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue* llvm::VPlan::BackedgeTakenCount = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents the backedge taken count of the original loop, for folding the tail.</p>


<p>It equals TripCount - 1.</p>


<p>Definition at line 3845 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### CreatedBlocks {#a49319e5fea946cbfe7371e9abe389d40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VPBlockBase *&gt; llvm::VPlan::CreatedBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Blocks allocated and owned by the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>


<p>They will be deleted once the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> is destroyed.</p>


<p>Definition at line 3871 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### Entry {#ad1b90fb992672520a22270f8f6bd32f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock* llvm::VPlan::Entry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> corresponding to the original preheader.</p>


<p>Used to place VPExpandSCEV recipes for expressions used during skeleton creation and the rest of <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> execution. When this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> is used for the epilogue vector loop, the entry will be replaced by a new entry block created during skeleton creation.</p>


<p>Definition at line 3824 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### Name {#a9b587f308f99954318dea76f0500dc8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::VPlan::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the name of the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>, for printing.</p>

<p>Definition at line 3837 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### ScalarHeader {#a020c90524f3268cadfb0cb03a6f350d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPIRBasicBlock* llvm::VPlan::ScalarHeader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock">VPIRBasicBlock</a> wrapping the header of the original scalar loop.</p>

<p>Definition at line 3827 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### SCEVToExpansion {#ad157763ed381d7b447be5e4f784485df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const SCEV *, VPValue *&gt; llvm::VPlan::SCEVToExpansion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping from SCEVs to the VPValues representing their expansions.</p>


<p>NOTE: This mapping is temporary and will be removed once all users have been modeled in <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> directly.</p>


<p>Definition at line 3867 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### TripCount {#a49cbc66e734c87ec1f94a6edf9a999c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue* llvm::VPlan::TripCount = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents the trip count of the original loop, for folding the tail.</p>

<p>Definition at line 3841 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### UFs {#a7eccac4ed0bb4c551e6e4ee286906a3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;unsigned, 2&gt; llvm::VPlan::UFs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the UFs applicable to this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>


<p>If empty, the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> is valid for any UF.</p>


<p>Definition at line 3834 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### Value2VPValue {#ae8fc3cd5cfbe2026cef38440206951a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value2VPValueTy llvm::VPlan::Value2VPValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds a mapping between Values and their corresponding <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> inside <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>

<p>Definition at line 3858 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### VectorTripCount {#a55c4ae680bbb7c5b8dad14af25216b0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue llvm::VPlan::VectorTripCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents the vector trip count.</p>

<p>Definition at line 3848 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### VF {#a228158d5895f46519fb926cfc83b8a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue llvm::VPlan::VF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents the vectorization factor of the loop.</p>

<p>Definition at line 3851 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### VFs {#acb43d7cfe07bcc38eb2638da45a15f49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;ElementCount, 2&gt; llvm::VPlan::VFs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the VFs applicable to this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>

<p>Definition at line 3830 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### VFxUF {#a51d3cce8183338e863e6ef269bd0f07d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue llvm::VPlan::VFxUF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents the loop-invariant VF * UF of the vector loop region.</p>

<p>Definition at line 3854 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### VPLiveInsToFree {#a5304850697f98f8a42826b4bca29fe03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VPValue *, 16&gt; llvm::VPlan::VPLiveInsToFree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Contains all the external definitions created for this <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>


<p>External definitions are VPValues that hold a pointer to their underlying IR.</p>


<p>Definition at line 3862 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createInitialVPlan() {#a5a956378c8f267d4b2afc6e036a08d42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlanPtr VPlan::createInitialVPlan (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * InductionTy, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, bool RequiresScalarEpilogueCheck, bool TailFolded, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop)</td>
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

<p>Create initial <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>, having an "entry" <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> (wrapping original scalar pre-header) which contains <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expansions that need to happen before the CFG is modified (when executing a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> for the epilogue vector loop, the original entry needs to be replaced by a new one); a <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> for the vector pre-header, followed by a region for the vector loop, followed by the middle <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a>.</p>


<p>If a check is needed to guard executing the scalar epilogue loop, it will be added to the middle block, together with VPBasicBlocks for the scalar preheader and exit blocks. <span class="doxyComputerOutput">InductionTy</span> is the type of the canonical induction and used for related values, like the trip count expression.</p>


<p>Declaration at line 3913 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 844 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a0062eccdb4956531f7b6a3cf71c3320c">llvm::VPInstruction::BranchOnCond</a>, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#aa8a293d9d0bf609e45f591ce4bd55bb3">llvm::VPTransformState::Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a40bc7fec35d7093efcdbadf566d6b5ee">llvm::VPBlockUtils::connectBlocks</a>, <a href="#aa1202b66a60b632b7adbdee13a20ad7e">createVPBasicBlock</a>, <a href="#aa12c0d3acb3f625ee09d2919907d4067">createVPIRBasicBlock</a>, <a href="#a229a878bb15506314b99639e3d6dca41">createVPRegionBlock</a>, <a href="#a1c868dfd250ff9592c06dd61a7fb0bcf">getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="#ac38d49d70b5f78779e83abdf4dcb4be0">getOrAddLiveIn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a064976a6c7458b10c24021b7334cec2a">llvm::vputils::getOrCreateVPValueForSCEVExpr</a>, <a href="#ae56a6505c6bfa319e686fc23acd52495">getScalarHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a10ca5eacc61b5669880de2f8b0cff33c">llvm::PredicatedScalarEvolution::getSE</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#adbabf05e94f95f775d59497b6b1004d8">llvm::PredicatedScalarEvolution::getSymbolicMaxBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="#a2f5fc19caa67daeca8a1316c7e055e3c">getTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a3e3935d45c4b79b85a117b47cc1d2e61">llvm::ScalarEvolution::getTripCountFromExitCount</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a462e59069cb22aa0abd869033bb546fb">llvm::LoopBase&lt; BlockT, LoopT &gt;::getUniqueLatchExitBlock</a>, <a href="#a233848f0bf7aef1aca22e6172e5d900d">getVectorTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a1f625b90be26a131061ab1e43740cc81">llvm::VPBlockUtils::insertBlockAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#ac0b363a134c3bfac25ba209704ef3ee3">llvm::VPTransformState::Plan</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplancfg-h">VPlanCFG.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
