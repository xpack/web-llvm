---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/mc/mcsubtargetinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MCSubtargetInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">llvm/MC/MCInstrItineraries.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">llvm/MC/MCSchedule.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">llvm/TargetParser/SubtargetFeature.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstring&gt;
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a08e140d603b53c440c54cffc85131c8f">Find</a> (StringRef S, ArrayRef&lt; T &gt; A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find KV in array using binary search. <a href="#a08e140d603b53c440c54cffc85131c8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09e4ddb5c9eead1f368615b3bde65f92">SetImpliedBits</a> (FeatureBitset &amp;Bits, const FeatureBitset &amp;Implies, ArrayRef&lt; SubtargetFeatureKV &gt; FeatureTable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each feature that is (transitively) implied by this feature, set it. <a href="#a09e4ddb5c9eead1f368615b3bde65f92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad95f670b9a1cbb21ad61a831fa26a2ce">ClearImpliedBits</a> (FeatureBitset &amp;Bits, unsigned Value, ArrayRef&lt; SubtargetFeatureKV &gt; FeatureTable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each feature that (transitively) implies this feature, clear it. <a href="#ad95f670b9a1cbb21ad61a831fa26a2ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00ea531f15b6ca7bac68acbd9e89082d">ApplyFeatureFlag</a> (FeatureBitset &amp;Bits, StringRef Feature, ArrayRef&lt; SubtargetFeatureKV &gt; FeatureTable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2a65437d3d68ce46ac3d9658ef80944">getLongestEntryLength</a> (ArrayRef&lt; SubtargetFeatureKV &gt; Table)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the length of the longest entry in the table. <a href="#aa2a65437d3d68ce46ac3d9658ef80944">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a792809b6b4e181e7d2204a400a457478">getLongestEntryLength</a> (ArrayRef&lt; StringRef &gt; Table)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ca03d80394915099159a13786e8291">Help</a> (ArrayRef&lt; StringRef &gt; CPUNames, ArrayRef&lt; SubtargetFeatureKV &gt; FeatTable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Display help for feature and mcpu choices. <a href="#a65ca03d80394915099159a13786e8291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84643128c35738cb6dedcb19c0a0d712">cpuHelp</a> (ArrayRef&lt; StringRef &gt; CPUNames)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Display help for mcpu choices only. <a href="#a84643128c35738cb6dedcb19c0a0d712">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedfa5e387d929b78090c06db5e0965e2">getFeatures</a> (MCSubtargetInfo &amp;STI, StringRef CPU, StringRef TuneCPU, StringRef FS, ArrayRef&lt; StringRef &gt; ProcNames, ArrayRef&lt; SubtargetSubTypeKV &gt; ProcDesc, ArrayRef&lt; SubtargetFeatureKV &gt; ProcFeatures)</td>
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


<div class="doxySectionDef">

## Functions

### ApplyFeatureFlag() {#a00ea531f15b6ca7bac68acbd9e89082d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ApplyFeatureFlag (<a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; Bits, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Feature, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv">SubtargetFeatureKV</a> &gt; FeatureTable)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad95f670b9a1cbb21ad61a831fa26a2ce">ClearImpliedBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a08e140d603b53c440c54cffc85131c8f">Find</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitarray/#ac4a0360586ccc1be7d8ec4e824778e1a">llvm::FeatureBitArray::getAsBitset</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a8a75c4defaf794fb1baf8afe140c0fe7">llvm::SubtargetFeatures::hasFlag</a>, <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv/#aa8238dd9dd2289c37c52823f01dfe460">llvm::SubtargetFeatureKV::Implies</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#ae07a5960fad31a5e146cb9d81dd15b47">llvm::SubtargetFeatures::isEnabled</a>, <a href="#a09e4ddb5c9eead1f368615b3bde65f92">SetImpliedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a8de4cf7f3a21b57333330349f1f32ff3">llvm::SubtargetFeatures::StripFlag</a> and <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv/#a7052536ef4db759fa568ba0541e6170e">llvm::SubtargetFeatureKV::Value</a>.</p>


<p>Referenced by <a href="#aedfa5e387d929b78090c06db5e0965e2">getFeatures</a>.</p>

</div>
</div>

### ClearImpliedBits() {#ad95f670b9a1cbb21ad61a831fa26a2ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClearImpliedBits (<a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; Bits, unsigned Value, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv">SubtargetFeatureKV</a> &gt; FeatureTable)</td>
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

<p>For each feature that (transitively) implies this feature, clear it.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>Reference <a href="#ad95f670b9a1cbb21ad61a831fa26a2ce">ClearImpliedBits</a>.</p>


<p>Referenced by <a href="#a00ea531f15b6ca7bac68acbd9e89082d">ApplyFeatureFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af4b8dd4ace194f4d2fd90bc1c7cc9e61">llvm::MCSubtargetInfo::ClearFeatureBitsTransitively</a>, <a href="#ad95f670b9a1cbb21ad61a831fa26a2ce">ClearImpliedBits</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a2624192c54a92722351fa791af3e862d">llvm::MCSubtargetInfo::ToggleFeature</a>.</p>

