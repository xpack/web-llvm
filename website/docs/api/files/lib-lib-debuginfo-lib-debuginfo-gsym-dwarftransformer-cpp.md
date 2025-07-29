---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DwarfTransformer.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">llvm/DebugInfo/DIContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcompileunit-h">llvm/DebugInfo/DWARF/DWARFCompileUnit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">llvm/DebugInfo/DWARF/DWARFContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">llvm/Support/ThreadPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/dwarftransformer-h">llvm/DebugInfo/GSYM/DwarfTransformer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">llvm/DebugInfo/GSYM/FunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">llvm/DebugInfo/GSYM/GsymCreator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">llvm/DebugInfo/GSYM/GsymReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">llvm/DebugInfo/GSYM/InlineInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/outputaggregator-h">llvm/DebugInfo/GSYM/OutputAggregator.h</a>"
#include &lt;optional&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gsym/cuinfo">CUInfo</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae805ed41c31e2492528701718a34276a">GetParentDeclContextDIE</a> (DWARFDie &amp;Die)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa755805a8a835eba37c76377d871d3b0">getQualifiedNameIndex</a> (DWARFDie &amp;Die, uint64_t Language, GsymCreator &amp;Gsym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> string table offset for the qualified name for the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> passed in. <a href="#aa755805a8a835eba37c76377d871d3b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a814ac0131e04e8e9e7a715d8029ea010">hasInlineInfo</a> (DWARFDie Die, uint32_t Depth)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91569f1eeb48bfd99f2dba4301726d33">ConvertDWARFRanges</a> (const DWARFAddressRangesVector &amp;DwarfRanges)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a> (GsymCreator &amp;Gsym, OutputAggregator &amp;Out, CUInfo &amp;CUI, DWARFDie Die, uint32_t Depth, FunctionInfo &amp;FI, InlineInfo &amp;Parent, const AddressRanges &amp;AllParentRanges, bool &amp;WarnIfEmpty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a> (OutputAggregator &amp;Out, CUInfo &amp;CUI, DWARFDie Die, GsymCreator &amp;Gsym, FunctionInfo &amp;FI)</td>
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


<div class="doxySectionDef">

## Functions

### ConvertDWARFRanges() {#a91569f1eeb48bfd99f2dba4301726d33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddressRanges ConvertDWARFRanges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#af7b7409cf7c2a265eb671b0023fb9ebf">DWARFAddressRangesVector</a> &amp; DwarfRanges)</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>Referenced by <a href="#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>.</p>

</div>
</div>

### convertFunctionLineTable() {#af08e62850443dbd1f2003aac7845ab3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void convertFunctionLineTable (<a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator">OutputAggregator</a> &amp; Out, <a href="/web-llvm/docs/api/structs/llvm/gsym/cuinfo">CUInfo</a> &amp; CUI, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Die, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &amp; Gsym, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &amp; FI)</td>
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



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3a7e2c85add6bbb98ae5b91471b11fd9a2">llvm::DILineInfoSpecifier::AbsoluteFilePath</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/row/#a70339398304baa1ee590858b889e5c77">llvm::DWARFDebugLine::Row::Address</a>, <a href="/web-llvm/docs/api/classes/llvm/addressrange/#accce80061bb85f65b4223c49d91216a0">llvm::AddressRange::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/cuinfo/#a44c3e2e1f1513822fef926de568c244f">llvm::gsym::CUInfo::DWARFToGSYMFileIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a0ce61ffd4f47c4faabccb79d5c70a252">llvm::gsym::FunctionInfo::endAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a63fa5eea47d71eee71631388500cc8e5">llvm::DWARFDie::findRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a9d3dccb6b4b6b618de926e3863327b49">llvm::DWARFDie::getDeclFile</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a39edcd45ac2f03df8e7c2b8f32a1d19b">llvm::DIDumpOptions::getForSingleDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a14abe929fe7e3d9a46c3ad1d8a1eb2fd">llvm::DWARFDie::getOffset</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h/#ad9fd7a73c45fec3c647590738cef3fc9">HEX32</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h/#abedaa94d52e9958ad4a0d3790d0e4451">HEX64</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#ac9372d27c9fb107c96a7b241848d05ed">llvm::gsym::GsymCreator::insertFile</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/cuinfo/#a38439c35bdf12e0604fe47ea99c69a40">llvm::gsym::CUInfo::LineTable</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a910420e98a8f344483b3c461314898e3">llvm::DWARFDebugLine::LineTable::lookupAddressRange</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#aca03bd4694755ceb052d01df2cc3af82">llvm::gsym::FunctionInfo::OptLineTable</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a102aa70a223f40f43c99d916bc69a603">llvm::gsym::FunctionInfo::Range</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator/#a051eee638f618d1ebe54f433350b7c1d">llvm::gsym::OutputAggregator::Report</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a08f2df6a1aaacec42c6ded0585a11e4d">llvm::DWARFDebugLine::LineTable::Rows</a>, <a href="/web-llvm/docs/api/classes/llvm/addressrange/#a37ab39927de3ceda2cd6766243b516b9">llvm::AddressRange::start</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a0b158428fe205ce8c6f34d1ccd78f1fb">llvm::gsym::FunctionInfo::startAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a> and <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#aab5f6719f1bf1cfd6c53e95ebce09470">llvm::object::SectionedAddress::UndefSection</a>.</p>

