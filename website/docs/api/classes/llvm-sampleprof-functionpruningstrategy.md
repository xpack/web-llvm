---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/functionpruningstrategy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FunctionPruningStrategy` Class

<p>When writing a profile with size limit, user may want to use a different strategy to reduce function count other than dropping functions with fewest samples first. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::FunctionPruningStrategy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">llvm/ProfileData/SampleProfWriter.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/defaultfunctionpruningstrategy">DefaultFunctionPruningStrategy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6be976c54f94894b624c258569f67bcb">FunctionPruningStrategy</a> (SampleProfileMap &amp;ProfileMap, size_t OutputSizeLimit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">ProfileMap</span> A reference to the original profile map. <a href="#a6be976c54f94894b624c258569f67bcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55afaa165cb1dd2484c5d81c28d89f9d">~FunctionPruningStrategy</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bb7affe9c405afd71075e2e56513db4">Erase</a> (size_t CurrentOutputSize)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a9283506633cf544e4a6163c0133fc769">SampleProfileWriter::writeWithSizeLimit()</a> calls this after every write iteration if the output size still exceeds the limit. <a href="#a3bb7affe9c405afd71075e2e56513db4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91a31cd495fea709940239ebcbb10a4c">ProfileMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3809dcbffabed1814b07e6add7bac2c">OutputSizeLimit</a></td>
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

<p>When writing a profile with size limit, user may want to use a different strategy to reduce function count other than dropping functions with fewest samples first.</p>


<p>In this case a class implementing the same interfaces should be provided to <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a9283506633cf544e4a6163c0133fc769">SampleProfileWriter::writeWithSizeLimit()</a>.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionPruningStrategy() {#a6be976c54f94894b624c258569f67bcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::FunctionPruningStrategy::FunctionPruningStrategy (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap, size_t OutputSizeLimit)</td>
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

<p><span class="doxyComputerOutput">ProfileMap</span> A reference to the original profile map.</p>


<p>It will be modified by <a href="#a3bb7affe9c405afd71075e2e56513db4">Erase()</a>. <span class="doxyComputerOutput">OutputSizeLimit</span> Size limit in bytes of the output profile. This is necessary to estimate how many functions to remove.</p>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>References <a href="#ad3809dcbffabed1814b07e6add7bac2c">OutputSizeLimit</a> and <a href="#a91a31cd495fea709940239ebcbb10a4c">ProfileMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/defaultfunctionpruningstrategy/#a064d283609c9be796770a8a411b0ddb1">llvm::sampleprof::DefaultFunctionPruningStrategy::DefaultFunctionPruningStrategy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~FunctionPruningStrategy() {#a55afaa165cb1dd2484c5d81c28d89f9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::sampleprof::FunctionPruningStrategy::~FunctionPruningStrategy ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Erase() {#a3bb7affe9c405afd71075e2e56513db4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::sampleprof::FunctionPruningStrategy::Erase (size_t CurrentOutputSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a9283506633cf544e4a6163c0133fc769">SampleProfileWriter::writeWithSizeLimit()</a> calls this after every write iteration if the output size still exceeds the limit.</p>


<p>This function should erase some functions from the profile map so that the writer tries to write the profile again with fewer functions. At least 1 entry from the profile map must be erased.</p>


<p><span class="doxyComputerOutput">CurrentOutputSize</span> Number of bytes in the output if current profile map is written.</p>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a383a9c6d7b337512fa69de542cec0375">llvm::sampleprof::SampleProfileWriter::writeWithSizeLimitInternal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### OutputSizeLimit {#ad3809dcbffabed1814b07e6add7bac2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::sampleprof::FunctionPruningStrategy::OutputSizeLimit</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/defaultfunctionpruningstrategy/#a064d283609c9be796770a8a411b0ddb1">llvm::sampleprof::DefaultFunctionPruningStrategy::DefaultFunctionPruningStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/defaultfunctionpruningstrategy/#a8abb143feff2f640ccc483ba91019c1b">llvm::sampleprof::DefaultFunctionPruningStrategy::Erase</a> and <a href="#a6be976c54f94894b624c258569f67bcb">FunctionPruningStrategy</a>.</p>

</div>
</div>

### ProfileMap {#a91a31cd495fea709940239ebcbb10a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleProfileMap&amp; llvm::sampleprof::FunctionPruningStrategy::ProfileMap</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/defaultfunctionpruningstrategy/#a064d283609c9be796770a8a411b0ddb1">llvm::sampleprof::DefaultFunctionPruningStrategy::DefaultFunctionPruningStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/defaultfunctionpruningstrategy/#a8abb143feff2f640ccc483ba91019c1b">llvm::sampleprof::DefaultFunctionPruningStrategy::Erase</a> and <a href="#a6be976c54f94894b624c258569f67bcb">FunctionPruningStrategy</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofwriter-h">SampleProfWriter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
