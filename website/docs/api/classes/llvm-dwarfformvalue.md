---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfformvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARFFormValue` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::DWARFFormValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">llvm/DebugInfo/DWARF/DWARFFormValue.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FormClass { <a href="#a031683a2f97f9d8db3b493ada43e2228">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea38641ad6d13b90e729d7ebbc3368a8">DWARFFormValue</a> (dwarf::Form F=dwarf::Form(0))</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e9aaaa69e133c7693aa5a2ecff29237">DWARFFormValue</a> (dwarf::Form F, const ValueType &amp;V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Context for extract time. <a href="#a9e9aaaa69e133c7693aa5a2ecff29237">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae7527783aa2e969040c3cfcb4070c6">getForm</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff41df6db83444b2f49193bc1f362fae">getRawUValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f4acdd5d8a9b78623878262b10f8e4f">isFormClass</a> (FormClass FC) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0a85f9b35aad5e7d4790835e4ce7515">getUnit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abccb4aa356ed1bf8bae692df185a885a">dump</a> (raw_ostream &amp;OS, DIDumpOptions DumpOpts=DIDumpOptions()) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a644ff714cd89b432924d685f0f21adcb">dumpSectionedAddress</a> (raw_ostream &amp;OS, DIDumpOptions DumpOpts, object::SectionedAddress SA) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0373b5360a46d14a991fea39390d7240">dumpAddress</a> (raw_ostream &amp;OS, uint64_t Address) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa146755e2500aea560c4417a30c0b96b">extractValue</a> (const DWARFDataExtractor &amp;Data, uint64_t *OffsetPtr, dwarf::FormParams FormParams, const DWARFContext *Context=nullptr, const DWARFUnit *Unit=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts a value in <span class="doxyComputerOutput">Data</span> at offset <span class="doxyComputerOutput">*OffsetPtr</span>. <a href="#aa146755e2500aea560c4417a30c0b96b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab279d9eb9f9ec4bd6a21f1d620952234">extractValue</a> (const DWARFDataExtractor &amp;Data, uint64_t *OffsetPtr, dwarf::FormParams FormParams, const DWARFUnit *U)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa379ebd24e7782b901ad1110ddd11833">getAsRelativeReference</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAsFoo functions below return the extracted value as Foo if only <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> has form class is suitable for representing Foo. <a href="#aa379ebd24e7782b901ad1110ddd11833">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab967429b71c38060f3be76c48b359753">getAsDebugInfoReference</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8268c33eef15761e468285e4c18261b">getAsSignatureReference</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2443b5a8ac3dd97f95bb66d3382b8e91">getAsSupplementaryReference</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf6d7ec7b1699c2bf60e54e032aae623">getAsUnsignedConstant</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95368a5748aa1df8f1d4a2923585a3d3">getAsSignedConstant</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6bcf159d6ccb3adb4f7409e3adbbb37">getAsCString</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a958f097ef2e9e5f193089b36ee820e85">getAsAddress</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fc1d711d6f952a305382ec6a518bfc5">getAsSectionedAddress</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b4361a52bbe519104734f746a248f9">getAsSectionOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3429295ea0185a78b39c2e853b13b851">getAsBlock</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a210c090337f1fb2ac9920d9e193a24cc">getAsCStringOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a889eeb948d34e992d9d46f1174f9c457">getAsReferenceUVal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2af35f9fb586ccbd0416130e8b3f17aa">getAsFile</a> (DILineInfoSpecifier::FileLineInfoKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Correctly extract any file paths from a form value. <a href="#a2af35f9fb586ccbd0416130e8b3f17aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad16686174287aeb36289484f271d5225">skipValue</a> (DataExtractor DebugInfoData, uint64_t *OffsetPtr, const dwarf::FormParams Params) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip a form's value in <span class="doxyComputerOutput">DebugInfoData</span> at the offset specified by <span class="doxyComputerOutput">OffsetPtr</span>. <a href="#ad16686174287aeb36289484f271d5225">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d900c7b58bfaeac8ec1d026c1f16ca7">dumpString</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95082bf19bbdfc92d035beb44c4a899b">Form</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1e27d849d5af4e400c07970add6136f">Format</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Form for this value. <a href="#ad1e27d849d5af4e400c07970add6136f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarfformvalue/valuetype">ValueType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32f94fc848a42881d6d5f10e10a5df43">Value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remember the DWARF format at extract time. <a href="#a32f94fc848a42881d6d5f10e10a5df43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b6c60be483941e921b0b89c688fc7cb">U</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Contains all data for the form. <a href="#a5b6c60be483941e921b0b89c688fc7cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad51b270eb0cf95d9ec7e698a4295df63">C</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remember the <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> at extract time. <a href="#ad51b270eb0cf95d9ec7e698a4295df63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac346eaa0ba929794c7261e78a757f7ad">createFromSValue</a> (dwarf::Form F, int64_t V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22ddba895c7cabfcfcd529211782ea71">createFromUValue</a> (dwarf::Form F, uint64_t V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3905b85f3ac726af3668b04cc9fa68">createFromPValue</a> (dwarf::Form F, const char *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9e25a95408ffef54103c6136b60b1e9">createFromBlockValue</a> (dwarf::Form F, ArrayRef&lt; uint8_t &gt; D)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae10fbb14f19a44ed3a9464eb6cc36dc0">createFromUnit</a> (dwarf::Form F, const DWARFUnit *Unit, uint64_t *OffsetPtr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a806ef7f21e05aad3d69517e241b77a7b">getAsSectionedAddress</a> (const ValueType &amp;Val, const dwarf::Form Form, const DWARFUnit *U)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6904315158f4d30aedc905545ff59d59">dumpAddress</a> (raw_ostream &amp;OS, uint8_t AddressSize, uint64_t Address)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bdd3a234a4ad4d695aea54ddb2b92bf">dumpAddressSection</a> (const DWARFObject &amp;Obj, raw_ostream &amp;OS, DIDumpOptions DumpOpts, uint64_t SectionIndex)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b10b1371b2d1f535ff65cf1aeed3158">skipValue</a> (dwarf::Form Form, DataExtractor DebugInfoData, uint64_t *OffsetPtr, const dwarf::FormParams FormParams)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip a form's value in <span class="doxyComputerOutput">DebugInfoData</span> at the offset specified by <span class="doxyComputerOutput">OffsetPtr</span>. <a href="#a4b10b1371b2d1f535ff65cf1aeed3158">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### FormClass {#a031683a2f97f9d8db3b493ada43e2228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::DWARFFormValue::FormClass </td>
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
<td class="doxyEnumItemName">FC_Unknown<a id="a031683a2f97f9d8db3b493ada43e2228aafd5e9425f11dddeaac05301f9808d71"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FC_Address<a id="a031683a2f97f9d8db3b493ada43e2228ab9a403b58117de942610f95d22109d9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FC_Block<a id="a031683a2f97f9d8db3b493ada43e2228ab7f7ffb183c98435d2b766c0bd9412eb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FC_Constant<a id="a031683a2f97f9d8db3b493ada43e2228a9190be54233acc999af9cb02ed854c0f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FC_String<a id="a031683a2f97f9d8db3b493ada43e2228a39865546c65a182a3f9fa1bfe487203a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FC_Flag<a id="a031683a2f97f9d8db3b493ada43e2228aa32d75d2d5fc3faca059726ac4615fd2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FC_Reference<a id="a031683a2f97f9d8db3b493ada43e2228aecc352ab32050f10e6c1d07d39eca711"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FC_Indirect<a id="a031683a2f97f9d8db3b493ada43e2228a5c69008ea56bef0e6962d52cb40b905b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FC_SectionOffset<a id="a031683a2f97f9d8db3b493ada43e2228ad4d4f9b4b3969ebc99a811b168072ff0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FC_Exprloc<a id="a031683a2f97f9d8db3b493ada43e2228a5a1c5d88ff1af292b7f88f4c8a4fa8f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DWARFFormValue() {#aea38641ad6d13b90e729d7ebbc3368a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFFormValue::DWARFFormValue (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> F=<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a>(0))</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### DWARFFormValue() {#a9e9aaaa69e133c7693aa5a2ecff29237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFFormValue::DWARFFormValue (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfformvalue/valuetype">ValueType</a> &amp; V)</td>
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

<p>Context for extract time.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#abccb4aa356ed1bf8bae692df185a885a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFFormValue::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts=<a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#a644ff714cd89b432924d685f0f21adcb">dumpSectionedAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a986df42e8d99e128c31168ef61b02f5a">llvm::WithColor::get</a>, <a href="#a7fc1d711d6f952a305382ec6a518bfc5">getAsSectionedAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ad4ae565ad87db4c534952e2c88f310">llvm::nulls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a828913b4a1930e52edc8f9d696d0e560">llvm::DIDumpOptions::ShowAddresses</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#add6a33649e764a95f041d7b8358a019e">llvm::DIDumpOptions::Verbose</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a5ba2ece4b959bae02752c34b784ba087">llvm::raw_ostream::write_escaped</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#a337d62499b18cdbc7fa0a79cc820d09b">llvm::DWARFDebugLine::Prologue::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a6909786db93d43294a17f0dd5c5665e6">dumpLocationList</a>.</p>

</div>
</div>

### dumpAddress() {#a0373b5360a46d14a991fea39390d7240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFFormValue::dumpAddress (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfaddressrange/#af81b0ebe03203f548bf8244b75c5a65a">llvm::DWARFAddressRange::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugarangeset/descriptor/#abb37d4f66fa7518e6518d4f4a0b7b2c4">llvm::DWARFDebugArangeSet::Descriptor::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/rangelistentry/#a9490d0b5d168b24193e600de304103e1">llvm::RangeListEntry::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="#a644ff714cd89b432924d685f0f21adcb">dumpSectionedAddress</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a>.</p>

</div>
</div>

### dumpSectionedAddress() {#a644ff714cd89b432924d685f0f21adcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFFormValue::dumpSectionedAddress (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> SA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#a8807f1e455c2c5a36f3f2aaf617f823b">llvm::object::SectionedAddress::Address</a>, <a href="#a0373b5360a46d14a991fea39390d7240">dumpAddress</a>, <a href="#a0bdd3a234a4ad4d695aea54ddb2b92bf">dumpAddressSection</a> and <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#adb3de5796b8423b3f4442e10b55747a5">llvm::object::SectionedAddress::SectionIndex</a>.</p>


<p>Referenced by <a href="#abccb4aa356ed1bf8bae692df185a885a">dump</a>.</p>

</div>
</div>

### extractValue() {#aa146755e2500aea560c4417a30c0b96b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFFormValue::extractValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> &amp; Data, uint64_t * OffsetPtr, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> FormParams, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> * Context=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * Unit=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extracts a value in <span class="doxyComputerOutput">Data</span> at offset <span class="doxyComputerOutput">*OffsetPtr</span>.</p>


<p>The information in <span class="doxyComputerOutput">FormParams</span> is needed to interpret some forms. The optional <span class="doxyComputerOutput">Context</span> and <span class="doxyComputerOutput">Unit</span> allows extracting information if the form refers to other sections (e.g., .debug_str).</p>


<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0596fb939ff753151c9c37ed2b671b4c">llvm::errorToBool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a601419af5c3f8b56909c01a8596aecb7">llvm::dwarf_linker::parallel::DIEAttributeCloner::clone</a>, <a href="#ae10fbb14f19a44ed3a9464eb6cc36dc0">createFromUnit</a>, <a href="#ab279d9eb9f9ec4bd6a21f1d620952234">extractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfabbreviationdeclaration/#ae2e00474b41566a698cda953e1d62d3c">llvm::DWARFAbbreviationDeclaration::getAttributeValueFromOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a42ebac4ef7af0fc75e5f1a36dccd169a">llvm::dwarf_linker::parallel::DependencyTracker::maybeAddReferencedRoots</a> and <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/#a916b783c03f11e76d5144b3468d0c775">llvm::AppleAcceleratorTable::readAtoms</a>.</p>

</div>
</div>

### extractValue() {#ab279d9eb9f9ec4bd6a21f1d620952234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFFormValue::extractValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> &amp; Data, uint64_t * OffsetPtr, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> FormParams, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="#aa146755e2500aea560c4417a30c0b96b">extractValue</a>.</p>

</div>
</div>

### getAsAddress() {#a958f097ef2e9e5f193089b36ee820e85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFFormValue::getAsAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>Reference <a href="#a7fc1d711d6f952a305382ec6a518bfc5">getAsSectionedAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>.</p>

</div>
</div>

### getAsBlock() {#a3429295ea0185a78b39c2e853b13b851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ArrayRef&lt; uint8_t &gt; &gt; DWARFFormValue::getAsBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#a031683a2f97f9d8db3b493ada43e2228ab7f7ffb183c98435d2b766c0bd9412eb">FC_Block</a>, <a href="#a031683a2f97f9d8db3b493ada43e2228a5a1c5d88ff1af292b7f88f4c8a4fa8f1">FC_Exprloc</a> and <a href="#a7f4acdd5d8a9b78623878262b10f8e4f">isFormClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a00f85301e155c37fcab125f50a67cfb4">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneBlockAttr</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a180f88c410e11a7df7b17e9a782197e2">dumpLocationExpr</a>.</p>

</div>
</div>

### getAsCString() {#ae6bcf159d6ccb3adb4f7409e3adbbb37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const char * &gt; DWARFFormValue::getAsCString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="#a031683a2f97f9d8db3b493ada43e2228a39865546c65a182a3f9fa1bfe487203a">FC_String</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga4863132f9f3dd24b6df4cfc6c9cfb676">llvm::dwarf::FormEncodingString</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a17638a9e9146a6f6feef1adb50c53d2b">llvm::DataExtractor::getCStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="#a7f4acdd5d8a9b78623878262b10f8e4f">isFormClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#a337d62499b18cdbc7fa0a79cc820d09b">llvm::DWARFDebugLine::Prologue::dump</a>.</p>

</div>
</div>

### getAsCStringOffset() {#a210c090337f1fb2ac9920d9e193a24cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFFormValue::getAsCStringOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="#a031683a2f97f9d8db3b493ada43e2228a39865546c65a182a3f9fa1bfe487203a">FC_String</a> and <a href="#a7f4acdd5d8a9b78623878262b10f8e4f">isFormClass</a>.</p>

</div>
</div>

### getAsDebugInfoReference() {#ab967429b71c38060f3be76c48b359753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFFormValue::getAsDebugInfoReference ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ae40361c138fe76519f53bc8366a281c7">llvm::dwarf_linker::parallel::CompileUnit::resolveDIEReference</a>.</p>

</div>
</div>

### getAsFile() {#a2af35f9fb586ccbd0416130e8b3f17aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::string &gt; DWARFFormValue::getAsFile (<a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3">DILineInfoSpecifier::FileLineInfoKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Correctly extract any file paths from a form value.</p>


<p>These attributes can be in the from DW_AT_decl_file or DW_AT_call_file attributes. We need to use the file index in the correct <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a>'s line table prologue, and each <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> has the <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> the form value was extracted from.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Kind</td>
<td class="doxyParamItemDescription"><p>The kind of path to extract.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A valid string value on success, or std::nullopt if the form class is not FC_Constant, or if the file index is not valid.</p></dd>
</dl>


<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 758 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="#a031683a2f97f9d8db3b493ada43e2228a9190be54233acc999af9cb02ed854c0f">FC_Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a610e091c42196cd8bdddce77b7a407e4">llvm::DWARFUnit::getCompilationDir</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2f4b745612c1f38ddeeb42af9a4df2d8">llvm::DWARFUnit::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a6b034e23dde3985292359895c41c74f6">llvm::DWARFContext::getLineTableForUnit</a> and <a href="#a7f4acdd5d8a9b78623878262b10f8e4f">isFormClass</a>.</p>

</div>
</div>

### getAsReferenceUVal() {#a889eeb948d34e992d9d46f1174f9c457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFFormValue::getAsReferenceUVal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="#a031683a2f97f9d8db3b493ada43e2228aecc352ab32050f10e6c1d07d39eca711">FC_Reference</a> and <a href="#a7f4acdd5d8a9b78623878262b10f8e4f">isFormClass</a>.</p>

</div>
</div>

### getAsRelativeReference() {#aa379ebd24e7782b901ad1110ddd11833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFFormValue::getAsRelativeReference ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getAsFoo functions below return the extracted value as Foo if only <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> has form class is suitable for representing Foo.</p>

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ae40361c138fe76519f53bc8366a281c7">llvm::dwarf_linker::parallel::CompileUnit::resolveDIEReference</a>.</p>

</div>
</div>

### getAsSectionedAddress() {#a7fc1d711d6f952a305382ec6a518bfc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; object::SectionedAddress &gt; DWARFFormValue::getAsSectionedAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>Reference <a href="#a7fc1d711d6f952a305382ec6a518bfc5">getAsSectionedAddress</a>.</p>


<p>Referenced by <a href="#abccb4aa356ed1bf8bae692df185a885a">dump</a>, <a href="#a958f097ef2e9e5f193089b36ee820e85">getAsAddress</a> and <a href="#a7fc1d711d6f952a305382ec6a518bfc5">getAsSectionedAddress</a>.</p>

</div>
</div>

### getAsSectionOffset() {#a34b4361a52bbe519104734f746a248f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFFormValue::getAsSectionOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 706 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="#a031683a2f97f9d8db3b493ada43e2228ad4d4f9b4b3969ebc99a811b168072ff0">FC_SectionOffset</a> and <a href="#a7f4acdd5d8a9b78623878262b10f8e4f">isFormClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a46b9ec0a91b5f1a1ea42559b16bcdc4d">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneScalarAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a6909786db93d43294a17f0dd5c5665e6">dumpLocationList</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#adc641b1f4e9cea792161329bdaab4078">llvm::dwarf_linker::parallel::CompileUnit::getDirAndFilenameFromLineTable</a>.</p>

</div>
</div>

### getAsSignatureReference() {#aa8268c33eef15761e468285e4c18261b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFFormValue::getAsSignatureReference ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>

</div>
</div>

### getAsSignedConstant() {#a95368a5748aa1df8f1d4a2923585a3d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int64_t &gt; DWARFFormValue::getAsSignedConstant ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="#a031683a2f97f9d8db3b493ada43e2228a9190be54233acc999af9cb02ed854c0f">FC_Constant</a>, <a href="#a031683a2f97f9d8db3b493ada43e2228aa32d75d2d5fc3faca059726ac4615fd2">FC_Flag</a> and <a href="#a7f4acdd5d8a9b78623878262b10f8e4f">isFormClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a46b9ec0a91b5f1a1ea42559b16bcdc4d">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneScalarAttr</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#adc641b1f4e9cea792161329bdaab4078">llvm::dwarf_linker::parallel::CompileUnit::getDirAndFilenameFromLineTable</a>.</p>

</div>
</div>

### getAsSupplementaryReference() {#a2443b5a8ac3dd97f95bb66d3382b8e91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFFormValue::getAsSupplementaryReference ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>

</div>
</div>

### getAsUnsignedConstant() {#acf6d7ec7b1699c2bf60e54e032aae623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFFormValue::getAsUnsignedConstant ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="#a031683a2f97f9d8db3b493ada43e2228a9190be54233acc999af9cb02ed854c0f">FC_Constant</a>, <a href="#a031683a2f97f9d8db3b493ada43e2228aa32d75d2d5fc3faca059726ac4615fd2">FC_Flag</a> and <a href="#a7f4acdd5d8a9b78623878262b10f8e4f">isFormClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a46b9ec0a91b5f1a1ea42559b16bcdc4d">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneScalarAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#adc641b1f4e9cea792161329bdaab4078">llvm::dwarf_linker::parallel::CompileUnit::getDirAndFilenameFromLineTable</a> and <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/#a916b783c03f11e76d5144b3468d0c775">llvm::AppleAcceleratorTable::readAtoms</a>.</p>

</div>
</div>

### getForm() {#afae7527783aa2e969040c3cfcb4070c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Form llvm::DWARFFormValue::getForm ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a6909786db93d43294a17f0dd5c5665e6">dumpLocationList</a> and <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/#a5281584900ceee9be87126630f1fae12">llvm::AppleAcceleratorTable::validateForms</a>.</p>

</div>
</div>

### getRawUValue() {#aff41df6db83444b2f49193bc1f362fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFFormValue::getRawUValue ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#aba2b0348c09eb9e1b9245a012aab2503">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneAddressAttr</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry/#aeb639b3c403a927db9dd576cd989339d">llvm::DWARFDebugNames::Entry::dumpParentIdx</a>.</p>

</div>
</div>

### getUnit() {#af0a85f9b35aad5e7d4790835e4ce7515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFUnit * llvm::DWARFFormValue::getUnit ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ae40361c138fe76519f53bc8366a281c7">llvm::dwarf_linker::parallel::CompileUnit::resolveDIEReference</a>.</p>

</div>
</div>

### isFormClass() {#a7f4acdd5d8a9b78623878262b10f8e4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFFormValue::isFormClass (<a href="#a031683a2f97f9d8db3b493ada43e2228">FormClass</a> FC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a92aaa66ec12298250ec99438ffd2df2c">llvm::dwarf::doesFormBelongToClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a00f85301e155c37fcab125f50a67cfb4">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneBlockAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a180f88c410e11a7df7b17e9a782197e2">dumpLocationExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a6909786db93d43294a17f0dd5c5665e6">dumpLocationList</a>, <a href="#a3429295ea0185a78b39c2e853b13b851">getAsBlock</a>, <a href="#ae6bcf159d6ccb3adb4f7409e3adbbb37">getAsCString</a>, <a href="#a210c090337f1fb2ac9920d9e193a24cc">getAsCStringOffset</a>, <a href="#a2af35f9fb586ccbd0416130e8b3f17aa">getAsFile</a>, <a href="#a889eeb948d34e992d9d46f1174f9c457">getAsReferenceUVal</a>, <a href="#a34b4361a52bbe519104734f746a248f9">getAsSectionOffset</a>, <a href="#a95368a5748aa1df8f1d4a2923585a3d3">getAsSignedConstant</a>, <a href="#acf6d7ec7b1699c2bf60e54e032aae623">getAsUnsignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a42ebac4ef7af0fc75e5f1a36dccd169a">llvm::dwarf_linker::parallel::DependencyTracker::maybeAddReferencedRoots</a> and <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/#a5281584900ceee9be87126630f1fae12">llvm::AppleAcceleratorTable::validateForms</a>.</p>

</div>
</div>

### skipValue() {#ad16686174287aeb36289484f271d5225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFFormValue::skipValue (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> DebugInfoData, uint64_t * OffsetPtr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> Params)</td>
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

<p>Skip a form's value in <span class="doxyComputerOutput">DebugInfoData</span> at the offset specified by <span class="doxyComputerOutput">OffsetPtr</span>.</p>


<p>Skips the bytes for the current form and updates the offset.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DebugInfoData</td>
<td class="doxyParamItemDescription"><p>The data where we want to skip the value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OffsetPtr</td>
<td class="doxyParamItemDescription"><p>A reference to the offset that will be updated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Params</td>
<td class="doxyParamItemDescription"><p>DWARF parameters to help interpret forms.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true on success, false if the form was not skipped.</p></dd>
</dl>


<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>


<p>Reference <a href="#ad16686174287aeb36289484f271d5225">skipValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a601419af5c3f8b56909c01a8596aecb7">llvm::dwarf_linker::parallel::DIEAttributeCloner::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a8146aa10694a8fda28757fdd993823d9">llvm::DWARFDebugInfoEntry::extractFast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfabbreviationdeclaration/#a94f847fdc533254e25f90cd4ea91de3e">llvm::DWARFAbbreviationDeclaration::getAttributeOffsetFromIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a8bd04295f552ef30463ffb24174d649b">getCUIdentifiers</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a42ebac4ef7af0fc75e5f1a36dccd169a">llvm::dwarf_linker::parallel::DependencyTracker::maybeAddReferencedRoots</a> and <a href="#ad16686174287aeb36289484f271d5225">skipValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### dumpString() {#a1d900c7b58bfaeac8ec1d026c1f16ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFFormValue::dumpString (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### C {#ad51b270eb0cf95d9ec7e698a4295df63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFContext* llvm::DWARFFormValue::C = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remember the <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> at extract time.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>

</div>
</div>

### Form {#a95082bf19bbdfc92d035beb44c4a899b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Form llvm::DWARFFormValue::Form</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>

</div>
</div>

### Format {#ad1e27d849d5af4e400c07970add6136f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::DwarfFormat llvm::DWARFFormValue::Format</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Form for this value.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">dwarf::DWARF32</a>
</div>
</dd>
</dl>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>

</div>
</div>

### U {#a5b6c60be483941e921b0b89c688fc7cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFUnit* llvm::DWARFFormValue::U = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Contains all data for the form.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>

</div>
</div>

### Value {#a32f94fc848a42881d6d5f10e10a5df43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueType llvm::DWARFFormValue::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remember the DWARF format at extract time.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createFromBlockValue() {#ab9e25a95408ffef54103c6136b60b1e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFFormValue DWARFFormValue::createFromBlockValue (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; D)</td>
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



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfformvalue/valuetype/#a0e6a98b59f217c213dc64c3c3af9116d">llvm::DWARFFormValue::ValueType::uval</a>.</p>

</div>
</div>

### createFromPValue() {#a0c3905b85f3ac726af3668b04cc9fa68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFFormValue DWARFFormValue::createFromPValue (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * V)</td>
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



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a28f2b75ae3485678ba907fd613f90317">parseV2DirFileTables</a>.</p>

</div>
</div>

### createFromSValue() {#ac346eaa0ba929794c7261e78a757f7ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFFormValue DWARFFormValue::createFromSValue (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> F, int64_t V)</td>
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



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfabbreviationdeclaration/#ae2e00474b41566a698cda953e1d62d3c">llvm::DWARFAbbreviationDeclaration::getAttributeValueFromOffset</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec/#a3abfd85641f7025ead5cbc6ef45d59ad">llvm::DWARFAbbreviationDeclaration::AttributeSpec::getFormValue</a>.</p>

</div>
</div>

### createFromUnit() {#ae10fbb14f19a44ed3a9464eb6cc36dc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFFormValue DWARFFormValue::createFromUnit (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * Unit, uint64_t * OffsetPtr)</td>
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



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="#aa146755e2500aea560c4417a30c0b96b">extractValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### createFromUValue() {#a22ddba895c7cabfcfcd529211782ea71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFFormValue DWARFFormValue::createFromUValue (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> F, uint64_t V)</td>
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



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>.</p>

</div>
</div>

### dumpAddress() {#a6904315158f4d30aedc905545ff59d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFFormValue::dumpAddress (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint8_t AddressSize, uint64_t Address)</td>
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



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>.</p>

</div>
</div>

### dumpAddressSection() {#a0bdd3a234a4ad4d695aea54ddb2b92bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFFormValue::dumpAddressSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfobject">DWARFObject</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts, uint64_t SectionIndex)</td>
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



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a5fe2df7a6816980d149d6d31309936aa">llvm::DWARFObject::getSectionNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0f886fd1f1f18036b775a0cbe4c15bc6">llvm::dwarf_linker::SectionNames</a> and <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#add6a33649e764a95f041d7b8358a019e">llvm::DIDumpOptions::Verbose</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfaddressrange/#af81b0ebe03203f548bf8244b75c5a65a">llvm::DWARFAddressRange::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc/#a11cbb190f63755889353aaef746ba05a">llvm::DWARFDebugLoc::dumpRawEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloclists/#aaa38af193e8749bb5d9b945b405e933e">llvm::DWARFDebugLoclists::dumpRawEntry</a> and <a href="#a644ff714cd89b432924d685f0f21adcb">dumpSectionedAddress</a>.</p>

</div>
</div>

### getAsSectionedAddress() {#a806ef7f21e05aad3d69517e241b77a7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; object::SectionedAddress &gt; DWARFFormValue::getAsSectionedAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfformvalue/valuetype">ValueType</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> Form, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U)</td>
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



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a92aaa66ec12298250ec99438ffd2df2c">llvm::dwarf::doesFormBelongToClass</a> and <a href="#a031683a2f97f9d8db3b493ada43e2228ab9a403b58117de942610f95d22109d9c">FC_Address</a>.</p>

</div>
</div>

### skipValue() {#a4b10b1371b2d1f535ff65cf1aeed3158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFFormValue::skipValue (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> Form, <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> DebugInfoData, uint64_t * OffsetPtr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> FormParams)</td>
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

<p>Skip a form's value in <span class="doxyComputerOutput">DebugInfoData</span> at the offset specified by <span class="doxyComputerOutput">OffsetPtr</span>.</p>


<p>Skips the bytes for the specified form and updates the offset.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Form</td>
<td class="doxyParamItemDescription"><p>The DW_FORM enumeration that indicates the form to skip.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DebugInfoData</td>
<td class="doxyParamItemDescription"><p>The data where we want to skip the value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OffsetPtr</td>
<td class="doxyParamItemDescription"><p>A reference to the offset that will be updated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FormParams</td>
<td class="doxyParamItemDescription"><p>DWARF parameters to help interpret forms.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true on success, false if the form was not skipped.</p></dd>
</dl>


<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a17638a9e9146a6f6feef1adb50c53d2b">llvm::DataExtractor::getCStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa03b0ad8792b784269332332eb61d8ad">llvm::dwarf::getFixedFormByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a88a902fb0c1d600e6b4fe880d770acdf">llvm::DataExtractor::getSLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a98923ce73981e5171ef246bdcc6fde60">llvm::DataExtractor::getU16</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a0eb55ea3f585f9c8a2619fe7250e56f4">llvm::DataExtractor::getU32</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a45ee696c4102751e0194a0210c07dac0">llvm::DataExtractor::getU8</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a6f2f68613d44758a66e49320fb075a02">llvm::DataExtractor::getULEB128</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">DWARFFormValue.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfformvalue-cpp">DWARFFormValue.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
