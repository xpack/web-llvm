---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regallocevictionadvisor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegAllocEvictionAdvisor` Class



## Declaration

<div class="doxyDeclaration">
class llvm::RegAllocEvictionAdvisor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">CodeGen/RegAllocEvictionAdvisor.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/defaultevictionadvisor">DefaultEvictionAdvisor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b0b4e86b4e406fa43f4768f55dd738f">RegAllocEvictionAdvisor</a> (const RegAllocEvictionAdvisor &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d4996508f4a35ec7352f1875d0d64c8">RegAllocEvictionAdvisor</a> (RegAllocEvictionAdvisor &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d0d898ba65160068451253f5cd0a11">RegAllocEvictionAdvisor</a> (const MachineFunction &amp;MF, const RAGreedy &amp;RA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2c111eb8eb4d1a6dfbc44771fc7550e">~RegAllocEvictionAdvisor</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4788ed56977563b684675e9394cbb56f">tryFindEvictionCandidate</a> (const LiveInterval &amp;VirtReg, const AllocationOrder &amp;Order, uint8_t CostPerUseLimit, const SmallVirtRegSet &amp;FixedRegisters) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a physical register that can be freed by evicting the FixedRegisters, or return NoRegister. <a href="#a4788ed56977563b684675e9394cbb56f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12fa23ba554defbd00ab700ffece0eb5">canEvictHintInterference</a> (const LiveInterval &amp;VirtReg, MCRegister PhysReg, const SmallVirtRegSet &amp;FixedRegisters) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find out if we can evict the live ranges occupying the given PhysReg, which is a hint (preferred register) for VirtReg. <a href="#a12fa23ba554defbd00ab700ffece0eb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7668040bfd8eabd52974d0d17645c5f3">isUnusedCalleeSavedReg</a> (MCRegister PhysReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given <span class="doxyComputerOutput">PhysReg</span> is a callee saved register and has not been used for allocation yet. <a href="#a7668040bfd8eabd52974d0d17645c5f3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0ec56bd57b2676e33aa9f1b0213f0a4">canReassign</a> (const LiveInterval &amp;VirtReg, MCRegister FromReg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d78f0675943050b646535282e211da6">getOrderLimit</a> (const LiveInterval &amp;VirtReg, const AllocationOrder &amp;Order, unsigned CostPerUseLimit) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab73980ecf32dc1f8119938c7bfb390cc">canAllocatePhysReg</a> (unsigned CostPerUseLimit, MCRegister PhysReg) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ef24df2a7b1a0c199e1933face85e44">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ragreedy">RAGreedy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81658f4e8af40f2d2a6bb91ea807042b">RA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveregmatrix">LiveRegMatrix</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad92ce3f6ffed2f967f22e87b8ff84400">Matrix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac66a00c77cf643e5e9f9074bf0f96425">LIS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e2aaf9500c32aa637f07121dc21fd17">VRM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4eb87adc2921aca1db9e5270ad210e">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00156681d3902a949b4c2e1dfe97bb15">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6311e341e3f7596d6fb11d181dc251ed">RegClassInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5950a465d7e126c5ef6360ae19855938">RegCosts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1e7ca6190354a4ad9bb230a96622bae">EnableLocalReassign</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run or not the local reassignment heuristic. <a href="#ab1e7ca6190354a4ad9bb230a96622bae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegAllocEvictionAdvisor() {#a8b0b4e86b4e406fa43f4768f55dd738f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegAllocEvictionAdvisor::RegAllocEvictionAdvisor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor">RegAllocEvictionAdvisor</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Reference <a href="#a8b0b4e86b4e406fa43f4768f55dd738f">RegAllocEvictionAdvisor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/defaultevictionadvisor/#aa84832873bdcccdbf6fc514adb1e773e">llvm::DefaultEvictionAdvisor::DefaultEvictionAdvisor</a>, <a href="#a8b0b4e86b4e406fa43f4768f55dd738f">RegAllocEvictionAdvisor</a> and <a href="#a1d4996508f4a35ec7352f1875d0d64c8">RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

### RegAllocEvictionAdvisor() {#a1d4996508f4a35ec7352f1875d0d64c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegAllocEvictionAdvisor::RegAllocEvictionAdvisor (<a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor">RegAllocEvictionAdvisor</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Reference <a href="#a8b0b4e86b4e406fa43f4768f55dd738f">RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### RegAllocEvictionAdvisor() {#a15d0d898ba65160068451253f5cd0a11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegAllocEvictionAdvisor::RegAllocEvictionAdvisor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ragreedy">RAGreedy</a> &amp; RA)</td>
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



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp">RegAllocEvictionAdvisor.cpp</a>.</p>


<p>References <a href="#ab1e7ca6190354a4ad9bb230a96622bae">EnableLocalReassign</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#ae0f42a1d485da3b65571ba06322d8c3d">EnableLocalReassignment</a>, <a href="#ac66a00c77cf643e5e9f9074bf0f96425">LIS</a>, <a href="#ad92ce3f6ffed2f967f22e87b8ff84400">Matrix</a>, <a href="#a6ef24df2a7b1a0c199e1933face85e44">MF</a>, <a href="#a5d4eb87adc2921aca1db9e5270ad210e">MRI</a>, <a href="#a81658f4e8af40f2d2a6bb91ea807042b">RA</a>, <a href="#a6311e341e3f7596d6fb11d181dc251ed">RegClassInfo</a>, <a href="#a5950a465d7e126c5ef6360ae19855938">RegCosts</a>, <a href="#a00156681d3902a949b4c2e1dfe97bb15">TRI</a> and <a href="#a6e2aaf9500c32aa637f07121dc21fd17">VRM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RegAllocEvictionAdvisor() {#ab2c111eb8eb4d1a6dfbc44771fc7550e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::RegAllocEvictionAdvisor::~RegAllocEvictionAdvisor ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canEvictHintInterference() {#a12fa23ba554defbd00ab700ffece0eb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::RegAllocEvictionAdvisor::canEvictHintInterference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a1d6cfdcc234093f39fb0719ddb649500">SmallVirtRegSet</a> &amp; FixedRegisters)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find out if we can evict the live ranges occupying the given PhysReg, which is a hint (preferred register) for VirtReg.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>References <a href="#a6ef24df2a7b1a0c199e1933face85e44">MF</a> and <a href="#a81658f4e8af40f2d2a6bb91ea807042b">RA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp/#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

### isUnusedCalleeSavedReg() {#a7668040bfd8eabd52974d0d17645c5f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocEvictionAdvisor::isUnusedCalleeSavedReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the given <span class="doxyComputerOutput">PhysReg</span> is a callee saved register and has not been used for allocation yet.</p>

<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>, definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>


<p>References <a href="#ad92ce3f6ffed2f967f22e87b8ff84400">Matrix</a> and <a href="#a6311e341e3f7596d6fb11d181dc251ed">RegClassInfo</a>.</p>


<p>Referenced by <a href="#ab73980ecf32dc1f8119938c7bfb390cc">canAllocatePhysReg</a>.</p>

</div>
</div>

### tryFindEvictionCandidate() {#a4788ed56977563b684675e9394cbb56f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MCRegister llvm::RegAllocEvictionAdvisor::tryFindEvictionCandidate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, uint8_t CostPerUseLimit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a1d6cfdcc234093f39fb0719ddb649500">SmallVirtRegSet</a> &amp; FixedRegisters)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find a physical register that can be freed by evicting the FixedRegisters, or return NoRegister.</p>


<p>The eviction decision is assumed to be correct (i.e. no fixed live ranges are evicted) and profitable.</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp/#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### canAllocatePhysReg() {#ab73980ecf32dc1f8119938c7bfb390cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocEvictionAdvisor::canAllocatePhysReg (unsigned CostPerUseLimit, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
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



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>, definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#af8403cc977c65b910e618ebcb6a12c32">llvm::MCRegister::id</a>, <a href="#a7668040bfd8eabd52974d0d17645c5f3">isUnusedCalleeSavedReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="#a6311e341e3f7596d6fb11d181dc251ed">RegClassInfo</a>, <a href="#a5950a465d7e126c5ef6360ae19855938">RegCosts</a> and <a href="#a00156681d3902a949b4c2e1dfe97bb15">TRI</a>.</p>

</div>
</div>

### canReassign() {#ab0ec56bd57b2676e33aa9f1b0213f0a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocEvictionAdvisor::canReassign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> FromReg)</td>
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



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>, definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query/#ab7eacb4ff3e11e61bbe97acaf46d47d8">llvm::LiveIntervalUnion::Query::checkInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/allocationorder/#a1d17986988f0819f29d78d1be8555c9e">llvm::AllocationOrder::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ad92ce3f6ffed2f967f22e87b8ff84400">Matrix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="#a6311e341e3f7596d6fb11d181dc251ed">RegClassInfo</a>, <a href="#a00156681d3902a949b4c2e1dfe97bb15">TRI</a> and <a href="#a6e2aaf9500c32aa637f07121dc21fd17">VRM</a>.</p>

</div>
</div>

### getOrderLimit() {#a3d78f0675943050b646535282e211da6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; RegAllocEvictionAdvisor::getOrderLimit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, unsigned CostPerUseLimit)</td>
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



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>, definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/allocationorder/#a159dc0c9f93541de35421273dcbb82c4">llvm::AllocationOrder::getOrder</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a5d4eb87adc2921aca1db9e5270ad210e">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="#a6311e341e3f7596d6fb11d181dc251ed">RegClassInfo</a>, <a href="#a5950a465d7e126c5ef6360ae19855938">RegCosts</a> and <a href="#a00156681d3902a949b4c2e1dfe97bb15">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### EnableLocalReassign {#ab1e7ca6190354a4ad9bb230a96622bae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::RegAllocEvictionAdvisor::EnableLocalReassign</td>
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

<p>Run or not the local reassignment heuristic.</p>


<p>This information is obtained from the <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a>.</p>


<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Referenced by <a href="#a15d0d898ba65160068451253f5cd0a11">RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

### LIS {#ac66a00c77cf643e5e9f9074bf0f96425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals* const llvm::RegAllocEvictionAdvisor::LIS</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Referenced by <a href="#a15d0d898ba65160068451253f5cd0a11">RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

### Matrix {#ad92ce3f6ffed2f967f22e87b8ff84400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegMatrix* const llvm::RegAllocEvictionAdvisor::Matrix</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Referenced by <a href="#ab0ec56bd57b2676e33aa9f1b0213f0a4">canReassign</a>, <a href="#a7668040bfd8eabd52974d0d17645c5f3">isUnusedCalleeSavedReg</a> and <a href="#a15d0d898ba65160068451253f5cd0a11">RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

### MF {#a6ef24df2a7b1a0c199e1933face85e44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction&amp; llvm::RegAllocEvictionAdvisor::MF</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Referenced by <a href="#a12fa23ba554defbd00ab700ffece0eb5">canEvictHintInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/defaultevictionadvisor/#aa84832873bdcccdbf6fc514adb1e773e">llvm::DefaultEvictionAdvisor::DefaultEvictionAdvisor</a> and <a href="#a15d0d898ba65160068451253f5cd0a11">RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

### MRI {#a5d4eb87adc2921aca1db9e5270ad210e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* const llvm::RegAllocEvictionAdvisor::MRI</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Referenced by <a href="#a3d78f0675943050b646535282e211da6">getOrderLimit</a> and <a href="#a15d0d898ba65160068451253f5cd0a11">RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

### RA {#a81658f4e8af40f2d2a6bb91ea807042b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RAGreedy&amp; llvm::RegAllocEvictionAdvisor::RA</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Referenced by <a href="#a12fa23ba554defbd00ab700ffece0eb5">canEvictHintInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/defaultevictionadvisor/#aa84832873bdcccdbf6fc514adb1e773e">llvm::DefaultEvictionAdvisor::DefaultEvictionAdvisor</a> and <a href="#a15d0d898ba65160068451253f5cd0a11">RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

### RegClassInfo {#a6311e341e3f7596d6fb11d181dc251ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterClassInfo&amp; llvm::RegAllocEvictionAdvisor::RegClassInfo</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Referenced by <a href="#ab73980ecf32dc1f8119938c7bfb390cc">canAllocatePhysReg</a>, <a href="#ab0ec56bd57b2676e33aa9f1b0213f0a4">canReassign</a>, <a href="#a3d78f0675943050b646535282e211da6">getOrderLimit</a>, <a href="#a7668040bfd8eabd52974d0d17645c5f3">isUnusedCalleeSavedReg</a> and <a href="#a15d0d898ba65160068451253f5cd0a11">RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

### RegCosts {#a5950a465d7e126c5ef6360ae19855938}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ArrayRef&lt;uint8_t&gt; llvm::RegAllocEvictionAdvisor::RegCosts</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Referenced by <a href="#ab73980ecf32dc1f8119938c7bfb390cc">canAllocatePhysReg</a>, <a href="#a3d78f0675943050b646535282e211da6">getOrderLimit</a> and <a href="#a15d0d898ba65160068451253f5cd0a11">RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

### TRI {#a00156681d3902a949b4c2e1dfe97bb15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* const llvm::RegAllocEvictionAdvisor::TRI</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Referenced by <a href="#ab73980ecf32dc1f8119938c7bfb390cc">canAllocatePhysReg</a>, <a href="#ab0ec56bd57b2676e33aa9f1b0213f0a4">canReassign</a>, <a href="#a3d78f0675943050b646535282e211da6">getOrderLimit</a> and <a href="#a15d0d898ba65160068451253f5cd0a11">RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

### VRM {#a6e2aaf9500c32aa637f07121dc21fd17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VirtRegMap* const llvm::RegAllocEvictionAdvisor::VRM</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Referenced by <a href="#ab0ec56bd57b2676e33aa9f1b0213f0a4">canReassign</a> and <a href="#a15d0d898ba65160068451253f5cd0a11">RegAllocEvictionAdvisor</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp">RegAllocEvictionAdvisor.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
