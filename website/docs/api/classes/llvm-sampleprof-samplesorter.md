---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/samplesorter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SampleSorter` Class Template

<p>Sort a LocationT-&gt;SampleT map by LocationT. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class LocationT, class SampleT&gt;
class llvm::sampleprof::SampleSorter&lt;LocationT, SampleT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">llvm/ProfileData/SampleProf.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LocationT, class SampleT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a05893e1e561ae58550372d98bf51119f">SamplesWithLoc</a> = std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LocationT, SampleT &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LocationT, class SampleT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab7d64919f4972a0383657b52d5723d2f">SamplesWithLocList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a05893e1e561ae58550372d98bf51119f">SamplesWithLoc</a> *, 20 &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LocationT, class SampleT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a59e9b3abb6c95f54ddf6f331415006f7">SampleSorter</a> (const std::map&lt; LocationT, SampleT &gt; &amp;Samples)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LocationT, class SampleT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab7d64919f4972a0383657b52d5723d2f">SamplesWithLocList</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a63724eb0b03848a61809932b0d5a63a7">get</a> () const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LocationT, class SampleT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ab7d64919f4972a0383657b52d5723d2f">SamplesWithLocList</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2ea808fd0900ac66113161f667173468">V</a></td>
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

<p>Sort a LocationT-&gt;SampleT map by LocationT.</p>


<p>It produces a sorted list of &lt;LocationT, SampleT&gt; records by ascending order of LocationT.</p>


<p>Definition at line 1353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SamplesWithLoc {#a05893e1e561ae58550372d98bf51119f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LocationT, class SampleT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprof::SampleSorter&lt; LocationT, SampleT &gt;::SamplesWithLoc =  std::pair&lt;const LocationT, SampleT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### SamplesWithLocList {#ab7d64919f4972a0383657b52d5723d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LocationT, class SampleT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprof::SampleSorter&lt; LocationT, SampleT &gt;::SamplesWithLocList =  SmallVector&lt;const SamplesWithLoc *, 20&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SampleSorter() {#a59e9b3abb6c95f54ddf6f331415006f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LocationT, class SampleT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleSorter&lt; LocationT, SampleT &gt;::SampleSorter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::map&lt; LocationT, SampleT &gt; &amp; Samples)</td>
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



<p>Definition at line 1358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#a63724eb0b03848a61809932b0d5a63a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LocationT, class SampleT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SamplesWithLocList &amp; llvm::sampleprof::SampleSorter&lt; LocationT, SampleT &gt;::get ()</td>
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



<p>Definition at line 1366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#adca18b92b535ad86d151efc86442027d">llvm::sampleprof::FunctionSamples::print</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### V {#a2ea808fd0900ac66113161f667173468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LocationT, class SampleT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SamplesWithLocList llvm::sampleprof::SampleSorter&lt; LocationT, SampleT &gt;::V</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
