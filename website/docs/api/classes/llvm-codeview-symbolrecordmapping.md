---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/symbolrecordmapping
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SymbolRecordMapping` Class



## Declaration

<div class="doxyDeclaration">
class llvm::codeview::SymbolRecordMapping { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecordmapping-h">llvm/DebugInfo/CodeView/SymbolRecordMapping.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a928e32985d3e0ee127c5e82d1ee19ab8">SymbolRecordMapping</a> (BinaryStreamReader &amp;Reader, CodeViewContainer Container)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa398ff8e2a21fa10471c0fbac024c4ac">SymbolRecordMapping</a> (BinaryStreamWriter &amp;Writer, CodeViewContainer Container)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac071b7f9eb995f4bbc5adde6f938b536">visitSymbolBegin</a> (CVSymbol &amp;Record) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aae7efbe35d635a423c6459f25f5a04">visitSymbolEnd</a> (CVSymbol &amp;Record) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac3fd578f133e7ee0210c835b393bca59">SymbolKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2e056a5d828b66ea43f7a0d96c7bc69">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio">CodeViewRecordIO</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e40fc0ca347a95119ecd33862af96bb">IO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af483a6f5695bfa37be36c56ad2f175b6">CodeViewContainer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ee74ce9836e077a3199d19b3484003f">Container</a></td>
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


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecordmapping-h">SymbolRecordMapping.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SymbolRecordMapping() {#a928e32985d3e0ee127c5e82d1ee19ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::SymbolRecordMapping::SymbolRecordMapping (<a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &amp; Reader, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af483a6f5695bfa37be36c56ad2f175b6">CodeViewContainer</a> Container)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecordmapping-h">SymbolRecordMapping.h</a>.</p>

</div>
</div>

### SymbolRecordMapping() {#aa398ff8e2a21fa10471c0fbac024c4ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::SymbolRecordMapping::SymbolRecordMapping (<a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter">BinaryStreamWriter</a> &amp; Writer, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af483a6f5695bfa37be36c56ad2f175b6">CodeViewContainer</a> Container)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecordmapping-h">SymbolRecordMapping.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visitSymbolBegin() {#ac071b7f9eb995f4bbc5adde6f938b536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SymbolRecordMapping::visitSymbolBegin (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record)</td>
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



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecordmapping-h">SymbolRecordMapping.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp">SymbolRecordMapping.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a77953260dd85922d9583bf426f89787aa30d8ae376cd42fd999ac8713cf85be2e">llvm::codeview::MaxRecordLength</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad540067d5e143dbc9d0a957b4b28968f">llvm::codeview::getSymbolName</a>.</p>

</div>
</div>

### visitSymbolEnd() {#a1aae7efbe35d635a423c6459f25f5a04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SymbolRecordMapping::visitSymbolEnd (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record)</td>
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



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecordmapping-h">SymbolRecordMapping.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp">SymbolRecordMapping.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a721643c85bdb4bbdc0ec6d04cc5770fe">llvm::codeview::alignOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad540067d5e143dbc9d0a957b4b28968f">llvm::codeview::getSymbolName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Container {#a1ee74ce9836e077a3199d19b3484003f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeViewContainer llvm::codeview::SymbolRecordMapping::Container</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecordmapping-h">SymbolRecordMapping.h</a>.</p>

</div>
</div>

### IO {#a3e40fc0ca347a95119ecd33862af96bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeViewRecordIO llvm::codeview::SymbolRecordMapping::IO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecordmapping-h">SymbolRecordMapping.h</a>.</p>

</div>
</div>

### Kind {#ad2e056a5d828b66ea43f7a0d96c7bc69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;SymbolKind&gt; llvm::codeview::SymbolRecordMapping::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecordmapping-h">SymbolRecordMapping.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecordmapping-h">SymbolRecordMapping.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp">SymbolRecordMapping.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
