---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/runtimepointerchecking
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RuntimePointerChecking` Class

<p>Holds information about the memory runtime legality checks to verify that a group of pointers do not overlap. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RuntimePointerChecking { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">llvm/Analysis/LoopAccessAnalysis.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7edc8945ccb0d14840604272b8ff0f10">RuntimeCheckingPtrGroup</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31fd3ecfe377ebf3eb5192da29878fa4">RuntimePointerChecking</a> (MemoryDepChecker &amp;DC, ScalarEvolution *SE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b570db2adb62a2c7ffca1869987682b">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the state of the pointer runtime information. <a href="#a1b570db2adb62a2c7ffca1869987682b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6c75313479a0d0d8dd63b870faeeac">insert</a> (Loop *Lp, Value *Ptr, const SCEV *PtrExpr, Type *AccessTy, bool WritePtr, unsigned DepSetId, unsigned ASId, PredicatedScalarEvolution &amp;PSE, bool NeedsFreeze)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a pointer and calculate the start and end SCEVs. <a href="#abe6c75313479a0d0d8dd63b870faeeac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cf66c1cf0a720805c2c9d396f9c0b1d">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>No run-time memory checking is necessary. <a href="#a9cf66c1cf0a720805c2c9d396f9c0b1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799b2020cc896db04085849aed060f20">generateChecks</a> (MemoryDepChecker::DepCandidates &amp;DepCands, bool UseDependencies)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the checks and store it. <a href="#a799b2020cc896db04085849aed060f20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a12b6596f3de8ec2382209b04c2b5444c">RuntimePointerCheck</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac837a7d2828c8fe9e84140095d003d51">getChecks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the checks that generateChecks created. <a href="#ac837a7d2828c8fe9e84140095d003d51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/pointerdiffinfo">PointerDiffInfo</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a741849368bb652fdaba99d70c36b527f">getDiffChecks</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6134973479f9ed6eb1920d0fe69b6bc9">needsChecking</a> (const RuntimeCheckingPtrGroup &amp;M, const RuntimeCheckingPtrGroup &amp;N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decide if we need to add a check between two groups of pointers, according to needsChecking. <a href="#a6134973479f9ed6eb1920d0fe69b6bc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24e5c89884a8b7b92a1d27da4e94e230">getNumberOfChecks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of run-time checks required according to needsChecking. <a href="#a24e5c89884a8b7b92a1d27da4e94e230">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a616cdd740bc8d7ccbed42ce872ca86c4">print</a> (raw_ostream &amp;OS, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the list run-time memory checks necessary. <a href="#a616cdd740bc8d7ccbed42ce872ca86c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e60690517dfc1dd58b48cbbc1e0657f">printChecks</a> (raw_ostream &amp;OS, const SmallVectorImpl&lt; RuntimePointerCheck &gt; &amp;Checks, unsigned Depth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print <span class="doxyComputerOutput">Checks</span>. <a href="#a3e60690517dfc1dd58b48cbbc1e0657f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea9847642d2da97fd896d4e79187f990">needsChecking</a> (unsigned I, unsigned J) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decide whether we need to issue a run-time check for pointer at index <span class="doxyComputerOutput">I</span> and <span class="doxyComputerOutput">J</span> to prove their independence. <a href="#aea9847642d2da97fd896d4e79187f990">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/runtimepointerchecking/pointerinfo">PointerInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad9f77ce820c5b27aee18bfe7993bf5">getPointerInfo</a> (unsigned PtrIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return <a href="/web-llvm/docs/api/structs/llvm/runtimepointerchecking/pointerinfo">PointerInfo</a> for pointer at index <span class="doxyComputerOutput">PtrIdx</span>. <a href="#acad9f77ce820c5b27aee18bfe7993bf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0218e8e5076821eef4d493245b90a3b">getSE</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f6af6c87c6754ff0bd5e625cb3c7969">groupChecks</a> (MemoryDepChecker::DepCandidates &amp;DepCands, bool UseDependencies)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Groups pointers such that a single memcheck is required between two different groups. <a href="#a7f6af6c87c6754ff0bd5e625cb3c7969">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a12b6596f3de8ec2382209b04c2b5444c">RuntimePointerCheck</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d94d10df64770bc7fb8be204a15f004">generateChecks</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the checks and return them. <a href="#a6d94d10df64770bc7fb8be204a15f004">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5628ff315c129a4d3c8ab44482eb7db8">tryToCreateDiffCheck</a> (const RuntimeCheckingPtrGroup &amp;CGI, const RuntimeCheckingPtrGroup &amp;CGJ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to create add a new (pointer-difference, access size) pair to DiffCheck for checking groups <span class="doxyComputerOutput">CGI</span> and <span class="doxyComputerOutput">CGJ</span>. <a href="#a5628ff315c129a4d3c8ab44482eb7db8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a177df4fcdf758fb57ca59102c15d30c3">Need</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This flag indicates if we need to add the runtime check. <a href="#a177df4fcdf758fb57ca59102c15d30c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/runtimepointerchecking/pointerinfo">PointerInfo</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6ad96a1c2591e0a61c92e0be5776978">Pointers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Information about the pointers that may require checking. <a href="#aa6ad96a1c2591e0a61c92e0be5776978">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/runtimecheckingptrgroup">RuntimeCheckingPtrGroup</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75861e65bcc83641cbe3c5196ba04055">CheckingGroups</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds a partitioning of pointers into "check groups". <a href="#a75861e65bcc83641cbe3c5196ba04055">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorydepchecker">MemoryDepChecker</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed2e68a70dd4d62e4714bfa348df3f23">DC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6214388084a1a4ab88f9cfaeec480a6">SE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds a pointer to the <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> analysis. <a href="#ad6214388084a1a4ab88f9cfaeec480a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a12b6596f3de8ec2382209b04c2b5444c">RuntimePointerCheck</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8995a53e847751e838184e801ec5a60">Checks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of run-time checks required to establish independence of otherwise may-aliasing pointers in the loop. <a href="#af8995a53e847751e838184e801ec5a60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbf07318ec5a5bf0f8d671e23423b07c">CanUseDiffCheck</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag indicating if pointer-difference checks can be used. <a href="#afbf07318ec5a5bf0f8d671e23423b07c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/pointerdiffinfo">PointerDiffInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a514d1cc3ae11213dc164e2ecbbfae293">DiffChecks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of (pointer-difference, access size) pairs that can be used to prove that there are no vectorization-preventing dependencies. <a href="#a514d1cc3ae11213dc164e2ecbbfae293">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ebeb3910d03eaa4e30ef67edc21df0b">arePointersInSamePartition</a> (const SmallVectorImpl&lt; int &gt; &amp;PtrToPartition, unsigned PtrIdx1, unsigned PtrIdx2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if pointers are in the same partition. <a href="#a8ebeb3910d03eaa4e30ef67edc21df0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Holds information about the memory runtime legality checks to verify that a group of pointers do not overlap.</p>

<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Friends

### RuntimeCheckingPtrGroup {#a7edc8945ccb0d14840604272b8ff0f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/runtimecheckingptrgroup">RuntimeCheckingPtrGroup</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Reference <a href="#a7edc8945ccb0d14840604272b8ff0f10">RuntimeCheckingPtrGroup</a>.</p>


<p>Referenced by <a href="#a6134973479f9ed6eb1920d0fe69b6bc9">needsChecking</a> and <a href="#a7edc8945ccb0d14840604272b8ff0f10">RuntimeCheckingPtrGroup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RuntimePointerChecking() {#a31fd3ecfe377ebf3eb5192da29878fa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimePointerChecking::RuntimePointerChecking (<a href="/web-llvm/docs/api/classes/llvm/memorydepchecker">MemoryDepChecker</a> &amp; DC, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE)</td>
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



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### empty() {#a9cf66c1cf0a720805c2c9d396f9c0b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimePointerChecking::empty ()</td>
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

<p>No run-time memory checking is necessary.</p>

<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Reference <a href="#aa6ad96a1c2591e0a61c92e0be5776978">Pointers</a>.</p>

</div>
</div>

### generateChecks() {#a799b2020cc896db04085849aed060f20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RuntimePointerChecking::generateChecks (<a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a4eb0c14b923c59b75a82bc41e03c2575">MemoryDepChecker::DepCandidates</a> &amp; DepCands, bool UseDependencies)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate the checks and store it.</p>


<p>This also performs the grouping of pointers to reduce the number of memchecks necessary.</p>


<p>Declaration at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a799b2020cc896db04085849aed060f20">generateChecks</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis/#a60735e0d022845d03d123916bb48e1e8">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::canCheckPtrAtRT</a> and <a href="#a799b2020cc896db04085849aed060f20">generateChecks</a>.</p>

</div>
</div>

### getChecks() {#ac837a7d2828c8fe9e84140095d003d51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; RuntimePointerCheck &gt; &amp; llvm::RuntimePointerChecking::getChecks ()</td>
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

<p>Returns the checks that generateChecks created.</p>


<p>They can be used to ensure no read/write accesses overlap across all loop iterations.</p>


<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-loopversioning-cpp-/#aed4891b5f4ab2e016fc238f42dfd939e">anonymous{LoopVersioning.cpp}::runImpl</a>.</p>

</div>
</div>

### getDiffChecks() {#a741849368bb652fdaba99d70c36b527f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ArrayRef&lt; PointerDiffInfo &gt; &gt; llvm::RuntimePointerChecking::getDiffChecks ()</td>
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



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>.</p>

</div>
</div>

### getNumberOfChecks() {#a24e5c89884a8b7b92a1d27da4e94e230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimePointerChecking::getNumberOfChecks ()</td>
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

<p>Returns the number of run-time checks required according to needsChecking.</p>

<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis/#a60735e0d022845d03d123916bb48e1e8">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::canCheckPtrAtRT</a>.</p>

</div>
</div>

### getPointerInfo() {#acad9f77ce820c5b27aee18bfe7993bf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PointerInfo &amp; llvm::RuntimePointerChecking::getPointerInfo (unsigned PtrIdx)</td>
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

<p>Return <a href="/web-llvm/docs/api/structs/llvm/runtimepointerchecking/pointerinfo">PointerInfo</a> for pointer at index <span class="doxyComputerOutput">PtrIdx</span>.</p>

<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Reference <a href="#aa6ad96a1c2591e0a61c92e0be5776978">Pointers</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a3afb2369af2abf8e93badf5822eca761">llvm::LoopVersioning::prepareNoAliasMetadata</a>.</p>

</div>
</div>

### getSE() {#ab0218e8e5076821eef4d493245b90a3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution * llvm::RuntimePointerChecking::getSE ()</td>
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



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### insert() {#abe6c75313479a0d0d8dd63b870faeeac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RuntimePointerChecking::insert (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * Lp, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * PtrExpr, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AccessTy, bool WritePtr, unsigned DepSetId, unsigned ASId, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, bool NeedsFreeze)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a pointer and calculate the start and end SCEVs.</p>


<p>Calculate Start and End points of memory access using getStartAndEndForAccess.</p>


<p>We need <span class="doxyComputerOutput">PSE</span> in order to compute the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression of the pointer according to the assumptions that we've made during the analysis. The method might also version the pointer stride according to <span class="doxyComputerOutput">Strides</span>, and add new predicates to <span class="doxyComputerOutput">PSE</span>.</p>


<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a10ca5eacc61b5669880de2f8b0cff33c">llvm::PredicatedScalarEvolution::getSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdd1ebe6412f9afb43d0639420afffe0">llvm::getStartAndEndForAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#adbabf05e94f95f775d59497b6b1004d8">llvm::PredicatedScalarEvolution::getSymbolicMaxBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#aa6ad96a1c2591e0a61c92e0be5776978">Pointers</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis/#add290ed56a35aadf648ebccf66491f0f">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::createCheckForAccess</a>.</p>

</div>
</div>

### needsChecking() {#a6134973479f9ed6eb1920d0fe69b6bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RuntimePointerChecking::needsChecking (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/runtimecheckingptrgroup">RuntimeCheckingPtrGroup</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/runtimecheckingptrgroup">RuntimeCheckingPtrGroup</a> &amp; N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decide if we need to add a check between two groups of pointers, according to needsChecking.</p>

<p>Declaration at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a6134973479f9ed6eb1920d0fe69b6bc9">needsChecking</a> and <a href="#a7edc8945ccb0d14840604272b8ff0f10">RuntimeCheckingPtrGroup</a>.</p>


<p>Referenced by <a href="#a6134973479f9ed6eb1920d0fe69b6bc9">needsChecking</a>.</p>

</div>
</div>

### needsChecking() {#aea9847642d2da97fd896d4e79187f990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RuntimePointerChecking::needsChecking (unsigned I, unsigned J)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decide whether we need to issue a run-time check for pointer at index <span class="doxyComputerOutput">I</span> and <span class="doxyComputerOutput">J</span> to prove their independence.</p>

<p>Declaration at line 572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/runtimepointerchecking/pointerinfo/#aa4ba7560118a4dcd0907b66f9a58384d">llvm::RuntimePointerChecking::PointerInfo::AliasSetId</a>, <a href="/web-llvm/docs/api/structs/llvm/runtimepointerchecking/pointerinfo/#a80a449988c5d5b47f20c1b3bbd2e2a31">llvm::RuntimePointerChecking::PointerInfo::DependencySetId</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/runtimepointerchecking/pointerinfo/#a6ddd46705dc2cd974b46450d7d37759e">llvm::RuntimePointerChecking::PointerInfo::IsWritePtr</a> and <a href="#aa6ad96a1c2591e0a61c92e0be5776978">Pointers</a>.</p>

</div>
</div>

### print() {#a616cdd740bc8d7ccbed42ce872ca86c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RuntimePointerChecking::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the list run-time memory checks necessary.</p>

<p>Declaration at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="#a75861e65bcc83641cbe3c5196ba04055">CheckingGroups</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="#aa6ad96a1c2591e0a61c92e0be5776978">Pointers</a> and <a href="#a3e60690517dfc1dd58b48cbbc1e0657f">printChecks</a>.</p>

</div>
</div>

### printChecks() {#a3e60690517dfc1dd58b48cbbc1e0657f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RuntimePointerChecking::printChecks (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a12b6596f3de8ec2382209b04c2b5444c">RuntimePointerCheck</a> &gt; &amp; Checks, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print <span class="doxyComputerOutput">Checks</span>.</p>

<p>Declaration at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#aa6ad96a1c2591e0a61c92e0be5776978">Pointers</a>.</p>


<p>Referenced by <a href="#a616cdd740bc8d7ccbed42ce872ca86c4">print</a>.</p>

</div>
</div>

### reset() {#a1b570db2adb62a2c7ffca1869987682b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimePointerChecking::reset ()</td>
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

<p>Reset the state of the pointer runtime information.</p>

<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>References <a href="#a177df4fcdf758fb57ca59102c15d30c3">Need</a> and <a href="#aa6ad96a1c2591e0a61c92e0be5776978">Pointers</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis/#a60735e0d022845d03d123916bb48e1e8">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::canCheckPtrAtRT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### generateChecks() {#a6d94d10df64770bc7fb8be204a15f004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; RuntimePointerCheck, 4 &gt; RuntimePointerChecking::generateChecks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate the checks and return them.</p>

<p>Declaration at line 590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### groupChecks() {#a7f6af6c87c6754ff0bd5e625cb3c7969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RuntimePointerChecking::groupChecks (<a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a4eb0c14b923c59b75a82bc41e03c2575">MemoryDepChecker::DepCandidates</a> &amp; DepCands, bool UseDependencies)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Groups pointers such that a single memcheck is required between two different groups.</p>


<p>This will clear the CheckingGroups vector and re-compute it. We will only group dependecies if <span class="doxyComputerOutput">UseDependencies</span> is true, otherwise we will create a separate group for each pointer.</p>


<p>Declaration at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### tryToCreateDiffCheck() {#a5628ff315c129a4d3c8ab44482eb7db8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RuntimePointerChecking::tryToCreateDiffCheck (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/runtimecheckingptrgroup">RuntimeCheckingPtrGroup</a> &amp; CGI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/runtimecheckingptrgroup">RuntimeCheckingPtrGroup</a> &amp; CGJ)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to create add a new (pointer-difference, access size) pair to DiffCheck for checking groups <span class="doxyComputerOutput">CGI</span> and <span class="doxyComputerOutput">CGJ</span>.</p>


<p>If pointer-difference checks cannot be used for the groups, set CanUseDiffCheck to false.</p>


<p>Declaration at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CheckingGroups {#a75861e65bcc83641cbe3c5196ba04055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RuntimeCheckingPtrGroup, 2&gt; llvm::RuntimePointerChecking::CheckingGroups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds a partitioning of pointers into "check groups".</p>

<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a3afb2369af2abf8e93badf5822eca761">llvm::LoopVersioning::prepareNoAliasMetadata</a> and <a href="#a616cdd740bc8d7ccbed42ce872ca86c4">print</a>.</p>

</div>
</div>

### Need {#a177df4fcdf758fb57ca59102c15d30c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimePointerChecking::Need = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This flag indicates if we need to add the runtime check.</p>

<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis/#a60735e0d022845d03d123916bb48e1e8">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::canCheckPtrAtRT</a> and <a href="#a1b570db2adb62a2c7ffca1869987682b">reset</a>.</p>

</div>
</div>

### Pointers {#aa6ad96a1c2591e0a61c92e0be5776978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PointerInfo, 2&gt; llvm::RuntimePointerChecking::Pointers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Information about the pointers that may require checking.</p>

<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/runtimecheckingptrgroup/#a2a9ec6fa93583e6d3806bc859a9ee94e">llvm::RuntimeCheckingPtrGroup::addPointer</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis/#a60735e0d022845d03d123916bb48e1e8">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::canCheckPtrAtRT</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#a223e50a7d4a7c2c8290b0697da780758">anonymous{LoopDistribute.cpp}::InstPartitionContainer::computePartitionSetForPointers</a>, <a href="#a9cf66c1cf0a720805c2c9d396f9c0b1d">empty</a>, <a href="#acad9f77ce820c5b27aee18bfe7993bf5">getPointerInfo</a>, <a href="#abe6c75313479a0d0d8dd63b870faeeac">insert</a>, <a href="#aea9847642d2da97fd896d4e79187f990">needsChecking</a>, <a href="#a616cdd740bc8d7ccbed42ce872ca86c4">print</a>, <a href="#a3e60690517dfc1dd58b48cbbc1e0657f">printChecks</a> and <a href="#a1b570db2adb62a2c7ffca1869987682b">reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CanUseDiffCheck {#afbf07318ec5a5bf0f8d671e23423b07c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimePointerChecking::CanUseDiffCheck = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag indicating if pointer-difference checks can be used.</p>

<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### Checks {#af8995a53e847751e838184e801ec5a60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RuntimePointerCheck, 4&gt; llvm::RuntimePointerChecking::Checks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of run-time checks required to establish independence of otherwise may-aliasing pointers in the loop.</p>

<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### DC {#aed2e68a70dd4d62e4714bfa348df3f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryDepChecker&amp; llvm::RuntimePointerChecking::DC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### DiffChecks {#a514d1cc3ae11213dc164e2ecbbfae293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PointerDiffInfo&gt; llvm::RuntimePointerChecking::DiffChecks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of (pointer-difference, access size) pairs that can be used to prove that there are no vectorization-preventing dependencies.</p>

<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### SE {#ad6214388084a1a4ab88f9cfaeec480a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* llvm::RuntimePointerChecking::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds a pointer to the <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> analysis.</p>

<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### arePointersInSamePartition() {#a8ebeb3910d03eaa4e30ef67edc21df0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RuntimePointerChecking::arePointersInSamePartition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; PtrToPartition, unsigned PtrIdx1, unsigned PtrIdx2)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if pointers are in the same partition.</p>


<p><span class="doxyComputerOutput">PtrToPartition</span> contains the partition number for pointers (-1 if the pointer belongs to multiple partitions).</p>


<p>Declaration at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
