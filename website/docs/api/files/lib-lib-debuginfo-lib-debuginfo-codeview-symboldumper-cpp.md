---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SymbolDumper.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldumper-h">llvm/DebugInfo/CodeView/SymbolDumper.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvsymbolvisitor-h">llvm/DebugInfo/CodeView/CVSymbolVisitor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugstringtablesubsection-h">llvm/DebugInfo/CodeView/DebugStringTableSubsection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/enumtables-h">llvm/DebugInfo/CodeView/EnumTables.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">llvm/DebugInfo/CodeView/SymbolDeserializer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldumpdelegate-h">llvm/DebugInfo/CodeView/SymbolDumpDelegate.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">llvm/DebugInfo/CodeView/SymbolRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolvisitorcallbackpipeline-h">llvm/DebugInfo/CodeView/SymbolVisitorCallbackPipeline.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolvisitorcallbacks-h">llvm/DebugInfo/CodeView/SymbolVisitorCallbacks.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typeindex-h">llvm/DebugInfo/CodeView/TypeIndex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scopedprinter-h">llvm/Support/ScopedPrinter.h</a>"
#include "llvm/DebugInfo/CodeView/CodeViewSymbols.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-symboldumper-cpp-">anonymous{SymbolDumper.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-symboldumper-cpp-/cvsymboldumperimpl">CVSymbolDumperImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this private dumper implementation to keep implementation details about the visitor out of <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldumper-h">SymbolDumper.h</a>. <a href="/web-llvm/docs/api/classes/anonymous-symboldumper-cpp-/cvsymboldumperimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accfb4cec96e2903fc434688a5b344172">getSymbolKindName</a> (SymbolKind Kind)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b7c796b66e8f676b7405babeac39cc">SYMBOL_RECORD</a>(EnumName, EnumVal, Name)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvsymbolvisitor-cpp/#ad5efdd36be98503f918fde701e83b28b">visitKnownRecord</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp;CVR, Name &amp;<a href="/web-llvm/docs/api/classes/llvm/record">Record</a>) override;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/codeview/cvsymbolvisitor">CVSymbolVisitor</a> overrides. <a href="#ab6b7c796b66e8f676b7405babeac39cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11f9ef2d1b54587ddeb3e53c450e75e3">SYMBOL_RECORD_ALIAS</a>(EnumName, EnumVal, Name, AliasName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62e34730e42b815aff4728aabed1135e">SYMBOL_RECORD</a>(EnumName, EnumVal, Name)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/codeview/cvsymbolvisitor">CVSymbolVisitor</a> overrides. <a href="#a62e34730e42b815aff4728aabed1135e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### getSymbolKindName() {#accfb4cec96e2903fc434688a5b344172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getSymbolKindName (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac3fd578f133e7ee0210c835b393bca59">SymbolKind</a> Kind)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-symboldumper-cpp-/cvsymboldumperimpl/#afdd17a4669d7d1cf98833763cfbb09c4">anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::visitSymbolBegin</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### SYMBOL\_RECORD {#ab6b7c796b66e8f676b7405babeac39cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SYMBOL_RECORD(EnumName, EnumVal, Name)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvsymbolvisitor-cpp/#ad5efdd36be98503f918fde701e83b28b">visitKnownRecord</a>(<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp;CVR, Name &amp;<a href="/web-llvm/docs/api/classes/llvm/record">Record</a>) override;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/codeview/cvsymbolvisitor">CVSymbolVisitor</a> overrides.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

### SYMBOL\_RECORD {#a62e34730e42b815aff4728aabed1135e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SYMBOL_RECORD(EnumName, EnumVal, Name)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/codeview/cvsymbolvisitor">CVSymbolVisitor</a> overrides.</p>

<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case EnumName:                                                               \
    return #Name;
</div>
</dd>
</dl>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

### SYMBOL\_RECORD\_ALIAS {#a11f9ef2d1b54587ddeb3e53c450e75e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SYMBOL_RECORD_ALIAS(EnumName, EnumVal, Name, AliasName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symboldumper-cpp">SymbolDumper.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
