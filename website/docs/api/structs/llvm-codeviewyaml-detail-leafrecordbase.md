---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/codeviewyaml/detail/leafrecordbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LeafRecordBase` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::CodeViewYAML::detail::LeafRecordBase { ... }
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/leafrecordimpl-832f6a201a493b7c1e0caf0ea997f0f9">LeafRecordImpl&lt;FieldListRecord&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/leafrecordimpl">LeafRecordImpl&lt;T&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/leafrecordimpl-832f6a201a493b7c1e0caf0ea997f0f9">LeafRecordImpl&lt;FieldListRecord&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e6e975628d32e39a65efbbff09757b6">LeafRecordBase</a> (TypeLeafKind K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c6d5c5e8f3ea60a59d65a59d8e303f8">~LeafRecordBase</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38fdffabc9d2733aed73fc04d31f156c">map</a> (yaml::IO &amp;io)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16d6f41231ae34d8563defb396fbab85">toCodeViewRecord</a> (AppendingTypeTableBuilder &amp;TS) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaac226827ce51ec5826901c8d7c64b9">fromCodeViewRecord</a> (CVType Type)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a945d5dcbe78d400d17656726e2f6089b">TypeLeafKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca14e075ee40af62b8cb00ebc8fc32b1">Kind</a></td>
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


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp">CodeViewYAMLTypes.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LeafRecordBase() {#a5e6e975628d32e39a65efbbff09757b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CodeViewYAML::detail::LeafRecordBase::LeafRecordBase (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a945d5dcbe78d400d17656726e2f6089b">TypeLeafKind</a> K)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp">CodeViewYAMLTypes.cpp</a>.</p>


<p>Reference <a href="#aca14e075ee40af62b8cb00ebc8fc32b1">Kind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/leafrecordimpl/#a832095eb204497c809e746155dff9942">llvm::CodeViewYAML::detail::LeafRecordImpl&lt; T &gt;::LeafRecordImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/leafrecordimpl-832f6a201a493b7c1e0caf0ea997f0f9/#aaab25a8176325ff5fe5a9bedfdd3e66d">llvm::CodeViewYAML::detail::LeafRecordImpl&lt; FieldListRecord &gt;::LeafRecordImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LeafRecordBase() {#a6c6d5c5e8f3ea60a59d65a59d8e303f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::CodeViewYAML::detail::LeafRecordBase::~LeafRecordBase ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp">CodeViewYAMLTypes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### fromCodeViewRecord() {#abaac226827ce51ec5826901c8d7c64b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::CodeViewYAML::detail::LeafRecordBase::fromCodeViewRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp">CodeViewYAMLTypes.cpp</a>.</p>

</div>
</div>

### map() {#a38fdffabc9d2733aed73fc04d31f156c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::CodeViewYAML::detail::LeafRecordBase::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">yaml::IO</a> &amp; io)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp">CodeViewYAMLTypes.cpp</a>.</p>

</div>
</div>

### toCodeViewRecord() {#a16d6f41231ae34d8563defb396fbab85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual CVType llvm::CodeViewYAML::detail::LeafRecordBase::toCodeViewRecord (<a href="/web-llvm/docs/api/classes/llvm/codeview/appendingtypetablebuilder">AppendingTypeTableBuilder</a> &amp; TS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp">CodeViewYAMLTypes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Kind {#aca14e075ee40af62b8cb00ebc8fc32b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeLeafKind llvm::CodeViewYAML::detail::LeafRecordBase::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp">CodeViewYAMLTypes.cpp</a>.</p>


<p>Referenced by <a href="#a5e6e975628d32e39a65efbbff09757b6">LeafRecordBase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp">CodeViewYAMLTypes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
