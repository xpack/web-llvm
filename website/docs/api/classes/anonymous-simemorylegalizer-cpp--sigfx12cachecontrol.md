---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-simemorylegalizer-cpp-/sigfx12cachecontrol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SIGfx12CacheControl` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx11cachecontrol">SIGfx11CacheControl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4810933233f160a2dbddd23095413685">SIGfx12CacheControl</a> (const GCNSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0569f01e3d6c805c55d479767678e539">insertWait</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace, SIMemOp Op, bool IsCrossAddrSpaceOrdering, Position Pos, AtomicOrdering Order) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure memory instructions before <span class="doxyComputerOutput">Pos</span> of kind <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> associated with address spaces <span class="doxyComputerOutput">AddrSpace</span> have completed. <a href="#a0569f01e3d6c805c55d479767678e539">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91bdbe4fa62b27dc742255dd1d9b16f4">insertAcquire</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace, Position Pos) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure any subsequent memory instructions of this thread with address spaces <span class="doxyComputerOutput">AddrSpace</span> will observe the previous memory operations by any thread for memory scopes up to memory scope <span class="doxyComputerOutput">Scope</span> . <a href="#a91bdbe4fa62b27dc742255dd1d9b16f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb56865ac127afa818b94df112fe4a2d">enableVolatileAndOrNonTemporal</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicAddrSpace AddrSpace, SIMemOp Op, bool IsVolatile, bool IsNonTemporal, bool IsLastUse) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory instruction of kind <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> associated with address spaces <span class="doxyComputerOutput">AddrSpace</span> to indicate it is volatile and/or nontemporal/last-use. <a href="#acb56865ac127afa818b94df112fe4a2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af13701df68c42f280802442b6448d530">expandSystemScopeStore</a> (MachineBasicBlock::iterator &amp;MI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd7e366e4bb57f129d2e7204e4359498">insertRelease</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace, bool IsCrossAddrSpaceOrdering, Position Pos) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure previous memory instructions by this thread with address spaces <span class="doxyComputerOutput">AddrSpace</span> have completed and can be observed by subsequent memory instructions by any thread executing in memory scope <span class="doxyComputerOutput">Scope</span>. <a href="#abd7e366e4bb57f129d2e7204e4359498">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c8cc2876c6d1863a03d926cf5e53e8">enableLoadCacheBypass</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory load instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>. <a href="#ac8c8cc2876c6d1863a03d926cf5e53e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad75eb33a640278380a562e344cc2f5a7">enableStoreCacheBypass</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory store instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>. <a href="#ad75eb33a640278380a562e344cc2f5a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec90cd5cadc970b39ca4609e79159c54">enableRMWCacheBypass</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory read-modify-write instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>. <a href="#aec90cd5cadc970b39ca4609e79159c54">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c6dfcc28519b6d7e82c3819f4735f5">setTH</a> (const MachineBasicBlock::iterator MI, AMDGPU::CPol::CPol Value) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a2ade61e77da25454c0aae4726ab8ce">setScope</a> (const MachineBasicBlock::iterator MI, AMDGPU::CPol::CPol Value) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd2b540da970228602da10afc6023333">insertWaitsBeforeSystemScopeStore</a> (const MachineBasicBlock::iterator MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad46cc43080b65ebfc0a67c4bbca405a3">setAtomicScope</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const</td>
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


<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIGfx12CacheControl() {#a4810933233f160a2dbddd23095413685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::SIGfx12CacheControl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
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



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx11cachecontrol/#a74823155afa35d4d0d242887a4299094">anonymous{SIMemoryLegalizer.cpp}::SIGfx11CacheControl::SIGfx11CacheControl</a> and <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### enableLoadCacheBypass() {#ac8c8cc2876c6d1863a03d926cf5e53e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::enableLoadCacheBypass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
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

<p>Update <span class="doxyComputerOutput">MI</span> memory load instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>.</p>


<p>Return true iff the instruction was modified.</p>


<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ad46cc43080b65ebfc0a67c4bbca405a3">setAtomicScope</a>.</p>

</div>
</div>

### enableRMWCacheBypass() {#aec90cd5cadc970b39ca4609e79159c54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::enableRMWCacheBypass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
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

<p>Update <span class="doxyComputerOutput">MI</span> memory read-modify-write instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>.</p>


<p>Return true iff the instruction was modified.</p>


<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ad46cc43080b65ebfc0a67c4bbca405a3">setAtomicScope</a>.</p>

</div>
</div>

### enableStoreCacheBypass() {#ad75eb33a640278380a562e344cc2f5a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::enableStoreCacheBypass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
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

<p>Update <span class="doxyComputerOutput">MI</span> memory store instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>.</p>


<p>Return true iff the instruction was modified.</p>


<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ad46cc43080b65ebfc0a67c4bbca405a3">setAtomicScope</a>.</p>

</div>
</div>

### enableVolatileAndOrNonTemporal() {#acb56865ac127afa818b94df112fe4a2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx12CacheControl::enableVolatileAndOrNonTemporal (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9">SIMemOp</a> Op, bool IsVolatile, bool IsNonTemporal, bool IsLastUse)</td>
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

<p>Update <span class="doxyComputerOutput">MI</span> memory instruction of kind <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> associated with address spaces <span class="doxyComputerOutput">AddrSpace</span> to indicate it is volatile and/or nontemporal/last-use.</p>


<p>Return true iff the instruction was modified.</p>


<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2ac130fda0cb93540bf1574912e78964fb">anonymous{SIMemoryLegalizer.cpp}::AFTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0569f01e3d6c805c55d479767678e539">insertWait</a>, <a href="#afd2b540da970228602da10afc6023333">insertWaitsBeforeSystemScopeStore</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a615d2885ef7576cedd9aafbb2578f028">anonymous{SIMemoryLegalizer.cpp}::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a642542075686ad680d6c3e477dc6eebd">llvm::AMDGPU::CPol::SCOPE_SYS</a>, <a href="#a8a2ade61e77da25454c0aae4726ab8ce">setScope</a>, <a href="#a37c6dfcc28519b6d7e82c3819f4735f5">setTH</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a3cfba54f6873dfd55b0b09d32910b20e">anonymous{SIMemoryLegalizer.cpp}::STORE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a8154ff62ee9b4a9eaca3572120081634">llvm::AMDGPU::CPol::TH_LU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4aaef85254998537aca69557f206ae1583">llvm::AMDGPU::CPol::TH_NT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>

</div>
</div>

### expandSystemScopeStore() {#af13701df68c42f280802442b6448d530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx12CacheControl::expandSystemScopeStore (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
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



<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="#afd2b540da970228602da10afc6023333">insertWaitsBeforeSystemScopeStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4aa8e9e83bd8766765cd8143ebfa384962">llvm::AMDGPU::CPol::SCOPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a642542075686ad680d6c3e477dc6eebd">llvm::AMDGPU::CPol::SCOPE_SYS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### insertAcquire() {#a91bdbe4fa62b27dc742255dd1d9b16f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx12CacheControl::insertAcquire (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2">Position</a> Pos)</td>
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

<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure any subsequent memory instructions of this thread with address spaces <span class="doxyComputerOutput">AddrSpace</span> will observe the previous memory operations by any thread for memory scopes up to memory scope <span class="doxyComputerOutput">Scope</span> .</p>


<p>Returns true iff any instructions inserted.</p>


<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2ac130fda0cb93540bf1574912e78964fb">anonymous{SIMemoryLegalizer.cpp}::AFTER</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#af86b41c4dc55b14178852aa49488897a">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::InsertCacheInv</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a824fd28203d9969e65c6b03a75509ef3">llvm::AMDGPU::CPol::SCOPE_DEV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a7dc2e69975fb9894a38e613ae389fd2a">llvm::AMDGPU::CPol::SCOPE_SE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a642542075686ad680d6c3e477dc6eebd">llvm::AMDGPU::CPol::SCOPE_SYS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>

</div>
</div>

### insertRelease() {#abd7e366e4bb57f129d2e7204e4359498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx12CacheControl::insertRelease (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, bool IsCrossAddrSpaceOrdering, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2">Position</a> Pos)</td>
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

<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure previous memory instructions by this thread with address spaces <span class="doxyComputerOutput">AddrSpace</span> have completed and can be observed by subsequent memory instructions by any thread executing in memory scope <span class="doxyComputerOutput">Scope</span>.</p>


<p><span class="doxyComputerOutput">IsCrossAddrSpaceOrdering</span> indicates if the memory ordering is between address spaces. Returns true iff any instructions inserted.</p>


<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2ac130fda0cb93540bf1574912e78964fb">anonymous{SIMemoryLegalizer.cpp}::AFTER</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="#a0569f01e3d6c805c55d479767678e539">insertWait</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a615d2885ef7576cedd9aafbb2578f028">anonymous{SIMemoryLegalizer.cpp}::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a642542075686ad680d6c3e477dc6eebd">llvm::AMDGPU::CPol::SCOPE_SYS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a3cfba54f6873dfd55b0b09d32910b20e">anonymous{SIMemoryLegalizer.cpp}::STORE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>

</div>
</div>

### insertWait() {#a0569f01e3d6c805c55d479767678e539}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx12CacheControl::insertWait (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9">SIMemOp</a> Op, bool IsCrossAddrSpaceOrdering, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2">Position</a> Pos, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Order)</td>
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

<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure memory instructions before <span class="doxyComputerOutput">Pos</span> of kind <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> associated with address spaces <span class="doxyComputerOutput">AddrSpace</span> have completed.</p>


<p>Used between memory instructions to enforce the order they become visible as observed by other memory instructions executing in memory scope <span class="doxyComputerOutput">Scope</span>. <span class="doxyComputerOutput">IsCrossAddrSpaceOrdering</span> indicates if the memory ordering is between address spaces. Returns true iff any instructions inserted.</p>


<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2ac130fda0cb93540bf1574912e78964fb">anonymous{SIMemoryLegalizer.cpp}::AFTER</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a4e8d3f5460164e12276c09537ffb5285">anonymous{SIMemoryLegalizer.cpp}::LDS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a615d2885ef7576cedd9aafbb2578f028">anonymous{SIMemoryLegalizer.cpp}::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a445a0aadad9b9505d6277348cd05da2c">anonymous{SIMemoryLegalizer.cpp}::SCRATCH</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a3cfba54f6873dfd55b0b09d32910b20e">anonymous{SIMemoryLegalizer.cpp}::STORE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>


<p>Referenced by <a href="#acb56865ac127afa818b94df112fe4a2d">enableVolatileAndOrNonTemporal</a> and <a href="#abd7e366e4bb57f129d2e7204e4359498">insertRelease</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### insertWaitsBeforeSystemScopeStore() {#afd2b540da970228602da10afc6023333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx12CacheControl::insertWaitsBeforeSystemScopeStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
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



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#acb56865ac127afa818b94df112fe4a2d">enableVolatileAndOrNonTemporal</a> and <a href="#af13701df68c42f280802442b6448d530">expandSystemScopeStore</a>.</p>

</div>
</div>

### setAtomicScope() {#ad46cc43080b65ebfc0a67c4bbca405a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx12CacheControl::setAtomicScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
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



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a824fd28203d9969e65c6b03a75509ef3">llvm::AMDGPU::CPol::SCOPE_DEV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a7dc2e69975fb9894a38e613ae389fd2a">llvm::AMDGPU::CPol::SCOPE_SE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a642542075686ad680d6c3e477dc6eebd">llvm::AMDGPU::CPol::SCOPE_SYS</a>, <a href="#a8a2ade61e77da25454c0aae4726ab8ce">setScope</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>


<p>Referenced by <a href="#ac8c8cc2876c6d1863a03d926cf5e53e8">enableLoadCacheBypass</a>, <a href="#aec90cd5cadc970b39ca4609e79159c54">enableRMWCacheBypass</a> and <a href="#ad75eb33a640278380a562e344cc2f5a7">enableStoreCacheBypass</a>.</p>

</div>
</div>

### setScope() {#a8a2ade61e77da25454c0aae4726ab8ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx12CacheControl::setScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4">AMDGPU::CPol::CPol</a> Value)</td>
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



<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4aa8e9e83bd8766765cd8143ebfa384962">llvm::AMDGPU::CPol::SCOPE</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#acb56865ac127afa818b94df112fe4a2d">enableVolatileAndOrNonTemporal</a> and <a href="#ad46cc43080b65ebfc0a67c4bbca405a3">setAtomicScope</a>.</p>

</div>
</div>

### setTH() {#a37c6dfcc28519b6d7e82c3819f4735f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx12CacheControl::setTH (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4">AMDGPU::CPol::CPol</a> Value)</td>
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



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4ada8257c4b012c0b7ec22b9b95d8ce960">llvm::AMDGPU::CPol::TH</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#acb56865ac127afa818b94df112fe4a2d">enableVolatileAndOrNonTemporal</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
