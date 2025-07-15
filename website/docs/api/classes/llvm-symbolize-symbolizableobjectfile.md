---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/symbolize/symbolizableobjectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SymbolizableObjectFile` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::symbolize::SymbolizableObjectFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">llvm/DebugInfo/Symbolize/SymbolizableObjectFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule">SymbolizableModule</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f39324ed48c2c91f135b63665837699">SymbolizableObjectFile</a> (const object::ObjectFile *Obj, std::unique_ptr&lt; DIContext &gt; DICtx, bool UntagAddresses)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a218915a5f9c3f5f93eb5b91d64b86bef">symbolizeCode</a> (object::SectionedAddress ModuleOffset, DILineInfoSpecifier LineInfoSpecifier, bool UseSymbolTable) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diinlininginfo">DIInliningInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af579f0af68a8e23690bd1e3ef3ed2b0e">symbolizeInlinedCode</a> (object::SectionedAddress ModuleOffset, DILineInfoSpecifier LineInfoSpecifier, bool UseSymbolTable) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diglobal">DIGlobal</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16e36ac568ecb580c16c44a3b74a4cd0">symbolizeData</a> (object::SectionedAddress ModuleOffset) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dilocal">DILocal</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf76406be4473b3ff08ed20aeac28adb">symbolizeFrame</a> (object::SectionedAddress ModuleOffset) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e5710046e14b7ebaacb3dbb25efc989">findSymbol</a> (StringRef Symbol, uint64_t Offset) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac72e6fb0e20d5035a0208d0d1bd13955">isWin32Module</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1e9c1fa0a5e15a18b5391c33ef3d16c">getModulePreferredBase</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5e415b77b4e8374b6f9f0b677376618">shouldOverrideWithSymbolTable</a> (FunctionNameKind FNKind, bool UseSymbolTable) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90a6351375c01863cdb9ff57c20bbbbe">getNameFromSymbolTable</a> (uint64_t Address, std::string &amp;Name, uint64_t &amp;Addr, uint64_t &amp;Size, std::string &amp;FileName) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cdc182034461175c85afe46ad458ef7">addSymbol</a> (const object::SymbolRef &amp;Symbol, uint64_t SymbolSize, DataExtractor *OpdExtractor=nullptr, uint64_t OpdAddress=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168d32f18596273f397eb90310f11446">addCoffExportSymbols</a> (const object::COFFObjectFile *CoffObj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2d4dff082d92e1877b76599bbe3b182">getModuleSectionIndexForAddress</a> (uint64_t Address) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the first occurence of specified Address in <a href="/web-llvm/docs/api/classes/llvm/objectfile">ObjectFile</a>. <a href="#ab2d4dff082d92e1877b76599bbe3b182">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a713a2a65cb8d2ffe365cd92af20c926c">Module</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dicontext">DIContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ab4f50a57feaac7c4a9464cd18c3ce">DebugInfoContext</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8e9f307d2e3f22e4d9d1e507856aff9">UntagAddresses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; SymbolDesc &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee878c5d27b76085fa61d22d476dd68b">Symbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; uint32_t, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2da8fed12408cce59a05ceb096454299">FileSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile">SymbolizableObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ea94ca4d9dff028d5c6c11d8b045917">create</a> (const object::ObjectFile *Obj, std::unique_ptr&lt; DIContext &gt; DICtx, bool UntagAddresses)</td>
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


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### SymbolizableObjectFile() {#a4f39324ed48c2c91f135b63665837699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolizableObjectFile::SymbolizableObjectFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> * Obj, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dicontext">DIContext</a> &gt; DICtx, bool UntagAddresses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### findSymbol() {#a8e5710046e14b7ebaacb3dbb25efc989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; object::SectionedAddress &gt; SymbolizableObjectFile::findSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Symbol, uint64_t Offset)</td>
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



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getModulePreferredBase() {#aa1e9c1fa0a5e15a18b5391c33ef3d16c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t SymbolizableObjectFile::getModulePreferredBase ()</td>
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



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### isWin32Module() {#ac72e6fb0e20d5035a0208d0d1bd13955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SymbolizableObjectFile::isWin32Module ()</td>
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



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8ab9b603eafcb824ebeb03f246cff0b4d4">llvm::COFF::IMAGE_FILE_MACHINE_I386</a>.</p>

</div>
</div>

### symbolizeCode() {#a218915a5f9c3f5f93eb5b91d64b86bef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILineInfo SymbolizableObjectFile::symbolizeCode (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier">DILineInfoSpecifier</a> LineInfoSpecifier, bool UseSymbolTable)</td>
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



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#a8807f1e455c2c5a36f3f2aaf617f823b">llvm::object::SectionedAddress::Address</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#a1d2fecd19cf03aa8167943894af5f8c4">llvm::DILineInfo::BadString</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#aafbd532afdd9c251604c825b8368580d">llvm::DILineInfo::FileName</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#af080957130b4d8a21d897fe7b809b4e6">llvm::DILineInfoSpecifier::FNKind</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#ab8894db2d4e97b2f89e68769bea54b3b">llvm::DILineInfo::FunctionName</a>, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#adb3de5796b8423b3f4442e10b55747a5">llvm::object::SectionedAddress::SectionIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#a2b086783f95057c188bc04c705faff25">llvm::DILineInfo::StartAddress</a> and <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#aab5f6719f1bf1cfd6c53e95ebce09470">llvm::object::SectionedAddress::UndefSection</a>.</p>

</div>
</div>

### symbolizeData() {#a16e36ac568ecb580c16c44a3b74a4cd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIGlobal SymbolizableObjectFile::symbolizeData (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
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



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#a8807f1e455c2c5a36f3f2aaf617f823b">llvm::object::SectionedAddress::Address</a>, <a href="/web-llvm/docs/api/structs/llvm/diglobal/#a534e2ad980e4548cef7e4008d00f7824">llvm::DIGlobal::DeclFile</a>, <a href="/web-llvm/docs/api/structs/llvm/diglobal/#a61000cb0f5ccc6560e59178494649474">llvm::DIGlobal::DeclLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/diglobal/#a3cbdbd114c74f0ed2e9e49295f1593ea">llvm::DIGlobal::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/diglobal/#a074724206a257bfa774969c3faae70c1">llvm::DIGlobal::Size</a> and <a href="/web-llvm/docs/api/structs/llvm/diglobal/#a3839dc397e710342a45721424472bf15">llvm::DIGlobal::Start</a>.</p>

</div>
</div>

### symbolizeFrame() {#aaf76406be4473b3ff08ed20aeac28adb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; DILocal &gt; SymbolizableObjectFile::symbolizeFrame (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
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



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#a8807f1e455c2c5a36f3f2aaf617f823b">llvm::object::SectionedAddress::Address</a>, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#adb3de5796b8423b3f4442e10b55747a5">llvm::object::SectionedAddress::SectionIndex</a> and <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#aab5f6719f1bf1cfd6c53e95ebce09470">llvm::object::SectionedAddress::UndefSection</a>.</p>

</div>
</div>

### symbolizeInlinedCode() {#af579f0af68a8e23690bd1e3ef3ed2b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIInliningInfo SymbolizableObjectFile::symbolizeInlinedCode (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier">DILineInfoSpecifier</a> LineInfoSpecifier, bool UseSymbolTable)</td>
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



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#a8807f1e455c2c5a36f3f2aaf617f823b">llvm::object::SectionedAddress::Address</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#a1d2fecd19cf03aa8167943894af5f8c4">llvm::DILineInfo::BadString</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#aafbd532afdd9c251604c825b8368580d">llvm::DILineInfo::FileName</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#af080957130b4d8a21d897fe7b809b4e6">llvm::DILineInfoSpecifier::FNKind</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#ab8894db2d4e97b2f89e68769bea54b3b">llvm::DILineInfo::FunctionName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca0639979a0b27bb1cd0e0d94784fd3285">llvm::sampleprof::InlinedContext</a>, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#adb3de5796b8423b3f4442e10b55747a5">llvm::object::SectionedAddress::SectionIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#a2b086783f95057c188bc04c705faff25">llvm::DILineInfo::StartAddress</a> and <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#aab5f6719f1bf1cfd6c53e95ebce09470">llvm::object::SectionedAddress::UndefSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addCoffExportSymbols() {#a168d32f18596273f397eb90310f11446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SymbolizableObjectFile::addCoffExportSymbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile">object::COFFObjectFile</a> * CoffObj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>

</div>
</div>

### addSymbol() {#a2cdc182034461175c85afe46ad458ef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SymbolizableObjectFile::addSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">object::SymbolRef</a> &amp; Symbol, uint64_t SymbolSize, <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> * OpdExtractor=nullptr, uint64_t OpdAddress=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>

</div>
</div>

### getModuleSectionIndexForAddress() {#ab2d4dff082d92e1877b76599bbe3b182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t SymbolizableObjectFile::getModuleSectionIndexForAddress (uint64_t Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search for the first occurence of specified Address in <a href="/web-llvm/docs/api/classes/llvm/objectfile">ObjectFile</a>.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>

</div>
</div>

### getNameFromSymbolTable() {#a90a6351375c01863cdb9ff57c20bbbbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SymbolizableObjectFile::getNameFromSymbolTable (uint64_t Address, std::string &amp; Name, uint64_t &amp; Addr, uint64_t &amp; Size, std::string &amp; FileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>

</div>
</div>

### shouldOverrideWithSymbolTable() {#ab5e415b77b4e8374b6f9f0b677376618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SymbolizableObjectFile::shouldOverrideWithSymbolTable (<a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870">FunctionNameKind</a> FNKind, bool UseSymbolTable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DebugInfoContext {#a34ab4f50a57feaac7c4a9464cd18c3ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DIContext&gt; llvm::symbolize::SymbolizableObjectFile::DebugInfoContext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>.</p>

</div>
</div>

### FileSymbols {#a2da8fed12408cce59a05ceb096454299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;uint32_t, StringRef&gt; &gt; llvm::symbolize::SymbolizableObjectFile::FileSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>.</p>

</div>
</div>

### Module {#a713a2a65cb8d2ffe365cd92af20c926c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const object::ObjectFile* llvm::symbolize::SymbolizableObjectFile::Module</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>.</p>

</div>
</div>

### Symbols {#aee878c5d27b76085fa61d22d476dd68b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SymbolDesc&gt; llvm::symbolize::SymbolizableObjectFile::Symbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>.</p>

</div>
</div>

### UntagAddresses {#ae8e9f307d2e3f22e4d9d1e507856aff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::symbolize::SymbolizableObjectFile::UntagAddresses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a3ea94ca4d9dff028d5c6c11d8b045917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; SymbolizableObjectFile &gt; &gt; SymbolizableObjectFile::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> * Obj, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dicontext">DIContext</a> &gt; DICtx, bool UntagAddresses)</td>
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



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acf228956812ef6e7722e8c114fe3b923">llvm::object::computeSymbolSizes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#ade6a289b7efafc8625daf0575ad81c08">llvm::object::ObjectFile::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a43ad027c7a7cc0488f41d28529096967">llvm::object::ObjectFile::getBytesInAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a638ca5d7bf4e2a09998c8e7fe8563ad8">llvm::object::Binary::isLittleEndian</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a7f73649118e365a230be4870d824e7cf">llvm::object::ObjectFile::sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizableobjectfile-h">SymbolizableObjectFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolizableobjectfile-cpp">SymbolizableObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
