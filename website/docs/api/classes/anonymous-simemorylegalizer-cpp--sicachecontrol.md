---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SICacheControl` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{SIMemoryLegalizer.cpp}::SICacheControl { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol">SIGfx6CacheControl</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94ad7872dbdc8a745f93be1a330870b7">SICacheControl</a> (const GCNSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac65f6080a4714a368d3fa6062840a327">~SICacheControl</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virtual destructor to allow derivations to be deleted. <a href="#ac65f6080a4714a368d3fa6062840a327">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a19dd6d6ea7cb0bc7ea91408dea134">enableLoadCacheBypass</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory load instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>. <a href="#ae3a19dd6d6ea7cb0bc7ea91408dea134">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b9b75bcc1aab80b1aac7427ad1e61e">enableStoreCacheBypass</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory store instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>. <a href="#a50b9b75bcc1aab80b1aac7427ad1e61e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afca5c87368b586da84976ba1bf8ae594">enableRMWCacheBypass</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory read-modify-write instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>. <a href="#afca5c87368b586da84976ba1bf8ae594">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e8efdfff172cf4b21303462be453365">enableVolatileAndOrNonTemporal</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicAddrSpace AddrSpace, SIMemOp Op, bool IsVolatile, bool IsNonTemporal, bool IsLastUse=false) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory instruction of kind <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> associated with address spaces <span class="doxyComputerOutput">AddrSpace</span> to indicate it is volatile and/or nontemporal/last-use. <a href="#a7e8efdfff172cf4b21303462be453365">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeae2358f3b29f4c816a2492716358c0">expandSystemScopeStore</a> (MachineBasicBlock::iterator &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76250342dad0c88b927574249886ddc3">insertWait</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace, SIMemOp Op, bool IsCrossAddrSpaceOrdering, Position Pos, AtomicOrdering Order) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure memory instructions before <span class="doxyComputerOutput">Pos</span> of kind <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> associated with address spaces <span class="doxyComputerOutput">AddrSpace</span> have completed. <a href="#a76250342dad0c88b927574249886ddc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46a0a8c0d6d0334d1819d27d4945af83">insertAcquire</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace, Position Pos) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure any subsequent memory instructions of this thread with address spaces <span class="doxyComputerOutput">AddrSpace</span> will observe the previous memory operations by any thread for memory scopes up to memory scope <span class="doxyComputerOutput">Scope</span> . <a href="#a46a0a8c0d6d0334d1819d27d4945af83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa436c983876074d047ce6b9a4234997d">insertRelease</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace, bool IsCrossAddrSpaceOrdering, Position Pos) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure previous memory instructions by this thread with address spaces <span class="doxyComputerOutput">AddrSpace</span> have completed and can be observed by subsequent memory instructions by any thread executing in memory scope <span class="doxyComputerOutput">Scope</span>. <a href="#aa436c983876074d047ce6b9a4234997d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add8983b896ba4bf7f4dcc42842f26eeb">tryForceStoreSC0SC1</a> (const SIMemOpInfo &amp;MOI, MachineBasicBlock::iterator &amp;MI) const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2684cefdc15612e87071d36aac3858dd">enableNamedBit</a> (const MachineBasicBlock::iterator MI, AMDGPU::CPol::CPol Bit) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets named bit <span class="doxyComputerOutput">BitName</span> to "true" if present in instruction <span class="doxyComputerOutput">MI</span>. <a href="#a2684cefdc15612e87071d36aac3858dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31e7caf93ea45b3d39743fbbe2e66605">ST</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> subtarget info. <a href="#a31e7caf93ea45b3d39743fbbe2e66605">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a130c7591df8c5cec4f5326a210be3a3a">TII</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> info. <a href="#a130c7591df8c5cec4f5326a210be3a3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/amdgpu/isaversion">IsaVersion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0bc290a7f79eb2b40d404e43a7d325b">IV</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af86b41c4dc55b14178852aa49488897a">InsertCacheInv</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to insert cache invalidating instructions. <a href="#af86b41c4dc55b14178852aa49488897a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol">SICacheControl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d080c45233af5a033d89cfd7dbef1f">create</a> (const GCNSubtarget &amp;ST)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a cache control for the subtarget <span class="doxyComputerOutput">ST</span>. <a href="#a52d080c45233af5a033d89cfd7dbef1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### SICacheControl() {#a94ad7872dbdc8a745f93be1a330870b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SICacheControl::SICacheControl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp/#a02f19180c720740e1bdce2ce1746bd92">AmdgcnSkipCacheInvalidations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4c450943f424116a9b6b9a3db451af6c">llvm::AMDGPU::getIsaVersion</a>, <a href="#af86b41c4dc55b14178852aa49488897a">InsertCacheInv</a>, <a href="#aa0bc290a7f79eb2b40d404e43a7d325b">IV</a>, <a href="#a31e7caf93ea45b3d39743fbbe2e66605">ST</a> and <a href="#a130c7591df8c5cec4f5326a210be3a3a">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#a5a3b925a981abf67d4a60cbf292b77bd">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::SIGfx6CacheControl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SICacheControl() {#ac65f6080a4714a368d3fa6062840a327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{SIMemoryLegalizer.cpp}::SICacheControl::~SICacheControl ()</td>
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

<p>Virtual destructor to allow derivations to be deleted.</p>

<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### enableLoadCacheBypass() {#ae3a19dd6d6ea7cb0bc7ea91408dea134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{SIMemoryLegalizer.cpp}::SICacheControl::enableLoadCacheBypass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update <span class="doxyComputerOutput">MI</span> memory load instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>.</p>


<p>Return true iff the instruction was modified.</p>


<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### enableRMWCacheBypass() {#afca5c87368b586da84976ba1bf8ae594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{SIMemoryLegalizer.cpp}::SICacheControl::enableRMWCacheBypass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update <span class="doxyComputerOutput">MI</span> memory read-modify-write instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>.</p>


<p>Return true iff the instruction was modified.</p>


<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### enableStoreCacheBypass() {#a50b9b75bcc1aab80b1aac7427ad1e61e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{SIMemoryLegalizer.cpp}::SICacheControl::enableStoreCacheBypass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update <span class="doxyComputerOutput">MI</span> memory store instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>.</p>


<p>Return true iff the instruction was modified.</p>


<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### enableVolatileAndOrNonTemporal() {#a7e8efdfff172cf4b21303462be453365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{SIMemoryLegalizer.cpp}::SICacheControl::enableVolatileAndOrNonTemporal (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9">SIMemOp</a> Op, bool IsVolatile, bool IsNonTemporal, bool IsLastUse=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update <span class="doxyComputerOutput">MI</span> memory instruction of kind <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> associated with address spaces <span class="doxyComputerOutput">AddrSpace</span> to indicate it is volatile and/or nontemporal/last-use.</p>


<p>Return true iff the instruction was modified.</p>


<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### expandSystemScopeStore() {#abeae2358f3b29f4c816a2492716358c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{SIMemoryLegalizer.cpp}::SICacheControl::expandSystemScopeStore (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### insertAcquire() {#a46a0a8c0d6d0334d1819d27d4945af83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{SIMemoryLegalizer.cpp}::SICacheControl::insertAcquire (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2">Position</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure any subsequent memory instructions of this thread with address spaces <span class="doxyComputerOutput">AddrSpace</span> will observe the previous memory operations by any thread for memory scopes up to memory scope <span class="doxyComputerOutput">Scope</span> .</p>


<p>Returns true iff any instructions inserted.</p>


<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### insertRelease() {#aa436c983876074d047ce6b9a4234997d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{SIMemoryLegalizer.cpp}::SICacheControl::insertRelease (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, bool IsCrossAddrSpaceOrdering, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2">Position</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure previous memory instructions by this thread with address spaces <span class="doxyComputerOutput">AddrSpace</span> have completed and can be observed by subsequent memory instructions by any thread executing in memory scope <span class="doxyComputerOutput">Scope</span>.</p>


<p><span class="doxyComputerOutput">IsCrossAddrSpaceOrdering</span> indicates if the memory ordering is between address spaces. Returns true iff any instructions inserted.</p>


<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a86d0c030b48e2942c893d0a483248d4f">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::insertRelease</a>.</p>

</div>
</div>

### insertWait() {#a76250342dad0c88b927574249886ddc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{SIMemoryLegalizer.cpp}::SICacheControl::insertWait (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9">SIMemOp</a> Op, bool IsCrossAddrSpaceOrdering, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2">Position</a> Pos, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Order)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure memory instructions before <span class="doxyComputerOutput">Pos</span> of kind <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> associated with address spaces <span class="doxyComputerOutput">AddrSpace</span> have completed.</p>


<p>Used between memory instructions to enforce the order they become visible as observed by other memory instructions executing in memory scope <span class="doxyComputerOutput">Scope</span>. <span class="doxyComputerOutput">IsCrossAddrSpaceOrdering</span> indicates if the memory ordering is between address spaces. Returns true iff any instructions inserted.</p>


<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a7c935402e1e89698b7f9413d41d438e0">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::insertWait</a>.</p>

</div>
</div>

### tryForceStoreSC0SC1() {#add8983b896ba4bf7f4dcc42842f26eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{SIMemoryLegalizer.cpp}::SICacheControl::tryForceStoreSC0SC1 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopinfo">SIMemOpInfo</a> &amp; MOI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### enableNamedBit() {#a2684cefdc15612e87071d36aac3858dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SICacheControl::enableNamedBit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4">AMDGPU::CPol::CPol</a> Bit)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets named bit <span class="doxyComputerOutput">BitName</span> to "true" if present in instruction <span class="doxyComputerOutput">MI</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Returns true if <span class="doxyComputerOutput">MI</span> is modified, false otherwise.</p></dd>
</dl>


<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a130c7591df8c5cec4f5326a210be3a3a">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#aa03f2a6d9d5e121e526fc36cc33f2b02">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::enableDLCBit</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#a7bf4a0d22d0350c9acb245bce6a29ba6">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::enableGLCBit</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#aeaf42a1e6482c5b7206b5e4457d980df">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::enableNTBit</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#ae21e69d2af33292fd6909916ad7bcd00">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::enableSC0Bit</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#a2a61df2ef440c389862cc0d923637731">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::enableSC1Bit</a> and <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#ac55cfbb3c22595d8ad6cfa5a56e8765b">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::enableSLCBit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### InsertCacheInv {#af86b41c4dc55b14178852aa49488897a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIMemoryLegalizer.cpp}::SICacheControl::InsertCacheInv</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to insert cache invalidating instructions.</p>

<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#ae0677a2f7caf45722a4d780efe5f78de">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx12cachecontrol/#a91bdbe4fa62b27dc742255dd1d9b16f4">anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#a7622472f73aa2ecee214cc9fb584032b">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx7cachecontrol/#a2e161e3d05558b723efa58b0d3802ff9">anonymous{SIMemoryLegalizer.cpp}::SIGfx7CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a5b8c6d47b259060fbc531822e0f933d9">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#ad056b2534ea3030fc135769c9e2fe51c">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::insertAcquire</a> and <a href="#a94ad7872dbdc8a745f93be1a330870b7">SICacheControl</a>.</p>

</div>
</div>

### IV {#aa0bc290a7f79eb2b40d404e43a7d325b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IsaVersion anonymous{SIMemoryLegalizer.cpp}::SICacheControl::IV</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#adbdd3b28d00cd76ee5e8ec0caf4443dc">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::insertWait</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#af78f627db81fe741605f4d60420ba145">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::insertWait</a> and <a href="#a94ad7872dbdc8a745f93be1a330870b7">SICacheControl</a>.</p>

</div>
</div>

### ST {#a31e7caf93ea45b3d39743fbbe2e66605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget&amp; anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> subtarget info.</p>

<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Referenced by <a href="#a52d080c45233af5a033d89cfd7dbef1f">create</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#a35eb13e706d8492fab3bf97b8ab5864e">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::enableLoadCacheBypass</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx11cachecontrol/#ab54df9304f63eb77966bb71c4f40d001">anonymous{SIMemoryLegalizer.cpp}::SIGfx11CacheControl::enableLoadCacheBypass</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a915f43f31860091a73afdf5502616cab">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::enableLoadCacheBypass</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#ae0677a2f7caf45722a4d780efe5f78de">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx12cachecontrol/#a91bdbe4fa62b27dc742255dd1d9b16f4">anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a5b8c6d47b259060fbc531822e0f933d9">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#ad056b2534ea3030fc135769c9e2fe51c">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#adbdd3b28d00cd76ee5e8ec0caf4443dc">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::insertWait</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx12cachecontrol/#a0569f01e3d6c805c55d479767678e539">anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::insertWait</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a7c935402e1e89698b7f9413d41d438e0">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::insertWait</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx12cachecontrol/#ad46cc43080b65ebfc0a67c4bbca405a3">anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::setAtomicScope</a>, <a href="#a94ad7872dbdc8a745f93be1a330870b7">SICacheControl</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#ad7fc68a6bc85127e705cb76da2307dee">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::SIGfx10CacheControl</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx11cachecontrol/#a74823155afa35d4d0d242887a4299094">anonymous{SIMemoryLegalizer.cpp}::SIGfx11CacheControl::SIGfx11CacheControl</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx12cachecontrol/#a4810933233f160a2dbddd23095413685">anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::SIGfx12CacheControl</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#a5a3b925a981abf67d4a60cbf292b77bd">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::SIGfx6CacheControl</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx7cachecontrol/#a1d425809e77457f3adefeb79963937f0">anonymous{SIMemoryLegalizer.cpp}::SIGfx7CacheControl::SIGfx7CacheControl</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a9177aab1bbec40d0fc2c5ea04114ac29">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::SIGfx90ACacheControl</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#aa31f7ba4c335f7e3bd2133ab565b290b">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::SIGfx940CacheControl</a> and <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#aaf72a1e1847c49ad698f22517391a2c1">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::tryForceStoreSC0SC1</a>.</p>

</div>
</div>

### TII {#a130c7591df8c5cec4f5326a210be3a3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo* anonymous{SIMemoryLegalizer.cpp}::SICacheControl::TII = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> info.</p>

<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Referenced by <a href="#a2684cefdc15612e87071d36aac3858dd">enableNamedBit</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#ae0677a2f7caf45722a4d780efe5f78de">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#a7622472f73aa2ecee214cc9fb584032b">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx7cachecontrol/#a2e161e3d05558b723efa58b0d3802ff9">anonymous{SIMemoryLegalizer.cpp}::SIGfx7CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a5b8c6d47b259060fbc531822e0f933d9">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#ad056b2534ea3030fc135769c9e2fe51c">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a86d0c030b48e2942c893d0a483248d4f">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::insertRelease</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#a4ce0cfef837f200c15610c1fb1d5971f">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::insertRelease</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#adbdd3b28d00cd76ee5e8ec0caf4443dc">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::insertWait</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#af78f627db81fe741605f4d60420ba145">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::insertWait</a> and <a href="#a94ad7872dbdc8a745f93be1a330870b7">SICacheControl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a52d080c45233af5a033d89cfd7dbef1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; SICacheControl &gt; SICacheControl::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
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

<p>Create a cache control for the subtarget <span class="doxyComputerOutput">ST</span>.</p>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aafd52d574f92cc47671a38d95bca9988">llvm::AMDGPUSubtarget::SOUTHERN_ISLANDS</a> and <a href="#a31e7caf93ea45b3d39743fbbe2e66605">ST</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemorylegalizer/#a599c4517601e4b05d04b3093a7968a91">anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
