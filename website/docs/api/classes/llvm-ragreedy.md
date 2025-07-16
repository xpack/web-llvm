---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ragreedy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RAGreedy` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RAGreedy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">CodeGen/RegAllocGreedy.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regallocbase">RegAllocBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/regallocbase">RegAllocBase</a> provides the register allocation driver and interface that can be extended to add interesting heuristics. <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverangeedit/delegate">Delegate</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback methods for <a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> owners. <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/delegate/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8dbcf5d6359e0e9f27a823bf5fd047a">PQueue</a> = std::priority_queue&lt; std::pair&lt; unsigned, unsigned &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5edf24867806e4c9dafc6b8007c7c9a2">SmallLISet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *, 4 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aea2fbe63efaa1184486c57ff75b623">RecoloringStack</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &gt;, 8 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59caef7c7bc4ea931fb4792109a38301">HintsInfo</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; HintInfo, 4 &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CutOffStage { <a href="#ab37e9ea7f61e5c72ba2225fd84022f6e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#ad121cffc4f53555fe6b5d39ead1715b5">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc503bf8aca22e0b405fbdf940ec76a2">RAGreedy</a> (const RegAllocFilterFunc F=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveregmatrix">LiveRegMatrix</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae72e53f0df37c3d160a12cf91dd1d5cf">getInterferenceMatrix</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e5ac7360a3710d473f87101427218e4">getLiveIntervals</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b648cac4e5a698287916619782685c9">getVirtRegMap</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7517d71d39eeb4a8857c9cc2dc8e3c1e">getRegClassInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ragreedy/extrareginfo">ExtraRegInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e3e56e8a3dd80cfd15f3e9e17bcd876">getExtraInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adef4d443e08bd60fd1c2c8d0a1108bc3">getQueueSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4ee3cdd6516d10ee3d98f6c913226f1">getRegClassPriorityTrumpsGlobalness</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac656ebfe8dfea4d0f7187fd6f0d74d94">getReverseLocalAssignment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d5ee2559fb200e43c77c18d8d2258bf">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the pass name. <a href="#a0d5ee2559fb200e43c77c18d8d2258bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec26bf822b32b653438f2c81d8a220a2">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/ragreedy">RAGreedy</a> analysis usage. <a href="#aec26bf822b32b653438f2c81d8a220a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4387b6ce7f4f52e3c99d4b275781d53b">releaseMemory</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a4387b6ce7f4f52e3c99d4b275781d53b">releaseMemory()</a> - This member can be implemented by a pass if it wants to be able to release its memory when it is no longer needed. <a href="#a4387b6ce7f4f52e3c99d4b275781d53b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spiller">Spiller</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3005c8a0b2f3c6b3d211c55bca1a471c">spiller</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1dc8fef31f8b6c87cee82d35b95f684">enqueueImpl</a> (const LiveInterval *LI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>enqueue - Add VirtReg to the priority queue of unassigned registers. <a href="#ac1dc8fef31f8b6c87cee82d35b95f684">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6e839ab9149b9e4bba152ca5408a19c">dequeue</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dequeue - Return the next unassigned register, or NULL. <a href="#aa6e839ab9149b9e4bba152ca5408a19c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61a893421c22ef66b14401945560e4af">selectOrSplit</a> (const LiveInterval &amp;, SmallVectorImpl&lt; Register &gt; &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4e3fe7472622039e7a9f5a54e584ec4">aboutToRemoveInterval</a> (const LiveInterval &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method called when the allocator is about to remove a <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a>. <a href="#af4e3fe7472622039e7a9f5a54e584ec4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f1a58845384add66455538dc8725392">runOnMachineFunction</a> (MachineFunction &amp;mf) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform register allocation. <a href="#a9f1a58845384add66455538dc8725392">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36c2bd8ddd9e9e08a4674b0ba60f864a">getRequiredProperties</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2157525b0c1a0284c11b859dc69a392c">getClearedProperties</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46350270c34baee08012f08b25f4acb7">selectOrSplitImpl</a> (const LiveInterval &amp;, SmallVectorImpl&lt; Register &gt; &amp;, SmallVirtRegSet &amp;, RecoloringStack &amp;, unsigned=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb0919124e1f597b7c837d8077fd31c4">LRE_CanEraseVirtReg</a> (Register) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called when a virtual register is no longer used. <a href="#acb0919124e1f597b7c837d8077fd31c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b2efa270c5ef47a6c37b42186f9f1b5">LRE_WillShrinkVirtReg</a> (Register) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called before shrinking the live range of a virtual register. <a href="#a4b2efa270c5ef47a6c37b42186f9f1b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae910b39c2fdc1139f33341639d619f81">LRE_DidCloneVirtReg</a> (Register, Register) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called after cloning a virtual register. <a href="#ae910b39c2fdc1139f33341639d619f81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c0afaa0cb6991c0d2092609dc2581d">enqueue</a> (PQueue &amp;CurQueue, const LiveInterval *LI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a076b6222c5973ecec3d73d8580462e4d">dequeue</a> (PQueue &amp;CurQueue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7119b869fbf80fc94bbe97614d1252d1">hasVirtRegAlloc</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45acffa18196bf2fb6c821ce1eadb379">calcSpillCost</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>calcSpillCost - Compute how expensive it would be to split the live range in SA around all use blocks instead of forming bundle regions. <a href="#a45acffa18196bf2fb6c821ce1eadb379">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8b334d2e11e79c1ad39c1dfa7a84df0">addSplitConstraints</a> (InterferenceCache::Cursor, BlockFrequency &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addSplitConstraints - Fill out the SplitConstraints vector based on the interference pattern in Physreg and its aliases. <a href="#ad8b334d2e11e79c1ad39c1dfa7a84df0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aef19f5c6da907a9da4e4dbdb6df766">addThroughConstraints</a> (InterferenceCache::Cursor, ArrayRef&lt; unsigned &gt;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addThroughConstraints - Add constraints and links to SpillPlacer from the live-through blocks in Blocks. <a href="#a5aef19f5c6da907a9da4e4dbdb6df766">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a760b52ca48e876a9f4ebb87416591e38">growRegion</a> (GlobalSplitCandidate &amp;Cand)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135c9202c14864cd52d50ef762300697">calcGlobalSplitCost</a> (GlobalSplitCandidate &amp;, const AllocationOrder &amp;Order)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>calcGlobalSplitCost - Return the global split cost of following the split pattern in LiveBundles. <a href="#a135c9202c14864cd52d50ef762300697">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeea48e8daa92940d018aba7b07eb065d">calcCompactRegion</a> (GlobalSplitCandidate &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>calcCompactRegion - Compute the set of edge bundles that should be live when splitting the current live range into compact regions. <a href="#aeea48e8daa92940d018aba7b07eb065d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad791707dd477419b199afa98cf52abd9">splitAroundRegion</a> (LiveRangeEdit &amp;, ArrayRef&lt; unsigned &gt;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>splitAroundRegion - Split the current live range around the regions determined by BundleCand and GlobalCand. <a href="#ad791707dd477419b199afa98cf52abd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa711c5a8177d7207e844f4581530584b">calcGapWeights</a> (MCRegister, SmallVectorImpl&lt; float &gt; &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>calcGapWeights - Compute the maximum spill weight that needs to be evicted in order to use PhysReg between two entries in SA-&gt;UseSlots. <a href="#aa711c5a8177d7207e844f4581530584b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e2380c6d062712ee9c402aca6c9b40">evictInterference</a> (const LiveInterval &amp;, MCRegister, SmallVectorImpl&lt; Register &gt; &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>evictInterference - Evict any interferring registers that prevent VirtReg from being assigned to Physreg. <a href="#a49e2380c6d062712ee9c402aca6c9b40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66438378187bbedf30bb2b93cc111460">mayRecolorAllInterferences</a> (MCRegister PhysReg, const LiveInterval &amp;VirtReg, SmallLISet &amp;RecoloringCandidates, const SmallVirtRegSet &amp;FixedRegisters)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>mayRecolorAllInterferences - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the virtual registers that interfere with <span class="doxyComputerOutput">VirtReg</span> on <span class="doxyComputerOutput">PhysReg</span> (or one of its aliases) may be recolored to free <span class="doxyComputerOutput">PhysReg</span>. <a href="#a66438378187bbedf30bb2b93cc111460">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a714dd63e220808b28aca2019ea73562f">tryAssign</a> (const LiveInterval &amp;, AllocationOrder &amp;, SmallVectorImpl&lt; Register &gt; &amp;, const SmallVirtRegSet &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryAssign - Try to assign VirtReg to an available register. <a href="#a714dd63e220808b28aca2019ea73562f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a653446dc2291fedee0087911081fed">tryEvict</a> (const LiveInterval &amp;, AllocationOrder &amp;, SmallVectorImpl&lt; Register &gt; &amp;, uint8_t, const SmallVirtRegSet &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryEvict - Try to evict all interferences for a physreg. <a href="#a5a653446dc2291fedee0087911081fed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fb6dfa434046cc7ee2aeedc09b3ce39">tryRegionSplit</a> (const LiveInterval &amp;, AllocationOrder &amp;, SmallVectorImpl&lt; Register &gt; &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba233a7c188cf92cfe7dd4177cb30b6c">calculateRegionSplitCostAroundReg</a> (MCPhysReg PhysReg, AllocationOrder &amp;Order, BlockFrequency &amp;BestCost, unsigned &amp;NumCands, unsigned &amp;BestCand)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate cost of region splitting around the specified register. <a href="#aba233a7c188cf92cfe7dd4177cb30b6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00a78aefd8c9f82eea0e60d53ee18283">calculateRegionSplitCost</a> (const LiveInterval &amp;VirtReg, AllocationOrder &amp;Order, BlockFrequency &amp;BestCost, unsigned &amp;NumCands, bool IgnoreCSR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate cost of region splitting. <a href="#a00a78aefd8c9f82eea0e60d53ee18283">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1140bd905229a68ec7b6b73675360b9b">doRegionSplit</a> (const LiveInterval &amp;VirtReg, unsigned BestCand, bool HasCompact, SmallVectorImpl&lt; Register &gt; &amp;NewVRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform region splitting. <a href="#a1140bd905229a68ec7b6b73675360b9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2600051701cc651e7322e73fd6ec7167">trySplitAroundHintReg</a> (MCPhysReg Hint, const LiveInterval &amp;VirtReg, SmallVectorImpl&lt; Register &gt; &amp;NewVRegs, AllocationOrder &amp;Order)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to split VirtReg around physical Hint register. <a href="#a2600051701cc651e7322e73fd6ec7167">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11c1981342329f4cebd1e5b176492593">tryAssignCSRFirstTime</a> (const LiveInterval &amp;VirtReg, AllocationOrder &amp;Order, MCRegister PhysReg, uint8_t &amp;CostPerUseLimit, SmallVectorImpl&lt; Register &gt; &amp;NewVRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> other options before using a callee-saved register for the first time. <a href="#a11c1981342329f4cebd1e5b176492593">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fec8bb02793224900ae1b4accefd1fd">initializeCSRCost</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ddc34ed7c3fc84fef0d325a46f54fa">tryBlockSplit</a> (const LiveInterval &amp;, AllocationOrder &amp;, SmallVectorImpl&lt; Register &gt; &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryBlockSplit - Split a global live range around every block with uses. <a href="#af3ddc34ed7c3fc84fef0d325a46f54fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af75df116dc724d9f86f6ed6ff3bf8c75">tryInstructionSplit</a> (const LiveInterval &amp;, AllocationOrder &amp;, SmallVectorImpl&lt; Register &gt; &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryInstructionSplit - Split a live range around individual instructions. <a href="#af75df116dc724d9f86f6ed6ff3bf8c75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd218bb57b6eed4cda062356adae6a43">tryLocalSplit</a> (const LiveInterval &amp;, AllocationOrder &amp;, SmallVectorImpl&lt; Register &gt; &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryLocalSplit - Try to split VirtReg into smaller intervals inside its only basic block. <a href="#abd218bb57b6eed4cda062356adae6a43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5181f9f12665ed6716a747a4fdbffec2">trySplit</a> (const LiveInterval &amp;, AllocationOrder &amp;, SmallVectorImpl&lt; Register &gt; &amp;, const SmallVirtRegSet &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>trySplit - Try to split VirtReg or one of its interferences, making it assignable. <a href="#a5181f9f12665ed6716a747a4fdbffec2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07c95105ea98d3e391e7036e52287c21">tryLastChanceRecoloring</a> (const LiveInterval &amp;, AllocationOrder &amp;, SmallVectorImpl&lt; Register &gt; &amp;, SmallVirtRegSet &amp;, RecoloringStack &amp;, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryLastChanceRecoloring - Try to assign a color to <span class="doxyComputerOutput">VirtReg</span> by recoloring its interferences. <a href="#a07c95105ea98d3e391e7036e52287c21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab56889769f60c67206e74e54ad7bbd12">tryRecoloringCandidates</a> (PQueue &amp;, SmallVectorImpl&lt; Register &gt; &amp;, SmallVirtRegSet &amp;, RecoloringStack &amp;, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryRecoloringCandidates - Try to assign a new color to every register in \RecoloringQueue. <a href="#ab56889769f60c67206e74e54ad7bbd12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2b29bc44380b16eb80abab428560328">tryHintRecoloring</a> (const LiveInterval &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Using the register assigned to <span class="doxyComputerOutput">VirtReg</span>, try to recolor all the live ranges that are copy-related with <span class="doxyComputerOutput">VirtReg</span>. <a href="#ae2b29bc44380b16eb80abab428560328">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a5839284d805cb0a2f287c334ce04d3">tryHintsRecoloring</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to recolor broken hints. <a href="#a1a5839284d805cb0a2f287c334ce04d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3018507266bfedb4805c1415e62b1f07">getBrokenHintFreq</a> (const HintsInfo &amp;, MCRegister)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Using the given <span class="doxyComputerOutput">List</span>, compute the cost of the broken hints if <span class="doxyComputerOutput">PhysReg</span> was used. <a href="#a3018507266bfedb4805c1415e62b1f07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a235458b38b0ca540cea8f49b26f4eb40">collectHintInfo</a> (Register, HintsInfo &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect the hint info for <span class="doxyComputerOutput">Reg</span>. <a href="#a235458b38b0ca540cea8f49b26f4eb40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">RAGreedyStats</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a6dead05115c7b69f4881405fb00db">computeStats</a> (MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute statistic for a basic block. <a href="#a89a6dead05115c7b69f4881405fb00db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">RAGreedyStats</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f1ec95f99f392f2a1a76610d7ba3e1d">reportStats</a> (MachineLoop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute and report statistic through a remark. <a href="#a0f1ec95f99f392f2a1a76610d7ba3e1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a4b9d6fad5dc578afa9957a13280c7">reportStats</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report the statistic for each loop. <a href="#a73a4b9d6fad5dc578afa9957a13280c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae740923c145d21fee28f5fd833c88316">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a853123c7c53cbc65566b1c4af0dcf19b">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc7d9931c89ee721fe4205f4d1b75ec">Indexes</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0b6b0ddab681d0fb4ca736f23f8769a">MBFI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b0051f55729437208758c9b9168c29d">DomTree</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a4f829070f028240bf15ffc22edce7">Loops</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitter">MachineOptimizationRemarkEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4146be245e8fb552bcfb168808f7884">ORE</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/edgebundles">EdgeBundles</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa970f0cb50b0c60d47bb1a1288712ba7">Bundles</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spillplacement">SpillPlacement</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca3322707cfb26dd9c57234bb0111d92">SpillPlacer</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/livedebugvariables">LiveDebugVariables</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae32e2c0f184ead36f1c132a975ec76cc">DebugVars</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/spiller">Spiller</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aa9d39514774ae077f35e02ad1a1030">SpillerInstance</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PQueue</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6538b17ea400426cfdcd477960fef7ae">Queue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo">VirtRegAuxInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bb4eea876b59167bdafbe5206a8c991">VRAI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/ragreedy/extrareginfo">ExtraRegInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a040160998a56a7aca1d9f768dc91414c">ExtraInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor">RegAllocEvictionAdvisor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa614f9d2b23051bfc1dbb2c029175226">EvictAdvisor</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisor">RegAllocPriorityAdvisor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58c6d2e74ecdbaa31c939d4340a9f454">PriorityAdvisor</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a6439c5942f97229fd5091ab7a2f46a">CutOffInfo</a> = CutOffStage::CO_None</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/splitanalysis">SplitAnalysis</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a223c21c6c93360b5f4461b3e0af2a85e">SA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/spliteditor">SplitEditor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78a46a02148fc3b6c31cd1bacfc7546">SE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/interferencecache">InterferenceCache</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae24326d9c0488808f067ae003df2720">IntfCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cached per-block interference maps. <a href="#aae24326d9c0488808f067ae003df2720">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/spillplacement/blockconstraint">SpillPlacement::BlockConstraint</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a644f631cb3b2d9510c397d2b76d8fbe3">SplitConstraints</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All basic blocks where the current register has uses. <a href="#a644f631cb3b2d9510c397d2b76d8fbe3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; GlobalSplitCandidate, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa53cf7488bedd62988bc02084a0e74bc">GlobalCand</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Candidate info for each PhysReg in <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a>. <a href="#aa53cf7488bedd62988bc02084a0e74bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a128b75c0d40c89e5b87f91a843292de6">BundleCand</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Candidate map. <a href="#a128b75c0d40c89e5b87f91a843292de6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88a37ccee06633c4e89967dce1a8568e">CSRCost</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callee-save register cost, calculated once per machine function. <a href="#a88a37ccee06633c4e89967dce1a8568e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ea97d5085ea163b14da0a15f24d4047">SetOfBrokenHints</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of broken hints that may be reconciled later because of eviction. <a href="#a6ea97d5085ea163b14da0a15f24d4047">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e4dff8edfc06ff34a53ef6f679d1662">RegCosts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The register cost values. <a href="#a1e4dff8edfc06ff34a53ef6f679d1662">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f25350939d2d89183b4e96e3f5a12a">RegClassPriorityTrumpsGlobalness</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flags for the live range priority calculation, determined once per machine function. <a href="#a21f25350939d2d89183b4e96e3f5a12a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b81de0420a7e67a9642f51ed19bc653">ReverseLocalAssignment</a> = false</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1010755cb4b7307ca310cc6d86167f">ID</a> = 0</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72b20e4a4d7fbe89fc10903cab1fca26">StageName</a>[] = ...</td>
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


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### HintsInfo {#a59caef7c7bc4ea931fb4792109a38301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RAGreedy::HintsInfo =  SmallVector&lt;HintInfo, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### PQueue {#ad8dbcf5d6359e0e9f27a823bf5fd047a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RAGreedy::PQueue =  std::priority_queue&lt;std::pair&lt;unsigned, unsigned&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### RecoloringStack {#a1aea2fbe63efaa1184486c57ff75b623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RAGreedy::RecoloringStack = 
      SmallVector&lt;std::pair&lt;const LiveInterval *, MCRegister&gt;, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### SmallLISet {#a5edf24867806e4c9dafc6b8007c7c9a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RAGreedy::SmallLISet =  SmallSetVector&lt;const LiveInterval *, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#ad121cffc4f53555fe6b5d39ead1715b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoCand<a id="ad121cffc4f53555fe6b5d39ead1715b5ad365d97157db5ea993843ee86ebadcf8"></a></td>
<td class="doxyEnumItemDescription"> (= ~0u)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### CutOffStage {#ab37e9ea7f61e5c72ba2225fd84022f6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RAGreedy::CutOffStage </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CO_None<a id="ab37e9ea7f61e5c72ba2225fd84022f6ea118ae3e1f25389541778603d22c6e306"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CO_Depth<a id="ab37e9ea7f61e5c72ba2225fd84022f6ea92f4b5fef031b775a01defa4fc6e7a37"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CO_Interf<a id="ab37e9ea7f61e5c72ba2225fd84022f6ea1e12fb4a83b813d859c0d2994d65b7a2"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RAGreedy() {#abc503bf8aca22e0b405fbdf940ec76a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RAGreedy::RAGreedy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a0ab9dba764b528b15e89f9c443b2e202">RegAllocFilterFunc</a> F=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#acc1010755cb4b7307ca310cc6d86167f">ID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a> and <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a012fb04b333e4c8875594766fd9f076a">llvm::RegAllocBase::RegAllocBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### aboutToRemoveInterval() {#af4e3fe7472622039e7a9f5a54e584ec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::aboutToRemoveInterval (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI)</td>
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

<p>Method called when the allocator is about to remove a <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a>.</p>

<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2222 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### dequeue() {#aa6e839ab9149b9e4bba152ca5408a19c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveInterval * RAGreedy::dequeue ()</td>
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

<p>dequeue - Return the next unassigned register, or NULL.</p>

<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>


<p>Reference <a href="#aa6e839ab9149b9e4bba152ca5408a19c">dequeue</a>.</p>


<p>Referenced by <a href="#aa6e839ab9149b9e4bba152ca5408a19c">dequeue</a>.</p>

</div>
</div>

### enqueueImpl() {#ac1dc8fef31f8b6c87cee82d35b95f684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::enqueueImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * LI)</td>
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

<p>enqueue - Add VirtReg to the priority queue of unassigned registers.</p>

<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### getAnalysisUsage() {#aec26bf822b32b653438f2c81d8a220a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/ragreedy">RAGreedy</a> analysis usage.</p>

<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae9356b720f6fbab112d809738dcc4f2a">llvm::AnalysisUsage::addPreserved</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af11a6ebf7ab3c388234cb6d5378439a3">llvm::AnalysisUsage::setPreservesCFG</a>.</p>

</div>
</div>

### getClearedProperties() {#a2157525b0c1a0284c11b859dc69a392c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties llvm::RAGreedy::getClearedProperties ()</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a4fc3b812627e58da17a703f73013db96">llvm::MachineFunctionProperties::IsSSA</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### getExtraInfo() {#a2e3e56e8a3dd80cfd15f3e9e17bcd876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ExtraRegInfo &amp; llvm::RAGreedy::getExtraInfo ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### getInterferenceMatrix() {#ae72e53f0df37c3d160a12cf91dd1d5cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegMatrix * llvm::RAGreedy::getInterferenceMatrix ()</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a865e0247c5f922b8afaaaec481e4939c">llvm::RegAllocBase::Matrix</a>.</p>

</div>
</div>

### getLiveIntervals() {#a6e5ac7360a3710d473f87101427218e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals * llvm::RAGreedy::getLiveIntervals ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a575345318339b28557a6c8ea57708434">llvm::RegAllocBase::LIS</a>.</p>

</div>
</div>

### getPassName() {#a0d5ee2559fb200e43c77c18d8d2258bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::RAGreedy::getPassName ()</td>
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

<p>Return the pass name.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### getQueueSize() {#adef4d443e08bd60fd1c2c8d0a1108bc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::RAGreedy::getQueueSize ()</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### getRegClassInfo() {#a7517d71d39eeb4a8857c9cc2dc8e3c1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterClassInfo &amp; llvm::RAGreedy::getRegClassInfo ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#aa6330bc662bf646d769c2a0771282eaf">llvm::RegAllocBase::RegClassInfo</a>.</p>

</div>
</div>

### getRegClassPriorityTrumpsGlobalness() {#af4ee3cdd6516d10ee3d98f6c913226f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RAGreedy::getRegClassPriorityTrumpsGlobalness ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### getRequiredProperties() {#a36c2bd8ddd9e9e08a4674b0ba60f864a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties llvm::RAGreedy::getRequiredProperties ()</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a76eece0bfd57256980609b66faaef22c">llvm::MachineFunctionProperties::NoPHIs</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### getReverseLocalAssignment() {#ac656ebfe8dfea4d0f7187fd6f0d74d94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RAGreedy::getReverseLocalAssignment ()</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### getVirtRegMap() {#a3b648cac4e5a698287916619782685c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VirtRegMap * llvm::RAGreedy::getVirtRegMap ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a96bb57a8041a40ded1ba0ef3b411a615">llvm::RegAllocBase::VRM</a>.</p>

</div>
</div>

### releaseMemory() {#a4387b6ce7f4f52e3c99d4b275781d53b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::releaseMemory ()</td>
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

<p><a href="#a4387b6ce7f4f52e3c99d4b275781d53b">releaseMemory()</a> - This member can be implemented by a pass if it wants to be able to release its memory when it is no longer needed.</p>


<p>The default behavior of passes is to hold onto memory for the entire duration of their lifetime (which is the entire compile time). For pipelined passes, this is not a big deal because that memory gets recycled every time the pass is invoked on another program unit. For IP passes, it is more important to free memory when it is unused.</p>


<p>Optionally implement this function to release pass memory when it is no longer used.</p>


<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>


<p>Referenced by <a href="#a9f1a58845384add66455538dc8725392">runOnMachineFunction</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a9f1a58845384add66455538dc8725392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RAGreedy::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf)</td>
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

<p>Perform register allocation.</p>

<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2723 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#ac35fef2aafb20ef4b079d0819394e87d">llvm::RegAllocBase::allocatePhysRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a81d47204d9157a6d8709e7aa6c278bac">llvm::createInlineSpiller</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#a09c424ac0729676684e1b5bab309bcbb">GreedyRegClassPriorityTrumpsGlobalness</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#aeefb7f5f30792f795fed211decddbf4e">GreedyReverseLocalAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a2e9547b9bc56b02aad18e54488c8059b">llvm::RegAllocBase::init</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a575345318339b28557a6c8ea57708434">llvm::RegAllocBase::LIS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a865e0247c5f922b8afaaaec481e4939c">llvm::RegAllocBase::Matrix</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a93e2dd7d80790456c7201dc40d3b1263">llvm::RegAllocBase::postOptimization</a>, <a href="#a4387b6ce7f4f52e3c99d4b275781d53b">releaseMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a523cbc58f79fe5e9e95dc87f9cee8a36">llvm::RegAllocBase::TRI</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#afbeaddcf447db994c372dfff591105ac">llvm::RegAllocBase::VerifyEnabled</a> and <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a96bb57a8041a40ded1ba0ef3b411a615">llvm::RegAllocBase::VRM</a>.</p>

</div>
</div>

### selectOrSplit() {#a61a893421c22ef66b14401945560e4af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister RAGreedy::selectOrSplit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs)</td>
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



<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### spiller() {#a3005c8a0b2f3c6b3d211c55bca1a471c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Spiller &amp; llvm::RAGreedy::spiller ()</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addSplitConstraints() {#ad8b334d2e11e79c1ad39c1dfa7a84df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RAGreedy::addSplitConstraints (<a href="/web-llvm/docs/api/classes/llvm/interferencecache/cursor">InterferenceCache::Cursor</a> Intf, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> &amp; Cost)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addSplitConstraints - Fill out the SplitConstraints vector based on the interference pattern in Physreg and its aliases.</p>


<p>Add the constraints to <a href="/web-llvm/docs/api/classes/llvm/spillplacement">SpillPlacement</a> and return the static cost of this split in <a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a>, assuming that all preferences in SplitConstraints are met. Return false if there are no bundles with positive bias.</p>


<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### addThroughConstraints() {#a5aef19f5c6da907a9da4e4dbdb6df766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RAGreedy::addThroughConstraints (<a href="/web-llvm/docs/api/classes/llvm/interferencecache/cursor">InterferenceCache::Cursor</a> Intf, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Blocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addThroughConstraints - Add constraints and links to SpillPlacer from the live-through blocks in Blocks.</p>

<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### calcCompactRegion() {#aeea48e8daa92940d018aba7b07eb065d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RAGreedy::calcCompactRegion (GlobalSplitCandidate &amp; Cand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>calcCompactRegion - Compute the set of edge bundles that should be live when splitting the current live range into compact regions.</p>


<p>Compact regions can be computed without looking at interference. They are the regions formed by removing all the live-through blocks from the live range.</p>


<p>Returns false if the current live range is already compact, or if the compact regions would form single block regions anyway.</p>


<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### calcGapWeights() {#aa711c5a8177d7207e844f4581530584b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::calcGapWeights (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; float &gt; &amp; GapWeight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>calcGapWeights - Compute the maximum spill weight that needs to be evicted in order to use PhysReg between two entries in SA-&gt;UseSlots.</p>


<p>GapWeight[I] represents the gap between UseSlots[I] and UseSlots[I + 1].</p>


<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 1492 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### calcGlobalSplitCost() {#a135c9202c14864cd52d50ef762300697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency RAGreedy::calcGlobalSplitCost (GlobalSplitCandidate &amp; Cand, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>calcGlobalSplitCost - Return the global split cost of following the split pattern in LiveBundles.</p>


<p>This cost should be added to the local cost of the interference pattern in SplitConstraints.</p>


<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 871 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### calcSpillCost() {#a45acffa18196bf2fb6c821ce1eadb379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency RAGreedy::calcSpillCost ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>calcSpillCost - Compute how expensive it would be to split the live range in SA around all use blocks instead of forming bundle regions.</p>

<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### calculateRegionSplitCost() {#a00a78aefd8c9f82eea0e60d53ee18283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RAGreedy::calculateRegionSplitCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> &amp; BestCost, unsigned &amp; NumCands, bool IgnoreCSR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate cost of region splitting.</p>

<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 1174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### calculateRegionSplitCostAroundReg() {#aba233a7c188cf92cfe7dd4177cb30b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RAGreedy::calculateRegionSplitCostAroundReg (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> PhysReg, <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> &amp; BestCost, unsigned &amp; NumCands, unsigned &amp; BestCand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate cost of region splitting around the specified register.</p>

<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 1097 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### collectHintInfo() {#a235458b38b0ca540cea8f49b26f4eb40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::collectHintInfo (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smallvector">HintsInfo</a> &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect the hint info for <span class="doxyComputerOutput">Reg</span>.</p>


<p>The results are stored into <span class="doxyComputerOutput">Out</span>. <span class="doxyComputerOutput">Out</span> is not cleared before being populated.</p>


<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2256 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### computeStats() {#a89a6dead05115c7b69f4881405fb00db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RAGreedy::RAGreedyStats RAGreedy::computeStats (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute statistic for a basic block.</p>

<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2564 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### dequeue() {#a076b6222c5973ecec3d73d8580462e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveInterval * RAGreedy::dequeue (PQueue &amp; CurQueue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### doRegionSplit() {#a1140bd905229a68ec7b6b73675360b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RAGreedy::doRegionSplit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, unsigned BestCand, bool HasCompact, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform region splitting.</p>

<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 1192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### enqueue() {#a94c0afaa0cb6991c0d2092609dc2581d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::enqueue (PQueue &amp; CurQueue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### evictInterference() {#a49e2380c6d062712ee9c402aca6c9b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::evictInterference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>evictInterference - Evict any interferring registers that prevent VirtReg from being assigned to Physreg.</p>


<p>This assumes that canEvictInterference returned true.</p>


<p>Declaration at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### getBrokenHintFreq() {#a3018507266bfedb4805c1415e62b1f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency RAGreedy::getBrokenHintFreq (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">HintsInfo</a> &amp; List, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Using the given <span class="doxyComputerOutput">List</span>, compute the cost of the broken hints if <span class="doxyComputerOutput">PhysReg</span> was used.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cost of <span class="doxyComputerOutput">List</span> for <span class="doxyComputerOutput">PhysReg</span>.</p></dd>
</dl>


<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2279 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### growRegion() {#a760b52ca48e876a9f4ebb87416591e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RAGreedy::growRegion (GlobalSplitCandidate &amp; Cand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### hasVirtRegAlloc() {#a7119b869fbf80fc94bbe97614d1252d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RAGreedy::hasVirtRegAlloc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2708 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### initializeCSRCost() {#a6fec8bb02793224900ae1b4accefd1fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::initializeCSRCost ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2227 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### LRE\_CanEraseVirtReg() {#acb0919124e1f597b7c837d8077fd31c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RAGreedy::LRE_CanEraseVirtReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a>)</td>
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

<p>Called when a virtual register is no longer used.</p>


<p>Return false to defer its deletion from <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a>.</p>


<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### LRE\_DidCloneVirtReg() {#ae910b39c2fdc1139f33341639d619f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::LRE_DidCloneVirtReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> New, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Old)</td>
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

<p>Called after cloning a virtual register.</p>


<p>This is used for new registers representing connected components of Old.</p>


<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### LRE\_WillShrinkVirtReg() {#a4b2efa270c5ef47a6c37b42186f9f1b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::LRE_WillShrinkVirtReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a>)</td>
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

<p>Called before shrinking the live range of a virtual register.</p>

<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### mayRecolorAllInterferences() {#a66438378187bbedf30bb2b93cc111460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RAGreedy::mayRecolorAllInterferences (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallLISet</a> &amp; RecoloringCandidates, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a1d6cfdcc234093f39fb0719ddb649500">SmallVirtRegSet</a> &amp; FixedRegisters)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>mayRecolorAllInterferences - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the virtual registers that interfere with <span class="doxyComputerOutput">VirtReg</span> on <span class="doxyComputerOutput">PhysReg</span> (or one of its aliases) may be recolored to free <span class="doxyComputerOutput">PhysReg</span>.</p>


<p>When true is returned, <span class="doxyComputerOutput">RecoloringCandidates</span> has been augmented with all the live intervals that need to be recolored in order to free <span class="doxyComputerOutput">PhysReg</span> for <span class="doxyComputerOutput">VirtReg</span>. <span class="doxyComputerOutput">FixedRegisters</span> contains all the virtual registers that cannot be recolored.</p>


<p>Declaration at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 1870 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### reportStats() {#a0f1ec95f99f392f2a1a76610d7ba3e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RAGreedy::RAGreedyStats RAGreedy::reportStats (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute and report statistic through a remark.</p>

<p>Declaration at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2656 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### reportStats() {#a73a4b9d6fad5dc578afa9957a13280c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::reportStats ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Report the statistic for each loop.</p>

<p>Declaration at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2682 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### selectOrSplitImpl() {#a46350270c34baee08012f08b25f4acb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister RAGreedy::selectOrSplitImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs, <a href="/web-llvm/docs/api/namespaces/llvm/#a1d6cfdcc234093f39fb0719ddb649500">SmallVirtRegSet</a> &amp; FixedRegisters, <a href="/web-llvm/docs/api/classes/llvm/smallvector">RecoloringStack</a> &amp; RecolorStack, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2422 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### splitAroundRegion() {#ad791707dd477419b199afa98cf52abd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::splitAroundRegion (<a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> &amp; LREdit, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; UsedCands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>splitAroundRegion - Split the current live range around the regions determined by BundleCand and GlobalCand.</p>


<p>Before calling this function, GlobalCand and BundleCand must be initialized so each bundle is assigned to a valid candidate, or NoCand for the stack-bound bundles. The shared SA/SE <a href="/web-llvm/docs/api/classes/llvm/splitanalysis">SplitAnalysis</a> and <a href="/web-llvm/docs/api/classes/llvm/spliteditor">SplitEditor</a> objects must be initialized for the current live range, and intervals created for the used candidates.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LREdit</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> object handling the current split.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UsedCands</td>
<td class="doxyParamItemDescription"><p>List of used GlobalCand entries. Every BundleCand value must appear in this list.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 925 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### tryAssign() {#a714dd63e220808b28aca2019ea73562f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister RAGreedy::tryAssign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a1d6cfdcc234093f39fb0719ddb649500">SmallVirtRegSet</a> &amp; FixedRegisters)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>tryAssign - Try to assign VirtReg to an available register.</p>

<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### tryAssignCSRFirstTime() {#a11c1981342329f4cebd1e5b176492593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister RAGreedy::tryAssignCSRFirstTime (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, uint8_t &amp; CostPerUseLimit, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> other options before using a callee-saved register for the first time.</p>


<p>Using a CSR for the first time has a cost because it causes push|pop to be added to prologue|epilogue.</p>


<p>Splitting a cold section of the live range can have lower cost than using the CSR for the first time; Spilling a live range in the cold path can have lower cost than using the CSR for the first time. Returns the physical register if we decide to use the CSR; otherwise return 0.</p>


<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### tryBlockSplit() {#af3ddc34ed7c3fc84fef0d325a46f54fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RAGreedy::tryBlockSplit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>tryBlockSplit - Split a global live range around every block with uses.</p>


<p>This creates a lot of local live ranges, that will be split by tryLocalSplit if they don't allocate.</p>


<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 1296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### tryEvict() {#a5a653446dc2291fedee0087911081fed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister RAGreedy::tryEvict (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs, uint8_t CostPerUseLimit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a1d6cfdcc234093f39fb0719ddb649500">SmallVirtRegSet</a> &amp; FixedRegisters)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>tryEvict - Try to evict all interferences for a physreg.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">VirtReg</td>
<td class="doxyParamItemDescription"><p>Currently unassigned virtual register.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Order</td>
<td class="doxyParamItemDescription"><p>Physregs to try.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Physreg to assign VirtReg, or 0.</p></dd>
</dl>


<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### tryHintRecoloring() {#ae2b29bc44380b16eb80abab428560328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::tryHintRecoloring (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Using the register assigned to <span class="doxyComputerOutput">VirtReg</span>, try to recolor all the live ranges that are copy-related with <span class="doxyComputerOutput">VirtReg</span>.</p>


<p>The recoloring is then propagated to all the live-ranges that have been recolored and so on, until no more copies can be coalesced or it is not profitable. For a given live range, profitability is determined by the sum of the frequencies of the non-identity copies it would introduce with the old and new register.</p>


<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2297 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### tryHintsRecoloring() {#a1a5839284d805cb0a2f287c334ce04d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RAGreedy::tryHintsRecoloring ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to recolor broken hints.</p>


<p>Broken hints may be repaired by recoloring when an evicted variable freed up a register for a larger live-range. Consider the following example: BB1: a = b = BB2: ... = b = a Let us assume b gets split: BB1: a = b = BB2: c = b ... d = c = d = a Because of how the allocation work, b, c, and d may be assigned different colors. Now, if a gets evicted later: BB1: a = st a, SpillSlot b = BB2: c = b ... d = c = d e = ld SpillSlot = e This is likely that we can assign the same register for b, c, and d, getting rid of 2 copies.</p>


<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2410 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### tryInstructionSplit() {#af75df116dc724d9f86f6ed6ff3bf8c75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RAGreedy::tryInstructionSplit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>tryInstructionSplit - Split a live range around individual instructions.</p>


<p>This is normally not worthwhile since the spiller is doing essentially the same thing. However, when the live range is in a constrained register class, it may help to insert copies such that parts of the live range can be moved to a larger register class.</p>


<p>This is similar to spilling to a larger register class.</p>


<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 1417 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### tryLastChanceRecoloring() {#a07c95105ea98d3e391e7036e52287c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RAGreedy::tryLastChanceRecoloring (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs, <a href="/web-llvm/docs/api/namespaces/llvm/#a1d6cfdcc234093f39fb0719ddb649500">SmallVirtRegSet</a> &amp; FixedRegisters, <a href="/web-llvm/docs/api/classes/llvm/smallvector">RecoloringStack</a> &amp; RecolorStack, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>tryLastChanceRecoloring - Try to assign a color to <span class="doxyComputerOutput">VirtReg</span> by recoloring its interferences.</p>


<p>Last chance recoloring chooses a color for <span class="doxyComputerOutput">VirtReg</span> and recolors every virtual register that was using it. The recoloring process may recursively use the last chance recoloring. Therefore, when a virtual register has been assigned a color by this mechanism, it is marked as Fixed, i.e., it cannot be last-chance-recolored again during this recoloring "session". E.g., Let vA can use {R1, R2 } vB can use { R2, R3} vC can use {R1 } Where vA, vB, and vC cannot be split anymore (they are reloads for instance) and they all interfere.</p>


<p>vA is assigned R1 vB is assigned R2 vC tries to evict vA but vA is already done. Regular register allocation fails.</p>


<p>Last chance recoloring kicks in: vC does as if vA was evicted =&gt; vC uses R1. vC is marked as fixed. vA needs to find a color. None are available. vA cannot evict vC: vC is a fixed virtual register now. vA does as if vB was evicted =&gt; vA uses R2. vB needs to find a color. R3 is available. Recoloring =&gt; vC = R1, vA = R2, vB = R3</p>


<p><span class="doxyComputerOutput">Order</span> defines the preferred allocation order for <span class="doxyComputerOutput">VirtReg</span>. <span class="doxyComputerOutput">NewRegs</span> will contain any new virtual register that have been created (split, spill) during the process and that must be assigned. <span class="doxyComputerOutput">FixedRegisters</span> contains all the virtual registers that cannot be recolored.</p>


<p><span class="doxyComputerOutput">RecolorStack</span> tracks the original assignments of successfully recolored registers.</p>


<p><span class="doxyComputerOutput">Depth</span> gives the current depth of the last chance recoloring.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a physical register that can be used for VirtReg or ~0u if none exists.</p></dd>
</dl>


<p>Declaration at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 1957 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### tryLocalSplit() {#abd218bb57b6eed4cda062356adae6a43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RAGreedy::tryLocalSplit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>tryLocalSplit - Try to split VirtReg into smaller intervals inside its only basic block.</p>

<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 1570 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### tryRecoloringCandidates() {#ab56889769f60c67206e74e54ad7bbd12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RAGreedy::tryRecoloringCandidates (PQueue &amp; RecoloringQueue, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs, <a href="/web-llvm/docs/api/namespaces/llvm/#a1d6cfdcc234093f39fb0719ddb649500">SmallVirtRegSet</a> &amp; FixedRegisters, <a href="/web-llvm/docs/api/classes/llvm/smallvector">RecoloringStack</a> &amp; RecolorStack, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>tryRecoloringCandidates - Try to assign a new color to every register in \RecoloringQueue.</p>


<p><span class="doxyComputerOutput">NewRegs</span> will contain any new virtual register created during the recoloring process. <span class="doxyComputerOutput">FixedRegisters</span>[in/out] contains all the registers that have been recolored.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if all virtual registers in RecoloringQueue were successfully recolored, false otherwise.</p></dd>
</dl>


<p>Declaration at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 2120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### tryRegionSplit() {#a1fb6dfa434046cc7ee2aeedc09b3ce39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister RAGreedy::tryRegionSplit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 1063 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### trySplit() {#a5181f9f12665ed6716a747a4fdbffec2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RAGreedy::trySplit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a1d6cfdcc234093f39fb0719ddb649500">SmallVirtRegSet</a> &amp; FixedRegisters)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>trySplit - Try to split VirtReg or one of its interferences, making it assignable.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Physreg when VirtReg may be assigned and/or new NewVRegs.</p></dd>
</dl>


<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 1801 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

### trySplitAroundHintReg() {#a2600051701cc651e7322e73fd6ec7167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RAGreedy::trySplitAroundHintReg (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Hint, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; NewVRegs, <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a> &amp; Order)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to split VirtReg around physical Hint register.</p>

<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>, definition at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BundleCand {#a128b75c0d40c89e5b87f91a843292de6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 32&gt; llvm::RAGreedy::BundleCand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Candidate map.</p>


<p>Each edge bundle is assigned to a GlobalCand entry, or to NoCand which indicates the stack interval.</p>


<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### Bundles {#aa970f0cb50b0c60d47bb1a1288712ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeBundles* llvm::RAGreedy::Bundles = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### CSRCost {#a88a37ccee06633c4e89967dce1a8568e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency llvm::RAGreedy::CSRCost</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callee-save register cost, calculated once per machine function.</p>

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### CutOffInfo {#a9a6439c5942f97229fd5091ab7a2f46a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::RAGreedy::CutOffInfo = CutOffStage::CO_None</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### DebugVars {#ae32e2c0f184ead36f1c132a975ec76cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveDebugVariables* llvm::RAGreedy::DebugVars = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### DomTree {#a5b0051f55729437208758c9b9168c29d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree* llvm::RAGreedy::DomTree = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### EvictAdvisor {#aa614f9d2b23051bfc1dbb2c029175226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;RegAllocEvictionAdvisor&gt; llvm::RAGreedy::EvictAdvisor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### ExtraInfo {#a040160998a56a7aca1d9f768dc91414c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;ExtraRegInfo&gt; llvm::RAGreedy::ExtraInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### GlobalCand {#aa53cf7488bedd62988bc02084a0e74bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;GlobalSplitCandidate, 32&gt; llvm::RAGreedy::GlobalCand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Candidate info for each PhysReg in <a href="/web-llvm/docs/api/classes/llvm/allocationorder">AllocationOrder</a>.</p>


<p>This vector never shrinks, but grows to the size of the largest register class.</p>


<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### Indexes {#abfc7d9931c89ee721fe4205f4d1b75ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndexes* llvm::RAGreedy::Indexes = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### IntfCache {#aae24326d9c0488808f067ae003df2720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InterferenceCache llvm::RAGreedy::IntfCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cached per-block interference maps.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### Loops {#af8a4f829070f028240bf15ffc22edce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLoopInfo* llvm::RAGreedy::Loops = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### MBFI {#ac0b6b0ddab681d0fb4ca736f23f8769a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBlockFrequencyInfo* llvm::RAGreedy::MBFI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### MF {#ae740923c145d21fee28f5fd833c88316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::RAGreedy::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### ORE {#aa4146be245e8fb552bcfb168808f7884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOptimizationRemarkEmitter* llvm::RAGreedy::ORE = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### PriorityAdvisor {#a58c6d2e74ecdbaa31c939d4340a9f454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;RegAllocPriorityAdvisor&gt; llvm::RAGreedy::PriorityAdvisor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### Queue {#a6538b17ea400426cfdcd477960fef7ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PQueue llvm::RAGreedy::Queue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### RegClassPriorityTrumpsGlobalness {#a21f25350939d2d89183b4e96e3f5a12a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RAGreedy::RegClassPriorityTrumpsGlobalness = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flags for the live range priority calculation, determined once per machine function.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### RegCosts {#a1e4dff8edfc06ff34a53ef6f679d1662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::RAGreedy::RegCosts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The register cost values.</p>


<p>This list will be recreated for each Machine <a href="/web-llvm/docs/api/classes/llvm/function">Function</a></p>


<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### ReverseLocalAssignment {#a3b81de0420a7e67a9642f51ed19bc653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RAGreedy::ReverseLocalAssignment = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### SA {#a223c21c6c93360b5f4461b3e0af2a85e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SplitAnalysis&gt; llvm::RAGreedy::SA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### SE {#ac78a46a02148fc3b6c31cd1bacfc7546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SplitEditor&gt; llvm::RAGreedy::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### SetOfBrokenHints {#a6ea97d5085ea163b14da0a15f24d4047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;const LiveInterval *, 8&gt; llvm::RAGreedy::SetOfBrokenHints</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of broken hints that may be reconciled later because of eviction.</p>

<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### SpillerInstance {#a7aa9d39514774ae077f35e02ad1a1030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Spiller&gt; llvm::RAGreedy::SpillerInstance</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### SpillPlacer {#aca3322707cfb26dd9c57234bb0111d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpillPlacement* llvm::RAGreedy::SpillPlacer = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### SplitConstraints {#a644f631cb3b2d9510c397d2b76d8fbe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SpillPlacement::BlockConstraint, 8&gt; llvm::RAGreedy::SplitConstraints</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All basic blocks where the current register has uses.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### TII {#a853123c7c53cbc65566b1c4af0dcf19b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::RAGreedy::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

### VRAI {#a5bb4eea876b59167bdafbe5206a8c991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;VirtRegAuxInfo&gt; llvm::RAGreedy::VRAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#acc1010755cb4b7307ca310cc6d86167f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char RAGreedy::ID = 0</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>


<p>Referenced by <a href="#abc503bf8aca22e0b405fbdf940ec76a2">RAGreedy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### StageName {#a72b20e4a4d7fbe89fc10903cab1fca26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Greedy Register false const char *const RAGreedy::StageName</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    "RS_New",
    "RS_Assign",
    "RS_Split",
    "RS_Split2",
    "RS_Spill",
    "RS_Memory",
    "RS_Done"
}
</div>
</dd>
</dl>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-h">RegAllocGreedy.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
