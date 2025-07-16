---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-msgpackdocumentyaml-cpp-/scalardocnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ScalarDocNode` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{MsgPackDocumentYAML.cpp}::ScalarDocNode { ... }
</div>

## Base struct

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e240b31940358d89a17fe15ae402220">ScalarDocNode</a> (DocNode N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eeed73cd2b23e69e57d250ffece67d1">getYAMLTag</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the YAML tag for this <a href="/web-llvm/docs/api/structs/anonymous-msgpackdocumentyaml-cpp-/scalardocnode">ScalarDocNode</a>. <a href="#a3eeed73cd2b23e69e57d250ffece67d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocumentyaml-cpp">MsgPackDocumentYAML.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ScalarDocNode() {#a2e240b31940358d89a17fe15ae402220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MsgPackDocumentYAML.cpp}::ScalarDocNode::ScalarDocNode (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> N)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocumentyaml-cpp">MsgPackDocumentYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a0b25c4da6f9e05dd69ef15f988c426a3">llvm::msgpack::DocNode::DocNode</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a3eeed73cd2b23e69e57d250ffece67d1">getYAMLTag</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getYAMLTag() {#a3eeed73cd2b23e69e57d250ffece67d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef ScalarDocNode::getYAMLTag ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the YAML tag for this <a href="/web-llvm/docs/api/structs/anonymous-msgpackdocumentyaml-cpp-/scalardocnode">ScalarDocNode</a>.</p>


<p>This normally returns ""; it only returns something else if the result of toString would be ambiguous, e.g. a string that parses as a number or boolean.</p>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocumentyaml-cpp">MsgPackDocumentYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27226c864bac7454a8504f8edb15d95b">llvm::msgpack::Boolean</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a22ae0e2b89e5e3d477f988cc36d3272b">llvm::msgpack::Float</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#afb24ac524a469733ad7e1cd3f1de9dc5">llvm::msgpack::DocNode::getDocument</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a3ed9efe27c6b7fcf2faef82736f3617a">llvm::msgpack::DocNode::getKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a1686a6c336b71b36d77354cea19a8b52">llvm::msgpack::Int</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4da8b7eb2c3f2007cf8238334401ef51">llvm::msgpack::Nil</a>, <a href="#a2e240b31940358d89a17fe15ae402220">ScalarDocNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27118326006d3829667a400ad23d5d98">llvm::msgpack::String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocumentyaml-cpp">MsgPackDocumentYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
