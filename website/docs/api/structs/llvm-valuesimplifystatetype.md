---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/valuesimplifystatetype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ValueSimplifyStateType` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::ValueSimplifyStateType { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ff04feb3c50d53847f4c9840284257">ValueSimplifyStateType</a> (Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype">ValueSimplifyStateType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4684c2c2e8fa2454ec809b41218b8de5">operator^=</a> (const ValueSimplifyStateType &amp;VS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>"Clamp" this state with <span class="doxyComputerOutput">PVS</span>. <a href="#a4684c2c2e8fa2454ec809b41218b8de5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad70b17ba782d01eb1f17633d14e0d033">operator==</a> (const ValueSimplifyStateType &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a6972b66fea1956156c533cc2e9e82">isValidState</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractState::isValidState(...) <a href="#aa7a6972b66fea1956156c533cc2e9e82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f4bca7ae5e76efbe268190a80a3c9d">isAtFixpoint</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractState::isAtFixpoint(...) <a href="#aa3f4bca7ae5e76efbe268190a80a3c9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype">ValueSimplifyStateType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af72827cb11e76b396318cceea0068d07">getAssumed</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the assumed state encoding. <a href="#af72827cb11e76b396318cceea0068d07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype">ValueSimplifyStateType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe4c0f9def243232420bd721f5413e5a">getAssumed</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a542727e23786c7a963cadd43c6d44473">indicatePessimisticFixpoint</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractState::indicatePessimisticFixpoint(...) <a href="#a542727e23786c7a963cadd43c6d44473">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ffae162336203495d2773c8418efc85">indicateOptimisticFixpoint</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractState::indicateOptimisticFixpoint(...) <a href="#a3ffae162336203495d2773c8418efc85">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b30794202b9b3042b5567a270ea8735">unionAssumed</a> (std::optional&lt; Value * &gt; Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge <span class="doxyComputerOutput">Other</span> into the currently assumed simplified value. <a href="#a3b30794202b9b3042b5567a270ea8735">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0e539b8f2629b0024a998d435822d48">Ty</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of the original value. <a href="#ad0e539b8f2629b0024a998d435822d48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/booleanstate">BooleanState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad02b27bc2a112bdc9e80820cbc5b0878">BS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to track validity and fixpoint. <a href="#ad02b27bc2a112bdc9e80820cbc5b0878">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabe3cb56f76e6a223406ba8fd571f5f4">SimplifiedAssociatedValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An assumed simplified value. <a href="#aabe3cb56f76e6a223406ba8fd571f5f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype">ValueSimplifyStateType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c2c9e9bbd67dc27f58a14c9f8866a7">getBestState</a> (Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype">ValueSimplifyStateType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e8d558c1b7761c15270982961d56be">getBestState</a> (const ValueSimplifyStateType &amp;VS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype">ValueSimplifyStateType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0447b63e9b31ebfb662abcf445e69065">getWorstState</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the worst possible representable state. <a href="#a0447b63e9b31ebfb662abcf445e69065">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype">ValueSimplifyStateType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac79cde1d3e1e4f98bcb81de733b443e">getWorstState</a> (const ValueSimplifyStateType &amp;VS)</td>
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


<p>Definition at line 4436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ValueSimplifyStateType() {#a59ff04feb3c50d53847f4c9840284257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueSimplifyStateType::ValueSimplifyStateType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 4438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#ad0e539b8f2629b0024a998d435822d48">Ty</a>.</p>


<p>Referenced by <a href="#af72827cb11e76b396318cceea0068d07">getAssumed</a>, <a href="#afe4c0f9def243232420bd721f5413e5a">getAssumed</a>, <a href="#a04e8d558c1b7761c15270982961d56be">getBestState</a>, <a href="#a84c2c9e9bbd67dc27f58a14c9f8866a7">getBestState</a>, <a href="#aac79cde1d3e1e4f98bcb81de733b443e">getWorstState</a>, <a href="#a0447b63e9b31ebfb662abcf445e69065">getWorstState</a>, <a href="#ad70b17ba782d01eb1f17633d14e0d033">operator==</a> and <a href="#a4684c2c2e8fa2454ec809b41218b8de5">operator^=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator^=() {#a4684c2c2e8fa2454ec809b41218b8de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueSimplifyStateType llvm::ValueSimplifyStateType::operator^= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype">ValueSimplifyStateType</a> &amp; VS)</td>
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

<p>"Clamp" this state with <span class="doxyComputerOutput">PVS</span>.</p>

<p>Definition at line 4479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#ad02b27bc2a112bdc9e80820cbc5b0878">BS</a>, <a href="#a3b30794202b9b3042b5567a270ea8735">unionAssumed</a> and <a href="#a59ff04feb3c50d53847f4c9840284257">ValueSimplifyStateType</a>.</p>

</div>
</div>

### operator==() {#ad70b17ba782d01eb1f17633d14e0d033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueSimplifyStateType::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype">ValueSimplifyStateType</a> &amp; RHS)</td>
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



<p>Definition at line 4485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#aa7a6972b66fea1956156c533cc2e9e82">isValidState</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aabe3cb56f76e6a223406ba8fd571f5f4">SimplifiedAssociatedValue</a> and <a href="#a59ff04feb3c50d53847f4c9840284257">ValueSimplifyStateType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAssumed() {#af72827cb11e76b396318cceea0068d07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueSimplifyStateType llvm::ValueSimplifyStateType::getAssumed ()</td>
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

<p>Definition at line 4465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a59ff04feb3c50d53847f4c9840284257">ValueSimplifyStateType</a>.</p>

</div>
</div>

### getAssumed() {#afe4c0f9def243232420bd721f5413e5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ValueSimplifyStateType &amp; llvm::ValueSimplifyStateType::getAssumed ()</td>
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



<p>Definition at line 4466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a59ff04feb3c50d53847f4c9840284257">ValueSimplifyStateType</a>.</p>

</div>
</div>

### indicateOptimisticFixpoint() {#a3ffae162336203495d2773c8418efc85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus llvm::ValueSimplifyStateType::indicateOptimisticFixpoint ()</td>
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

<p>Definition at line 4474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#ad02b27bc2a112bdc9e80820cbc5b0878">BS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsitereturned/#a249035cbf55468e38187c74bfcd1204b">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteReturned::initialize</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyfunction/#af68c191c5904e7c1b67393ba18ae722c">anonymous{AttributorAttributes.cpp}::AAValueSimplifyFunction::initialize</a>.</p>

</div>
</div>

### indicatePessimisticFixpoint() {#a542727e23786c7a963cadd43c6d44473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus llvm::ValueSimplifyStateType::indicatePessimisticFixpoint ()</td>
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

<p>Definition at line 4469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#ad02b27bc2a112bdc9e80820cbc5b0878">BS</a>.</p>

</div>
</div>

### isAtFixpoint() {#aa3f4bca7ae5e76efbe268190a80a3c9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueSimplifyStateType::isAtFixpoint ()</td>
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

<p>Definition at line 4462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#ad02b27bc2a112bdc9e80820cbc5b0878">BS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#af174738655489092808b152675c84311">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::getAsStr</a>.</p>

</div>
</div>

### isValidState() {#aa7a6972b66fea1956156c533cc2e9e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueSimplifyStateType::isValidState ()</td>
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

<p>Definition at line 4459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#ad02b27bc2a112bdc9e80820cbc5b0878">BS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#af174738655489092808b152675c84311">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyreturned/#a1bd851a4aaa71b142b2db5125d55c209">anonymous{AttributorAttributes.cpp}::AAValueSimplifyReturned::getAssumedSimplifiedValue</a> and <a href="#ad70b17ba782d01eb1f17633d14e0d033">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### unionAssumed() {#a3b30794202b9b3042b5567a270ea8735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ValueSimplifyStateType::unionAssumed (std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Other)</td>
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

<p>Merge <span class="doxyComputerOutput">Other</span> into the currently assumed simplified value.</p>


<p>---------------— <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> Simplify <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> -------------------------—</p>


<p>Declaration at line 4498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 6128 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a1e7aede47c97d1e610eeb8bdf152f4cc">llvm::AA::combineOptionalValuesInAAValueLatice</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#aabe3cb56f76e6a223406ba8fd571f5f4">SimplifiedAssociatedValue</a> and <a href="#ad0e539b8f2629b0024a998d435822d48">Ty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a9359926dcece9d9c26725b86829b4103">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::checkAndUpdate</a>, <a href="#a4684c2c2e8fa2454ec809b41218b8de5">operator^=</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BS {#ad02b27bc2a112bdc9e80820cbc5b0878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BooleanState llvm::ValueSimplifyStateType::BS</td>
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

<p>Helper to track validity and fixpoint.</p>

<p>Definition at line 4501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#a3ffae162336203495d2773c8418efc85">indicateOptimisticFixpoint</a>, <a href="#a542727e23786c7a963cadd43c6d44473">indicatePessimisticFixpoint</a>, <a href="#aa3f4bca7ae5e76efbe268190a80a3c9d">isAtFixpoint</a>, <a href="#aa7a6972b66fea1956156c533cc2e9e82">isValidState</a> and <a href="#a4684c2c2e8fa2454ec809b41218b8de5">operator^=</a>.</p>

</div>
</div>

### SimplifiedAssociatedValue {#aabe3cb56f76e6a223406ba8fd571f5f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Value *&gt; llvm::ValueSimplifyStateType::SimplifiedAssociatedValue</td>
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

<p>An assumed simplified value.</p>


<p>Initially, it is set to std::nullopt, which means that the value is not clear under current assumption. If in the pessimistic state, getAssumedSimplifiedValue doesn't return this value but returns orignal associated value.</p>


<p>Definition at line 4507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#ac74c71265c51cb1cd82cebadc0cfa913">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::askSimplifiedValueFor</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#af174738655489092808b152675c84311">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a8fbd14119f3e6248e220722b2e332942">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::getAssumedSimplifiedValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyreturned/#a1bd851a4aaa71b142b2db5125d55c209">anonymous{AttributorAttributes.cpp}::AAValueSimplifyReturned::getAssumedSimplifiedValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#ad277bd35b295f10501e8ead87d705599">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyfunction/#af68c191c5904e7c1b67393ba18ae722c">anonymous{AttributorAttributes.cpp}::AAValueSimplifyFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a469217e1991252d89a236638f25c5293">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::manifestReplacementValue</a>, <a href="#ad70b17ba782d01eb1f17633d14e0d033">operator==</a>, <a href="#a3b30794202b9b3042b5567a270ea8735">unionAssumed</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyfloating/#a5e38f307b522c2e541b9cccb795186fc">anonymous{AttributorAttributes.cpp}::AAValueSimplifyFloating::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyreturned/#ac9ae54449e677f539c50426011907713">anonymous{AttributorAttributes.cpp}::AAValueSimplifyReturned::updateImpl</a>.</p>

</div>
</div>

### Ty {#ad0e539b8f2629b0024a998d435822d48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::ValueSimplifyStateType::Ty</td>
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

<p>The type of the original value.</p>

<p>Definition at line 4495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a63540fe3243b44a62cb656c73274f8ac">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::ensureType</a>, <a href="#a84c2c9e9bbd67dc27f58a14c9f8866a7">getBestState</a>, <a href="#a0447b63e9b31ebfb662abcf445e69065">getWorstState</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#ad87f4b76b6846d029880d6b9012a7e69">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::reproduceInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a450c2f1a2d1c2e08bf66297247baa964">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::reproduceValue</a>, <a href="#a3b30794202b9b3042b5567a270ea8735">unionAssumed</a> and <a href="#a59ff04feb3c50d53847f4c9840284257">ValueSimplifyStateType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getBestState() {#a84c2c9e9bbd67dc27f58a14c9f8866a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueSimplifyStateType llvm::ValueSimplifyStateType::getBestState (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 4440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#ad0e539b8f2629b0024a998d435822d48">Ty</a> and <a href="#a59ff04feb3c50d53847f4c9840284257">ValueSimplifyStateType</a>.</p>


<p>Referenced by <a href="#a04e8d558c1b7761c15270982961d56be">getBestState</a>.</p>

</div>
</div>

### getBestState() {#a04e8d558c1b7761c15270982961d56be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueSimplifyStateType llvm::ValueSimplifyStateType::getBestState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype">ValueSimplifyStateType</a> &amp; VS)</td>
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



<p>Definition at line 4443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a84c2c9e9bbd67dc27f58a14c9f8866a7">getBestState</a> and <a href="#a59ff04feb3c50d53847f4c9840284257">ValueSimplifyStateType</a>.</p>

</div>
</div>

### getWorstState() {#a0447b63e9b31ebfb662abcf445e69065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueSimplifyStateType llvm::ValueSimplifyStateType::getWorstState (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Definition at line 4448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#ad0e539b8f2629b0024a998d435822d48">Ty</a> and <a href="#a59ff04feb3c50d53847f4c9840284257">ValueSimplifyStateType</a>.</p>


<p>Referenced by <a href="#aac79cde1d3e1e4f98bcb81de733b443e">getWorstState</a>.</p>

</div>
</div>

### getWorstState() {#aac79cde1d3e1e4f98bcb81de733b443e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueSimplifyStateType llvm::ValueSimplifyStateType::getWorstState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype">ValueSimplifyStateType</a> &amp; VS)</td>
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



<p>Definition at line 4454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a0447b63e9b31ebfb662abcf445e69065">getWorstState</a> and <a href="#a59ff04feb3c50d53847f4c9840284257">ValueSimplifyStateType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
