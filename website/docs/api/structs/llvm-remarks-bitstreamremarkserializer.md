---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/bitstreamremarkserializer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `BitstreamRemarkSerializer` Struct

<p>Implementation of the remark serializer using LLVM bitstream. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::BitstreamRemarkSerializer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">llvm/Remarks/BitstreamRemarkSerializer.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer">RemarkSerializer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the base class for a remark serializer. <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42696d420acd17e7e8ab585db9f0b5c4">BitstreamRemarkSerializer</a> (raw_ostream &amp;OS, SerializerMode Mode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a serializer that will create its own string table. <a href="#a42696d420acd17e7e8ab585db9f0b5c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29d9a4e5bd223b77ecd204b5061ca00">BitstreamRemarkSerializer</a> (raw_ostream &amp;OS, SerializerMode Mode, StringTable StrTab)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a serializer with a pre-filled string table. <a href="#ad29d9a4e5bd223b77ecd204b5061ca00">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e6b2c791986011c32c7a0d37739bd49">emit</a> (const Remark &amp;Remark) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a remark to the stream. <a href="#a7e6b2c791986011c32c7a0d37739bd49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer">MetaSerializer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc127a6ed6eab26d127985ec8c38ef0f">metaSerializer</a> (raw_ostream &amp;OS, std::optional&lt; StringRef &gt; ExternalFilename=std::nullopt) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The metadata serializer associated to this remark serializer. <a href="#abc127a6ed6eab26d127985ec8c38ef0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b04e17884b4aab23e73cf48d515d1b5">DidSetUp</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The file should contain: 1) The block info block that describes how to read the blocks. <a href="#a4b04e17884b4aab23e73cf48d515d1b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper">BitstreamRemarkSerializerHelper</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ad27a674514a190c2417b69a79c65c">Helper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The helper to emit bitstream. <a href="#a65ad27a674514a190c2417b69a79c65c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ad59c8c4d42d338abf808697597855a">classof</a> (const RemarkSerializer *S)</td>
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

