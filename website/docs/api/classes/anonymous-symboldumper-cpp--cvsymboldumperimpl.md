---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-symboldumper-cpp-/cvsymboldumperimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CVSymbolDumperImpl` Class

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this private dumper implementation to keep implementation details about the visitor out of <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldumper-h">SymbolDumper.h</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitorcallbacks">SymbolVisitorCallbacks</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b507a7b7b6b6ec6ce522f1f65a1e14">CVSymbolDumperImpl</a> (TypeCollection &amp;Types, SymbolDumpDelegate *ObjDelegate, ScopedPrinter &amp;W, CPUType CPU, bool PrintRecordBytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdd17a4669d7d1cf98833763cfbb09c4">visitSymbolBegin</a> (CVSymbol &amp;Record) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4236f2c1eae2b4f515a4f75986e61b68">visitSymbolEnd</a> (CVSymbol &amp;Record) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd0a783cd91db1983a177bdfee26a6a9">visitUnknownSymbol</a> (CVSymbol &amp;Record) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Action to take on unknown symbols. By default, they are ignored. <a href="#abd0a783cd91db1983a177bdfee26a6a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3a314f44c015362563c5333db978173d">CPUType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70b83937cf8c80703daea2c01084530a">getCompilationCPUType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12c21dcdcb0ab314594ad487a40721eb">printLocalVariableAddrRange</a> (const LocalVariableAddrRange &amp;Range, uint32_t RelocationOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16a7fac0eb03cdcb4e2e4acf90a8b476">printLocalVariableAddrGap</a> (ArrayRef&lt; LocalVariableAddrGap &gt; Gaps)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d896a46ed1849e9df2bbab244c5d90">printTypeIndex</a> (StringRef FieldName, TypeIndex TI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typecollection">TypeCollection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8471b740432aaa93bdf2a0ca09f919">Types</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/symboldumpdelegate">SymbolDumpDelegate</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b08cc0594960f6afa6065eea510fd46">ObjDelegate</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7533be7b1a239921e0b2e0502fce189">W</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3a314f44c015362563c5333db978173d">CPUType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bdb4bb70e386a54f3eeeec14f00ce81">CompilationCPUType</a> = CPUType::X64</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Save the machine or CPU type when dumping a compile symbols. <a href="#a3bdb4bb70e386a54f3eeeec14f00ce81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6bca3dd981d9aa9cd7a000bdf7721fa">PrintRecordBytes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa17f8236300cf03f8ef6dbdc004374df">InFunctionScope</a></td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this private dumper implementation to keep implementation details about the visitor out of <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldumper-h">SymbolDumper.h</a>.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CVSymbolDumperImpl() {#af3b507a7b7b6b6ec6ce522f1f65a1e14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::CVSymbolDumperImpl (<a href="/web-llvm/docs/api/classes/llvm/codeview/typecollection">TypeCollection</a> &amp; Types, <a href="/web-llvm/docs/api/classes/llvm/codeview/symboldumpdelegate">SymbolDumpDelegate</a> * ObjDelegate, <a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp; W, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3a314f44c015362563c5333db978173d">CPUType</a> CPU, bool PrintRecordBytes)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCompilationCPUType() {#a70b83937cf8c80703daea2c01084530a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CPUType anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::getCompilationCPUType ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

### visitSymbolBegin() {#afdd17a4669d7d1cf98833763cfbb09c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CVSymbolDumperImpl::visitSymbolBegin (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp/#accfb4cec96e2903fc434688a5b344172">getSymbolKindName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a7c1504aff077c30eff33d31643dbb57d">llvm::codeview::getSymbolTypeNames</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord/#aaeef9f2a2d0dc09ec00ec9b38242c706">llvm::codeview::CVRecord&lt; Kind &gt;::kind</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitSymbolEnd() {#a4236f2c1eae2b4f515a4f75986e61b68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CVSymbolDumperImpl::visitSymbolEnd (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord/#acb4bfb2259905c9116067e4a2837fd4b">llvm::codeview::CVRecord&lt; Kind &gt;::content</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitUnknownSymbol() {#abd0a783cd91db1983a177bdfee26a6a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CVSymbolDumperImpl::visitUnknownSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record)</td>
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

<p>Action to take on unknown symbols. By default, they are ignored.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord/#ad2287d2f898bae38b5295534990e6856">llvm::codeview::CVRecord&lt; Kind &gt;::length</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### printLocalVariableAddrGap() {#a16a7fac0eb03cdcb4e2e4acf90a8b476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CVSymbolDumperImpl::printLocalVariableAddrGap (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/localvariableaddrgap">LocalVariableAddrGap</a> &gt; Gaps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

### printLocalVariableAddrRange() {#a12c21dcdcb0ab314594ad487a40721eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CVSymbolDumperImpl::printLocalVariableAddrRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/codeview/localvariableaddrrange">LocalVariableAddrRange</a> &amp; Range, uint32_t RelocationOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

### printTypeIndex() {#a87d896a46ed1849e9df2bbab244c5d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CVSymbolDumperImpl::printTypeIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CompilationCPUType {#a3bdb4bb70e386a54f3eeeec14f00ce81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CPUType anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::CompilationCPUType = CPUType::X64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Save the machine or CPU type when dumping a compile symbols.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

### InFunctionScope {#aa17f8236300cf03f8ef6dbdc004374df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::InFunctionScope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

### ObjDelegate {#a5b08cc0594960f6afa6065eea510fd46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolDumpDelegate* anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::ObjDelegate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

### PrintRecordBytes {#af6bca3dd981d9aa9cd7a000bdf7721fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::PrintRecordBytes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

### Types {#a6c8471b740432aaa93bdf2a0ca09f919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeCollection&amp; anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::Types</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

### W {#aa7533be7b1a239921e0b2e0502fce189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScopedPrinter&amp; anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::W</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
