---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-simemorylegalizer-cpp-/sigfx11cachecontrol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SIGfx11CacheControl` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{SIMemoryLegalizer.cpp}::SIGfx11CacheControl { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol">SIGfx10CacheControl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx12cachecontrol">SIGfx12CacheControl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74823155afa35d4d0d242887a4299094">SIGfx11CacheControl</a> (const GCNSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab54df9304f63eb77966bb71c4f40d001">enableLoadCacheBypass</a> (const MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory load instruction to bypass any caches up to the <span class="doxyComputerOutput">Scope</span> memory scope for address spaces <span class="doxyComputerOutput">AddrSpace</span>. <a href="#ab54df9304f63eb77966bb71c4f40d001">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19094c7a8d989805ab954e60af4852be">enableVolatileAndOrNonTemporal</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicAddrSpace AddrSpace, SIMemOp Op, bool IsVolatile, bool IsNonTemporal, bool IsLastUse) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">MI</span> memory instruction of kind <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> associated with address spaces <span class="doxyComputerOutput">AddrSpace</span> to indicate it is volatile and/or nontemporal/last-use. <a href="#a19094c7a8d989805ab954e60af4852be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIGfx11CacheControl() {#a74823155afa35d4d0d242887a4299094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIMemoryLegalizer.cpp}::SIGfx11CacheControl::SIGfx11CacheControl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
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



<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#ad7fc68a6bc85127e705cb76da2307dee">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::SIGfx10CacheControl</a> and <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx12cachecontrol/#a4810933233f160a2dbddd23095413685">anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::SIGfx12CacheControl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### enableLoadCacheBypass() {#ab54df9304f63eb77966bb71c4f40d001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx11CacheControl::enableLoadCacheBypass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace)</td>
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


<p>Definition at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#a7bf4a0d22d0350c9acb245bce6a29ba6">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::enableGLCBit</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>

</div>
</div>

### enableVolatileAndOrNonTemporal() {#a19094c7a8d989805ab954e60af4852be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx11CacheControl::enableVolatileAndOrNonTemporal (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9">SIMemOp</a> Op, bool IsVolatile, bool IsNonTemporal, bool IsLastUse)</td>
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


<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2ac130fda0cb93540bf1574912e78964fb">anonymous{SIMemoryLegalizer.cpp}::AFTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#aa03f2a6d9d5e121e526fc36cc33f2b02">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::enableDLCBit</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#a7bf4a0d22d0350c9acb245bce6a29ba6">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::enableGLCBit</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#ac55cfbb3c22595d8ad6cfa5a56e8765b">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::enableSLCBit</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#adbdd3b28d00cd76ee5e8ec0caf4443dc">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::insertWait</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a615d2885ef7576cedd9aafbb2578f028">anonymous{SIMemoryLegalizer.cpp}::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a7d1379b61882d548830c6e5b216942a9a3cfba54f6873dfd55b0b09d32910b20e">anonymous{SIMemoryLegalizer.cpp}::STORE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>

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
