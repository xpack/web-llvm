---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-llparser-cpp-/mdsignedormdfield
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MDSignedOrMDField` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{LLParser.cpp}::MDSignedOrMDField { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdeitherfieldimpl">MDEitherFieldImpl&lt;FieldTypeA, FieldTypeB&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Structure to represent an optional metadata field that can be of either type (A or B) and encapsulates the MD&lt;typeofA&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a> and MD&lt;typeofB&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a> structs, so not to reimplement the specifics for representing each <a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a>. <a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdeitherfieldimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfe2cdb7afcb375dea37e6c686d4bd1c">MDSignedOrMDField</a> (int64_t Default=0, bool AllowNull=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19536b4ef13bc258f34be26ea93437a5">MDSignedOrMDField</a> (int64_t Default, int64_t Min, int64_t Max, bool AllowNull=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affee5c06bf94f60e57c4dfed624dd7f8">isMDSignedField</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3cd1b3bc7632d67c1f4de5391ee70f4">isMDField</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267047beb827d22af01308e274909a36">getMDSignedValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4137a19a3c443bd68813ba6eda4614fc">getMDFieldValue</a> () const</td>
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


<p>Definition at line 4757 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MDSignedOrMDField() {#abfe2cdb7afcb375dea37e6c686d4bd1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LLParser.cpp}::MDSignedOrMDField::MDSignedOrMDField (int64_t Default=0, bool AllowNull=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 4758 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aaf2a32c0f2738e57cac623b73b2c88aba79935518a3889663d8688b6b01fff051">Default</a>.</p>

</div>
</div>

### MDSignedOrMDField() {#a19536b4ef13bc258f34be26ea93437a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LLParser.cpp}::MDSignedOrMDField::MDSignedOrMDField (int64_t Default, int64_t Min, int64_t Max, bool AllowNull=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 4761 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aaf2a32c0f2738e57cac623b73b2c88aba79935518a3889663d8688b6b01fff051">Default</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMDFieldValue() {#a4137a19a3c443bd68813ba6eda4614fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * anonymous{LLParser.cpp}::MDSignedOrMDField::getMDFieldValue ()</td>
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



<p>Definition at line 4771 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdeitherfieldimpl/#a0798423da500b8cc1d7ec7ba9447e98e">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; MDSignedField, MDField &gt;::B</a> and <a href="#ae3cd1b3bc7632d67c1f4de5391ee70f4">isMDField</a>.</p>

</div>
</div>

### getMDSignedValue() {#a267047beb827d22af01308e274909a36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{LLParser.cpp}::MDSignedOrMDField::getMDSignedValue ()</td>
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



<p>Definition at line 4767 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdeitherfieldimpl/#ac1ac753837c492a2274032fd96aad59d">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; MDSignedField, MDField &gt;::A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#affee5c06bf94f60e57c4dfed624dd7f8">isMDSignedField</a>.</p>

</div>
</div>

### isMDField() {#ae3cd1b3bc7632d67c1f4de5391ee70f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LLParser.cpp}::MDSignedOrMDField::isMDField ()</td>
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



<p>Definition at line 4766 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdeitherfieldimpl/#a980f0c7f474cefd0589f10f1e88dd1b3aef5f9da4e85c844579b96de6e1e285d0">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; MDSignedField, MDField &gt;::IsTypeB</a> and <a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdeitherfieldimpl/#ad2f8f294cbc5fcef179a47197e4ade45">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; MDSignedField, MDField &gt;::WhatIs</a>.</p>


<p>Referenced by <a href="#a4137a19a3c443bd68813ba6eda4614fc">getMDFieldValue</a>.</p>

</div>
</div>

### isMDSignedField() {#affee5c06bf94f60e57c4dfed624dd7f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LLParser.cpp}::MDSignedOrMDField::isMDSignedField ()</td>
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



<p>Definition at line 4765 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdeitherfieldimpl/#a980f0c7f474cefd0589f10f1e88dd1b3a0b9bbfffd9dece828b8eb76734e69292">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; MDSignedField, MDField &gt;::IsTypeA</a> and <a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdeitherfieldimpl/#ad2f8f294cbc5fcef179a47197e4ade45">anonymous{LLParser.cpp}::MDEitherFieldImpl&lt; MDSignedField, MDField &gt;::WhatIs</a>.</p>


<p>Referenced by <a href="#a267047beb827d22af01308e274909a36">getMDSignedValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
