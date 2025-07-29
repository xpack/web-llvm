---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DWARFDie.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">llvm/DebugInfo/DWARF/DWARFDie.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">llvm/DebugInfo/DWARF/DWARFAbbreviationDeclaration.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">llvm/DebugInfo/DWARF/DWARFContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">llvm/DebugInfo/DWARF/DWARFDebugLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugloc-h">llvm/DebugInfo/DWARF/DWARFDebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfexpression-h">llvm/DebugInfo/DWARF/DWARFExpression.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfformvalue-h">llvm/DebugInfo/DWARF/DWARFFormValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeprinter-h">llvm/DebugInfo/DWARF/DWARFTypePrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeunit-h">llvm/DebugInfo/DWARF/DWARFTypeUnit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">llvm/DebugInfo/DWARF/DWARFUnit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">llvm/Object/ObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">llvm/Support/DataExtractor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">llvm/Support/WithColor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cinttypes&gt;
#include &lt;cstdint&gt;
#include &lt;string&gt;
#include &lt;utility&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad26f8ef87191b57fd335580433bc6bd4">dumpApplePropertyAttribute</a> (raw_ostream &amp;OS, uint64_t Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade69f55e99e7ef15fbbb7468ac74b557">dumpRanges</a> (const DWARFObject &amp;Obj, raw_ostream &amp;OS, const DWARFAddressRangesVector &amp;Ranges, unsigned AddressSize, unsigned Indent, const DIDumpOptions &amp;DumpOpts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6909786db93d43294a17f0dd5c5665e6">dumpLocationList</a> (raw_ostream &amp;OS, const DWARFFormValue &amp;FormValue, DWARFUnit *U, unsigned Indent, DIDumpOptions DumpOpts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a180f88c410e11a7df7b17e9a782197e2">dumpLocationExpr</a> (raw_ostream &amp;OS, const DWARFFormValue &amp;FormValue, DWARFUnit *U, unsigned Indent, DIDumpOptions DumpOpts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5647dddfaab1db26a990598fdac978f0">resolveReferencedType</a> (DWARFDie D, DWARFFormValue F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a> (raw_ostream &amp;OS, const DWARFDie &amp;Die, const DWARFAttribute &amp;AttrValue, unsigned Indent, DIDumpOptions DumpOpts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accf3be3ee4da66e202a85c57bc4135a4">getTypeSizeImpl</a> (DWARFDie Die, uint64_t PointerSize, SmallPtrSetImpl&lt; const DWARFDebugInfoEntry * &gt; &amp;Visited)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50bceafadc9172f69d322e3f2eb1ad3f">dumpParentChain</a> (DWARFDie Die, raw_ostream &amp;OS, unsigned Indent, DIDumpOptions DumpOpts, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to dump a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with all of its parents, but no siblings. <a href="#a50bceafadc9172f69d322e3f2eb1ad3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### dumpApplePropertyAttribute() {#ad26f8ef87191b57fd335580433bc6bd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dumpApplePropertyAttribute (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t Val)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga96530f1970d440a1d1cd33bedbf19fba">llvm::dwarf::ApplePropertyString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>.</p>


<p>Referenced by <a href="#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>.</p>

</div>
</div>

