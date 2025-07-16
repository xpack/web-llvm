---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/minidumpyaml/rawcontentstream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RawContentStream` Struct Reference

<p>A minidump stream represented as a sequence of hex bytes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MinidumpYAML::RawContentStream { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d20bc714bfcbd91e1f196c1c1b7414c">RawContentStream</a> (minidump::StreamType Type, ArrayRef&lt; uint8_t &gt; Content={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/binaryref">yaml::BinaryRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a116bd6e02ac11c3346eefb88cd8b7">Content</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">yaml::Hex32</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcb3707edc430543bb6541aa0fc4445a">Size</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90e2abb4327d0b5c5386e7891fdbbd6a">classof</a> (const Stream *S)</td>
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

<p>A minidump stream represented as a sequence of hex bytes.</p>


<p>This is used as a fallback when no other stream kind is suitable.</p>


<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RawContentStream() {#a8d20bc714bfcbd91e1f196c1c1b7414c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MinidumpYAML::RawContentStream::RawContentStream (<a href="/web-llvm/docs/api/namespaces/llvm/minidump/#aa8cbdda4c517e8f73a3f150077295280">minidump::StreamType</a> Type, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Content={})</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>References <a href="#ad1a116bd6e02ac11c3346eefb88cd8b7">Content</a> and <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#ac752f3d2d3fbedb56cc912c2123d0a45">llvm::MinidumpYAML::Stream::Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Content {#ad1a116bd6e02ac11c3346eefb88cd8b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::BinaryRef llvm::MinidumpYAML::RawContentStream::Content</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>Referenced by <a href="#a8d20bc714bfcbd91e1f196c1c1b7414c">RawContentStream</a>.</p>

</div>
</div>

### Size {#adcb3707edc430543bb6541aa0fc4445a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::Hex32 llvm::MinidumpYAML::RawContentStream::Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpemitter-cpp/#a9572de1ba76b89eae1eb07c8b446b143">layout</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a90e2abb4327d0b5c5386e7891fdbbd6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MinidumpYAML::RawContentStream::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream">Stream</a> * S)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a492be506d939f72ca251976bc543d2a0">llvm::MinidumpYAML::Stream::Kind</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abcac34949db9ce05a7dcfa4cf073b161233">llvm::MinidumpYAML::Stream::RawContent</a> and <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a8522621888f28e27ba36290efcdc04bc">llvm::MinidumpYAML::Stream::Stream</a>.</p>

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
