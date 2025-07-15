---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/aa/pointerinfo/state
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `State` Struct Reference

<p>A type to track pointer/struct usage and accesses for <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo">AAPointerInfo</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct AA::PointerInfo::State { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4409ccb452d9104fe636a4dac6c11007">State</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a661847278eab89db1d26527d9d1c859f">State</a> (State &amp;&amp;SIS)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/aa/pointerinfo/state">State</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0773518a860640b39e49b03915e0abd">operator=</a> (const State &amp;R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/aa/pointerinfo/state">State</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a2dcabbd815ade9dbb178a1500c5ac1">operator=</a> (State &amp;&amp;R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state">State</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4c99e28f5b3b00f99ca68170761c070">getAssumed</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afff19c78fad092351f89268d421648a8">isValidState</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#ae2b42216b30b52bbb803df6884ef34d2">AbstractState::isValidState()</a>. <a href="#afff19c78fad092351f89268d421648a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4dc308f1ac1ba6ae0db991893690e46">isAtFixpoint</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#adab11027e1a9fdc4c600bb8dba1df413">AbstractState::isAtFixpoint()</a>. <a href="#ac4dc308f1ac1ba6ae0db991893690e46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee95b495b33c21b58954d20575a343a3">indicateOptimisticFixpoint</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#aeafeaa2dc5ca5ca15830d8fa0b8762d2">AbstractState::indicateOptimisticFixpoint()</a>. <a href="#aee95b495b33c21b58954d20575a343a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3f647a9e57c2939aedc4e2d8ea63198">indicatePessimisticFixpoint</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#ac61c038186769d32f4f8c10168367965">AbstractState::indicatePessimisticFixpoint()</a>. <a href="#af3f647a9e57c2939aedc4e2d8ea63198">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec6e46ec669f364d2396241b5b7b2ae">addAccess</a> (Attributor &amp;A, const AAPointerInfo::RangeList &amp;Ranges, Instruction &amp;I, std::optional&lt; Value * &gt; Content, AAPointerInfo::AccessKind Kind, Type *Ty, Instruction *RemoteI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new Access to the state at offset <span class="doxyComputerOutput">Offset</span> and with size <span class="doxyComputerOutput">Size</span>. <a href="#a0ec6e46ec669f364d2396241b5b7b2ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a3e84a44b3b77bd1e127e7eca539393d7">AAPointerInfo::const_bin_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b0bbaaccb617ae4da3a16175ecabcbf">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a3e84a44b3b77bd1e127e7eca539393d7">AAPointerInfo::const_bin_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04da06409f830f9417dc4d871b6c27e0">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad33443715510726cc6183acd1346bf85">numOffsetBins</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access">AAPointerInfo::Access</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67d01f4b0a7738d6a431df49133f2221">getAccess</a> (unsigned Index) const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename F&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0100a0bf4251ceebee66a03626dcb39b">forallInterferingAccesses</a> (AA::RangeTy Range, F CB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a7e074b029fa7e785f9836fdc15ef50e2">AAPointerInfo::forallInterferingAccesses</a>. <a href="#a0100a0bf4251ceebee66a03626dcb39b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename F&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac64c9ad13e64797a22ad540e9e4123d0">forallInterferingAccesses</a> (Instruction &amp;I, F CB, AA::RangeTy &amp;Range) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a7e074b029fa7e785f9836fdc15ef50e2">AAPointerInfo::forallInterferingAccesses</a>. <a href="#ac64c9ad13e64797a22ad540e9e4123d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access">AAPointerInfo::Access</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd4dff7c985b2b43b438b72f3a76bfa3">AccessList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a6bd5350ba0828a918b5459f90ac037c4">AAPointerInfo::OffsetBinsTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1f4ae274080b8f536b012494768a714">OffsetBins</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f95c58e4dfb9965e55d8f8f02bfe729">RemoteIMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/offsetinfo">AAPointerInfo::OffsetInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aeb8276fb7bbfcb10a9a365d4a82453">ReturnedOffsets</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to determine if the underlying pointer is reaching a return statement in the associated function or not. <a href="#a2aeb8276fb7bbfcb10a9a365d4a82453">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/booleanstate">BooleanState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a44c43af199f9acf0174f39e850f96f">BS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State to track fixpoint and validity. <a href="#a1a44c43af199f9acf0174f39e850f96f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state">State</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7edcdaf5c527237ef65fec8f4a0b73c">getBestState</a> (const State &amp;SIS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the best possible representable state. <a href="#af7edcdaf5c527237ef65fec8f4a0b73c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state">State</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceaf80dc02170410a5639ab9e2fd3971">getWorstState</a> (const State &amp;SIS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the worst possible representable state. <a href="#aceaf80dc02170410a5639ab9e2fd3971">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A type to track pointer/struct usage and accesses for <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo">AAPointerInfo</a>.</p>

