---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/arglistrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ArgListRecord` Class



## Declaration

<div class="doxyDeclaration">
class llvm::codeview::ArgListRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">llvm/DebugInfo/CodeView/TypeRecord.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord">TypeRecord</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65d2b5aa2da6cd5780fe7136d28b685d">ArgListRecord</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade60a139d3376d354fb6e3df65812fcb">ArgListRecord</a> (TypeRecordKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac69f8af068648b80b1277424dcfe8137">ArgListRecord</a> (TypeRecordKind Kind, ArrayRef&lt; TypeIndex &gt; Indices)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a643dede0dc9b16a54d3c26b4f1def342">getIndices</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57606307e95d9aecdbec9e184d798d24">ArgIndices</a></td>
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


<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ArgListRecord() {#a65d2b5aa2da6cd5780fe7136d28b685d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::ArgListRecord::ArgListRecord ()</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>

</div>
</div>

### ArgListRecord() {#ade60a139d3376d354fb6e3df65812fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::ArgListRecord::ArgListRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#abf3db0193e50769bab633545f88c383a">TypeRecordKind</a> Kind)</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord/#a714d9d1981216f2af467fc81f53b8790">llvm::codeview::TypeRecord::Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord/#a4259276eb9e9ab247c88103b93a20b5d">llvm::codeview::TypeRecord::TypeRecord</a>.</p>

</div>
</div>

### ArgListRecord() {#ac69f8af068648b80b1277424dcfe8137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::ArgListRecord::ArgListRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#abf3db0193e50769bab633545f88c383a">TypeRecordKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt; Indices)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>References <a href="#a57606307e95d9aecdbec9e184d798d24">ArgIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord/#a714d9d1981216f2af467fc81f53b8790">llvm::codeview::TypeRecord::Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord/#a4259276eb9e9ab247c88103b93a20b5d">llvm::codeview::TypeRecord::TypeRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getIndices() {#a643dede0dc9b16a54d3c26b4f1def342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; TypeIndex &gt; llvm::codeview::ArgListRecord::getIndices ()</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Reference <a href="#a57606307e95d9aecdbec9e184d798d24">ArgIndices</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ArgIndices {#a57606307e95d9aecdbec9e184d798d24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;TypeIndex&gt; llvm::codeview::ArgListRecord::ArgIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="#ac69f8af068648b80b1277424dcfe8137">ArgListRecord</a> and <a href="#a643dede0dc9b16a54d3c26b4f1def342">getIndices</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