### dumpAttribute() {#a0acd4c91ee5645013bd3ac2e45e90dba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dumpAttribute (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfattribute">DWARFAttribute</a> &amp; AttrValue, unsigned Indent, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3a7e2c85add6bbb98ae5b91471b11fd9a2">llvm::DILineInfoSpecifier::AbsoluteFilePath</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfattribute/#af1c7584c49ed3e3d9ad797a1eecfd835">llvm::DWARFAttribute::Attr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343af2bbdf9f72c085adc4d0404e370f0f4c">llvm::Attribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac0f9352892681cb5bc580382ff8f5929">llvm::dwarf::AttributeValueString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ad31a7a9cab8288e009f13cfabc5afc13">llvm::dwarf::computeTombstoneAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a22ddba895c7cabfcfcd529211782ea71">llvm::DWARFFormValue::createFromUValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#abccb4aa356ed1bf8bae692df185a885a">llvm::DWARFFormValue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a0373b5360a46d14a991fea39390d7240">llvm::DWARFFormValue::dumpAddress</a>, <a href="#ad26f8ef87191b57fd335580433bc6bd4">dumpApplePropertyAttribute</a>, <a href="#a180f88c410e11a7df7b17e9a782197e2">dumpLocationExpr</a>, <a href="#a6909786db93d43294a17f0dd5c5665e6">dumpLocationList</a>, <a href="#ade69f55e99e7ef15fbbb7468ac74b557">dumpRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9d0e8c22e295e665838a1f8fdff8676d">llvm::dumpTypeQualifiedName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a30309b565fa53a27f30668e22f7cf058">llvm::Enumerator</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a031683a2f97f9d8db3b493ada43e2228ab7f7ffb183c98435d2b766c0bd9412eb">llvm::DWARFFormValue::FC_Block</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a031683a2f97f9d8db3b493ada43e2228a5a1c5d88ff1af292b7f88f4c8a4fa8f1">llvm::DWARFFormValue::FC_Exprloc</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a031683a2f97f9d8db3b493ada43e2228ad4d4f9b4b3969ebc99a811b168072ff0">llvm::DWARFFormValue::FC_SectionOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a1eac3980947a504ac089ba80976debda">llvm::DWARFDie::getAddressRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a958f097ef2e9e5f193089b36ee820e85">llvm::DWARFFormValue::getAsAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a34b4361a52bbe519104734f746a248f9">llvm::DWARFFormValue::getAsSectionOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#acf6d7ec7b1699c2bf60e54e032aae623">llvm::DWARFFormValue::getAsUnsignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a2343cb0aab23f03ea5e28ea535894dd1">llvm::DWARFDie::getAttributeValueAsReferencedDie</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2f4b745612c1f38ddeeb42af9a4df2d8">llvm::DWARFUnit::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#af5ebc989c207cabcabe0e9943938ddf1">llvm::DWARFContext::getDWARFObj</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a4030d97efbcfaf77b80c112cd27c4214">llvm::DWARFDie::getDwarfUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#afae7527783aa2e969040c3cfcb4070c6">llvm::DWARFFormValue::getForm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a608a08ce1fda97817fddbc8b82b0b622">llvm::DWARFDie::getLowAndHighPC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a834590fd64e02e844dd117b380ab819b">llvm::DWARFDie::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a7f4acdd5d8a9b78623878262b10f8e4f">llvm::DWARFFormValue::isFormClass</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ae970d60ab52d996448bb030b4a0b67bc">llvm::DWARFDie::isValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfattribute/#abcfbc296ea65dfc9205a4211bfb2d45b">llvm::DWARFAttribute::mayHaveLocationExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfattribute/#a789c218461af8a727bcdfd037ee666b9">llvm::DWARFAttribute::mayHaveLocationList</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a37d04f96a64f8d44fb59b8ca1ab8935b">llvm::DIDumpOptions::RecoverableErrorHandler</a>, <a href="#a5647dddfaab1db26a990598fdac978f0">resolveReferencedType</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a828913b4a1930e52edc8f9d696d0e560">llvm::DIDumpOptions::ShowAddresses</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a3a0ae33bfdfe31cd538d48aea20ac452">llvm::DIDumpOptions::ShowForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a39a67e6dc97585d609932dc2fb04a377">llvm::dwarf::toString</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfattribute/#a88d7dfc62ca448b69b30e7ac4dcd02b4">llvm::DWARFAttribute::Value</a> and <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#add6a33649e764a95f041d7b8358a019e">llvm::DIDumpOptions::Verbose</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a>.</p>

</div>
</div>

