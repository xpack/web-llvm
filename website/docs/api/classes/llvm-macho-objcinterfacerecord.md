---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/macho/objcinterfacerecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ObjCInterfaceRecord` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MachO::ObjCInterfaceRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">llvm/TextAPI/Record.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord">ObjCContainerRecord</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1befb918686e43e4e912988cdecf2dcb">ObjCInterfaceRecord</a> (StringRef Name, RecordLinkage Linkage, ObjCIFSymbolKind SymType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae71f5ed2a9562e07f5b3bc3bdb461057">hasExceptionAttribute</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1cf5360c874e093892820f08b6f6bcd">isCompleteInterface</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade45d422dc36ede4e2853f31bbe6a148">isExportedSymbol</a> (ObjCIFSymbolKind CurrType) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ff">RecordLinkage</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a075ab67a976138bc878809382714767f">getLinkageForSymbol</a> (ObjCIFSymbolKind CurrType) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b7e231ea214423c70c04c3e7ef46237">updateLinkageForSymbols</a> (ObjCIFSymbolKind SymType, RecordLinkage Link)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fa88d10d21b4df676199e49177e4b88">addObjCCategory</a> (ObjCCategoryRecord *Record)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/objccategoryrecord">ObjCCategoryRecord</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f90ae66430d870c8797faabc88fb4a7">getObjCCategories</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Linkages</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2737a195dcc6a8323b4e79ba0643282d">Linkages</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objccategoryrecord">ObjCCategoryRecord</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa30588e4901beefc4262a823b9dadce0">Categories</a></td>
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


<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ObjCInterfaceRecord() {#a1befb918686e43e4e912988cdecf2dcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::ObjCInterfaceRecord::ObjCInterfaceRecord (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ff">RecordLinkage</a> Linkage, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568">ObjCIFSymbolKind</a> SymType)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/macho/record/#ac617292ffd14e2658362629e552ac3a8">llvm::MachO::Record::Linkage</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/record/#ae1da3190ebbff030b4f205be49606ec6">llvm::MachO::Record::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord/#a97c5d891019f0f22072bf593df1545c0">llvm::MachO::ObjCContainerRecord::ObjCContainerRecord</a> and <a href="#a7b7e231ea214423c70c04c3e7ef46237">updateLinkageForSymbols</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addObjCCategory() {#a6fa88d10d21b4df676199e49177e4b88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjCInterfaceRecord::addObjCCategory (<a href="/web-llvm/docs/api/classes/llvm/macho/objccategoryrecord">ObjCCategoryRecord</a> * Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/macho/record/#ae1da3190ebbff030b4f205be49606ec6">llvm::MachO::Record::Name</a>.</p>

</div>
</div>

### getLinkageForSymbol() {#a075ab67a976138bc878809382714767f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordLinkage ObjCInterfaceRecord::getLinkageForSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568">ObjCIFSymbolKind</a> CurrType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568a9bd81329febf6efe22788e03ddeaf0af">llvm::MachO::Class</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568a963fa9a2037bb41f86948ebaea16e37e">llvm::MachO::EHType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568abf34b52bf0f0734db36974cfc4307440">llvm::MachO::MetaClass</a>.</p>


<p>Referenced by <a href="#ade45d422dc36ede4e2853f31bbe6a148">isExportedSymbol</a>.</p>

</div>
</div>

### getObjCCategories() {#a6f90ae66430d870c8797faabc88fb4a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; ObjCCategoryRecord * &gt; ObjCInterfaceRecord::getObjCCategories ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/symbolconverter/#a212640fcd49c76726374251900489631">llvm::MachO::SymbolConverter::visitObjCInterface</a>.</p>

</div>
</div>

### hasExceptionAttribute() {#ae71f5ed2a9562e07f5b3bc3bdb461057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::ObjCInterfaceRecord::hasExceptionAttribute ()</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::MachO::Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/symbolconverter/#a212640fcd49c76726374251900489631">llvm::MachO::SymbolConverter::visitObjCInterface</a>.</p>

</div>
</div>

### isCompleteInterface() {#aa1cf5360c874e093892820f08b6f6bcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::ObjCInterfaceRecord::isCompleteInterface ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffa6994917dfcfb9ef55fc6bce4b454f9a4">llvm::MachO::Rexported</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/symbolconverter/#a212640fcd49c76726374251900489631">llvm::MachO::SymbolConverter::visitObjCInterface</a>.</p>

</div>
</div>

### isExportedSymbol() {#ade45d422dc36ede4e2853f31bbe6a148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::ObjCInterfaceRecord::isExportedSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568">ObjCIFSymbolKind</a> CurrType)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="#a075ab67a976138bc878809382714767f">getLinkageForSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffa6994917dfcfb9ef55fc6bce4b454f9a4">llvm::MachO::Rexported</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/symbolconverter/#a212640fcd49c76726374251900489631">llvm::MachO::SymbolConverter::visitObjCInterface</a>.</p>

</div>
</div>

### updateLinkageForSymbols() {#a7b7e231ea214423c70c04c3e7ef46237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ObjCInterfaceRecord::updateLinkageForSymbols (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568">ObjCIFSymbolKind</a> SymType, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ff">RecordLinkage</a> Link)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568a9bd81329febf6efe22788e03ddeaf0af">llvm::MachO::Class</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568a963fa9a2037bb41f86948ebaea16e37e">llvm::MachO::EHType</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/record/#ac617292ffd14e2658362629e552ac3a8">llvm::MachO::Record::Linkage</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568abf34b52bf0f0734db36974cfc4307440">llvm::MachO::MetaClass</a>.</p>


<p>Referenced by <a href="#a1befb918686e43e4e912988cdecf2dcb">ObjCInterfaceRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Categories {#aa30588e4901beefc4262a823b9dadce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MapVector&lt;StringRef, ObjCCategoryRecord *&gt; llvm::MachO::ObjCInterfaceRecord::Categories</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>

</div>
</div>

### Linkages {#a2737a195dcc6a8323b4e79ba0643282d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Linkages llvm::MachO::ObjCInterfaceRecord::Linkages</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
