---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-pgoctxprofwriter-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{PGOCtxProfWriter.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{PGOCtxProfWriter.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-pgoctxprofwriter-cpp-/serializablectxrepresentation">SerializableCtxRepresentation</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Representation of the context node suitable for yaml serialization / deserialization. <a href="/web-llvm/docs/api/structs/anonymous-pgoctxprofwriter-cpp-/serializablectxrepresentation/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ctx-profile/contextnode">ctx_profile::ContextNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5667796c39cbc9f0e66a7bc79958a54d">createNode</a> (std::vector&lt; std::unique_ptr&lt; char[]&gt; &gt; &amp;Nodes, const std::vector&lt; SerializableCtxRepresentation &gt; &amp;DCList)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ctx-profile/contextnode">ctx_profile::ContextNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c66a7958c747574e383ef19e15da4f">createNode</a> (std::vector&lt; std::unique_ptr&lt; char[]&gt; &gt; &amp;Nodes, const SerializableCtxRepresentation &amp;DC, ctx_profile::ContextNode *Next=nullptr)</td>
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


<div class="doxySectionDef">

## Functions

### createNode() {#a5667796c39cbc9f0e66a7bc79958a54d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ctx_profile::ContextNode * anonymous{PGOCtxProfWriter.cpp}::createNode (std::vector&lt; std::unique_ptr&lt; char[]&gt; &gt; &amp; Nodes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-pgoctxprofwriter-cpp-/serializablectxrepresentation">SerializableCtxRepresentation</a> &gt; &amp; DCList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofwriter-cpp">PGOCtxProfWriter.cpp</a>.</p>


<p>Reference <a href="#a5667796c39cbc9f0e66a7bc79958a54d">createNode</a>.</p>


<p>Referenced by <a href="#af1c66a7958c747574e383ef19e15da4f">createNode</a> and <a href="#a5667796c39cbc9f0e66a7bc79958a54d">createNode</a>.</p>

</div>
</div>

### createNode() {#af1c66a7958c747574e383ef19e15da4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ctx_profile::ContextNode * anonymous{PGOCtxProfWriter.cpp}::createNode (std::vector&lt; std::unique_ptr&lt; char[]&gt; &gt; &amp; Nodes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-pgoctxprofwriter-cpp-/serializablectxrepresentation">SerializableCtxRepresentation</a> &amp; DC, <a href="/web-llvm/docs/api/classes/llvm/ctx-profile/contextnode">ctx_profile::ContextNode</a> * Next=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofwriter-cpp">PGOCtxProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-pgoctxprofwriter-cpp-/serializablectxrepresentation/#a12f1c5432bbe9f9708650020811ca898">anonymous{PGOCtxProfWriter.cpp}::SerializableCtxRepresentation::Callsites</a>, <a href="/web-llvm/docs/api/structs/anonymous-pgoctxprofwriter-cpp-/serializablectxrepresentation/#a8ed3034ef7032a4fd5227bdfb64da374">anonymous{PGOCtxProfWriter.cpp}::SerializableCtxRepresentation::Counters</a>, <a href="#a5667796c39cbc9f0e66a7bc79958a54d">createNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/ctx-profile/contextnode/#a9eec8d154d4aff4bda0f8aef9d5b74b3">llvm::ctx_profile::ContextNode::getAllocSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-pgoctxprofwriter-cpp-/serializablectxrepresentation/#aeedef1884268659bef88263119bfb8aa">anonymous{PGOCtxProfWriter.cpp}::SerializableCtxRepresentation::Guid</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofwriter-cpp">PGOCtxProfWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