<p>Implementation of the remark serializer using LLVM bitstream.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitstreamRemarkSerializer() {#a42696d420acd17e7e8ab585db9f0b5c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamRemarkSerializer::BitstreamRemarkSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66">SerializerMode</a> Mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a serializer that will create its own string table.</p>

<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea0b79eab5aacf81d139c4eaec818a549a">llvm::remarks::Bitstream</a>, <a href="#a65ad27a674514a190c2417b69a79c65c">Helper</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a0bd374f9c556edbdf166ed6d981f5b6f">llvm::remarks::RemarkSerializer::Mode</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#ac7d21a17c33bd0fbb700107a19468973">llvm::remarks::RemarkSerializer::OS</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a78423a0a6a3684579a42b75fb2e85875">llvm::remarks::RemarkSerializer::RemarkSerializer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66a8244cf379b2a4a11d4706e53f510a5f6">llvm::remarks::Separate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea2a431092369d68b3ddf5f61852fee1a9">llvm::remarks::SeparateRemarksFile</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#aa72574e7bd50aa35940e878f31635e1a">llvm::remarks::RemarkSerializer::StrTab</a>.</p>

</div>
</div>

### BitstreamRemarkSerializer() {#ad29d9a4e5bd223b77ecd204b5061ca00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamRemarkSerializer::BitstreamRemarkSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66">SerializerMode</a> Mode, <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> StrTab)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a serializer with a pre-filled string table.</p>

<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea0b79eab5aacf81d139c4eaec818a549a">llvm::remarks::Bitstream</a>, <a href="#a65ad27a674514a190c2417b69a79c65c">Helper</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a0bd374f9c556edbdf166ed6d981f5b6f">llvm::remarks::RemarkSerializer::Mode</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#ac7d21a17c33bd0fbb700107a19468973">llvm::remarks::RemarkSerializer::OS</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a78423a0a6a3684579a42b75fb2e85875">llvm::remarks::RemarkSerializer::RemarkSerializer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66a8244cf379b2a4a11d4706e53f510a5f6">llvm::remarks::Separate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea2a431092369d68b3ddf5f61852fee1a9">llvm::remarks::SeparateRemarksFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea5c80f101108a356211fcb26b3f83eabb">llvm::remarks::Standalone</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#aa72574e7bd50aa35940e878f31635e1a">llvm::remarks::RemarkSerializer::StrTab</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a7e6b2c791986011c32c7a0d37739bd49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitstreamRemarkSerializer::emit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp; Remark)</td>
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

<p>Emit a remark to the stream.</p>


<p>This also emits the metadata associated to the remarks based on the <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66">SerializerMode</a> specified at construction. This writes the serialized output to the provided stream.</p>


<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b04e17884b4aab23e73cf48d515d1b5">DidSetUp</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/metaserializer/#a0127be2f36d1c1fa93cc08df861a8d56">llvm::remarks::MetaSerializer::emit</a>, <a href="#a65ad27a674514a190c2417b69a79c65c">Helper</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#ac7d21a17c33bd0fbb700107a19468973">llvm::remarks::RemarkSerializer::OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea5c80f101108a356211fcb26b3f83eabb">llvm::remarks::Standalone</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#aa72574e7bd50aa35940e878f31635e1a">llvm::remarks::RemarkSerializer::StrTab</a>.</p>

</div>
</div>

### metaSerializer() {#abc127a6ed6eab26d127985ec8c38ef0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MetaSerializer &gt; BitstreamRemarkSerializer::metaSerializer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; ExternalFilename=std::nullopt)</td>
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

<p>The metadata serializer associated to this remark serializer.</p>


<p>Based on the container type of the current serializer, the container type of the metadata serializer will change.</p>


<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a65ad27a674514a190c2417b69a79c65c">Helper</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#ac7d21a17c33bd0fbb700107a19468973">llvm::remarks::RemarkSerializer::OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea4169738237fc9d6c1463bd5260de6c91">llvm::remarks::SeparateRemarksMeta</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a07f17102dd54c318b10c6c6009e27e1ea5c80f101108a356211fcb26b3f83eabb">llvm::remarks::Standalone</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#aa72574e7bd50aa35940e878f31635e1a">llvm::remarks::RemarkSerializer::StrTab</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DidSetUp {#a4b04e17884b4aab23e73cf48d515d1b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::remarks::BitstreamRemarkSerializer::DidSetUp = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The file should contain: 1) The block info block that describes how to read the blocks.</p>


<p>2) The metadata block that contains various information about the remarks in the file. 3) A number of remark blocks. We need to set up 1) and 2) first, so that we can emit 3) after. This flag is used to emit the first two blocks only once.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#a7e6b2c791986011c32c7a0d37739bd49">emit</a>.</p>

</div>
</div>

### Helper {#a65ad27a674514a190c2417b69a79c65c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamRemarkSerializerHelper llvm::remarks::BitstreamRemarkSerializer::Helper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The helper to emit bitstream.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>Referenced by <a href="#a42696d420acd17e7e8ab585db9f0b5c4">BitstreamRemarkSerializer</a>, <a href="#ad29d9a4e5bd223b77ecd204b5061ca00">BitstreamRemarkSerializer</a>, <a href="#a7e6b2c791986011c32c7a0d37739bd49">emit</a> and <a href="#abc127a6ed6eab26d127985ec8c38ef0f">metaSerializer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a6ad59c8c4d42d338abf808697597855a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::remarks::BitstreamRemarkSerializer::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer">RemarkSerializer</a> * S)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea0b79eab5aacf81d139c4eaec818a549a">llvm::remarks::Bitstream</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a78423a0a6a3684579a42b75fb2e85875">llvm::remarks::RemarkSerializer::RemarkSerializer</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkserializer/#a062e25757dafc42e1222cb5df962d267">llvm::remarks::RemarkSerializer::SerializerFormat</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/bitstreamremarkserializer-h">BitstreamRemarkSerializer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp">BitstreamRemarkSerializer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
