---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/object/sectionedaddress
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SectionedAddress` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::object::SectionedAddress { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">llvm/Object/ObjectFile.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8807f1e455c2c5a36f3f2aaf617f823b">Address</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb3de5796b8423b3f4442e10b55747a5">SectionIndex</a> = <a href="#aab5f6719f1bf1cfd6c53e95ebce09470">UndefSection</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5f6719f1bf1cfd6c53e95ebce09470">UndefSection</a> = <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a></td>
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


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Address {#a8807f1e455c2c5a36f3f2aaf617f823b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::SectionedAddress::Address = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/sequence/#ad71c2b014b37f42efef1e43d3d104a73">llvm::DWARFDebugLine::Sequence::containsPC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a644ff714cd89b432924d685f0f21adcb">llvm::DWARFFormValue::dumpSectionedAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#aefea632d85600f98ca5b9c58f192d46b">llvm::object::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#a218915a5f9c3f5f93eb5b91d64b86bef">llvm::symbolize::SymbolizableObjectFile::symbolizeCode</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#a16e36ac568ecb580c16c44a3b74a4cd0">llvm::symbolize::SymbolizableObjectFile::symbolizeData</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#aaf76406be4473b3ff08ed20aeac28adb">llvm::symbolize::SymbolizableObjectFile::symbolizeFrame</a> and <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#af579f0af68a8e23690bd1e3ef3ed2b0e">llvm::symbolize::SymbolizableObjectFile::symbolizeInlinedCode</a>.</p>

</div>
</div>

### SectionIndex {#adb3de5796b8423b3f4442e10b55747a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::SectionedAddress::SectionIndex = <a href="#aab5f6719f1bf1cfd6c53e95ebce09470">UndefSection</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/sequence/#ad71c2b014b37f42efef1e43d3d104a73">llvm::DWARFDebugLine::Sequence::containsPC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a644ff714cd89b432924d685f0f21adcb">llvm::DWARFFormValue::dumpSectionedAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#aefea632d85600f98ca5b9c58f192d46b">llvm::object::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#a218915a5f9c3f5f93eb5b91d64b86bef">llvm::symbolize::SymbolizableObjectFile::symbolizeCode</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#aaf76406be4473b3ff08ed20aeac28adb">llvm::symbolize::SymbolizableObjectFile::symbolizeFrame</a> and <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#af579f0af68a8e23690bd1e3ef3ed2b0e">llvm::symbolize::SymbolizableObjectFile::symbolizeInlinedCode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### UndefSection {#aab5f6719f1bf1cfd6c53e95ebce09470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::object::SectionedAddress::UndefSection = <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a></td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfaddressrange/#ab1ac3fccbdc0aa51833b044bda302a16">llvm::DWARFAddressRange::DWARFAddressRange</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a814a7655e692e4f880b38eed143052fb">llvm::DWARFDataExtractor::getRelocatedValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfdebugloc-cpp-/dwarflocationinterpreter/#a096c9f49eb6554512951952f512b94ec">anonymous{DWARFDebugLoc.cpp}::DWARFLocationInterpreter::Interpret</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a07f83f8b45826aae82ba63fef9bcb70c">llvm::DWARFDebugLine::LineTable::lookupAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a910420e98a8f344483b3c461314898e3">llvm::DWARFDebugLine::LineTable::lookupAddressRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-perfjiteventlistener-cpp-/perfjiteventlistener/#a502ebf0f061782cbcfa72244fbd0ec97">anonymous{PerfJITEventListener.cpp}::PerfJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#aefea632d85600f98ca5b9c58f192d46b">llvm::object::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/row/#acd34f23460a8d624ac95fde2e08efa82">llvm::DWARFDebugLine::Row::reset</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/sequence/#aa108fa264ddea1330c82b79be3139072">llvm::DWARFDebugLine::Sequence::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#a218915a5f9c3f5f93eb5b91d64b86bef">llvm::symbolize::SymbolizableObjectFile::symbolizeCode</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#aaf76406be4473b3ff08ed20aeac28adb">llvm::symbolize::SymbolizableObjectFile::symbolizeFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#af579f0af68a8e23690bd1e3ef3ed2b0e">llvm::symbolize::SymbolizableObjectFile::symbolizeInlinedCode</a> and <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ac40e6efe1caf07771eb6713f41db076b">llvm::gsym::DwarfTransformer::verify</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
