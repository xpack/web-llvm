---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-llparser-cpp-/mdeitherfieldimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MDEitherFieldImpl` Struct Template Reference

<p>Structure to represent an optional metadata field that can be of either type (A or B) and encapsulates the MD&lt;typeofA&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a> and MD&lt;typeofB&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a> structs, so not to reimplement the specifics for representing each <a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class FieldTypeA, class FieldTypeB&gt;
struct anonymous{LLParser.cpp}::MDEitherFieldImpl&lt;FieldTypeA, FieldTypeB&gt; { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FieldTypeA, class FieldTypeB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdeitherfieldimpl">MDEitherFieldImpl</a>&lt; FieldTypeA, FieldTypeB &gt; <a href="#af401ed8cc6f7b1c5df3bd3a428a08fd1">ImplTy</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FieldTypeA, class FieldTypeB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"> { <a href="#a980f0c7f474cefd0589f10f1e88dd1b3">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FieldTypeA, class FieldTypeB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a073fa762ab91cd6b0631f26b584227a1">MDEitherFieldImpl</a> (FieldTypeA DefaultA, FieldTypeB DefaultB)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FieldTypeA, class FieldTypeB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b997eab28d42a5be16b25d8df6f9149">assign</a> (FieldTypeA A)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FieldTypeA, class FieldTypeB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd0313890256aae29a9a5c0e2ffddc75">assign</a> (FieldTypeB B)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FieldTypeA, class FieldTypeB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">FieldTypeA</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac1ac753837c492a2274032fd96aad59d">A</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FieldTypeA, class FieldTypeB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">FieldTypeB</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0798423da500b8cc1d7ec7ba9447e98e">B</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FieldTypeA, class FieldTypeB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a39a6b8dbc509b89bc4198fd70331e291">Seen</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FieldTypeA, class FieldTypeB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">enum anonymous_namespace{LLParser.cpp}<a href="#a073fa762ab91cd6b0631f26b584227a1">::MDEitherFieldImpl</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad2f8f294cbc5fcef179a47197e4ade45">WhatIs</a></td>
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

<p>Structure to represent an optional metadata field that can be of either type (A or B) and encapsulates the MD&lt;typeofA&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a> and MD&lt;typeofB&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a> structs, so not to reimplement the specifics for representing each <a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a>.</p>

<p>Definition at line 4628 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ImplTy {#af401ed8cc6f7b1c5df3bd3a428a08fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FieldTypeA, class FieldTypeB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef MDEitherFieldImpl&lt;FieldTypeA, FieldTypeB&gt; anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::ImplTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4629 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a980f0c7f474cefd0589f10f1e88dd1b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsInvalid<a id="a980f0c7f474cefd0589f10f1e88dd1b3ac58ad5a42b0a88d638cbabd2eb4f03dc"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsTypeA<a id="a980f0c7f474cefd0589f10f1e88dd1b3a0b9bbfffd9dece828b8eb76734e69292"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsTypeB<a id="a980f0c7f474cefd0589f10f1e88dd1b3aef5f9da4e85c844579b96de6e1e285d0"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 4634 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MDEitherFieldImpl() {#a073fa762ab91cd6b0631f26b584227a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FieldTypeA, class FieldTypeB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::MDEitherFieldImpl (FieldTypeA DefaultA, FieldTypeB DefaultB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4652 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="#ac1ac753837c492a2274032fd96aad59d">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::A</a>, <a href="#a0798423da500b8cc1d7ec7ba9447e98e">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::B</a>, <a href="#a980f0c7f474cefd0589f10f1e88dd1b3ac58ad5a42b0a88d638cbabd2eb4f03dc">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::IsInvalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a39a6b8dbc509b89bc4198fd70331e291">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::Seen</a> and <a href="#ad2f8f294cbc5fcef179a47197e4ade45">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::WhatIs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assign() {#a8b997eab28d42a5be16b25d8df6f9149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FieldTypeA, class FieldTypeB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::assign (FieldTypeA A)</td>
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



<p>Definition at line 4640 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="#ac1ac753837c492a2274032fd96aad59d">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::A</a>, <a href="#a980f0c7f474cefd0589f10f1e88dd1b3a0b9bbfffd9dece828b8eb76734e69292">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::IsTypeA</a>, <a href="#a39a6b8dbc509b89bc4198fd70331e291">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::Seen</a> and <a href="#ad2f8f294cbc5fcef179a47197e4ade45">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::WhatIs</a>.</p>

</div>
</div>

### assign() {#afd0313890256aae29a9a5c0e2ffddc75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FieldTypeA, class FieldTypeB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::assign (FieldTypeB B)</td>
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



<p>Definition at line 4646 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="#a0798423da500b8cc1d7ec7ba9447e98e">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::B</a>, <a href="#a980f0c7f474cefd0589f10f1e88dd1b3aef5f9da4e85c844579b96de6e1e285d0">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::IsTypeB</a>, <a href="#a39a6b8dbc509b89bc4198fd70331e291">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::Seen</a> and <a href="#ad2f8f294cbc5fcef179a47197e4ade45">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::WhatIs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### A {#ac1ac753837c492a2274032fd96aad59d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FieldTypeA, class FieldTypeB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FieldTypeA anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::A</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4630 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Referenced by <a href="#a8b997eab28d42a5be16b25d8df6f9149">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::assign</a> and <a href="#a073fa762ab91cd6b0631f26b584227a1">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::MDEitherFieldImpl</a>.</p>

</div>
</div>

### B {#a0798423da500b8cc1d7ec7ba9447e98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FieldTypeA, class FieldTypeB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FieldTypeB anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::B</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4631 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Referenced by <a href="#afd0313890256aae29a9a5c0e2ffddc75">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::assign</a> and <a href="#a073fa762ab91cd6b0631f26b584227a1">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::MDEitherFieldImpl</a>.</p>

</div>
</div>

### Seen {#a39a6b8dbc509b89bc4198fd70331e291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FieldTypeA, class FieldTypeB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::Seen</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4632 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Referenced by <a href="#a8b997eab28d42a5be16b25d8df6f9149">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::assign</a>, <a href="#afd0313890256aae29a9a5c0e2ffddc75">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::assign</a> and <a href="#a073fa762ab91cd6b0631f26b584227a1">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::MDEitherFieldImpl</a>.</p>

</div>
</div>

### WhatIs {#ad2f8f294cbc5fcef179a47197e4ade45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FieldTypeA, class FieldTypeB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{LLParser.cpp}::MDEitherFieldImpl anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::WhatIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4638 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Referenced by <a href="#a8b997eab28d42a5be16b25d8df6f9149">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::assign</a>, <a href="#afd0313890256aae29a9a5c0e2ffddc75">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::assign</a> and <a href="#a073fa762ab91cd6b0631f26b584227a1">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; FieldTypeA, FieldTypeB &gt;::MDEitherFieldImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