</div>
</div>

### cpuHelp() {#a84643128c35738cb6dedcb19c0a0d712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void cpuHelp (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; CPUNames)</td>
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

<p>Display help for mcpu choices only.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>.</p>


<p>Referenced by <a href="#aedfa5e387d929b78090c06db5e0965e2">getFeatures</a>.</p>

</div>
</div>

### Find() {#a08e140d603b53c440c54cffc85131c8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * Find (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; A)</td>
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

<p>Find KV in array using binary search.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a574dd51b4e96c2754eaea0e457c6f909">llvm::fuzzerop::anyAggregateType</a>, <a href="#a00ea531f15b6ca7bac68acbd9e89082d">ApplyFeatureFlag</a>, <a href="#aedfa5e387d929b78090c06db5e0965e2">getFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a2eddfb1a986d95b7f9e8e0988f72960c">llvm::MCSubtargetInfo::getSchedModelForCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#af383e0dc7e81bbf2e0583590dd9a4066">llvm::logicalview::LVCodeViewReader::isSystemEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a8e5c4577c64728c435eca5f4f7e163ab">replaceTargetsFromPHINode</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a2624192c54a92722351fa791af3e862d">llvm::MCSubtargetInfo::ToggleFeature</a>.</p>

</div>
</div>

### getFeatures() {#aedfa5e387d929b78090c06db5e0965e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset getFeatures (<a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; ProcNames, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetsubtypekv">SubtargetSubTypeKV</a> &gt; ProcDesc, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv">SubtargetFeatureKV</a> &gt; ProcFeatures)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>References <a href="#a00ea531f15b6ca7bac68acbd9e89082d">ApplyFeatureFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a84643128c35738cb6dedcb19c0a0d712">cpuHelp</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a08e140d603b53c440c54cffc85131c8f">Find</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitarray/#ac4a0360586ccc1be7d8ec4e824778e1a">llvm::FeatureBitArray::getAsBitset</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a39a9e8ebdc3fdfb710357fdb5e724abe">llvm::SubtargetFeatures::getFeatures</a>, <a href="#a65ca03d80394915099159a13786e8291">Help</a>, <a href="/web-llvm/docs/api/structs/llvm/subtargetsubtypekv/#a81f7413b246b670568e35061dc0b9f0c">llvm::SubtargetSubTypeKV::Implies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a>, <a href="#a09e4ddb5c9eead1f368615b3bde65f92">SetImpliedBits</a> and <a href="/web-llvm/docs/api/structs/llvm/subtargetsubtypekv/#a8ebb04a577050aa4baab2d26fe977777">llvm::SubtargetSubTypeKV::TuneImplies</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#adea593fdfefa11ea2aa7ed07d9df6155">llvm::MCSubtargetInfo::InitMCProcessorInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#ac717fb0e66df93c662f97cc56de7d1f3">llvm::MCSubtargetInfo::setDefaultFeatures</a>.</p>

</div>
</div>

### getLongestEntryLength() {#aa2a65437d3d68ce46ac3d9658ef80944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t getLongestEntryLength (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv">SubtargetFeatureKV</a> &gt; Table)</td>
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

<p>Return the length of the longest entry in the table.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a65ca03d80394915099159a13786e8291">Help</a>.</p>

</div>
</div>

### getLongestEntryLength() {#a792809b6b4e181e7d2204a400a457478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t getLongestEntryLength (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Table)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### Help() {#a65ca03d80394915099159a13786e8291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Help (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; CPUNames, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv">SubtargetFeatureKV</a> &gt; FeatTable)</td>
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

<p>Display help for feature and mcpu choices.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a> and <a href="#aa2a65437d3d68ce46ac3d9658ef80944">getLongestEntryLength</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/cl/extrahelp/#ae3207bcbcbb8e0c039027d44427240fa">llvm::cl::extrahelp::extrahelp</a> and <a href="#aedfa5e387d929b78090c06db5e0965e2">getFeatures</a>.</p>

</div>
</div>

### SetImpliedBits() {#a09e4ddb5c9eead1f368615b3bde65f92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SetImpliedBits (<a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; Bits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; Implies, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv">SubtargetFeatureKV</a> &gt; FeatureTable)</td>
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

<p>For each feature that is (transitively) implied by this feature, set it.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp">MCSubtargetInfo.cpp</a>.</p>


<p>References <a href="#a09e4ddb5c9eead1f368615b3bde65f92">SetImpliedBits</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>


<p>Referenced by <a href="#a00ea531f15b6ca7bac68acbd9e89082d">ApplyFeatureFlag</a>, <a href="#aedfa5e387d929b78090c06db5e0965e2">getFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a930d94c27661f22a8f6959e3cab4ffda">llvm::MCSubtargetInfo::SetFeatureBitsTransitively</a>, <a href="#a09e4ddb5c9eead1f368615b3bde65f92">SetImpliedBits</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a2624192c54a92722351fa791af3e862d">llvm::MCSubtargetInfo::ToggleFeature</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
