---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/defaultfunctionpruningstrategy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DefaultFunctionPruningStrategy` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::DefaultFunctionPruningStrategy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">llvm/ProfileData/SampleProfWriter.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionpruningstrategy">FunctionPruningStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When writing a profile with size limit, user may want to use a different strategy to reduce function count other than dropping functions with fewest samples first. <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionpruningstrategy/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a064d283609c9be796770a8a411b0ddb1">DefaultFunctionPruningStrategy</a> (SampleProfileMap &amp;ProfileMap, size_t OutputSizeLimit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8abb143feff2f640ccc483ba91019c1b">Erase</a> (size_t CurrentOutputSize) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In this default implementation, functions with fewest samples are dropped first. <a href="#a8abb143feff2f640ccc483ba91019c1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a8418041ee57fb1966c79fb7d54643d90">NameFunctionSamples</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a764465285e52f0e65df8c30cd6ad64a0">SortedFunctions</a></td>
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


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DefaultFunctionPruningStrategy() {#a064d283609c9be796770a8a411b0ddb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefaultFunctionPruningStrategy::DefaultFunctionPruningStrategy (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap, size_t OutputSizeLimit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionpruningstrategy/#a6be976c54f94894b624c258569f67bcb">llvm::sampleprof::FunctionPruningStrategy::FunctionPruningStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionpruningstrategy/#ad3809dcbffabed1814b07e6add7bac2c">llvm::sampleprof::FunctionPruningStrategy::OutputSizeLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionpruningstrategy/#a91a31cd495fea709940239ebcbb10a4c">llvm::sampleprof::FunctionPruningStrategy::ProfileMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a11f675e2f1396d64eefeaf67cdce624e">llvm::sampleprof::sortFuncProfiles</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Erase() {#a8abb143feff2f640ccc483ba91019c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefaultFunctionPruningStrategy::Erase (size_t CurrentOutputSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In this default implementation, functions with fewest samples are dropped first.</p>


<p>Since the exact size of the output cannot be easily calculated due to compression, we use a heuristic to remove as many functions as necessary but not too many, aiming to minimize the number of write iterations. Empirically, functions with larger total sample count contain linearly more sample entries, meaning it takes linearly more space to write them. The cumulative length is therefore quadratic if all functions are sorted by total sample count. TODO: Find better heuristic.</p>


<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionpruningstrategy/#ad3809dcbffabed1814b07e6add7bac2c">llvm::sampleprof::FunctionPruningStrategy::OutputSizeLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionpruningstrategy/#a91a31cd495fea709940239ebcbb10a4c">llvm::sampleprof::FunctionPruningStrategy::ProfileMap</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#ae4e947c75dafebd71b8de03cd0dbf5d6">round</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SortedFunctions {#a764465285e52f0e65df8c30cd6ad64a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;NameFunctionSamples&gt; llvm::sampleprof::DefaultFunctionPruningStrategy::SortedFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
