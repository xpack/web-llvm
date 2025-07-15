---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memprof/yamlmemprofreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `YAMLMemProfReader` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::memprof::YAMLMemProfReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">llvm/ProfileData/MemProfReader.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memprof/memprofreader">MemProfReader</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a194a33390315265c4d4e75ea84cc9674">YAMLMemProfReader</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa050d96fe18573b4d459a769f576f1dc">parse</a> (StringRef YAMLData)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3312e664f5df1acd8f78ea8b824e7b5d">hasFormat</a> (const MemoryBuffer &amp;DataBuffer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61cde3150c070e36e72b24eac157b5ad">hasFormat</a> (const StringRef Path)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memprof/yamlmemprofreader">YAMLMemProfReader</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77027f7da4a6c0240777e8fe6aa4912d">create</a> (const Twine &amp;Path)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memprof/yamlmemprofreader">YAMLMemProfReader</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac14115d0e350eec8f05915d35d43991d">create</a> (std::unique_ptr&lt; MemoryBuffer &gt; Buffer)</td>
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


<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### YAMLMemProfReader() {#a194a33390315265c4d4e75ea84cc9674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::YAMLMemProfReader::YAMLMemProfReader ()</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parse() {#aa050d96fe18573b4d459a769f576f1dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::memprof::YAMLMemProfReader::parse (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> YAMLData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 784 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofrecord/#a41e6206cdacc4b9e172f1dd222f439fe">llvm::memprof::IndexedMemProfRecord::AllocSites</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofrecord/#a21be5df80ae1f2034f2479fabcfa5d3e">llvm::memprof::IndexedMemProfRecord::CallSiteIds</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/allocationinfo/#a09e66c1a54259cfb1ba348abef976058">llvm::memprof::AllocationInfo::CallStack</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/input/#aa353fb192bcd1d2e0561858ad440829b">llvm::yaml::Input::error</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/allmemprofdata/#aba83a912e4af27518f6cb08095ac1c48">llvm::memprof::AllMemProfData::HeapProfileRecords</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/allocationinfo/#a3752a895ac142ca07c83615a33bd5740">llvm::memprof::AllocationInfo::Info</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/memprofreader/#a5433f28dd23b726c305096acb90b3f23">llvm::memprof::MemProfReader::MemProfData</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a77027f7da4a6c0240777e8fe6aa4912d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; YAMLMemProfReader &gt; &gt; llvm::memprof::YAMLMemProfReader::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path)</td>
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



<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 755 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>


<p>References <a href="#a77027f7da4a6c0240777e8fe6aa4912d">create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a> and <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a9c54e2428ad0163441789c281ca42ee4">llvm::MemoryBuffer::getFileOrSTDIN</a>.</p>


<p>Referenced by <a href="#a77027f7da4a6c0240777e8fe6aa4912d">create</a>.</p>

</div>
</div>

### create() {#ac14115d0e350eec8f05915d35d43991d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; YAMLMemProfReader &gt; &gt; llvm::memprof::YAMLMemProfReader::create (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; Buffer)</td>
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



<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>

</div>
</div>

### hasFormat() {#a3312e664f5df1acd8f78ea8b824e7b5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::memprof::YAMLMemProfReader::hasFormat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp; DataBuffer)</td>
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



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 780 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a69d9843621ff4677c0b9087277dc4bd0">llvm::MemoryBuffer::getBuffer</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="#a61cde3150c070e36e72b24eac157b5ad">hasFormat</a>.</p>

</div>
</div>

### hasFormat() {#a61cde3150c070e36e72b24eac157b5ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::memprof::YAMLMemProfReader::hasFormat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
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



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 771 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a9c54e2428ad0163441789c281ca42ee4">llvm::MemoryBuffer::getFileOrSTDIN</a> and <a href="#a3312e664f5df1acd8f78ea8b824e7b5d">hasFormat</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
