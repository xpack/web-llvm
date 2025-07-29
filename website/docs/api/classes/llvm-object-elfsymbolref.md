---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/elfsymbolref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ELFSymbolRef` Class



## Declaration

<div class="doxyDeclaration">
class llvm::object::ELFSymbolRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">llvm/Object/ELFObjectFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a value type class that represents a single symbol in the list of symbols in the object file. <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d1e9186871dbe19b521894ce4c5a2ef">ELFSymbolRef</a> (const SymbolRef &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase">ELFObjectFileBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2285d03995b7c7455fb2ff328c05aaad">getObject</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8549874db03a19df5cb846d78eddf383">getSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc4fe71d834ddfcc6981f15b43ba100">getBinding</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a226b51dd73c554ff4c2960696682c0ca">getOther</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d021019938a83613dc66fad533adcfc">getELFType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af057b66a5eaae80436ba423e0c4334e2">getELFTypeName</a> () const</td>
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


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ELFSymbolRef() {#a4d1e9186871dbe19b521894ce4c5a2ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::ELFSymbolRef::ELFSymbolRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> &amp; B)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#aa08bcfd0fd633889120aa52eb115f3fb">llvm::object::SymbolRef::getObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a4cfb6c528a7cc26455f507d98b9e6f53">llvm::object::SymbolRef::SymbolRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBinding() {#a7cc4fe71d834ddfcc6981f15b43ba100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::ELFSymbolRef::getBinding ()</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2285d03995b7c7455fb2ff328c05aaad">getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#ab999296a42f5a01597b3b1d84c4b6cbd">llvm::object::ELFObjectFileBase::getSymbolBinding</a>.</p>

</div>
</div>

### getELFType() {#a2d021019938a83613dc66fad533adcfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::ELFSymbolRef::getELFType ()</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2285d03995b7c7455fb2ff328c05aaad">getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#a6c0d6e795aa8871b817dc44b62a57d89">llvm::object::ELFObjectFileBase::getSymbolELFType</a>.</p>


<p>Referenced by <a href="#af057b66a5eaae80436ba423e0c4334e2">getELFTypeName</a>.</p>

</div>
</div>

### getELFTypeName() {#af057b66a5eaae80436ba423e0c4334e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::ELFSymbolRef::getELFTypeName ()</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#abea98bdf0fd53636a0f4a8bc7b6f22b6">llvm::object::ElfSymbolTypes</a> and <a href="#a2d021019938a83613dc66fad533adcfc">getELFType</a>.</p>

</div>
</div>

### getObject() {#a2285d03995b7c7455fb2ff328c05aaad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ELFObjectFileBase * llvm::object::ELFSymbolRef::getObject ()</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a294f053bad4966edce6b5edb3697cb08">llvm::object::BasicSymbolRef::getObject</a>.</p>


<p>Referenced by <a href="#a7cc4fe71d834ddfcc6981f15b43ba100">getBinding</a>, <a href="#a2d021019938a83613dc66fad533adcfc">getELFType</a>, <a href="#a226b51dd73c554ff4c2960696682c0ca">getOther</a> and <a href="#a8549874db03a19df5cb846d78eddf383">getSize</a>.</p>

</div>
</div>

### getOther() {#a226b51dd73c554ff4c2960696682c0ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::ELFSymbolRef::getOther ()</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2285d03995b7c7455fb2ff328c05aaad">getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#a7fc8ab2f18bc6413914863a7c05db3e8">llvm::object::ELFObjectFileBase::getSymbolOther</a>.</p>

</div>
</div>

### getSize() {#a8549874db03a19df5cb846d78eddf383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFSymbolRef::getSize ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a2285d03995b7c7455fb2ff328c05aaad">getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#a088066f8437df088b67f1eae30f682f9">llvm::object::ELFObjectFileBase::getSymbolSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/objectfiletransformer/#a9940b2d9a5f2a7de1dcfcdb970bf5e51">llvm::gsym::ObjectFileTransformer::convert</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
