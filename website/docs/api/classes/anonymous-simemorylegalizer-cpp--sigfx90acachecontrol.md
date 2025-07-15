---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SIGfx90ACacheControl` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx7cachecontrol">SIGfx7CacheControl</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol">SIGfx940CacheControl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9177aab1bbec40d0fc2c5ea04114ac29">SIGfx90ACacheControl</a> (const GCNSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a915f43f31860091a73afdf5502616cab">enableLoadCacheBypass</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory load instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>. <a href="#a915f43f31860091a73afdf5502616cab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91344af58229564f9ae0daad11cfb673">enableStoreCacheBypass</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory store instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>. <a href="#a91344af58229564f9ae0daad11cfb673">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adca1c39cdb62262b4c8094588e058613">enableRMWCacheBypass</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory read-modify-write instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>. <a href="#adca1c39cdb62262b4c8094588e058613">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d384679753acdf3fa8ea66d116d55c9">enableVolatileAndOrNonTemporal</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicAddrSpace AddrSpace, SIMemOp Op, bool IsVolatile, bool IsNonTemporal, bool IsLastUse) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory instruction of kind <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> associated with address spaces <span class="doxyComputerOutput">AddrSpace</span> to indicate it is volatile and/or nontemporal/last-use. <a href="#a1d384679753acdf3fa8ea66d116d55c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c935402e1e89698b7f9413d41d438e0">insertWait</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace, SIMemOp Op, bool IsCrossAddrSpaceOrdering, Position Pos, AtomicOrdering Order) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure memory instructions before <span class="doxyComputerOutput">Pos</span> of kind <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> associated with address spaces <span class="doxyComputerOutput">AddrSpace</span> have completed. <a href="#a7c935402e1e89698b7f9413d41d438e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b8c6d47b259060fbc531822e0f933d9">insertAcquire</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace, Position Pos) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure any subsequent memory instructions of this thread with address spaces <span class="doxyComputerOutput">AddrSpace</span> will observe the previous memory operations by any thread for memory scopes up to memory scope <span class="doxyComputerOutput">Scope</span> . <a href="#a5b8c6d47b259060fbc531822e0f933d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86d0c030b48e2942c893d0a483248d4f">insertRelease</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace, bool IsCrossAddrSpaceOrdering, Position Pos) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure previous memory instructions by this thread with address spaces <span class="doxyComputerOutput">AddrSpace</span> have completed and can be observed by subsequent memory instructions by any thread executing in memory scope <span class="doxyComputerOutput">Scope</span>. <a href="#a86d0c030b48e2942c893d0a483248d4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIGfx90ACacheControl() {#a9177aab1bbec40d0fc2c5ea04114ac29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::SIGfx90ACacheControl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
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



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx7cachecontrol/#a1d425809e77457f3adefeb79963937f0">anonymous{SIMemoryLegalizer.cpp}::SIGfx7CacheControl::SIGfx7CacheControl</a> and <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#aa31f7ba4c335f7e3bd2133ab565b290b">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::SIGfx940CacheControl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### enableLoadCacheBypass() {#a915f43f31860091a73afdf5502616cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx90ACacheControl::enableLoadCacheBypass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
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

<p>Update <span class="doxyComputerOutput">MI</span> memory load instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>.</p>


<p>Return true iff the instruction was modified.</p>


<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#a7bf4a0d22d0350c9acb245bce6a29ba6">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::enableGLCBit</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>

</div>
</div>

### enableRMWCacheBypass() {#adca1c39cdb62262b4c8094588e058613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx90ACacheControl::enableRMWCacheBypass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
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

<p>Update <span class="doxyComputerOutput">MI</span> memory read-modify-write instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>.</p>


<p>Return true iff the instruction was modified.</p>


<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>

</div>
</div>

### enableStoreCacheBypass() {#a91344af58229564f9ae0daad11cfb673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx90ACacheControl::enableStoreCacheBypass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
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

<p>Update <span class="doxyComputerOutput">MI</span> memory store instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>.</p>


<p>Return true iff the instruction was modified.</p>


<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>

</div>
</div>

### enableVolatileAndOrNonTemporal() {#a1d384679753acdf3fa8ea66d116d55c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx90ACacheControl::enableVolatileAndOrNonTemporal (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9">SIMemOp</a> Op, bool IsVolatile, bool IsNonTemporal, bool IsLastUse)</td>
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


<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2ac130fda0cb93540bf1574912e78964fb">anonymous{SIMemoryLegalizer.cpp}::AFTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#a7bf4a0d22d0350c9acb245bce6a29ba6">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::enableGLCBit</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#ac55cfbb3c22595d8ad6cfa5a56e8765b">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::enableSLCBit</a>, <a href="#a7c935402e1e89698b7f9413d41d438e0">insertWait</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a615d2885ef7576cedd9aafbb2578f028">anonymous{SIMemoryLegalizer.cpp}::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a3cfba54f6873dfd55b0b09d32910b20e">anonymous{SIMemoryLegalizer.cpp}::STORE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>

</div>
</div>

### insertAcquire() {#a5b8c6d47b259060fbc531822e0f933d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx90ACacheControl::insertAcquire (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2">Position</a> Pos)</td>
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


<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2ac130fda0cb93540bf1574912e78964fb">anonymous{SIMemoryLegalizer.cpp}::AFTER</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx7cachecontrol/#a2e161e3d05558b723efa58b0d3802ff9">anonymous{SIMemoryLegalizer.cpp}::SIGfx7CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#af86b41c4dc55b14178852aa49488897a">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::InsertCacheInv</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a130c7591df8c5cec4f5326a210be3a3a">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::TII</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>

</div>
</div>

### insertRelease() {#a86d0c030b48e2942c893d0a483248d4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx90ACacheControl::insertRelease (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, bool IsCrossAddrSpaceOrdering, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2">Position</a> Pos)</td>
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


<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2ac130fda0cb93540bf1574912e78964fb">anonymous{SIMemoryLegalizer.cpp}::AFTER</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#aa436c983876074d047ce6b9a4234997d">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::insertRelease</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a39cdb386c8e6358db46b658828960381">llvm::AMDGPU::CPol::SC0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a4690b39a9275d5b009ecf78b08cfd27c">llvm::AMDGPU::CPol::SC1</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a130c7591df8c5cec4f5326a210be3a3a">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::TII</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>

</div>
</div>

### insertWait() {#a7c935402e1e89698b7f9413d41d438e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx90ACacheControl::insertWait (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9">SIMemOp</a> Op, bool IsCrossAddrSpaceOrdering, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2">Position</a> Pos, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Order)</td>
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


<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a495ebb08d96fd1ef02a05992b75a58e0">anonymous{SIMemoryLegalizer.cpp}::GDS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a76250342dad0c88b927574249886ddc3">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::insertWait</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a4e8d3f5460164e12276c09537ffb5285">anonymous{SIMemoryLegalizer.cpp}::LDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a445a0aadad9b9505d6277348cd05da2c">anonymous{SIMemoryLegalizer.cpp}::SCRATCH</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>


<p>Referenced by <a href="#a1d384679753acdf3fa8ea66d116d55c9">enableVolatileAndOrNonTemporal</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#af8b9946baa1e3ee84180bde7f21848fd">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::enableVolatileAndOrNonTemporal</a> and <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#a4ce0cfef837f200c15610c1fb1d5971f">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::insertRelease</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
