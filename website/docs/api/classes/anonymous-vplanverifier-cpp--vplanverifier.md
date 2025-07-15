---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-vplanverifier-cpp-/vplanverifier
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VPlanVerifier` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{VPlanVerifier.cpp}::VPlanVerifier { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7312edccf9cd943447b127b879429ff">VPlanVerifier</a> (VPDominatorTree &amp;VPDT, VPTypeAnalysis &amp;TypeInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4140274aee97c60c4a26d1ecd4234a78">verify</a> (const VPlan &amp;Plan)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adefa7277a56d34c927ff0246e6245e46">verifyPhiRecipes</a> (const VPBasicBlock *VPBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a263faa2dde080ab369462625af8f9dd9">verifyEVLRecipe</a> (const VPInstruction &amp;EVL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that <span class="doxyComputerOutput">EVL</span> is used correctly. <a href="#a263faa2dde080ab369462625af8f9dd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4159c587c30f22e09e046ca609a9070">verifyVPBasicBlock</a> (const VPBasicBlock *VPBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d65233112fa56b3ab5ef377bb0d07e4">verifyBlock</a> (const VPBlockBase *VPB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa810600b55e9dd028b740ab4a45874bb">verifyBlocksInRegion</a> (const VPRegionBlock *Region)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function that verifies the CFG invariants of the VPBlockBases within <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span>. <a href="#aa810600b55e9dd028b740ab4a45874bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33211cb0b9468e472f048ef37b24fa5">verifyRegion</a> (const VPRegionBlock *Region)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the CFG invariants of <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> and its nested VPBlockBases. <a href="#ab33211cb0b9468e472f048ef37b24fa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3975e6701efaac50e9e4af510c32b04">verifyRegionRec</a> (const VPRegionBlock *Region)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the CFG invariants of <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> and its nested VPBlockBases. <a href="#ae3975e6701efaac50e9e4af510c32b04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpdominatortree">VPDominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9b9e8b5c3c8273a699a1c4b83d42dff">VPDT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis">VPTypeAnalysis</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a207730fe20a3d13c50bcb13d41a3ce47">TypeInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd7992cd34bc3120b609dee700d57952">WrappedIRBBs</a></td>
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


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VPlanVerifier() {#ae7312edccf9cd943447b127b879429ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{VPlanVerifier.cpp}::VPlanVerifier::VPlanVerifier (<a href="/web-llvm/docs/api/classes/llvm/vpdominatortree">VPDominatorTree</a> &amp; VPDT, <a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis">VPTypeAnalysis</a> &amp; TypeInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af5f1d1b7df16dee92c5b56c26e322b89">llvm::verifyVPlanIsValid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### verify() {#a4140274aee97c60c4a26d1ecd4234a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPlanVerifier::verify (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a0062eccdb4956531f7b6a3cf71c3320c">llvm::VPInstruction::BranchOnCond</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a507f9482c01673384c0c203530dad6f2a49dcace93798ddd457a9d4e584bbc9a2">llvm::VPInstruction::BranchOnCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#aeb3dd295f833ecc508d7586df94a76f3">llvm::VPBasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a4a7f4b8433e9a788149ffd94a0a07051">llvm::VPBasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a1c868dfd250ff9592c06dd61a7fb0bcf">llvm::VPlan::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a1ae2cb3c63b4d67324ddc947fb9696fc">llvm::VPRegionBlock::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#add3be1d1d9e5b1ee2014c32d21bf2b5b">llvm::VPRegionBlock::getExiting</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a09de70cbaf2f15aa3b0697b5f378cc9d">llvm::VPBlockBase::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4474bfb1e0ca062e5bfe2a35980e7d19">llvm::vp_depth_first_shallow</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### verifyBlock() {#a6d65233112fa56b3ab5ef377bb0d07e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPlanVerifier::verifyBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * VPB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a>.</p>

</div>
</div>

### verifyBlocksInRegion() {#aa810600b55e9dd028b740ab4a45874bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPlanVerifier::verifyBlocksInRegion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> * Region)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function that verifies the CFG invariants of the VPBlockBases within <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span>.</p>


<p>Checks in this function are generic for VPBlockBases. They are not specific for VPBasicBlocks or VPRegionBlocks.</p>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a>.</p>

</div>
</div>

### verifyEVLRecipe() {#a263faa2dde080ab369462625af8f9dd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPlanVerifier::verifyEVLRecipe (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> &amp; EVL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that <span class="doxyComputerOutput">EVL</span> is used correctly.</p>


<p>The user must be either in EVL-based recipes as a last operand or VPInstruction::Add which is incoming value into EVL's recipe.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a>.</p>

</div>
</div>

### verifyPhiRecipes() {#adefa7277a56d34c927ff0246e6245e46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPlanVerifier::verifyPhiRecipes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * VPBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a>.</p>

</div>
</div>

### verifyRegion() {#ab33211cb0b9468e472f048ef37b24fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPlanVerifier::verifyRegion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> * Region)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the CFG invariants of <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> and its nested VPBlockBases.</p>


<p>Do not recurse inside nested VPRegionBlocks.</p>


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a>.</p>

</div>
</div>

### verifyRegionRec() {#ae3975e6701efaac50e9e4af510c32b04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPlanVerifier::verifyRegionRec (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> * Region)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the CFG invariants of <a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> and its nested VPBlockBases.</p>


<p>Recurse inside nested VPRegionBlocks.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a>.</p>

</div>
</div>

### verifyVPBasicBlock() {#af4159c587c30f22e09e046ca609a9070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPlanVerifier::verifyVPBasicBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * VPBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TypeInfo {#a207730fe20a3d13c50bcb13d41a3ce47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPTypeAnalysis&amp; anonymous{VPlanVerifier.cpp}::VPlanVerifier::TypeInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a>.</p>

</div>
</div>

### VPDT {#aa9b9e8b5c3c8273a699a1c4b83d42dff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPDominatorTree&amp; anonymous{VPlanVerifier.cpp}::VPlanVerifier::VPDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a>.</p>

</div>
</div>

### WrappedIRBBs {#abd7992cd34bc3120b609dee700d57952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;BasicBlock *, 8&gt; anonymous{VPlanVerifier.cpp}::VPlanVerifier::WrappedIRBBs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-cpp">VPlanVerifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
