---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/reachabilityqueryinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ReachabilityQueryInfo` Struct Template Reference

<p>----------------—<a href="/web-llvm/docs/api/structs/llvm/aaintrafnreachability">AAIntraFnReachability</a> Attribute-----------------------— <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ToTy&gt;
struct ReachabilityQueryInfo&lt;ToTy&gt; { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ToTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">Reachable { <a href="#a41f34b69e17cfbc9bda7385be0d90eaa">...</a> }</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ToTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ab61dcdc06c0198820a8a9807cba33415">ReachabilityQueryInfo</a> (const Instruction *From, const ToTy *To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ToTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac7e0dd79c719ac786282002e7b96f8a4">ReachabilityQueryInfo</a> (Attributor &amp;A, const Instruction &amp;From, const ToTy &amp;To, const AA::InstExclusionSetTy *ES, bool MakeUnique)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor replacement to ensure unique and stable sets are used for the cache. <a href="#ac7e0dd79c719ac786282002e7b96f8a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ToTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a3b40a66358bee4a50d64641628a6d836">ReachabilityQueryInfo</a> (const ReachabilityQueryInfo &amp;RQI)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ToTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe8aa36e977b0f4baaebe46c82fe912e">computeHashValue</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ToTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a978f894ba06c0fcdb14b122f0f592a64">From</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start here,. <a href="#a978f894ba06c0fcdb14b122f0f592a64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ToTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ToTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae643947f553593989540cd23924ce6f7">To</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reach this place, <a href="#ae643947f553593989540cd23924ce6f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ToTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ab7dc88f593d600ddcfe97fcbd6f15e43">AA::InstExclusionSetTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afc90658d591576cc41480685aa24f7ec">ExclusionSet</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>without going through any of these instructions, <a href="#afc90658d591576cc41480685aa24f7ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ToTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a41f34b69e17cfbc9bda7385be0d90eaa">Reachable</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa083392720b7e2d5a9b851da4501173b">Result</a> = <a href="#a41f34b69e17cfbc9bda7385be0d90eaaabafd7322c6e97d25b6299b5d6fe8920b">Reachable::No</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>and remember if it worked: <a href="#aa083392720b7e2d5a9b851da4501173b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ToTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5bb2bc277bf5bd97f9f2b5da7e574bfd">Hash</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Precomputed hash for this RQI. <a href="#a5bb2bc277bf5bd97f9f2b5da7e574bfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>----------------—<a href="/web-llvm/docs/api/structs/llvm/aaintrafnreachability">AAIntraFnReachability</a> Attribute-----------------------—</p>


<p>All information associated with a reachability query. This boilerplate code is used by both <a href="/web-llvm/docs/api/structs/llvm/aaintrafnreachability">AAIntraFnReachability</a> and <a href="/web-llvm/docs/api/structs/llvm/aainterfnreachability">AAInterFnReachability</a>, with different <span class="doxyComputerOutput">ToTy</span> values.</p>


<p>Definition at line 3414 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Reachable {#a41f34b69e17cfbc9bda7385be0d90eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class ReachabilityQueryInfo::Reachable </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">No<a id="a41f34b69e17cfbc9bda7385be0d90eaaabafd7322c6e97d25b6299b5d6fe8920b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Yes<a id="a41f34b69e17cfbc9bda7385be0d90eaaa93cba07454f06a4a960172bbd6e2a435"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 3415 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ReachabilityQueryInfo() {#ab61dcdc06c0198820a8a9807cba33415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ToTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ToTy * To)</td>
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



<p>Definition at line 3441 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="#a978f894ba06c0fcdb14b122f0f592a64">ReachabilityQueryInfo&lt; ToTy &gt;::From</a> and <a href="#ae643947f553593989540cd23924ce6f7">ReachabilityQueryInfo&lt; ToTy &gt;::To</a>.</p>


<p>Referenced by <a href="#afe8aa36e977b0f4baaebe46c82fe912e">ReachabilityQueryInfo&lt; ToTy &gt;::computeHashValue</a> and <a href="#a3b40a66358bee4a50d64641628a6d836">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo</a>.</p>

</div>
</div>

### ReachabilityQueryInfo() {#ac7e0dd79c719ac786282002e7b96f8a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ToTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ToTy &amp; To, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ab7dc88f593d600ddcfe97fcbd6f15e43">AA::InstExclusionSetTy</a> * ES, bool MakeUnique)</td>
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

<p>Constructor replacement to ensure unique and stable sets are used for the cache.</p>

<p>Definition at line 3446 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="#afc90658d591576cc41480685aa24f7ec">ReachabilityQueryInfo&lt; ToTy &gt;::ExclusionSet</a>, <a href="#a978f894ba06c0fcdb14b122f0f592a64">ReachabilityQueryInfo&lt; ToTy &gt;::From</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> and <a href="#ae643947f553593989540cd23924ce6f7">ReachabilityQueryInfo&lt; ToTy &gt;::To</a>.</p>

</div>
</div>

### ReachabilityQueryInfo() {#a3b40a66358bee4a50d64641628a6d836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ToTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/reachabilityqueryinfo">ReachabilityQueryInfo</a> &amp; RQI)</td>
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



<p>Definition at line 3457 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="#afc90658d591576cc41480685aa24f7ec">ReachabilityQueryInfo&lt; ToTy &gt;::ExclusionSet</a>, <a href="#a978f894ba06c0fcdb14b122f0f592a64">ReachabilityQueryInfo&lt; ToTy &gt;::From</a>, <a href="#ab61dcdc06c0198820a8a9807cba33415">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo</a> and <a href="#ae643947f553593989540cd23924ce6f7">ReachabilityQueryInfo&lt; ToTy &gt;::To</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeHashValue() {#afe8aa36e977b0f4baaebe46c82fe912e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ToTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ReachabilityQueryInfo&lt; ToTy &gt;::computeHashValue ()</td>
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



<p>Definition at line 3432 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#adaf63b0798f9c39efed487be544ba508">llvm::detail::combineHashValue</a>, <a href="#afc90658d591576cc41480685aa24f7ec">ReachabilityQueryInfo&lt; ToTy &gt;::ExclusionSet</a>, <a href="#a978f894ba06c0fcdb14b122f0f592a64">ReachabilityQueryInfo&lt; ToTy &gt;::From</a>, <a href="#a5bb2bc277bf5bd97f9f2b5da7e574bfd">ReachabilityQueryInfo&lt; ToTy &gt;::Hash</a>, <a href="#ab61dcdc06c0198820a8a9807cba33415">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo</a> and <a href="#ae643947f553593989540cd23924ce6f7">ReachabilityQueryInfo&lt; ToTy &gt;::To</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-1f70f14c582cbbbb4c4580fe510d45f9/#af7f1c19b8f5e43f8d85e22d1c23df8ca">llvm::DenseMapInfo&lt; ReachabilityQueryInfo&lt; ToTy &gt; * &gt;::getHashValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ExclusionSet {#afc90658d591576cc41480685aa24f7ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ToTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AA::InstExclusionSetTy* ReachabilityQueryInfo&lt; ToTy &gt;::ExclusionSet = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>without going through any of these instructions,</p>

<p>Definition at line 3425 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/cachedreachabilityaa/#a8b9423e461bb953df93b2832f9d31ef5">anonymous{AttributorAttributes.cpp}::CachedReachabilityAA&lt; AAIntraFnReachability, Instruction &gt;::checkQueryCache</a>, <a href="#afe8aa36e977b0f4baaebe46c82fe912e">ReachabilityQueryInfo&lt; ToTy &gt;::computeHashValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainterfnreachabilityfunction/#a6c50862efd6adb69da166ddce9dc912c">anonymous{AttributorAttributes.cpp}::AAInterFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaintrafnreachabilityfunction/#aa6f399598404d630b1091693ed0a6f88">anonymous{AttributorAttributes.cpp}::AAIntraFnReachabilityFunction::isReachableImpl</a>, <a href="#ac7e0dd79c719ac786282002e7b96f8a4">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo</a>, <a href="#a3b40a66358bee4a50d64641628a6d836">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/cachedreachabilityaa/#a9cb7899855145ac6df66881fe11cdc43">anonymous{AttributorAttributes.cpp}::CachedReachabilityAA&lt; AAIntraFnReachability, Instruction &gt;::rememberResult</a>.</p>

</div>
</div>

### From {#a978f894ba06c0fcdb14b122f0f592a64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ToTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction* ReachabilityQueryInfo&lt; ToTy &gt;::From = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Start here,.</p>

<p>Definition at line 3421 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/cachedreachabilityaa/#a8b9423e461bb953df93b2832f9d31ef5">anonymous{AttributorAttributes.cpp}::CachedReachabilityAA&lt; AAIntraFnReachability, Instruction &gt;::checkQueryCache</a>, <a href="#afe8aa36e977b0f4baaebe46c82fe912e">ReachabilityQueryInfo&lt; ToTy &gt;::computeHashValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainterfnreachabilityfunction/#a6c50862efd6adb69da166ddce9dc912c">anonymous{AttributorAttributes.cpp}::AAInterFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaintrafnreachabilityfunction/#aa6f399598404d630b1091693ed0a6f88">anonymous{AttributorAttributes.cpp}::AAIntraFnReachabilityFunction::isReachableImpl</a>, <a href="#ac7e0dd79c719ac786282002e7b96f8a4">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo</a>, <a href="#ab61dcdc06c0198820a8a9807cba33415">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo</a>, <a href="#a3b40a66358bee4a50d64641628a6d836">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/cachedreachabilityaa/#a9cb7899855145ac6df66881fe11cdc43">anonymous{AttributorAttributes.cpp}::CachedReachabilityAA&lt; AAIntraFnReachability, Instruction &gt;::rememberResult</a>.</p>

</div>
</div>

### Hash {#a5bb2bc277bf5bd97f9f2b5da7e574bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ToTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ReachabilityQueryInfo&lt; ToTy &gt;::Hash = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Precomputed hash for this RQI.</p>

<p>Definition at line 3430 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="#afe8aa36e977b0f4baaebe46c82fe912e">ReachabilityQueryInfo&lt; ToTy &gt;::computeHashValue</a> and <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-1f70f14c582cbbbb4c4580fe510d45f9/#af7f1c19b8f5e43f8d85e22d1c23df8ca">llvm::DenseMapInfo&lt; ReachabilityQueryInfo&lt; ToTy &gt; * &gt;::getHashValue</a>.</p>

</div>
</div>

### Result {#aa083392720b7e2d5a9b851da4501173b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ToTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Reachable ReachabilityQueryInfo&lt; ToTy &gt;::Result = <a href="#a41f34b69e17cfbc9bda7385be0d90eaaabafd7322c6e97d25b6299b5d6fe8920b">Reachable::No</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>and remember if it worked:</p>

<p>Definition at line 3427 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/cachedreachabilityaa/#a9cb7899855145ac6df66881fe11cdc43">anonymous{AttributorAttributes.cpp}::CachedReachabilityAA&lt; AAIntraFnReachability, Instruction &gt;::rememberResult</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/cachedreachabilityaa/#a3dead7060258bad7ff30428ac7541a8e">anonymous{AttributorAttributes.cpp}::CachedReachabilityAA&lt; AAIntraFnReachability, Instruction &gt;::updateImpl</a>.</p>

</div>
</div>

### To {#ae643947f553593989540cd23924ce6f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ToTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ToTy* ReachabilityQueryInfo&lt; ToTy &gt;::To = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reach this place,</p>

<p>Definition at line 3423 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/cachedreachabilityaa/#a8b9423e461bb953df93b2832f9d31ef5">anonymous{AttributorAttributes.cpp}::CachedReachabilityAA&lt; AAIntraFnReachability, Instruction &gt;::checkQueryCache</a>, <a href="#afe8aa36e977b0f4baaebe46c82fe912e">ReachabilityQueryInfo&lt; ToTy &gt;::computeHashValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainterfnreachabilityfunction/#a6c50862efd6adb69da166ddce9dc912c">anonymous{AttributorAttributes.cpp}::AAInterFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaintrafnreachabilityfunction/#aa6f399598404d630b1091693ed0a6f88">anonymous{AttributorAttributes.cpp}::AAIntraFnReachabilityFunction::isReachableImpl</a>, <a href="#ac7e0dd79c719ac786282002e7b96f8a4">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo</a>, <a href="#ab61dcdc06c0198820a8a9807cba33415">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo</a>, <a href="#a3b40a66358bee4a50d64641628a6d836">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/cachedreachabilityaa/#a9cb7899855145ac6df66881fe11cdc43">anonymous{AttributorAttributes.cpp}::CachedReachabilityAA&lt; AAIntraFnReachability, Instruction &gt;::rememberResult</a>.</p>

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
