---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/minidumpyaml/object
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Object` Struct

<p>The top level structure representing a minidump object, consisting of a minidump header, and zero or more streams. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MinidumpYAML::Object { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">llvm/ObjectYAML/MinidumpYAML.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04f5bf9fd9a0077b7cb8465289828be4">Object</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a965efa00b52e50ceeca01466f7a61022">Object</a> (const Object &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af17eac2fc4dc71357b72f144e261c99d">Object</a> (Object &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1353c0fba7a85ef5f55c58b8e20e21">Object</a> (const minidump::Header &amp;Header, std::vector&lt; std::unique_ptr&lt; Stream &gt; &gt; Streams)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/object">Object</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6aa8ad7deddd47f9c97a28a9db1abcb">operator=</a> (const Object &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/object">Object</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f4b5b1ddd9831d99733738cb81b65a7">operator=</a> (Object &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/minidump/header">minidump::Header</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae553781fa1ca4cc55a140a9dac563e4b">Header</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The minidump header. <a href="#ae553781fa1ca4cc55a140a9dac563e4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream">Stream</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61c43617525d40362380ec91aabe46f2">Streams</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of streams in this minidump object. <a href="#a61c43617525d40362380ec91aabe46f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/object">Object</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f7b44b37ffc751518ea6a163fbd9df2">create</a> (const object::MinidumpFile &amp;File)</td>
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

<p>The top level structure representing a minidump object, consisting of a minidump header, and zero or more streams.</p>


<p>To construct an <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/object">Object</a> from a minidump file, use the static create function. To serialize to/from yaml, use the appropriate streaming operator on a yaml stream.</p>


<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Object() {#a04f5bf9fd9a0077b7cb8465289828be4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MinidumpYAML::Object::Object ()</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>Referenced by <a href="#a9f7b44b37ffc751518ea6a163fbd9df2">create</a>, <a href="#a965efa00b52e50ceeca01466f7a61022">Object</a>, <a href="#af17eac2fc4dc71357b72f144e261c99d">Object</a>, <a href="#ae6aa8ad7deddd47f9c97a28a9db1abcb">operator=</a> and <a href="#a1f4b5b1ddd9831d99733738cb81b65a7">operator=</a>.</p>

</div>
</div>

### Object() {#a965efa00b52e50ceeca01466f7a61022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MinidumpYAML::Object::Object (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/object">Object</a> &amp;)</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>Reference <a href="#a04f5bf9fd9a0077b7cb8465289828be4">Object</a>.</p>

</div>
</div>

### Object() {#af17eac2fc4dc71357b72f144e261c99d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MinidumpYAML::Object::Object (<a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/object">Object</a> &amp;&amp;)</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>Reference <a href="#a04f5bf9fd9a0077b7cb8465289828be4">Object</a>.</p>

</div>
</div>

### Object() {#aca1353c0fba7a85ef5f55c58b8e20e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MinidumpYAML::Object::Object (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidump/header">minidump::Header</a> &amp; Header, std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream">Stream</a> &gt; &gt; Streams)</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>References <a href="#ae553781fa1ca4cc55a140a9dac563e4b">Header</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a61c43617525d40362380ec91aabe46f2">Streams</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ae6aa8ad7deddd47f9c97a28a9db1abcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Object &amp; llvm::MinidumpYAML::Object::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/object">Object</a> &amp;)</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>Reference <a href="#a04f5bf9fd9a0077b7cb8465289828be4">Object</a>.</p>

</div>
</div>

### operator=() {#a1f4b5b1ddd9831d99733738cb81b65a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Object &amp; llvm::MinidumpYAML::Object::operator= (<a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/object">Object</a> &amp;&amp;)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>Reference <a href="#a04f5bf9fd9a0077b7cb8465289828be4">Object</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Header {#ae553781fa1ca4cc55a140a9dac563e4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">minidump::Header llvm::MinidumpYAML::Object::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The minidump header.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>Referenced by <a href="#aca1353c0fba7a85ef5f55c58b8e20e21">Object</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aec505024f93ccc62d2b0214ac9bcb9f2">llvm::yaml::yaml2minidump</a>.</p>

</div>
</div>

### Streams {#a61c43617525d40362380ec91aabe46f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;Stream&gt; &gt; llvm::MinidumpYAML::Object::Streams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of streams in this minidump object.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>Referenced by <a href="#a9f7b44b37ffc751518ea6a163fbd9df2">create</a>, <a href="#aca1353c0fba7a85ef5f55c58b8e20e21">Object</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aec505024f93ccc62d2b0214ac9bcb9f2">llvm::yaml::yaml2minidump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a9f7b44b37ffc751518ea6a163fbd9df2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Object &gt; Object::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile">object::MinidumpFile</a> &amp; File)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>, definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp">MinidumpYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a0a7936841f610beb0639f88f3e7cc7a3">llvm::MinidumpYAML::Stream::create</a>, <a href="#a04f5bf9fd9a0077b7cb8465289828be4">Object</a> and <a href="#a61c43617525d40362380ec91aabe46f2">Streams</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp">MinidumpYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
