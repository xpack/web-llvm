---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sampleprof/linelocation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LineLocation` Struct Reference

<p>Represents the relative location of an instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::sampleprof::LineLocation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">llvm/ProfileData/SampleProf.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a437b7c002f9aac9916241b5d17ffd670">LineLocation</a> (uint32_t L, uint32_t D)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59167ae5bcb45cf663e273c51892baf4">operator&lt;</a> (const LineLocation &amp;O) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1fb5e61edfc5d6593b7002c2d084a3c">operator==</a> (const LineLocation &amp;O) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a465c124147a1d16054bacf1ab466e5d9">operator!=</a> (const LineLocation &amp;O) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ff8f7a933134513cf80feaf6f41b4ec">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac76f76a568bbf03e252a65c04ed7c1aa">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab112e029f040b44ca0199b3f93dfde81">getHashCode</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac38b029469edc31486c5ce8adf89e5f3">LineOffset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8129e173d0cdcdd59271bf89f32544c">Discriminator</a></td>
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

<p>Represents the relative location of an instruction.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> locations are specified by the line offset from the beginning of the function (marked by the line where the function header is) and the discriminator value within that line.</p>


<p>The discriminator value is useful to distinguish instructions that are on the same line but belong to different basic blocks (e.g., the two post-increment instructions in "if (p) x++; else y++;").</p>


<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LineLocation() {#a437b7c002f9aac9916241b5d17ffd670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::LineLocation::LineLocation (uint32_t L, uint32_t D)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#ac8129e173d0cdcdd59271bf89f32544c">Discriminator</a> and <a href="#ac38b029469edc31486c5ce8adf89e5f3">LineOffset</a>.</p>


<p>Referenced by <a href="#a465c124147a1d16054bacf1ab466e5d9">operator!=</a>, <a href="#a59167ae5bcb45cf663e273c51892baf4">operator&lt;</a> and <a href="#ab1fb5e61edfc5d6593b7002c2d084a3c">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a465c124147a1d16054bacf1ab466e5d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::LineLocation::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; O)</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#ac8129e173d0cdcdd59271bf89f32544c">Discriminator</a>, <a href="#a437b7c002f9aac9916241b5d17ffd670">LineLocation</a> and <a href="#ac38b029469edc31486c5ce8adf89e5f3">LineOffset</a>.</p>

</div>
</div>

### operator&lt;() {#a59167ae5bcb45cf663e273c51892baf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::LineLocation::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; O)</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#ac8129e173d0cdcdd59271bf89f32544c">Discriminator</a>, <a href="#a437b7c002f9aac9916241b5d17ffd670">LineLocation</a> and <a href="#ac38b029469edc31486c5ce8adf89e5f3">LineOffset</a>.</p>

</div>
</div>

### operator==() {#ab1fb5e61edfc5d6593b7002c2d084a3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::LineLocation::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; O)</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#ac8129e173d0cdcdd59271bf89f32544c">Discriminator</a>, <a href="#a437b7c002f9aac9916241b5d17ffd670">LineLocation</a> and <a href="#ac38b029469edc31486c5ce8adf89e5f3">LineOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#ac76f76a568bbf03e252a65c04ed7c1aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LineLocation::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a2ff8f7a933134513cf80feaf6f41b4ec">print</a>.</p>

</div>
</div>

### getHashCode() {#ab112e029f040b44ca0199b3f93dfde81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::LineLocation::getHashCode ()</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#ac8129e173d0cdcdd59271bf89f32544c">Discriminator</a> and <a href="#ac38b029469edc31486c5ce8adf89e5f3">LineOffset</a>.</p>

</div>
</div>

### print() {#a2ff8f7a933134513cf80feaf6f41b4ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LineLocation::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a>.</p>


<p>References <a href="#ac8129e173d0cdcdd59271bf89f32544c">Discriminator</a> and <a href="#ac38b029469edc31486c5ce8adf89e5f3">LineOffset</a>.</p>


<p>Referenced by <a href="#ac76f76a568bbf03e252a65c04ed7c1aa">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Discriminator {#ac8129e173d0cdcdd59271bf89f32544c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::sampleprof::LineLocation::Discriminator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#a8405818cd197f55e233406e23f59c76e">llvm::sampleprof::SampleContext::decodeContextString</a>, <a href="#ab112e029f040b44ca0199b3f93dfde81">getHashCode</a>, <a href="#a437b7c002f9aac9916241b5d17ffd670">LineLocation</a>, <a href="#a465c124147a1d16054bacf1ab466e5d9">operator!=</a>, <a href="#a59167ae5bcb45cf663e273c51892baf4">operator&lt;</a>, <a href="#ab1fb5e61edfc5d6593b7002c2d084a3c">operator==</a> and <a href="#a2ff8f7a933134513cf80feaf6f41b4ec">print</a>.</p>

</div>
</div>

### LineOffset {#ac38b029469edc31486c5ce8adf89e5f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::sampleprof::LineLocation::LineOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#a8405818cd197f55e233406e23f59c76e">llvm::sampleprof::SampleContext::decodeContextString</a>, <a href="#ab112e029f040b44ca0199b3f93dfde81">getHashCode</a>, <a href="#a437b7c002f9aac9916241b5d17ffd670">LineLocation</a>, <a href="#a465c124147a1d16054bacf1ab466e5d9">operator!=</a>, <a href="#a59167ae5bcb45cf663e273c51892baf4">operator&lt;</a>, <a href="#ab1fb5e61edfc5d6593b7002c2d084a3c">operator==</a> and <a href="#a2ff8f7a933134513cf80feaf6f41b4ec">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
