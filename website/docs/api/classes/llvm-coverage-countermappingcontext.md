---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/coverage/countermappingcontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CounterMappingContext` Class

<p>A <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> mapping context is used to connect the counters, expressions and the obtained counter values. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::coverage::CounterMappingContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">llvm/ProfileData/Coverage/CoverageMapping.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98536f1dc4806be9e1d72768766ce5ca">CounterMappingContext</a> (ArrayRef&lt; CounterExpression &gt; Expressions, ArrayRef&lt; uint64_t &gt; CounterValues={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64a0ee0f4d1ff2694d9c2d5f40b36339">setCounts</a> (ArrayRef&lt; uint64_t &gt; Counts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f2461db510dca84f702085ae19ae97">setBitmap</a> (BitVector &amp;&amp;Bitmap_)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab51ae1c563e141c138bd1f48148ea15c">dump</a> (const Counter &amp;C, raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81dfcc539759797a45b55b1a9e64be65">dump</a> (const Counter &amp;C) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a864c87ebba81fb2ed961ca9f9d2cc8e8">evaluate</a> (const Counter &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of times that a region of code associated with this counter was executed. <a href="#a864c87ebba81fb2ed961ca9f9d2cc8e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord">MCDCRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c33b841af0c1be38c0fabb09167710a">evaluateMCDCRegion</a> (const CounterMappingRegion &amp;Region, ArrayRef&lt; const CounterMappingRegion * &gt; Branches, bool IsVersion11)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an MCDC record that indicates executed test vectors and condition pairs. <a href="#a4c33b841af0c1be38c0fabb09167710a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96e28dfb703584ae264ed8408863ab7d">getMaxCounterID</a> (const Counter &amp;C) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression">CounterExpression</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae90fbe4e1e37df92fcc213ac2ec88361">Expressions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed104fceb8f278bb2462696faa961b37">CounterValues</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94487512dbc9aa577ee4dfffa117ac3d">Bitmap</a></td>
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

<p>A <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> mapping context is used to connect the counters, expressions and the obtained counter values.</p>

<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CounterMappingContext() {#a98536f1dc4806be9e1d72768766ce5ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CounterMappingContext::CounterMappingContext (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression">CounterExpression</a> &gt; Expressions, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; CounterValues={})</td>
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



<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#ab51ae1c563e141c138bd1f48148ea15c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CounterMappingContext::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca4d833352a08a316752f999f56e6bf06e">llvm::coverage::Counter::CounterValueReference</a>, <a href="#ab51ae1c563e141c138bd1f48148ea15c">dump</a>, <a href="#a864c87ebba81fb2ed961ca9f9d2cc8e8">evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca3414aa40642d6bfd511e941d82ed1780">llvm::coverage::Counter::Expression</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression/#ae5156429537263d93d5d165c7501e49cad1416de918b7a5b4457401a093632670">llvm::coverage::CounterExpression::Subtract</a> and <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca67a8514f4af2332820b159b681e49b1a">llvm::coverage::Counter::Zero</a>.</p>


<p>Referenced by <a href="#ab51ae1c563e141c138bd1f48148ea15c">dump</a>.</p>

</div>
</div>

### dump() {#a81dfcc539759797a45b55b1a9e64be65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::coverage::CounterMappingContext::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> &amp; C)</td>
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



<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a81dfcc539759797a45b55b1a9e64be65">dump</a>.</p>


<p>Referenced by <a href="#a81dfcc539759797a45b55b1a9e64be65">dump</a>.</p>

</div>
</div>

### evaluate() {#a864c87ebba81fb2ed961ca9f9d2cc8e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int64_t &gt; CounterMappingContext::evaluate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of times that a region of code associated with this counter was executed.</p>

<p>Declaration at line 692 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba4b82222a0895b538d0597092b3ceab3e">llvm::argument_out_of_domain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca4d833352a08a316752f999f56e6bf06e">llvm::coverage::Counter::CounterValueReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca3414aa40642d6bfd511e941d82ed1780">llvm::coverage::Counter::Expression</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression/#ae5156429537263d93d5d165c7501e49cad1416de918b7a5b4457401a093632670">llvm::coverage::CounterExpression::Subtract</a> and <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca67a8514f4af2332820b159b681e49b1a">llvm::coverage::Counter::Zero</a>.</p>


<p>Referenced by <a href="#ab51ae1c563e141c138bd1f48148ea15c">dump</a>.</p>

</div>
</div>

### evaluateMCDCRegion() {#a4c33b841af0c1be38c0fabb09167710a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MCDCRecord &gt; CounterMappingContext::evaluateMCDCRegion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a> &amp; Region, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a> * &gt; Branches, bool IsVersion11)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an MCDC record that indicates executed test vectors and condition pairs.</p>

<p>Declaration at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>, definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### getMaxCounterID() {#a96e28dfb703584ae264ed8408863ab7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CounterMappingContext::getMaxCounterID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>, definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca4d833352a08a316752f999f56e6bf06e">llvm::coverage::Counter::CounterValueReference</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca3414aa40642d6bfd511e941d82ed1780">llvm::coverage::Counter::Expression</a> and <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a5e36bdc59afb1fa1af1e70a3f89a3ceca67a8514f4af2332820b159b681e49b1a">llvm::coverage::Counter::Zero</a>.</p>

</div>
</div>

### setBitmap() {#a94f2461db510dca84f702085ae19ae97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::coverage::CounterMappingContext::setBitmap (<a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;&amp; Bitmap_)</td>
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



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### setCounts() {#a64a0ee0f4d1ff2694d9c2d5f40b36339}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::coverage::CounterMappingContext::setCounts (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Counts)</td>
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



<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Bitmap {#a94487512dbc9aa577ee4dfffa117ac3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::coverage::CounterMappingContext::Bitmap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### CounterValues {#aed104fceb8f278bb2462696faa961b37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint64_t&gt; llvm::coverage::CounterMappingContext::CounterValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### Expressions {#ae90fbe4e1e37df92fcc213ac2ec88361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;CounterExpression&gt; llvm::coverage::CounterMappingContext::Expressions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
