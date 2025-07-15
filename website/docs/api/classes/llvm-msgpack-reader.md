---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/msgpack/reader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Reader` Class Reference

<p>Reads MessagePack objects from memory, one at a time. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::msgpack::Reader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">llvm/BinaryFormat/MsgPackReader.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ee641a54e5b81c096f00f0dea4a9020">Reader</a> (MemoryBufferRef InputBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a reader, keeping a reference to the <span class="doxyComputerOutput">InputBuffer</span>. <a href="#a3ee641a54e5b81c096f00f0dea4a9020">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cc99a300964976aa65fecceb1a18975">Reader</a> (StringRef Input)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a reader, keeping a reference to the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/input">Input</a></span>. <a href="#a8cc99a300964976aa65fecceb1a18975">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a29f14d34fa5853f3b21bf466a2209e">Reader</a> (const Reader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/reader">Reader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fbc015b191dbb6c8816d8aa81ec9a41">operator=</a> (const Reader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f20ee2ca37e3839b73900aef8e26ac5">read</a> (Object &amp;Obj)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read one object from the input buffer, advancing past it. <a href="#a4f20ee2ca37e3839b73900aef8e26ac5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc72b99668717fde22fd00a1384c456e">remainingSpace</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad579f450f586e8c6d9d353e270be7da5">readRaw</a> (Object &amp;Obj) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a96d50f81e3030565a4fcdea666f3011c">readInt</a> (Object &amp;Obj) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac687413b80c8970240dad62aefae5508">readUInt</a> (Object &amp;Obj) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8fffde66d56a7b2867300eedf90a7a75">readLength</a> (Object &amp;Obj) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6cb50dd97de9ee27ff82416f57a5d2e0">readExt</a> (Object &amp;Obj) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22eca32e4b2e334e36cfe1041f20286d">createRaw</a> (Object &amp;Obj, uint32_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0531d019b8d8695fcc1a0bdf626dfc89">createExt</a> (Object &amp;Obj, uint32_t Size)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15787d5d28ccb9d4c975de6bd06fbb41">InputBuffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a847d7049b29398411837fbffa8aa53ff">Current</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5119a2866b7bd56c697309b0e7524f6">End</a></td>
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

<p>Reads MessagePack objects from memory, one at a time.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Reader() {#a3ee641a54e5b81c096f00f0dea4a9020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Reader::Reader (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> InputBuffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a reader, keeping a reference to the <span class="doxyComputerOutput">InputBuffer</span>.</p>

<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackreader-cpp">MsgPackReader.cpp</a>.</p>


<p>Referenced by <a href="#a8fbc015b191dbb6c8816d8aa81ec9a41">operator=</a>, <a href="#a0a29f14d34fa5853f3b21bf466a2209e">Reader</a> and <a href="#a8cc99a300964976aa65fecceb1a18975">Reader</a>.</p>

</div>
</div>

### Reader() {#a8cc99a300964976aa65fecceb1a18975}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Reader::Reader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Input)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a reader, keeping a reference to the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/input">Input</a></span>.</p>

<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackreader-cpp">MsgPackReader.cpp</a>.</p>


<p>Reference <a href="#a3ee641a54e5b81c096f00f0dea4a9020">Reader</a>.</p>

</div>
</div>

### Reader() {#a0a29f14d34fa5853f3b21bf466a2209e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::msgpack::Reader::Reader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msgpack/reader">Reader</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>


<p>Reference <a href="#a3ee641a54e5b81c096f00f0dea4a9020">Reader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a8fbc015b191dbb6c8816d8aa81ec9a41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Reader &amp; llvm::msgpack::Reader::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msgpack/reader">Reader</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>


<p>Reference <a href="#a3ee641a54e5b81c096f00f0dea4a9020">Reader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### read() {#a4f20ee2ca37e3839b73900aef8e26ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; Reader::read (<a href="/web-llvm/docs/api/structs/llvm/msgpack/object">Object</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read one object from the input buffer, advancing past it.</p>


<p>The <span class="doxyComputerOutput">Obj</span> is updated with the kind of the object read, and the corresponding union member is updated.</p>


<p>For the collection objects (Array and Map), only the length is read, and the caller must make and additional <span class="doxyComputerOutput">N</span> calls (in the case of Array) or <span class="doxyComputerOutput">N*2</span> calls (in the case of Map) to <span class="doxyComputerOutput">Read</span> to retrieve the collection elements.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] Obj</td>
<td class="doxyParamItemDescription"><p>filled with next object on success.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true when object successfully read, false when at end of input (and so <span class="doxyComputerOutput">Obj</span> was not updated), otherwise an error.</p></dd>
</dl>


<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackreader-cpp">MsgPackReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4410ec34d9e6c1a68100ca0ce033fb17">llvm::msgpack::Array</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a6ce976e8f061b2b5cfe4d0c50c3405dd">llvm::msgpack::Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/msgpack/object/#a900f97ddaa7e4a41529ce65ccbee434c">llvm::msgpack::Object::Bool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27226c864bac7454a8504f8edb15d95b">llvm::msgpack::Boolean</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a63e4e92bb7d207ca577b11c07f827279">llvm::msgpack::Extension</a>, <a href="/web-llvm/docs/api/structs/llvm/msgpack/object/#a2a6e0f8746aa6b37252d1486b9a6c934">llvm::msgpack::Object::Float</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a22ae0e2b89e5e3d477f988cc36d3272b">llvm::msgpack::Float</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/msgpack/object/#a0b2cf114cfacc839eb297fbda910251f">llvm::msgpack::Object::Int</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a1686a6c336b71b36d77354cea19a8b52">llvm::msgpack::Int</a>, <a href="/web-llvm/docs/api/structs/llvm/msgpack/object/#a40c189db1e185c4452f4bb32835d4609">llvm::msgpack::Object::Kind</a>, <a href="/web-llvm/docs/api/structs/llvm/msgpack/object/#afb776758ebe06e1aa3bc537b7b90c5cb">llvm::msgpack::Object::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a46f3ea056caa3126b91f3f70beea068c">llvm::msgpack::Map</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4da8b7eb2c3f2007cf8238334401ef51">llvm::msgpack::Nil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#acfdf941f45bc58470ed8423b98862486">llvm::support::endian::read</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27118326006d3829667a400ad23d5d98">llvm::msgpack::String</a>, <a href="/web-llvm/docs/api/structs/llvm/msgpack/object/#a75139a8d216034cb6340d63dbcbc17c3">llvm::msgpack::Object::UInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createExt() {#a0531d019b8d8695fcc1a0bdf626dfc89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; Reader::createExt (<a href="/web-llvm/docs/api/structs/llvm/msgpack/object">Object</a> &amp; Obj, uint32_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackreader-cpp">MsgPackReader.cpp</a>.</p>

</div>
</div>

### createRaw() {#a22eca32e4b2e334e36cfe1041f20286d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; Reader::createRaw (<a href="/web-llvm/docs/api/structs/llvm/msgpack/object">Object</a> &amp; Obj, uint32_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackreader-cpp">MsgPackReader.cpp</a>.</p>

</div>
</div>

### readExt() {#a6cb50dd97de9ee27ff82416f57a5d2e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; Reader::readExt (<a href="/web-llvm/docs/api/structs/llvm/msgpack/object">Object</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackreader-cpp">MsgPackReader.cpp</a>.</p>

</div>
</div>

### readInt() {#a96d50f81e3030565a4fcdea666f3011c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; Reader::readInt (<a href="/web-llvm/docs/api/structs/llvm/msgpack/object">Object</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackreader-cpp">MsgPackReader.cpp</a>.</p>

</div>
</div>

### readLength() {#a8fffde66d56a7b2867300eedf90a7a75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; Reader::readLength (<a href="/web-llvm/docs/api/structs/llvm/msgpack/object">Object</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackreader-cpp">MsgPackReader.cpp</a>.</p>

</div>
</div>

### readRaw() {#ad579f450f586e8c6d9d353e270be7da5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; Reader::readRaw (<a href="/web-llvm/docs/api/structs/llvm/msgpack/object">Object</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackreader-cpp">MsgPackReader.cpp</a>.</p>

</div>
</div>

### readUInt() {#ac687413b80c8970240dad62aefae5508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; Reader::readUInt (<a href="/web-llvm/docs/api/structs/llvm/msgpack/object">Object</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackreader-cpp">MsgPackReader.cpp</a>.</p>

</div>
</div>

### remainingSpace() {#adc72b99668717fde22fd00a1384c456e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::msgpack::Reader::remainingSpace ()</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Current {#a847d7049b29398411837fbffa8aa53ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::iterator llvm::msgpack::Reader::Current</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>

</div>
</div>

### End {#aa5119a2866b7bd56c697309b0e7524f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::iterator llvm::msgpack::Reader::End</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>

</div>
</div>

### InputBuffer {#a15787d5d28ccb9d4c975de6bd06fbb41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryBufferRef llvm::msgpack::Reader::InputBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackreader-h">MsgPackReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackreader-cpp">MsgPackReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
