---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/object/coff-section
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `coff_section` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::object::coff_section { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">llvm/Object/COFF.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41f6a2580da2db22c06644782a8a1a5a">hasExtendedRelocations</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55b4f91a2ce6aa1f508fcb111489e592">getAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf355f3912e00f48f6a476ce4889eee">Name</a>[COFF::NameSize]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24835b5586d912858a9de0efbf6b8a15">VirtualSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa784468f9faf20b0d54bbe644a0b94f0">VirtualAddress</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8882aa2bfacd40fbbd4bac3f492269c6">SizeOfRawData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030e8ad39c3fe9a41a2f1927c5255701">PointerToRawData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9414df1bfeef620e659e9c076e554e4">PointerToRelocations</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6e873f1f415d5bf318c325a825bcdfd">PointerToLinenumbers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a4e29b3df92632c930b82161555c3b8d6">support::ulittle16_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a1d1041d981008585dba187df5f5af">NumberOfRelocations</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a4e29b3df92632c930b82161555c3b8d6">support::ulittle16_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e49d33d4d614726fc62a5264c42e0c8">NumberOfLinenumbers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d5c6f0e1d23df171e3bdd1c027a06e1">Characteristics</a></td>
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


<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getAlignment() {#a55b4f91a2ce6aa1f508fcb111489e592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::coff_section::getAlignment ()</td>
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



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a5d5c6f0e1d23df171e3bdd1c027a06e1">Characteristics</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa826c29f04efaa027000050ec33315703">llvm::COFF::IMAGE_SCN_TYPE_NO_PAD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#aeec303725814db1282e05d6f1d775fb2">llvm::object::COFFObjectFile::getSectionAlignment</a>.</p>

</div>
</div>

### hasExtendedRelocations() {#a41f6a2580da2db22c06644782a8a1a5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::coff_section::hasExtendedRelocations ()</td>
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



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a5d5c6f0e1d23df171e3bdd1c027a06e1">Characteristics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa7a0c196168bd2cee7fedcbcf0a5c8bf1">llvm::COFF::IMAGE_SCN_LNK_NRELOC_OVFL</a> and <a href="#ac2a1d1041d981008585dba187df5f5af">NumberOfRelocations</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#a5a4d2bf09a4074476f11647f7ac20126">getFirstReloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#a21926dd764fb7f7c891ec7c1ed725991">getNumberOfRelocations</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Characteristics {#a5d5c6f0e1d23df171e3bdd1c027a06e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::object::coff_section::Characteristics</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="#a55b4f91a2ce6aa1f508fcb111489e592">getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#ae71e8902775f8de0490455dc8c929d2f">llvm::RuntimeDyldCOFFThumb::getJITSymbolFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#aaa859579ac4adb9cbcebf0ddc98a085b">llvm::objcopy::coff::handleArgs</a>, <a href="#a41f6a2580da2db22c06644782a8a1a5a">hasExtendedRelocations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af84608c14d72c4d634360ce6a536e4a4">llvm::isRequiredForExecution</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a5b21593703df58c8a59363f737f0d064">llvm::object::COFFObjectFile::isSectionBSS</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#afab27e325389f1d03e34557b3a75f98c">llvm::object::COFFObjectFile::isSectionData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#aa3abf1f90c004e86372b780b11bca263">llvm::object::COFFObjectFile::isSectionText</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a50b4341d651ea41cb74546557170ebaa">llvm::logicalview::LVBinaryReader::mapVirtualAddress</a>.</p>

</div>
</div>

### Name {#a1cf355f3912e00f48f6a476ce4889eee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::object::coff_section::Name[COFF::NameSize]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a61b450c11951eeed5ec4560ce599ee87">llvm::object::COFFObjectFile::getSectionName</a>.</p>

</div>
</div>

### NumberOfLinenumbers {#a7e49d33d4d614726fc62a5264c42e0c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle16_t llvm::object::coff_section::NumberOfLinenumbers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### NumberOfRelocations {#ac2a1d1041d981008585dba187df5f5af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle16_t llvm::object::coff_section::NumberOfRelocations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#a21926dd764fb7f7c891ec7c1ed725991">getNumberOfRelocations</a> and <a href="#a41f6a2580da2db22c06644782a8a1a5a">hasExtendedRelocations</a>.</p>

</div>
</div>

### PointerToLinenumbers {#ac6e873f1f415d5bf318c325a825bcdfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::object::coff_section::PointerToLinenumbers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### PointerToRawData {#a030e8ad39c3fe9a41a2f1927c5255701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::object::coff_section::PointerToRawData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ae94132813b134e3bca64884e6b6b3cd5">llvm::object::COFFObjectFile::getSectionContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a769fe4d369055ba0768429c0b671c734">llvm::object::COFFObjectFile::isSectionVirtual</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a50b4341d651ea41cb74546557170ebaa">llvm::logicalview::LVBinaryReader::mapVirtualAddress</a>.</p>

</div>
</div>

### PointerToRelocations {#ab9414df1bfeef620e659e9c076e554e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::object::coff_section::PointerToRelocations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#a5a4d2bf09a4074476f11647f7ac20126">getFirstReloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#a21926dd764fb7f7c891ec7c1ed725991">getNumberOfRelocations</a>.</p>

</div>
</div>

### SizeOfRawData {#a8882aa2bfacd40fbbd4bac3f492269c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::object::coff_section::SizeOfRawData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a5f385ce6f800f27716d33de9bacc0729">llvm::object::COFFObjectFile::getSectionSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#aaa859579ac4adb9cbcebf0ddc98a085b">llvm::objcopy::coff::handleArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af84608c14d72c4d634360ce6a536e4a4">llvm::isRequiredForExecution</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a50b4341d651ea41cb74546557170ebaa">llvm::logicalview::LVBinaryReader::mapVirtualAddress</a>.</p>

</div>
</div>

### VirtualAddress {#aa784468f9faf20b0d54bbe644a0b94f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::object::coff_section::VirtualAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a62a40ad1dec679e8c38a9a1705e63ed6">llvm::object::COFFObjectFile::getSectionAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#aaa859579ac4adb9cbcebf0ddc98a085b">llvm::objcopy::coff::handleArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a50b4341d651ea41cb74546557170ebaa">llvm::logicalview::LVBinaryReader::mapVirtualAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a7a78994887ac9a82a012307b4f7baf27">llvm::object::COFFObjectFile::section_rel_begin</a>.</p>

</div>
</div>

### VirtualSize {#a24835b5586d912858a9de0efbf6b8a15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::object::coff_section::VirtualSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a5f385ce6f800f27716d33de9bacc0729">llvm::object::COFFObjectFile::getSectionSize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af84608c14d72c4d634360ce6a536e4a4">llvm::isRequiredForExecution</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
