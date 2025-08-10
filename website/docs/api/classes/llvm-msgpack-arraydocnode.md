---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/msgpack/arraydocnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ArrayDocNode` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> that is an array. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::msgpack::ArrayDocNode { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d3ea4c9dfc2b681633c2684ca5c3b5f">ArrayDocNode</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a321c0ea44e257246ee630eb346be23fa">ArrayDocNode</a> (DocNode &amp;N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9df88e85c1ec39c1604e13c22e38f3ef">operator[]</a> (size_t Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Element access. This extends the array if necessary, with empty nodes. <a href="#a9df88e85c1ec39c1604e13c22e38f3ef">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea55f8d3f2ce25ead106e0ff9bc8f28f">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a339c1914ccdc706d7bb8e662abc65adc">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eab7452ad80d10e271598239cd1ee1c">back</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ArrayTy::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb82966fbf1e09d5ee6235eb2e7e394c">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ArrayTy::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a424d291ef3b070f70969b1f220db4580">end</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a969a25cab20bacfc1d698c1980a6b858">push_back</a> (DocNode N)</td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> that is an array.</p>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ArrayDocNode() {#a3d3ea4c9dfc2b681633c2684ca5c3b5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::msgpack::ArrayDocNode::ArrayDocNode ()</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

### ArrayDocNode() {#a321c0ea44e257246ee630eb346be23fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::msgpack::ArrayDocNode::ArrayDocNode (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp; N)</td>
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



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4410ec34d9e6c1a68100ca0ce033fb17">llvm::msgpack::Array</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a3ed9efe27c6b7fcf2faef82736f3617a">llvm::msgpack::DocNode::getKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a9df88e85c1ec39c1604e13c22e38f3ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; ArrayDocNode::operator[] (size_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Element access. This extends the array if necessary, with empty nodes.</p>


<p>Array element access. This extends the array if necessary.</p>


<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a603b51266c0e0421d37f7cc6cd6fb20b">llvm::msgpack::DocNode::Array</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#afb24ac524a469733ad7e1cd3f1de9dc5">llvm::msgpack::DocNode::getDocument</a> and <a href="#aea55f8d3f2ce25ead106e0ff9bc8f28f">size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### back() {#a4eab7452ad80d10e271598239cd1ee1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; llvm::msgpack::ArrayDocNode::back ()</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a603b51266c0e0421d37f7cc6cd6fb20b">llvm::msgpack::DocNode::Array</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a>.</p>

</div>
</div>

### begin() {#afb82966fbf1e09d5ee6235eb2e7e394c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayTy::iterator llvm::msgpack::ArrayDocNode::begin ()</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a603b51266c0e0421d37f7cc6cd6fb20b">llvm::msgpack::DocNode::Array</a>.</p>

</div>
</div>

### empty() {#a339c1914ccdc706d7bb8e662abc65adc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msgpack::ArrayDocNode::empty ()</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Reference <a href="#aea55f8d3f2ce25ead106e0ff9bc8f28f">size</a>.</p>

</div>
</div>

### end() {#a424d291ef3b070f70969b1f220db4580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayTy::iterator llvm::msgpack::ArrayDocNode::end ()</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a603b51266c0e0421d37f7cc6cd6fb20b">llvm::msgpack::DocNode::Array</a>.</p>

</div>
</div>

### push\_back() {#a969a25cab20bacfc1d698c1980a6b858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::msgpack::ArrayDocNode::push_back (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> N)</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a603b51266c0e0421d37f7cc6cd6fb20b">llvm::msgpack::DocNode::Array</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#afb24ac524a469733ad7e1cd3f1de9dc5">llvm::msgpack::DocNode::getDocument</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### size() {#aea55f8d3f2ce25ead106e0ff9bc8f28f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::msgpack::ArrayDocNode::size ()</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a603b51266c0e0421d37f7cc6cd6fb20b">llvm::msgpack::DocNode::Array</a>.</p>


<p>Referenced by <a href="#a339c1914ccdc706d7bb8e662abc65adc">empty</a> and <a href="#a9df88e85c1ec39c1604e13c22e38f3ef">operator[]</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
