---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/samplerecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SampleRecord` Class Reference

<p>Representation of a single sample record. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::SampleRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">llvm/ProfileData/SampleProf.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5bbb4b126391880d59fc57d715d730">CallTarget</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, uint64_t &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a680d7f1eb4466835294fb3c127bd66d2">SortedCallTargetSet</a> = std::set&lt; <a href="#acb5bbb4b126391880d59fc57d715d730">CallTarget</a>, <a href="/web-llvm/docs/api/structs/llvm/sampleprof/samplerecord/calltargetcomparator">CallTargetComparator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25d27170e0de5f9f6d999f8efa3cc32d">CallTargetMap</a> = std::unordered_map&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, uint64_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e45fc6fb7b892f8d86be28794da2dbd">SampleRecord</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc6ca6ba144453939357fb8f61f8a66b">operator==</a> (const SampleRecord &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc2de4631669bf294c3374ead280fd2">operator!=</a> (const SampleRecord &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbe">sampleprof_error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf5e9aa8e25f99292eeaa21f0efe945">addSamples</a> (uint64_t S, uint64_t Weight=1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Increment the number of samples for this record by <span class="doxyComputerOutput">S</span>. <a href="#a8cf5e9aa8e25f99292eeaa21f0efe945">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8327dfec292cb31cfd4739acc0bff45a">removeSamples</a> (uint64_t S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decrease the number of samples for this record by <span class="doxyComputerOutput">S</span>. <a href="#a8327dfec292cb31cfd4739acc0bff45a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbe">sampleprof_error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff7b06c9fc5bb911a6cde3d7f68aa677">addCalledTarget</a> (FunctionId F, uint64_t S, uint64_t Weight=1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add called function <span class="doxyComputerOutput">F</span> with samples <span class="doxyComputerOutput">S</span>. <a href="#aff7b06c9fc5bb911a6cde3d7f68aa677">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1a0a4b1ed4fc469424473f238d9e5e">removeCalledTarget</a> (FunctionId F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove called function from the call target map. <a href="#a9a1a0a4b1ed4fc469424473f238d9e5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42abd30a49946a0ce4824807dbd2b7de">hasCalls</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this sample record contains function calls. <a href="#a42abd30a49946a0ce4824807dbd2b7de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e5033adccbe0a93cc7c77cd89ed2fec">getSamples</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a25d27170e0de5f9f6d999f8efa3cc32d">CallTargetMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a643e540a629559bc145405a68f3f0cbb">getCallTargets</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a680d7f1eb4466835294fb3c127bd66d2">SortedCallTargetSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe2b5ee88eea4c21f9efe473183744ed">getSortedCallTargets</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a757faa1e09780c18048eb10f56f7e829">getCallTargetSum</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbe">sampleprof_error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60dc779551fee20748756f379ce658ec">merge</a> (const SampleRecord &amp;Other, uint64_t Weight=1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge the samples in <span class="doxyComputerOutput">Other</span> into this record. <a href="#a60dc779551fee20748756f379ce658ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afab5a58513f5b4f13ff4e02659b255e9">print</a> (raw_ostream &amp;OS, unsigned Indent) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the sample record to the stream <span class="doxyComputerOutput">OS</span> indented by <span class="doxyComputerOutput">Indent</span>. <a href="#afab5a58513f5b4f13ff4e02659b255e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fd74749576d39c8ed03c634f407183a">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c9ea5164c583eb5328b2fd442a3e050">NumSamples</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a25d27170e0de5f9f6d999f8efa3cc32d">CallTargetMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26550324a9cb8870e432ef4e2114dce8">CallTargets</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a680d7f1eb4466835294fb3c127bd66d2">SortedCallTargetSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63324042ea47580bcee3675b4351b704">sortCallTargets</a> (const CallTargetMap &amp;Targets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sort call targets in descending order of call frequency. <a href="#a63324042ea47580bcee3675b4351b704">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a25d27170e0de5f9f6d999f8efa3cc32d">CallTargetMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfed1f1dfd251457d62aa20c4c4e95eb">adjustCallTargets</a> (const CallTargetMap &amp;Targets, float DistributionFactor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prorate call targets by a distribution factor. <a href="#abfed1f1dfd251457d62aa20c4c4e95eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Representation of a single sample record.</p>


<p>A sample record is represented by a positive integer value, which indicates how frequently was the associated line location executed.</p>


<p>Additionally, if the associated location contains a function call, the record will hold a list of all the possible called targets. For direct calls, this will be the exact function being invoked. For indirect calls (function pointers, virtual table dispatch), this will be a list of one or more functions.</p>


<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CallTarget {#acb5bbb4b126391880d59fc57d715d730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprof::SampleRecord::CallTarget =  std::pair&lt;FunctionId, uint64_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### CallTargetMap {#a25d27170e0de5f9f6d999f8efa3cc32d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprof::SampleRecord::CallTargetMap =  std::unordered_map&lt;FunctionId, uint64_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### SortedCallTargetSet {#a680d7f1eb4466835294fb3c127bd66d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprof::SampleRecord::SortedCallTargetSet =  std::set&lt;CallTarget, CallTargetComparator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SampleRecord() {#a9e45fc6fb7b892f8d86be28794da2dbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleRecord::SampleRecord ()</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#a60dc779551fee20748756f379ce658ec">merge</a>, <a href="#accc2de4631669bf294c3374ead280fd2">operator!=</a> and <a href="#adc6ca6ba144453939357fb8f61f8a66b">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#accc2de4631669bf294c3374ead280fd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleRecord::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord">SampleRecord</a> &amp; Other)</td>
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



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a9e45fc6fb7b892f8d86be28794da2dbd">SampleRecord</a>.</p>

</div>
</div>

### operator==() {#adc6ca6ba144453939357fb8f61f8a66b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleRecord::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord">SampleRecord</a> &amp; Other)</td>
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



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a9e45fc6fb7b892f8d86be28794da2dbd">SampleRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCalledTarget() {#aff7b06c9fc5bb911a6cde3d7f68aa677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sampleprof_error llvm::sampleprof::SampleRecord::addCalledTarget (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> F, uint64_t S, uint64_t Weight=1)</td>
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

<p>Add called function <span class="doxyComputerOutput">F</span> with samples <span class="doxyComputerOutput">S</span>.</p>


<p>Optionally scale sample count <span class="doxyComputerOutput">S</span> by <span class="doxyComputerOutput">Weight</span>.</p>


<p>Sample counts accumulate using saturating arithmetic, to avoid wrapping around unsigned integers.</p>


<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea5e8bae22cbd37f66c813d8a3749bda1c">llvm::counter_overflow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84836a719cdf82a516d556ae66cc8dc0">llvm::SaturatingMultiplyAdd</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#a60dc779551fee20748756f379ce658ec">merge</a>.</p>

</div>
</div>

### addSamples() {#a8cf5e9aa8e25f99292eeaa21f0efe945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sampleprof_error llvm::sampleprof::SampleRecord::addSamples (uint64_t S, uint64_t Weight=1)</td>
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

<p>Increment the number of samples for this record by <span class="doxyComputerOutput">S</span>.</p>


<p>Optionally scale sample count <span class="doxyComputerOutput">S</span> by <span class="doxyComputerOutput">Weight</span>.</p>


<p>Sample counts accumulate using saturating arithmetic, to avoid wrapping around unsigned integers.</p>


<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea5e8bae22cbd37f66c813d8a3749bda1c">llvm::counter_overflow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84836a719cdf82a516d556ae66cc8dc0">llvm::SaturatingMultiplyAdd</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="#a60dc779551fee20748756f379ce658ec">merge</a>.</p>

</div>
</div>

### dump() {#a3fd74749576d39c8ed03c634f407183a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SampleRecord::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#afab5a58513f5b4f13ff4e02659b255e9">print</a>.</p>

</div>
</div>

### getCallTargets() {#a643e540a629559bc145405a68f3f0cbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallTargetMap &amp; llvm::sampleprof::SampleRecord::getCallTargets ()</td>
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



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a880b4a9e6f81baaa1c9a1fe9a2151cfd">llvm::sampleprof::SampleProfileWriterBinary::addNames</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#ae7c088ecf1befc97ec9b4d36f30ae06d">llvm::sampleprof::SampleProfileWriterBinary::writeBody</a>.</p>

</div>
</div>

### getCallTargetSum() {#a757faa1e09780c18048eb10f56f7e829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::SampleRecord::getCallTargetSum ()</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getSamples() {#a6e5033adccbe0a93cc7c77cd89ed2fec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::SampleRecord::getSamples ()</td>
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



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#ae7c088ecf1befc97ec9b4d36f30ae06d">llvm::sampleprof::SampleProfileWriterBinary::writeBody</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

### getSortedCallTargets() {#abe2b5ee88eea4c21f9efe473183744ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SortedCallTargetSet llvm::sampleprof::SampleRecord::getSortedCallTargets ()</td>
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



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="#a63324042ea47580bcee3675b4351b704">sortCallTargets</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a>, <a href="#afab5a58513f5b4f13ff4e02659b255e9">print</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#ae7c088ecf1befc97ec9b4d36f30ae06d">llvm::sampleprof::SampleProfileWriterBinary::writeBody</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

### hasCalls() {#a42abd30a49946a0ce4824807dbd2b7de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleRecord::hasCalls ()</td>
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

<p>Return true if this sample record contains function calls.</p>

<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#afab5a58513f5b4f13ff4e02659b255e9">print</a>.</p>

</div>
</div>

### merge() {#a60dc779551fee20748756f379ce658ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sampleprof_error SampleRecord::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord">SampleRecord</a> &amp; Other, uint64_t Weight=1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge the samples in <span class="doxyComputerOutput">Other</span> into this record.</p>


<p>Optionally scale sample counts by <span class="doxyComputerOutput">Weight</span>.</p>


<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a>.</p>


<p>References <a href="#aff7b06c9fc5bb911a6cde3d7f68aa677">addCalledTarget</a>, <a href="#a8cf5e9aa8e25f99292eeaa21f0efe945">addSamples</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6af78b474302640c3fd76f2e8031f9f9">llvm::mergeSampleProfErrors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a9e45fc6fb7b892f8d86be28794da2dbd">SampleRecord</a>.</p>

</div>
</div>

### print() {#afab5a58513f5b4f13ff4e02659b255e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleRecord::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, unsigned Indent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the sample record to the stream <span class="doxyComputerOutput">OS</span> indented by <span class="doxyComputerOutput">Indent</span>.</p>

<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a>.</p>


<p>References <a href="#abe2b5ee88eea4c21f9efe473183744ed">getSortedCallTargets</a>, <a href="#a42abd30a49946a0ce4824807dbd2b7de">hasCalls</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a3fd74749576d39c8ed03c634f407183a">dump</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#afc34a15e141e022fc10837f80593b0a2">llvm::sampleprof::operator&lt;&lt;</a>.</p>

</div>
</div>

### removeCalledTarget() {#a9a1a0a4b1ed4fc469424473f238d9e5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::SampleRecord::removeCalledTarget (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> F)</td>
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

<p>Remove called function from the call target map.</p>


<p>Return the target sample count of the called function.</p>


<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### removeSamples() {#a8327dfec292cb31cfd4739acc0bff45a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::SampleRecord::removeSamples (uint64_t S)</td>
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

<p>Decrease the number of samples for this record by <span class="doxyComputerOutput">S</span>.</p>


<p>Return the amout of samples actually decreased.</p>


<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CallTargets {#a26550324a9cb8870e432ef4e2114dce8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallTargetMap llvm::sampleprof::SampleRecord::CallTargets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### NumSamples {#a9c9ea5164c583eb5328b2fd442a3e050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::SampleRecord::NumSamples = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### adjustCallTargets() {#abfed1f1dfd251457d62aa20c4c4e95eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallTargetMap llvm::sampleprof::SampleRecord::adjustCallTargets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a25d27170e0de5f9f6d999f8efa3cc32d">CallTargetMap</a> &amp; Targets, float DistributionFactor)</td>
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

<p>Prorate call targets by a distribution factor.</p>

<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>.</p>

</div>
</div>

### sortCallTargets() {#a63324042ea47580bcee3675b4351b704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SortedCallTargetSet llvm::sampleprof::SampleRecord::sortCallTargets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a25d27170e0de5f9f6d999f8efa3cc32d">CallTargetMap</a> &amp; Targets)</td>
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

<p>Sort call targets in descending order of call frequency.</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#abe2b5ee88eea4c21f9efe473183744ed">getSortedCallTargets</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#aaf55fbc9b8550957ceb81da6a13f54e4">GetSortedValueDataFromCallTargets</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
