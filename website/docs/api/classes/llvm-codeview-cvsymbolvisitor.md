---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/cvsymbolvisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CVSymbolVisitor` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::codeview::CVSymbolVisitor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvsymbolvisitor-h">llvm/DebugInfo/CodeView/CVSymbolVisitor.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1707b6d4c21be859df78a07b89f12c5a">CVSymbolVisitor</a> (SymbolVisitorCallbacks &amp;Callbacks)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715b6cd253e266c828dbe77fcfd96670">visitSymbolRecord</a> (CVSymbol &amp;Record)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a237506610112c92d17def9b8833220dc">visitSymbolRecord</a> (CVSymbol &amp;Record, uint32_t Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace5661625caed8c5d8e8a7d062742576">visitSymbolStream</a> (const CVSymbolArray &amp;Symbols)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ad23d917b096777db5fc5911eb0fc13">visitSymbolStream</a> (const CVSymbolArray &amp;Symbols, uint32_t InitialOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386edc0742a93b59caac3efd31876012">visitSymbolStreamFiltered</a> (const CVSymbolArray &amp;Symbols, const FilterOptions &amp;Filter)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitorcallbacks">SymbolVisitorCallbacks</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38a7fab033d0dd65465086d5a5043498">Callbacks</a></td>
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


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvsymbolvisitor-h">CVSymbolVisitor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CVSymbolVisitor() {#a1707b6d4c21be859df78a07b89f12c5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CVSymbolVisitor::CVSymbolVisitor (<a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitorcallbacks">SymbolVisitorCallbacks</a> &amp; Callbacks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvsymbolvisitor-h">CVSymbolVisitor.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvsymbolvisitor-cpp">CVSymbolVisitor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visitSymbolRecord() {#a715b6cd253e266c828dbe77fcfd96670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CVSymbolVisitor::visitSymbolRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvsymbolvisitor-h">CVSymbolVisitor.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvsymbolvisitor-cpp">CVSymbolVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvsymbolvisitor-cpp/#a6087eb2848e529ac18b815211091ff27">finishVisitation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/cvsymboldumper/#a79198a9e094afc8f8ad976e74c266eca">llvm::codeview::CVSymbolDumper::dump</a>, <a href="#ace5661625caed8c5d8e8a7d062742576">visitSymbolStream</a>, <a href="#a7ad23d917b096777db5fc5911eb0fc13">visitSymbolStream</a> and <a href="#a386edc0742a93b59caac3efd31876012">visitSymbolStreamFiltered</a>.</p>

</div>
</div>

### visitSymbolRecord() {#a237506610112c92d17def9b8833220dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CVSymbolVisitor::visitSymbolRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, uint32_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvsymbolvisitor-h">CVSymbolVisitor.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvsymbolvisitor-cpp">CVSymbolVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvsymbolvisitor-cpp/#a6087eb2848e529ac18b815211091ff27">finishVisitation</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### visitSymbolStream() {#ace5661625caed8c5d8e8a7d062742576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CVSymbolVisitor::visitSymbolStream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a290687148df1bff1e309cd6af93dc035">CVSymbolArray</a> &amp; Symbols)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvsymbolvisitor-h">CVSymbolVisitor.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvsymbolvisitor-cpp">CVSymbolVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa5214a8a633c296d1d9d504fc54556692">llvm::codeview::Symbols</a> and <a href="#a715b6cd253e266c828dbe77fcfd96670">visitSymbolRecord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/cvsymboldumper/#a680879d065d4742893348286b11ebde6">llvm::codeview::CVSymbolDumper::dump</a> and <a href="#a386edc0742a93b59caac3efd31876012">visitSymbolStreamFiltered</a>.</p>

</div>
</div>

### visitSymbolStream() {#a7ad23d917b096777db5fc5911eb0fc13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CVSymbolVisitor::visitSymbolStream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a290687148df1bff1e309cd6af93dc035">CVSymbolArray</a> &amp; Symbols, uint32_t InitialOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvsymbolvisitor-h">CVSymbolVisitor.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvsymbolvisitor-cpp">CVSymbolVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa5214a8a633c296d1d9d504fc54556692">llvm::codeview::Symbols</a> and <a href="#a715b6cd253e266c828dbe77fcfd96670">visitSymbolRecord</a>.</p>

</div>
</div>

### visitSymbolStreamFiltered() {#a386edc0742a93b59caac3efd31876012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CVSymbolVisitor::visitSymbolStreamFiltered (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a290687148df1bff1e309cd6af93dc035">CVSymbolArray</a> &amp; Symbols, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/codeview/cvsymbolvisitor/filteroptions">FilterOptions</a> &amp; Filter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvsymbolvisitor-h">CVSymbolVisitor.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvsymbolvisitor-cpp">CVSymbolVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaee5189b9c4db9ad666a88abaf1ee0c4ad7778d0c64b6ba21494c97f77a66885a">llvm::Filter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a7eef7c2356ec9c0368019221027fb432">llvm::codeview::getScopeEndOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord/#aaeef9f2a2d0dc09ec00ec9b38242c706">llvm::codeview::CVRecord&lt; Kind &gt;::kind</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a68021fb1ffc174d48bce0deeb5671788">llvm::codeview::symbolEndsScope</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a921f65a0abb128eb4e94c61eb85a1748">llvm::codeview::symbolOpensScope</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa5214a8a633c296d1d9d504fc54556692">llvm::codeview::Symbols</a>, <a href="#a715b6cd253e266c828dbe77fcfd96670">visitSymbolRecord</a> and <a href="#ace5661625caed8c5d8e8a7d062742576">visitSymbolStream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Callbacks {#a38a7fab033d0dd65465086d5a5043498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolVisitorCallbacks&amp; llvm::codeview::CVSymbolVisitor::Callbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvsymbolvisitor-h">CVSymbolVisitor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/cvsymbolvisitor-h">CVSymbolVisitor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvsymbolvisitor-cpp">CVSymbolVisitor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
