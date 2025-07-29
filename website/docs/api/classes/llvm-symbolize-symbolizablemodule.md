---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/symbolize/symbolizablemodule
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SymbolizableModule` Class



## Declaration

<div class="doxyDeclaration">
class llvm::symbolize::SymbolizableModule { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizablemodule-h">llvm/DebugInfo/Symbolize/SymbolizableModule.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile">SymbolizableObjectFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a775dc29a9cb514ab8d5d5a36790418d8">~SymbolizableModule</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0df591a28de39acf88be35b30c5e9ea">symbolizeCode</a> (object::SectionedAddress ModuleOffset, DILineInfoSpecifier LineInfoSpecifier, bool UseSymbolTable) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2742620673b604aa4a483063980d1be7">symbolizeInlinedCode</a> (object::SectionedAddress ModuleOffset, DILineInfoSpecifier LineInfoSpecifier, bool UseSymbolTable) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2136fbc00c2f6d6e9705fe559ed9b3bd">symbolizeData</a> (object::SectionedAddress ModuleOffset) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf21584680a074e03bf21ccc8bb9c832">symbolizeFrame</a> (object::SectionedAddress ModuleOffset) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477f4941b5216c4dcb6c0b130903d32b">findSymbol</a> (StringRef Symbol, uint64_t Offset) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89baf7e7fedad506270275e18daf866c">isWin32Module</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cbdd3745472d00526ff5b0ffab667f1">getModulePreferredBase</a> () const =0</td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizablemodule-h">SymbolizableModule.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~SymbolizableModule() {#a775dc29a9cb514ab8d5d5a36790418d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::symbolize::SymbolizableModule::~SymbolizableModule ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizablemodule-h">SymbolizableModule.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### findSymbol() {#a477f4941b5216c4dcb6c0b130903d32b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::vector&lt; object::SectionedAddress &gt; llvm::symbolize::SymbolizableModule::findSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Symbol, uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizablemodule-h">SymbolizableModule.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getModulePreferredBase() {#a7cbdd3745472d00526ff5b0ffab667f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::symbolize::SymbolizableModule::getModulePreferredBase ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizablemodule-h">SymbolizableModule.h</a>.</p>

</div>
</div>

### isWin32Module() {#a89baf7e7fedad506270275e18daf866c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::symbolize::SymbolizableModule::isWin32Module ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizablemodule-h">SymbolizableModule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/symbolize/llvmsymbolizer/#a06a25cb56878fe4f0431c046d1a67fcf">llvm::symbolize::LLVMSymbolizer::DemangleName</a>.</p>

</div>
</div>

### symbolizeCode() {#af0df591a28de39acf88be35b30c5e9ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual DILineInfo llvm::symbolize::SymbolizableModule::symbolizeCode (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier">DILineInfoSpecifier</a> LineInfoSpecifier, bool UseSymbolTable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizablemodule-h">SymbolizableModule.h</a>.</p>

</div>
</div>

### symbolizeData() {#a2136fbc00c2f6d6e9705fe559ed9b3bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual DIGlobal llvm::symbolize::SymbolizableModule::symbolizeData (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizablemodule-h">SymbolizableModule.h</a>.</p>

</div>
</div>

### symbolizeFrame() {#aaf21584680a074e03bf21ccc8bb9c832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::vector&lt; DILocal &gt; llvm::symbolize::SymbolizableModule::symbolizeFrame (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizablemodule-h">SymbolizableModule.h</a>.</p>

</div>
</div>

### symbolizeInlinedCode() {#a2742620673b604aa4a483063980d1be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual DIInliningInfo llvm::symbolize::SymbolizableModule::symbolizeInlinedCode (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> ModuleOffset, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier">DILineInfoSpecifier</a> LineInfoSpecifier, bool UseSymbolTable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizablemodule-h">SymbolizableModule.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/symbolizablemodule-h">SymbolizableModule.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
