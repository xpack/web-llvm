---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regallocbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegAllocBase` Class

<p><a href="/web-llvm/docs/api/classes/llvm/regallocbase">RegAllocBase</a> provides the register allocation driver and interface that can be extended to add interesting heuristics. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RegAllocBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">CodeGen/RegAllocBase.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic">RABasic</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic">RABasic</a> provides a minimal implementation of the basic register allocation algorithm. <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ragreedy">RAGreedy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a012fb04b333e4c8875594766fd9f076a">RegAllocBase</a> (const RegAllocFilterFunc F=nullptr)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a942377d78de304f20a6037ae4edbe1">~RegAllocBase</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e9547b9bc56b02aad18e54488c8059b">init</a> (VirtRegMap &amp;vrm, LiveIntervals &amp;lis, LiveRegMatrix &amp;mat)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee328fb90c6cef95857090cdc67de0d4">shouldAllocateRegister</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get whether a given register should be allocated. <a href="#aee328fb90c6cef95857090cdc67de0d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35fef2aafb20ef4b079d0819394e87d">allocatePhysRegs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93e2dd7d80790456c7201dc40d3b1263">postOptimization</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spiller">Spiller</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49d5127f2ab5ad47f9b00a889948dd91">spiller</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac41354781f406aa77d665f9e5aec8309">enqueueImpl</a> (const LiveInterval *LI)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>enqueue - Add VirtReg to the priority queue of unassigned registers. <a href="#ac41354781f406aa77d665f9e5aec8309">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d4798520a9880c2b801fd18ff8342d2">enqueue</a> (const LiveInterval *LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>enqueue - Add VirtReg to the priority queue of unassigned registers. <a href="#a1d4798520a9880c2b801fd18ff8342d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c9575386e3e74d0ebf3b80ec946feda">dequeue</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dequeue - Return the next unassigned register, or NULL. <a href="#a8c9575386e3e74d0ebf3b80ec946feda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10ad31d44cbe980bf48cbb166a924091">selectOrSplit</a> (const LiveInterval &amp;VirtReg, SmallVectorImpl&lt; Register &gt; &amp;splitLVRs)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1558554539a5b133b8e361c0517e9fb1">getErrorAssignment</a> (const TargetRegisterClass &amp;RC, const MachineInstr *CtxMI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query a physical register to use as a filler in contexts where the allocation has failed. <a href="#a1558554539a5b133b8e361c0517e9fb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a064c82f883b28000d10199532b1c35">aboutToRemoveInterval</a> (const LiveInterval &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method called when the allocator is about to remove a <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a>. <a href="#a0a064c82f883b28000d10199532b1c35">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71dacb3fb537bf1648c1b1cb7ebded58">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af47f48e36ce2f7d72e0f4536dc48f330">seedLiveRegs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a523cbc58f79fe5e9e95dc87f9cee8a36">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba058f684e1b6704e5b4a09f889ec18c">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96bb57a8041a40ded1ba0ef3b411a615">VRM</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a575345318339b28557a6c8ea57708434">LIS</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveregmatrix">LiveRegMatrix</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a865e0247c5f922b8afaaaec481e4939c">Matrix</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6330bc662bf646d769c2a0771282eaf">RegClassInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a073386d697a3adacf27699bd95441d">DeadRemats</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inst which is a def of an original reg and whose defs are already all dead after remat is saved in DeadRemats. <a href="#a3a073386d697a3adacf27699bd95441d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a0ab9dba764b528b15e89f9c443b2e202">RegAllocFilterFunc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade24838a8fad55b383378261c91a5b6a">shouldAllocateRegisterImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Private, callees should go through shouldAllocateRegister. <a href="#ade24838a8fad55b383378261c91a5b6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbeaddcf447db994c372dfff591105ac">VerifyEnabled</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VerifyEnabled - True when -verify-regalloc is given. <a href="#afbeaddcf447db994c372dfff591105ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a666d8b67c14d35f657e591cb87984592">TimerGroupName</a>[] = "regalloc"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a298de4027780720785b5cd3479e92">TimerGroupDescription</a>[] = "Register Allocation"</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/regallocbase">RegAllocBase</a> provides the register allocation driver and interface that can be extended to add interesting heuristics.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> allocators must override the <a href="#a10ad31d44cbe980bf48cbb166a924091">selectOrSplit()</a> method to implement live range splitting. They must also override enqueue/dequeue to provide an assignment order.</p>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### RegAllocBase() {#a012fb04b333e4c8875594766fd9f076a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegAllocBase::RegAllocBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a0ab9dba764b528b15e89f9c443b2e202">RegAllocFilterFunc</a> F=nullptr)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a8e9b0771270f5d554cb9b66c1fc2f586">anonymous{RegAllocBasic.cpp}::RABasic::RABasic</a> and <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#abc503bf8aca22e0b405fbdf940ec76a2">llvm::RAGreedy::RAGreedy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~RegAllocBase() {#a2a942377d78de304f20a6037ae4edbe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::RegAllocBase::~RegAllocBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### aboutToRemoveInterval() {#a0a064c82f883b28000d10199532b1c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::RegAllocBase::aboutToRemoveInterval (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Method called when the allocator is about to remove a <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a>.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Referenced by <a href="#ac35fef2aafb20ef4b079d0819394e87d">allocatePhysRegs</a>.</p>

</div>
</div>

### allocatePhysRegs() {#ac35fef2aafb20ef4b079d0819394e87d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocBase::allocatePhysRegs ()</td>
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



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-cpp">RegAllocBase.cpp</a>.</p>


<p>References <a href="#a0a064c82f883b28000d10199532b1c35">aboutToRemoveInterval</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8c9575386e3e74d0ebf3b80ec946feda">dequeue</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a66ff664a97cd3c30de7e873335a0c075">llvm::LiveRange::empty</a>, <a href="#a1d4798520a9880c2b801fd18ff8342d2">enqueue</a>, <a href="#a1558554539a5b133b8e361c0517e9fb1">getErrorAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="#a575345318339b28557a6c8ea57708434">LIS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a865e0247c5f922b8afaaaec481e4939c">Matrix</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#aba058f684e1b6704e5b4a09f889ec18c">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="#a10ad31d44cbe980bf48cbb166a924091">selectOrSplit</a>, <a href="#a523cbc58f79fe5e9e95dc87f9cee8a36">TRI</a> and <a href="#a96bb57a8041a40ded1ba0ef3b411a615">VRM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a94391e15de6cfad5cf6522641d8b7f95">anonymous{RegAllocBasic.cpp}::RABasic::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a9f1a58845384add66455538dc8725392">llvm::RAGreedy::runOnMachineFunction</a>.</p>

</div>
</div>

### dequeue() {#a8c9575386e3e74d0ebf3b80ec946feda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const LiveInterval * llvm::RegAllocBase::dequeue ()</td>
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

<p>dequeue - Return the next unassigned register, or NULL.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Referenced by <a href="#ac35fef2aafb20ef4b079d0819394e87d">allocatePhysRegs</a>.</p>

</div>
</div>

### enqueue() {#a1d4798520a9880c2b801fd18ff8342d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocBase::enqueue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * LI)</td>
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

<p>enqueue - Add VirtReg to the priority queue of unassigned registers.</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-cpp">RegAllocBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac41354781f406aa77d665f9e5aec8309">enqueueImpl</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="#aee328fb90c6cef95857090cdc67de0d4">shouldAllocateRegister</a>, <a href="#a523cbc58f79fe5e9e95dc87f9cee8a36">TRI</a> and <a href="#a96bb57a8041a40ded1ba0ef3b411a615">VRM</a>.</p>


<p>Referenced by <a href="#ac35fef2aafb20ef4b079d0819394e87d">allocatePhysRegs</a>.</p>

</div>
</div>

### enqueueImpl() {#ac41354781f406aa77d665f9e5aec8309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::RegAllocBase::enqueueImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * LI)</td>
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

<p>enqueue - Add VirtReg to the priority queue of unassigned registers.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Referenced by <a href="#a1d4798520a9880c2b801fd18ff8342d2">enqueue</a>.</p>

</div>
</div>

### getErrorAssignment() {#a1558554539a5b133b8e361c0517e9fb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCPhysReg RegAllocBase::getErrorAssignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CtxMI=nullptr)</td>
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

<p>Query a physical register to use as a filler in contexts where the allocation has failed.</p>


<p>This will raise an error, but not abort the compilation.</p>


<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-cpp">RegAllocBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad72245681f0ae02a2d4574d434bc813d">llvm::MachineInstr::emitInlineAsmError</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a84c7a981b331eae0f00669f3775ab3ca">llvm::MachineFunctionProperties::FailedRegAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abb10ef030fba4ea901518a0c8dbef3e2">llvm::MachineInstr::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac1f888bba00f32cb4f9a0010c958f397">llvm::MachineFunction::getProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a208148ec39e21c8c4591ad914e318dc9">llvm::TargetRegisterClass::getRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aacef05f16d3e71703f08bb4677e1d7a2">llvm::MachineFunctionProperties::hasProperty</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a4b743093219cfca13b1ec2cb58903fba">llvm::MachineInstr::isInlineAsm</a>, <a href="#aa6330bc662bf646d769c2a0771282eaf">RegClassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a> and <a href="#a96bb57a8041a40ded1ba0ef3b411a615">VRM</a>.</p>


<p>Referenced by <a href="#ac35fef2aafb20ef4b079d0819394e87d">allocatePhysRegs</a>.</p>

</div>
</div>

### init() {#a2e9547b9bc56b02aad18e54488c8059b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocBase::init (<a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp; vrm, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; lis, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix">LiveRegMatrix</a> &amp; mat)</td>
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



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-cpp">RegAllocBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a7619711af4bb95253dea3e0783400f26">llvm::VirtRegMap::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a5b03bffeedbff2a86dfe427fd90c1465">llvm::VirtRegMap::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#adb16c0664049f377c9ff542829013a75">llvm::VirtRegMap::getTargetRegInfo</a>, <a href="#a575345318339b28557a6c8ea57708434">LIS</a>, <a href="#a865e0247c5f922b8afaaaec481e4939c">Matrix</a>, <a href="#aba058f684e1b6704e5b4a09f889ec18c">MRI</a>, <a href="#aa6330bc662bf646d769c2a0771282eaf">RegClassInfo</a>, <a href="#a523cbc58f79fe5e9e95dc87f9cee8a36">TRI</a> and <a href="#a96bb57a8041a40ded1ba0ef3b411a615">VRM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a94391e15de6cfad5cf6522641d8b7f95">anonymous{RegAllocBasic.cpp}::RABasic::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a9f1a58845384add66455538dc8725392">llvm::RAGreedy::runOnMachineFunction</a>.</p>

</div>
</div>

### postOptimization() {#a93e2dd7d80790456c7201dc40d3b1263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocBase::postOptimization ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-cpp">RegAllocBase.cpp</a>.</p>


<p>References <a href="#a3a073386d697a3adacf27699bd95441d">DeadRemats</a>, <a href="#a575345318339b28557a6c8ea57708434">LIS</a>, <a href="/web-llvm/docs/api/classes/llvm/spiller/#ac5e77cbf6ad42d3a68d03f7d20f0a07d">llvm::Spiller::postOptimization</a> and <a href="#a49d5127f2ab5ad47f9b00a889948dd91">spiller</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a94391e15de6cfad5cf6522641d8b7f95">anonymous{RegAllocBasic.cpp}::RABasic::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a9f1a58845384add66455538dc8725392">llvm::RAGreedy::runOnMachineFunction</a>.</p>

</div>
</div>

### selectOrSplit() {#a10ad31d44cbe980bf48cbb166a924091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MCRegister llvm::RegAllocBase::selectOrSplit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; splitLVRs)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Referenced by <a href="#ac35fef2aafb20ef4b079d0819394e87d">allocatePhysRegs</a>.</p>

</div>
</div>

### shouldAllocateRegister() {#aee328fb90c6cef95857090cdc67de0d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegAllocBase::shouldAllocateRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Get whether a given register should be allocated.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>References <a href="#aba058f684e1b6704e5b4a09f889ec18c">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="#a523cbc58f79fe5e9e95dc87f9cee8a36">TRI</a>.</p>


<p>Referenced by <a href="#a1d4798520a9880c2b801fd18ff8342d2">enqueue</a>.</p>

</div>
</div>

### spiller() {#a49d5127f2ab5ad47f9b00a889948dd91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Spiller &amp; llvm::RegAllocBase::spiller ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Referenced by <a href="#a93e2dd7d80790456c7201dc40d3b1263">postOptimization</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a71dacb3fb537bf1648c1b1cb7ebded58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocBase::anchor ()</td>
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



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-cpp">RegAllocBase.cpp</a>.</p>

</div>
</div>

### seedLiveRegs() {#af47f48e36ce2f7d72e0f4536dc48f330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegAllocBase::seedLiveRegs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-cpp">RegAllocBase.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DeadRemats {#a3a073386d697a3adacf27699bd95441d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineInstr *, 32&gt; llvm::RegAllocBase::DeadRemats</td>
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

<p>Inst which is a def of an original reg and whose defs are already all dead after remat is saved in DeadRemats.</p>


<p>The deletion of such inst is postponed till all the allocations are done, so its remat expr is always available for the remat of all the siblings of the original reg.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Referenced by <a href="#a93e2dd7d80790456c7201dc40d3b1263">postOptimization</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a6f1fe32957cb698200b26a3a96e0145c">anonymous{RegAllocBasic.cpp}::RABasic::selectOrSplit</a> and <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#ab2d41fa069e7edcedf9949fa64aa6e30">anonymous{RegAllocBasic.cpp}::RABasic::spillInterferences</a>.</p>

</div>
</div>

### LIS {#a575345318339b28557a6c8ea57708434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals* llvm::RegAllocBase::LIS = nullptr</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Referenced by <a href="#ac35fef2aafb20ef4b079d0819394e87d">allocatePhysRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a6e5ac7360a3710d473f87101427218e4">llvm::RAGreedy::getLiveIntervals</a>, <a href="#a2e9547b9bc56b02aad18e54488c8059b">init</a>, <a href="#a93e2dd7d80790456c7201dc40d3b1263">postOptimization</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a94391e15de6cfad5cf6522641d8b7f95">anonymous{RegAllocBasic.cpp}::RABasic::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a9f1a58845384add66455538dc8725392">llvm::RAGreedy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a6f1fe32957cb698200b26a3a96e0145c">anonymous{RegAllocBasic.cpp}::RABasic::selectOrSplit</a> and <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#ab2d41fa069e7edcedf9949fa64aa6e30">anonymous{RegAllocBasic.cpp}::RABasic::spillInterferences</a>.</p>

</div>
</div>

### Matrix {#a865e0247c5f922b8afaaaec481e4939c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegMatrix* llvm::RegAllocBase::Matrix = nullptr</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Referenced by <a href="#ac35fef2aafb20ef4b079d0819394e87d">allocatePhysRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#ae72e53f0df37c3d160a12cf91dd1d5cf">llvm::RAGreedy::getInterferenceMatrix</a>, <a href="#a2e9547b9bc56b02aad18e54488c8059b">init</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a9f1a58845384add66455538dc8725392">llvm::RAGreedy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a6f1fe32957cb698200b26a3a96e0145c">anonymous{RegAllocBasic.cpp}::RABasic::selectOrSplit</a> and <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#ab2d41fa069e7edcedf9949fa64aa6e30">anonymous{RegAllocBasic.cpp}::RABasic::spillInterferences</a>.</p>

</div>
</div>

### MRI {#aba058f684e1b6704e5b4a09f889ec18c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* llvm::RegAllocBase::MRI = nullptr</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Referenced by <a href="#ac35fef2aafb20ef4b079d0819394e87d">allocatePhysRegs</a>, <a href="#a2e9547b9bc56b02aad18e54488c8059b">init</a> and <a href="#aee328fb90c6cef95857090cdc67de0d4">shouldAllocateRegister</a>.</p>

</div>
</div>

### RegClassInfo {#aa6330bc662bf646d769c2a0771282eaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterClassInfo llvm::RegAllocBase::RegClassInfo</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Referenced by <a href="#a1558554539a5b133b8e361c0517e9fb1">getErrorAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a7517d71d39eeb4a8857c9cc2dc8e3c1e">llvm::RAGreedy::getRegClassInfo</a>, <a href="#a2e9547b9bc56b02aad18e54488c8059b">init</a> and <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a6f1fe32957cb698200b26a3a96e0145c">anonymous{RegAllocBasic.cpp}::RABasic::selectOrSplit</a>.</p>

</div>
</div>

### TRI {#a523cbc58f79fe5e9e95dc87f9cee8a36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::RegAllocBase::TRI = nullptr</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Referenced by <a href="#ac35fef2aafb20ef4b079d0819394e87d">allocatePhysRegs</a>, <a href="#a1d4798520a9880c2b801fd18ff8342d2">enqueue</a>, <a href="#a2e9547b9bc56b02aad18e54488c8059b">init</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a9f1a58845384add66455538dc8725392">llvm::RAGreedy::runOnMachineFunction</a>, <a href="#aee328fb90c6cef95857090cdc67de0d4">shouldAllocateRegister</a> and <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#ab2d41fa069e7edcedf9949fa64aa6e30">anonymous{RegAllocBasic.cpp}::RABasic::spillInterferences</a>.</p>

</div>
</div>

### VRM {#a96bb57a8041a40ded1ba0ef3b411a615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VirtRegMap* llvm::RegAllocBase::VRM = nullptr</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Referenced by <a href="#ac35fef2aafb20ef4b079d0819394e87d">allocatePhysRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#a6e87024d7fe817808e0288f6b213d40c">assignedRegPartiallyOverlaps</a>, <a href="#a1d4798520a9880c2b801fd18ff8342d2">enqueue</a>, <a href="#a1558554539a5b133b8e361c0517e9fb1">getErrorAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a3b648cac4e5a698287916619782685c9">llvm::RAGreedy::getVirtRegMap</a>, <a href="#a2e9547b9bc56b02aad18e54488c8059b">init</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a94391e15de6cfad5cf6522641d8b7f95">anonymous{RegAllocBasic.cpp}::RABasic::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a9f1a58845384add66455538dc8725392">llvm::RAGreedy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a6f1fe32957cb698200b26a3a96e0145c">anonymous{RegAllocBasic.cpp}::RABasic::selectOrSplit</a> and <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#ab2d41fa069e7edcedf9949fa64aa6e30">anonymous{RegAllocBasic.cpp}::RABasic::spillInterferences</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### shouldAllocateRegisterImpl {#ade24838a8fad55b383378261c91a5b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegAllocFilterFunc llvm::RegAllocBase::shouldAllocateRegisterImpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Private, callees should go through shouldAllocateRegister.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### VerifyEnabled {#afbeaddcf447db994c372dfff591105ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegAllocBase::VerifyEnabled = false</td>
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

<p>VerifyEnabled - True when -verify-regalloc is given.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a9f1a58845384add66455538dc8725392">llvm::RAGreedy::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### TimerGroupDescription {#a75a298de4027780720785b5cd3479e92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char RegAllocBase::TimerGroupDescription = "Register Allocation"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>

</div>
</div>

### TimerGroupName {#a666d8b67c14d35f657e591cb87984592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char RegAllocBase::TimerGroupName = "regalloc"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-cpp">RegAllocBase.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
