---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-diarawsymbol-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{DIARawSymbol.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{DIARawSymbol.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/pdb/variant">Variant</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a759c7de9c5527303336304d5187b87cf">VariantFromVARIANT</a> (const VARIANT &amp;V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ArgType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ArgType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab973aa56f18d9e3bfe6c35a43f0e9541">PrivateGetDIAValue</a> (IDiaSymbol *Symbol, HRESULT(__stdcall IDiaSymbol::*Method)(ArgType *))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ArgType, typename RetType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed96fa8a15ad8a1e99cd6ded4fcc1adc">PrivateGetDIAValue</a> (IDiaSymbol *Symbol, HRESULT(__stdcall IDiaSymbol::*Method)(ArgType *))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f98bb827bcc26d5dd09c53134e7f4ed">PrivateGetDIAValue</a> (IDiaSymbol *Symbol, HRESULT(__stdcall IDiaSymbol::*Method)(BSTR *))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeview/guid">codeview::GUID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae094dcc29b0ee25e7d2490c535722db0">PrivateGetDIAValue</a> (IDiaSymbol *Symbol, HRESULT(__stdcall IDiaSymbol::*Method)(GUID *))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PrintType, typename ArgType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acea763ad3b9fe7b1a2fe533b9f007473">DumpDIAValueAs</a> (llvm::raw_ostream &amp;OS, int Indent, StringRef Name, IDiaSymbol *Symbol, HRESULT(__stdcall IDiaSymbol::*Method)(ArgType *))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95012a5ac68fd943f9fa5ebd1e996f55">DumpDIAIdValue</a> (llvm::raw_ostream &amp;OS, int Indent, StringRef Name, IDiaSymbol *Symbol, HRESULT(__stdcall IDiaSymbol::*Method)(DWORD *), const IPDBSession &amp;Session, PdbSymbolIdField FieldId, PdbSymbolIdField ShowFlags, PdbSymbolIdField RecurseFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ArgType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0409b0be9b07cfd47e03317d085bb4ea">DumpDIAValue</a> (llvm::raw_ostream &amp;OS, int Indent, StringRef Name, IDiaSymbol *Symbol, HRESULT(__stdcall IDiaSymbol::*Method)(ArgType *))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f44467b6a1b954e529dd37ffec59aa">DumpDIAValue</a> (llvm::raw_ostream &amp;OS, int Indent, StringRef Name, IDiaSymbol *Symbol, HRESULT(__stdcall IDiaSymbol::*Method)(BSTR *))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a704e04339448a16c28d9b9b47df53f8c">DumpDIAValue</a> (llvm::raw_ostream &amp;OS, int Indent, StringRef Name, IDiaSymbol *Symbol, HRESULT(__stdcall IDiaSymbol::*Method)(VARIANT *))</td>
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

### DumpDIAIdValue() {#a95012a5ac68fd943f9fa5ebd1e996f55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DIARawSymbol.cpp}::DumpDIAIdValue (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; OS, int Indent, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, IDiaSymbol * Symbol, HRESULT(__stdcall IDiaSymbol::*)(DWORD *) Method, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbsession">IPDBSession</a> &amp; Session, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> FieldId, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> ShowFlags, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> RecurseFlags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aebe60f61f4fe8956834c561bfb8a75e8">llvm::pdb::dumpSymbolIdField</a>.</p>

</div>
</div>

### DumpDIAValue() {#a0409b0be9b07cfd47e03317d085bb4ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ArgType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DIARawSymbol.cpp}::DumpDIAValue (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; OS, int Indent, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, IDiaSymbol * Symbol, HRESULT(__stdcall IDiaSymbol::*)(ArgType *) Method)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a28e0e7c7f7920e3608fea13ec3e4394e">llvm::pdb::dumpSymbolField</a>.</p>

</div>
</div>

### DumpDIAValue() {#aa7f44467b6a1b954e529dd37ffec59aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DIARawSymbol.cpp}::DumpDIAValue (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; OS, int Indent, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, IDiaSymbol * Symbol, HRESULT(__stdcall IDiaSymbol::*)(BSTR *) Method)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa173f8cd4ef07c4ae06a26520daf8f7bf">llvm::pdb::BSTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8059c040f5af7b4554015074e49f5cd2">llvm::convertUTF16ToUTF8String</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a28e0e7c7f7920e3608fea13ec3e4394e">llvm::pdb::dumpSymbolField</a>.</p>

</div>
</div>

### DumpDIAValue() {#a704e04339448a16c28d9b9b47df53f8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DIARawSymbol.cpp}::DumpDIAValue (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; OS, int Indent, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, IDiaSymbol * Symbol, HRESULT(__stdcall IDiaSymbol::*)(VARIANT *) Method)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a28e0e7c7f7920e3608fea13ec3e4394e">llvm::pdb::dumpSymbolField</a> and <a href="#a759c7de9c5527303336304d5187b87cf">VariantFromVARIANT</a>.</p>

</div>
</div>

### DumpDIAValueAs() {#acea763ad3b9fe7b1a2fe533b9f007473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PrintType, typename ArgType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DIARawSymbol.cpp}::DumpDIAValueAs (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; OS, int Indent, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, IDiaSymbol * Symbol, HRESULT(__stdcall IDiaSymbol::*)(ArgType *) Method)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a28e0e7c7f7920e3608fea13ec3e4394e">llvm::pdb::dumpSymbolField</a>.</p>

</div>
</div>

### PrivateGetDIAValue() {#ab973aa56f18d9e3bfe6c35a43f0e9541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ArgType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgType anonymous{DIARawSymbol.cpp}::PrivateGetDIAValue (IDiaSymbol * Symbol, HRESULT(__stdcall IDiaSymbol::*)(ArgType *) Method)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a>.</p>

</div>
</div>

### PrivateGetDIAValue() {#aed96fa8a15ad8a1e99cd6ded4fcc1adc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ArgType, typename RetType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetType anonymous{DIARawSymbol.cpp}::PrivateGetDIAValue (IDiaSymbol * Symbol, HRESULT(__stdcall IDiaSymbol::*)(ArgType *) Method)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a>.</p>

</div>
</div>

### PrivateGetDIAValue() {#a5f98bb827bcc26d5dd09c53134e7f4ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{DIARawSymbol.cpp}::PrivateGetDIAValue (IDiaSymbol * Symbol, HRESULT(__stdcall IDiaSymbol::*)(BSTR *) Method)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa173f8cd4ef07c4ae06a26520daf8f7bf">llvm::pdb::BSTR</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diautils-h/#ad6c60a50832554e59decc8a64f4d6051">invokeBstrMethod</a>.</p>

</div>
</div>

### PrivateGetDIAValue() {#ae094dcc29b0ee25e7d2490c535722db0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::GUID anonymous{DIARawSymbol.cpp}::PrivateGetDIAValue (IDiaSymbol * Symbol, HRESULT(__stdcall IDiaSymbol::*)(GUID *) Method)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a>.</p>

</div>
</div>

### VariantFromVARIANT() {#a759c7de9c5527303336304d5187b87cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Variant anonymous{DIARawSymbol.cpp}::VariantFromVARIANT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VARIANT &amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9ea6527ac1698392492922f152309c9cab1">llvm::pdb::Bool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8059c040f5af7b4554015074e49f5cd2">llvm::convertUTF16ToUTF8String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9ead2ec7f6717029419e50f2c37332e8341">llvm::pdb::Double</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9ea3faf2bc8c8c4b0fb591b5d2604132bda">llvm::pdb::Int16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9ea786eecab07351b4cc9e4c33f4cf5691e">llvm::pdb::Int32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9ea68311183bd3c447d90828b5e2c90f582">llvm::pdb::Int64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9eab4469cd975dfe176a70d24e5904cedf6">llvm::pdb::Int8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9ea94b04abec1ca9dfc26d182145a2ff9de">llvm::pdb::Single</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9ea4501cbae351ca0ef6f162f946ba58d0e">llvm::pdb::String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9eaefdbbd0544eace5efa8f04052db39e1c">llvm::pdb::UInt16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9ea0ca360365331d9e298b726321529ee25">llvm::pdb::UInt32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9ea796898b84e5c80a0e59874e982646cec">llvm::pdb::UInt64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9eaf930816fdefa1f6cbb2c18a077d4fd7f">llvm::pdb::UInt8</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9eab5923ebc864d1679cf1c3a929c122037">llvm::pdb::Unknown</a>.</p>


<p>Referenced by <a href="#a704e04339448a16c28d9b9b47df53f8c">DumpDIAValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
