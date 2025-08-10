---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/trackingstatistic
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TrackingStatistic` Class



## Declaration

<div class="doxyDeclaration">
class llvm::TrackingStatistic { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3c669930d2039d91c0ae719240e4da4">TrackingStatistic</a> (const char *DebugType, const char *Name, const char *Desc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c995898b97ff9b222ed45de9a0569ba">operator uint64_t</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/trackingstatistic">TrackingStatistic</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb37d2855adc6e4dfe8cd516844f53b">operator=</a> (uint64_t Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/trackingstatistic">TrackingStatistic</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef82b89dc9accfbec90a8ae2b255528">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a36a2c23622828f49899e6f7fa6f6e4">operator++</a> (int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/trackingstatistic">TrackingStatistic</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a014839d7e3902ff4ddd8655f7c3909ed">operator--</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b969e017efc33025d2fc4c0f82040a4">operator--</a> (int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/trackingstatistic">TrackingStatistic</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae422917db782a6247fd48baeb535f0fe">operator+=</a> (uint64_t V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/trackingstatistic">TrackingStatistic</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac61a88df51a7e2f0c4a89984c9feeb05">operator-=</a> (uint64_t V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30537c4d546fff17153fdc060d59ca77">getDebugType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e5903a6dddd728b902428b4b75b6929">getName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ef64a3953bb8330989f953897b37437">getDesc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16d97f1b51dbcb20eb720512669a4642">getValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60c8454b697b7d0c42752cd3dc05678a">updateMax</a> (uint64_t V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/trackingstatistic">TrackingStatistic</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e7f75184692a3cc6e247b3f1f3213ef">init</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af204074bb99629a0b644be5a81b1a269">RegisterStatistic</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegisterStatistic - The first time a statistic is bumped, this method is called. <a href="#af204074bb99629a0b644be5a81b1a269">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2c241e214cc30611008e0af77ee4d6a">DebugType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45ca77eb7879cf71ab950311795e812d">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf1cc9dc8bde0abddd2b72ba1af9590b">Desc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35551bf997b08d95de945a32e1b9ad6b">Value</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac316effa43b4fd54b6451be0a3cc3d69">Initialized</a></td>
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


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TrackingStatistic() {#ae3c669930d2039d91c0ae719240e4da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TrackingStatistic::TrackingStatistic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * DebugType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Desc)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>References <a href="#ae2c241e214cc30611008e0af77ee4d6a">DebugType</a>, <a href="#abf1cc9dc8bde0abddd2b72ba1af9590b">Desc</a>, <a href="#ac316effa43b4fd54b6451be0a3cc3d69">Initialized</a>, <a href="#a45ca77eb7879cf71ab950311795e812d">Name</a> and <a href="#a35551bf997b08d95de945a32e1b9ad6b">Value</a>.</p>


<p>Referenced by <a href="#a4e7f75184692a3cc6e247b3f1f3213ef">init</a>, <a href="#a8ef82b89dc9accfbec90a8ae2b255528">operator++</a>, <a href="#ae422917db782a6247fd48baeb535f0fe">operator+=</a>, <a href="#a014839d7e3902ff4ddd8655f7c3909ed">operator--</a>, <a href="#ac61a88df51a7e2f0c4a89984c9feeb05">operator-=</a> and <a href="#a7eb37d2855adc6e4dfe8cd516844f53b">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator uint64\_t() {#a7c995898b97ff9b222ed45de9a0569ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TrackingStatistic::operator uint64_t ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>Reference <a href="#a16d97f1b51dbcb20eb720512669a4642">getValue</a>.</p>

</div>
</div>

### operator--() {#a014839d7e3902ff4ddd8655f7c3909ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TrackingStatistic &amp; llvm::TrackingStatistic::operator-- ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>References <a href="#a4e7f75184692a3cc6e247b3f1f3213ef">init</a>, <a href="#ae3c669930d2039d91c0ae719240e4da4">TrackingStatistic</a> and <a href="#a35551bf997b08d95de945a32e1b9ad6b">Value</a>.</p>

</div>
</div>

### operator--() {#a8b969e017efc33025d2fc4c0f82040a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::TrackingStatistic::operator-- (int)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>References <a href="#a4e7f75184692a3cc6e247b3f1f3213ef">init</a> and <a href="#a35551bf997b08d95de945a32e1b9ad6b">Value</a>.</p>

</div>
</div>

### operator-=() {#ac61a88df51a7e2f0c4a89984c9feeb05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TrackingStatistic &amp; llvm::TrackingStatistic::operator-= (uint64_t V)</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>References <a href="#a4e7f75184692a3cc6e247b3f1f3213ef">init</a>, <a href="#ae3c669930d2039d91c0ae719240e4da4">TrackingStatistic</a> and <a href="#a35551bf997b08d95de945a32e1b9ad6b">Value</a>.</p>

</div>
</div>

### operator++() {#a8ef82b89dc9accfbec90a8ae2b255528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TrackingStatistic &amp; llvm::TrackingStatistic::operator++ ()</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>References <a href="#a4e7f75184692a3cc6e247b3f1f3213ef">init</a>, <a href="#ae3c669930d2039d91c0ae719240e4da4">TrackingStatistic</a> and <a href="#a35551bf997b08d95de945a32e1b9ad6b">Value</a>.</p>

</div>
</div>

### operator++() {#a2a36a2c23622828f49899e6f7fa6f6e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::TrackingStatistic::operator++ (int)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>References <a href="#a4e7f75184692a3cc6e247b3f1f3213ef">init</a> and <a href="#a35551bf997b08d95de945a32e1b9ad6b">Value</a>.</p>

</div>
</div>

### operator+=() {#ae422917db782a6247fd48baeb535f0fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TrackingStatistic &amp; llvm::TrackingStatistic::operator+= (uint64_t V)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>References <a href="#a4e7f75184692a3cc6e247b3f1f3213ef">init</a>, <a href="#ae3c669930d2039d91c0ae719240e4da4">TrackingStatistic</a> and <a href="#a35551bf997b08d95de945a32e1b9ad6b">Value</a>.</p>

</div>
</div>

### operator=() {#a7eb37d2855adc6e4dfe8cd516844f53b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TrackingStatistic &amp; llvm::TrackingStatistic::operator= (uint64_t Val)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>References <a href="#a4e7f75184692a3cc6e247b3f1f3213ef">init</a>, <a href="#ae3c669930d2039d91c0ae719240e4da4">TrackingStatistic</a> and <a href="#a35551bf997b08d95de945a32e1b9ad6b">Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDebugType() {#a30537c4d546fff17153fdc060d59ca77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::TrackingStatistic::getDebugType ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>Reference <a href="#ae2c241e214cc30611008e0af77ee4d6a">DebugType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4956c1072998f3de28fb64a8979fcbf5">llvm::PrintStatistics</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aec1a19ebf309a206257e212c33f045a1">llvm::PrintStatisticsJSON</a>.</p>

</div>
</div>

### getDesc() {#a0ef64a3953bb8330989f953897b37437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::TrackingStatistic::getDesc ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>Reference <a href="#abf1cc9dc8bde0abddd2b72ba1af9590b">Desc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4956c1072998f3de28fb64a8979fcbf5">llvm::PrintStatistics</a>.</p>

</div>
</div>

### getName() {#a8e5903a6dddd728b902428b4b75b6929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::TrackingStatistic::getName ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>Reference <a href="#a45ca77eb7879cf71ab950311795e812d">Name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aec1a19ebf309a206257e212c33f045a1">llvm::PrintStatisticsJSON</a>.</p>

</div>
</div>

### getValue() {#a16d97f1b51dbcb20eb720512669a4642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::TrackingStatistic::getValue ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>Reference <a href="#a35551bf997b08d95de945a32e1b9ad6b">Value</a>.</p>


<p>Referenced by <a href="#a7c995898b97ff9b222ed45de9a0569ba">operator uint64_t</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956c1072998f3de28fb64a8979fcbf5">llvm::PrintStatistics</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aec1a19ebf309a206257e212c33f045a1">llvm::PrintStatisticsJSON</a>.</p>

</div>
</div>

### updateMax() {#a60c8454b697b7d0c42752cd3dc05678a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TrackingStatistic::updateMax (uint64_t V)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>References <a href="#a4e7f75184692a3cc6e247b3f1f3213ef">init</a> and <a href="#a35551bf997b08d95de945a32e1b9ad6b">Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### init() {#a4e7f75184692a3cc6e247b3f1f3213ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrackingStatistic &amp; llvm::TrackingStatistic::init ()</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>References <a href="#ac316effa43b4fd54b6451be0a3cc3d69">Initialized</a>, <a href="#af204074bb99629a0b644be5a81b1a269">RegisterStatistic</a> and <a href="#ae3c669930d2039d91c0ae719240e4da4">TrackingStatistic</a>.</p>


<p>Referenced by <a href="#a8ef82b89dc9accfbec90a8ae2b255528">operator++</a>, <a href="#a2a36a2c23622828f49899e6f7fa6f6e4">operator++</a>, <a href="#ae422917db782a6247fd48baeb535f0fe">operator+=</a>, <a href="#a014839d7e3902ff4ddd8655f7c3909ed">operator--</a>, <a href="#a8b969e017efc33025d2fc4c0f82040a4">operator--</a>, <a href="#ac61a88df51a7e2f0c4a89984c9feeb05">operator-=</a>, <a href="#a7eb37d2855adc6e4dfe8cd516844f53b">operator=</a> and <a href="#a60c8454b697b7d0c42752cd3dc05678a">updateMax</a>.</p>

</div>
</div>

### RegisterStatistic() {#af204074bb99629a0b644be5a81b1a269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TrackingStatistic::RegisterStatistic ()</td>
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

<p>RegisterStatistic - The first time a statistic is bumped, this method is called.</p>

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp/#a558f5c44426d0eb7abb82a65e8892d9a">Enabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp/#a38906af8cc37ba9ddf2260cf1e2b0483">EnableStats</a>, <a href="#ac316effa43b4fd54b6451be0a3cc3d69">Initialized</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp/#a9d1a0181d192027598d0cf59a7291e5d">StatInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp/#ac984e1f297b2dac8cbf7c4cf8777e4ea">StatLock</a>.</p>


<p>Referenced by <a href="#a4e7f75184692a3cc6e247b3f1f3213ef">init</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DebugType {#ae2c241e214cc30611008e0af77ee4d6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* const llvm::TrackingStatistic::DebugType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>Referenced by <a href="#a30537c4d546fff17153fdc060d59ca77">getDebugType</a> and <a href="#ae3c669930d2039d91c0ae719240e4da4">TrackingStatistic</a>.</p>

</div>
</div>

### Desc {#abf1cc9dc8bde0abddd2b72ba1af9590b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* const llvm::TrackingStatistic::Desc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>Referenced by <a href="#a0ef64a3953bb8330989f953897b37437">getDesc</a> and <a href="#ae3c669930d2039d91c0ae719240e4da4">TrackingStatistic</a>.</p>

</div>
</div>

### Initialized {#ac316effa43b4fd54b6451be0a3cc3d69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;bool&gt; llvm::TrackingStatistic::Initialized</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>Referenced by <a href="#a4e7f75184692a3cc6e247b3f1f3213ef">init</a>, <a href="#af204074bb99629a0b644be5a81b1a269">RegisterStatistic</a> and <a href="#ae3c669930d2039d91c0ae719240e4da4">TrackingStatistic</a>.</p>

</div>
</div>

### Name {#a45ca77eb7879cf71ab950311795e812d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* const llvm::TrackingStatistic::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>Referenced by <a href="#a8e5903a6dddd728b902428b4b75b6929">getName</a> and <a href="#ae3c669930d2039d91c0ae719240e4da4">TrackingStatistic</a>.</p>

</div>
</div>

### Value {#a35551bf997b08d95de945a32e1b9ad6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;uint64_t&gt; llvm::TrackingStatistic::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>


<p>Referenced by <a href="#a16d97f1b51dbcb20eb720512669a4642">getValue</a>, <a href="#a8ef82b89dc9accfbec90a8ae2b255528">operator++</a>, <a href="#a2a36a2c23622828f49899e6f7fa6f6e4">operator++</a>, <a href="#ae422917db782a6247fd48baeb535f0fe">operator+=</a>, <a href="#a014839d7e3902ff4ddd8655f7c3909ed">operator--</a>, <a href="#a8b969e017efc33025d2fc4c0f82040a4">operator--</a>, <a href="#ac61a88df51a7e2f0c4a89984c9feeb05">operator-=</a>, <a href="#a7eb37d2855adc6e4dfe8cd516844f53b">operator=</a>, <a href="#ae3c669930d2039d91c0ae719240e4da4">TrackingStatistic</a> and <a href="#a60c8454b697b7d0c42752cd3dc05678a">updateMax</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
