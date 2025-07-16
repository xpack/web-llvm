---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/msgpack/object
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Object` Struct Reference

<p>MessagePack object, represented as a tagged union of C++ types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::msgpack::Object { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">llvm/BinaryFormat/MsgPackReader.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a921e8682e988ea3f50a999f33a18dbdf">Object</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c189db1e185c4452f4bb32835d4609">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b2cf114cfacc839eb297fbda910251f">Int</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a1686a6c336b71b36d77354cea19a8b52">Type::Int</a></span>. <a href="#a0b2cf114cfacc839eb297fbda910251f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75139a8d216034cb6340d63dbcbc17c3">UInt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput">Type::Uint</span>. <a href="#a75139a8d216034cb6340d63dbcbc17c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a900f97ddaa7e4a41529ce65ccbee434c">Bool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27226c864bac7454a8504f8edb15d95b">Type::Boolean</a></span>. <a href="#a900f97ddaa7e4a41529ce65ccbee434c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6e0f8746aa6b37252d1486b9a6c934">Float</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a22ae0e2b89e5e3d477f988cc36d3272b">Type::Float</a></span>. <a href="#a2a6e0f8746aa6b37252d1486b9a6c934">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bdfab2d7d4b7820ec82336a6c498a4c">Raw</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27118326006d3829667a400ad23d5d98">Type::String</a></span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a6ce976e8f061b2b5cfe4d0c50c3405dd">Type::Binary</a></span>. <a href="#a2bdfab2d7d4b7820ec82336a6c498a4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb776758ebe06e1aa3bc537b7b90c5cb">Length</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4410ec34d9e6c1a68100ca0ce033fb17">Type::Array</a></span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a46f3ea056caa3126b91f3f70beea068c">Type::Map</a></span>. <a href="#afb776758ebe06e1aa3bc537b7b90c5cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/msgpack/extensiontype">ExtensionType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb15d85573fbf4975061692fb654d4b4">Extension</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a63e4e92bb7d207ca577b11c07f827279">Type::Extension</a></span>. <a href="#afb15d85573fbf4975061692fb654d4b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/msgpack/object">llvm::msgpack::Object</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7efdca09725ea7d3712628363155304"></a></td>
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

<p>MessagePack object, represented as a tagged union of C++ types.</p>


<p>All types except <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4da8b7eb2c3f2007cf8238334401ef51">Type::Nil</a></span> (which has only one value, and so is completely represented by the <span class="doxyComputerOutput">Kind</span> itself) map to a exactly one union member.</p>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Object() {#a921e8682e988ea3f50a999f33a18dbdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::msgpack::Object::Object ()</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>


<p>References <a href="#a0b2cf114cfacc839eb297fbda910251f">Int</a> and <a href="#a40c189db1e185c4452f4bb32835d4609">Kind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#ae7efdca09725ea7d3712628363155304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::msgpack::Object llvm::msgpack::Object</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>

</div>
</div>

### Bool {#a900f97ddaa7e4a41529ce65ccbee434c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msgpack::Object::Bool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27226c864bac7454a8504f8edb15d95b">Type::Boolean</a></span>.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/reader/#a4f20ee2ca37e3839b73900aef8e26ac5">llvm::msgpack::Reader::read</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a>.</p>

</div>
</div>

### Extension {#afb15d85573fbf4975061692fb654d4b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExtensionType llvm::msgpack::Object::Extension</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a63e4e92bb7d207ca577b11c07f827279">Type::Extension</a></span>.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>

</div>
</div>

### Float {#a2a6e0f8746aa6b37252d1486b9a6c934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::msgpack::Object::Float</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a22ae0e2b89e5e3d477f988cc36d3272b">Type::Float</a></span>.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/reader/#a4f20ee2ca37e3839b73900aef8e26ac5">llvm::msgpack::Reader::read</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a>.</p>

</div>
</div>

### Int {#a0b2cf114cfacc839eb297fbda910251f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::msgpack::Object::Int</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a1686a6c336b71b36d77354cea19a8b52">Type::Int</a></span>.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>


<p>Referenced by <a href="#a921e8682e988ea3f50a999f33a18dbdf">Object</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/reader/#a4f20ee2ca37e3839b73900aef8e26ac5">llvm::msgpack::Reader::read</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a>.</p>

</div>
</div>

### Kind {#a40c189db1e185c4452f4bb32835d4609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::msgpack::Object::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>


<p>Referenced by <a href="#a921e8682e988ea3f50a999f33a18dbdf">Object</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/reader/#a4f20ee2ca37e3839b73900aef8e26ac5">llvm::msgpack::Reader::read</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a>.</p>

</div>
</div>

### Length {#afb776758ebe06e1aa3bc537b7b90c5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::msgpack::Object::Length</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4410ec34d9e6c1a68100ca0ce033fb17">Type::Array</a></span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a46f3ea056caa3126b91f3f70beea068c">Type::Map</a></span>.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/reader/#a4f20ee2ca37e3839b73900aef8e26ac5">llvm::msgpack::Reader::read</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a>.</p>

</div>
</div>

### Raw {#a2bdfab2d7d4b7820ec82336a6c498a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::msgpack::Object::Raw</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27118326006d3829667a400ad23d5d98">Type::String</a></span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a6ce976e8f061b2b5cfe4d0c50c3405dd">Type::Binary</a></span>.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a>.</p>

</div>
</div>

### UInt {#a75139a8d216034cb6340d63dbcbc17c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::msgpack::Object::UInt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for <span class="doxyComputerOutput">Type::Uint</span>.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/reader/#a4f20ee2ca37e3839b73900aef8e26ac5">llvm::msgpack::Reader::read</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