<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### State() {#a4409ccb452d9104fe636a4dac6c11007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AA::PointerInfo::State::State ()</td>
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



<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="#af4c99e28f5b3b00f99ca68170761c070">llvm::AA::PointerInfo::State::getAssumed</a>, <a href="#af7edcdaf5c527237ef65fec8f4a0b73c">llvm::AA::PointerInfo::State::getBestState</a>, <a href="#aceaf80dc02170410a5639ab9e2fd3971">llvm::AA::PointerInfo::State::getWorstState</a>, <a href="#af0773518a860640b39e49b03915e0abd">llvm::AA::PointerInfo::State::operator=</a>, <a href="#a4a2dcabbd815ade9dbb178a1500c5ac1">llvm::AA::PointerInfo::State::operator=</a>, <a href="#a661847278eab89db1d26527d9d1c859f">llvm::AA::PointerInfo::State::State</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#afa9d4327193a1cc24ab70233ec67af82">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddState</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a42a2b649b3ebe7e9cf882d260685c9d0">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddStateFromCallee</a>.</p>

</div>
</div>

### State() {#a661847278eab89db1d26527d9d1c859f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AA::PointerInfo::State::State (<a href="/web-llvm/docs/api/structs/aa/pointerinfo/state">State</a> &amp;&amp; SIS)</td>
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



<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="#a4409ccb452d9104fe636a4dac6c11007">llvm::AA::PointerInfo::State::State</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#af0773518a860640b39e49b03915e0abd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">State &amp; llvm::AA::PointerInfo::State::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state">State</a> &amp; R)</td>
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



<p>Definition at line 822 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="#abd4dff7c985b2b43b438b72f3a76bfa3">llvm::AA::PointerInfo::State::AccessList</a>, <a href="#ae1f4ae274080b8f536b012494768a714">llvm::AA::PointerInfo::State::OffsetBins</a>, <a href="#a0f95c58e4dfb9965e55d8f8f02bfe729">llvm::AA::PointerInfo::State::RemoteIMap</a>, <a href="#a2aeb8276fb7bbfcb10a9a365d4a82453">llvm::AA::PointerInfo::State::ReturnedOffsets</a> and <a href="#a4409ccb452d9104fe636a4dac6c11007">llvm::AA::PointerInfo::State::State</a>.</p>

</div>
</div>

