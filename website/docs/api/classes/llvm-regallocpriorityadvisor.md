---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regallocpriorityadvisor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegAllocPriorityAdvisor` Class

<p>Interface to the priority advisor, which is responsible for prioritizing live ranges. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RegAllocPriorityAdvisor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">CodeGen/RegAllocPriorityAdvisor.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/defaultpriorityadvisor">DefaultPriorityAdvisor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dummypriorityadvisor">DummyPriorityAdvisor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stupid priority advisor which just enqueues in virtual register number order, for debug purposes only. <a href="/web-llvm/docs/api/classes/llvm/dummypriorityadvisor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mlpriorityadvisor">MLPriorityAdvisor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f50907e5573ee63e225caf72e35673">RegAllocPriorityAdvisor</a> (const RegAllocPriorityAdvisor &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45ef2e848a3f707003ea7a20102e41f1">RegAllocPriorityAdvisor</a> (RegAllocPriorityAdvisor &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93fefa160e531e5699da7ae4101402c4">RegAllocPriorityAdvisor</a> (const MachineFunction &amp;MF, const RAGreedy &amp;RA, SlotIndexes *const Indexes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d6da5c503806f8218310f145df7ef58">~RegAllocPriorityAdvisor</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1f86b038750abea2e1199a82b025078">getPriority</a> (const LiveInterval &amp;LI) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the priority value for a live range. <a href="#aa1f86b038750abea2e1199a82b025078">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ragreedy">RAGreedy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf987014e5e42fb7b026f07f6531c4e6">RA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e72c6a436fed1360e0bc99ef12d584e">LIS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29d23ab9c722bc3aff786b37fa5f8b6">VRM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d8161ab3a1bc799758a2be5623744e">MRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad958c6ee6b3412fa7b414e5b3b0458c4">TRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00da5e93bfe1441435dbf1aac0ead827">RegClassInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d874faa48e46514c877bd65bd0c2cd">Indexes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e56cef5c30ab91fec973bfb3d394f9c">RegClassPriorityTrumpsGlobalness</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76893390e810f01592573d68b0776b8f">ReverseLocalAssignment</a></td>
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

<p>Interface to the priority advisor, which is responsible for prioritizing live ranges.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegAllocPriorityAdvisor() {#a24f50907e5573ee63e225caf72e35673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegAllocPriorityAdvisor::RegAllocPriorityAdvisor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisor">RegAllocPriorityAdvisor</a> &amp;)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Reference <a href="#a24f50907e5573ee63e225caf72e35673">RegAllocPriorityAdvisor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/defaultpriorityadvisor/#a6b56a26431d84ec4b815ad8f2c9c171f">llvm::DefaultPriorityAdvisor::DefaultPriorityAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/dummypriorityadvisor/#a268947993c60a084692eb45ade3e99ce">llvm::DummyPriorityAdvisor::DummyPriorityAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/mlpriorityadvisor/#a759268285d8a8848331c37e4ff4de310">llvm::MLPriorityAdvisor::getDefaultAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/mlpriorityadvisor/#a4fb81be52acc66e8ae6c35bd889bd10d">llvm::MLPriorityAdvisor::MLPriorityAdvisor</a>, <a href="#a24f50907e5573ee63e225caf72e35673">RegAllocPriorityAdvisor</a> and <a href="#a45ef2e848a3f707003ea7a20102e41f1">RegAllocPriorityAdvisor</a>.</p>

</div>
</div>

### RegAllocPriorityAdvisor() {#a45ef2e848a3f707003ea7a20102e41f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegAllocPriorityAdvisor::RegAllocPriorityAdvisor (<a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisor">RegAllocPriorityAdvisor</a> &amp;&amp;)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Reference <a href="#a24f50907e5573ee63e225caf72e35673">RegAllocPriorityAdvisor</a>.</p>

</div>
</div>

### RegAllocPriorityAdvisor() {#a93fefa160e531e5699da7ae4101402c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegAllocPriorityAdvisor::RegAllocPriorityAdvisor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ragreedy">RAGreedy</a> &amp; RA, <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Indexes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-cpp">RegAllocPriorityAdvisor.cpp</a>.</p>


<p>References <a href="#aa0d874faa48e46514c877bd65bd0c2cd">Indexes</a>, <a href="#a0e72c6a436fed1360e0bc99ef12d584e">LIS</a>, <a href="#a05d8161ab3a1bc799758a2be5623744e">MRI</a>, <a href="#abf987014e5e42fb7b026f07f6531c4e6">RA</a>, <a href="#a00da5e93bfe1441435dbf1aac0ead827">RegClassInfo</a>, <a href="#a2e56cef5c30ab91fec973bfb3d394f9c">RegClassPriorityTrumpsGlobalness</a>, <a href="#a76893390e810f01592573d68b0776b8f">ReverseLocalAssignment</a>, <a href="#ad958c6ee6b3412fa7b414e5b3b0458c4">TRI</a> and <a href="#ad29d23ab9c722bc3aff786b37fa5f8b6">VRM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RegAllocPriorityAdvisor() {#a9d6da5c503806f8218310f145df7ef58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::RegAllocPriorityAdvisor::~RegAllocPriorityAdvisor ()</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPriority() {#aa1f86b038750abea2e1199a82b025078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::RegAllocPriorityAdvisor::getPriority (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the priority value for a live range.</p>


<p>A float value is used since ML prefers it.</p>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>References <a href="#aa0d874faa48e46514c877bd65bd0c2cd">Indexes</a> and <a href="#abf987014e5e42fb7b026f07f6531c4e6">RA</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Indexes {#aa0d874faa48e46514c877bd65bd0c2cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndexes* const llvm::RegAllocPriorityAdvisor::Indexes</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/defaultpriorityadvisor/#a6b56a26431d84ec4b815ad8f2c9c171f">llvm::DefaultPriorityAdvisor::DefaultPriorityAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/dummypriorityadvisor/#a268947993c60a084692eb45ade3e99ce">llvm::DummyPriorityAdvisor::DummyPriorityAdvisor</a>, <a href="#aa1f86b038750abea2e1199a82b025078">getPriority</a>, <a href="/web-llvm/docs/api/classes/llvm/mlpriorityadvisor/#a4fb81be52acc66e8ae6c35bd889bd10d">llvm::MLPriorityAdvisor::MLPriorityAdvisor</a> and <a href="#a93fefa160e531e5699da7ae4101402c4">RegAllocPriorityAdvisor</a>.</p>

</div>
</div>

### LIS {#a0e72c6a436fed1360e0bc99ef12d584e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals* const llvm::RegAllocPriorityAdvisor::LIS</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Referenced by <a href="#a93fefa160e531e5699da7ae4101402c4">RegAllocPriorityAdvisor</a>.</p>

</div>
</div>

### MRI {#a05d8161ab3a1bc799758a2be5623744e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* const llvm::RegAllocPriorityAdvisor::MRI</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Referenced by <a href="#a93fefa160e531e5699da7ae4101402c4">RegAllocPriorityAdvisor</a>.</p>

</div>
</div>

### RA {#abf987014e5e42fb7b026f07f6531c4e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RAGreedy&amp; llvm::RegAllocPriorityAdvisor::RA</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/defaultpriorityadvisor/#a6b56a26431d84ec4b815ad8f2c9c171f">llvm::DefaultPriorityAdvisor::DefaultPriorityAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/dummypriorityadvisor/#a268947993c60a084692eb45ade3e99ce">llvm::DummyPriorityAdvisor::DummyPriorityAdvisor</a>, <a href="#aa1f86b038750abea2e1199a82b025078">getPriority</a>, <a href="/web-llvm/docs/api/classes/llvm/mlpriorityadvisor/#ab1ca75ff5e477978c030cd3040346f3d">llvm::MLPriorityAdvisor::getPriorityImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mlpriorityadvisor/#a4fb81be52acc66e8ae6c35bd889bd10d">llvm::MLPriorityAdvisor::MLPriorityAdvisor</a> and <a href="#a93fefa160e531e5699da7ae4101402c4">RegAllocPriorityAdvisor</a>.</p>

</div>
</div>

### RegClassInfo {#a00da5e93bfe1441435dbf1aac0ead827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterClassInfo&amp; llvm::RegAllocPriorityAdvisor::RegClassInfo</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Referenced by <a href="#a93fefa160e531e5699da7ae4101402c4">RegAllocPriorityAdvisor</a>.</p>

</div>
</div>

### RegClassPriorityTrumpsGlobalness {#a2e56cef5c30ab91fec973bfb3d394f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::RegAllocPriorityAdvisor::RegClassPriorityTrumpsGlobalness</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Referenced by <a href="#a93fefa160e531e5699da7ae4101402c4">RegAllocPriorityAdvisor</a>.</p>

</div>
</div>

### ReverseLocalAssignment {#a76893390e810f01592573d68b0776b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::RegAllocPriorityAdvisor::ReverseLocalAssignment</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Referenced by <a href="#a93fefa160e531e5699da7ae4101402c4">RegAllocPriorityAdvisor</a>.</p>

</div>
</div>

### TRI {#ad958c6ee6b3412fa7b414e5b3b0458c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* const llvm::RegAllocPriorityAdvisor::TRI</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Referenced by <a href="#a93fefa160e531e5699da7ae4101402c4">RegAllocPriorityAdvisor</a>.</p>

</div>
</div>

### VRM {#ad29d23ab9c722bc3aff786b37fa5f8b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VirtRegMap* const llvm::RegAllocPriorityAdvisor::VRM</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Referenced by <a href="#a93fefa160e531e5699da7ae4101402c4">RegAllocPriorityAdvisor</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-cpp">RegAllocPriorityAdvisor.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
