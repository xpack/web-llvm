---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-pgoctxprofwriter-cpp-/serializablectxrepresentation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SerializableCtxRepresentation` Struct

<p>Representation of the context node suitable for yaml serialization / deserialization. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{PGOCtxProfWriter.cpp}::SerializableCtxRepresentation { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ctx-profile/#a6680521b81ea3a4c433750426966360b">ctx_profile::GUID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeedef1884268659bef88263119bfb8aa">Guid</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed3034ef7032a4fd5227bdfb64da374">Counters</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-pgoctxprofwriter-cpp-/serializablectxrepresentation">SerializableCtxRepresentation</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12f1c5432bbe9f9708650020811ca898">Callsites</a></td>
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

<p>Representation of the context node suitable for yaml serialization / deserialization.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofwriter-cpp">PGOCtxProfWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Callsites {#a12f1c5432bbe9f9708650020811ca898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;SerializableCtxRepresentation&gt; &gt; anonymous{PGOCtxProfWriter.cpp}::SerializableCtxRepresentation::Callsites</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofwriter-cpp">PGOCtxProfWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-pgoctxprofwriter-cpp-/#af1c66a7958c747574e383ef19e15da4f">anonymous{PGOCtxProfWriter.cpp}::createNode</a>.</p>

</div>
</div>

### Counters {#a8ed3034ef7032a4fd5227bdfb64da374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint64_t&gt; anonymous{PGOCtxProfWriter.cpp}::SerializableCtxRepresentation::Counters</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofwriter-cpp">PGOCtxProfWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-pgoctxprofwriter-cpp-/#af1c66a7958c747574e383ef19e15da4f">anonymous{PGOCtxProfWriter.cpp}::createNode</a>.</p>

</div>
</div>

### Guid {#aeedef1884268659bef88263119bfb8aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ctx_profile::GUID anonymous{PGOCtxProfWriter.cpp}::SerializableCtxRepresentation::Guid = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofwriter-cpp">PGOCtxProfWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-pgoctxprofwriter-cpp-/#af1c66a7958c747574e383ef19e15da4f">anonymous{PGOCtxProfWriter.cpp}::createNode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofwriter-cpp">PGOCtxProfWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
