---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/macho/symbolconverter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SymbolConverter` Class

<p>Specialized <a href="/web-llvm/docs/api/classes/llvm/macho/recordvisitor">RecordVisitor</a> for collecting exported symbols and undefined symbols if RecordSlice being visited represents a flat-namespaced library. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachO::SymbolConverter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordvisitor-h">llvm/TextAPI/RecordVisitor.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/recordvisitor">RecordVisitor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for any usage of traversing over collected <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ab5b5510db9083f228e5929bf5ad0f717">Records</a>. <a href="/web-llvm/docs/api/classes/llvm/macho/recordvisitor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4abeb7cd0f05ef5dd33e10bdf2d28a6">SymbolConverter</a> (SymbolSet *Symbols, const Target &amp;T, const bool RecordUndefs=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3e40f86314ef9875bfd12cd2eab9b5e">visitGlobal</a> (const GlobalRecord &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a212640fcd49c76726374251900489631">visitObjCInterface</a> (const ObjCInterfaceRecord &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4821f93278208c868cd078fb8afc2746">visitObjCCategory</a> (const ObjCCategoryRecord &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe01894129a603b1aab9b1b720255f21">addIVars</a> (const ArrayRef&lt; ObjCIVarRecord * &gt;, StringRef ContainerName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/symbolset">SymbolSet</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad44b917e7b01e5335e212ac91665b759">Symbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28f99e08ccc55e7524f66b4b2fd2f16e">Targ</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787214b8a9ad16391fecce3c441f1e5f">RecordUndefs</a></td>
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

<p>Specialized <a href="/web-llvm/docs/api/classes/llvm/macho/recordvisitor">RecordVisitor</a> for collecting exported symbols and undefined symbols if RecordSlice being visited represents a flat-namespaced library.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordvisitor-h">RecordVisitor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SymbolConverter() {#ab4abeb7cd0f05ef5dd33e10bdf2d28a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::SymbolConverter::SymbolConverter (<a href="/web-llvm/docs/api/classes/llvm/macho/symbolset">SymbolSet</a> * Symbols, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool RecordUndefs=false)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordvisitor-h">RecordVisitor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visitGlobal() {#ab3e40f86314ef9875bfd12cd2eab9b5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SymbolConverter::visitGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord">GlobalRecord</a> &amp; GR)</td>
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



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordvisitor-h">RecordVisitor.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordvisitor-cpp">RecordVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/macho/record/#a671acbd063953da6403ccbd2fa35c349">llvm::MachO::Record::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/record/#a275e8a5b9303c59fe00b7eecd1066f6b">llvm::MachO::Record::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09adac49f2966d60d1973e56e22359e377e68">llvm::MachO::GlobalSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568a6adf97f83acf6453d4a6a4b1070f3754">llvm::MachO::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ab0d2fab5845ea5a11a1a57775090aec7">llvm::MachO::parseSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordvisitor-cpp/#ae3a5eb6c0d506b5dbfcca9497dea8d84">shouldSkipRecord</a>.</p>

</div>
</div>

### visitObjCCategory() {#a4821f93278208c868cd078fb8afc2746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SymbolConverter::visitObjCCategory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/objccategoryrecord">ObjCCategoryRecord</a> &amp; Cat)</td>
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



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordvisitor-h">RecordVisitor.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordvisitor-cpp">RecordVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord/#ae884774726774b58b46eef58effa5ac1">llvm::MachO::ObjCContainerRecord::getObjCIVars</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/objccategoryrecord/#ab882a886d176a5ce72b39c822deffff1">llvm::MachO::ObjCCategoryRecord::getSuperClassName</a>.</p>

</div>
</div>

### visitObjCInterface() {#a212640fcd49c76726374251900489631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SymbolConverter::visitObjCInterface (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord">ObjCInterfaceRecord</a> &amp; ObjCR)</td>
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



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordvisitor-h">RecordVisitor.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordvisitor-cpp">RecordVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568a9bd81329febf6efe22788e03ddeaf0af">llvm::MachO::Class</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568a963fa9a2037bb41f86948ebaea16e37e">llvm::MachO::EHType</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/record/#a671acbd063953da6403ccbd2fa35c349">llvm::MachO::Record::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/record/#a275e8a5b9303c59fe00b7eecd1066f6b">llvm::MachO::Record::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord/#a6f90ae66430d870c8797faabc88fb4a7">llvm::MachO::ObjCInterfaceRecord::getObjCCategories</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord/#ae884774726774b58b46eef58effa5ac1">llvm::MachO::ObjCContainerRecord::getObjCIVars</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09adac49f2966d60d1973e56e22359e377e68">llvm::MachO::GlobalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord/#ae71f5ed2a9562e07f5b3bc3bdb461057">llvm::MachO::ObjCInterfaceRecord::hasExceptionAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord/#aa1cf5360c874e093892820f08b6f6bcd">llvm::MachO::ObjCInterfaceRecord::isCompleteInterface</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord/#ade45d422dc36ede4e2853f31bbe6a148">llvm::MachO::ObjCInterfaceRecord::isExportedSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568abf34b52bf0f0734db36974cfc4307440">llvm::MachO::MetaClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48d87ec7a8852d05f1ea472e72072786">llvm::MachO::ObjC2ClassNamePrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aec5334f8d61fd44732dd28881a68e889">llvm::MachO::ObjC2EHTypePrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abe38e21d7038427b4c2c5eca693ebbcf">llvm::MachO::ObjC2MetaClassNamePrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09adabadb331c797ea02208fed9025369cfb1">llvm::MachO::ObjectiveCClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ada54da6ac4046a5d0d1b4c31bc3dc43247">llvm::MachO::ObjectiveCClassEHType</a> and <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordvisitor-cpp/#ae3a5eb6c0d506b5dbfcca9497dea8d84">shouldSkipRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addIVars() {#abe01894129a603b1aab9b1b720255f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SymbolConverter::addIVars (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/objcivarrecord">ObjCIVarRecord</a> * &gt; IVars, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ContainerName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordvisitor-h">RecordVisitor.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordvisitor-cpp">RecordVisitor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### RecordUndefs {#a787214b8a9ad16391fecce3c441f1e5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::MachO::SymbolConverter::RecordUndefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordvisitor-h">RecordVisitor.h</a>.</p>

</div>
</div>

### Symbols {#ad44b917e7b01e5335e212ac91665b759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolSet* llvm::MachO::SymbolConverter::Symbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordvisitor-h">RecordVisitor.h</a>.</p>

</div>
</div>

### Targ {#a28f99e08ccc55e7524f66b4b2fd2f16e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Target llvm::MachO::SymbolConverter::Targ</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordvisitor-h">RecordVisitor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordvisitor-h">RecordVisitor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/textapi/recordvisitor-cpp">RecordVisitor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
