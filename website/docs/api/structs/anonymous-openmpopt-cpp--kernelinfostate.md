---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-openmpopt-cpp-/kernelinfostate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `KernelInfoState` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{OpenMPOpt.cpp}::KernelInfoState { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/abstractstate">AbstractState</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An interface to query the internal state of an abstract attribute. <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d5b0c807d03de0eefb1323235314164">KernelInfoState</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract State interface {. <a href="#a0d5b0c807d03de0eefb1323235314164">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f5e681720091b85ca02d4864484ed7b">KernelInfoState</a> (bool BestState)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c627de0c8f345722b7ade65d578fd2d">operator==</a> (const KernelInfoState &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/kernelinfostate">KernelInfoState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6ef64bf87a658114ae9223e21546c1c">operator^=</a> (const KernelInfoState &amp;KIS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>"Clamp" this state with <span class="doxyComputerOutput">KIS</span>. <a href="#ab6ef64bf87a658114ae9223e21546c1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/kernelinfostate">KernelInfoState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81fc78c76ad12631bf26b9f354dc21ce">operator&amp;=</a> (const KernelInfoState &amp;KIS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a053ba5c89174d9a2fbdaf8861f284ef7">isValidState</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractState::isValidState(...) <a href="#a053ba5c89174d9a2fbdaf8861f284ef7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c85d5253e092b937064e6cd75a9e2a7">isAtFixpoint</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractState::isAtFixpoint(...) <a href="#a5c85d5253e092b937064e6cd75a9e2a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e84549f82ddc1136bea2a57a9d4f355">indicatePessimisticFixpoint</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractState::indicatePessimisticFixpoint(...) <a href="#a4e84549f82ddc1136bea2a57a9d4f355">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64d031e14e10acc86cb7658aa7c8cf7b">indicateOptimisticFixpoint</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractState::indicateOptimisticFixpoint(...) <a href="#a64d031e14e10acc86cb7658aa7c8cf7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/kernelinfostate">KernelInfoState</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa272bf648e5b4b1a1ea9735720847143">getAssumed</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the assumed state. <a href="#aa272bf648e5b4b1a1ea9735720847143">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/kernelinfostate">KernelInfoState</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68a8194bcce8aeabfe3109e3c1aae67f">getAssumed</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac472eed79d513573b0927bbc9f1bd001">mayContainParallelRegion</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this kernel contains any OpenMP parallel regions. <a href="#ac472eed79d513573b0927bbc9f1bd001">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeb874832b637c86d6e50e02e1914281">IsAtFixpoint</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to track if we reached a fixpoint. <a href="#adeb874832b637c86d6e50e02e1914281">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-openmpopt-cpp-/#a4afe576309f31d3174c89f408e56ab11">BooleanStateWithPtrSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a>, false &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87c9e3cd99621ef0e9e2104f9c847431">ReachedKnownParallelRegions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The parallel regions (identified by the outlined parallel functions) that can be reached from the associated function. <a href="#a87c9e3cd99621ef0e9e2104f9c847431">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-openmpopt-cpp-/#a4afe576309f31d3174c89f408e56ab11">BooleanStateWithPtrSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a406ef2085f5b8aac20753bc35fe00523">ReachedUnknownParallelRegions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State to track what parallel region we might reach. <a href="#a406ef2085f5b8aac20753bc35fe00523">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-openmpopt-cpp-/#a4afe576309f31d3174c89f408e56ab11">BooleanStateWithPtrSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>, false &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adde402f89a9e23365839f80a5c883b2a">SPMDCompatibilityTracker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State to track if we are in SPMD-mode, assumed or know, and why we decided we cannot be. <a href="#adde402f89a9e23365839f80a5c883b2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c3c4ecfaa275680d338ac295910c533">KernelInitCB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The __kmpc_target_init call in this kernel, if any. <a href="#a4c3c4ecfaa275680d338ac295910c533">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantstruct">ConstantStruct</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d5a64bfc9a5dbf14f540876d8b15e1d">KernelEnvC</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The constant kernel environement as taken from and passed to __kmpc_target_init. <a href="#a0d5a64bfc9a5dbf14f540876d8b15e1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c7a5a5c0f6dc35c8e9a318c8ad01510">KernelDeinitCB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The __kmpc_target_deinit call in this kernel, if any. <a href="#a5c7a5a5c0f6dc35c8e9a318c8ad01510">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68cc557d31388bffeec353f23bc21833">IsKernelEntry</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to indicate if the associated function is a kernel entry. <a href="#a68cc557d31388bffeec353f23bc21833">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-openmpopt-cpp-/#a4afe576309f31d3174c89f408e56ab11">BooleanStateWithPtrSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>, false &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d2f8bfa10468d2c982bb8afdd8e1647">ReachingKernelEntries</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State to track what kernel entries can reach the associated function. <a href="#a7d2f8bfa10468d2c982bb8afdd8e1647">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/booleanstatewithsetvector">BooleanStateWithSetVector</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e85903539838e7468800b801727f1fa">ParallelLevels</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State to indicate if we can track parallel level of the associated function. <a href="#a4e85903539838e7468800b801727f1fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e6728a723b8891df4aafae495636132">NestedParallelism</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag that indicates if the kernel has nested Parallelism. <a href="#a8e6728a723b8891df4aafae495636132">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/kernelinfostate">KernelInfoState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2f836a4c3df4b02a5cbc4271bc57442">getBestState</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return empty set as the best state of potential values. <a href="#ad2f836a4c3df4b02a5cbc4271bc57442">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/kernelinfostate">KernelInfoState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93db20942479ee28698c7fc2ac907b7a">getBestState</a> (KernelInfoState &amp;KIS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/kernelinfostate">KernelInfoState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583bdf4924630f5ec489166873504d5d">getWorstState</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return full set as the worst state of potential values. <a href="#a583bdf4924630f5ec489166873504d5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### KernelInfoState() {#a0d5b0c807d03de0eefb1323235314164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{OpenMPOpt.cpp}::KernelInfoState::KernelInfoState ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Abstract State interface {.</p>

<p>Definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#aa272bf648e5b4b1a1ea9735720847143">getAssumed</a>, <a href="#a68a8194bcce8aeabfe3109e3c1aae67f">getAssumed</a>, <a href="#ad2f836a4c3df4b02a5cbc4271bc57442">getBestState</a>, <a href="#a93db20942479ee28698c7fc2ac907b7a">getBestState</a>, <a href="#a583bdf4924630f5ec489166873504d5d">getWorstState</a>, <a href="#a81fc78c76ad12631bf26b9f354dc21ce">operator&amp;=</a>, <a href="#a8c627de0c8f345722b7ade65d578fd2d">operator==</a> and <a href="#ab6ef64bf87a658114ae9223e21546c1c">operator^=</a>.</p>

</div>
</div>

### KernelInfoState() {#a7f5e681720091b85ca02d4864484ed7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{OpenMPOpt.cpp}::KernelInfoState::KernelInfoState (bool BestState)</td>
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



<p>Definition at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Reference <a href="#a4e84549f82ddc1136bea2a57a9d4f355">indicatePessimisticFixpoint</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&amp;=() {#a81fc78c76ad12631bf26b9f354dc21ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KernelInfoState anonymous{OpenMPOpt.cpp}::KernelInfoState::operator&amp;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/kernelinfostate">KernelInfoState</a> &amp; KIS)</td>
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



<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Reference <a href="#a0d5b0c807d03de0eefb1323235314164">KernelInfoState</a>.</p>

</div>
</div>

### operator^=() {#ab6ef64bf87a658114ae9223e21546c1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KernelInfoState anonymous{OpenMPOpt.cpp}::KernelInfoState::operator^= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/kernelinfostate">KernelInfoState</a> &amp; KIS)</td>
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

<p>"Clamp" this state with <span class="doxyComputerOutput">KIS</span>.</p>

<p>Definition at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="#a5c7a5a5c0f6dc35c8e9a318c8ad01510">KernelDeinitCB</a>, <a href="#a0d5a64bfc9a5dbf14f540876d8b15e1d">KernelEnvC</a>, <a href="#a0d5b0c807d03de0eefb1323235314164">KernelInfoState</a>, <a href="#a4c3c4ecfaa275680d338ac295910c533">KernelInitCB</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a8e6728a723b8891df4aafae495636132">NestedParallelism</a>, <a href="#a87c9e3cd99621ef0e9e2104f9c847431">ReachedKnownParallelRegions</a>, <a href="#a406ef2085f5b8aac20753bc35fe00523">ReachedUnknownParallelRegions</a> and <a href="#adde402f89a9e23365839f80a5c883b2a">SPMDCompatibilityTracker</a>.</p>

</div>
</div>

### operator==() {#a8c627de0c8f345722b7ade65d578fd2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::KernelInfoState::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/kernelinfostate">KernelInfoState</a> &amp; RHS)</td>
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



<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="#a0d5b0c807d03de0eefb1323235314164">KernelInfoState</a>, <a href="#a8e6728a723b8891df4aafae495636132">NestedParallelism</a>, <a href="#a4e85903539838e7468800b801727f1fa">ParallelLevels</a>, <a href="#a87c9e3cd99621ef0e9e2104f9c847431">ReachedKnownParallelRegions</a>, <a href="#a406ef2085f5b8aac20753bc35fe00523">ReachedUnknownParallelRegions</a>, <a href="#a7d2f8bfa10468d2c982bb8afdd8e1647">ReachingKernelEntries</a> and <a href="#adde402f89a9e23365839f80a5c883b2a">SPMDCompatibilityTracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAssumed() {#aa272bf648e5b4b1a1ea9735720847143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KernelInfoState &amp; anonymous{OpenMPOpt.cpp}::KernelInfoState::getAssumed ()</td>
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

<p>Return the assumed state.</p>

<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Reference <a href="#a0d5b0c807d03de0eefb1323235314164">KernelInfoState</a>.</p>

</div>
</div>

### getAssumed() {#a68a8194bcce8aeabfe3109e3c1aae67f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const KernelInfoState &amp; anonymous{OpenMPOpt.cpp}::KernelInfoState::getAssumed ()</td>
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



<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Reference <a href="#a0d5b0c807d03de0eefb1323235314164">KernelInfoState</a>.</p>

</div>
</div>

### indicateOptimisticFixpoint() {#a64d031e14e10acc86cb7658aa7c8cf7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{OpenMPOpt.cpp}::KernelInfoState::indicateOptimisticFixpoint ()</td>
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

<p>See AbstractState::indicateOptimisticFixpoint(...)</p>

<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="#adeb874832b637c86d6e50e02e1914281">IsAtFixpoint</a>, <a href="#a4e85903539838e7468800b801727f1fa">ParallelLevels</a>, <a href="#a87c9e3cd99621ef0e9e2104f9c847431">ReachedKnownParallelRegions</a>, <a href="#a406ef2085f5b8aac20753bc35fe00523">ReachedUnknownParallelRegions</a>, <a href="#a7d2f8bfa10468d2c982bb8afdd8e1647">ReachingKernelEntries</a>, <a href="#adde402f89a9e23365839f80a5c883b2a">SPMDCompatibilityTracker</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a>.</p>

</div>
</div>

### indicatePessimisticFixpoint() {#a4e84549f82ddc1136bea2a57a9d4f355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{OpenMPOpt.cpp}::KernelInfoState::indicatePessimisticFixpoint ()</td>
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

<p>See AbstractState::indicatePessimisticFixpoint(...)</p>

<p>Definition at line 756 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a>, <a href="#adeb874832b637c86d6e50e02e1914281">IsAtFixpoint</a>, <a href="#a8e6728a723b8891df4aafae495636132">NestedParallelism</a>, <a href="#a4e85903539838e7468800b801727f1fa">ParallelLevels</a>, <a href="#a87c9e3cd99621ef0e9e2104f9c847431">ReachedKnownParallelRegions</a>, <a href="#a406ef2085f5b8aac20753bc35fe00523">ReachedUnknownParallelRegions</a>, <a href="#a7d2f8bfa10468d2c982bb8afdd8e1647">ReachingKernelEntries</a> and <a href="#adde402f89a9e23365839f80a5c883b2a">SPMDCompatibilityTracker</a>.</p>


<p>Referenced by <a href="#a7f5e681720091b85ca02d4864484ed7b">KernelInfoState</a>.</p>

</div>
</div>

### isAtFixpoint() {#a5c85d5253e092b937064e6cd75a9e2a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::KernelInfoState::isAtFixpoint ()</td>
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

<p>See AbstractState::isAtFixpoint(...)</p>

<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Reference <a href="#adeb874832b637c86d6e50e02e1914281">IsAtFixpoint</a>.</p>

</div>
</div>

### isValidState() {#a053ba5c89174d9a2fbdaf8861f284ef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::KernelInfoState::isValidState ()</td>
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

<p>See AbstractState::isValidState(...)</p>

<p>Definition at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

### mayContainParallelRegion() {#ac472eed79d513573b0927bbc9f1bd001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::KernelInfoState::mayContainParallelRegion ()</td>
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

<p>Returns true if this kernel contains any OpenMP parallel regions.</p>

<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="#a87c9e3cd99621ef0e9e2104f9c847431">ReachedKnownParallelRegions</a> and <a href="#a406ef2085f5b8aac20753bc35fe00523">ReachedUnknownParallelRegions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsAtFixpoint {#adeb874832b637c86d6e50e02e1914281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::KernelInfoState::IsAtFixpoint = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to track if we reached a fixpoint.</p>

<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a64d031e14e10acc86cb7658aa7c8cf7b">indicateOptimisticFixpoint</a>, <a href="#a4e84549f82ddc1136bea2a57a9d4f355">indicatePessimisticFixpoint</a> and <a href="#a5c85d5253e092b937064e6cd75a9e2a7">isAtFixpoint</a>.</p>

</div>
</div>

### IsKernelEntry {#a68cc557d31388bffeec353f23bc21833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::KernelInfoState::IsKernelEntry = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to indicate if the associated function is a kernel entry.</p>

<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

### KernelDeinitCB {#a5c7a5a5c0f6dc35c8e9a318c8ad01510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase* anonymous{OpenMPOpt.cpp}::KernelInfoState::KernelDeinitCB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The __kmpc_target_deinit call in this kernel, if any.</p>


<p>If we find more than one we abort as the kernel is malformed.</p>


<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#ab6ef64bf87a658114ae9223e21546c1c">operator^=</a>.</p>

</div>
</div>

### KernelEnvC {#a0d5a64bfc9a5dbf14f540876d8b15e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantStruct* anonymous{OpenMPOpt.cpp}::KernelInfoState::KernelEnvC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The constant kernel environement as taken from and passed to __kmpc_target_init.</p>

<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#ab6ef64bf87a658114ae9223e21546c1c">operator^=</a>.</p>

</div>
</div>

### KernelInitCB {#a4c3c4ecfaa275680d338ac295910c533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase* anonymous{OpenMPOpt.cpp}::KernelInfoState::KernelInitCB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The __kmpc_target_init call in this kernel, if any.</p>


<p>If we find more than one we abort as the kernel is malformed.</p>


<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#ab6ef64bf87a658114ae9223e21546c1c">operator^=</a>.</p>

</div>
</div>

### NestedParallelism {#a8e6728a723b8891df4aafae495636132}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::KernelInfoState::NestedParallelism = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag that indicates if the kernel has nested Parallelism.</p>

<p>Definition at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a4e84549f82ddc1136bea2a57a9d4f355">indicatePessimisticFixpoint</a>, <a href="#a8c627de0c8f345722b7ade65d578fd2d">operator==</a> and <a href="#ab6ef64bf87a658114ae9223e21546c1c">operator^=</a>.</p>

</div>
</div>

### ParallelLevels {#a4e85903539838e7468800b801727f1fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BooleanStateWithSetVector&lt;uint8_t&gt; anonymous{OpenMPOpt.cpp}::KernelInfoState::ParallelLevels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>State to indicate if we can track parallel level of the associated function.</p>


<p>We will give up tracking if we encounter unknown caller or the caller is __kmpc_parallel_51.</p>


<p>Definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a64d031e14e10acc86cb7658aa7c8cf7b">indicateOptimisticFixpoint</a>, <a href="#a4e84549f82ddc1136bea2a57a9d4f355">indicatePessimisticFixpoint</a> and <a href="#a8c627de0c8f345722b7ade65d578fd2d">operator==</a>.</p>

</div>
</div>

### ReachedKnownParallelRegions {#a87c9e3cd99621ef0e9e2104f9c847431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BooleanStateWithPtrSetVector&lt;CallBase, false&gt; anonymous{OpenMPOpt.cpp}::KernelInfoState::ReachedKnownParallelRegions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The parallel regions (identified by the outlined parallel functions) that can be reached from the associated function.</p>

<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a64d031e14e10acc86cb7658aa7c8cf7b">indicateOptimisticFixpoint</a>, <a href="#a4e84549f82ddc1136bea2a57a9d4f355">indicatePessimisticFixpoint</a>, <a href="#ac472eed79d513573b0927bbc9f1bd001">mayContainParallelRegion</a>, <a href="#a8c627de0c8f345722b7ade65d578fd2d">operator==</a> and <a href="#ab6ef64bf87a658114ae9223e21546c1c">operator^=</a>.</p>

</div>
</div>

### ReachedUnknownParallelRegions {#a406ef2085f5b8aac20753bc35fe00523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BooleanStateWithPtrSetVector&lt;CallBase&gt; anonymous{OpenMPOpt.cpp}::KernelInfoState::ReachedUnknownParallelRegions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>State to track what parallel region we might reach.</p>

<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a64d031e14e10acc86cb7658aa7c8cf7b">indicateOptimisticFixpoint</a>, <a href="#a4e84549f82ddc1136bea2a57a9d4f355">indicatePessimisticFixpoint</a>, <a href="#ac472eed79d513573b0927bbc9f1bd001">mayContainParallelRegion</a>, <a href="#a8c627de0c8f345722b7ade65d578fd2d">operator==</a> and <a href="#ab6ef64bf87a658114ae9223e21546c1c">operator^=</a>.</p>

</div>
</div>

### ReachingKernelEntries {#a7d2f8bfa10468d2c982bb8afdd8e1647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BooleanStateWithPtrSetVector&lt;Function, false&gt; anonymous{OpenMPOpt.cpp}::KernelInfoState::ReachingKernelEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>State to track what kernel entries can reach the associated function.</p>

<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a64d031e14e10acc86cb7658aa7c8cf7b">indicateOptimisticFixpoint</a>, <a href="#a4e84549f82ddc1136bea2a57a9d4f355">indicatePessimisticFixpoint</a> and <a href="#a8c627de0c8f345722b7ade65d578fd2d">operator==</a>.</p>

</div>
</div>

### SPMDCompatibilityTracker {#adde402f89a9e23365839f80a5c883b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BooleanStateWithPtrSetVector&lt;Instruction, false&gt; anonymous{OpenMPOpt.cpp}::KernelInfoState::SPMDCompatibilityTracker</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>State to track if we are in SPMD-mode, assumed or know, and why we decided we cannot be.</p>


<p>If it is assumed, then RequiresFullRuntime should also be false.</p>


<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a64d031e14e10acc86cb7658aa7c8cf7b">indicateOptimisticFixpoint</a>, <a href="#a4e84549f82ddc1136bea2a57a9d4f355">indicatePessimisticFixpoint</a>, <a href="#a8c627de0c8f345722b7ade65d578fd2d">operator==</a> and <a href="#ab6ef64bf87a658114ae9223e21546c1c">operator^=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getBestState() {#ad2f836a4c3df4b02a5cbc4271bc57442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KernelInfoState anonymous{OpenMPOpt.cpp}::KernelInfoState::getBestState ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return empty set as the best state of potential values.</p>

<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Reference <a href="#a0d5b0c807d03de0eefb1323235314164">KernelInfoState</a>.</p>


<p>Referenced by <a href="#a93db20942479ee28698c7fc2ac907b7a">getBestState</a>.</p>

</div>
</div>

### getBestState() {#a93db20942479ee28698c7fc2ac907b7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KernelInfoState anonymous{OpenMPOpt.cpp}::KernelInfoState::getBestState (<a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/kernelinfostate">KernelInfoState</a> &amp; KIS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="#ad2f836a4c3df4b02a5cbc4271bc57442">getBestState</a> and <a href="#a0d5b0c807d03de0eefb1323235314164">KernelInfoState</a>.</p>

</div>
</div>

### getWorstState() {#a583bdf4924630f5ec489166873504d5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KernelInfoState anonymous{OpenMPOpt.cpp}::KernelInfoState::getWorstState ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return full set as the worst state of potential values.</p>

<p>Definition at line 812 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Reference <a href="#a0d5b0c807d03de0eefb1323235314164">KernelInfoState</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
