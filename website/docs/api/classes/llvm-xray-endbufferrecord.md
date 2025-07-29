---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/xray/endbufferrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `EndBufferRecord` Class



## Declaration

<div class="doxyDeclaration">
class llvm::xray::EndBufferRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/fdrrecords-h">llvm/XRay/FDRRecords.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xray/metadatarecord">MetadataRecord</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0063a181b4ed70b7cdb1cdca783a4ce6">EndBufferRecord</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2784a133a111320ae14912c28b931beb">apply</a> (RecordVisitor &amp;V) override</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd40336279f8d16eb6397c3e6864add5">classof</a> (const Record *R)</td>
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


<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/fdrrecords-h">FDRRecords.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### EndBufferRecord() {#a0063a181b4ed70b7cdb1cdca783a4ce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::xray::EndBufferRecord::EndBufferRecord ()</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/fdrrecords-h">FDRRecords.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/xray/metadatarecord/#a6bed42fe3a7fd8885848437d16a02116ae5da385dbefcea25180d295762b0b38f">llvm::xray::MetadataRecord::EndOfBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/metadatarecord/#a1abc942c50eb0bfc315ff9fc2d2b08f5">llvm::xray::MetadataRecord::MetadataRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/xray/record/#a51c09ad0492682e78c37551b18187976a14c8173effd0154aa568239d71e92e6f">llvm::xray::Record::RK_Metadata_EndOfBuffer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### apply() {#a2784a133a111320ae14912c28b931beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::xray::EndBufferRecord::apply (<a href="/web-llvm/docs/api/classes/llvm/xray/recordvisitor">RecordVisitor</a> &amp; V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/fdrrecords-h">FDRRecords.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/fdrrecords-cpp">FDRRecords.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#acd40336279f8d16eb6397c3e6864add5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::xray::EndBufferRecord::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/xray/record">Record</a> * R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/fdrrecords-h">FDRRecords.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/xray/record/#a51c09ad0492682e78c37551b18187976a14c8173effd0154aa568239d71e92e6f">llvm::xray::Record::RK_Metadata_EndOfBuffer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/fdrrecords-h">FDRRecords.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/xray/fdrrecords-cpp">FDRRecords.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
