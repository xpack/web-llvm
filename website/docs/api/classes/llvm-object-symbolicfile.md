---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/symbolicfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SymbolicFile` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::SymbolicFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">llvm/Object/SymbolicFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/coffimportfile">COFFImportFile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile">IRObjectFile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is the base class for all object file types. <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/tapifile">TapiFile</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cf1861651973dcb00123f21bf0ab33f">basic_symbol_iterator_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eeef7e2323c6f1ec25eb240e1842fee">SymbolicFile</a> (unsigned int Type, MemoryBufferRef Source)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e84cb6718ca7b956121a2f08becd9e0">~SymbolicFile</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac96de0097bfe22b147c27162a22d41bd">moveSymbolNext</a> (DataRefImpl &amp;Symb) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9715b85c91d21c116f17e9f08ac8015a">printSymbolName</a> (raw_ostream &amp;OS, DataRefImpl Symb) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa060785f66d4e44ba0fbdc3ae33a1e42">getSymbolFlags</a> (DataRefImpl Symb) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c5717c994df60bcbe3d9299f6a5982">symbol_begin</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc0f444aecc9b7aaef7facdb3d2bddb">symbol_end</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a635a922ee4f32bce5b1f3ae39e065c31">is64Bit</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4cf1861651973dcb00123f21bf0ab33f">basic_symbol_iterator_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa224a43fb4348654b3a36b5309630905">symbols</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">SymbolicFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ee418c47f5baa9b4b570371fc9630ce">createSymbolicFile</a> (MemoryBufferRef Object, llvm::file_magic Type, LLVMContext *Context, bool InitContent=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">SymbolicFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94a6766b2f7e1ec6eb4a07d8af35742f">createSymbolicFile</a> (MemoryBufferRef Object)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0951841c25d27d7f4cd67919fb84b7c8">classof</a> (const Binary *v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfda2a40879c19a80434914b8a55ce42">isSymbolicFile</a> (file_magic Type, const LLVMContext *Context)</td>
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


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### basic\_symbol\_iterator\_range {#a4cf1861651973dcb00123f21bf0ab33f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::SymbolicFile::basic_symbol_iterator_range =  iterator_range&lt;basic_symbol_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SymbolicFile() {#a8eeef7e2323c6f1ec25eb240e1842fee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolicFile::SymbolicFile (unsigned int Type, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Source)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/object/symbolicfile-cpp">SymbolicFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5efaba206c0c82deb1e8898c4c3aad4b">llvm::object::Binary::Binary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffimportfile/#a91dfa542412feb3ee7112eba1f9569c6">llvm::object::COFFImportFile::COFFImportFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#af74504142c7146b3602a3aa280d07df7">llvm::object::ObjectFile::ObjectFile</a> and <a href="/web-llvm/docs/api/classes/llvm/object/tapifile/#ac3c5a735a60750b0d6f1d232f3d359c3">llvm::object::TapiFile::TapiFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SymbolicFile() {#a8e84cb6718ca7b956121a2f08becd9e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolicFile::~SymbolicFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getSymbolFlags() {#aa060785f66d4e44ba0fbdc3ae33a1e42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; uint32_t &gt; llvm::object::SymbolicFile::getSymbolFlags (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a0be1fdc703dfefdcd9298662351d5daf">llvm::object::ObjectFile::getCommonSymbolSize</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aa520e1a721f81e1befb66b422c6e4a60">llvm::object::ObjectFile::getSymbolValue</a>.</p>

</div>
</div>

### is64Bit() {#a635a922ee4f32bce5b1f3ae39e065c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::object::SymbolicFile::is64Bit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#ab1e1cc599a5a829c5962a07153a9a8c1">llvm::object::XCOFFSymbolRef::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a26a389fcf3a6cc81cb007bfcf9f253c5">is64BitSymbolicFile</a>.</p>

</div>
</div>

### moveSymbolNext() {#ac96de0097bfe22b147c27162a22d41bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::object::SymbolicFile::moveSymbolNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>

</div>
</div>

### printSymbolName() {#a9715b85c91d21c116f17e9f08ac8015a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::object::SymbolicFile::printSymbolName (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>

</div>
</div>

### symbol\_begin() {#a40c5717c994df60bcbe3d9299f6a5982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual basic_symbol_iterator llvm::object::SymbolicFile::symbol_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af089befa203447cdf71f665a1993a997">llvm::RuntimeDyldImpl::computeTotalAllocSize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afe85af578989c7f3e9627866e7fa4962">llvm::RuntimeDyldImpl::loadObjectImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-oprofilejiteventlistener-cpp-/oprofilejiteventlistener/#a5c97ec6ebe56df1ba872dcd002f860d5">anonymous{OProfileJITEventListener.cpp}::OProfileJITEventListener::notifyFreeingObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#aa82326b6efec7b9b4135f9c346c9eb8c">llvm::object::ELFObjectFileBase::symbols</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aa22a9825f4937b28269552f5b8db4a69">llvm::object::ObjectFile::symbols</a> and <a href="#aa224a43fb4348654b3a36b5309630905">symbols</a>.</p>

</div>
</div>

### symbol\_end() {#a7bc0f444aecc9b7aaef7facdb3d2bddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual basic_symbol_iterator llvm::object::SymbolicFile::symbol_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af089befa203447cdf71f665a1993a997">llvm::RuntimeDyldImpl::computeTotalAllocSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#ab5019ff9e3502f422f3d8668201f5756">llvm::object::ELFObjectFileBase::getPltEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#aaca2a6196a0b153d686419f0fd252e91">getSymbolInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afe85af578989c7f3e9627866e7fa4962">llvm::RuntimeDyldImpl::loadObjectImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-oprofilejiteventlistener-cpp-/oprofilejiteventlistener/#a5c97ec6ebe56df1ba872dcd002f860d5">anonymous{OProfileJITEventListener.cpp}::OProfileJITEventListener::notifyFreeingObject</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#a47afe575c279c175037d664bde7e53a3">llvm::RuntimeDyldCOFFI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a200d4c53b00f55a8d0911279bf576c18">llvm::RuntimeDyldCOFFThumb::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#afcf3722d9ca669767870af1a84877924">llvm::RuntimeDyldCOFFX86_64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#aa82326b6efec7b9b4135f9c346c9eb8c">llvm::object::ELFObjectFileBase::symbols</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aa22a9825f4937b28269552f5b8db4a69">llvm::object::ObjectFile::symbols</a> and <a href="#aa224a43fb4348654b3a36b5309630905">symbols</a>.</p>

</div>
</div>

### symbols() {#aa224a43fb4348654b3a36b5309630905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator_range llvm::object::SymbolicFile::symbols ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<p>References <a href="#a40c5717c994df60bcbe3d9299f6a5982">symbol_begin</a> and <a href="#a7bc0f444aecc9b7aaef7facdb3d2bddb">symbol_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a1f4394e4fc8872fa8f2a5baca5b3cc4b">getSymbols</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a0951841c25d27d7f4cd67919fb84b7c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SymbolicFile::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> * v)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5efaba206c0c82deb1e8898c4c3aad4b">llvm::object::Binary::Binary</a>.</p>

</div>
</div>

### createSymbolicFile() {#a4ee418c47f5baa9b4b570371fc9630ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; SymbolicFile &gt; &gt; SymbolicFile::createSymbolicFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object, <a href="/web-llvm/docs/api/structs/llvm/file-magic">llvm::file_magic</a> Type, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> * Context, bool InitContent=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/object/symbolicfile-cpp">SymbolicFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa9b217cf59bac16d57cf52c3e76f3ce50">llvm::file_magic::bitcode</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa007729224f13c224129cef854ce5fc0c">llvm::file_magic::coff_import_library</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aac575f4e16f05741d7656211f860dfcc3">llvm::file_magic::coff_object</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile/#afcce1b766f055cfac90081cebb14ad23">llvm::object::IRObjectFile::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aad31db91c55e2f1f5090ddbe652c20b1f">llvm::file_magic::elf</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aabf5672e0a28c6ed1db85035f1b85fc5b">llvm::file_magic::elf_core</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa46a884b4756415ac19d0ac5d2bf56079">llvm::file_magic::elf_executable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa1b167178973059ff5b3a4b2bf2377450">llvm::file_magic::elf_relocatable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa380638a0d06dd9003d4dd307f7b0851c">llvm::file_magic::elf_shared_object</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile/#a803ed79cb2444088841a8c8618b21ab8">llvm::object::IRObjectFile::findBitcodeInObject</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa40ebaa45e99e5d81f24d506e33afdb42">llvm::file_magic::goff_object</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00941e59a16ad6eb14e905557a612501">llvm::identify_magic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20ad5a8a27f4e310ea593b285615faaca35">llvm::object::invalid_file_type</a>, <a href="#abfda2a40879c19a80434914b8a55ce42">isSymbolicFile</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aad50da1fb17899eb0b0f714edf96c83c7">llvm::file_magic::macho_bundle</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aaa01c66176cb9de4bb75c2b551133e38e">llvm::file_magic::macho_core</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aae40fb5199f3d0b10d917738a06b4b6b0">llvm::file_magic::macho_dsym_companion</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aaea9f98c476ea8892d4bf66157d526cde">llvm::file_magic::macho_dynamic_linker</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa45f3946b8331a826457113aa5d81bc96">llvm::file_magic::macho_dynamically_linked_shared_lib</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa56440a39ccbe80c75e2e674aaafd00d4">llvm::file_magic::macho_dynamically_linked_shared_lib_stub</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aae3fbcf9e4d077fe08e7e73eb785f0a2c">llvm::file_magic::macho_executable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa75fee6d4cd7dfafcb268524c93b56101">llvm::file_magic::macho_file_set</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aae796c2e08310bfe518ffc166cb788601">llvm::file_magic::macho_fixed_virtual_memory_shared_lib</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa86da0e718a3fbe29422c095c55af3bfa">llvm::file_magic::macho_kext_bundle</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aac557d5088dac1a5cca0c2c7e78174632">llvm::file_magic::macho_object</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa590d298012f657bc6b970e50d9f774c1">llvm::file_magic::macho_preload_executable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa906a95690dc1df5a24e4253c83edd77c">llvm::file_magic::pecoff_executable</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aae5a2f339dd671d3caf9b616ef7bf1efd">llvm::file_magic::unknown</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aaa0dedd1117ef34a81cb4b8751c3c1e4f">llvm::file_magic::wasm_object</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aaa39e4e5aa8493605e279d127dc484379">llvm::file_magic::xcoff_object_32</a> and <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa45ff397494885b031c2b6a75797e7d7e">llvm::file_magic::xcoff_object_64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/object/#aebd3886db896c46327320cfd1ccc808c">llvm::object::createBinary</a>, <a href="#a94a6766b2f7e1ec6eb4a07d8af35742f">createSymbolicFile</a>, <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#a5b9ae09da2b1f1939e37ba537fdf9eb1">llvm::NewArchiveMember::detectKindFromObject</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a838e4f1a36cc927704247e621bcf0204">getSymbolicFile</a>.</p>

</div>
</div>

### createSymbolicFile() {#a94a6766b2f7e1ec6eb4a07d8af35742f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; SymbolicFile &gt; &gt; llvm::object::SymbolicFile::createSymbolicFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>.</p>


<p>References <a href="#a4ee418c47f5baa9b4b570371fc9630ce">createSymbolicFile</a> and <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aae5a2f339dd671d3caf9b616ef7bf1efd">llvm::file_magic::unknown</a>.</p>

</div>
</div>

### isSymbolicFile() {#abfda2a40879c19a80434914b8a55ce42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SymbolicFile::isSymbolicFile (<a href="/web-llvm/docs/api/structs/llvm/file-magic">file_magic</a> Type, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> * Context)</td>
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



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/object/symbolicfile-cpp">SymbolicFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa9b217cf59bac16d57cf52c3e76f3ce50">llvm::file_magic::bitcode</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa007729224f13c224129cef854ce5fc0c">llvm::file_magic::coff_import_library</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aac575f4e16f05741d7656211f860dfcc3">llvm::file_magic::coff_object</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aad31db91c55e2f1f5090ddbe652c20b1f">llvm::file_magic::elf</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aabf5672e0a28c6ed1db85035f1b85fc5b">llvm::file_magic::elf_core</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa46a884b4756415ac19d0ac5d2bf56079">llvm::file_magic::elf_executable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa1b167178973059ff5b3a4b2bf2377450">llvm::file_magic::elf_relocatable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa380638a0d06dd9003d4dd307f7b0851c">llvm::file_magic::elf_shared_object</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa40ebaa45e99e5d81f24d506e33afdb42">llvm::file_magic::goff_object</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aad50da1fb17899eb0b0f714edf96c83c7">llvm::file_magic::macho_bundle</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aaa01c66176cb9de4bb75c2b551133e38e">llvm::file_magic::macho_core</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aae40fb5199f3d0b10d917738a06b4b6b0">llvm::file_magic::macho_dsym_companion</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aaea9f98c476ea8892d4bf66157d526cde">llvm::file_magic::macho_dynamic_linker</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa45f3946b8331a826457113aa5d81bc96">llvm::file_magic::macho_dynamically_linked_shared_lib</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa56440a39ccbe80c75e2e674aaafd00d4">llvm::file_magic::macho_dynamically_linked_shared_lib_stub</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aae3fbcf9e4d077fe08e7e73eb785f0a2c">llvm::file_magic::macho_executable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa75fee6d4cd7dfafcb268524c93b56101">llvm::file_magic::macho_file_set</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aae796c2e08310bfe518ffc166cb788601">llvm::file_magic::macho_fixed_virtual_memory_shared_lib</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa86da0e718a3fbe29422c095c55af3bfa">llvm::file_magic::macho_kext_bundle</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aac557d5088dac1a5cca0c2c7e78174632">llvm::file_magic::macho_object</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa590d298012f657bc6b970e50d9f774c1">llvm::file_magic::macho_preload_executable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa906a95690dc1df5a24e4253c83edd77c">llvm::file_magic::pecoff_executable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aaa0dedd1117ef34a81cb4b8751c3c1e4f">llvm::file_magic::wasm_object</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aaa39e4e5aa8493605e279d127dc484379">llvm::file_magic::xcoff_object_32</a> and <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa45ff397494885b031c2b6a75797e7d7e">llvm::file_magic::xcoff_object_64</a>.</p>


<p>Referenced by <a href="#a4ee418c47f5baa9b4b570371fc9630ce">createSymbolicFile</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a838e4f1a36cc927704247e621bcf0204">getSymbolicFile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">SymbolicFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/symbolicfile-cpp">SymbolicFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
