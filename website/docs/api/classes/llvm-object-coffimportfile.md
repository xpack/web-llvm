---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/coffimportfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `COFFImportFile` Class



## Declaration

<div class="doxyDeclaration">
class llvm::object::COFFImportFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">llvm/Object/COFFImportFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">SymbolicFile</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SymbolIndex { <a href="#af3c7151543eadf7602730ca437adfea7">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91dfa542412feb3ee7112eba1f9569c6">COFFImportFile</a> (MemoryBufferRef Source)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d73db2139a696b2313fec1c35a53cc1">moveSymbolNext</a> (DataRefImpl &amp;Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac68b1045f86cba91c3a222ea936595c5">printSymbolName</a> (raw_ostream &amp;OS, DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cb1f61fc8f27013003d760795fdf32a">getSymbolFlags</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ea33180758bfadfc25f3b2f471a7e9e">symbol_begin</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd2603f1a677486bf51ee9ea809ed39f">symbol_end</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57bd1f74a5f985281704305093dc279f">is64Bit</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-import-header">coff_import_header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cefee3781b746434326e85214ad52ac">getCOFFImportHeader</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb6311c33755bec8635be3a41057f924">getMachine</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d8a02f0ae2ba0e0132aa576c4f616fb">getFileFormatName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae96e0d873c421f268163eb04aa27b72">getExportName</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b1937dad859f4a5cfab3425abced267">isData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae652f4564590e1f02b2e2c84fe91ba7c">classof</a> (Binary const *V)</td>
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


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### SymbolIndex {#af3c7151543eadf7602730ca437adfea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::object::COFFImportFile::SymbolIndex </td>
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
<td class="doxyEnumItemName">ImpSymbol<a id="af3c7151543eadf7602730ca437adfea7ae3c7b5a6f6388a3be0b6070755deb456"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ThunkSymbol<a id="af3c7151543eadf7602730ca437adfea7a038c7e0cf2c85dda6da574b6bb46c763"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ECAuxSymbol<a id="af3c7151543eadf7602730ca437adfea7a0f0a9ed0ab9c051b4f42af5bd441fb27"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ECThunkSymbol<a id="af3c7151543eadf7602730ca437adfea7a2e1c4cfb8861475340b27e11b852ccc6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### COFFImportFile() {#a91dfa542412feb3ee7112eba1f9569c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::COFFImportFile::COFFImportFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Source)</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#af4e569b1876c0dbd751c766d6a1b926aaadad340ff64a200e953bd67604fa3965">llvm::object::Binary::ID_COFFImportFile</a> and <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a8eeef7e2323c6f1ec25eb240e1842fee">llvm::object::SymbolicFile::SymbolicFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCOFFImportHeader() {#a0cefee3781b746434326e85214ad52ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_import_header * llvm::object::COFFImportFile::getCOFFImportHeader ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>.</p>


<p>Referenced by <a href="#aae96e0d873c421f268163eb04aa27b72">getExportName</a> and <a href="#aeb6311c33755bec8635be3a41057f924">getMachine</a>.</p>

</div>
</div>

### getExportName() {#aae96e0d873c421f268163eb04aa27b72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::COFFImportFile::getExportName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a2582ad4e03989cb2e2712ae5ddf5e2a9">llvm::object::applyNameType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="#a0cefee3781b746434326e85214ad52ac">getCOFFImportHeader</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-import-header/#a45e75371adc80d56b66e92ef4cffcfb0">llvm::object::coff_import_header::getNameType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad4a4e9e3a0c174c170cb2badd2e5be45a92225bc24299e0d08480766408254e06">llvm::COFF::IMPORT_NAME_EXPORTAS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad4a4e9e3a0c174c170cb2badd2e5be45af4aacede2581867d5e256bb483b093ac">llvm::COFF::IMPORT_NAME_NOPREFIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad4a4e9e3a0c174c170cb2badd2e5be45aa7ea790597d87c53b00fec5e9d201e83">llvm::COFF::IMPORT_NAME_UNDECORATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad4a4e9e3a0c174c170cb2badd2e5be45a2d1fd4c41b0fab844452f97b8e04e95c">llvm::COFF::IMPORT_ORDINAL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>.</p>

</div>
</div>

### getFileFormatName() {#a7d8a02f0ae2ba0e0132aa576c4f616fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::COFFImportFile::getFileFormatName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>


<p>References <a href="#aeb6311c33755bec8635be3a41057f924">getMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a57211898d4494ccede1f9e90b92ebad4">llvm::COFF::IMAGE_FILE_MACHINE_AMD64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a0a3590d84a3fcf4c0f629a42e9384428">llvm::COFF::IMAGE_FILE_MACHINE_ARM64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a597eb40b38096e04b0e038af42dfa5a0">llvm::COFF::IMAGE_FILE_MACHINE_ARM64EC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8ae41778f19526c71645364352b56e06d4">llvm::COFF::IMAGE_FILE_MACHINE_ARM64X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8af90ffbdda9ed6facec414824d70f9de2">llvm::COFF::IMAGE_FILE_MACHINE_ARMNT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8ab9b603eafcb824ebeb03f246cff0b4d4">llvm::COFF::IMAGE_FILE_MACHINE_I386</a>.</p>

</div>
</div>

### getMachine() {#aeb6311c33755bec8635be3a41057f924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::COFFImportFile::getMachine ()</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>.</p>


<p>References <a href="#a0cefee3781b746434326e85214ad52ac">getCOFFImportHeader</a> and <a href="/web-llvm/docs/api/structs/llvm/object/coff-import-header/#a379b74f22154700ad709f6cf2890e951">llvm::object::coff_import_header::Machine</a>.</p>


<p>Referenced by <a href="#a7d8a02f0ae2ba0e0132aa576c4f616fb">getFileFormatName</a>, <a href="#ac68b1045f86cba91c3a222ea936595c5">printSymbolName</a> and <a href="#acd2603f1a677486bf51ee9ea809ed39f">symbol_end</a>.</p>

</div>
</div>

### getSymbolFlags() {#a4cb1f61fc8f27013003d760795fdf32a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; llvm::object::COFFImportFile::getSymbolFlags (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a1cc593ee22b60969ba0a3cb1e5e21b34">llvm::object::BasicSymbolRef::SF_Global</a>.</p>

</div>
</div>

### is64Bit() {#a57bd1f74a5f985281704305093dc279f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFImportFile::is64Bit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>.</p>

</div>
</div>

### moveSymbolNext() {#a7d73db2139a696b2313fec1c35a53cc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::COFFImportFile::moveSymbolNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>

</div>
</div>

### printSymbolName() {#ac68b1045f86cba91c3a222ea936595c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::object::COFFImportFile::printSymbolName (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a484450a0bb561c907c31db476c28772a">llvm::getArm64ECDemangledFunctionName</a>, <a href="#aeb6311c33755bec8635be3a41057f924">getMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad2af2071a60723ea6dd73bb28f238631">llvm::COFF::isArm64EC</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### symbol\_begin() {#a9ea33180758bfadfc25f3b2f471a7e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator llvm::object::COFFImportFile::symbol_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>.</p>

</div>
</div>

### symbol\_end() {#acd2603f1a677486bf51ee9ea809ed39f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator llvm::object::COFFImportFile::symbol_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>.</p>


<p>References <a href="#aeb6311c33755bec8635be3a41057f924">getMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad2af2071a60723ea6dd73bb28f238631">llvm::COFF::isArm64EC</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isData() {#a6b1937dad859f4a5cfab3425abced267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFImportFile::isData ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ae652f4564590e1f02b2e2c84fe91ba7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFImportFile::classof (<a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * V)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">COFFImportFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/coffimportfile-cpp">COFFImportFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
