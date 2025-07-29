---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/profilesummarybuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ProfileSummaryBuilder` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ProfileSummaryBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">llvm/ProfileData/ProfileCommon.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder">InstrProfSummaryBuilder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder">SampleProfileSummaryBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab24fb220148ef06233b2609976f3da9e">ProfileSummaryBuilder</a> (std::vector&lt; uint32_t &gt; Cutoffs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47cb5566f491d0c18288b3e55ff1dc3b">~ProfileSummaryBuilder</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28089a7d5a36c764dfe33f9f44b47d87">addCount</a> (uint64_t Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is called when a count is seen in the profile. <a href="#a28089a7d5a36c764dfe33f9f44b47d87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf99f7dc09e330137cb10a3a42c12b3">computeDetailedSummary</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ad9c07a9deae5d8875d689410d756168d">SummaryEntryVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad028b48e4b5b572a4d192042c467ac80">DetailedSummary</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f4b516c5122d851880c9e1f2cf59520">TotalCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1680e5f0b03a6e19ab4b9043a2db4c56">MaxCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a11c11194d7fa532931fa9421c7021">MaxFunctionCount</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf42bc6121e00b01b160019b4761c546">NumCounts</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac145bd9c0722766b91ad79062cb1028f">NumFunctions</a> = 0</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; uint64_t, uint32_t, std::greater&lt; uint64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64eb18c094dc84d5d0394f71503c131">CountFrequencies</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We keep track of the number of times a count (block count or samples) appears in the profile. <a href="#ae64eb18c094dc84d5d0394f71503c131">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfb3edc6dbe5a1e371e77428e1985376">DetailedSummaryCutoffs</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/profilesummaryentry">ProfileSummaryEntry</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dfdd1a19e144d5bda3e85eed520c036">getEntryForPercentile</a> (const SummaryEntryVector &amp;DS, uint64_t Percentile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the summary entry for a desired percentile of counts. <a href="#a2dfdd1a19e144d5bda3e85eed520c036">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9f81ccf878be56999d549123f628a9a">getHotCountThreshold</a> (const SummaryEntryVector &amp;DS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada15196a850a1aba577e73e5f29b14d9">getColdCountThreshold</a> (const SummaryEntryVector &amp;DS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b2e51220aabb88a132d3bc8fbdf5a66">DefaultCutoffs</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A vector of useful cutoff values for detailed summary. <a href="#a9b2e51220aabb88a132d3bc8fbdf5a66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### ProfileSummaryBuilder() {#ab24fb220148ef06233b2609976f3da9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ProfileSummaryBuilder::ProfileSummaryBuilder (std::vector&lt; uint32_t &gt; Cutoffs)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder/#ae8747e71b83f766bb1c7105a0e89bf07">llvm::InstrProfSummaryBuilder::InstrProfSummaryBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#abbfb3ab120a9cd59c8404b7065230d55">llvm::SampleProfileSummaryBuilder::SampleProfileSummaryBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~ProfileSummaryBuilder() {#a47cb5566f491d0c18288b3e55ff1dc3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ProfileSummaryBuilder::~ProfileSummaryBuilder ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addCount() {#a28089a7d5a36c764dfe33f9f44b47d87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ProfileSummaryBuilder::addCount (uint64_t Count)</td>
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

<p>This is called when a count is seen in the profile.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a1680e5f0b03a6e19ab4b9043a2db4c56">MaxCount</a>, <a href="#adf42bc6121e00b01b160019b4761c546">NumCounts</a> and <a href="#a9f4b516c5122d851880c9e1f2cf59520">TotalCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder/#ad877eb5253ae859efe7aef03e4c54e55">llvm::InstrProfSummaryBuilder::addEntryCount</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder/#a2002e9c0d71251ac2410f38173a383ca">llvm::InstrProfSummaryBuilder::addInternalCount</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#ab20d61c84972c3e0c411adb569076d78">llvm::SampleProfileSummaryBuilder::addRecord</a>.</p>

</div>
</div>

### computeDetailedSummary() {#a0cf99f7dc09e330137cb10a3a42c12b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ProfileSummaryBuilder::computeDetailedSummary ()</td>
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



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#ad028b48e4b5b572a4d192042c467ac80">DetailedSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#a7e1c8033e8518dd3ff895fd106bc75e1">llvm::ProfileSummary::Scale</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a71f7f6e3a4774296efc7274196a74793">llvm::APInt::sdiv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="#a9f4b516c5122d851880c9e1f2cf59520">TotalCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder/#a3d13ddc46d3f3bb1f92b191513008e5a">llvm::InstrProfSummaryBuilder::getSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#a1398195ea49701192f046b104172c2db">llvm::SampleProfileSummaryBuilder::getSummary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DetailedSummary {#ad028b48e4b5b572a4d192042c467ac80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SummaryEntryVector llvm::ProfileSummaryBuilder::DetailedSummary</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<p>Referenced by <a href="#a0cf99f7dc09e330137cb10a3a42c12b3">computeDetailedSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder/#a3d13ddc46d3f3bb1f92b191513008e5a">llvm::InstrProfSummaryBuilder::getSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#a1398195ea49701192f046b104172c2db">llvm::SampleProfileSummaryBuilder::getSummary</a>.</p>

</div>
</div>

### MaxCount {#a1680e5f0b03a6e19ab4b9043a2db4c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ProfileSummaryBuilder::MaxCount = 0</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<p>Referenced by <a href="#a28089a7d5a36c764dfe33f9f44b47d87">addCount</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder/#a3d13ddc46d3f3bb1f92b191513008e5a">llvm::InstrProfSummaryBuilder::getSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#a1398195ea49701192f046b104172c2db">llvm::SampleProfileSummaryBuilder::getSummary</a>.</p>

</div>
</div>

### MaxFunctionCount {#a72a11c11194d7fa532931fa9421c7021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ProfileSummaryBuilder::MaxFunctionCount = 0</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder/#ad877eb5253ae859efe7aef03e4c54e55">llvm::InstrProfSummaryBuilder::addEntryCount</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#ab20d61c84972c3e0c411adb569076d78">llvm::SampleProfileSummaryBuilder::addRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder/#a3d13ddc46d3f3bb1f92b191513008e5a">llvm::InstrProfSummaryBuilder::getSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#a1398195ea49701192f046b104172c2db">llvm::SampleProfileSummaryBuilder::getSummary</a>.</p>

</div>
</div>

### NumCounts {#adf42bc6121e00b01b160019b4761c546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ProfileSummaryBuilder::NumCounts = 0</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<p>Referenced by <a href="#a28089a7d5a36c764dfe33f9f44b47d87">addCount</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder/#a3d13ddc46d3f3bb1f92b191513008e5a">llvm::InstrProfSummaryBuilder::getSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#a1398195ea49701192f046b104172c2db">llvm::SampleProfileSummaryBuilder::getSummary</a>.</p>

</div>
</div>

### NumFunctions {#ac145bd9c0722766b91ad79062cb1028f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ProfileSummaryBuilder::NumFunctions = 0</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder/#ad877eb5253ae859efe7aef03e4c54e55">llvm::InstrProfSummaryBuilder::addEntryCount</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#ab20d61c84972c3e0c411adb569076d78">llvm::SampleProfileSummaryBuilder::addRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#aa77c45e5b6c316812092a7e8a1e30143">llvm::SampleProfileSummaryBuilder::computeSummaryForProfiles</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder/#a3d13ddc46d3f3bb1f92b191513008e5a">llvm::InstrProfSummaryBuilder::getSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#a1398195ea49701192f046b104172c2db">llvm::SampleProfileSummaryBuilder::getSummary</a>.</p>

</div>
</div>

### TotalCount {#a9f4b516c5122d851880c9e1f2cf59520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ProfileSummaryBuilder::TotalCount = 0</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<p>Referenced by <a href="#a28089a7d5a36c764dfe33f9f44b47d87">addCount</a>, <a href="#a0cf99f7dc09e330137cb10a3a42c12b3">computeDetailedSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder/#a3d13ddc46d3f3bb1f92b191513008e5a">llvm::InstrProfSummaryBuilder::getSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofilesummarybuilder/#a1398195ea49701192f046b104172c2db">llvm::SampleProfileSummaryBuilder::getSummary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CountFrequencies {#ae64eb18c094dc84d5d0394f71503c131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;uint64_t, uint32_t, std::greater&lt;uint64_t&gt; &gt; llvm::ProfileSummaryBuilder::CountFrequencies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We keep track of the number of times a count (block count or samples) appears in the profile.</p>


<p>The map is kept sorted in the descending order of counts.</p>


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>

</div>
</div>

### DetailedSummaryCutoffs {#adfb3edc6dbe5a1e371e77428e1985376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint32_t&gt; llvm::ProfileSummaryBuilder::DetailedSummaryCutoffs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getColdCountThreshold() {#ada15196a850a1aba577e73e5f29b14d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ProfileSummaryBuilder::getColdCountThreshold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ad9c07a9deae5d8875d689410d756168d">SummaryEntryVector</a> &amp; DS)</td>
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



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#a17e9acf4f2e3f412e4af1da184beac9a">ColdCountThreshold</a>, <a href="#a2dfdd1a19e144d5bda3e85eed520c036">getEntryForPercentile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a44e9929ed54f9a66fca59802c657c629">llvm::ProfileSummaryColdCount</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9643b788b4bd56054af2148a53cafe0d">llvm::ProfileSummaryCutoffCold</a>.</p>

</div>
</div>

### getEntryForPercentile() {#a2dfdd1a19e144d5bda3e85eed520c036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ProfileSummaryEntry &amp; ProfileSummaryBuilder::getEntryForPercentile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ad9c07a9deae5d8875d689410d756168d">SummaryEntryVector</a> &amp; DS, uint64_t Percentile)</td>
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

<p>Find the summary entry for a desired percentile of counts.</p>

<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a327a399b9f6ef414a29ddeffba934d26">llvm::partition_point</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#ada15196a850a1aba577e73e5f29b14d9">getColdCountThreshold</a> and <a href="#ad9f81ccf878be56999d549123f628a9a">getHotCountThreshold</a>.</p>

</div>
</div>

### getHotCountThreshold() {#ad9f81ccf878be56999d549123f628a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ProfileSummaryBuilder::getHotCountThreshold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ad9c07a9deae5d8875d689410d756168d">SummaryEntryVector</a> &amp; DS)</td>
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



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a>.</p>


<p>References <a href="#a2dfdd1a19e144d5bda3e85eed520c036">getEntryForPercentile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8c5449d8525fb94dfca2cde6ae665d9">llvm::ProfileSummaryCutoffHot</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a25ffc729a5833631efdbd68b2b6ba6ff">llvm::ProfileSummaryHotCount</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### DefaultCutoffs {#a9b2e51220aabb88a132d3bc8fbdf5a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ArrayRef&lt; uint32_t &gt; ProfileSummaryBuilder::DefaultCutoffs</td>
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

<p>A vector of useful cutoff values for detailed summary.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    <a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp/#ab329d892d13639442737fe6ffea4b41f">DefaultCutoffsData</a>
</div>
</dd>
</dl>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a862a85fc052e3da0f7109bc54ef4998d">llvm::sampleprof::SampleProfileReader::computeSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a4f8b2ab39ae70cd859c323fd97219c23">llvm::sampleprof::SampleProfileWriter::computeSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofflatteningpass/#a13390fcce3ec8b52ef55488e967081c5">llvm::PGOCtxProfFlatteningPass::run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
