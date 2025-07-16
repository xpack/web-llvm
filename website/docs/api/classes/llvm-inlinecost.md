---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/inlinecost
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InlineCost` Class Reference

<p>Represents the cost of inlining a function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InlineCost { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">llvm/Analysis/InlineCost.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SentinelValues { <a href="#ac3193d984e6364224a2645565cd79c9a">...</a> }</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4568757615adc8ed4c1d475345f4f43b">InlineCost</a> (int Cost, int Threshold, int StaticBonusApplied, const char *Reason=nullptr, std::optional&lt; CostBenefitPair &gt; CostBenefit=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1afbe29c3a4c4306ee7ba2f1b45c1a1e">operator bool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the inline cost is low enough for inlining. <a href="#a1afbe29c3a4c4306ee7ba2f1b45c1a1e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad166c05849a74acb5e56415f7533e8ad">isAlways</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe5d6bf96241855ed0c239fa621cd433">isNever</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb15e0a412ebed4724ab6e68346a666b">isVariable</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aa025661dacbb8cf0db3f6220d91f49">getCost</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the inline cost estimate. <a href="#a5aa025661dacbb8cf0db3f6220d91f49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ba48a10e442634367cf040a1167e355">getThreshold</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the threshold against which the cost was computed. <a href="#a0ba48a10e442634367cf040a1167e355">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1809a68615417e3dc85c93b1153c2354">getStaticBonusApplied</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the amount of StaticBonus applied. <a href="#a1809a68615417e3dc85c93b1153c2354">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/costbenefitpair">CostBenefitPair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08ba91080cf645092031afe0ce64d8c2">getCostBenefit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the cost-benefit pair which was computed by cost-benefit analysis. <a href="#a08ba91080cf645092031afe0ce64d8c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15bdb4c4b97c09c0e10ab50229ec4f49">getReason</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the reason of Always or Never. <a href="#a15bdb4c4b97c09c0e10ab50229ec4f49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1798a4114dad2820cb163dc5b2db758">getCostDelta</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the cost delta from the threshold for inlining. <a href="#ad1798a4114dad2820cb163dc5b2db758">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75915aa559432611651c57a521b43a05">Cost</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The estimated cost of inlining this callsite. <a href="#a75915aa559432611651c57a521b43a05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69c1c41379b67a6b66e742d884a7c5a3">Threshold</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The adjusted threshold against which this cost was computed. <a href="#a69c1c41379b67a6b66e742d884a7c5a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9594c175572276d244655b59f270e531">StaticBonusApplied</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The amount of StaticBonus that has been applied. <a href="#a9594c175572276d244655b59f270e531">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeea5869159a1f7a972f66c5bb3f9d39a">Reason</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Must be set for Always and Never instances. <a href="#aeea5869159a1f7a972f66c5bb3f9d39a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/costbenefitpair">CostBenefitPair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f643124c92ac039229f0a99bf511e71">CostBenefit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost-benefit pair computed by cost-benefit analysis. <a href="#a4f643124c92ac039229f0a99bf511e71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/inlinecost">InlineCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1dbd59a648c96031c8d91238017e6c2">get</a> (int Cost, int Threshold, int StaticBonus=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/inlinecost">InlineCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa71268864238db3f41e3d6582103e4e2">getAlways</a> (const char *Reason, std::optional&lt; CostBenefitPair &gt; CostBenefit=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/inlinecost">InlineCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1e6376794d0c3da5a2820a2943634eb">getNever</a> (const char *Reason, std::optional&lt; CostBenefitPair &gt; CostBenefit=std::nullopt)</td>
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

<p>Represents the cost of inlining a function.</p>


<p>This supports special values for functions which should "always" or "never" be inlined. Otherwise, the cost represents a unitless amount; smaller values increase the likelihood of the function being inlined.</p>


<p>Objects of this type also provide the adjusted threshold for inlining based on the information available for a particular callsite. They can be directly tested to determine if inlining should occur given the cost and threshold for this cost metric.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### SentinelValues {#ac3193d984e6364224a2645565cd79c9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::InlineCost::SentinelValues </td>
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
<td class="doxyEnumItemName">AlwaysInlineCost<a id="ac3193d984e6364224a2645565cd79c9aaf08635195142b45c2812468fa6ccdb82"></a></td>
<td class="doxyEnumItemDescription"> (= INT_MIN)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NeverInlineCost<a id="ac3193d984e6364224a2645565cd79c9aa949fded5fe57e45bca5d5df003ef6df7"></a></td>
<td class="doxyEnumItemDescription"> (= INT_MAX)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### InlineCost() {#a4568757615adc8ed4c1d475345f4f43b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineCost::InlineCost (int Cost, int Threshold, int StaticBonusApplied, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Reason=nullptr, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/costbenefitpair">CostBenefitPair</a> &gt; CostBenefit=std::nullopt)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a1afbe29c3a4c4306ee7ba2f1b45c1a1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineCost::operator bool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the inline cost is low enough for inlining.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCost() {#a5aa025661dacbb8cf0db3f6220d91f49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::InlineCost::getCost ()</td>
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

<p>Get the inline cost estimate.</p>


<p>It is an error to call this on an "always" or "never" <a href="/web-llvm/docs/api/classes/llvm/inlinecost">InlineCost</a>.</p>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aeb15e0a412ebed4724ab6e68346a666b">isVariable</a>.</p>


<p>Referenced by <a href="#ad1798a4114dad2820cb163dc5b2db758">getCostDelta</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf828eea7efcbbc84e0b3a0decdb8b44">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp/#a0e5ee7a451482722a4446bdf208df9fc">shouldBeDeferred</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a25e327ae759c3362067beb2aad1dbfdd">llvm::shouldInline</a>.</p>

</div>
</div>

### getCostBenefit() {#a08ba91080cf645092031afe0ce64d8c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CostBenefitPair &gt; llvm::InlineCost::getCostBenefit ()</td>
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

<p>Get the cost-benefit pair which was computed by cost-benefit analysis.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>

</div>
</div>

### getCostDelta() {#ad1798a4114dad2820cb163dc5b2db758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::InlineCost::getCostDelta ()</td>
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

<p>Get the cost delta from the threshold for inlining.</p>


<p>Only valid if the cost is of the variable kind. Returns a negative value if the cost is too high to inline.</p>


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>Reference <a href="#a5aa025661dacbb8cf0db3f6220d91f49">getCost</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp/#a0e5ee7a451482722a4446bdf208df9fc">shouldBeDeferred</a>.</p>

</div>
</div>

### getReason() {#a15bdb4c4b97c09c0e10ab50229ec4f49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::InlineCost::getReason ()</td>
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

<p>Get the reason of Always or Never.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aeb15e0a412ebed4724ab6e68346a666b">isVariable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aaf828eea7efcbbc84e0b3a0decdb8b44">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### getStaticBonusApplied() {#a1809a68615417e3dc85c93b1153c2354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::InlineCost::getStaticBonusApplied ()</td>
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

<p>Get the amount of StaticBonus applied.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aeb15e0a412ebed4724ab6e68346a666b">isVariable</a>.</p>

</div>
</div>

### getThreshold() {#a0ba48a10e442634367cf040a1167e355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::InlineCost::getThreshold ()</td>
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

<p>Get the threshold against which the cost was computed.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aeb15e0a412ebed4724ab6e68346a666b">isVariable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aaf828eea7efcbbc84e0b3a0decdb8b44">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### isAlways() {#ad166c05849a74acb5e56415f7533e8ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineCost::isAlways ()</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a83035d5c2bb6a64f3c35b716a994b586">llvm::emitInlinedIntoBasedOnCost</a>, <a href="#aeb15e0a412ebed4724ab6e68346a666b">isVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf828eea7efcbbc84e0b3a0decdb8b44">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp/#a0e5ee7a451482722a4446bdf208df9fc">shouldBeDeferred</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a25e327ae759c3362067beb2aad1dbfdd">llvm::shouldInline</a>.</p>

</div>
</div>

### isNever() {#afe5d6bf96241855ed0c239fa621cd433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineCost::isNever ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>Referenced by <a href="#aeb15e0a412ebed4724ab6e68346a666b">isVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf828eea7efcbbc84e0b3a0decdb8b44">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a25e327ae759c3362067beb2aad1dbfdd">llvm::shouldInline</a>.</p>

</div>
</div>

### isVariable() {#aeb15e0a412ebed4724ab6e68346a666b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineCost::isVariable ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>References <a href="#ad166c05849a74acb5e56415f7533e8ad">isAlways</a> and <a href="#afe5d6bf96241855ed0c239fa621cd433">isNever</a>.</p>


<p>Referenced by <a href="#a5aa025661dacbb8cf0db3f6220d91f49">getCost</a>, <a href="#a15bdb4c4b97c09c0e10ab50229ec4f49">getReason</a>, <a href="#a1809a68615417e3dc85c93b1153c2354">getStaticBonusApplied</a> and <a href="#a0ba48a10e442634367cf040a1167e355">getThreshold</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Cost {#a75915aa559432611651c57a521b43a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::InlineCost::Cost = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The estimated cost of inlining this callsite.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>

</div>
</div>

### CostBenefit {#a4f643124c92ac039229f0a99bf511e71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;CostBenefitPair&gt; llvm::InlineCost::CostBenefit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost-benefit pair computed by cost-benefit analysis.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>

</div>
</div>

### Reason {#aeea5869159a1f7a972f66c5bb3f9d39a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::InlineCost::Reason = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Must be set for Always and Never instances.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>

</div>
</div>

### StaticBonusApplied {#a9594c175572276d244655b59f270e531}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::InlineCost::StaticBonusApplied = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The amount of StaticBonus that has been applied.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>

</div>
</div>

### Threshold {#a69c1c41379b67a6b66e742d884a7c5a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::InlineCost::Threshold = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The adjusted threshold against which this cost was computed.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#ac1dbd59a648c96031c8d91238017e6c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineCost llvm::InlineCost::get (int Cost, int Threshold, int StaticBonus=0)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a11326a8194a8022478ebafeba2b5ccb5">llvm::getInlineCost</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a518b0cf18edfb9fb05aaa530550af870">anonymous{SampleProfile.cpp}::SampleProfileLoader::shouldInlineCandidate</a>.</p>

</div>
</div>

### getAlways() {#aa71268864238db3f41e3d6582103e4e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineCost llvm::InlineCost::getAlways (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Reason, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/costbenefitpair">CostBenefitPair</a> &gt; CostBenefit=std::nullopt)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-alwaysinliner-cpp-/#af5bb12426b6361914b816365eee4b4fd">anonymous{AlwaysInliner.cpp}::AlwaysInlineImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor/#a83088027da72950b627f9200965fb55b">llvm::ReplayInlineAdvisor::getAdviceImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ab8641bf75d896ad3caffd68a441c4a7e">anonymous{SampleProfile.cpp}::SampleProfileLoader::getExternalInlineAdvisorCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11326a8194a8022478ebafeba2b5ccb5">llvm::getInlineCost</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a518b0cf18edfb9fb05aaa530550af870">anonymous{SampleProfile.cpp}::SampleProfileLoader::shouldInlineCandidate</a>.</p>

</div>
</div>

### getNever() {#aa1e6376794d0c3da5a2820a2943634eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineCost llvm::InlineCost::getNever (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Reason, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/costbenefitpair">CostBenefitPair</a> &gt; CostBenefit=std::nullopt)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ab8641bf75d896ad3caffd68a441c4a7e">anonymous{SampleProfile.cpp}::SampleProfileLoader::getExternalInlineAdvisorCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11326a8194a8022478ebafeba2b5ccb5">llvm::getInlineCost</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a518b0cf18edfb9fb05aaa530550af870">anonymous{SampleProfile.cpp}::SampleProfileLoader::shouldInlineCandidate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