</div>
</div>

### GetParentDeclContextDIE() {#ae805ed41c31e2492528701718a34276a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie GetParentDeclContextDIE (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a2343cb0aab23f03ea5e28ea535894dd1">llvm::DWARFDie::getAttributeValueAsReferencedDie</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a2fa3d574c395e0628051860fc9be0463">llvm::DWARFDie::getParent</a>, <a href="#ae805ed41c31e2492528701718a34276a">GetParentDeclContextDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ac07a6d11b09b4e2c92e9609b6843e9ea">llvm::DWARFDie::getTag</a>.</p>


<p>Referenced by <a href="#ae805ed41c31e2492528701718a34276a">GetParentDeclContextDIE</a> and <a href="#aa755805a8a835eba37c76377d871d3b0">getQualifiedNameIndex</a>.</p>

</div>
</div>

### getQualifiedNameIndex() {#aa755805a8a835eba37c76377d871d3b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; getQualifiedNameIndex (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, uint64_t Language, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &amp; Gsym)</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> string table offset for the qualified name for the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> passed in.</p>


<p>This function will avoid making copies of any strings in the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> when possible. We don't need to copy a string when the string comes from our .debug_str section or is an inlined string in the .debug_info. If we create a qualified name string in this function by combining multiple strings in the DWARF string table or info, we will make a copy of the string when we add it to the string table.</p>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5b6faabb08339ea1dd11e9d37a668634">llvm::StringRef::back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ac0e347575bcc3e0fd9caa27e1edfadef">llvm::DWARFDie::getLinkageName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a834590fd64e02e844dd117b380ab819b">llvm::DWARFDie::getName</a>, <a href="#ae805ed41c31e2492528701718a34276a">GetParentDeclContextDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a22638e32cb1220ddfacd7eb1bc5dfcf5">llvm::gsym::GsymCreator::insertString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870ad26b007baa81cc3cd38d8d6c93e6df42">llvm::ShortName</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>.</p>

</div>
</div>

### hasInlineInfo() {#a814ac0131e04e8e9e7a715d8029ea010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasInlineInfo (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Die, uint32_t Depth)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a1fa7cbc55eb0808d9fc434ef3efb5bca">llvm::DWARFDie::children</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ac07a6d11b09b4e2c92e9609b6843e9ea">llvm::DWARFDie::getTag</a> and <a href="#a814ac0131e04e8e9e7a715d8029ea010">hasInlineInfo</a>.</p>


<p>Referenced by <a href="#a814ac0131e04e8e9e7a715d8029ea010">hasInlineInfo</a> and <a href="#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>.</p>

</div>
</div>

### parseInlineInfo() {#a254758a009a4c05dee5c67ee26e61529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseInlineInfo (<a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &amp; Gsym, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator">OutputAggregator</a> &amp; Out, <a href="/web-llvm/docs/api/structs/llvm/gsym/cuinfo">CUInfo</a> &amp; CUI, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Die, uint32_t Depth, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &amp; FI, <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> &amp; Parent, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> &amp; AllParentRanges, bool &amp; WarnIfEmpty)</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp">DwarfTransformer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo/#a53d934eaa717abd9781a703afed2b3b2">llvm::gsym::InlineInfo::Children</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a1fa7cbc55eb0808d9fc434ef3efb5bca">llvm::DWARFDie::children</a>, <a href="/web-llvm/docs/api/classes/llvm/addressrangesbase/#a3f7dc6877a2e9502fe7c51b9aef7ce6f">llvm::AddressRangesBase&lt; T &gt;::contains</a>, <a href="#a91569f1eeb48bfd99f2dba4301726d33">ConvertDWARFRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/cuinfo/#a44c3e2e1f1513822fef926de568c244f">llvm::gsym::CUInfo::DWARFToGSYMFileIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a63fa5eea47d71eee71631388500cc8e5">llvm::DWARFDie::findRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a1eac3980947a504ac089ba80976debda">llvm::DWARFDie::getAddressRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a14abe929fe7e3d9a46c3ad1d8a1eb2fd">llvm::DWARFDie::getOffset</a>, <a href="#aa755805a8a835eba37c76377d871d3b0">getQualifiedNameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ac07a6d11b09b4e2c92e9609b6843e9ea">llvm::DWARFDie::getTag</a>, <a href="#a814ac0131e04e8e9e7a715d8029ea010">hasInlineInfo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h/#ad9fd7a73c45fec3c647590738cef3fc9">HEX32</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h/#abedaa94d52e9958ad4a0d3790d0e4451">HEX64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/cuinfo/#aa9acfdd97feb3ec5219b6abbf578cf30">llvm::gsym::CUInfo::Language</a>, <a href="#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo/#a55c9eb4dff498093824304e525a9017a">llvm::gsym::InlineInfo::Ranges</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator/#a051eee638f618d1ebe54f433350b7c1d">llvm::gsym::OutputAggregator::Report</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a>.</p>


<p>Referenced by <a href="#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
