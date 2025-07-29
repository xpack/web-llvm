---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instrprofrecordwritertrait
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstrProfRecordWriterTrait` Class



## Declaration

<div class="doxyDeclaration">
class llvm::InstrProfRecordWriterTrait { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7777b8fd88d431702a9eacc2dcf9fe8e">key_type</a> = <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bb9bbbb912b897f9ab3829128ba4c24">key_type_ref</a> = <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeca35f81e72f0dd2b00324f23d014d3e">data_type</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#ab8307c49f2fa9f6b5d968b663105b5df">InstrProfWriter::ProfilingData</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a188bedb19889809b75e8913e87b02c71">data_type_ref</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#ab8307c49f2fa9f6b5d968b663105b5df">InstrProfWriter::ProfilingData</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea32ad3cd0058a4ea5c1ecfa09b1ddfb">hash_value_type</a> = uint64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64f4121d3cc753c8143a35dd9074de99">offset_type</a> = uint64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeb821906c800073ad04cde06e292953">InstrProfRecordWriterTrait</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6f07481b72e3568320b1a68fe1d320d">EmitKey</a> (raw_ostream &amp;Out, key_type_ref K, offset_type N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeade4a99cac29eaa9bf39f2729f8d75f">EmitData</a> (raw_ostream &amp;Out, key_type_ref, data_type_ref V, offset_type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c4ba41f5fd8a0cec1df5844322e69d">ValueProfDataEndianness</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::endianness::little</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder">InstrProfSummaryBuilder</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1964d68d81eeaaf5c94ece89e50ca45c">SummaryBuilder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofsummarybuilder">InstrProfSummaryBuilder</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89b90eb46fd5fcc1a061de24327b56f7">CSSummaryBuilder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#aea32ad3cd0058a4ea5c1ecfa09b1ddfb">hash_value_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76a192ea31b07d4aaa7890fa4f172b04">ComputeHash</a> (key_type_ref K)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="#a64f4121d3cc753c8143a35dd9074de99">offset_type</a>, <a href="#a64f4121d3cc753c8143a35dd9074de99">offset_type</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063fe524f591af6fc154088fe2feb92f">EmitKeyDataLength</a> (raw_ostream &amp;Out, key_type_ref K, data_type_ref V)</td>
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


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### data\_type {#aeca35f81e72f0dd2b00324f23d014d3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InstrProfRecordWriterTrait::data_type =  const InstrProfWriter::ProfilingData *const</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### data\_type\_ref {#a188bedb19889809b75e8913e87b02c71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InstrProfRecordWriterTrait::data_type_ref =  const InstrProfWriter::ProfilingData *const</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### hash\_value\_type {#aea32ad3cd0058a4ea5c1ecfa09b1ddfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InstrProfRecordWriterTrait::hash_value_type =  uint64_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### key\_type {#a7777b8fd88d431702a9eacc2dcf9fe8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InstrProfRecordWriterTrait::key_type =  StringRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### key\_type\_ref {#a4bb9bbbb912b897f9ab3829128ba4c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InstrProfRecordWriterTrait::key_type_ref =  StringRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

### offset\_type {#a64f4121d3cc753c8143a35dd9074de99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InstrProfRecordWriterTrait::offset_type =  uint64_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InstrProfRecordWriterTrait() {#aaeb821906c800073ad04cde06e292953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfRecordWriterTrait::InstrProfRecordWriterTrait ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### EmitData() {#aeade4a99cac29eaa9bf39f2729f8d75f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecordWriterTrait::EmitData (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="#a4bb9bbbb912b897f9ab3829128ba4c24">key_type_ref</a>, <a href="#a188bedb19889809b75e8913e87b02c71">data_type_ref</a> V, <a href="#a64f4121d3cc753c8143a35dd9074de99">offset_type</a>)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#ae04bac786c8ba17e3fcd332e26f4e257">llvm::InstrProfRecord::BitmapBytes</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#a1b5488b65ab76c49ab7dd16115c23f56">llvm::InstrProfRecord::Counts</a>, <a href="#a89b90eb46fd5fcc1a061de24327b56f7">CSSummaryBuilder</a>, <a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord/#a56beb93bcdcf5daaa14a432868f6d5d3">llvm::NamedInstrProfRecord::hasCSFlagInHash</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="#a1964d68d81eeaaf5c94ece89e50ca45c">SummaryBuilder</a>, <a href="#a51c4ba41f5fd8a0cec1df5844322e69d">ValueProfDataEndianness</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

### EmitKey() {#ad6f07481b72e3568320b1a68fe1d320d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfRecordWriterTrait::EmitKey (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="#a4bb9bbbb912b897f9ab3829128ba4c24">key_type_ref</a> K, <a href="#a64f4121d3cc753c8143a35dd9074de99">offset_type</a> N)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CSSummaryBuilder {#a89b90eb46fd5fcc1a061de24327b56f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfSummaryBuilder* llvm::InstrProfRecordWriterTrait::CSSummaryBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Referenced by <a href="#aeade4a99cac29eaa9bf39f2729f8d75f">EmitData</a>.</p>

</div>
</div>

### SummaryBuilder {#a1964d68d81eeaaf5c94ece89e50ca45c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfSummaryBuilder* llvm::InstrProfRecordWriterTrait::SummaryBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Referenced by <a href="#aeade4a99cac29eaa9bf39f2729f8d75f">EmitData</a>.</p>

</div>
</div>

### ValueProfDataEndianness {#a51c4ba41f5fd8a0cec1df5844322e69d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::endianness llvm::InstrProfRecordWriterTrait::ValueProfDataEndianness = <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::endianness::little</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Referenced by <a href="#aeade4a99cac29eaa9bf39f2729f8d75f">EmitData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### ComputeHash() {#a76a192ea31b07d4aaa7890fa4f172b04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hash_value_type llvm::InstrProfRecordWriterTrait::ComputeHash (<a href="#a4bb9bbbb912b897f9ab3829128ba4c24">key_type_ref</a> K)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/indexedinstrprof/#a26647986f25d6168afc4204fd79873df">llvm::IndexedInstrProf::ComputeHash</a>.</p>

</div>
</div>

### EmitKeyDataLength() {#a063fe524f591af6fc154088fe2feb92f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; offset_type, offset_type &gt; llvm::InstrProfRecordWriterTrait::EmitKeyDataLength (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="#a4bb9bbbb912b897f9ab3829128ba4c24">key_type_ref</a> K, <a href="#a188bedb19889809b75e8913e87b02c71">data_type_ref</a> V)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#ae04bac786c8ba17e3fcd332e26f4e257">llvm::InstrProfRecord::BitmapBytes</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#a1b5488b65ab76c49ab7dd16115c23f56">llvm::InstrProfRecord::Counts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
