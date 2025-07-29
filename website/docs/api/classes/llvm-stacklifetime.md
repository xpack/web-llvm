---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/stacklifetime
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `StackLifetime` Class

<p>Compute live ranges of allocas. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::StackLifetime { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">llvm/Analysis/StackLifetime.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a853c31e86608f1de86ef91d4c406640a">LivenessMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, BlockLifetimeInfo &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps active slots (per bit) for each basic block. <a href="#a853c31e86608f1de86ef91d4c406640a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LivenessType { <a href="#aff0f7b0e4c6e234e72e9569968bdcaff">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b7d12beaf92aa655097451b795d14db">StackLifetime</a> (const Function &amp;F, ArrayRef&lt; const AllocaInst * &gt; Allocas, LivenessType Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25fa11bd51d7c0fde33cc3534f68abda">run</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a34dde99f929971dfc4e50bb63dd7aecb">filter_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * &gt;::const_iterator, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> *)&gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e7326c8c210290b6ba7a55cba0468cf">getMarkers</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stacklifetime/liverange">LiveRange</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ea64f921940edb72d8186f097d549b">getLiveRange</a> (const AllocaInst *AI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a set of "interesting" instructions where the given alloca is live. <a href="#ad5ea64f921940edb72d8186f097d549b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e77476be657f7560a58e59f74202522">isReachable</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if instruction is reachable from entry. <a href="#a7e77476be657f7560a58e59f74202522">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affff56a9c59c7acf83736bb564fb8a7e">isAliveAfter</a> (const AllocaInst *AI, const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the alloca is alive after the instruction. <a href="#affff56a9c59c7acf83736bb564fb8a7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stacklifetime/liverange">LiveRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81507dd38799f96ad855b5b264959e83">getFullLiveRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a live range that represents an alloca that is live throughout the entire function. <a href="#a81507dd38799f96ad855b5b264959e83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f28683f49250822b4d77ba0fedeac78">print</a> (raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2be4b150696c2057e3d565c596ceac7f">dumpAllocas</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a641f6fff9426cb5e73b03064003b7730">dumpBlockLiveness</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72d61f6fa9e9538af5ba0e4b778f4f31">dumpLiveRanges</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af31fd8b1873f849dce23e7dc26110584">collectMarkers</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec5d0b08540459fad77ac56fca7ea75">calculateLocalLiveness</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3043f869e4791aec4ffe1abe766ee8e0">calculateLiveIntervals</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a865c608a1f0902e99c9522f51e0106ab">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aff0f7b0e4c6e234e72e9569968bdcaff">LivenessType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae45fef425cbef3647ac8bb5dceba395a">Type</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">LivenessMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a448144e6951cdf06ba5eda364f99ad7f">BlockLiveness</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> *, 64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebe39503d64ea503feffc417bdd5942d">Instructions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interesting instructions. <a href="#aebe39503d64ea503feffc417bdd5942d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, std::pair&lt; unsigned, unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe17fdc06ca4a043de8f9d849a4526fd">BlockInstRange</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A range [Start, End) of instruction ids for each basic block. <a href="#afe17fdc06ca4a043de8f9d849a4526fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a053a30af5946984064bcbae456151126">Allocas</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae12685ed9efb303893993b0594c7555d">NumAllocas</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a187b0321c8f1174c75c23d1f720623">AllocaNumbering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stacklifetime/liverange">LiveRange</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55bdc95b954cc9377745be223fd2c954">LiveRanges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/stacklifetime/liverange">LiveRange</a> for allocas. <a href="#a55bdc95b954cc9377745be223fd2c954">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1ecfe87ed02fb1b9d66243028c23349">InterestingAllocas</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of allocas that have at least one lifetime.start. <a href="#aa1ecfe87ed02fb1b9d66243028c23349">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; unsigned, Marker &gt;, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab18441de7e7fcf25b69bbafd15e4c43">BBMarkers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of {InstNo, {AllocaNo, IsStart}} for each BB, ordered by InstNo. <a href="#aab18441de7e7fcf25b69bbafd15e4c43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b40e3d8ee30387fa365498c1300fca9">HasUnknownLifetimeStartOrEnd</a> = false</td>
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

<p>Compute live ranges of allocas.</p>


<p>Live ranges are represented as sets of "interesting" instructions, which are defined as instructions that may start or end an alloca's lifetime. These are:</p>


<ul class="doxyList ">
<li>lifetime.start and lifetime.end intrinsics</li>
<li>first instruction of any basic block Interesting instructions are numbered in the depth-first walk of the CFG, and in the program order inside each basic block.</li>
</ul>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LivenessMap {#a853c31e86608f1de86ef91d4c406640a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StackLifetime::LivenessMap =  DenseMap&lt;const BasicBlock *, BlockLifetimeInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps active slots (per bit) for each basic block.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### LivenessType {#aff0f7b0e4c6e234e72e9569968bdcaff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::StackLifetime::LivenessType </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">May<a id="aff0f7b0e4c6e234e72e9569968bdcaffa195fbb57ffe7449796d23466085ce6d8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Must<a id="aff0f7b0e4c6e234e72e9569968bdcaffab2b39f251bc6784f2d44d4dd72a663be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### StackLifetime() {#a5b7d12beaf92aa655097451b795d14db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackLifetime::StackLifetime (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt; Allocas, <a href="#aff0f7b0e4c6e234e72e9569968bdcaff">LivenessType</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>, definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp">StackLifetime.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/stacklifetime/lifetimeannotationwriter/#ab78f64f3d197bf994d15a2f9fa809504">llvm::StackLifetime::LifetimeAnnotationWriter::LifetimeAnnotationWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFullLiveRange() {#a81507dd38799f96ad855b5b264959e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange llvm::StackLifetime::getFullLiveRange ()</td>
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

<p>Returns a live range that represents an alloca that is live throughout the entire function.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizevgprliverange-cpp/#acc192e3e53887e1d6fa56abbe10530e6">LiveRange</a>.</p>


<p>Referenced by <a href="#a25fa11bd51d7c0fde33cc3534f68abda">run</a>.</p>

</div>
</div>

### getLiveRange() {#ad5ea64f921940edb72d8186f097d549b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StackLifetime::LiveRange &amp; StackLifetime::getLiveRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * AI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a set of "interesting" instructions where the given alloca is live.</p>


<p>Not all instructions in a function are interesting: we pick a set that is large enough for LiveRange::Overlaps to be correct.</p>


<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp">StackLifetime.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp/#a6f57985fa144303082fa7517a52e6db9">IT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a0ee1f18526ee78ef18612b6a86dc16fc">anonymous{CoroFrame.cpp}::FrameTypeBuilder::addFieldForAllocas</a> and <a href="#affff56a9c59c7acf83736bb564fb8a7e">isAliveAfter</a>.</p>

</div>
</div>

### getMarkers() {#a6e7326c8c210290b6ba7a55cba0468cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; filter_iterator&lt; ArrayRef&lt; const IntrinsicInst * &gt;::const_iterator, std::function&lt; bool(const IntrinsicInst *)&gt; &gt; &gt; llvm::StackLifetime::getMarkers ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a>.</p>

</div>
</div>

### isAliveAfter() {#affff56a9c59c7acf83736bb564fb8a7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StackLifetime::isAliveAfter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * AI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the alloca is alive after the instruction.</p>

<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp">StackLifetime.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad5ea64f921940edb72d8186f097d549b">getLiveRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/stacklifetime/liverange/#a96f9864b7e501d9432ccceb21cf29549">llvm::StackLifetime::LiveRange::test</a>.</p>

</div>
</div>

### isReachable() {#a7e77476be657f7560a58e59f74202522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StackLifetime::isReachable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if instruction is reachable from entry.</p>

<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp">StackLifetime.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### print() {#a4f28683f49250822b4d77ba0fedeac78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackLifetime::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp">StackLifetime.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stacklifetimeprinterpass/#a7d1ec1183162820291a3dcc9a0e81d45">llvm::StackLifetimePrinterPass::run</a>.</p>

</div>
</div>

### run() {#a25fa11bd51d7c0fde33cc3534f68abda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackLifetime::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp">StackLifetime.cpp</a>.</p>


<p>References <a href="#a81507dd38799f96ad855b5b264959e83">getFullLiveRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizevgprliverange-cpp/#acc192e3e53887e1d6fa56abbe10530e6">LiveRange</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aff0f7b0e4c6e234e72e9569968bdcaffa195fbb57ffe7449796d23466085ce6d8">May</a> and <a href="#aff0f7b0e4c6e234e72e9569968bdcaffab2b39f251bc6784f2d44d4dd72a663be">Must</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a0ee1f18526ee78ef18612b6a86dc16fc">anonymous{CoroFrame.cpp}::FrameTypeBuilder::addFieldForAllocas</a>, <a href="/web-llvm/docs/api/classes/anonymous-stacksafetyanalysis-cpp-/stacksafetylocalanalysis/#aaed4fd903e016ae19555330092b0e3fc">anonymous{StackSafetyAnalysis.cpp}::StackSafetyLocalAnalysis::run</a> and <a href="/web-llvm/docs/api/classes/llvm/stacklifetimeprinterpass/#a7d1ec1183162820291a3dcc9a0e81d45">llvm::StackLifetimePrinterPass::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### calculateLiveIntervals() {#a3043f869e4791aec4ffe1abe766ee8e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackLifetime::calculateLiveIntervals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp">StackLifetime.cpp</a>.</p>

</div>
</div>

### calculateLocalLiveness() {#a1ec5d0b08540459fad77ac56fca7ea75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackLifetime::calculateLocalLiveness ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp">StackLifetime.cpp</a>.</p>

</div>
</div>

### collectMarkers() {#af31fd8b1873f849dce23e7dc26110584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackLifetime::collectMarkers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp">StackLifetime.cpp</a>.</p>

</div>
</div>

### dumpAllocas() {#a2be4b150696c2057e3d565c596ceac7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void StackLifetime::dumpAllocas ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp">StackLifetime.cpp</a>.</p>

</div>
</div>

### dumpBlockLiveness() {#a641f6fff9426cb5e73b03064003b7730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void StackLifetime::dumpBlockLiveness ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>, definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp">StackLifetime.cpp</a>.</p>

</div>
</div>

### dumpLiveRanges() {#a72d61f6fa9e9538af5ba0e4b778f4f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void StackLifetime::dumpLiveRanges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>, definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp">StackLifetime.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllocaNumbering {#a4a187b0321c8f1174c75c23d1f720623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const AllocaInst *, unsigned&gt; llvm::StackLifetime::AllocaNumbering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

### Allocas {#a053a30af5946984064bcbae456151126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;const AllocaInst *&gt; llvm::StackLifetime::Allocas</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

### BBMarkers {#aab18441de7e7fcf25b69bbafd15e4c43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, SmallVector&lt;std::pair&lt;unsigned, Marker&gt;, 4&gt; &gt; llvm::StackLifetime::BBMarkers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of {InstNo, {AllocaNo, IsStart}} for each BB, ordered by InstNo.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

### BlockInstRange {#afe17fdc06ca4a043de8f9d849a4526fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, std::pair&lt;unsigned, unsigned&gt; &gt; llvm::StackLifetime::BlockInstRange</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A range [Start, End) of instruction ids for each basic block.</p>


<p>Instructions inside each BB have monotonic and consecutive ids.</p>


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

### BlockLiveness {#a448144e6951cdf06ba5eda364f99ad7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LivenessMap llvm::StackLifetime::BlockLiveness</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

### F {#a865c608a1f0902e99c9522f51e0106ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function&amp; llvm::StackLifetime::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

### HasUnknownLifetimeStartOrEnd {#a1b40e3d8ee30387fa365498c1300fca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StackLifetime::HasUnknownLifetimeStartOrEnd = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

### Instructions {#aebe39503d64ea503feffc417bdd5942d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const IntrinsicInst *, 64&gt; llvm::StackLifetime::Instructions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interesting instructions.</p>


<p>Instructions of the same block are adjustent preserve in-block order.</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

### InterestingAllocas {#aa1ecfe87ed02fb1b9d66243028c23349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::StackLifetime::InterestingAllocas</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of allocas that have at least one lifetime.start.</p>


<p>All other allocas get <a href="/web-llvm/docs/api/classes/llvm/stacklifetime/liverange">LiveRange</a> that corresponds to the entire function.</p>


<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

### LiveRanges {#a55bdc95b954cc9377745be223fd2c954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;LiveRange, 8&gt; llvm::StackLifetime::LiveRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/stacklifetime/liverange">LiveRange</a> for allocas.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

### NumAllocas {#ae12685ed9efb303893993b0594c7555d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StackLifetime::NumAllocas</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

### Type {#ae45fef425cbef3647ac8bb5dceba395a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LivenessType llvm::StackLifetime::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">StackLifetime.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp">StackLifetime.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
