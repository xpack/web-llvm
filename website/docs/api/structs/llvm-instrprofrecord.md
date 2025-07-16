---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/instrprofrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `InstrProfRecord` Struct Reference

<p>Profiling information for a single function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::InstrProfRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">llvm/ProfileData/InstrProf.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord">NamedInstrProfRecord</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc7189fed34f55e5965dd279d9019094">ValueProfData</a> = std::array&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord">InstrProfValueSiteRecord</a> &gt;, IPVK_Last - IPVK_First+1 &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CountPseudoKind { <a href="#a69bdbaedb4ae6b233e5eccac5ebc2d77">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PseudoCountVal { <a href="#ae4e107f867d8effc45b74925aab32f40">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12b586f23ffc8a40ba78dba68cb4d896">InstrProfRecord</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31c8b08ab5e7a751a9dafc9a08791c7c">InstrProfRecord</a> (std::vector&lt; uint64_t &gt; Counts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3d6a31e78bceed4281586817df2ec4c">InstrProfRecord</a> (std::vector&lt; uint64_t &gt; Counts, std::vector&lt; uint8_t &gt; BitmapBytes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52f5cc092ac16d36eaee7ef92b1be254">InstrProfRecord</a> (InstrProfRecord &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c66101d7d856130170d3e042a217a73">InstrProfRecord</a> (const InstrProfRecord &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af47d10304e723c04fe6b9eb923c61be2">operator=</a> (InstrProfRecord &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78e1500f50ce9da871c8274f814499b7">operator=</a> (const InstrProfRecord &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a414bc35f56cbb06be9c8261256d7f180">getNumValueKinds</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of value profile kinds with non-zero number of profile sites. <a href="#a414bc35f56cbb06be9c8261256d7f180">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dd06bc69eacd72f8824db216b46adf6">getNumValueSites</a> (uint32_t ValueKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of instrumented sites for ValueKind. <a href="#a3dd06bc69eacd72f8824db216b46adf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5417f0221bfe56145cf78606995c5ec5">getNumValueData</a> (uint32_t ValueKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the total number of ValueData for ValueKind. <a href="#a5417f0221bfe56145cf78606995c5ec5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; InstrProfValueData &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23dd46152177b0ad29e6f66ab53c3867">getValueArrayForSite</a> (uint32_t ValueKind, uint32_t Site) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the array of profiled values at <span class="doxyComputerOutput">Site</span>. <a href="#a23dd46152177b0ad29e6f66ab53c3867">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac52492b11034bc3e83adc6fcf29cd9c1">reserveSites</a> (uint32_t ValueKind, uint32_t NumValueSites)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserve space for NumValueSites sites. <a href="#ac52492b11034bc3e83adc6fcf29cd9c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a661ee64d4ed40dfc71b7a2bd4d2fd4a2">addValueData</a> (uint32_t ValueKind, uint32_t Site, ArrayRef&lt; InstrProfValueData &gt; VData, InstrProfSymtab *SymTab)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add ValueData for ValueKind at value Site. <a href="#a661ee64d4ed40dfc71b7a2bd4d2fd4a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55de76ee38e5ab581cba99151df218aa">merge</a> (InstrProfRecord &amp;Other, uint64_t Weight, function_ref&lt; void(instrprof_error)&gt; Warn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge the counts in <span class="doxyComputerOutput">Other</span> into this one. <a href="#a55de76ee38e5ab581cba99151df218aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd434b7b22d9c00ba33a833940c91601">scale</a> (uint64_t N, uint64_t D, function_ref&lt; void(instrprof_error)&gt; Warn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scale up profile counts (including value profile data) by a factor of (N / D). <a href="#afd434b7b22d9c00ba33a833940c91601">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaffd59cff8639b87762035a169b7be0">sortValueData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sort value profile data (per site) by count. <a href="#adaffd59cff8639b87762035a169b7be0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5ac557e168121d4022bc30c2617a2ea">Clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear value data entries and edge counters. <a href="#af5ac557e168121d4022bc30c2617a2ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a872c64309a8f35d73ba95e4c811e0fd4">clearValueData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear value data entries. <a href="#a872c64309a8f35d73ba95e4c811e0fd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a394f37e06a6020180554dbe4a23bb3b8">accumulateCounts</a> (CountSumOrPercent &amp;Sum) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the sums of all counts and store in Sum. <a href="#a394f37e06a6020180554dbe4a23bb3b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9be35ce19db0a3b6de2350b5c2820f3">overlap</a> (InstrProfRecord &amp;Other, OverlapStats &amp;Overlap, OverlapStats &amp;FuncLevelOverlap, uint64_t ValueCutoff)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the overlap b/w this IntrprofRecord and Other. <a href="#ac9be35ce19db0a3b6de2350b5c2820f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a078cadc22c8d2b4f3397e5673ca2909f">overlapValueProfData</a> (uint32_t ValueKind, InstrProfRecord &amp;Src, OverlapStats &amp;Overlap, OverlapStats &amp;FuncLevelOverlap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the overlap of value profile counts. <a href="#a078cadc22c8d2b4f3397e5673ca2909f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a69bdbaedb4ae6b233e5eccac5ebc2d77">CountPseudoKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f346f3e1d5674bdebde0b5017deec68">getCountPseudoKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aaadc44395e18b6db1b18bc4fe37f1e">setPseudoCount</a> (CountPseudoKind Kind)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord">InstrProfValueSiteRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a773fc9fbd244efa5ce6f317c8822a504">getValueSitesForKind</a> (uint32_t ValueKind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord">InstrProfValueSiteRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae7443aa027658b01f84e146d51d4aa5">getValueSitesForKind</a> (uint32_t ValueKind) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord">InstrProfValueSiteRecord</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03ac15c564ce7603eac88b8774c22b6b">getOrCreateValueSitesForKind</a> (uint32_t ValueKind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae13673d1db3238df44506d201a6cb519">remapValue</a> (uint64_t Value, uint32_t ValueKind, InstrProfSymtab *SymTab)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26f70c4afc6fa2445617609a164bb6f4">mergeValueProfData</a> (uint32_t ValkeKind, InstrProfRecord &amp;Src, uint64_t Weight, function_ref&lt; void(instrprof_error)&gt; Warn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb4eb4cbe1f797145acb91b9ad852027">scaleValueProfData</a> (uint32_t ValueKind, uint64_t N, uint64_t D, function_ref&lt; void(instrprof_error)&gt; Warn)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b5488b65ab76c49ab7dd16115c23f56">Counts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae04bac786c8ba17e3fcd332e26f4e257">BitmapBytes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; ValueProfData &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5562bf1557baeab4ac79071047e6a71a">ValueData</a></td>
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

<p>Profiling information for a single function.</p>

<p>Definition at line 836 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ValueProfData {#abc7189fed34f55e5965dd279d9019094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InstrProfRecord::ValueProfData =  std::array&lt;std::vector&lt;InstrProfValueSiteRecord&gt;,
                                   IPVK_Last - IPVK_First + 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 950 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### CountPseudoKind {#a69bdbaedb4ae6b233e5eccac5ebc2d77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::InstrProfRecord::CountPseudoKind </td>
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
<td class="doxyEnumItemName">NotPseudo<a id="a69bdbaedb4ae6b233e5eccac5ebc2d77ac46600297a1a6f13ed709e33fcc7ae4e"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PseudoHot<a id="a69bdbaedb4ae6b233e5eccac5ebc2d77af66fe9759d6bc934e927ced864653318"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PseudoWarm<a id="a69bdbaedb4ae6b233e5eccac5ebc2d77a6f07c8523bab3d360ba4295189f40129"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### PseudoCountVal {#ae4e107f867d8effc45b74925aab32f40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::InstrProfRecord::PseudoCountVal </td>
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
<td class="doxyEnumItemName">HotFunctionVal<a id="ae4e107f867d8effc45b74925aab32f40a6a2a0e8e98dbda188814dfeb294aa0f3"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WarmFunctionVal<a id="ae4e107f867d8effc45b74925aab32f40a435b6031a972b82f2a143416134431e4"></a></td>
<td class="doxyEnumItemDescription"> (= -2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InstrProfRecord() {#a12b586f23ffc8a40ba78dba68cb4d896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfRecord::InstrProfRecord ()</td>
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



<p>Definition at line 840 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a8c66101d7d856130170d3e042a217a73">InstrProfRecord</a>, <a href="#a52f5cc092ac16d36eaee7ef92b1be254">InstrProfRecord</a>, <a href="#a55de76ee38e5ab581cba99151df218aa">merge</a>, <a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord/#a6721f7e25aed544f93affc2b01d1b22f">llvm::NamedInstrProfRecord::NamedInstrProfRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord/#a71b5d63bc3d5d70a64378bb067d28b6a">llvm::NamedInstrProfRecord::NamedInstrProfRecord</a>, <a href="#a78e1500f50ce9da871c8274f814499b7">operator=</a>, <a href="#af47d10304e723c04fe6b9eb923c61be2">operator=</a>, <a href="#ac9be35ce19db0a3b6de2350b5c2820f3">overlap</a> and <a href="#a078cadc22c8d2b4f3397e5673ca2909f">overlapValueProfData</a>.</p>

</div>
</div>

### InstrProfRecord() {#a31c8b08ab5e7a751a9dafc9a08791c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfRecord::InstrProfRecord (std::vector&lt; uint64_t &gt; Counts)</td>
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



<p>Definition at line 841 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#a1b5488b65ab76c49ab7dd16115c23f56">Counts</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### InstrProfRecord() {#ac3d6a31e78bceed4281586817df2ec4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfRecord::InstrProfRecord (std::vector&lt; uint64_t &gt; Counts, std::vector&lt; uint8_t &gt; BitmapBytes)</td>
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



<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#ae04bac786c8ba17e3fcd332e26f4e257">BitmapBytes</a>, <a href="#a1b5488b65ab76c49ab7dd16115c23f56">Counts</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### InstrProfRecord() {#a52f5cc092ac16d36eaee7ef92b1be254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfRecord::InstrProfRecord (<a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp;&amp;)</td>
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



<p>Definition at line 845 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Reference <a href="#a12b586f23ffc8a40ba78dba68cb4d896">InstrProfRecord</a>.</p>

</div>
</div>

### InstrProfRecord() {#a8c66101d7d856130170d3e042a217a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfRecord::InstrProfRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp; RHS)</td>
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



<p>Definition at line 846 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#ae04bac786c8ba17e3fcd332e26f4e257">BitmapBytes</a>, <a href="#a1b5488b65ab76c49ab7dd16115c23f56">Counts</a>, <a href="#a12b586f23ffc8a40ba78dba68cb4d896">InstrProfRecord</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#af47d10304e723c04fe6b9eb923c61be2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfRecord &amp; llvm::InstrProfRecord::operator= (<a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp;&amp;)</td>
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



<p>Definition at line 851 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Reference <a href="#a12b586f23ffc8a40ba78dba68cb4d896">InstrProfRecord</a>.</p>

</div>
</div>

### operator=() {#a78e1500f50ce9da871c8274f814499b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfRecord &amp; llvm::InstrProfRecord::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp; RHS)</td>
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



<p>Definition at line 852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#ae04bac786c8ba17e3fcd332e26f4e257">BitmapBytes</a>, <a href="#a1b5488b65ab76c49ab7dd16115c23f56">Counts</a>, <a href="#a12b586f23ffc8a40ba78dba68cb4d896">InstrProfRecord</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### accumulateCounts() {#a394f37e06a6020180554dbe4a23bb3b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecord::accumulateCounts (<a href="/web-llvm/docs/api/structs/llvm/countsumorpercent">CountSumOrPercent</a> &amp; Sum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the sums of all counts and store in Sum.</p>

<p>Declaration at line 914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 746 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a1b5488b65ab76c49ab7dd16115c23f56">Counts</a>, <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent/#aa86b18bf848839782dee252ea6871d00">llvm::CountSumOrPercent::CountSum</a>, <a href="#a3dd06bc69eacd72f8824db216b46adf6">getNumValueSites</a>, <a href="#a23dd46152177b0ad29e6f66ab53c3867">getValueArrayForSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent/#ac6ee8e5f865571103ec74dd37837b70e">llvm::CountSumOrPercent::NumEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f87322d8a42a0457f829566a0d48037">llvm::NumValueSites</a> and <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent/#aa65910538ca9fe224414a15b68bdcf33">llvm::CountSumOrPercent::ValueCounts</a>.</p>


<p>Referenced by <a href="#ac9be35ce19db0a3b6de2350b5c2820f3">overlap</a>.</p>

</div>
</div>

### addValueData() {#a661ee64d4ed40dfc71b7a2bd4d2fd4a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecord::addValueData (uint32_t ValueKind, uint32_t Site, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; InstrProfValueData &gt; VData, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> * SymTab)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add ValueData for ValueKind at value Site.</p>


<p>We do not support adding sites out of order. Site must go up from 0 one by one.</p>


<p>Declaration at line 884 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 1019 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### Clear() {#af5ac557e168121d4022bc30c2617a2ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecord::Clear ()</td>
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

<p>Clear value data entries and edge counters.</p>

<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#a872c64309a8f35d73ba95e4c811e0fd4">clearValueData</a> and <a href="#a1b5488b65ab76c49ab7dd16115c23f56">Counts</a>.</p>

</div>
</div>

### clearValueData() {#a872c64309a8f35d73ba95e4c811e0fd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecord::clearValueData ()</td>
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

<p>Clear value data entries.</p>

<p>Definition at line 911 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#af5ac557e168121d4022bc30c2617a2ea">Clear</a>.</p>

</div>
</div>

### getCountPseudoKind() {#a2f346f3e1d5674bdebde0b5017deec68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CountPseudoKind llvm::InstrProfRecord::getCountPseudoKind ()</td>
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



<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#a1b5488b65ab76c49ab7dd16115c23f56">Counts</a>, <a href="#ae4e107f867d8effc45b74925aab32f40a6a2a0e8e98dbda188814dfeb294aa0f3">HotFunctionVal</a>, <a href="#a69bdbaedb4ae6b233e5eccac5ebc2d77ac46600297a1a6f13ed709e33fcc7ae4e">NotPseudo</a>, <a href="#a69bdbaedb4ae6b233e5eccac5ebc2d77af66fe9759d6bc934e927ced864653318">PseudoHot</a>, <a href="#a69bdbaedb4ae6b233e5eccac5ebc2d77a6f07c8523bab3d360ba4295189f40129">PseudoWarm</a> and <a href="#ae4e107f867d8effc45b74925aab32f40a435b6031a972b82f2a143416134431e4">WarmFunctionVal</a>.</p>


<p>Referenced by <a href="#a55de76ee38e5ab581cba99151df218aa">merge</a>.</p>

</div>
</div>

### getNumValueData() {#a5417f0221bfe56145cf78606995c5ec5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::InstrProfRecord::getNumValueData (uint32_t ValueKind)</td>
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

<p>Return the total number of ValueData for ValueKind.</p>

<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getNumValueKinds() {#a414bc35f56cbb06be9c8261256d7f180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::InstrProfRecord::getNumValueKinds ()</td>
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

<p>Return the number of value profile kinds with non-zero number of profile sites.</p>

<p>Definition at line 868 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### getNumValueSites() {#a3dd06bc69eacd72f8824db216b46adf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::InstrProfRecord::getNumValueSites (uint32_t ValueKind)</td>
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

<p>Return the number of instrumented sites for ValueKind.</p>

<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a394f37e06a6020180554dbe4a23bb3b8">accumulateCounts</a>, <a href="#ac9be35ce19db0a3b6de2350b5c2820f3">overlap</a> and <a href="#a078cadc22c8d2b4f3397e5673ca2909f">overlapValueProfData</a>.</p>

</div>
</div>

### getValueArrayForSite() {#a23dd46152177b0ad29e6f66ab53c3867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; InstrProfValueData &gt; llvm::InstrProfRecord::getValueArrayForSite (uint32_t ValueKind, uint32_t Site)</td>
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

<p>Return the array of profiled values at <span class="doxyComputerOutput">Site</span>.</p>

<p>Definition at line 876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a394f37e06a6020180554dbe4a23bb3b8">accumulateCounts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a68ee9c22fcc77e40d4ae44e5b37c7998">llvm::annotateValueSite</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad16f59f62e543181c31fd9da8af2487c">llvm::getNumValueDataForSiteInstrProf</a>.</p>

</div>
</div>

### merge() {#a55de76ee38e5ab581cba99151df218aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecord::merge (<a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp; Other, uint64_t Weight, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086">instrprof_error</a>)&gt; Warn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge the counts in <span class="doxyComputerOutput">Other</span> into this one.</p>


<p>Optionally scale merged counts by <span class="doxyComputerOutput">Weight</span>.</p>


<p>Declaration at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 924 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086ae64e9d9acbb749af53a7768b8c82aac5">llvm::bitmap_mismatch</a>, <a href="#ae04bac786c8ba17e3fcd332e26f4e257">BitmapBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086abe18c02041981276362cfe50d581110e">llvm::count_mismatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a5e8bae22cbd37f66c813d8a3749bda1c">llvm::counter_overflow</a>, <a href="#a1b5488b65ab76c49ab7dd16115c23f56">Counts</a>, <a href="#a2f346f3e1d5674bdebde0b5017deec68">getCountPseudoKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5751c9ba595d25bf69ea8b197ce8dd78">llvm::getInstrMaxCountValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a12b586f23ffc8a40ba78dba68cb4d896">InstrProfRecord</a>, <a href="#a69bdbaedb4ae6b233e5eccac5ebc2d77ac46600297a1a6f13ed709e33fcc7ae4e">NotPseudo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a69bdbaedb4ae6b233e5eccac5ebc2d77af66fe9759d6bc934e927ced864653318">PseudoHot</a>, <a href="#a69bdbaedb4ae6b233e5eccac5ebc2d77a6f07c8523bab3d360ba4295189f40129">PseudoWarm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84836a719cdf82a516d556ae66cc8dc0">llvm::SaturatingMultiplyAdd</a> and <a href="#a4aaadc44395e18b6db1b18bc4fe37f1e">setPseudoCount</a>.</p>

</div>
</div>

### overlap() {#ac9be35ce19db0a3b6de2350b5c2820f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecord::overlap (<a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp; Other, <a href="/web-llvm/docs/api/structs/llvm/overlapstats">OverlapStats</a> &amp; Overlap, <a href="/web-llvm/docs/api/structs/llvm/overlapstats">OverlapStats</a> &amp; FuncLevelOverlap, uint64_t ValueCutoff)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the overlap b/w this IntrprofRecord and Other.</p>

<p>Declaration at line 917 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 813 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="#a394f37e06a6020180554dbe4a23bb3b8">accumulateCounts</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a0890bbfe709e212efce84003c8fb9469">llvm::OverlapStats::addOneMismatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a439f69d2f637d33a29889fef95c7f0ec">llvm::OverlapStats::Base</a>, <a href="#a1b5488b65ab76c49ab7dd16115c23f56">Counts</a>, <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent/#aa86b18bf848839782dee252ea6871d00">llvm::CountSumOrPercent::CountSum</a>, <a href="#a3dd06bc69eacd72f8824db216b46adf6">getNumValueSites</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a12b586f23ffc8a40ba78dba68cb4d896">InstrProfRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent/#ac6ee8e5f865571103ec74dd37837b70e">llvm::CountSumOrPercent::NumEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a3427e5f987ace470105d11ad6c7a89a1">llvm::OverlapStats::Overlap</a>, <a href="#a078cadc22c8d2b4f3397e5673ca2909f">overlapValueProfData</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a0e9a9f58836064e628e42236939edbeb">llvm::OverlapStats::score</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#aeacf37b436c25b1af9f22712417fef6c">llvm::OverlapStats::Test</a> and <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a4c54b81c583e348f8a4f01f3396537f1">llvm::OverlapStats::Valid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a2882c6d2a257083c160385fe493c0cf2">llvm::InstrProfWriter::overlapRecord</a> and <a href="#a078cadc22c8d2b4f3397e5673ca2909f">overlapValueProfData</a>.</p>

</div>
</div>

### overlapValueProfData() {#a078cadc22c8d2b4f3397e5673ca2909f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecord::overlapValueProfData (uint32_t ValueKind, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp; Src, <a href="/web-llvm/docs/api/structs/llvm/overlapstats">OverlapStats</a> &amp; Overlap, <a href="/web-llvm/docs/api/structs/llvm/overlapstats">OverlapStats</a> &amp; FuncLevelOverlap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the overlap of value profile counts.</p>

<p>Declaration at line 921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 795 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3dd06bc69eacd72f8824db216b46adf6">getNumValueSites</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a12b586f23ffc8a40ba78dba68cb4d896">InstrProfRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ac9be35ce19db0a3b6de2350b5c2820f3">overlap</a>.</p>


<p>Referenced by <a href="#ac9be35ce19db0a3b6de2350b5c2820f3">overlap</a>.</p>

</div>
</div>

### reserveSites() {#ac52492b11034bc3e83adc6fcf29cd9c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecord::reserveSites (uint32_t ValueKind, uint32_t NumValueSites)</td>
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

<p>Reserve space for NumValueSites sites.</p>

<p>Definition at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f87322d8a42a0457f829566a0d48037">llvm::NumValueSites</a>.</p>

</div>
</div>

### scale() {#afd434b7b22d9c00ba33a833940c91601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecord::scale (uint64_t N, uint64_t D, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086">instrprof_error</a>)&gt; Warn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scale up profile counts (including value profile data) by a factor of (N / D).</p>

<p>Declaration at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 987 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a5e8bae22cbd37f66c813d8a3749bda1c">llvm::counter_overflow</a>, <a href="#a1b5488b65ab76c49ab7dd16115c23f56">Counts</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5751c9ba595d25bf69ea8b197ce8dd78">llvm::getInstrMaxCountValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa6c35ac16c3c23e443f27a025d7a1597">llvm::SaturatingMultiply</a>.</p>

</div>
</div>

### setPseudoCount() {#a4aaadc44395e18b6db1b18bc4fe37f1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecord::setPseudoCount (<a href="#a69bdbaedb4ae6b233e5eccac5ebc2d77">CountPseudoKind</a> Kind)</td>
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



<p>Definition at line 942 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#a1b5488b65ab76c49ab7dd16115c23f56">Counts</a>, <a href="#ae4e107f867d8effc45b74925aab32f40a6a2a0e8e98dbda188814dfeb294aa0f3">HotFunctionVal</a>, <a href="#a69bdbaedb4ae6b233e5eccac5ebc2d77af66fe9759d6bc934e927ced864653318">PseudoHot</a>, <a href="#a69bdbaedb4ae6b233e5eccac5ebc2d77a6f07c8523bab3d360ba4295189f40129">PseudoWarm</a> and <a href="#ae4e107f867d8effc45b74925aab32f40a435b6031a972b82f2a143416134431e4">WarmFunctionVal</a>.</p>


<p>Referenced by <a href="#a55de76ee38e5ab581cba99151df218aa">merge</a>.</p>

</div>
</div>

### sortValueData() {#adaffd59cff8639b87762035a169b7be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecord::sortValueData ()</td>
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

<p>Sort value profile data (per site) by count.</p>

<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getOrCreateValueSitesForKind() {#a03ac15c564ce7603eac88b8774c22b6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; InstrProfValueSiteRecord &gt; &amp; llvm::InstrProfRecord::getOrCreateValueSitesForKind (uint32_t ValueKind)</td>
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



<p>Definition at line 974 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### getValueSitesForKind() {#a773fc9fbd244efa5ce6f317c8822a504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; InstrProfValueSiteRecord &gt; llvm::InstrProfRecord::getValueSitesForKind (uint32_t ValueKind)</td>
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



<p>Definition at line 955 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### getValueSitesForKind() {#aae7443aa027658b01f84e146d51d4aa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; InstrProfValueSiteRecord &gt; llvm::InstrProfRecord::getValueSitesForKind (uint32_t ValueKind)</td>
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



<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### mergeValueProfData() {#a26f70c4afc6fa2445617609a164bb6f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecord::mergeValueProfData (uint32_t ValkeKind, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp; Src, uint64_t Weight, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086">instrprof_error</a>)&gt; Warn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 988 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 905 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>

</div>
</div>

### remapValue() {#ae13673d1db3238df44506d201a6cb519}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::InstrProfRecord::remapValue (uint64_t Value, uint32_t ValueKind, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> * SymTab)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 983 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 1005 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>

</div>
</div>

### scaleValueProfData() {#aeb4eb4cbe1f797145acb91b9ad852027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecord::scaleValueProfData (uint32_t ValueKind, uint64_t N, uint64_t D, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086">instrprof_error</a>)&gt; Warn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 993 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BitmapBytes {#ae04bac786c8ba17e3fcd332e26f4e257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint8_t&gt; llvm::InstrProfRecord::BitmapBytes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofrecordwritertrait/#aeade4a99cac29eaa9bf39f2729f8d75f">llvm::InstrProfRecordWriterTrait::EmitData</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofrecordwritertrait/#a063fe524f591af6fc154088fe2feb92f">llvm::InstrProfRecordWriterTrait::EmitKeyDataLength</a>, <a href="#a8c66101d7d856130170d3e042a217a73">InstrProfRecord</a>, <a href="#ac3d6a31e78bceed4281586817df2ec4c">InstrProfRecord</a>, <a href="#a55de76ee38e5ab581cba99151df218aa">merge</a>, <a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord/#a71b5d63bc3d5d70a64378bb067d28b6a">llvm::NamedInstrProfRecord::NamedInstrProfRecord</a> and <a href="#a78e1500f50ce9da871c8274f814499b7">operator=</a>.</p>

</div>
</div>

### Counts {#a1b5488b65ab76c49ab7dd16115c23f56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint64_t&gt; llvm::InstrProfRecord::Counts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 837 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a394f37e06a6020180554dbe4a23bb3b8">accumulateCounts</a>, <a href="#af5ac557e168121d4022bc30c2617a2ea">Clear</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofrecordwritertrait/#aeade4a99cac29eaa9bf39f2729f8d75f">llvm::InstrProfRecordWriterTrait::EmitData</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofrecordwritertrait/#a063fe524f591af6fc154088fe2feb92f">llvm::InstrProfRecordWriterTrait::EmitKeyDataLength</a>, <a href="#a2f346f3e1d5674bdebde0b5017deec68">getCountPseudoKind</a>, <a href="#a8c66101d7d856130170d3e042a217a73">InstrProfRecord</a>, <a href="#a31c8b08ab5e7a751a9dafc9a08791c7c">InstrProfRecord</a>, <a href="#ac3d6a31e78bceed4281586817df2ec4c">InstrProfRecord</a>, <a href="#a55de76ee38e5ab581cba99151df218aa">merge</a>, <a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord/#a6721f7e25aed544f93affc2b01d1b22f">llvm::NamedInstrProfRecord::NamedInstrProfRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord/#a71b5d63bc3d5d70a64378bb067d28b6a">llvm::NamedInstrProfRecord::NamedInstrProfRecord</a>, <a href="#a78e1500f50ce9da871c8274f814499b7">operator=</a>, <a href="#ac9be35ce19db0a3b6de2350b5c2820f3">overlap</a>, <a href="#afd434b7b22d9c00ba33a833940c91601">scale</a> and <a href="#a4aaadc44395e18b6db1b18bc4fe37f1e">setPseudoCount</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ValueData {#a5562bf1557baeab4ac79071047e6a71a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ValueProfData&gt; llvm::InstrProfRecord::ValueData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
