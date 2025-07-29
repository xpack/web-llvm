---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/symbolrewriter/rewritedescriptor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RewriteDescriptor` Class

<p>The basic entity representing a rewrite operation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SymbolRewriter::RewriteDescriptor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">llvm/Transforms/Utils/SymbolRewriter.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-symbolrewriter-cpp-/explicitrewritedescriptor">ExplicitRewriteDescriptor&lt;DT, ValueType, Get&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-symbolrewriter-cpp-/patternrewritedescriptor">PatternRewriteDescriptor&lt;DT, ValueType, Get, Iterator&gt;</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Type { <a href="#aa2b16bcd3ad27db4f709afb257096018">...</a> }</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a530e03080c8232c38aefcf852d86e952">RewriteDescriptor</a> (const RewriteDescriptor &amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d8ca5c686ef6ea347581a3ea581c2d7">RewriteDescriptor</a> (Type T)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc3397e995d628babb4561fa4897ef8d">~RewriteDescriptor</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/symbolrewriter/rewritedescriptor">RewriteDescriptor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0eed3d5f685ea9023ca7105bf36cf67">operator=</a> (const RewriteDescriptor &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa2b16bcd3ad27db4f709afb257096018">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7207398e9e7643bb6430a94ce6dc8247">getType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3e72f5cfd0878a7b8f2d0ee1f9b2429">performOnModule</a> (Module &amp;M)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aa2b16bcd3ad27db4f709afb257096018">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ae85fb10a2f90c38db270884ec73267">Kind</a></td>
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

<p>The basic entity representing a rewrite operation.</p>


<p>It serves as the base class for any rewrite descriptor. It has a certain set of specializations which describe a particular rewrite.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/symbolrewriter/rewritemapparser">RewriteMapParser</a> can be used to parse a mapping file that provides the mapping for rewriting the symbols. The descriptors individually describe whether to rewrite a function, global variable, or global alias. Each of these can be selected either by explicitly providing a name for the ones to be rewritten or providing a (posix compatible) regular expression that will select the symbols to rewrite. This descriptor list is passed to the <a href="/web-llvm/docs/api/namespaces/llvm/symbolrewriter">SymbolRewriter</a> pass.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Type {#aa2b16bcd3ad27db4f709afb257096018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::SymbolRewriter::RewriteDescriptor::Type </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Invalid<a id="aa2b16bcd3ad27db4f709afb257096018a4bbb8f967da6d1a610596d7257179c2b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Function<a id="aa2b16bcd3ad27db4f709afb257096018a86408593c34af77fdd90df932f8b5261"></a></td>
<td class="doxyEnumItemDescription">invalid</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GlobalVariable<a id="aa2b16bcd3ad27db4f709afb257096018a43cd1cbc4ca88c2a2c8da1411bed1e41"></a></td>
<td class="doxyEnumItemDescription">function - descriptor rewrites a function</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NamedAlias<a id="aa2b16bcd3ad27db4f709afb257096018ab48a3f56cdfca5e9c72851f56baebbc7"></a></td>
<td class="doxyEnumItemDescription">global variable - descriptor rewrites a global variable</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RewriteDescriptor() {#a530e03080c8232c38aefcf852d86e952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SymbolRewriter::RewriteDescriptor::RewriteDescriptor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/symbolrewriter/rewritedescriptor">RewriteDescriptor</a> &amp;)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>.</p>


<p>Reference <a href="#a530e03080c8232c38aefcf852d86e952">RewriteDescriptor</a>.</p>


<p>Referenced by <a href="#ad0eed3d5f685ea9023ca7105bf36cf67">operator=</a> and <a href="#a530e03080c8232c38aefcf852d86e952">RewriteDescriptor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### RewriteDescriptor() {#a3d8ca5c686ef6ea347581a3ea581c2d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SymbolRewriter::RewriteDescriptor::RewriteDescriptor (<a href="#aa2b16bcd3ad27db4f709afb257096018">Type</a> T)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RewriteDescriptor() {#adc3397e995d628babb4561fa4897ef8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::SymbolRewriter::RewriteDescriptor::~RewriteDescriptor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ad0eed3d5f685ea9023ca7105bf36cf67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RewriteDescriptor &amp; llvm::SymbolRewriter::RewriteDescriptor::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/symbolrewriter/rewritedescriptor">RewriteDescriptor</a> &amp;)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>.</p>


<p>Reference <a href="#a530e03080c8232c38aefcf852d86e952">RewriteDescriptor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getType() {#a7207398e9e7643bb6430a94ce6dc8247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::SymbolRewriter::RewriteDescriptor::getType ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-symbolrewriter-cpp-/explicitrewritedescriptor/#ab7f522f31bab088189f522760317a4b1">anonymous{SymbolRewriter.cpp}::ExplicitRewriteDescriptor&lt; RewriteDescriptor::Type::Function, Function, &amp;Module::getFunction &gt;::classof</a> and <a href="/web-llvm/docs/api/classes/anonymous-symbolrewriter-cpp-/patternrewritedescriptor/#af7083ff725f489214631ad45ed39a6e6">anonymous{SymbolRewriter.cpp}::PatternRewriteDescriptor&lt; RewriteDescriptor::Type::Function, Function, &amp;Module::getFunction, &amp;Module::functions &gt;::classof</a>.</p>

</div>
</div>

### performOnModule() {#ad3e72f5cfd0878a7b8f2d0ee1f9b2429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::SymbolRewriter::RewriteDescriptor::performOnModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Kind {#a2ae85fb10a2f90c38db270884ec73267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Type llvm::SymbolRewriter::RewriteDescriptor::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
