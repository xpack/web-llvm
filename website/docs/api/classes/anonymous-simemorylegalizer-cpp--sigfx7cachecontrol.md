---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-simemorylegalizer-cpp-/sigfx7cachecontrol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SIGfx7CacheControl` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{SIMemoryLegalizer.cpp}::SIGfx7CacheControl { ... }
</div>

## Base class

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

## Derived Classes

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d425809e77457f3adefeb79963937f0">SIGfx7CacheControl</a> (const GCNSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e161e3d05558b723efa58b0d3802ff9">insertAcquire</a> (MachineBasicBlock::iterator &amp;MI, SIAtomicScope Scope, SIAtomicAddrSpace AddrSpace, Position Pos) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts any necessary instructions at position <span class="doxyComputerOutput">Pos</span> relative to instruction <span class="doxyComputerOutput">MI</span> to ensure any subsequent memory instructions of this thread with address spaces <span class="doxyComputerOutput">AddrSpace</span> will observe the previous memory operations by any thread for memory scopes up to memory scope <span class="doxyComputerOutput">Scope</span> . <a href="#a2e161e3d05558b723efa58b0d3802ff9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIGfx7CacheControl() {#a1d425809e77457f3adefeb79963937f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIMemoryLegalizer.cpp}::SIGfx7CacheControl::SIGfx7CacheControl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#a5a3b925a981abf67d4a60cbf292b77bd">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::SIGfx6CacheControl</a> and <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a31e7caf93ea45b3d39743fbbe2e66605">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::ST</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#ad7fc68a6bc85127e705cb76da2307dee">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::SIGfx10CacheControl</a> and <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a9177aab1bbec40d0fc2c5ea04114ac29">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::SIGfx90ACacheControl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### insertAcquire() {#a2e161e3d05558b723efa58b0d3802ff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIGfx7CacheControl::insertAcquire (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a> Scope, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> AddrSpace, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2">Position</a> Pos)</td>
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


<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a9e7ad3c4e4254ff96b3ddbd4a6515dc2ac130fda0cb93540bf1574912e78964fb">anonymous{SIMemoryLegalizer.cpp}::AFTER</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a355e2c58b95170df578b37fc88eadcac">anonymous{SIMemoryLegalizer.cpp}::AGENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95a6eecfba72d12922ee1dead07a0ef3334">anonymous{SIMemoryLegalizer.cpp}::GLOBAL</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#af86b41c4dc55b14178852aa49488897a">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::InsertCacheInv</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a1281d7594f66c61da2a6cacc27d613e8">llvm::AMDGPUSubtarget::isAmdPalOS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a0972f69944edd9b5edb80bab11002a3c">llvm::AMDGPUSubtarget::isMesa3DOS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974aa8710d9c2cf56b2dda4e9b798158525b">anonymous{SIMemoryLegalizer.cpp}::SINGLETHREAD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974afa177138f94a7ea01f549b1aa7893d03">anonymous{SIMemoryLegalizer.cpp}::SYSTEM</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a130c7591df8c5cec4f5326a210be3a3a">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::TII</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974a128b37580d79674baf59b5f2e15bad59">anonymous{SIMemoryLegalizer.cpp}::WAVEFRONT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974af7464491a3fc676a9c74fee700dd2973">anonymous{SIMemoryLegalizer.cpp}::WORKGROUP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a5b8c6d47b259060fbc531822e0f933d9">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::insertAcquire</a>.</p>

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
