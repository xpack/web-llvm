---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/macho/recordsslice
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RecordsSlice` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MachO::RecordsSlice { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">llvm/TextAPI/RecordsSlice.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dd3100814ad41d4384a8850c3294c94">RecordsSlice</a> (const llvm::Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">llvm::Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9789af72a375a33a70bcb9c62b874101">getTriple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get target triple. <a href="#a9789af72a375a33a70bcb9c62b874101">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85770f74a870c0757d678eb649a3704f">getTarget</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get TAPI converted target. <a href="#a85770f74a870c0757d678eb649a3704f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/record">Record</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf4c3f66b71dd4779762f774c48d08cc">addRecord</a> (StringRef Name, SymbolFlags Flags, GlobalRecord::Kind GV=GlobalRecord::Kind::Unknown, RecordLinkage Linkage=RecordLinkage::Unknown)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add unspecified record to slice. <a href="#acf4c3f66b71dd4779762f774c48d08cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord">GlobalRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49a084971b8eafc4df71fb85b6f1fc71">addGlobal</a> (StringRef Name, RecordLinkage Linkage, GlobalRecord::Kind GV, SymbolFlags Flags=SymbolFlags::None, bool Inlined=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add non-ObjC global record. <a href="#a49a084971b8eafc4df71fb85b6f1fc71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord">ObjCInterfaceRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192cc227fd11ca3fb13be837ea294c0d">addObjCInterface</a> (StringRef Name, RecordLinkage Linkage, ObjCIFSymbolKind SymType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add ObjC Class record. <a href="#a192cc227fd11ca3fb13be837ea294c0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objcivarrecord">ObjCIVarRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41a1ad036885f6571a0b968e30c2b52f">addObjCIVar</a> (ObjCContainerRecord *Container, StringRef Name, RecordLinkage Linkage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add ObjC IVar record. <a href="#a41a1ad036885f6571a0b968e30c2b52f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objccategoryrecord">ObjCCategoryRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a191772ca6b6f82efc394a169110c8cc1">addObjCCategory</a> (StringRef ClassToExtend, StringRef Category)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add ObjC Category record. <a href="#a191772ca6b6f82efc394a169110c8cc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord">ObjCInterfaceRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a982260c34d9834df05612c79c319dea4">findObjCInterface</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find ObjC Class. <a href="#a982260c34d9834df05612c79c319dea4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objccategoryrecord">ObjCCategoryRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a610e5bcdea09f9e1c7c7fe44586ab7d0">findObjCCategory</a> (StringRef ClassToExtend, StringRef Category) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find ObjC Category. <a href="#a610e5bcdea09f9e1c7c7fe44586ab7d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord">ObjCContainerRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3842ff31470f2555d64c627ae05c7582">findContainer</a> (bool IsIVar, StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find ObjC Container. <a href="#a3842ff31470f2555d64c627ae05c7582">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objcivarrecord">ObjCIVarRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c99d02cd99463b4161265f0c6cb30fd">findObjCIVar</a> (bool IsScopedName, StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find ObjC instance variable. <a href="#a0c99d02cd99463b4161265f0c6cb30fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord">GlobalRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bbe48203c60ad199df294db71d6266b">findGlobal</a> (StringRef Name, GlobalRecord::Kind GV=GlobalRecord::Kind::Unknown) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find non-objc global. <a href="#a5bbe48203c60ad199df294db71d6266b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af50e5ef4a51a66714b533dbbaaa1a19d">hasBinaryAttrs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31669a7ff7d8567ad8ce6cce12f6c1b9">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addbce149fe455246f1ff315693940c00">visit</a> (RecordVisitor &amp;V) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs">BinaryAttrs</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74ab94fb41c9098a41670298fecc5e8c">getBinaryAttrs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return reference to <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs">BinaryAttrs</a>. <a href="#a74ab94fb41c9098a41670298fecc5e8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089b364aff9663d489cf5814eba29c96">copyString</a> (StringRef String)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Store any strings owned by RecordSlice into allocator and return back reference to that. <a href="#a089b364aff9663d489cf5814eba29c96">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad518b5e8a6fbac825c8ee6fa37af4974">updateLinkage</a> (Record *R, RecordLinkage L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Promote linkage of requested record. <a href="#ad518b5e8a6fbac825c8ee6fa37af4974">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c426f065f4442426da04ee819837ef">updateFlags</a> (Record *R, SymbolFlags F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update set flags of requested record. <a href="#af0c426f065f4442426da04ee819837ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">llvm::Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2a59d272d25657b4e0a7ba77c127a97">TargetTriple</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef72bb387d35e2707695cc3b16d60665">TAPITarget</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">llvm::BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b77bac4b5d5c56700c3adc936499b42">StringAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> to store generated/copied strings. <a href="#a2b77bac4b5d5c56700c3adc936499b42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa27d6e08de741442bc5cd6affed0cfc6">RecordMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord">GlobalRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a648ab82901d346207c45cf94269269e6">Globals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa27d6e08de741442bc5cd6affed0cfc6">RecordMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord">ObjCInterfaceRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a4df03d4506c86daf639161f68c238f">Classes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa27d6e08de741442bc5cd6affed0cfc6">RecordMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/objccategoryrecord">ObjCCategoryRecord</a>, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26a4057491ef3885b7827d119377a7e4">Categories</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs">BinaryAttrs</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9b0c5a8dfffd2f8f36bcf24d56c464a">BA</a> {nullptr}</td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RecordsSlice() {#a1dd3100814ad41d4384a8850c3294c94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::RecordsSlice::RecordsSlice (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">llvm::Triple</a> &amp; T)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addGlobal() {#a49a084971b8eafc4df71fb85b6f1fc71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalRecord * RecordsSlice::addGlobal (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ff">RecordLinkage</a> Linkage, <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#ae65893a6685a0b1e5dbcdf5b0169d143">GlobalRecord::Kind</a> GV, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a> Flags=<a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a6adf97f83acf6453d4a6a4b1070f3754">SymbolFlags::None</a>, bool Inlined=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add non-ObjC global record.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The name of symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Linkage</td>
<td class="doxyParamItemDescription"><p>The linkage of symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GV</td>
<td class="doxyParamItemDescription"><p>The kind of global.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>The flags that describe attributes of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inlined</td>
<td class="doxyParamItemDescription"><p>Whether declaration is inlined, only applicable to functions.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The non-owning pointer to added record in slice.</p></dd>
</dl>


<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>References <a href="#a089b364aff9663d489cf5814eba29c96">copyString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4af6068daa29dbb05a7ead1e3b5a48bbee">llvm::MachO::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#ae65893a6685a0b1e5dbcdf5b0169d143a86408593c34af77fdd90df932f8b5261">llvm::MachO::GlobalRecord::Function</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a9dffbf69ffba8bc38bc4e01abf4b1675">llvm::MachO::Text</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#ae65893a6685a0b1e5dbcdf5b0169d143a47c14840d8e15331fa420b9b2f757cd9">llvm::MachO::GlobalRecord::Variable</a>.</p>


<p>Referenced by <a href="#acf4c3f66b71dd4779762f774c48d08cc">addRecord</a>.</p>

</div>
</div>

### addObjCCategory() {#a191772ca6b6f82efc394a169110c8cc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjCCategoryRecord * RecordsSlice::addObjCCategory (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ClassToExtend, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Category)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add ObjC Category record.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ClassToExtend</td>
<td class="doxyParamItemDescription"><p>The name of class that is being extended by the category, not symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Category</td>
<td class="doxyParamItemDescription"><p>The name of category.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The non-owning pointer to added record in slice.</p></dd>
</dl>


<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>References <a href="#a089b364aff9663d489cf5814eba29c96">copyString</a> and <a href="#a982260c34d9834df05612c79c319dea4">findObjCInterface</a>.</p>


<p>Referenced by <a href="#acf4c3f66b71dd4779762f774c48d08cc">addRecord</a>.</p>

</div>
</div>

### addObjCInterface() {#a192cc227fd11ca3fb13be837ea294c0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjCInterfaceRecord * RecordsSlice::addObjCInterface (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ff">RecordLinkage</a> Linkage, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568">ObjCIFSymbolKind</a> SymType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add ObjC Class record.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The name of class, not symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Linkage</td>
<td class="doxyParamItemDescription"><p>The linkage of symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SymType</td>
<td class="doxyParamItemDescription"><p>The symbols this class represents.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The non-owning pointer to added record in slice.</p></dd>
</dl>


<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>Reference <a href="#a089b364aff9663d489cf5814eba29c96">copyString</a>.</p>


<p>Referenced by <a href="#acf4c3f66b71dd4779762f774c48d08cc">addRecord</a>.</p>

</div>
</div>

### addObjCIVar() {#a41a1ad036885f6571a0b968e30c2b52f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjCIVarRecord * RecordsSlice::addObjCIVar (<a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord">ObjCContainerRecord</a> * Container, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ff">RecordLinkage</a> Linkage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add ObjC IVar record.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Container</td>
<td class="doxyParamItemDescription"><p>Owning pointer for instance variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The name of ivar, not symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Linkage</td>
<td class="doxyParamItemDescription"><p>The linkage of symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The non-owning pointer to added record in slice.</p></dd>
</dl>


<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>, definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord/#a85376daae5640f771d4da0beeac835e9">llvm::MachO::ObjCContainerRecord::addObjCIVar</a> and <a href="#a089b364aff9663d489cf5814eba29c96">copyString</a>.</p>


<p>Referenced by <a href="#acf4c3f66b71dd4779762f774c48d08cc">addRecord</a>.</p>

</div>
</div>

### addRecord() {#acf4c3f66b71dd4779762f774c48d08cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Record * RecordsSlice::addRecord (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#ae65893a6685a0b1e5dbcdf5b0169d143">GlobalRecord::Kind</a> GV=<a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#ae65893a6685a0b1e5dbcdf5b0169d143a88183b946cc5f0e8c96b2e66e1c74a7e">GlobalRecord::Kind::Unknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ff">RecordLinkage</a> Linkage=<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffa88183b946cc5f0e8c96b2e66e1c74a7e">RecordLinkage::Unknown</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add unspecified record to slice.</p>


<p>Assign specific record type based on properties and symbol name.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The name of symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>The flags that describe attributes of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GV</td>
<td class="doxyParamItemDescription"><p>The kind of global, if this represents a non obj-c global symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Linkage</td>
<td class="doxyParamItemDescription"><p>The linkage of symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The non-owning pointer to added record in slice.</p></dd>
</dl>


<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>References <a href="#a49a084971b8eafc4df71fb85b6f1fc71">addGlobal</a>, <a href="#a191772ca6b6f82efc394a169110c8cc1">addObjCCategory</a>, <a href="#a192cc227fd11ca3fb13be837ea294c0d">addObjCInterface</a>, <a href="#a41a1ad036885f6571a0b968e30c2b52f">addObjCIVar</a>, <a href="#a3842ff31470f2555d64c627ae05c7582">findContainer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09adac49f2966d60d1973e56e22359e377e68">llvm::MachO::GlobalSymbol</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09adabadb331c797ea02208fed9025369cfb1">llvm::MachO::ObjectiveCClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ada54da6ac4046a5d0d1b4c31bc3dc43247">llvm::MachO::ObjectiveCClassEHType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ada305fbf91fddce55318beefeb7170a5af">llvm::MachO::ObjectiveCInstanceVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ab0d2fab5845ea5a11a1a57775090aec7">llvm::MachO::parseSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a97a89195303306e8a5bacadf960312a9">llvm::MachO::WeakDefined</a>.</p>

</div>
</div>

### copyString() {#a089b364aff9663d489cf5814eba29c96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef RecordsSlice::copyString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> String)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Store any strings owned by RecordSlice into allocator and return back reference to that.</p>

<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>


<p>Referenced by <a href="#a49a084971b8eafc4df71fb85b6f1fc71">addGlobal</a>, <a href="#a191772ca6b6f82efc394a169110c8cc1">addObjCCategory</a>, <a href="#a192cc227fd11ca3fb13be837ea294c0d">addObjCInterface</a> and <a href="#a41a1ad036885f6571a0b968e30c2b52f">addObjCIVar</a>.</p>

</div>
</div>

### empty() {#a31669a7ff7d8567ad8ce6cce12f6c1b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::RecordsSlice::empty ()</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>


<p>Reference <a href="#af50e5ef4a51a66714b533dbbaaa1a19d">hasBinaryAttrs</a>.</p>

</div>
</div>

### findContainer() {#a3842ff31470f2555d64c627ae05c7582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjCContainerRecord * RecordsSlice::findContainer (bool IsIVar, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find ObjC Container.</p>


<p>This is commonly used for assigning for looking up instance variables that are assigned to either a category or class.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsIVar</td>
<td class="doxyParamItemDescription"><p>If true, the name is the name of the IVar, otherwise it will be looked up as the name of the container.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Either the name of ivar or name of container.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The non-owning pointer to record in slice.</p></dd>
</dl>


<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>References <a href="#a610e5bcdea09f9e1c7c7fe44586ab7d0">findObjCCategory</a> and <a href="#a982260c34d9834df05612c79c319dea4">findObjCInterface</a>.</p>


<p>Referenced by <a href="#acf4c3f66b71dd4779762f774c48d08cc">addRecord</a> and <a href="#a0c99d02cd99463b4161265f0c6cb30fd">findObjCIVar</a>.</p>

</div>
</div>

### findGlobal() {#a5bbe48203c60ad199df294db71d6266b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalRecord * RecordsSlice::findGlobal (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#ae65893a6685a0b1e5dbcdf5b0169d143">GlobalRecord::Kind</a> GV=<a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#ae65893a6685a0b1e5dbcdf5b0169d143a88183b946cc5f0e8c96b2e66e1c74a7e">GlobalRecord::Kind::Unknown</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find non-objc global.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The name of symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GV</td>
<td class="doxyParamItemDescription"><p>The Kind of global to find.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The non-owning pointer to record in slice.</p></dd>
</dl>


<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp/#af60cd1eab7adb7cd85da1dfb85cbcf6e">findRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#ae65893a6685a0b1e5dbcdf5b0169d143a86408593c34af77fdd90df932f8b5261">llvm::MachO::GlobalRecord::Function</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#ae65893a6685a0b1e5dbcdf5b0169d143a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::MachO::GlobalRecord::Unknown</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#ae65893a6685a0b1e5dbcdf5b0169d143a47c14840d8e15331fa420b9b2f757cd9">llvm::MachO::GlobalRecord::Variable</a>.</p>

</div>
</div>

### findObjCCategory() {#a610e5bcdea09f9e1c7c7fe44586ab7d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjCCategoryRecord * RecordsSlice::findObjCCategory (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ClassToExtend, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Category)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find ObjC Category.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ClassToExtend</td>
<td class="doxyParamItemDescription"><p>The name of class, not full symbol name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Category</td>
<td class="doxyParamItemDescription"><p>The name of category.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The non-owning pointer to record in slice.</p></dd>
</dl>


<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp/#af60cd1eab7adb7cd85da1dfb85cbcf6e">findRecord</a>.</p>


<p>Referenced by <a href="#a3842ff31470f2555d64c627ae05c7582">findContainer</a>.</p>

</div>
</div>

### findObjCInterface() {#a982260c34d9834df05612c79c319dea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjCInterfaceRecord * RecordsSlice::findObjCInterface (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find ObjC Class.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>name of class, not full symbol name.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The non-owning pointer to record in slice.</p></dd>
</dl>


<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp/#af60cd1eab7adb7cd85da1dfb85cbcf6e">findRecord</a>.</p>


<p>Referenced by <a href="#a191772ca6b6f82efc394a169110c8cc1">addObjCCategory</a> and <a href="#a3842ff31470f2555d64c627ae05c7582">findContainer</a>.</p>

</div>
</div>

### findObjCIVar() {#a0c99d02cd99463b4161265f0c6cb30fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjCIVarRecord * RecordsSlice::findObjCIVar (bool IsScopedName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find ObjC instance variable.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsScopedName</td>
<td class="doxyParamItemDescription"><p>This is used to determine how to parse the name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Either the full name of the symbol or just the ivar.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The non-owning pointer to record in slice.</p></dd>
</dl>


<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a> and <a href="#a3842ff31470f2555d64c627ae05c7582">findContainer</a>.</p>

</div>
</div>

### getBinaryAttrs() {#a74ab94fb41c9098a41670298fecc5e8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordsSlice::BinaryAttrs &amp; RecordsSlice::getBinaryAttrs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return reference to <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs">BinaryAttrs</a>.</p>

<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>Reference <a href="#af50e5ef4a51a66714b533dbbaaa1a19d">hasBinaryAttrs</a>.</p>

</div>
</div>

### getTarget() {#a85770f74a870c0757d678eb649a3704f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Target &amp; llvm::MachO::RecordsSlice::getTarget ()</td>
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

<p>Get TAPI converted target.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>

</div>
</div>

### getTriple() {#a9789af72a375a33a70bcb9c62b874101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const llvm::Triple &amp; llvm::MachO::RecordsSlice::getTriple ()</td>
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

<p>Get target triple.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>

</div>
</div>

### hasBinaryAttrs() {#af50e5ef4a51a66714b533dbbaaa1a19d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::RecordsSlice::hasBinaryAttrs ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>


<p>Referenced by <a href="#a31669a7ff7d8567ad8ce6cce12f6c1b9">empty</a> and <a href="#a74ab94fb41c9098a41670298fecc5e8c">getBinaryAttrs</a>.</p>

</div>
</div>

### visit() {#addbce149fe455246f1ff315693940c00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RecordsSlice::visit (<a href="/web-llvm/docs/api/classes/llvm/macho/recordvisitor">RecordVisitor</a> &amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### updateFlags() {#af0c426f065f4442426da04ee819837ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::RecordsSlice::updateFlags (<a href="/web-llvm/docs/api/classes/llvm/macho/record">Record</a> * R, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a> F)</td>
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

<p>Update set flags of requested record.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">R</td>
<td class="doxyParamItemDescription"><p>The record to update.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p>Flags to update to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>

</div>
</div>

### updateLinkage() {#ad518b5e8a6fbac825c8ee6fa37af4974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::RecordsSlice::updateLinkage (<a href="/web-llvm/docs/api/classes/llvm/macho/record">Record</a> * R, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ff">RecordLinkage</a> L)</td>
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

<p>Promote linkage of requested record.</p>


<p>It is no-op if linkage type is lower than the current assignment.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">R</td>
<td class="doxyParamItemDescription"><p>The record to update.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">L</td>
<td class="doxyParamItemDescription"><p>Linkage type to update to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BA {#aa9b0c5a8dfffd2f8f36bcf24d56c464a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BinaryAttrs&gt; llvm::MachO::RecordsSlice::BA {nullptr}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>

</div>
</div>

### Categories {#a26a4057491ef3885b7827d119377a7e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordMap&lt;ObjCCategoryRecord, std::pair&lt;StringRef, StringRef&gt; &gt; llvm::MachO::RecordsSlice::Categories</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>

</div>
</div>

### Classes {#a7a4df03d4506c86daf639161f68c238f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordMap&lt;ObjCInterfaceRecord&gt; llvm::MachO::RecordsSlice::Classes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>

</div>
</div>

### Globals {#a648ab82901d346207c45cf94269269e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordMap&lt;GlobalRecord&gt; llvm::MachO::RecordsSlice::Globals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>

</div>
</div>

### StringAllocator {#a2b77bac4b5d5c56700c3adc936499b42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BumpPtrAllocator llvm::MachO::RecordsSlice::StringAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> to store generated/copied strings.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>

</div>
</div>

### TAPITarget {#aef72bb387d35e2707695cc3b16d60665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Target llvm::MachO::RecordsSlice::TAPITarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>

</div>
</div>

### TargetTriple {#aa2a59d272d25657b4e0a7ba77c127a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const llvm::Triple llvm::MachO::RecordsSlice::TargetTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">RecordsSlice.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
