---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/namedinstrprofrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `NamedInstrProfRecord` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::NamedInstrProfRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">llvm/ProfileData/InstrProf.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Profiling information for a single function. <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7df73785a5e1363c8fbf680cc7fd629">NamedInstrProfRecord</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6721f7e25aed544f93affc2b01d1b22f">NamedInstrProfRecord</a> (StringRef Name, uint64_t Hash, std::vector&lt; uint64_t &gt; Counts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b5d63bc3d5d70a64378bb067d28b6a">NamedInstrProfRecord</a> (StringRef Name, uint64_t Hash, std::vector&lt; uint64_t &gt; Counts, std::vector&lt; uint8_t &gt; BitmapBytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76c9e7d5f0cd4c16bd3bbf4d72a34fcb">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8290e53a3027447e59b5bcb598e37704">Hash</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56beb93bcdcf5daaa14a432868f6d5d3">hasCSFlagInHash</a> (uint64_t FuncHash)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac51b9a380421e08532eb1e488863631d">setCSFlagInHash</a> (uint64_t &amp;FuncHash)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad32b36f5fceff8cca56b9803aa9e7cc2">CS_FLAG_IN_FUNC_HASH</a> = 60</td>
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


<p>Definition at line 997 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NamedInstrProfRecord() {#af7df73785a5e1363c8fbf680cc7fd629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::NamedInstrProfRecord::NamedInstrProfRecord ()</td>
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



<p>Definition at line 1004 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### NamedInstrProfRecord() {#a6721f7e25aed544f93affc2b01d1b22f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::NamedInstrProfRecord::NamedInstrProfRecord (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint64_t Hash, std::vector&lt; uint64_t &gt; Counts)</td>
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



<p>Definition at line 1005 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#a1b5488b65ab76c49ab7dd16115c23f56">llvm::InstrProfRecord::Counts</a>, <a href="#a8290e53a3027447e59b5bcb598e37704">Hash</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#a12b586f23ffc8a40ba78dba68cb4d896">llvm::InstrProfRecord::InstrProfRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a76c9e7d5f0cd4c16bd3bbf4d72a34fcb">Name</a>.</p>

</div>
</div>

### NamedInstrProfRecord() {#a71b5d63bc3d5d70a64378bb067d28b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::NamedInstrProfRecord::NamedInstrProfRecord (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint64_t Hash, std::vector&lt; uint64_t &gt; Counts, std::vector&lt; uint8_t &gt; BitmapBytes)</td>
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



<p>Definition at line 1008 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#ae04bac786c8ba17e3fcd332e26f4e257">llvm::InstrProfRecord::BitmapBytes</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#a1b5488b65ab76c49ab7dd16115c23f56">llvm::InstrProfRecord::Counts</a>, <a href="#a8290e53a3027447e59b5bcb598e37704">Hash</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#a12b586f23ffc8a40ba78dba68cb4d896">llvm::InstrProfRecord::InstrProfRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a76c9e7d5f0cd4c16bd3bbf4d72a34fcb">Name</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Hash {#a8290e53a3027447e59b5bcb598e37704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::NamedInstrProfRecord::Hash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 999 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a6721f7e25aed544f93affc2b01d1b22f">NamedInstrProfRecord</a> and <a href="#a71b5d63bc3d5d70a64378bb067d28b6a">NamedInstrProfRecord</a>.</p>

</div>
</div>

### Name {#a76c9e7d5f0cd4c16bd3bbf4d72a34fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::NamedInstrProfRecord::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 998 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a6721f7e25aed544f93affc2b01d1b22f">NamedInstrProfRecord</a> and <a href="#a71b5d63bc3d5d70a64378bb067d28b6a">NamedInstrProfRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### hasCSFlagInHash() {#a56beb93bcdcf5daaa14a432868f6d5d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::NamedInstrProfRecord::hasCSFlagInHash (uint64_t FuncHash)</td>
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



<p>Definition at line 1014 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#ad32b36f5fceff8cca56b9803aa9e7cc2">CS_FLAG_IN_FUNC_HASH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3757f72cb425574f0406a3144e9886df">llvm::FuncHash</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofreader/#af8e0c59b9bcc7888f39284b3fc417834">llvm::InstrProfReader::accumulateCounts</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofrecordwritertrait/#aeade4a99cac29eaa9bf39f2729f8d75f">llvm::InstrProfRecordWriterTrait::EmitData</a> and <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a8a83ecab002375cf09cf04f12470bf0e">llvm::IndexedInstrProfReader::getInstrProfRecord</a>.</p>

</div>
</div>

### setCSFlagInHash() {#ac51b9a380421e08532eb1e488863631d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::NamedInstrProfRecord::setCSFlagInHash (uint64_t &amp; FuncHash)</td>
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



<p>Definition at line 1017 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#ad32b36f5fceff8cca56b9803aa9e7cc2">CS_FLAG_IN_FUNC_HASH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3757f72cb425574f0406a3144e9886df">llvm::FuncHash</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### CS\_FLAG\_IN\_FUNC\_HASH {#ad32b36f5fceff8cca56b9803aa9e7cc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::NamedInstrProfRecord::CS_FLAG_IN_FUNC_HASH = 60</td>
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



<p>Definition at line 1002 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a56beb93bcdcf5daaa14a432868f6d5d3">hasCSFlagInHash</a> and <a href="#ac51b9a380421e08532eb1e488863631d">setCSFlagInHash</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
