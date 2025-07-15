---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/intervalmapoverlaps
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IntervalMapOverlaps` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/intervalmapoverlaps">IntervalMapOverlaps</a> - Iterate over the overlaps of mapped intervals in two IntervalMaps. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename MapA, typename MapB&gt;
class llvm::IntervalMapOverlaps&lt;MapA, MapB&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">llvm/ADT/IntervalMap.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd6669a1ede4f6b556409a4737c91c78">KeyType</a> = typename MapA::KeyType</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0384f5ce9a1a3e10b66a10349f6cea4d">Traits</a> = typename MapA::KeyTraits</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a57afb249460a361774661a77e49e1f41">IntervalMapOverlaps</a> (const MapA &amp;a, const MapB &amp;b)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/intervalmapoverlaps">IntervalMapOverlaps</a> - Create an iterator for the overlaps of a and b. <a href="#a57afb249460a361774661a77e49e1f41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapoverlaps">IntervalMapOverlaps</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a00504c874380f6ea16289f38068a81ce">operator++</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Preincrement - Move to the next overlap. <a href="#a00504c874380f6ea16289f38068a81ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad85fedf8fb1b786bf6ed0d3518790bae">valid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>valid - Return true if iterator is at an overlap. <a href="#ad85fedf8fb1b786bf6ed0d3518790bae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MapA::const_iterator &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a93ab390db4d538fdca9b2a7b1e36c554">a</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>a - access the left hand side in the overlap. <a href="#a93ab390db4d538fdca9b2a7b1e36c554">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MapB::const_iterator &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adeba65e06764f85677a5021735f3c9ff">b</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>b - access the right hand side in the overlap. <a href="#adeba65e06764f85677a5021735f3c9ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">KeyType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83b22db263330ef8539f68dcb01909a7">start</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>start - Beginning of the overlapping interval. <a href="#a83b22db263330ef8539f68dcb01909a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">KeyType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae54e21881ddbf5deb5044dbd07d59ff7">stop</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>stop - End of the overlapping interval. <a href="#ae54e21881ddbf5deb5044dbd07d59ff7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5720a7ad08cea2e6add75cc60595de16">skipA</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>skipA - Move to the next overlap that doesn't involve <a href="#a93ab390db4d538fdca9b2a7b1e36c554">a()</a>. <a href="#a5720a7ad08cea2e6add75cc60595de16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a40a00589246eced9934d7f52ed88d75e">skipB</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>skipB - Move to the next overlap that doesn't involve <a href="#adeba65e06764f85677a5021735f3c9ff">b()</a>. <a href="#a40a00589246eced9934d7f52ed88d75e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9b702a1f885add62ca0bb7dccaaab2c8">advanceTo</a> (KeyType x)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>advanceTo - Move to the first overlapping interval with stopLess(x, stop()). <a href="#a9b702a1f885add62ca0bb7dccaaab2c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac5775a16f000caf5c18fb7a1828db6d0">advance</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>advance - Move posA and posB forward until reaching an overlap, or until either meets end. <a href="#ac5775a16f000caf5c18fb7a1828db6d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">MapA::const_iterator</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2a66944d9f2da8a5216b5eebdc709f1a">posA</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MapA, typename MapB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">MapB::const_iterator</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2d267a8085f8d6add4a69fdcaf91a73b">posB</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/intervalmapoverlaps">IntervalMapOverlaps</a> - Iterate over the overlaps of mapped intervals in two IntervalMaps.</p>


<p>The maps may be different, but the KeyT and Traits types should be the same.</p>


<p>Typical uses:</p>


<ol class="doxyList" type="1">
<li>Test for overlap: bool overlap = IntervalMapOverlaps(a, b).<a href="#ad85fedf8fb1b786bf6ed0d3518790bae">valid()</a>;</li>
<li>Enumerate overlaps: for (<a href="/web-llvm/docs/api/classes/llvm/intervalmapoverlaps">IntervalMapOverlaps</a> <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I(a, b)</a>; I.valid() ; ++I) { ... }</li>
</ol>

<p>Definition at line 2110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### KeyType {#acd6669a1ede4f6b556409a4737c91c78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::KeyType =  typename MapA::KeyType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### Traits {#a0384f5ce9a1a3e10b66a10349f6cea4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::Traits =  typename MapA::KeyTraits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IntervalMapOverlaps() {#a57afb249460a361774661a77e49e1f41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::IntervalMapOverlaps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MapA &amp; a, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MapB &amp; b)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/intervalmapoverlaps">IntervalMapOverlaps</a> - Create an iterator for the overlaps of a and b.</p>

<p>Definition at line 2152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#a93ab390db4d538fdca9b2a7b1e36c554">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::a</a>, <a href="#adeba65e06764f85677a5021735f3c9ff">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="#a83b22db263330ef8539f68dcb01909a7">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::start</a> and <a href="#ad85fedf8fb1b786bf6ed0d3518790bae">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::valid</a>.</p>


<p>Referenced by <a href="#a00504c874380f6ea16289f38068a81ce">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::operator++</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator++() {#a00504c874380f6ea16289f38068a81ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntervalMapOverlaps &amp; llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::operator++ ()</td>
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

<p>Preincrement - Move to the next overlap.</p>

<p>Definition at line 2194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#a57afb249460a361774661a77e49e1f41">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::IntervalMapOverlaps</a>, <a href="#a5720a7ad08cea2e6add75cc60595de16">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::skipA</a> and <a href="#a40a00589246eced9934d7f52ed88d75e">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::skipB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### a() {#a93ab390db4d538fdca9b2a7b1e36c554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MapA::const_iterator &amp; llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::a ()</td>
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

<p>a - access the left hand side in the overlap.</p>

<p>Definition at line 2162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a57afb249460a361774661a77e49e1f41">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::IntervalMapOverlaps</a>, <a href="#a83b22db263330ef8539f68dcb01909a7">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::start</a> and <a href="#ae54e21881ddbf5deb5044dbd07d59ff7">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::stop</a>.</p>

</div>
</div>

### advanceTo() {#a9b702a1f885add62ca0bb7dccaaab2c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::advanceTo (KeyType x)</td>
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

<p>advanceTo - Move to the first overlapping interval with stopLess(x, stop()).</p>

<p>Definition at line 2205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#ad85fedf8fb1b786bf6ed0d3518790bae">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::valid</a>.</p>

</div>
</div>

### b() {#adeba65e06764f85677a5021735f3c9ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MapB::const_iterator &amp; llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::b ()</td>
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

<p>b - access the right hand side in the overlap.</p>

<p>Definition at line 2165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a57afb249460a361774661a77e49e1f41">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::IntervalMapOverlaps</a>, <a href="#a83b22db263330ef8539f68dcb01909a7">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::start</a> and <a href="#ae54e21881ddbf5deb5044dbd07d59ff7">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::stop</a>.</p>

</div>
</div>

### skipA() {#a5720a7ad08cea2e6add75cc60595de16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::skipA ()</td>
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

<p>skipA - Move to the next overlap that doesn't involve <a href="#a93ab390db4d538fdca9b2a7b1e36c554">a()</a>.</p>

<p>Definition at line 2182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a00504c874380f6ea16289f38068a81ce">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::operator++</a>.</p>

</div>
</div>

### skipB() {#a40a00589246eced9934d7f52ed88d75e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::skipB ()</td>
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

<p>skipB - Move to the next overlap that doesn't involve <a href="#adeba65e06764f85677a5021735f3c9ff">b()</a>.</p>

<p>Definition at line 2188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a00504c874380f6ea16289f38068a81ce">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::operator++</a>.</p>

</div>
</div>

### start() {#a83b22db263330ef8539f68dcb01909a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KeyType llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::start ()</td>
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

<p>start - Beginning of the overlapping interval.</p>

<p>Definition at line 2168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#a93ab390db4d538fdca9b2a7b1e36c554">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::a</a> and <a href="#adeba65e06764f85677a5021735f3c9ff">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::b</a>.</p>


<p>Referenced by <a href="#a57afb249460a361774661a77e49e1f41">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::IntervalMapOverlaps</a>.</p>

</div>
</div>

### stop() {#ae54e21881ddbf5deb5044dbd07d59ff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KeyType llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::stop ()</td>
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

<p>stop - End of the overlapping interval.</p>

<p>Definition at line 2175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#a93ab390db4d538fdca9b2a7b1e36c554">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::a</a> and <a href="#adeba65e06764f85677a5021735f3c9ff">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::b</a>.</p>

</div>
</div>

### valid() {#ad85fedf8fb1b786bf6ed0d3518790bae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::valid ()</td>
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

<p>valid - Return true if iterator is at an overlap.</p>

<p>Definition at line 2157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a9b702a1f885add62ca0bb7dccaaab2c8">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::advanceTo</a> and <a href="#a57afb249460a361774661a77e49e1f41">llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::IntervalMapOverlaps</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### advance() {#ac5775a16f000caf5c18fb7a1828db6d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::advance ()</td>
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

<p>advance - Move posA and posB forward until reaching an overlap, or until either meets end.</p>


<p>Don't move the iterators if they are already overlapping.</p>


<p>Definition at line 2120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### posA {#a2a66944d9f2da8a5216b5eebdc709f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapA::const_iterator llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::posA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### posB {#a2d267a8085f8d6add4a69fdcaf91a73b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MapA, typename MapB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapB::const_iterator llvm::IntervalMapOverlaps&lt; MapA, MapB &gt;::posB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
