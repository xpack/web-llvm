---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopversioning
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoopVersioning` Class Reference

<p>This class emits a version of the loop where run-time checks ensure that may-alias pointers can't overlap. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoopVersioning { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">llvm/Transforms/Utils/LoopVersioning.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab781d1d60b8dba236c33dba9ae54e087">LoopVersioning</a> (const LoopAccessInfo &amp;LAI, ArrayRef&lt; RuntimePointerCheck &gt; Checks, Loop *L, LoopInfo *LI, DominatorTree *DT, ScalarEvolution *SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expects <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> as input. <a href="#ab781d1d60b8dba236c33dba9ae54e087">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b5f9f4aa48ceb121d65679d8b1a689">versionLoop</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Performs the CFG manipulation part of versioning the loop including the <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> and <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> updates. <a href="#a65b5f9f4aa48ceb121d65679d8b1a689">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81c8a5368d02d0b52654a3efe83dec38">versionLoop</a> (const SmallVectorImpl&lt; Instruction * &gt; &amp;DefsUsedOutside)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same but if the client has already precomputed the set of values used outside the loop, this API will allows passing that. <a href="#a81c8a5368d02d0b52654a3efe83dec38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a296de170be5a983234de7d53da3c1635">getVersionedLoop</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the versioned loop. <a href="#a296de170be5a983234de7d53da3c1635">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc32c640645a5caeb9fe788699d4f75b">getNonVersionedLoop</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the fall-back loop. <a href="#afc32c640645a5caeb9fe788699d4f75b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a080fd063ce509a69475d5f80e8b2d973">annotateLoopWithNoAlias</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Annotate memory instructions in the versioned loop with no-alias metadata based on the memchecks issued. <a href="#a080fd063ce509a69475d5f80e8b2d973">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3afb2369af2abf8e93badf5822eca761">prepareNoAliasMetadata</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up the aliasing scopes based on the memchecks. <a href="#a3afb2369af2abf8e93badf5822eca761">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5da1dcc92515b7cdd28ce936d6488964">annotateInstWithNoAlias</a> (Instruction *VersionedInst, const Instruction *OrigInst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the noalias annotations to <span class="doxyComputerOutput">VersionedInst</span>. <a href="#a5da1dcc92515b7cdd28ce936d6488964">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4222829ce92822b035c2da4c4b2f2301">addPHINodes</a> (const SmallVectorImpl&lt; Instruction * &gt; &amp;DefsUsedOutside)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the necessary PHI nodes for the versioned loops based on the loop-defined values used outside of the loop. <a href="#a4222829ce92822b035c2da4c4b2f2301">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8e3355bce1ff6ac8d52d63f4940bb34">annotateInstWithNoAlias</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the noalias annotations to <span class="doxyComputerOutput">I</span>. <a href="#ac8e3355bce1ff6ac8d52d63f4940bb34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6e38ced23d434d645812ab2e0c173f4">VersionedLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The original loop. <a href="#aa6e38ced23d434d645812ab2e0c173f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5905c94f17b6b4d673ef954c41908cea">NonVersionedLoop</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The fall-back loop. <a href="#a5905c94f17b6b4d673ef954c41908cea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05391c899817c0f26591db37df2fa01d">VMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This maps the instructions from VersionedLoop to their counterpart in NonVersionedLoop. <a href="#a05391c899817c0f26591db37df2fa01d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a12b6596f3de8ec2382209b04c2b5444c">RuntimePointerCheck</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7491f57f0cca3b8b2eb22aa8afb5dae">AliasChecks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of alias checks that we are versioning for. <a href="#af7491f57f0cca3b8b2eb22aa8afb5dae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1fabc17fd4c6a77c10f82777ce3ffc1">Preds</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks that we are versioning for. <a href="#ab1fabc17fd4c6a77c10f82777ce3ffc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/runtimecheckingptrgroup">RuntimeCheckingPtrGroup</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14e8c9dff89f27f092b6bd220e298e5a">PtrToGroup</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a pointer to the pointer checking group that the pointer belongs to. <a href="#a14e8c9dff89f27f092b6bd220e298e5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/runtimecheckingptrgroup">RuntimeCheckingPtrGroup</a> *, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62da41fe0b736e8a5bef056059bd90b5">GroupToScope</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The alias scope corresponding to a pointer checking group. <a href="#a62da41fe0b736e8a5bef056059bd90b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/runtimecheckingptrgroup">RuntimeCheckingPtrGroup</a> *, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a24d9726543786281b86754cf3e34fd">GroupToNonAliasingScopeList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of alias scopes that a pointer checking group can't alias. <a href="#a4a24d9726543786281b86754cf3e34fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f5d50818633f3eab5bfced3e0dc4a4e">LAI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyses used. <a href="#a2f5d50818633f3eab5bfced3e0dc4a4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23ace17028b5695f54f647b0197388d6">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a800475a80597f92712049d208ad67d5d">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66ca5dcad6fee1936ccac49bb77af047">SE</a></td>
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

<p>This class emits a version of the loop where run-time checks ensure that may-alias pointers can't overlap.</p>


<p>It currently only supports single-exit loops and assumes that the loop already has a preheader.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopVersioning() {#ab781d1d60b8dba236c33dba9ae54e087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVersioning::LoopVersioning (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> &amp; LAI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a12b6596f3de8ec2382209b04c2b5444c">RuntimePointerCheck</a> &gt; Checks, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expects <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> as input.</p>


<p>It uses runtime check provided by the user. If <span class="doxyComputerOutput">UseLAIChecks</span> is true, we will retain the default checks made by LAI. Otherwise, construct an object having no checks and we expect the user to add them.</p>


<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopversioning-cpp">LoopVersioning.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### annotateInstWithNoAlias() {#a5da1dcc92515b7cdd28ce936d6488964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVersioning::annotateInstWithNoAlias (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * VersionedInst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * OrigInst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the noalias annotations to <span class="doxyComputerOutput">VersionedInst</span>.</p>


<p><span class="doxyComputerOutput">OrigInst</span> is the instruction corresponding to <span class="doxyComputerOutput">VersionedInst</span> in the original loop. Initialize the aliasing scopes with prepareNoAliasMetadata once before this can be called.</p>


<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>, definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopversioning-cpp">LoopVersioning.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopversioning-cpp/#a50455500f4af888548f310e92ba2055b">AnnotateNoAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a3279d6d110c594673e692308fce00fab">llvm::MDNode::concatenate</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9247a212ea89acc9573fa7e7f557eaba">llvm::Instruction::setMetadata</a>.</p>


<p>Referenced by <a href="#a080fd063ce509a69475d5f80e8b2d973">annotateLoopWithNoAlias</a>.</p>

</div>
</div>

### annotateLoopWithNoAlias() {#a080fd063ce509a69475d5f80e8b2d973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVersioning::annotateLoopWithNoAlias ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Annotate memory instructions in the versioned loop with no-alias metadata based on the memchecks issued.</p>


<p>This is just wrapper that calls prepareNoAliasMetadata and annotateInstWithNoAlias on the instructions of the versioned loop.</p>


<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopversioning-cpp">LoopVersioning.cpp</a>.</p>


<p>References <a href="#a5da1dcc92515b7cdd28ce936d6488964">annotateInstWithNoAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopversioning-cpp/#a50455500f4af888548f310e92ba2055b">AnnotateNoAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a3afb2369af2abf8e93badf5822eca761">prepareNoAliasMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-loopversioning-cpp-/#aed4891b5f4ab2e016fc238f42dfd939e">anonymous{LoopVersioning.cpp}::runImpl</a>.</p>

</div>
</div>

### getNonVersionedLoop() {#afc32c640645a5caeb9fe788699d4f75b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * llvm::LoopVersioning::getNonVersionedLoop ()</td>
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

<p>Returns the fall-back loop.</p>


<p>Control flows here if pointers in the loop may alias (i.e. one of the memchecks failed).</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a> and <a href="/web-llvm/docs/api/structs/anonymous-loopversioninglicm-cpp-/loopversioninglicm/#a24a87ea3f5cfc5c16ffff0817a8067b1">anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::run</a>.</p>

</div>
</div>

### getVersionedLoop() {#a296de170be5a983234de7d53da3c1635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * llvm::LoopVersioning::getVersionedLoop ()</td>
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

<p>Returns the versioned loop.</p>


<p>Control flows here if pointers in the loop don't alias (i.e. all memchecks passed). (This loop is actually the same as the original loop that we got constructed with.)</p>


<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-loopversioninglicm-cpp-/loopversioninglicm/#a24a87ea3f5cfc5c16ffff0817a8067b1">anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::run</a>.</p>

</div>
</div>

### prepareNoAliasMetadata() {#a3afb2369af2abf8e93badf5822eca761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVersioning::prepareNoAliasMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set up the aliasing scopes based on the memchecks.</p>


<p>This needs to be called before the first call to annotateInstWithNoAlias.</p>


<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopversioning-cpp">LoopVersioning.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#a75861e65bcc83641cbe3c5196ba04055">llvm::RuntimePointerChecking::CheckingGroups</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a29982864b11594aec54699f962f650ec">llvm::MDBuilder::createAnonymousAliasScope</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#ae2c00c06e087680961c2e70ef16e1f8f">llvm::MDBuilder::createAnonymousAliasScopeDomain</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#acad9f77ce820c5b27aee18bfe7993bf5">llvm::RuntimePointerChecking::getPointerInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/runtimepointerchecking/pointerinfo/#adc63bbc9514b000a89923bf1d1e88f1a">llvm::RuntimePointerChecking::PointerInfo::PointerValue</a>.</p>


<p>Referenced by <a href="#a080fd063ce509a69475d5f80e8b2d973">annotateLoopWithNoAlias</a>.</p>

</div>
</div>

### versionLoop() {#a65b5f9f4aa48ceb121d65679d8b1a689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVersioning::versionLoop ()</td>
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

<p>Performs the CFG manipulation part of versioning the loop including the <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> and <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> updates.</p>


<p>The loop that was used to construct the class will be the "versioned" loop i.e. the loop that will receive control if all the memchecks pass.</p>


<p>This allows the loop transform pass to operate on the same loop regardless of whether versioning was necessary or not:</p>


<p>for each loop L: analyze L if versioning is necessary version L transform L</p>


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6880d6c7da94499220b6d7dfcc3c88d4">llvm::findDefsUsedOutsideOfLoop</a> and <a href="#a65b5f9f4aa48ceb121d65679d8b1a689">versionLoop</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a6ff25bdf0db077015fe35d4a82b4b6dc">FlattenLoopPair</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#a1b795b0cd98521a7cf4ab769d9207258">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::processLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopversioninglicm-cpp-/loopversioninglicm/#a24a87ea3f5cfc5c16ffff0817a8067b1">anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::run</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loopversioning-cpp-/#aed4891b5f4ab2e016fc238f42dfd939e">anonymous{LoopVersioning.cpp}::runImpl</a> and <a href="#a65b5f9f4aa48ceb121d65679d8b1a689">versionLoop</a>.</p>

</div>
</div>

### versionLoop() {#a81c8a5368d02d0b52654a3efe83dec38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVersioning::versionLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; DefsUsedOutside)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same but if the client has already precomputed the set of values used outside the loop, this API will allows passing that.</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopversioning-cpp">LoopVersioning.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a076304d81553bb834b6d64f72e0fe055">llvm::addRuntimeChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a972c30f044db799668bdcace5544edeb">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1f7831449cd72e78894e3dcda705cd8">llvm::formDedicatedExitBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a858cab21fd29000697171b2f5b4bde31">llvm::BasicBlock::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8ec5c940fbc440c992716fbe4a48636">llvm::remapInstructionsInBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addPHINodes() {#a4222829ce92822b035c2da4c4b2f2301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVersioning::addPHINodes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; DefsUsedOutside)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds the necessary PHI nodes for the versioned loops based on the loop-defined values used outside of the loop.</p>


<p>This needs to be called after versionLoop if there are defs in the loop that are used outside the loop.</p>


<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopversioning-cpp">LoopVersioning.cpp</a>.</p>

</div>
</div>

### annotateInstWithNoAlias() {#ac8e3355bce1ff6ac8d52d63f4940bb34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVersioning::annotateInstWithNoAlias (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Add the noalias annotations to <span class="doxyComputerOutput">I</span>.</p>


<p>Initialize the aliasing scopes with prepareNoAliasMetadata once before this can be called.</p>


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AliasChecks {#af7491f57f0cca3b8b2eb22aa8afb5dae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RuntimePointerCheck, 4&gt; llvm::LoopVersioning::AliasChecks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of alias checks that we are versioning for.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>

</div>
</div>

### DT {#a800475a80597f92712049d208ad67d5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::LoopVersioning::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>

</div>
</div>

### GroupToNonAliasingScopeList {#a4a24d9726543786281b86754cf3e34fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const RuntimeCheckingPtrGroup *, MDNode *&gt; llvm::LoopVersioning::GroupToNonAliasingScopeList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of alias scopes that a pointer checking group can't alias.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>

</div>
</div>

### GroupToScope {#a62da41fe0b736e8a5bef056059bd90b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const RuntimeCheckingPtrGroup *, MDNode *&gt; llvm::LoopVersioning::GroupToScope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The alias scope corresponding to a pointer checking group.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>

</div>
</div>

### LAI {#a2f5d50818633f3eab5bfced3e0dc4a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopAccessInfo&amp; llvm::LoopVersioning::LAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyses used.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>

</div>
</div>

### LI {#a23ace17028b5695f54f647b0197388d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::LoopVersioning::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>

</div>
</div>

### NonVersionedLoop {#a5905c94f17b6b4d673ef954c41908cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::LoopVersioning::NonVersionedLoop = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The fall-back loop.</p>


<p>I.e. control flows here if pointers in the loop may alias (memchecks failed).</p>


<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>

</div>
</div>

### Preds {#ab1fabc17fd4c6a77c10f82777ce3ffc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEVPredicate&amp; llvm::LoopVersioning::Preds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks that we are versioning for.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>

</div>
</div>

### PtrToGroup {#a14e8c9dff89f27f092b6bd220e298e5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value *, const RuntimeCheckingPtrGroup *&gt; llvm::LoopVersioning::PtrToGroup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps a pointer to the pointer checking group that the pointer belongs to.</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>

</div>
</div>

### SE {#a66ca5dcad6fee1936ccac49bb77af047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* llvm::LoopVersioning::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>

</div>
</div>

### VersionedLoop {#aa6e38ced23d434d645812ab2e0c173f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::LoopVersioning::VersionedLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The original loop.</p>


<p>This becomes the "versioned" one. I.e., control flows here if pointers in the loop don't alias.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>

</div>
</div>

### VMap {#a05391c899817c0f26591db37df2fa01d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueToValueMapTy llvm::LoopVersioning::VMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This maps the instructions from VersionedLoop to their counterpart in NonVersionedLoop.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loopversioning-h">LoopVersioning.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopversioning-cpp">LoopVersioning.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
