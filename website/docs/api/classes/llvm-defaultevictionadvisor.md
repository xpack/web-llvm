---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/defaultevictionadvisor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DefaultEvictionAdvisor` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::DefaultEvictionAdvisor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">CodeGen/RegAllocEvictionAdvisor.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor">RegAllocEvictionAdvisor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa84832873bdcccdbf6fc514adb1e773e">DefaultEvictionAdvisor</a> (const MachineFunction &amp;MF, const RAGreedy &amp;RA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff4b246de34b1280466b8b728bda4157">tryFindEvictionCandidate</a> (const LiveInterval &amp;, const AllocationOrder &amp;, uint8_t, const SmallVirtRegSet &amp;) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a physical register that can be freed by evicting the FixedRegisters, or return NoRegister. <a href="#aff4b246de34b1280466b8b728bda4157">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22a76566ed72f875189d137ca972417f">canEvictHintInterference</a> (const LiveInterval &amp;, MCRegister, const SmallVirtRegSet &amp;) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>canEvictHintInterference - return true if the interference for VirtReg on the PhysReg, which is VirtReg's hint, can be evicted in favor of VirtReg. <a href="#a22a76566ed72f875189d137ca972417f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e8538c704cbf7e3f900e0d1c4a40b55">canEvictInterferenceBasedOnCost</a> (const LiveInterval &amp;, MCRegister, bool, EvictionCost &amp;, const SmallVirtRegSet &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>canEvictInterferenceBasedOnCost - Return true if all interferences between VirtReg and PhysReg can be evicted. <a href="#a8e8538c704cbf7e3f900e0d1c4a40b55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46b9ad6f22eb66ee14d0153fd8a4a464">shouldEvict</a> (const LiveInterval &amp;A, bool, const LiveInterval &amp;B, bool) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>shouldEvict - determine if A should evict the assigned live range B. <a href="#a46b9ad6f22eb66ee14d0153fd8a4a464">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DefaultEvictionAdvisor() {#aa84832873bdcccdbf6fc514adb1e773e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DefaultEvictionAdvisor::DefaultEvictionAdvisor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ragreedy">RAGreedy</a> &amp; RA)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor/#a6ef24df2a7b1a0c199e1933face85e44">llvm::RegAllocEvictionAdvisor::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor/#a81658f4e8af40f2d2a6bb91ea807042b">llvm::RegAllocEvictionAdvisor::RA</a> and <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor/#a8b0b4e86b4e406fa43f4768f55dd738f">llvm::RegAllocEvictionAdvisor::RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canEvictHintInterference() {#a22a76566ed72f875189d137ca972417f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefaultEvictionAdvisor::canEvictHintInterference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a1d6cfdcc234093f39fb0719ddb649500">SmallVirtRegSet</a> &amp; FixedRegisters)</td>
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

<p>canEvictHintInterference - return true if the interference for VirtReg on the PhysReg, which is VirtReg's hint, can be evicted in favor of VirtReg.</p>

<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp">RegAllocEvictionAdvisor.cpp</a>.</p>

</div>
</div>

### canEvictInterferenceBasedOnCost() {#a8e8538c704cbf7e3f900e0d1c4a40b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefaultEvictionAdvisor::canEvictInterferenceBasedOnCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, bool IsHint, <a href="/web-llvm/docs/api/structs/llvm/evictioncost">EvictionCost</a> &amp; MaxCost, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a1d6cfdcc234093f39fb0719ddb649500">SmallVirtRegSet</a> &amp; FixedRegisters)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>canEvictInterferenceBasedOnCost - Return true if all interferences between VirtReg and PhysReg can be evicted.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">VirtReg</td>
<td class="doxyParamItemDescription"><p>Live range that is about to be assigned.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PhysReg</td>
<td class="doxyParamItemDescription"><p>Desired register for assignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsHint</td>
<td class="doxyParamItemDescription"><p>True when PhysReg is VirtReg's preferred register.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxCost</td>
<td class="doxyParamItemDescription"><p>Only look for cheaper candidates and update with new cost when returning true.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True when interference can be evicted cheaper than MaxCost.</p></dd>
</dl>


<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp">RegAllocEvictionAdvisor.cpp</a>.</p>

</div>
</div>

### shouldEvict() {#a46b9ad6f22eb66ee14d0153fd8a4a464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefaultEvictionAdvisor::shouldEvict (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; A, bool IsHint, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; B, bool BreaksHint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>shouldEvict - determine if A should evict the assigned live range B.</p>


<p>The eviction policy defined by this function together with the allocation order defined by enqueue() decides which registers ultimately end up being split and spilled.</p>


<p>Cascade numbers are used to prevent infinite loops if this function is a cyclic relation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">A</td>
<td class="doxyParamItemDescription"><p>The live range to be assigned.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsHint</td>
<td class="doxyParamItemDescription"><p>True when A is about to be assigned to its preferred register.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">B</td>
<td class="doxyParamItemDescription"><p>The live range to be evicted.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BreaksHint</td>
<td class="doxyParamItemDescription"><p>True when B is already assigned to its preferred register.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp">RegAllocEvictionAdvisor.cpp</a>.</p>

</div>
</div>

### tryFindEvictionCandidate() {#aff4b246de34b1280466b8b728bda4157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister DefaultEvictionAdvisor::tryFindEvictionCandidate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, uint8_t CostPerUseLimit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a1d6cfdcc234093f39fb0719ddb649500">SmallVirtRegSet</a> &amp; FixedRegisters)</td>
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

<p>Find a physical register that can be freed by evicting the FixedRegisters, or return NoRegister.</p>


<p>The eviction decision is assumed to be correct (i.e. no fixed live ranges are evicted) and profitable.</p>


<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>, definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp">RegAllocEvictionAdvisor.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp">RegAllocEvictionAdvisor.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
