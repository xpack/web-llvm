---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SIGfx940CacheControl` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol">SIGfx90ACacheControl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa31f7ba4c335f7e3bd2133ab565b290b">SIGfx940CacheControl</a> (const GCNSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad39f104e0e2cc1f9d2e2cfb1bf2022ee">enableLoadCacheBypass</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory load instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>. <a href="#ad39f104e0e2cc1f9d2e2cfb1bf2022ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4148f14632cfbce48d81655a9e07161">enableStoreCacheBypass</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory store instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>. <a href="#ae4148f14632cfbce48d81655a9e07161">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9dac420a37cf667c38e4cb598221615">enableRMWCacheBypass</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory read-modify-write instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>. <a href="#ad9dac420a37cf667c38e4cb598221615">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8b9946baa1e3ee84180bde7f21848fd">enableVolatileAndOrNonTemporal</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicAddrSpace AddrSpace, SIMemOp Op, bool IsVolatile, bool IsNonTemporal, bool IsLastUse) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory instruction of kind <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> associated with address spaces <span class="doxyComputerOutput">AddrSpace</span> to indicate it is volatile and/or nontemporal/last-use. <a href="#af8b9946baa1e3ee84180bde7f21848fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad056b2534ea3030fc135769c9e2fe51c">insertAcquire</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace, Position Pos) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure any subsequent memory instructions of this thread with address spaces <span class="doxyComputerOutput">AddrSpace</span> will observe the previous memory operations by any thread for memory scopes up to memory scope <span class="doxyComputerOutput">Scope</span> . <a href="#ad056b2534ea3030fc135769c9e2fe51c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ce0cfef837f200c15610c1fb1d5971f">insertRelease</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace, bool IsCrossAddrSpaceOrdering, Position Pos) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure previous memory instructions by this thread with address spaces <span class="doxyComputerOutput">AddrSpace</span> have completed and can be observed by subsequent memory instructions by any thread executing in memory scope <span class="doxyComputerOutput">Scope</span>. <a href="#a4ce0cfef837f200c15610c1fb1d5971f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf72a1e1847c49ad698f22517391a2c1">tryForceStoreSC0SC1</a> (const SIMemOpInfo &amp;MOI, MachineBasicBlock::iterator &amp;MI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae21e69d2af33292fd6909916ad7bcd00">enableSC0Bit</a> (const MachineBasicBlock::iterator &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets SC0 bit to "true" if present in <span class="doxyComputerOutput">MI</span>. <a href="#ae21e69d2af33292fd6909916ad7bcd00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a61df2ef440c389862cc0d923637731">enableSC1Bit</a> (const MachineBasicBlock::iterator &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets SC1 bit to "true" if present in <span class="doxyComputerOutput">MI</span>. <a href="#a2a61df2ef440c389862cc0d923637731">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaf42a1e6482c5b7206b5e4457d980df">enableNTBit</a> (const MachineBasicBlock::iterator &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets NT bit to "true" if present in <span class="doxyComputerOutput">MI</span>. <a href="#aeaf42a1e6482c5b7206b5e4457d980df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIGfx940CacheControl() {#aa31f7ba4c335f7e3bd2133ab565b290b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::SIGfx940CacheControl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
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



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a9177aab1bbec40d0fc2c5ea04114ac29">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::SIGfx90ACacheControl</a> and <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### enableLoadCacheBypass() {#ad39f104e0e2cc1f9d2e2cfb1bf2022ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx940CacheControl::enableLoadCacheBypass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
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


<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae21e69d2af33292fd6909916ad7bcd00">enableSC0Bit</a>, <a href="#a2a61df2ef440c389862cc0d923637731">enableSC1Bit</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>

</div>
</div>

### enableRMWCacheBypass() {#ad9dac420a37cf667c38e4cb598221615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx940CacheControl::enableRMWCacheBypass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
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


<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2a61df2ef440c389862cc0d923637731">enableSC1Bit</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>

</div>
</div>

### enableStoreCacheBypass() {#ae4148f14632cfbce48d81655a9e07161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx940CacheControl::enableStoreCacheBypass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
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


<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae21e69d2af33292fd6909916ad7bcd00">enableSC0Bit</a>, <a href="#a2a61df2ef440c389862cc0d923637731">enableSC1Bit</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>

</div>
</div>

### enableVolatileAndOrNonTemporal() {#af8b9946baa1e3ee84180bde7f21848fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx940CacheControl::enableVolatileAndOrNonTemporal (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9">SIMemOp</a> Op, bool IsVolatile, bool IsNonTemporal, bool IsLastUse)</td>
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


<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2ac130fda0cb93540bf1574912e78964fb">anonymous{SIMemoryLegalizer.cpp}::AFTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aeaf42a1e6482c5b7206b5e4457d980df">enableNTBit</a>, <a href="#ae21e69d2af33292fd6909916ad7bcd00">enableSC0Bit</a>, <a href="#a2a61df2ef440c389862cc0d923637731">enableSC1Bit</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a7c935402e1e89698b7f9413d41d438e0">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::insertWait</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a615d2885ef7576cedd9aafbb2578f028">anonymous{SIMemoryLegalizer.cpp}::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a3cfba54f6873dfd55b0b09d32910b20e">anonymous{SIMemoryLegalizer.cpp}::STORE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>

</div>
</div>

### insertAcquire() {#ad056b2534ea3030fc135769c9e2fe51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx940CacheControl::insertAcquire (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2">Position</a> Pos)</td>
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


<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2ac130fda0cb93540bf1574912e78964fb">anonymous{SIMemoryLegalizer.cpp}::AFTER</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#af86b41c4dc55b14178852aa49488897a">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::InsertCacheInv</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a39cdb386c8e6358db46b658828960381">llvm::AMDGPU::CPol::SC0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a4690b39a9275d5b009ecf78b08cfd27c">llvm::AMDGPU::CPol::SC1</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a130c7591df8c5cec4f5326a210be3a3a">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::TII</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>

</div>
</div>

### insertRelease() {#a4ce0cfef837f200c15610c1fb1d5971f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx940CacheControl::insertRelease (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, bool IsCrossAddrSpaceOrdering, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2">Position</a> Pos)</td>
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


<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2ac130fda0cb93540bf1574912e78964fb">anonymous{SIMemoryLegalizer.cpp}::AFTER</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a7c935402e1e89698b7f9413d41d438e0">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::insertWait</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a615d2885ef7576cedd9aafbb2578f028">anonymous{SIMemoryLegalizer.cpp}::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a39cdb386c8e6358db46b658828960381">llvm::AMDGPU::CPol::SC0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a4690b39a9275d5b009ecf78b08cfd27c">llvm::AMDGPU::CPol::SC1</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a3cfba54f6873dfd55b0b09d32910b20e">anonymous{SIMemoryLegalizer.cpp}::STORE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a130c7591df8c5cec4f5326a210be3a3a">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::TII</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>

</div>
</div>

### tryForceStoreSC0SC1() {#aaf72a1e1847c49ad698f22517391a2c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::tryForceStoreSC0SC1 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopinfo">SIMemOpInfo</a> &amp; MOI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
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



<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="#ae21e69d2af33292fd6909916ad7bcd00">enableSC0Bit</a>, <a href="#a2a61df2ef440c389862cc0d923637731">enableSC1Bit</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopinfo/#aaee7c9f7bfee121ae532821e0101327e">anonymous{SIMemoryLegalizer.cpp}::SIMemOpInfo::getInstrAddrSpace</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a03570470bad94692ce93e32700d2e1cb">anonymous{SIMemoryLegalizer.cpp}::OTHER</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a445a0aadad9b9505d6277348cd05da2c">anonymous{SIMemoryLegalizer.cpp}::SCRATCH</a> and <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### enableNTBit() {#aeaf42a1e6482c5b7206b5e4457d980df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::enableNTBit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets NT bit to "true" if present in <span class="doxyComputerOutput">MI</span>.</p>


<p>Returns true if <span class="doxyComputerOutput">MI</span> is modified, false otherwise.</p>


<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a2684cefdc15612e87071d36aac3858dd">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::enableNamedBit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a3795a38ac6eb8cb14191aaba99205a87">llvm::AMDGPU::CPol::NT</a>.</p>


<p>Referenced by <a href="#af8b9946baa1e3ee84180bde7f21848fd">enableVolatileAndOrNonTemporal</a>.</p>

</div>
</div>

### enableSC0Bit() {#ae21e69d2af33292fd6909916ad7bcd00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::enableSC0Bit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets SC0 bit to "true" if present in <span class="doxyComputerOutput">MI</span>.</p>


<p>Returns true if <span class="doxyComputerOutput">MI</span> is modified, false otherwise.</p>


<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a2684cefdc15612e87071d36aac3858dd">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::enableNamedBit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a39cdb386c8e6358db46b658828960381">llvm::AMDGPU::CPol::SC0</a>.</p>


<p>Referenced by <a href="#ad39f104e0e2cc1f9d2e2cfb1bf2022ee">enableLoadCacheBypass</a>, <a href="#ae4148f14632cfbce48d81655a9e07161">enableStoreCacheBypass</a>, <a href="#af8b9946baa1e3ee84180bde7f21848fd">enableVolatileAndOrNonTemporal</a> and <a href="#aaf72a1e1847c49ad698f22517391a2c1">tryForceStoreSC0SC1</a>.</p>

</div>
</div>

### enableSC1Bit() {#a2a61df2ef440c389862cc0d923637731}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::enableSC1Bit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets SC1 bit to "true" if present in <span class="doxyComputerOutput">MI</span>.</p>


<p>Returns true if <span class="doxyComputerOutput">MI</span> is modified, false otherwise.</p>


<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a2684cefdc15612e87071d36aac3858dd">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::enableNamedBit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a4690b39a9275d5b009ecf78b08cfd27c">llvm::AMDGPU::CPol::SC1</a>.</p>


<p>Referenced by <a href="#ad39f104e0e2cc1f9d2e2cfb1bf2022ee">enableLoadCacheBypass</a>, <a href="#ad9dac420a37cf667c38e4cb598221615">enableRMWCacheBypass</a>, <a href="#ae4148f14632cfbce48d81655a9e07161">enableStoreCacheBypass</a>, <a href="#af8b9946baa1e3ee84180bde7f21848fd">enableVolatileAndOrNonTemporal</a> and <a href="#aaf72a1e1847c49ad698f22517391a2c1">tryForceStoreSC0SC1</a>.</p>

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
