---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/msgpack/mapdocnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MapDocNode` Class Reference

<p>A <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> that is a map. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::msgpack::MapDocNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">llvm/BinaryFormat/MsgPackDocument.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A node in a MsgPack <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d014b68b47e116fbe986d8c8f467239">MapDocNode</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42a79d432d9684765f8d3bcd3ed6a5e7">MapDocNode</a> (DocNode &amp;N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab551a82cec3f48431086a831936b7b3e">operator[]</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Member access. <a href="#ab551a82cec3f48431086a831936b7b3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeda90977a3a2d3a4ebf597cbd7b29694">operator[]</a> (DocNode Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Member access, with convenience versions for an integer key. <a href="#aeda90977a3a2d3a4ebf597cbd7b29694">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0438521060cc6dfd4b8b72efe3001e0">operator[]</a> (int Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Member access for <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">MapDocNode</a> for integer key. <a href="#ad0438521060cc6dfd4b8b72efe3001e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b037777503503f8a729ae8004625673">operator[]</a> (unsigned Key)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43d0afd4345b22cc90030df145e32140">operator[]</a> (int64_t Key)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e54eb8048e5f3b4eca3f8e129fd598">operator[]</a> (uint64_t Key)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d82d52907b09b2e4f9c657b17487bb8">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ef3f2e7a98ba8152cf24bd373f52c4">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MapTy::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f0767ec1c79e32931f71bc67b7e3b5b">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MapTy::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa782c90a40bee89192e839c1cfe2026d">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MapTy::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27c125345231b036f832814134ea95b4">find</a> (DocNode Key)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MapTy::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dea266109363b32fed08d85efa46523">find</a> (StringRef Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the key in the <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">MapDocNode</a>. <a href="#a2dea266109363b32fed08d85efa46523">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">MapTy::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac76af25be2986958c8175ddc7b85ad29">erase</a> (MapTy::const_iterator I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9faaea1483f0af67b2925acda7f638b5">erase</a> (DocNode Key)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MapTy::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d89a18fb5a460f0bfd7d703088e40b5">erase</a> (MapTy::const_iterator First, MapTy::const_iterator Second)</td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> that is a map.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MapDocNode() {#a4d014b68b47e116fbe986d8c8f467239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::msgpack::MapDocNode::MapDocNode ()</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

### MapDocNode() {#a42a79d432d9684765f8d3bcd3ed6a5e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::msgpack::MapDocNode::MapDocNode (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp; N)</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a3ed9efe27c6b7fcf2faef82736f3617a">llvm::msgpack::DocNode::getKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a46f3ea056caa3126b91f3f70beea068c">llvm::msgpack::Map</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#ab551a82cec3f48431086a831936b7b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; MapDocNode::operator[] (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Member access.</p>


<p>Member access for <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">MapDocNode</a>.</p>


<p>The string data must remain valid for the lifetime of the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>


<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#afb24ac524a469733ad7e1cd3f1de9dc5">llvm::msgpack::DocNode::getDocument</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a>.</p>

</div>
</div>

### operator\[\]() {#aeda90977a3a2d3a4ebf597cbd7b29694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; MapDocNode::operator[] (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> Key)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Member access, with convenience versions for an integer key.</p>


<p>Member access for <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">MapDocNode</a>.</p>


<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#afb24ac524a469733ad7e1cd3f1de9dc5">llvm::msgpack::DocNode::getDocument</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a58d0878f182d83be836a4081448a16b1">llvm::msgpack::Document::getEmptyNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### operator\[\]() {#ad0438521060cc6dfd4b8b72efe3001e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; MapDocNode::operator[] (int Key)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Member access for <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">MapDocNode</a> for integer key.</p>

<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#afb24ac524a469733ad7e1cd3f1de9dc5">llvm::msgpack::DocNode::getDocument</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### operator\[\]() {#a1b037777503503f8a729ae8004625673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; MapDocNode::operator[] (unsigned Key)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#afb24ac524a469733ad7e1cd3f1de9dc5">llvm::msgpack::DocNode::getDocument</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### operator\[\]() {#a43d0afd4345b22cc90030df145e32140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; MapDocNode::operator[] (int64_t Key)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#afb24ac524a469733ad7e1cd3f1de9dc5">llvm::msgpack::DocNode::getDocument</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### operator\[\]() {#a84e54eb8048e5f3b4eca3f8e129fd598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; MapDocNode::operator[] (uint64_t Key)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#afb24ac524a469733ad7e1cd3f1de9dc5">llvm::msgpack::DocNode::getDocument</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a1f0767ec1c79e32931f71bc67b7e3b5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapTy::iterator llvm::msgpack::MapDocNode::begin ()</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#adcc097d224c8c39ed85b9a938e11a36e">llvm::msgpack::DocNode::Map</a>.</p>

</div>
</div>

### empty() {#aa2ef3f2e7a98ba8152cf24bd373f52c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msgpack::MapDocNode::empty ()</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Reference <a href="#a3d82d52907b09b2e4f9c657b17487bb8">size</a>.</p>

</div>
</div>

### end() {#aa782c90a40bee89192e839c1cfe2026d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapTy::iterator llvm::msgpack::MapDocNode::end ()</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#adcc097d224c8c39ed85b9a938e11a36e">llvm::msgpack::DocNode::Map</a>.</p>

</div>
</div>

### erase() {#ac76af25be2986958c8175ddc7b85ad29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapTy::iterator llvm::msgpack::MapDocNode::erase (MapTy::const_iterator I)</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#adcc097d224c8c39ed85b9a938e11a36e">llvm::msgpack::DocNode::Map</a>.</p>

</div>
</div>

### erase() {#a9faaea1483f0af67b2925acda7f638b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::msgpack::MapDocNode::erase (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> Key)</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#adcc097d224c8c39ed85b9a938e11a36e">llvm::msgpack::DocNode::Map</a>.</p>

</div>
</div>

### erase() {#a3d89a18fb5a460f0bfd7d703088e40b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapTy::iterator llvm::msgpack::MapDocNode::erase (MapTy::const_iterator First, MapTy::const_iterator Second)</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#adcc097d224c8c39ed85b9a938e11a36e">llvm::msgpack::DocNode::Map</a>.</p>

</div>
</div>

### find() {#a27c125345231b036f832814134ea95b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapTy::iterator llvm::msgpack::MapDocNode::find (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> Key)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#adcc097d224c8c39ed85b9a938e11a36e">llvm::msgpack::DocNode::Map</a>.</p>


<p>Referenced by <a href="#a2dea266109363b32fed08d85efa46523">find</a>.</p>

</div>
</div>

### find() {#a2dea266109363b32fed08d85efa46523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode::MapTy::iterator MapDocNode::find (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the key in the <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">MapDocNode</a>.</p>

<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="#a27c125345231b036f832814134ea95b4">find</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#afb24ac524a469733ad7e1cd3f1de9dc5">llvm::msgpack::DocNode::getDocument</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a>.</p>

</div>
</div>

### size() {#a3d82d52907b09b2e4f9c657b17487bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::msgpack::MapDocNode::size ()</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#adcc097d224c8c39ed85b9a938e11a36e">llvm::msgpack::DocNode::Map</a>.</p>


<p>Referenced by <a href="#aa2ef3f2e7a98ba8152cf24bd373f52c4">empty</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