### operator=() {#a4a2dcabbd815ade9dbb178a1500c5ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">State &amp; llvm::AA::PointerInfo::State::operator= (<a href="/web-llvm/docs/api/structs/aa/pointerinfo/state">State</a> &amp;&amp; R)</td>
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



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="#abd4dff7c985b2b43b438b72f3a76bfa3">llvm::AA::PointerInfo::State::AccessList</a>, <a href="#ae1f4ae274080b8f536b012494768a714">llvm::AA::PointerInfo::State::OffsetBins</a>, <a href="#a0f95c58e4dfb9965e55d8f8f02bfe729">llvm::AA::PointerInfo::State::RemoteIMap</a>, <a href="#a2aeb8276fb7bbfcb10a9a365d4a82453">llvm::AA::PointerInfo::State::ReturnedOffsets</a>, <a href="#a4409ccb452d9104fe636a4dac6c11007">llvm::AA::PointerInfo::State::State</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAccess() {#a0ec6e46ec669f364d2396241b5b7b2ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus llvm::AA::PointerInfo::State::addAccess (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/rangelist">AAPointerInfo::RangeList</a> &amp; Ranges, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Content, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a78c4e7148167329c362738ab01ebdda1">AAPointerInfo::AccessKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * RemoteI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a new Access to the state at offset <span class="doxyComputerOutput">Offset</span> and with size <span class="doxyComputerOutput">Size</span>.</p>


<p>The access is associated with <span class="doxyComputerOutput">I</span>, writes <span class="doxyComputerOutput">Content</span> (if anything), and is of kind <span class="doxyComputerOutput">Kind</span>. If an Access already exists for the same <span class="doxyComputerOutput">I</span> and same <span class="doxyComputerOutput">RemoteI</span>, the two are combined, potentially losing information about offset and size. The resulting access must now be moved from its original OffsetBin to the bin for its new offset.</p>


<p>\Returns CHANGED, if the state changed, UNCHANGED otherwise.</p>


<p>Definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#abd4dff7c985b2b43b438b72f3a76bfa3">llvm::AA::PointerInfo::State::AccessList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da807dbe7d1c25a633894d4a231b1c76d3">llvm::Bin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ae1f4ae274080b8f536b012494768a714">llvm::AA::PointerInfo::State::OffsetBins</a>, <a href="#a0f95c58e4dfb9965e55d8f8f02bfe729">llvm::AA::PointerInfo::State::RemoteIMap</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/rangelist/#ac1944e462953413d1cac710fc359c1cb">llvm::AAPointerInfo::RangeList::set_difference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a272cd16957d147ad113779617eeabf77">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::handleAccess</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#afa9d4327193a1cc24ab70233ec67af82">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddState</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a42a2b649b3ebe7e9cf882d260685c9d0">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddStateFromCallee</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a>.</p>

</div>
</div>

### begin() {#a1b0bbaaccb617ae4da3a16175ecabcbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAPointerInfo::const_bin_iterator llvm::AA::PointerInfo::State::begin ()</td>
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



<p>Definition at line 857 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="#ae1f4ae274080b8f536b012494768a714">llvm::AA::PointerInfo::State::OffsetBins</a>.</p>

</div>
</div>

### end() {#a04da06409f830f9417dc4d871b6c27e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAPointerInfo::const_bin_iterator llvm::AA::PointerInfo::State::end ()</td>
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



<p>Definition at line 858 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="#ae1f4ae274080b8f536b012494768a714">llvm::AA::PointerInfo::State::OffsetBins</a>.</p>

</div>
</div>

### getAccess() {#a67d01f4b0a7738d6a431df49133f2221}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AAPointerInfo::Access &amp; llvm::AA::PointerInfo::State::getAccess (unsigned Index)</td>
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



<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="#abd4dff7c985b2b43b438b72f3a76bfa3">llvm::AA::PointerInfo::State::AccessList</a>.</p>

</div>
</div>

### getAssumed() {#af4c99e28f5b3b00f99ca68170761c070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const State &amp; llvm::AA::PointerInfo::State::getAssumed ()</td>
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



<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="#a4409ccb452d9104fe636a4dac6c11007">llvm::AA::PointerInfo::State::State</a>.</p>

</div>
</div>

### indicateOptimisticFixpoint() {#aee95b495b33c21b58954d20575a343a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus llvm::AA::PointerInfo::State::indicateOptimisticFixpoint ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#aeafeaa2dc5ca5ca15830d8fa0b8762d2">AbstractState::indicateOptimisticFixpoint()</a>.</p>

<p>Definition at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a>.</p>

</div>
</div>

### indicatePessimisticFixpoint() {#af3f647a9e57c2939aedc4e2d8ea63198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus llvm::AA::PointerInfo::State::indicatePessimisticFixpoint ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#ac61c038186769d32f4f8c10168367965">AbstractState::indicatePessimisticFixpoint()</a>.</p>

<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#afa9d4327193a1cc24ab70233ec67af82">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddState</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a42a2b649b3ebe7e9cf882d260685c9d0">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddStateFromCallee</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinforeturned/#aecb3013f4d454c72ccc12a53ced497a7">anonymous{AttributorAttributes.cpp}::AAPointerInfoReturned::updateImpl</a>.</p>

</div>
</div>

### isAtFixpoint() {#ac4dc308f1ac1ba6ae0db991893690e46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::PointerInfo::State::isAtFixpoint ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#adab11027e1a9fdc4c600bb8dba1df413">AbstractState::isAtFixpoint()</a>.</p>

<p>Definition at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>

</div>
</div>

### isValidState() {#afff19c78fad092351f89268d421648a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::PointerInfo::State::isValidState ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#ae2b42216b30b52bbb803df6884ef34d2">AbstractState::isValidState()</a>.</p>

<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="#a0100a0bf4251ceebee66a03626dcb39b">llvm::AA::PointerInfo::State::forallInterferingAccesses</a>, <a href="#ac64c9ad13e64797a22ad540e9e4123d0">llvm::AA::PointerInfo::State::forallInterferingAccesses</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#ac68524c8b473cee1070608f7acc9e734">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#afa9d4327193a1cc24ab70233ec67af82">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddState</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a42a2b649b3ebe7e9cf882d260685c9d0">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddStateFromCallee</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>.</p>

</div>
</div>

### numOffsetBins() {#ad33443715510726cc6183acd1346bf85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AA::PointerInfo::State::numOffsetBins ()</td>
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



<p>Definition at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="#ae1f4ae274080b8f536b012494768a714">llvm::AA::PointerInfo::State::OffsetBins</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### forallInterferingAccesses() {#a0100a0bf4251ceebee66a03626dcb39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename F&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::PointerInfo::State::forallInterferingAccesses (<a href="/web-llvm/docs/api/structs/llvm/aa/rangety">AA::RangeTy</a> Range, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> CB)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a7e074b029fa7e785f9836fdc15ef50e2">AAPointerInfo::forallInterferingAccesses</a>.</p>

<p>Definition at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#adb4fa2b9065093d32736f78ea43a8c8a">Access</a>, <a href="#abd4dff7c985b2b43b438b72f3a76bfa3">llvm::AA::PointerInfo::State::AccessList</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#afff19c78fad092351f89268d421648a8">llvm::AA::PointerInfo::State::isValidState</a>, <a href="#ae1f4ae274080b8f536b012494768a714">llvm::AA::PointerInfo::State::OffsetBins</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#a2aeb8276fb7bbfcb10a9a365d4a82453">llvm::AA::PointerInfo::State::ReturnedOffsets</a>.</p>


<p>Referenced by <a href="#ac64c9ad13e64797a22ad540e9e4123d0">llvm::AA::PointerInfo::State::forallInterferingAccesses</a>.</p>

</div>
</div>

### forallInterferingAccesses() {#ac64c9ad13e64797a22ad540e9e4123d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename F&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::PointerInfo::State::forallInterferingAccesses (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> CB, <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">AA::RangeTy</a> &amp; Range)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a7e074b029fa7e785f9836fdc15ef50e2">AAPointerInfo::forallInterferingAccesses</a>.</p>

<p>Definition at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="#abd4dff7c985b2b43b438b72f3a76bfa3">llvm::AA::PointerInfo::State::AccessList</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a0100a0bf4251ceebee66a03626dcb39b">llvm::AA::PointerInfo::State::forallInterferingAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#afff19c78fad092351f89268d421648a8">llvm::AA::PointerInfo::State::isValidState</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="#a0f95c58e4dfb9965e55d8f8f02bfe729">llvm::AA::PointerInfo::State::RemoteIMap</a> and <a href="#a2aeb8276fb7bbfcb10a9a365d4a82453">llvm::AA::PointerInfo::State::ReturnedOffsets</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AccessList {#abd4dff7c985b2b43b438b72f3a76bfa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AAPointerInfo::Access&gt; llvm::AA::PointerInfo::State::AccessList</td>
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



<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="#a0ec6e46ec669f364d2396241b5b7b2ae">llvm::AA::PointerInfo::State::addAccess</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#ae7fe4af569d52ef24a1d0625131e8399">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::dumpState</a>, <a href="#a0100a0bf4251ceebee66a03626dcb39b">llvm::AA::PointerInfo::State::forallInterferingAccesses</a>, <a href="#ac64c9ad13e64797a22ad540e9e4123d0">llvm::AA::PointerInfo::State::forallInterferingAccesses</a>, <a href="#a67d01f4b0a7738d6a431df49133f2221">llvm::AA::PointerInfo::State::getAccess</a>, <a href="#af0773518a860640b39e49b03915e0abd">llvm::AA::PointerInfo::State::operator=</a> and <a href="#a4a2dcabbd815ade9dbb178a1500c5ac1">llvm::AA::PointerInfo::State::operator=</a>.</p>

</div>
</div>

### OffsetBins {#ae1f4ae274080b8f536b012494768a714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAPointerInfo::OffsetBinsTy llvm::AA::PointerInfo::State::OffsetBins</td>
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



<p>Definition at line 879 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="#a0ec6e46ec669f364d2396241b5b7b2ae">llvm::AA::PointerInfo::State::addAccess</a>, <a href="#a1b0bbaaccb617ae4da3a16175ecabcbf">llvm::AA::PointerInfo::State::begin</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#ae7fe4af569d52ef24a1d0625131e8399">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::dumpState</a>, <a href="#a04da06409f830f9417dc4d871b6c27e0">llvm::AA::PointerInfo::State::end</a>, <a href="#a0100a0bf4251ceebee66a03626dcb39b">llvm::AA::PointerInfo::State::forallInterferingAccesses</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#ac68524c8b473cee1070608f7acc9e734">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::getAsStr</a>, <a href="#ad33443715510726cc6183acd1346bf85">llvm::AA::PointerInfo::State::numOffsetBins</a>, <a href="#af0773518a860640b39e49b03915e0abd">llvm::AA::PointerInfo::State::operator=</a> and <a href="#a4a2dcabbd815ade9dbb178a1500c5ac1">llvm::AA::PointerInfo::State::operator=</a>.</p>

</div>
</div>

### RemoteIMap {#a0f95c58e4dfb9965e55d8f8f02bfe729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Instruction *, SmallVector&lt;unsigned&gt; &gt; llvm::AA::PointerInfo::State::RemoteIMap</td>
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



<p>Definition at line 880 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="#a0ec6e46ec669f364d2396241b5b7b2ae">llvm::AA::PointerInfo::State::addAccess</a>, <a href="#ac64c9ad13e64797a22ad540e9e4123d0">llvm::AA::PointerInfo::State::forallInterferingAccesses</a>, <a href="#af0773518a860640b39e49b03915e0abd">llvm::AA::PointerInfo::State::operator=</a> and <a href="#a4a2dcabbd815ade9dbb178a1500c5ac1">llvm::AA::PointerInfo::State::operator=</a>.</p>

</div>
</div>

### ReturnedOffsets {#a2aeb8276fb7bbfcb10a9a365d4a82453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAPointerInfo::OffsetInfo llvm::AA::PointerInfo::State::ReturnedOffsets</td>
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

<p>Flag to determine if the underlying pointer is reaching a return statement in the associated function or not.</p>


<p>Returns in other functions cause invalidation.</p>


<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a6f3f47474554552391f037aeef54188b">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::addReturnedOffsetsTo</a>, <a href="#a0100a0bf4251ceebee66a03626dcb39b">llvm::AA::PointerInfo::State::forallInterferingAccesses</a>, <a href="#ac64c9ad13e64797a22ad540e9e4123d0">llvm::AA::PointerInfo::State::forallInterferingAccesses</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#ac68524c8b473cee1070608f7acc9e734">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::getAsStr</a>, <a href="#af0773518a860640b39e49b03915e0abd">llvm::AA::PointerInfo::State::operator=</a>, <a href="#a4a2dcabbd815ade9dbb178a1500c5ac1">llvm::AA::PointerInfo::State::operator=</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a9f7244f70e9a8a6ef17d06c186559288">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::reachesReturn</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a8836ddf956860b822d6b09d0040ca748">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::setReachesReturn</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BS {#a1a44c43af199f9acf0174f39e850f96f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BooleanState llvm::AA::PointerInfo::State::BS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>State to track fixpoint and validity.</p>

<p>Definition at line 931 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getBestState() {#af7edcdaf5c527237ef65fec8f4a0b73c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">State llvm::AA::PointerInfo::State::getBestState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state">State</a> &amp; SIS)</td>
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

<p>Definition at line 790 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="#a4409ccb452d9104fe636a4dac6c11007">llvm::AA::PointerInfo::State::State</a>.</p>

</div>
</div>

### getWorstState() {#aceaf80dc02170410a5639ab9e2fd3971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">State llvm::AA::PointerInfo::State::getWorstState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state">State</a> &amp; SIS)</td>
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

<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="#a4409ccb452d9104fe636a4dac6c11007">llvm::AA::PointerInfo::State::State</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
