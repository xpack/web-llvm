---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/memprof/indexedallocationinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IndexedAllocationInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::memprof::IndexedAllocationInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">llvm/ProfileData/MemProf.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af05bbe90fae98431dc54cdb4633c7ca8">IndexedAllocationInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d64e916a8a22e8c05fae3cb1998bf6">IndexedAllocationInfo</a> (CallStackId CSId, const MemInfoBlock &amp;MB, const MemProfSchema &amp;Schema=getFullSchema())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a708eae87acef990b7b2be5e58f5fde4a">IndexedAllocationInfo</a> (CallStackId CSId, const PortableMemInfoBlock &amp;MB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a324f537cb618df14976dbcf942e2b88f">operator==</a> (const IndexedAllocationInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea254aa7600ecf156cbe388b3755437">operator!=</a> (const IndexedAllocationInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99c91bdd8be25712df758806015e4c2a">serializedSize</a> (const MemProfSchema &amp;Schema, IndexedVersion Version) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">CallStackId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a848ebb2867b90eeec510ce14878b398e">CSId</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/memprof/portablememinfoblock">PortableMemInfoBlock</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56a65c467e068d248938fd52d7831f10">Info</a></td>
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


<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IndexedAllocationInfo() {#af05bbe90fae98431dc54cdb4633c7ca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::IndexedAllocationInfo::IndexedAllocationInfo ()</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Referenced by <a href="#a4ea254aa7600ecf156cbe388b3755437">operator!=</a> and <a href="#a324f537cb618df14976dbcf942e2b88f">operator==</a>.</p>

</div>
</div>

### IndexedAllocationInfo() {#a30d64e916a8a22e8c05fae3cb1998bf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::IndexedAllocationInfo::IndexedAllocationInfo (<a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">CallStackId</a> CSId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MemInfoBlock &amp; MB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a4c0e5dd93f0bc1942fcd93ae8e7a23ea">MemProfSchema</a> &amp; Schema=<a href="/web-llvm/docs/api/namespaces/llvm/memprof/#aa4e49c91a6b2f7fef6298991217c929d">getFullSchema</a>())</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>References <a href="#a848ebb2867b90eeec510ce14878b398e">CSId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#aa4e49c91a6b2f7fef6298991217c929d">llvm::memprof::getFullSchema</a> and <a href="#a56a65c467e068d248938fd52d7831f10">Info</a>.</p>

</div>
</div>

### IndexedAllocationInfo() {#a708eae87acef990b7b2be5e58f5fde4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::IndexedAllocationInfo::IndexedAllocationInfo (<a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">CallStackId</a> CSId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/portablememinfoblock">PortableMemInfoBlock</a> &amp; MB)</td>
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



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>References <a href="#a848ebb2867b90eeec510ce14878b398e">CSId</a> and <a href="#a56a65c467e068d248938fd52d7831f10">Info</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a4ea254aa7600ecf156cbe388b3755437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::memprof::IndexedAllocationInfo::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedallocationinfo">IndexedAllocationInfo</a> &amp; Other)</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>References <a href="#af05bbe90fae98431dc54cdb4633c7ca8">IndexedAllocationInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/mergedfunctionsinfo-cpp/#ad5db311411b09e79fcad62e7cee12e6b">operator==</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#a324f537cb618df14976dbcf942e2b88f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::memprof::IndexedAllocationInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedallocationinfo">IndexedAllocationInfo</a> &amp; Other)</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>References <a href="#a848ebb2867b90eeec510ce14878b398e">CSId</a>, <a href="#af05bbe90fae98431dc54cdb4633c7ca8">IndexedAllocationInfo</a>, <a href="#a56a65c467e068d248938fd52d7831f10">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### serializedSize() {#a99c91bdd8be25712df758806015e4c2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::memprof::IndexedAllocationInfo::serializedSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a4c0e5dd93f0bc1942fcd93ae8e7a23ea">MemProfSchema</a> &amp; Schema, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecb">IndexedVersion</a> Version)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprof-cpp">MemProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a49bcf18527d9a40d5eee1eb44821cbcb">llvm::memprof::serializedSizeV2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a5f06862de128b8a111f2ac9183fa2dee">llvm::memprof::serializedSizeV3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbaa4580b818c5644cc40399914cc86c227">llvm::memprof::Version2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a0fc6665973482c2867a12f718017eecbafe029208a9df98e11b723897a0f19b8d">llvm::memprof::Version3</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CSId {#a848ebb2867b90eeec510ce14878b398e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallStackId llvm::memprof::IndexedAllocationInfo::CSId = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/indexedmemprofreader/#af543f9026f539064b643534a8acf1ae5">llvm::IndexedMemProfReader::getMemProfCallerCalleePairs</a>, <a href="#a30d64e916a8a22e8c05fae3cb1998bf6">IndexedAllocationInfo</a>, <a href="#a708eae87acef990b7b2be5e58f5fde4a">IndexedAllocationInfo</a> and <a href="#a324f537cb618df14976dbcf942e2b88f">operator==</a>.</p>

</div>
</div>

### Info {#a56a65c467e068d248938fd52d7831f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PortableMemInfoBlock llvm::memprof::IndexedAllocationInfo::Info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Referenced by <a href="#a30d64e916a8a22e8c05fae3cb1998bf6">IndexedAllocationInfo</a>, <a href="#a708eae87acef990b7b2be5e58f5fde4a">IndexedAllocationInfo</a> and <a href="#a324f537cb618df14976dbcf942e2b88f">operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprof-cpp">MemProf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
