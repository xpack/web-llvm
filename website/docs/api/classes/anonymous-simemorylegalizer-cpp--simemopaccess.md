---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-simemorylegalizer-cpp-/simemopaccess
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SIMemOpAccess` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{SIMemoryLegalizer.cpp}::SIMemOpAccess { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98e06b2b71bf874d3a417c93155ff714">SIMemOpAccess</a> (const AMDGPUMachineModuleInfo &amp;MMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct class to support accessing the machine memory operands of instructions in the machine function <span class="doxyComputerOutput">MF</span>. <a href="#a98e06b2b71bf874d3a417c93155ff714">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopinfo">SIMemOpInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c9eaaf14f952bf7650b2b641dd189e1">getLoadInfo</a> (const MachineBasicBlock::iterator &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopinfo">SIMemOpInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ceca49cd13bf370627ce12620c1df5">getStoreInfo</a> (const MachineBasicBlock::iterator &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopinfo">SIMemOpInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c04c83bc2a4fbb5e62eca984f4b978c">getAtomicFenceInfo</a> (const MachineBasicBlock::iterator &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopinfo">SIMemOpInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3833cdce3bbe872457b464aac85063c">getAtomicCmpxchgOrRmwInfo</a> (const MachineBasicBlock::iterator &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58ace45b32f52213c9645fd1ce6d9e4d">reportUnsupported</a> (const MachineBasicBlock::iterator &amp;MI, const char *Msg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reports unsupported message <span class="doxyComputerOutput">Msg</span> for <span class="doxyComputerOutput">MI</span> to LLVM context. <a href="#a58ace45b32f52213c9645fd1ce6d9e4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::tuple&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974">SIAtomicScope</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a>, bool &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7827386f2badf5770265fab20978e571">toSIAtomicScope</a> (SyncScope::ID SSID, SIAtomicAddrSpace InstrAddrSpace) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inspects the target synchronization scope <span class="doxyComputerOutput">SSID</span> and determines the <a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a> atomic scope it corresponds to, the address spaces it covers, and whether the memory ordering applies between address spaces. <a href="#a7827386f2badf5770265fab20978e571">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77c014c77c88c8b407856ec4388efbb8">toSIAtomicAddrSpace</a> (unsigned AS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopinfo">SIMemOpInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4132f53074c1d5da89d2da80e8d081ff">constructFromMIWithMMO</a> (const MachineBasicBlock::iterator &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinemoduleinfo">AMDGPUMachineModuleInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af806963e824512bcbef4d76dc6a24acd">MMI</a> = nullptr</td>
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


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIMemOpAccess() {#a98e06b2b71bf874d3a417c93155ff714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIMemOpAccess::SIMemOpAccess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinemoduleinfo">AMDGPUMachineModuleInfo</a> &amp; MMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct class to support accessing the machine memory operands of instructions in the machine function <span class="doxyComputerOutput">MF</span>.</p>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAtomicCmpxchgOrRmwInfo() {#aa3833cdce3bbe872457b464aac85063c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SIMemOpInfo &gt; SIMemOpAccess::getAtomicCmpxchgOrRmwInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Atomic cmpxchg/rmw info if <span class="doxyComputerOutput">MI</span> is an atomic cmpxchg or rmw operation, "std::nullopt" otherwise.</p></dd>
</dl>


<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca55d8f9babd910d3931296db01832f171">llvm::SIInstrFlags::maybeAtomic</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemorylegalizer/#a599c4517601e4b05d04b3093a7968a91">anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::runOnMachineFunction</a>.</p>

</div>
</div>

### getAtomicFenceInfo() {#a5c04c83bc2a4fbb5e62eca984f4b978c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SIMemOpInfo &gt; SIMemOpAccess::getAtomicFenceInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Atomic fence info if <span class="doxyComputerOutput">MI</span> is an atomic fence operation, "std::nullopt" otherwise.</p></dd>
</dl>


<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95aef668eed93582ab6729f8a7e679d4f4a">anonymous{SIMemoryLegalizer.cpp}::ATOMIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca55d8f9babd910d3931296db01832f171">llvm::SIInstrFlags::maybeAtomic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a3a7d6d0a72ccf09bee528f6baa0bf974ab50339a10e1de285ac99d4c3990b8693">anonymous{SIMemoryLegalizer.cpp}::NONE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemorylegalizer/#a599c4517601e4b05d04b3093a7968a91">anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::runOnMachineFunction</a>.</p>

</div>
</div>

### getLoadInfo() {#a2c9eaaf14f952bf7650b2b641dd189e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SIMemOpInfo &gt; SIMemOpAccess::getLoadInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Load info if <span class="doxyComputerOutput">MI</span> is a load operation, "std::nullopt" otherwise.</p></dd>
</dl>


<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca55d8f9babd910d3931296db01832f171">llvm::SIInstrFlags::maybeAtomic</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemorylegalizer/#a599c4517601e4b05d04b3093a7968a91">anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::runOnMachineFunction</a>.</p>

</div>
</div>

### getStoreInfo() {#aa0ceca49cd13bf370627ce12620c1df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SIMemOpInfo &gt; SIMemOpAccess::getStoreInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Store info if <span class="doxyComputerOutput">MI</span> is a store operation, "std::nullopt" otherwise.</p></dd>
</dl>


<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca55d8f9babd910d3931296db01832f171">llvm::SIInstrFlags::maybeAtomic</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemorylegalizer/#a599c4517601e4b05d04b3093a7968a91">anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### constructFromMIWithMMO() {#a4132f53074c1d5da89d2da80e8d081ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SIMemOpInfo &gt; SIMemOpAccess::constructFromMIWithMMO (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Info constructed from <span class="doxyComputerOutput">MI</span>, which has at least machine memory operand.</p></dd>
</dl>


<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

### reportUnsupported() {#a58ace45b32f52213c9645fd1ce6d9e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIMemOpAccess::reportUnsupported (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reports unsupported message <span class="doxyComputerOutput">Msg</span> for <span class="doxyComputerOutput">MI</span> to LLVM context.</p>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

### toSIAtomicAddrSpace() {#a77c014c77c88c8b407856ec4388efbb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIAtomicAddrSpace SIMemOpAccess::toSIAtomicAddrSpace (unsigned AS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Return a bit set of the address spaces accessed by <span class="doxyComputerOutput">AS</span>.</p></dd>
</dl>


<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

### toSIAtomicScope() {#a7827386f2badf5770265fab20978e571}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::tuple&lt; SIAtomicScope, SIAtomicAddrSpace, bool &gt; &gt; SIMemOpAccess::toSIAtomicScope (<a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID, <a href="/web-llvm/docs/api/namespaces/anonymous-simemorylegalizer-cpp-/#a468bcaf55f58682520bae3261b54cc95">SIAtomicAddrSpace</a> InstrAddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inspects the target synchronization scope <span class="doxyComputerOutput">SSID</span> and determines the <a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a> atomic scope it corresponds to, the address spaces it covers, and whether the memory ordering applies between address spaces.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MMI {#af806963e824512bcbef4d76dc6a24acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPUMachineModuleInfo* anonymous{SIMemoryLegalizer.cpp}::SIMemOpAccess::MMI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

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
