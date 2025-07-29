---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/minidumpyaml/textcontentstream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TextContentStream` Struct

<p>A <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, which is printed using YAML block notation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MinidumpYAML::TextContentStream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">llvm/ObjectYAML/MinidumpYAML.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream">Stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The base class for all minidump streams. <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd971b68174fad0d2d1853e1cedb8006">TextContentStream</a> (minidump::StreamType Type, StringRef Text={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">BlockStringRef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a222fe55302b8b2c4d34fecc0934712d3">Text</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19f20c942ad72778142aa5b1de586a52">classof</a> (const Stream *S)</td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, which is printed using YAML block notation.</p>


<p>A minidump stream containing textual data (typically, the contents of a /proc/&lt;pid&gt; file on linux).</p>


<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TextContentStream() {#acd971b68174fad0d2d1853e1cedb8006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MinidumpYAML::TextContentStream::TextContentStream (<a href="/web-llvm/docs/api/namespaces/llvm/minidump/#aa8cbdda4c517e8f73a3f150077295280">minidump::StreamType</a> Type, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Text={})</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>References <a href="#a222fe55302b8b2c4d34fecc0934712d3">Text</a> and <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#ac752f3d2d3fbedb56cc912c2123d0a45">llvm::MinidumpYAML::Stream::Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Text {#a222fe55302b8b2c4d34fecc0934712d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockStringRef llvm::MinidumpYAML::TextContentStream::Text</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>Referenced by <a href="#acd971b68174fad0d2d1853e1cedb8006">TextContentStream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a19f20c942ad72778142aa5b1de586a52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MinidumpYAML::TextContentStream::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream">Stream</a> * S)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a492be506d939f72ca251976bc543d2a0">llvm::MinidumpYAML::Stream::Kind</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a8522621888f28e27ba36290efcdc04bc">llvm::MinidumpYAML::Stream::Stream</a> and <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abcae03ab724014b7833bdc333912ed9db12">llvm::MinidumpYAML::Stream::TextContent</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