### dumpLocationExpr() {#a180f88c410e11a7df7b17e9a782197e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dumpLocationExpr (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; FormValue, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U, unsigned Indent, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a031683a2f97f9d8db3b493ada43e2228ab7f7ffb183c98435d2b766c0bd9412eb">llvm::DWARFFormValue::FC_Block</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a031683a2f97f9d8db3b493ada43e2228a5a1c5d88ff1af292b7f88f4c8a4fa8f1">llvm::DWARFFormValue::FC_Exprloc</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a3429295ea0185a78b39c2e853b13b851">llvm::DWARFFormValue::getAsBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a7f4acdd5d8a9b78623878262b10f8e4f">llvm::DWARFFormValue::isFormClass</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acc23d591518160d5e67b43293906bc8a">llvm::DWARFExpression::print</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>.</p>

</div>
</div>

### dumpLocationList() {#a6909786db93d43294a17f0dd5c5665e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dumpLocationList (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; FormValue, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U, unsigned Indent, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#abccb4aa356ed1bf8bae692df185a885a">llvm::DWARFFormValue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a031683a2f97f9d8db3b493ada43e2228ad4d4f9b4b3969ebc99a811b168072ff0">llvm::DWARFFormValue::FC_SectionOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a34b4361a52bbe519104734f746a248f9">llvm::DWARFFormValue::getAsSectionOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#afae7527783aa2e969040c3cfcb4070c6">llvm::DWARFFormValue::getForm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a7f4acdd5d8a9b78623878262b10f8e4f">llvm::DWARFFormValue::isFormClass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>.</p>

</div>
</div>

### dumpParentChain() {#a50bceafadc9172f69d322e3f2eb1ad3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned dumpParentChain (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Die, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, unsigned Indent, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts, unsigned Depth=0)</td>
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

<p>Helper to dump a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with all of its parents, but no siblings.</p>

<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a>, <a href="#a50bceafadc9172f69d322e3f2eb1ad3f">dumpParentChain</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a2fa3d574c395e0628051860fc9be0463">llvm::DWARFDie::getParent</a> and <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#af55e071b0b0ed1579cc2cf244d7aa92e">llvm::DIDumpOptions::ParentRecurseDepth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a> and <a href="#a50bceafadc9172f69d322e3f2eb1ad3f">dumpParentChain</a>.</p>

</div>
</div>

### dumpRanges() {#ade69f55e99e7ef15fbbb7468ac74b557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dumpRanges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfobject">DWARFObject</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#af7b7409cf7c2a265eb671b0023fb9ebf">DWARFAddressRangesVector</a> &amp; Ranges, unsigned AddressSize, unsigned Indent, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> &amp; DumpOpts)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a> and <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a828913b4a1930e52edc8f9d696d0e560">llvm::DIDumpOptions::ShowAddresses</a>.</p>


<p>Referenced by <a href="#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>.</p>

</div>
</div>

### getTypeSizeImpl() {#accf3be3ee4da66e202a85c57bc4135a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; getTypeSizeImpl (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Die, uint64_t PointerSize, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * &gt; &amp; Visited)</td>
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



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a2343cb0aab23f03ea5e28ea535894dd1">llvm::DWARFDie::getAttributeValueAsReferencedDie</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a41fc5e2ca3d059c98029728b2677be44">llvm::DWARFDie::getDebugInfoEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ac07a6d11b09b4e2c92e9609b6843e9ea">llvm::DWARFDie::getTag</a>, <a href="#accf3be3ee4da66e202a85c57bc4135a4">getTypeSizeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a778b64ccbeb836841eb9b35bbe91e3c8">llvm::DWARFDie::getTypeSize</a> and <a href="#accf3be3ee4da66e202a85c57bc4135a4">getTypeSizeImpl</a>.</p>

</div>
</div>

### resolveReferencedType() {#a5647dddfaab1db26a990598fdac978f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie resolveReferencedType (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> D, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> F)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
