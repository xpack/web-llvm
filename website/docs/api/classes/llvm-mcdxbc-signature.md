---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcdxbc/signature
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Signature` Class



## Declaration

<div class="doxyDeclaration">
class llvm::mcdxbc::Signature { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">llvm/MC/DXContainerPSVInfo.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bd3f36dd873172b82f4cdbaba502566">addParam</a> (uint32_t Stream, StringRef Name, uint32_t Index, dxbc::D3DSystemValue SystemValue, dxbc::SigComponentType CompType, uint32_t Register, uint8_t Mask, uint8_t ExclusiveMask, dxbc::SigMinPrecision MinPrecision)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608616d2779ddc0d1ca2669b17119ba2">write</a> (raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; Parameter &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eee3f731a0087526febb582c0b28e9f">Params</a></td>
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


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### addParam() {#a4bd3f36dd873172b82f4cdbaba502566}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mcdxbc::Signature::addParam (uint32_t Stream, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint32_t Index, <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/#a10c892417ddf709bb72ac6c19c3146d1">dxbc::D3DSystemValue</a> SystemValue, <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/#a02c3a495a56bc9a255d05d912afe0173">dxbc::SigComponentType</a> CompType, uint32_t Register, uint8_t Mask, uint8_t ExclusiveMask, <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/#a5ad6c5b17ba8ae365308ec3b0dfa6cc6">dxbc::SigMinPrecision</a> MinPrecision)</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>

</div>
</div>

### write() {#a608616d2779ddc0d1ca2669b17119ba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Signature::write (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp">DXContainerPSVInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#ae6ba484ec18769c20a3c576c02f0b2a7">llvm::StringTableBuilder::add</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/programsignatureelement/#aead9ad20b61ae17efce676c34c9e3e95">llvm::dxbc::ProgramSignatureElement::CompType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a58c8b5f09afd8827aed05c9a1804e73aafa19fdcc19d034fbc975465426a59188">llvm::StringTableBuilder::DWARF</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/programsignatureelement/#a94fc660d4c3168074117b1100b542ca7">llvm::dxbc::ProgramSignatureElement::ExclusiveMask</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a12ff7a5198a84bc90537e2f1007af9fd">llvm::StringTableBuilder::finalizeInOrder</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/programsignatureelement/#a6bd64a58ebaeafe7463633fb49815f04">llvm::dxbc::ProgramSignatureElement::Index</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ab9f705441a3a825d4b8a93ca4476d4e7">llvm::sys::IsBigEndianHost</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/programsignatureelement/#a97a2d3661f44250122781ea4c4aedd6d">llvm::dxbc::ProgramSignatureElement::Mask</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/programsignatureelement/#a29d95cbbed956c636c64d3ec73971af8">llvm::dxbc::ProgramSignatureElement::MinPrecision</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/programsignatureelement/#a52f512d94d7be0e77ad9039aa92b0dca">llvm::dxbc::ProgramSignatureElement::NameOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/programsignatureelement/#afa1755a94dfc4e5217dd03b0c4d404d1">llvm::dxbc::ProgramSignatureElement::Register</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/programsignatureelement/#aa0f95f5339f9abc93301c2f5edb07f11">llvm::dxbc::ProgramSignatureElement::Stream</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/programsignatureheader/#a2a6df212b6a70e0447059e38346fc739">llvm::dxbc::ProgramSignatureHeader::swapBytes</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/programsignatureelement/#aabf85abfa40e7b61c54ce888679dec4f">llvm::dxbc::ProgramSignatureElement::SystemValue</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a> and <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#ae2469d919349b52e2d98dd09fed5d623">llvm::StringTableBuilder::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Params {#a5eee3f731a0087526febb582c0b28e9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Parameter&gt; llvm::mcdxbc::Signature::Params</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp">DXContainerPSVInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
