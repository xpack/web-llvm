---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/integerrangestate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IntegerRangeState` Struct Reference

<p>State for an integer range. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::IntegerRangeState { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
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

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/statewrapper">StateWrapper&lt;StateTy, BaseType, Ts&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to tie a abstract state implementation to an abstract attribute. <a href="/web-llvm/docs/api/structs/llvm/statewrapper/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642798e1c0646dd4dee731ad3b1525be">IntegerRangeState</a> (uint32_t BitWidth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a96611f0657001f1ac807026a1ed79f">IntegerRangeState</a> (const ConstantRange &amp;CR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a651d3925edf3d25a6039d4662f8e3a12">operator==</a> (const IntegerRangeState &amp;R) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equality for <a href="/web-llvm/docs/api/structs/llvm/integerrangestate">IntegerRangeState</a>. <a href="#a651d3925edf3d25a6039d4662f8e3a12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/integerrangestate">IntegerRangeState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fddc5e209f863af9d7956c6ef451bfa">operator^=</a> (const IntegerRangeState &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>"Clamp" this state with <span class="doxyComputerOutput">R</span>. <a href="#a0fddc5e209f863af9d7956c6ef451bfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/integerrangestate">IntegerRangeState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25176ef1c7380949da3dc2d015bce285">operator&amp;=</a> (const IntegerRangeState &amp;R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac96a74a0334b982914fcebf7720a98b9">getBitWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return associated values' bit width. <a href="#ac96a74a0334b982914fcebf7720a98b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dc41a8b06647f7b13a7575e6951d8d8">isValidState</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#ae2b42216b30b52bbb803df6884ef34d2">AbstractState::isValidState()</a> <a href="#a7dc41a8b06647f7b13a7575e6951d8d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e2ad96ab0bac244505b38fd3c2527cb">isAtFixpoint</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#adab11027e1a9fdc4c600bb8dba1df413">AbstractState::isAtFixpoint()</a> <a href="#a2e2ad96ab0bac244505b38fd3c2527cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada645f14d8a81d9640cb8921cf509517">indicateOptimisticFixpoint</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractState::indicateOptimisticFixpoint(...) <a href="#ada645f14d8a81d9640cb8921cf509517">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa13036717a5ffd3ae9b9d717f981978e">indicatePessimisticFixpoint</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractState::indicatePessimisticFixpoint(...) <a href="#aa13036717a5ffd3ae9b9d717f981978e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf5d2b73a9ab6a5f6c038ccc3b87621e">getKnown</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the known state encoding. <a href="#aaf5d2b73a9ab6a5f6c038ccc3b87621e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3c5924f36fc704b6a1f12211c897113">getAssumed</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the assumed state encoding. <a href="#ac3c5924f36fc704b6a1f12211c897113">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98c259eba1e3f4a48b73b00e4b17b619">unionAssumed</a> (const ConstantRange &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unite assumed range with the passed state. <a href="#a98c259eba1e3f4a48b73b00e4b17b619">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39c808f1201e5d3c4ef994be7c26519a">unionAssumed</a> (const IntegerRangeState &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="#a98c259eba1e3f4a48b73b00e4b17b619">IntegerRangeState::unionAssumed</a>(..). <a href="#a39c808f1201e5d3c4ef994be7c26519a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba968663106abb1b267a4a8673b89f55">intersectKnown</a> (const ConstantRange &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Intersect known range with the passed state. <a href="#aba968663106abb1b267a4a8673b89f55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78f115a7b8f44272eee68f2938959f53">intersectKnown</a> (const IntegerRangeState &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="#aba968663106abb1b267a4a8673b89f55">IntegerRangeState::intersectKnown</a>(..). <a href="#a78f115a7b8f44272eee68f2938959f53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8dff1bd0a385be9d9679112abd6a9">BitWidth</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitwidth of the associated value. <a href="#a7ee8dff1bd0a385be9d9679112abd6a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4386fbf0609524525ddb030f243ce4a1">Assumed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State representing assumed range, initially set to empty. <a href="#a4386fbf0609524525ddb030f243ce4a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a807fb347d0feef5f839837e6d3dc5dbc">Known</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State representing known range, initially set to [-inf, inf]. <a href="#a807fb347d0feef5f839837e6d3dc5dbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade656897ef13aaa480677e37a4fcfa43">getWorstState</a> (uint32_t BitWidth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the worst possible representable state. <a href="#ade656897ef13aaa480677e37a4fcfa43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd6cabd61fdf0fdf8c0b1adf560e032b">getBestState</a> (uint32_t BitWidth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the best possible representable state. <a href="#afd6cabd61fdf0fdf8c0b1adf560e032b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7db3cda88846a13412374a1060e7dd79">getBestState</a> (const IntegerRangeState &amp;IRS)</td>
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

<p>State for an integer range.</p>

<p>Definition at line 2939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IntegerRangeState() {#a642798e1c0646dd4dee731ad3b1525be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntegerRangeState::IntegerRangeState (uint32_t BitWidth)</td>
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



<p>Definition at line 2950 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a4386fbf0609524525ddb030f243ce4a1">Assumed</a>, <a href="#a7ee8dff1bd0a385be9d9679112abd6a9">BitWidth</a> and <a href="#a807fb347d0feef5f839837e6d3dc5dbc">Known</a>.</p>


<p>Referenced by <a href="#a7db3cda88846a13412374a1060e7dd79">getBestState</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdflatworkgroupsize/#aef14a169486d41becf73e9ef0c945760">anonymous{AMDGPUAttributor.cpp}::AAAMDFlatWorkGroupSize::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a798b523ae8591cd1d289cde6b234c1a6">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::initialize</a>, <a href="#a78f115a7b8f44272eee68f2938959f53">intersectKnown</a>, <a href="#a25176ef1c7380949da3dc2d015bce285">operator&amp;=</a>, <a href="#a651d3925edf3d25a6039d4662f8e3a12">operator==</a>, <a href="#a0fddc5e209f863af9d7956c6ef451bfa">operator^=</a>, <a href="#a39c808f1201e5d3c4ef994be7c26519a">unionAssumed</a> and <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a6e7ec06ac86c48e6d651e37817ed7359">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::updateImpl</a>.</p>

</div>
</div>

### IntegerRangeState() {#a5a96611f0657001f1ac807026a1ed79f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntegerRangeState::IntegerRangeState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
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



<p>Definition at line 2954 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a4386fbf0609524525ddb030f243ce4a1">Assumed</a>, <a href="#a7ee8dff1bd0a385be9d9679112abd6a9">BitWidth</a>, <a href="#ac96a74a0334b982914fcebf7720a98b9">getBitWidth</a>, <a href="#ade656897ef13aaa480677e37a4fcfa43">getWorstState</a> and <a href="#a807fb347d0feef5f839837e6d3dc5dbc">Known</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&amp;=() {#a25176ef1c7380949da3dc2d015bce285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerRangeState llvm::IntegerRangeState::operator&amp;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/integerrangestate">IntegerRangeState</a> &amp; R)</td>
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



<p>Definition at line 3037 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a4386fbf0609524525ddb030f243ce4a1">Assumed</a>, <a href="#a642798e1c0646dd4dee731ad3b1525be">IntegerRangeState</a> and <a href="#a807fb347d0feef5f839837e6d3dc5dbc">Known</a>.</p>

</div>
</div>

### operator^=() {#a0fddc5e209f863af9d7956c6ef451bfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerRangeState llvm::IntegerRangeState::operator^= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/integerrangestate">IntegerRangeState</a> &amp; R)</td>
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

<p>"Clamp" this state with <span class="doxyComputerOutput">R</span>.</p>


<p>The result is subtype dependent but it is intended that only information assumed in both states will be assumed in this one afterwards.</p>


<p>Definition at line 3030 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a642798e1c0646dd4dee731ad3b1525be">IntegerRangeState</a> and <a href="#a98c259eba1e3f4a48b73b00e4b17b619">unionAssumed</a>.</p>

</div>
</div>

### operator==() {#a651d3925edf3d25a6039d4662f8e3a12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntegerRangeState::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/integerrangestate">IntegerRangeState</a> &amp; R)</td>
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

<p>Equality for <a href="/web-llvm/docs/api/structs/llvm/integerrangestate">IntegerRangeState</a>.</p>

<p>Definition at line 3023 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#ac3c5924f36fc704b6a1f12211c897113">getAssumed</a>, <a href="#aaf5d2b73a9ab6a5f6c038ccc3b87621e">getKnown</a> and <a href="#a642798e1c0646dd4dee731ad3b1525be">IntegerRangeState</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAssumed() {#ac3c5924f36fc704b6a1f12211c897113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::IntegerRangeState::getAssumed ()</td>
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

<p>Return the assumed state encoding.</p>

<p>Definition at line 2998 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a4386fbf0609524525ddb030f243ce4a1">Assumed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdsizerangeattribute/#a67ae1ad562dccec0023641ab0e8fc48e">anonymous{AMDGPUAttributor.cpp}::AAAMDSizeRangeAttribute::emitAttributeIfNotDefaultAfterClamp</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdsizerangeattribute/#a6cca267d184aa0f88f69f9423e2bd573">anonymous{AMDGPUAttributor.cpp}::AAAMDSizeRangeAttribute::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a5b5568e59f33b74c9b10462295c0ecb6">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#ad39b005f46b9ffb7cc54942161210656">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getAssumedConstantRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8a5d9712817e5a3a55a593c62ed3a698">llvm::operator&lt;&lt;</a>, <a href="#a651d3925edf3d25a6039d4662f8e3a12">operator==</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#a8f460c92906b40c343854b69d48db50a">stripAndAccumulateOffsets</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a6e7ec06ac86c48e6d651e37817ed7359">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a326d4c3fb95ebe6cbdca9c9e312da4a8">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::updateImpl</a>.</p>

</div>
</div>

### getBitWidth() {#ac96a74a0334b982914fcebf7720a98b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::IntegerRangeState::getBitWidth ()</td>
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

<p>Return associated values' bit width.</p>

<p>Definition at line 2972 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a7ee8dff1bd0a385be9d9679112abd6a9">BitWidth</a>.</p>


<p>Referenced by <a href="#a7db3cda88846a13412374a1060e7dd79">getBestState</a>, <a href="#a5a96611f0657001f1ac807026a1ed79f">IntegerRangeState</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8a5d9712817e5a3a55a593c62ed3a698">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### getKnown() {#aaf5d2b73a9ab6a5f6c038ccc3b87621e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::IntegerRangeState::getKnown ()</td>
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

<p>Return the known state encoding.</p>

<p>Definition at line 2995 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a807fb347d0feef5f839837e6d3dc5dbc">Known</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a5b5568e59f33b74c9b10462295c0ecb6">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a6d362ce614123852df0f345317c6c957">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getKnownConstantRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8a5d9712817e5a3a55a593c62ed3a698">llvm::operator&lt;&lt;</a>, <a href="#a651d3925edf3d25a6039d4662f8e3a12">operator==</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#a8f460c92906b40c343854b69d48db50a">stripAndAccumulateOffsets</a>.</p>

</div>
</div>

### indicateOptimisticFixpoint() {#ada645f14d8a81d9640cb8921cf509517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus llvm::IntegerRangeState::indicateOptimisticFixpoint ()</td>
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

<p>Definition at line 2983 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a4386fbf0609524525ddb030f243ce4a1">Assumed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a> and <a href="#a807fb347d0feef5f839837e6d3dc5dbc">Known</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdflatworkgroupsize/#aef14a169486d41becf73e9ef0c945760">anonymous{AMDGPUAttributor.cpp}::AAAMDFlatWorkGroupSize::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a798b523ae8591cd1d289cde6b234c1a6">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::initialize</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a2b827c74bf3fdb8d906b3eeb0e1e5f8f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::initialize</a>.</p>

</div>
</div>

### indicatePessimisticFixpoint() {#aa13036717a5ffd3ae9b9d717f981978e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus llvm::IntegerRangeState::indicatePessimisticFixpoint ()</td>
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

<p>Definition at line 2989 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a4386fbf0609524525ddb030f243ce4a1">Assumed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a> and <a href="#a807fb347d0feef5f839837e6d3dc5dbc">Known</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a2b827c74bf3fdb8d906b3eeb0e1e5f8f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a98a9160e61aee9e51514937e1cd8b2f0">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangereturned/#aed13ba291673dddaaa77b0ad21c4182d">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a6e7ec06ac86c48e6d651e37817ed7359">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a326d4c3fb95ebe6cbdca9c9e312da4a8">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdsizerangeattribute/#a29bd4b6b1ce02623406f833daf4668cc">anonymous{AMDGPUAttributor.cpp}::AAAMDSizeRangeAttribute::updateImplImpl</a>.</p>

</div>
</div>

### intersectKnown() {#aba968663106abb1b267a4a8673b89f55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntegerRangeState::intersectKnown (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; R)</td>
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

<p>Intersect known range with the passed state.</p>

<p>Definition at line 3012 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a4386fbf0609524525ddb030f243ce4a1">Assumed</a> and <a href="#a807fb347d0feef5f839837e6d3dc5dbc">Known</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangecallsitereturned/#adea35464b5cc6628399f3a058c28bb0b">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a2b827c74bf3fdb8d906b3eeb0e1e5f8f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a98a9160e61aee9e51514937e1cd8b2f0">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::initialize</a> and <a href="#a78f115a7b8f44272eee68f2938959f53">intersectKnown</a>.</p>

</div>
</div>

### intersectKnown() {#a78f115a7b8f44272eee68f2938959f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntegerRangeState::intersectKnown (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/integerrangestate">IntegerRangeState</a> &amp; R)</td>
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

<p>See <a href="#aba968663106abb1b267a4a8673b89f55">IntegerRangeState::intersectKnown</a>(..).</p>

<p>Definition at line 3018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a642798e1c0646dd4dee731ad3b1525be">IntegerRangeState</a> and <a href="#aba968663106abb1b267a4a8673b89f55">intersectKnown</a>.</p>

</div>
</div>

### isAtFixpoint() {#a2e2ad96ab0bac244505b38fd3c2527cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntegerRangeState::isAtFixpoint ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#adab11027e1a9fdc4c600bb8dba1df413">AbstractState::isAtFixpoint()</a></p>

<p>Definition at line 2980 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a4386fbf0609524525ddb030f243ce4a1">Assumed</a> and <a href="#a807fb347d0feef5f839837e6d3dc5dbc">Known</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a2b827c74bf3fdb8d906b3eeb0e1e5f8f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::initialize</a>.</p>

</div>
</div>

### isValidState() {#a7dc41a8b06647f7b13a7575e6951d8d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntegerRangeState::isValidState ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#ae2b42216b30b52bbb803df6884ef34d2">AbstractState::isValidState()</a></p>

<p>Definition at line 2975 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a4386fbf0609524525ddb030f243ce4a1">Assumed</a> and <a href="#a7ee8dff1bd0a385be9d9679112abd6a9">BitWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a6e7ec06ac86c48e6d651e37817ed7359">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::updateImpl</a>.</p>

</div>
</div>

### unionAssumed() {#a98c259eba1e3f4a48b73b00e4b17b619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntegerRangeState::unionAssumed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; R)</td>
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

<p>Unite assumed range with the passed state.</p>

<p>Definition at line 3001 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a4386fbf0609524525ddb030f243ce4a1">Assumed</a> and <a href="#a807fb347d0feef5f839837e6d3dc5dbc">Known</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a2b827c74bf3fdb8d906b3eeb0e1e5f8f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::initialize</a>, <a href="#a0fddc5e209f863af9d7956c6ef451bfa">operator^=</a> and <a href="#a39c808f1201e5d3c4ef994be7c26519a">unionAssumed</a>.</p>

</div>
</div>

### unionAssumed() {#a39c808f1201e5d3c4ef994be7c26519a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntegerRangeState::unionAssumed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/integerrangestate">IntegerRangeState</a> &amp; R)</td>
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

<p>See <a href="#a98c259eba1e3f4a48b73b00e4b17b619">IntegerRangeState::unionAssumed</a>(..).</p>

<p>Definition at line 3007 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a642798e1c0646dd4dee731ad3b1525be">IntegerRangeState</a> and <a href="#a98c259eba1e3f4a48b73b00e4b17b619">unionAssumed</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Assumed {#a4386fbf0609524525ddb030f243ce4a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::IntegerRangeState::Assumed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>State representing assumed range, initially set to empty.</p>

<p>Definition at line 2945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#ac3c5924f36fc704b6a1f12211c897113">getAssumed</a>, <a href="#ada645f14d8a81d9640cb8921cf509517">indicateOptimisticFixpoint</a>, <a href="#aa13036717a5ffd3ae9b9d717f981978e">indicatePessimisticFixpoint</a>, <a href="#a5a96611f0657001f1ac807026a1ed79f">IntegerRangeState</a>, <a href="#a642798e1c0646dd4dee731ad3b1525be">IntegerRangeState</a>, <a href="#aba968663106abb1b267a4a8673b89f55">intersectKnown</a>, <a href="#a2e2ad96ab0bac244505b38fd3c2527cb">isAtFixpoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a745987cc07ad13e3d1b5e07ea6d8e78f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::isBetterRange</a>, <a href="#a7dc41a8b06647f7b13a7575e6951d8d8">isValidState</a>, <a href="#a25176ef1c7380949da3dc2d015bce285">operator&amp;=</a> and <a href="#a98c259eba1e3f4a48b73b00e4b17b619">unionAssumed</a>.</p>

</div>
</div>

### BitWidth {#a7ee8dff1bd0a385be9d9679112abd6a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::IntegerRangeState::BitWidth</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bitwidth of the associated value.</p>

<p>Definition at line 2942 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#afd6cabd61fdf0fdf8c0b1adf560e032b">getBestState</a>, <a href="#ac96a74a0334b982914fcebf7720a98b9">getBitWidth</a>, <a href="#ade656897ef13aaa480677e37a4fcfa43">getWorstState</a>, <a href="#a5a96611f0657001f1ac807026a1ed79f">IntegerRangeState</a>, <a href="#a642798e1c0646dd4dee731ad3b1525be">IntegerRangeState</a> and <a href="#a7dc41a8b06647f7b13a7575e6951d8d8">isValidState</a>.</p>

</div>
</div>

### Known {#a807fb347d0feef5f839837e6d3dc5dbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::IntegerRangeState::Known</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>State representing known range, initially set to [-inf, inf].</p>

<p>Definition at line 2948 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#aaf5d2b73a9ab6a5f6c038ccc3b87621e">getKnown</a>, <a href="#ada645f14d8a81d9640cb8921cf509517">indicateOptimisticFixpoint</a>, <a href="#aa13036717a5ffd3ae9b9d717f981978e">indicatePessimisticFixpoint</a>, <a href="#a5a96611f0657001f1ac807026a1ed79f">IntegerRangeState</a>, <a href="#a642798e1c0646dd4dee731ad3b1525be">IntegerRangeState</a>, <a href="#aba968663106abb1b267a4a8673b89f55">intersectKnown</a>, <a href="#a2e2ad96ab0bac244505b38fd3c2527cb">isAtFixpoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a745987cc07ad13e3d1b5e07ea6d8e78f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::isBetterRange</a>, <a href="#a25176ef1c7380949da3dc2d015bce285">operator&amp;=</a> and <a href="#a98c259eba1e3f4a48b73b00e4b17b619">unionAssumed</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getBestState() {#afd6cabd61fdf0fdf8c0b1adf560e032b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::IntegerRangeState::getBestState (uint32_t BitWidth)</td>
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

<p>Return the best possible representable state.</p>

<p>Definition at line 2964 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a7ee8dff1bd0a385be9d9679112abd6a9">BitWidth</a>.</p>


<p>Referenced by <a href="#a7db3cda88846a13412374a1060e7dd79">getBestState</a>.</p>

</div>
</div>

### getBestState() {#a7db3cda88846a13412374a1060e7dd79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::IntegerRangeState::getBestState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/integerrangestate">IntegerRangeState</a> &amp; IRS)</td>
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



<p>Definition at line 2967 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#afd6cabd61fdf0fdf8c0b1adf560e032b">getBestState</a>, <a href="#ac96a74a0334b982914fcebf7720a98b9">getBitWidth</a> and <a href="#a642798e1c0646dd4dee731ad3b1525be">IntegerRangeState</a>.</p>

</div>
</div>

### getWorstState() {#ade656897ef13aaa480677e37a4fcfa43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::IntegerRangeState::getWorstState (uint32_t BitWidth)</td>
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

<p>Return the worst possible representable state.</p>

<p>Definition at line 2959 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a7ee8dff1bd0a385be9d9679112abd6a9">BitWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#aa5a45de2ff151caaae105b2aa429f35b">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getConstantRangeFromLVI</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#aa917f47e75cf32ee8a1abf71f2ebde01">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getConstantRangeFromSCEV</a> and <a href="#a5a96611f0657001f1ac807026a1ed79f">IntegerRangeState</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
