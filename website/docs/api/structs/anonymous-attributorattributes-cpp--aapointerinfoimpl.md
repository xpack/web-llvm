---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AAPointerInfoImpl` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl { ... }
</div>

## Base struct

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

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating">AAPointerInfoFloating</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinforeturned">AAPointerInfoReturned</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac520a32677ab774ffa2d4a750b96961e">BaseTy</a> = <a href="/web-llvm/docs/api/structs/llvm/statewrapper">StateWrapper</a>&lt; <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state">AA::PointerInfo::State</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo">AAPointerInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dbb3355d0d483076a38ccd5c40d6b48">AAPointerInfoImpl</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac68524c8b473cee1070608f7acc9e734">getAsStr</a> (Attributor *A) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#ab46cf8c2872fdda027ddc8691afbf498">AbstractAttribute::getAsStr()</a>. <a href="#ac68524c8b473cee1070608f7acc9e734">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73b8ded2cc1e73a9eb1a597c77225d63">manifest</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::manifest(...). <a href="#a73b8ded2cc1e73a9eb1a597c77225d63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a3e84a44b3b77bd1e127e7eca539393d7">const_bin_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f57ed9ffd77d096f310c2c9e7c3fa3">begin</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a3e84a44b3b77bd1e127e7eca539393d7">const_bin_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b7935321d6e009be71a179169040110">end</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adda6ce3818117e459c8af41c2f42e721">numOffsetBins</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f7244f70e9a8a6ef17d06c186559288">reachesReturn</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f3f47474554552391f037aeef54188b">addReturnedOffsetsTo</a> (OffsetInfo &amp;OI) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8836ddf956860b822d6b09d0040ca748">setReachesReturn</a> (const OffsetInfo &amp;ReachedReturnedOffsets)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad90250ec1845a63324ddae4635adea1">forallInterferingAccesses</a> (AA::RangeTy Range, function_ref&lt; bool(const AAPointerInfo::Access &amp;, bool)&gt; CB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call <span class="doxyComputerOutput">CB</span> on all accesses that might interfere with <span class="doxyComputerOutput">Range</span> and return true if all such accesses were known and the callback returned true for all of them, false otherwise. <a href="#aad90250ec1845a63324ddae4635adea1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dcc7e60c55b76d16688ee3b04f804e4">forallInterferingAccesses</a> (Attributor &amp;A, const AbstractAttribute &amp;QueryingAA, Instruction &amp;I, bool FindInterferingWrites, bool FindInterferingReads, function_ref&lt; bool(const Access &amp;, bool)&gt; UserCB, bool &amp;HasBeenWrittenTo, AA::RangeTy &amp;Range, function_ref&lt; bool(const Access &amp;)&gt; SkipCB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call <span class="doxyComputerOutput">CB</span> on all accesses that might interfere with <span class="doxyComputerOutput">I</span> and return true if all such accesses were known and the callback returned true for all of them, false otherwise. <a href="#a7dcc7e60c55b76d16688ee3b04f804e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42a2b649b3ebe7e9cf882d260685c9d0">translateAndAddStateFromCallee</a> (Attributor &amp;A, const AAPointerInfo &amp;OtherAA, CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa9d4327193a1cc24ab70233ec67af82">translateAndAddState</a> (Attributor &amp;A, const AAPointerInfo &amp;OtherAA, const OffsetInfo &amp;Offsets, CallBase &amp;CB, bool IsMustAcc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0498acb1ad958b0a7392d1c8f12a36f7">trackPointerInfoStatistics</a> (const IRPosition &amp;IRP) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/#a6412c3ea6550f1aeab7571b6d38a2bf3">Statistic</a> tracking for all AAPointerInfo implementations. <a href="#a0498acb1ad958b0a7392d1c8f12a36f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7fe4af569d52ef24a1d0625131e8399">dumpState</a> (raw_ostream &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the state into <span class="doxyComputerOutput">O</span>. <a href="#ae7fe4af569d52ef24a1d0625131e8399">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 1023 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BaseTy {#ac520a32677ab774ffa2d4a750b96961e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::BaseTy =  StateWrapper&lt;AA::PointerInfo::State, AAPointerInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1025 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AAPointerInfoImpl() {#a1dbb3355d0d483076a38ccd5c40d6b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::AAPointerInfoImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 1026 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#ad54405549dff78b4d8bc7ea1d04873e0">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::AAPointerInfoFloating</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinforeturned/#ae974aa194a89562209394ed2478e797a">anonymous{AttributorAttributes.cpp}::AAPointerInfoReturned::AAPointerInfoReturned</a>, <a href="#afa9d4327193a1cc24ab70233ec67af82">translateAndAddState</a> and <a href="#a42a2b649b3ebe7e9cf882d260685c9d0">translateAndAddStateFromCallee</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addReturnedOffsetsTo() {#a6f3f47474554552391f037aeef54188b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::addReturnedOffsetsTo (<a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/offsetinfo">OffsetInfo</a> &amp; OI)</td>
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



<p>Definition at line 1056 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/offsetinfo/#afc62d5cbad359ff2a03b831053c470ec">llvm::AAPointerInfo::OffsetInfo::addToAll</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/offsetinfo/#af3981da39f7d4904f07fa2c456a06448">llvm::AAPointerInfo::OffsetInfo::merge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#a2aeb8276fb7bbfcb10a9a365d4a82453">llvm::AA::PointerInfo::State::ReturnedOffsets</a> and <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/offsetinfo/#a0ffc9e3ce7217e6b65ccb47a5acb0f02">llvm::AAPointerInfo::OffsetInfo::setUnknown</a>.</p>

</div>
</div>

### begin() {#ab0f57ed9ffd77d096f310c2c9e7c3fa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const_bin_iterator anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::begin ()</td>
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



<p>Definition at line 1048 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>

</div>
</div>

### dumpState() {#ae7fe4af569d52ef24a1d0625131e8399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::dumpState (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Dump the state into <span class="doxyComputerOutput">O</span>.</p>

<p>Definition at line 1435 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#abd4dff7c985b2b43b438b72f3a76bfa3">llvm::AA::PointerInfo::State::AccessList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a> and <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#ae1f4ae274080b8f536b012494768a714">llvm::AA::PointerInfo::State::OffsetBins</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>.</p>

</div>
</div>

### end() {#a1b7935321d6e009be71a179169040110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const_bin_iterator anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::end ()</td>
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



<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>

</div>
</div>

### forallInterferingAccesses() {#aad90250ec1845a63324ddae4635adea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::forallInterferingAccesses (<a href="/web-llvm/docs/api/structs/llvm/aa/rangety">AA::RangeTy</a> Range, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access">AAPointerInfo::Access</a> &amp;, bool)&gt; CB)</td>
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

<p>Call <span class="doxyComputerOutput">CB</span> on all accesses that might interfere with <span class="doxyComputerOutput">Range</span> and return true if all such accesses were known and the callback returned true for all of them, false otherwise.</p>


<p>An access interferes with an offset-size pair if it might read or write that memory region.</p>


<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### forallInterferingAccesses() {#a7dcc7e60c55b76d16688ee3b04f804e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::forallInterferingAccesses (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, bool FindInterferingWrites, bool FindInterferingReads, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access">Access</a> &amp;, bool)&gt; CB, bool &amp; HasBeenWrittenTo, <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">AA::RangeTy</a> &amp; Range, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access">Access</a> &amp;)&gt; SkipCB)</td>
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

<p>Call <span class="doxyComputerOutput">CB</span> on all accesses that might interfere with <span class="doxyComputerOutput">I</span> and return true if all such accesses were known and the callback returned true for all of them, false otherwise.</p>


<p>In contrast to forallInterferingAccesses this function will perform reasoning to exclude write accesses that cannot affect the load even if they on the surface look as if they would. The flag <span class="doxyComputerOutput">HasBeenWrittenTo</span> will be set to true if we know that <span class="doxyComputerOutput">I</span> does not read the initial value of the underlying memory. If <span class="doxyComputerOutput">SkipCB</span> is given and returns false for a potentially interfering access, that access is not checked for actual interference.</p>


<p>Definition at line 1090 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#acff34214cf426db8b010a1d977bd2899">llvm::AbstractAttribute::AbstractAttribute</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a0ab72bc360a96141393d6ff9f1af7511acb17869fe51048b5a5c4c6106551a255">llvm::AA::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a11045c7973ab24a8d6315b61fa337d4e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::erase</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a8936a7eb7c9151c46513b192053afb2e">llvm::IRPosition::function</a>, <a href="/web-llvm/docs/api/structs/llvm/informationcache/#af887d734d176f82b42528b55c0bdc4f7">llvm::InformationCache::getAnalysisResultForFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a8743c58384e11cb6228f6f871304ad35">llvm::Function::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access/#ae6aa86dd515ac8bbc7071107bc171ffa">llvm::AAPointerInfo::Access::getRemoteInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ae8abeaeed2f11072b2d064fe70510e9f">llvm::AA::hasAssumedIRAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a1f2a3f39b7febd40285065a7ed05b71d">llvm::AA::isAssumedThreadLocalObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#aba7baf8e2e8dff3bb7152c6ffeb52fb8">llvm::AA::isGPU</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access/#afc20b28fcb9827e4012ff0b844958b78">llvm::AAPointerInfo::Access::isMustAccess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#adc52b79e64dcac96ea901cbfab1ccc52">llvm::AA::isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access/#a98ea1d651bed48c5b634d128476a4d9b">llvm::AAPointerInfo::Access::isRead</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access/#a990a1e9160da29d9eec8b016b01d4a13">llvm::AAPointerInfo::Access::isWrite</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access/#a9718c2b67dd987b9cf987a7f18321a06">llvm::AAPointerInfo::Access::isWriteOrAssumption</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a0ab72bc360a96141393d6ff9f1af7511a509820290d57f333403f490dde7316f4">llvm::AA::Local</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1ab50339a10e1de285ac99d4c3990b8693">llvm::NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a0ab72bc360a96141393d6ff9f1af7511aa6156ea9d66fef24e87e841fbabf7cca">llvm::AA::Shared</a>.</p>

</div>
</div>

### getAsStr() {#ac68524c8b473cee1070608f7acc9e734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::getAsStr (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> * A)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#ab46cf8c2872fdda027ddc8691afbf498">AbstractAttribute::getAsStr()</a>.</p>

<p>Definition at line 1029 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#afff19c78fad092351f89268d421648a8">llvm::AA::PointerInfo::State::isValidState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51c7cbd21e1104ee6841c18d7daa6edb">llvm::map_range</a>, <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#ae1f4ae274080b8f536b012494768a714">llvm::AA::PointerInfo::State::OffsetBins</a>, <a href="#a9f7244f70e9a8a6ef17d06c186559288">reachesReturn</a> and <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#a2aeb8276fb7bbfcb10a9a365d4a82453">llvm::AA::PointerInfo::State::ReturnedOffsets</a>.</p>

</div>
</div>

### manifest() {#a73b8ded2cc1e73a9eb1a597c77225d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::manifest (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See AbstractAttribute::manifest(...).</p>

<p>Definition at line 1044 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a> and <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a1405b111f812f19e71bbe4286484ef54">llvm::AbstractAttribute::manifest</a>.</p>

</div>
</div>

### numOffsetBins() {#adda6ce3818117e459c8af41c2f42e721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int64_t anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::numOffsetBins ()</td>
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



<p>Definition at line 1050 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>

</div>
</div>

### reachesReturn() {#a9f7244f70e9a8a6ef17d06c186559288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::reachesReturn ()</td>
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



<p>Definition at line 1053 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#a2aeb8276fb7bbfcb10a9a365d4a82453">llvm::AA::PointerInfo::State::ReturnedOffsets</a>.</p>


<p>Referenced by <a href="#ac68524c8b473cee1070608f7acc9e734">getAsStr</a>.</p>

</div>
</div>

### setReachesReturn() {#a8836ddf956860b822d6b09d0040ca748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::setReachesReturn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/offsetinfo">OffsetInfo</a> &amp; ReachedReturnedOffsets)</td>
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



<p>Definition at line 1071 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/offsetinfo/#a84931776d6bfa263f9066657ec3ccc0e">llvm::AAPointerInfo::OffsetInfo::isUnknown</a>, <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#a2aeb8276fb7bbfcb10a9a365d4a82453">llvm::AA::PointerInfo::State::ReturnedOffsets</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a>.</p>


<p>Referenced by <a href="#a42a2b649b3ebe7e9cf882d260685c9d0">translateAndAddStateFromCallee</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>.</p>

</div>
</div>

### trackPointerInfoStatistics() {#a0498acb1ad958b0a7392d1c8f12a36f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::trackPointerInfoStatistics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/#a6412c3ea6550f1aeab7571b6d38a2bf3">Statistic</a> tracking for all AAPointerInfo implementations.</p>


<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#add85e4d78cefc67429904d7492aff9a4">AbstractAttribute::trackStatistics()</a>.</p>


<p>Definition at line 1432 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoargument/#a0c27d9b0faab709fc39e83d6897b14a1">anonymous{AttributorAttributes.cpp}::AAPointerInfoArgument::trackStatistics</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#acbd7ad8085dd201c1e5e80431005af87">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::trackStatistics</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsitereturned/#ab0914a4c3d0c98c8e035c4ab68772bd9">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteReturned::trackStatistics</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#ac6a9182fd16581de19c12e81c8d430dc">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::trackStatistics</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinforeturned/#ac2e16438e57e29aacb671589fc58555e">anonymous{AttributorAttributes.cpp}::AAPointerInfoReturned::trackStatistics</a>.</p>

</div>
</div>

### translateAndAddState() {#afa9d4327193a1cc24ab70233ec67af82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddState (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo">AAPointerInfo</a> &amp; OtherAA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/offsetinfo">OffsetInfo</a> &amp; Offsets, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, bool IsMustAcc)</td>
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



<p>Definition at line 1395 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#ad1d0686143c13ac3502bf10cd9e32aad">llvm::AAPointerInfo::AAPointerInfo</a>, <a href="#a1dbb3355d0d483076a38ccd5c40d6b48">AAPointerInfoImpl</a>, <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#a0ec6e46ec669f364d2396241b5b7b2ae">llvm::AA::PointerInfo::State::addAccess</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a78c4e7148167329c362738ab01ebdda1a1e154051f64c29dc28598977dc56ae92">llvm::AAPointerInfo::AK_MAY</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a78c4e7148167329c362738ab01ebdda1a54020ed18b5ad8c231c81baa173aad83">llvm::AAPointerInfo::AK_MUST</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a5f3c26aaee1ca991435953c032b3fd08">llvm::AbstractAttribute::getState</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/aa/rangety/#a7a2f37da6d4fb687896f10c0877386d5">llvm::AA::RangeTy::getUnknown</a>, <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#af3f647a9e57c2939aedc4e2d8ea63198">llvm::AA::PointerInfo::State::indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#afff19c78fad092351f89268d421648a8">llvm::AA::PointerInfo::State::isValidState</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#ae2b42216b30b52bbb803df6884ef34d2">llvm::AbstractState::isValidState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#a4409ccb452d9104fe636a4dac6c11007">llvm::AA::PointerInfo::State::State</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a> and <a href="/web-llvm/docs/api/structs/llvm/aa/rangety/#a3a61943cb8a1b4b07da2b2edeb9cf51c">llvm::AA::RangeTy::Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>.</p>

</div>
</div>

### translateAndAddStateFromCallee() {#a42a2b649b3ebe7e9cf882d260685c9d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddStateFromCallee (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo">AAPointerInfo</a> &amp; OtherAA, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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



<p>Definition at line 1362 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#ad1d0686143c13ac3502bf10cd9e32aad">llvm::AAPointerInfo::AAPointerInfo</a>, <a href="#a1dbb3355d0d483076a38ccd5c40d6b48">AAPointerInfoImpl</a>, <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#a0ec6e46ec669f364d2396241b5b7b2ae">llvm::AA::PointerInfo::State::addAccess</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a78c4e7148167329c362738ab01ebdda1a1e154051f64c29dc28598977dc56ae92">llvm::AAPointerInfo::AK_MAY</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a78c4e7148167329c362738ab01ebdda1a54020ed18b5ad8c231c81baa173aad83">llvm::AAPointerInfo::AK_MUST</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a78c4e7148167329c362738ab01ebdda1a3dd50dec5233b17dc99e213fa2368431">llvm::AAPointerInfo::AK_R</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a78c4e7148167329c362738ab01ebdda1addc8a1504a2cac4a232e96beafb0bd5e">llvm::AAPointerInfo::AK_RW</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a5f3c26aaee1ca991435953c032b3fd08">llvm::AbstractAttribute::getState</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#af3f647a9e57c2939aedc4e2d8ea63198">llvm::AA::PointerInfo::State::indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#afff19c78fad092351f89268d421648a8">llvm::AA::PointerInfo::State::isValidState</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#ae2b42216b30b52bbb803df6884ef34d2">llvm::AbstractState::isValidState</a>, <a href="#a8836ddf956860b822d6b09d0040ca748">setReachesReturn</a>, <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#a4409ccb452d9104fe636a4dac6c11007">llvm::AA::PointerInfo::State::State</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
