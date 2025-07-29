---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/msgpack/document
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Document` Class

<p>Simple in-memory representation of a document of msgpack objects with ability to find and create array and map elements. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::msgpack::Document { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">llvm/BinaryFormat/MsgPackDocument.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdbc82cd8e3f3c6c8514a49fdfe91270">Document</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5deadb4fe33da953cf16a27551f02c3c">getRoot</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get ref to the document's root element. <a href="#a5deadb4fe33da953cf16a27551f02c3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a652965396b20331b4d45122baba0eccc">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Restore the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a> to an empty state. <a href="#a652965396b20331b4d45122baba0eccc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58d0878f182d83be836a4081448a16b1">getEmptyNode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an empty node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#a58d0878f182d83be836a4081448a16b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d5fb2463b89c95b17ffffcef9cf7f4e">getNode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a nil node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#a6d5fb2463b89c95b17ffffcef9cf7f4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b94a260cad744fb7871a0ff6e15838f">getNode</a> (int64_t V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an Int node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#a7b94a260cad744fb7871a0ff6e15838f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae058e5223d395e89d7f8a63a22f65f3">getNode</a> (int V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an Int node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#aae058e5223d395e89d7f8a63a22f65f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a622493610a44dfcbba874f9fe7a5583b">getNode</a> (uint64_t V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a UInt node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#a622493610a44dfcbba874f9fe7a5583b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ebb06f24a82047ec691bd8b1ccac4f3">getNode</a> (unsigned V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a UInt node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#a0ebb06f24a82047ec691bd8b1ccac4f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a852305a31c763efece584325cb814441">getNode</a> (bool V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a Boolean node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#a852305a31c763efece584325cb814441">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bd41a83d5d273091ac8b9f5fd633197">getNode</a> (double V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a Float node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#a3bd41a83d5d273091ac8b9f5fd633197">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a337d91aa41dbe0ed407a0cd267c3a208">getNode</a> (StringRef V, bool Copy=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a String node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#a337d91aa41dbe0ed407a0cd267c3a208">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf75cd657f70fe892ae9201ed9db9296">getNode</a> (const char *V, bool Copy=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a String node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#abf75cd657f70fe892ae9201ed9db9296">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8e2909cdbfc27ac0ec2c2710b633300">getNode</a> (MemoryBufferRef V, bool Copy=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a Binary node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#af8e2909cdbfc27ac0ec2c2710b633300">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">MapDocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47c7647f08d2672561d925ce3c291dd3">getMapNode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an empty Map node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#a47c7647f08d2672561d925ce3c291dd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode">ArrayDocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e361fdc7f6a0c9dd44e46c0f020b46e">getArrayNode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an empty Array node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#a6e361fdc7f6a0c9dd44e46c0f020b46e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1132fee67332a4c0a707984b97f9b52">readFromBlob</a> (StringRef Blob, bool Multi, function_ref&lt; int(DocNode *DestNode, DocNode SrcNode, DocNode MapKey)&gt; Merger=[](DocNode *DestNode, DocNode SrcNode, DocNode MapKey) { return -1;})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read a document from a binary msgpack blob, merging into anything already in the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#aa1132fee67332a4c0a707984b97f9b52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f94c9dc628a8565363014088523a0fa">writeToBlob</a> (std::string &amp;Blob)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a MsgPack document to a binary MsgPack blob. <a href="#a8f94c9dc628a8565363014088523a0fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1accb391b511ed37f3b8b88f773f09c">addString</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy a string into the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>'s strings list, and return the copy that is owned by the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#aa1accb391b511ed37f3b8b88f773f09c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eaa9ace85c8de5372f56901aca561e4">setHexMode</a> (bool Val=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether YAML output uses hex for UInt. Default off. <a href="#a7eaa9ace85c8de5372f56901aca561e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a023584d9bd4eef5c0c296d73ca327f0b">getHexMode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get Hexmode flag. <a href="#a023584d9bd4eef5c0c296d73ca327f0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82205f2c71cb88331e554cb4fc8b8822">toYAML</a> (raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert MsgPack <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a> to YAML text. <a href="#a82205f2c71cb88331e554cb4fc8b8822">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abec5174f9edec79de20397f6b8e0ccdf">fromYAML</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read YAML text into the MsgPack document. Returns false on failure. <a href="#abec5174f9edec79de20397f6b8e0ccdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a4c045ba223a97b258ea4a6e1e76b7727">DocNode::MapTy</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a943cfad5da263fb2b4c509cfa84afee6">Maps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#ad07796bcfea70271f5cf0ee66cf568b4">DocNode::ArrayTy</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbad885e4497d71f0f59051a6d30a2d3">Arrays</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; char[]&gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55e3c67a4ddc9472cc12a36653439e96">Strings</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a703ea7d0083310fd04badc0b2bfd9fa2">Root</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/msgpack/kindanddocument">KindAndDocument</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e8e8cae58224b46361623eff7b6b002">KindAndDocs</a>[size_t(Type::Empty)+1]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10b35e57f871a82c67683e7af224ae20">HexMode</a> = false</td>
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

<p>Simple in-memory representation of a document of msgpack objects with ability to find and create array and map elements.</p>


<p>Does not currently cope with any extension types.</p>


<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Document() {#acdbc82cd8e3f3c6c8514a49fdfe91270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::msgpack::Document::Document ()</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="#a652965396b20331b4d45122baba0eccc">clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6ace2c8aed9c2fa0cfbed56cbda4d8bf07">llvm::msgpack::Empty</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addString() {#aa1accb391b511ed37f3b8b88f773f09c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::msgpack::Document::addString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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

<p>Copy a string into the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>'s strings list, and return the copy that is owned by the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>

<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#af8e2909cdbfc27ac0ec2c2710b633300">getNode</a> and <a href="#a337d91aa41dbe0ed407a0cd267c3a208">getNode</a>.</p>

</div>
</div>

### clear() {#a652965396b20331b4d45122baba0eccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::msgpack::Document::clear ()</td>
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

<p>Restore the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a> to an empty state.</p>

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="#a58d0878f182d83be836a4081448a16b1">getEmptyNode</a> and <a href="#a5deadb4fe33da953cf16a27551f02c3c">getRoot</a>.</p>


<p>Referenced by <a href="#acdbc82cd8e3f3c6c8514a49fdfe91270">Document</a> and <a href="#abec5174f9edec79de20397f6b8e0ccdf">fromYAML</a>.</p>

</div>
</div>

### fromYAML() {#abec5174f9edec79de20397f6b8e0ccdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool msgpack::Document::fromYAML (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read YAML text into the MsgPack document. Returns false on failure.</p>

<p>Declaration at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocumentyaml-cpp">MsgPackDocumentYAML.cpp</a>.</p>


<p>References <a href="#a652965396b20331b4d45122baba0eccc">clear</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/input/#aa353fb192bcd1d2e0561858ad440829b">llvm::yaml::Input::error</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp/#ab590661425ca60ca82edfdb4cf22233d">getRoot</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#a3206989ed2eb7d82c26434da35b469e8">llvm::AMDGPUTargetStreamer::EmitHSAMetadataV3</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#ab08f2a767eab0b5eb8db953d35d80b03">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::verify</a>.</p>

</div>
</div>

### getArrayNode() {#a6e361fdc7f6a0c9dd44e46c0f020b46e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayDocNode llvm::msgpack::Document::getArrayNode ()</td>
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

<p>Create an empty Array node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>

<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4410ec34d9e6c1a68100ca0ce033fb17">llvm::msgpack::Array</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a161232fcda35d33312029e1d80015b77">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelLanguage</a> and <a href="#aa1132fee67332a4c0a707984b97f9b52">readFromBlob</a>.</p>

</div>
</div>

### getEmptyNode() {#a58d0878f182d83be836a4081448a16b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode llvm::msgpack::Document::getEmptyNode ()</td>
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

<p>Create an empty node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>

<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6ace2c8aed9c2fa0cfbed56cbda4d8bf07">llvm::msgpack::Empty</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a652965396b20331b4d45122baba0eccc">clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#aeda90977a3a2d3a4ebf597cbd7b29694">llvm::msgpack::MapDocNode::operator[]</a>.</p>

</div>
</div>

### getHexMode() {#a023584d9bd4eef5c0c296d73ca327f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msgpack::Document::getHexMode ()</td>
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

<p>Get Hexmode flag.</p>

<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

### getMapNode() {#a47c7647f08d2672561d925ce3c291dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapDocNode llvm::msgpack::Document::getMapNode ()</td>
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

<p>Create an empty Map node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>

<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a46f3ea056caa3126b91f3f70beea068c">llvm::msgpack::Map</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#aa1132fee67332a4c0a707984b97f9b52">readFromBlob</a>.</p>

</div>
</div>

### getNode() {#a6d5fb2463b89c95b17ffffcef9cf7f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode llvm::msgpack::Document::getNode ()</td>
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

<p>Create a nil node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>

<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4da8b7eb2c3f2007cf8238334401ef51">llvm::msgpack::Nil</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a2877b4f51a65483c451edd59a4704df6">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv5/#ae8b78bc8c92db11a11ca0cf7f7fc6f90">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV5::emitKernelAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a161232fcda35d33312029e1d80015b77">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelLanguage</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0a2160ffa04d67291e2827a29994a3b9">llvm::msgpack::DocNode::fromString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a>, <a href="#abf75cd657f70fe892ae9201ed9db9296">getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a85f28c20e0b68d334f63d60d21ab7109">llvm::msgpack::DocNode::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a4f88e6587461103193f66c63999b6b36">llvm::msgpack::DocNode::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a091cbf7795bca9759a7f6aa86c692dfc">llvm::msgpack::DocNode::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#ae799c9c9dda75bf386ee714a0db638a8">llvm::msgpack::DocNode::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a3b9b31645cb2a12ab5c315725ba367b1">llvm::msgpack::DocNode::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0312cc6e961a6b29ea43d313e17f3009">llvm::msgpack::DocNode::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#ad31b00a8fa469faa012f219a7f9466a1">llvm::msgpack::DocNode::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#ad0438521060cc6dfd4b8b72efe3001e0">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a43d0afd4345b22cc90030df145e32140">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#ab551a82cec3f48431086a831936b7b3e">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a84e54eb8048e5f3b4eca3f8e129fd598">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a1b037777503503f8a729ae8004625673">llvm::msgpack::MapDocNode::operator[]</a> and <a href="#aa1132fee67332a4c0a707984b97f9b52">readFromBlob</a>.</p>

</div>
</div>

### getNode() {#a7b94a260cad744fb7871a0ff6e15838f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode llvm::msgpack::Document::getNode (int64_t V)</td>
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

<p>Create an Int node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>

<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a1686a6c336b71b36d77354cea19a8b52">llvm::msgpack::Int</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getNode() {#aae058e5223d395e89d7f8a63a22f65f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode llvm::msgpack::Document::getNode (int V)</td>
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

<p>Create an Int node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>

<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a1686a6c336b71b36d77354cea19a8b52">llvm::msgpack::Int</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getNode() {#a622493610a44dfcbba874f9fe7a5583b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode llvm::msgpack::Document::getNode (uint64_t V)</td>
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

<p>Create a UInt node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>

<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>

</div>
</div>

### getNode() {#a0ebb06f24a82047ec691bd8b1ccac4f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode llvm::msgpack::Document::getNode (unsigned V)</td>
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

<p>Create a UInt node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>

</div>
</div>

### getNode() {#a852305a31c763efece584325cb814441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode llvm::msgpack::Document::getNode (bool V)</td>
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

<p>Create a Boolean node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>

<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27226c864bac7454a8504f8edb15d95b">llvm::msgpack::Boolean</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getNode() {#a3bd41a83d5d273091ac8b9f5fd633197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode llvm::msgpack::Document::getNode (double V)</td>
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

<p>Create a Float node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a22ae0e2b89e5e3d477f988cc36d3272b">llvm::msgpack::Float</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getNode() {#a337d91aa41dbe0ed407a0cd267c3a208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode llvm::msgpack::Document::getNode (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> V, bool Copy=false)</td>
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

<p>Create a String node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>


<p>If !Copy, the passed string must remain valid for the lifetime of the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>


<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="#aa1accb391b511ed37f3b8b88f773f09c">addString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27118326006d3829667a400ad23d5d98">llvm::msgpack::String</a>.</p>

</div>
</div>

### getNode() {#abf75cd657f70fe892ae9201ed9db9296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode llvm::msgpack::Document::getNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * V, bool Copy=false)</td>
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

<p>Create a String node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>


<p>If !Copy, the passed string must remain valid for the lifetime of the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>


<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Reference <a href="#a6d5fb2463b89c95b17ffffcef9cf7f4e">getNode</a>.</p>

</div>
</div>

### getNode() {#af8e2909cdbfc27ac0ec2c2710b633300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode llvm::msgpack::Document::getNode (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> V, bool Copy=false)</td>
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

<p>Create a Binary node associated with this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>


<p>If !Copy, the passed buffer must remain valid for the lifetime of the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>


<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="#aa1accb391b511ed37f3b8b88f773f09c">addString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a6ce976e8f061b2b5cfe4d0c50c3405dd">llvm::msgpack::Binary</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getRoot() {#a5deadb4fe33da953cf16a27551f02c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; llvm::msgpack::Document::getRoot ()</td>
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

<p>Get ref to the document's root element.</p>

<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Referenced by <a href="#a652965396b20331b4d45122baba0eccc">clear</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#a3ea71f46259463a2379530358a02d372">llvm::AMDGPUTargetAsmStreamer::EmitHSAMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a5f962a3da2e5e21ea73c8a2ba3d60cf1">llvm::AMDGPUTargetELFStreamer::EmitHSAMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-utility-cpp-/kernelinforeader/#aa4be56491fd1f1bfc2d12285da64e4a0">anonymous{Utility.cpp}::KernelInfoReader::processNote</a> and <a href="#a8f94c9dc628a8565363014088523a0fa">writeToBlob</a>.</p>

</div>
</div>

### readFromBlob() {#aa1132fee67332a4c0a707984b97f9b52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Document::readFromBlob (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Blob, bool Multi, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; int(<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> *DestNode, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> SrcNode, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> MapKey)&gt; Merger=[](<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> *DestNode, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> SrcNode, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> MapKey) { return -1;})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read a document from a binary msgpack blob, merging into anything already in the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>


<p>The blob data must remain valid for the lifetime of this <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a> (because a string object in the document contains a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> into the original blob). If Multi, then this sets root to an array and adds top-level objects to it. If !Multi, then it only reads a single top-level object, even if there are more, and sets root to that. Returns false if failed due to illegal format or merge error.</p>


<p>The Merger arg is a callback function that is called when the merge has a conflict, that is, it is trying to set an item that is already set. If the conflict cannot be resolved, the callback function returns -1. If the conflict can be resolved, the callback returns a non-negative number and sets *DestNode to the resolved node. The returned non-negative number is significant only for an array node; it is then the array index to start populating at. That allows Merger to choose whether to merge array elements (returns 0) or append new elements (returns existing size).</p>


<p>If SrcNode is an array or map, the resolution must be that *DestNode is an array or map respectively, although it could be the array or map (respectively) that was already there. MapKey is the key if *DestNode is a map entry, a nil node otherwise.</p>


<p>The default for Merger is to disallow any conflict.</p>


<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4410ec34d9e6c1a68100ca0ce033fb17">llvm::msgpack::Array</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a6ce976e8f061b2b5cfe4d0c50c3405dd">llvm::msgpack::Binary</a>, <a href="/web-llvm/docs/api/structs/llvm/msgpack/object/#a900f97ddaa7e4a41529ce65ccbee434c">llvm::msgpack::Object::Bool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27226c864bac7454a8504f8edb15d95b">llvm::msgpack::Boolean</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/structs/llvm/msgpack/object/#a2a6e0f8746aa6b37252d1486b9a6c934">llvm::msgpack::Object::Float</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a22ae0e2b89e5e3d477f988cc36d3272b">llvm::msgpack::Float</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a6e361fdc7f6a0c9dd44e46c0f020b46e">getArrayNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a3ed9efe27c6b7fcf2faef82736f3617a">llvm::msgpack::DocNode::getKind</a>, <a href="#a47c7647f08d2672561d925ce3c291dd3">getMapNode</a>, <a href="#a6d5fb2463b89c95b17ffffcef9cf7f4e">getNode</a>, <a href="/web-llvm/docs/api/structs/llvm/msgpack/object/#a0b2cf114cfacc839eb297fbda910251f">llvm::msgpack::Object::Int</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a1686a6c336b71b36d77354cea19a8b52">llvm::msgpack::Int</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a7baf73f31a4531f8214a287c9c107fcc">llvm::msgpack::DocNode::isArray</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#abe1ba2052b98cee8a31531493c21f559">llvm::msgpack::DocNode::isEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a78440e992da7b87645bb9c7cdb1b6525">llvm::msgpack::DocNode::isMap</a>, <a href="/web-llvm/docs/api/structs/llvm/msgpack/object/#a40c189db1e185c4452f4bb32835d4609">llvm::msgpack::Object::Kind</a>, <a href="/web-llvm/docs/api/structs/llvm/msgpack/object/#afb776758ebe06e1aa3bc537b7b90c5cb">llvm::msgpack::Object::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a46f3ea056caa3126b91f3f70beea068c">llvm::msgpack::Map</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600optimizevectorregisters-cpp/#ae6d00e421255752875ef3bd9919bb05a">Merger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4da8b7eb2c3f2007cf8238334401ef51">llvm::msgpack::Nil</a>, <a href="/web-llvm/docs/api/structs/llvm/msgpack/object/#a2bdfab2d7d4b7820ec82336a6c498a4c">llvm::msgpack::Object::Raw</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/reader/#a4f20ee2ca37e3839b73900aef8e26ac5">llvm::msgpack::Reader::read</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27118326006d3829667a400ad23d5d98">llvm::msgpack::String</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/structs/llvm/msgpack/object/#a75139a8d216034cb6340d63dbcbc17c3">llvm::msgpack::Object::UInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-utility-cpp-/kernelinforeader/#aa4be56491fd1f1bfc2d12285da64e4a0">anonymous{Utility.cpp}::KernelInfoReader::processNote</a>.</p>

</div>
</div>

### setHexMode() {#a7eaa9ace85c8de5372f56901aca561e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::msgpack::Document::setHexMode (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Set whether YAML output uses hex for UInt. Default off.</p>

<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

### toYAML() {#a82205f2c71cb88331e554cb4fc8b8822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void msgpack::Document::toYAML (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert MsgPack <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a> to YAML text.</p>

<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocumentyaml-cpp">MsgPackDocumentYAML.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp/#ab590661425ca60ca82edfdb4cf22233d">getRoot</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#a3ea71f46259463a2379530358a02d372">llvm::AMDGPUTargetAsmStreamer::EmitHSAMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#ab08f2a767eab0b5eb8db953d35d80b03">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::verify</a>.</p>

</div>
</div>

### writeToBlob() {#a8f94c9dc628a8565363014088523a0fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Document::writeToBlob (std::string &amp; Blob)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a MsgPack document to a binary MsgPack blob.</p>

<p>Declaration at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4410ec34d9e6c1a68100ca0ce033fb17">llvm::msgpack::Array</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a6ce976e8f061b2b5cfe4d0c50c3405dd">llvm::msgpack::Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27226c864bac7454a8504f8edb15d95b">llvm::msgpack::Boolean</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6ace2c8aed9c2fa0cfbed56cbda4d8bf07">llvm::msgpack::Empty</a>, <a href="/web-llvm/docs/api/classes/node/#aae5cdb3eedc870de0873aed823149a3a">Node::getKind</a>, <a href="#a5deadb4fe33da953cf16a27551f02c3c">getRoot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a1686a6c336b71b36d77354cea19a8b52">llvm::msgpack::Int</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a46f3ea056caa3126b91f3f70beea068c">llvm::msgpack::Map</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4da8b7eb2c3f2007cf8238334401ef51">llvm::msgpack::Nil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27118326006d3829667a400ad23d5d98">llvm::msgpack::String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/writer/#afc1743f31ddf3870711ebdcc210700c0">llvm::msgpack::Writer::write</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/writer/#a8ed0ae40a1f440ec59f5e7d22b99a65c">llvm::msgpack::Writer::writeArraySize</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/writer/#a50372c2c26c41e47324691f53269072a">llvm::msgpack::Writer::writeMapSize</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/writer/#a0282d6201e15dba0d5fda1a4774e45df">llvm::msgpack::Writer::writeNil</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a5f962a3da2e5e21ea73c8a2ba3d60cf1">llvm::AMDGPUTargetELFStreamer::EmitHSAMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Arrays {#abbad885e4497d71f0f59051a6d30a2d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;DocNode::ArrayTy&gt; &gt; llvm::msgpack::Document::Arrays</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

### HexMode {#a10b35e57f871a82c67683e7af224ae20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msgpack::Document::HexMode = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

### KindAndDocs {#a6e8e8cae58224b46361623eff7b6b002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KindAndDocument llvm::msgpack::Document::KindAndDocs[size_t(Type::Empty)+1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

### Maps {#a943cfad5da263fb2b4c509cfa84afee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;DocNode::MapTy&gt; &gt; llvm::msgpack::Document::Maps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

### Root {#a703ea7d0083310fd04badc0b2bfd9fa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode llvm::msgpack::Document::Root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

### Strings {#a55e3c67a4ddc9472cc12a36653439e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;char[]&gt; &gt; llvm::msgpack::Document::Strings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocumentyaml-cpp">MsgPackDocumentYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
