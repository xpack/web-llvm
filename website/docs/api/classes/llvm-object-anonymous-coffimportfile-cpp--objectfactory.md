---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/anonymous-coffimportfile-cpp-/objectfactory
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ObjectFactory` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c76af0dcc381852892416e1b102101c">u16</a> = <a href="/web-llvm/docs/api/namespaces/llvm/support/#a4e29b3df92632c930b82161555c3b8d6">support::ulittle16_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e35e692815994fbe1481830d1f5e401">u32</a> = <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592eaf3a989e37e91d97e4109acf60ca">ObjectFactory</a> (StringRef S, MachineTypes M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/newarchivemember">NewArchiveMember</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a711507659368382a73cbb514ecdc53d0">createImportDescriptor</a> (std::vector&lt; uint8_t &gt; &amp;Buffer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/newarchivemember">NewArchiveMember</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ccea714ca92129b91646a8756af1ea3">createNullImportDescriptor</a> (std::vector&lt; uint8_t &gt; &amp;Buffer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/newarchivemember">NewArchiveMember</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a588e185cfb380f8a9206285676c0f321">createNullThunk</a> (std::vector&lt; uint8_t &gt; &amp;Buffer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/newarchivemember">NewArchiveMember</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0194b0cf6c8e570555fe9a8eb0c8d167">createShortImport</a> (StringRef Sym, uint16_t Ordinal, ImportType Type, ImportNameType NameType, StringRef ExportName, MachineTypes Machine)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/newarchivemember">NewArchiveMember</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f315ec5e0d164d9cfc44a35fa8d0828">createWeakExternal</a> (StringRef Sym, StringRef Weak, bool Imp, MachineTypes Machine)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d0c794f377ae479b7471c82620ea034">is64Bit</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8">MachineTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70d226af57d3f45b3c1211d1fd037b4a">NativeMachine</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3561c3a30c702f51e21d72d12d09a8d8">Alloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8505ad95cee8e5410c0698f777f4ab2a">ImportName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3421e4df4dbfde73873155cdda53b72c">Library</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab44ae2669bd2e37e7c90f9b8458d93ea">ImportDescriptorSymbolName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0587dac994a02b3d77c9a8cd353b889f">NullThunkSymbolName</a></td>
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


<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### u16 {#a7c76af0dcc381852892416e1b102101c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::u16 =  support::ulittle16_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>

</div>
</div>

### u32 {#a6e35e692815994fbe1481830d1f5e401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::u32 =  support::ulittle32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ObjectFactory() {#a592eaf3a989e37e91d97e4109acf60ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::ObjectFactory (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8">MachineTypes</a> M)</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#af433dfa7afd9b346f99c32aadd484114">llvm::object::ImportDescriptorPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a76efa8f8a29e582d7baeccbf548a3058">llvm::object::NullThunkDataPrefix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#abae8f3e6131a78a842714f24404ccbaf">llvm::object::NullThunkDataSuffix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createImportDescriptor() {#a711507659368382a73cbb514ecdc53d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NewArchiveMember llvm::object::ObjectFactory::createImportDescriptor (std::vector&lt; uint8_t &gt; &amp; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a07addf66b1e29aef725906aa868d736d">llvm::object::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae910a2dff8296efe077dd5121db763a2a1b54b088c84ddd9d94d3fedd18a5de1e">llvm::COFF::C_Invalid</a>, <a href="#a711507659368382a73cbb514ecdc53d0">createImportDescriptor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6c594664d7c57a587de68f6bae6d6aac">llvm::object::getImgRelRelocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae910a2dff8296efe077dd5121db763a2a75687afb19f3f8fe5d35b82eb9bb4f32">llvm::COFF::IMAGE_FILE_32BIT_MACHINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aab3c7c3378d0458f4989c89b9b90e4ee1">llvm::COFF::IMAGE_SCN_ALIGN_2BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa8e56a92024f9d15fa0ee42b68ca00e04">llvm::COFF::IMAGE_SCN_ALIGN_4BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa6a1c5fd37f3374c2e8e233d9e19bd205">llvm::COFF::IMAGE_SCN_CNT_INITIALIZED_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa3c5ce7207c84ca0e6a03fd08ab4831ba">llvm::COFF::IMAGE_SCN_MEM_READ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aac1dfcdc9a17df9b148557d4c01759767">llvm::COFF::IMAGE_SCN_MEM_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115a8b4296b2d59a622e33b331345fc9507b">llvm::COFF::IMAGE_SYM_CLASS_EXTERNAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115a45a16b5dd6e74cbfef8b2cb72dc418c4">llvm::COFF::IMAGE_SYM_CLASS_SECTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115afc617a23fd5e4cce7f2adfc7c2966e1c">llvm::COFF::IMAGE_SYM_CLASS_STATIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acb6f88f4307d83ce7c625a0775f2b512">llvm::COFF::is64Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-symbol/#a5532f6d49e6a8709bed19f99b274e279">llvm::object::coff_symbol&lt; SectionNumberType &gt;::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a102830d484cf8e6029c7103410e702b1">llvm::object::NullImportDescriptorSymbolName</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-symbol/#a48d42a4d8f92bf19723facdfe4f4a1a6">llvm::object::coff_symbol&lt; SectionNumberType &gt;::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/object/stringtableoffset/#a0aea7b3c0a46f0ba47ba50de5489ce71">llvm::object::StringTableOffset::Offset</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h/#a276e8a32e0bbf024aadd9420b8f2d3b3">offsetof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#ade2e0a3aaeed1571f499b1618fefa16f">llvm::object::writeStringTable</a>.</p>


<p>Referenced by <a href="#a711507659368382a73cbb514ecdc53d0">createImportDescriptor</a>.</p>

</div>
</div>

### createNullImportDescriptor() {#a3ccea714ca92129b91646a8756af1ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NewArchiveMember llvm::object::ObjectFactory::createNullImportDescriptor (std::vector&lt; uint8_t &gt; &amp; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a07addf66b1e29aef725906aa868d736d">llvm::object::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae910a2dff8296efe077dd5121db763a2a1b54b088c84ddd9d94d3fedd18a5de1e">llvm::COFF::C_Invalid</a>, <a href="#a3ccea714ca92129b91646a8756af1ea3">createNullImportDescriptor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae910a2dff8296efe077dd5121db763a2a75687afb19f3f8fe5d35b82eb9bb4f32">llvm::COFF::IMAGE_FILE_32BIT_MACHINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa8e56a92024f9d15fa0ee42b68ca00e04">llvm::COFF::IMAGE_SCN_ALIGN_4BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa6a1c5fd37f3374c2e8e233d9e19bd205">llvm::COFF::IMAGE_SCN_CNT_INITIALIZED_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa3c5ce7207c84ca0e6a03fd08ab4831ba">llvm::COFF::IMAGE_SCN_MEM_READ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aac1dfcdc9a17df9b148557d4c01759767">llvm::COFF::IMAGE_SCN_MEM_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115a8b4296b2d59a622e33b331345fc9507b">llvm::COFF::IMAGE_SYM_CLASS_EXTERNAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acb6f88f4307d83ce7c625a0775f2b512">llvm::COFF::is64Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-symbol/#a5532f6d49e6a8709bed19f99b274e279">llvm::object::coff_symbol&lt; SectionNumberType &gt;::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a102830d484cf8e6029c7103410e702b1">llvm::object::NullImportDescriptorSymbolName</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-symbol/#a48d42a4d8f92bf19723facdfe4f4a1a6">llvm::object::coff_symbol&lt; SectionNumberType &gt;::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/object/stringtableoffset/#a0aea7b3c0a46f0ba47ba50de5489ce71">llvm::object::StringTableOffset::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#ade2e0a3aaeed1571f499b1618fefa16f">llvm::object::writeStringTable</a>.</p>


<p>Referenced by <a href="#a3ccea714ca92129b91646a8756af1ea3">createNullImportDescriptor</a>.</p>

</div>
</div>

### createNullThunk() {#a588e185cfb380f8a9206285676c0f321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NewArchiveMember llvm::object::ObjectFactory::createNullThunk (std::vector&lt; uint8_t &gt; &amp; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a07addf66b1e29aef725906aa868d736d">llvm::object::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae910a2dff8296efe077dd5121db763a2a1b54b088c84ddd9d94d3fedd18a5de1e">llvm::COFF::C_Invalid</a>, <a href="#a588e185cfb380f8a9206285676c0f321">createNullThunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae910a2dff8296efe077dd5121db763a2a75687afb19f3f8fe5d35b82eb9bb4f32">llvm::COFF::IMAGE_FILE_32BIT_MACHINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa8e56a92024f9d15fa0ee42b68ca00e04">llvm::COFF::IMAGE_SCN_ALIGN_4BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa88c186e05b45bfa0468a57ead2951928">llvm::COFF::IMAGE_SCN_ALIGN_8BYTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa6a1c5fd37f3374c2e8e233d9e19bd205">llvm::COFF::IMAGE_SCN_CNT_INITIALIZED_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa3c5ce7207c84ca0e6a03fd08ab4831ba">llvm::COFF::IMAGE_SCN_MEM_READ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aac1dfcdc9a17df9b148557d4c01759767">llvm::COFF::IMAGE_SCN_MEM_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115a8b4296b2d59a622e33b331345fc9507b">llvm::COFF::IMAGE_SYM_CLASS_EXTERNAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acb6f88f4307d83ce7c625a0775f2b512">llvm::COFF::is64Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-symbol/#a5532f6d49e6a8709bed19f99b274e279">llvm::object::coff_symbol&lt; SectionNumberType &gt;::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-symbol/#a48d42a4d8f92bf19723facdfe4f4a1a6">llvm::object::coff_symbol&lt; SectionNumberType &gt;::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/object/stringtableoffset/#a0aea7b3c0a46f0ba47ba50de5489ce71">llvm::object::StringTableOffset::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#ade2e0a3aaeed1571f499b1618fefa16f">llvm::object::writeStringTable</a>.</p>


<p>Referenced by <a href="#a588e185cfb380f8a9206285676c0f321">createNullThunk</a>.</p>

</div>
</div>

### createShortImport() {#a0194b0cf6c8e570555fe9a8eb0c8d167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NewArchiveMember llvm::object::ObjectFactory::createShortImport (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Sym, uint16_t Ordinal, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a4f3aac6d3acb6d403ac4e0a9c9d4456b">ImportType</a> Type, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad4a4e9e3a0c174c170cb2badd2e5be45">ImportNameType</a> NameType, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ExportName, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8">MachineTypes</a> Machine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>


<p>References <a href="#a0194b0cf6c8e570555fe9a8eb0c8d167">createShortImport</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#a0194b0cf6c8e570555fe9a8eb0c8d167">createShortImport</a>.</p>

</div>
</div>

### createWeakExternal() {#a3f315ec5e0d164d9cfc44a35fa8d0828}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NewArchiveMember llvm::object::ObjectFactory::createWeakExternal (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Sym, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Weak, bool Imp, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8">MachineTypes</a> Machine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a07addf66b1e29aef725906aa868d736d">llvm::object::append</a>, <a href="#a3f315ec5e0d164d9cfc44a35fa8d0828">createWeakExternal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa61592fa0a2c7dc765dff44ec84f60e49">llvm::COFF::IMAGE_SCN_LNK_INFO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa24ac1300caa85825d3526b8baaec159f">llvm::COFF::IMAGE_SCN_LNK_REMOVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115a8b4296b2d59a622e33b331345fc9507b">llvm::COFF::IMAGE_SYM_CLASS_EXTERNAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115ad8a590fc93ee336e303f0ffb6e290244">llvm::COFF::IMAGE_SYM_CLASS_NULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115afc617a23fd5e4cce7f2adfc7c2966e1c">llvm::COFF::IMAGE_SYM_CLASS_STATIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115afbf31b8df4bc8375989d1e65af8c8925">llvm::COFF::IMAGE_SYM_CLASS_WEAK_EXTERNAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ac437dcd9750980233a278c48d2515271a24243cd03a81991e278a4817b463acdb">llvm::COFF::IMAGE_WEAK_EXTERN_SEARCH_ALIAS</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-symbol/#a5532f6d49e6a8709bed19f99b274e279">llvm::object::coff_symbol&lt; SectionNumberType &gt;::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-symbol/#a48d42a4d8f92bf19723facdfe4f4a1a6">llvm::object::coff_symbol&lt; SectionNumberType &gt;::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/object/stringtableoffset/#a0aea7b3c0a46f0ba47ba50de5489ce71">llvm::object::StringTableOffset::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#ade2e0a3aaeed1571f499b1618fefa16f">llvm::object::writeStringTable</a>.</p>


<p>Referenced by <a href="#a3f315ec5e0d164d9cfc44a35fa8d0828">createWeakExternal</a>.</p>

</div>
</div>

### is64Bit() {#a0d0c794f377ae479b7471c82620ea034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::is64Bit ()</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acb6f88f4307d83ce7c625a0775f2b512">llvm::COFF::is64Bit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Alloc {#a3561c3a30c702f51e21d72d12d09a8d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::Alloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>

</div>
</div>

### ImportDescriptorSymbolName {#ab44ae2669bd2e37e7c90f9b8458d93ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::ImportDescriptorSymbolName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>

</div>
</div>

### ImportName {#a8505ad95cee8e5410c0698f777f4ab2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::ImportName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>

</div>
</div>

### Library {#a3421e4df4dbfde73873155cdda53b72c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::Library</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>

</div>
</div>

### NativeMachine {#a70d226af57d3f45b3c1211d1fd037b4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineTypes llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::NativeMachine</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>

</div>
</div>

### NullThunkSymbolName {#a0587dac994a02b3d77c9a8cd353b889f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::NullThunkSymbolName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
