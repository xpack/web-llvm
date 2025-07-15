---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/objcopy/macho/symbolentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SymbolEntry` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::objcopy::macho::SymbolEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">ObjCopy/MachO/MachOObject.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9d81f91808f0ffb9f2bd3e9af630c1">isExternalSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab176a3748dabf874adb1d06deaf8ee2f">isLocalSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a63a1935a2580819745fcbbfbe5aab4">isUndefinedSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d7d7d589ddcfe74ece7aee10d38ba5d">isSwiftSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f5d77ab4ce77924f8d8ed6b2b08371">section</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a614b7cc8bdf811b60786c0dba3214906">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4be78edc14431bea745a92fd6f25c1d2">Referenced</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eabc798ce35f96b9616b355e23b1f34">Index</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05de774a480bbfc1c398d279bbc85965">n_type</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f5e6f40870c2d8f759bfaa9893e134">n_sect</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad93a3bb12765133a3ec10e11d7916657">n_desc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa91e6d5d585bde132f3a3af577b6d3a5">n_value</a></td>
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


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### isExternalSymbol() {#a0c9d81f91808f0ffb9f2bd3e9af630c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::macho::SymbolEntry::isExternalSymbol ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11a8bc1bbfcee7206480576072973724a1a">llvm::MachO::N_EXT</a> and <a href="#a05de774a480bbfc1c398d279bbc85965">n_type</a>.</p>


<p>Referenced by <a href="#ab176a3748dabf874adb1d06deaf8ee2f">isLocalSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#af77b232892df5c7e1321f2885b0c49ef">updateAndRemoveSymbols</a>.</p>

</div>
</div>

### isLocalSymbol() {#ab176a3748dabf874adb1d06deaf8ee2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::macho::SymbolEntry::isLocalSymbol ()</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>


<p>Reference <a href="#a0c9d81f91808f0ffb9f2bd3e9af630c1">isExternalSymbol</a>.</p>

</div>
</div>

### isSwiftSymbol() {#a4d7d7d589ddcfe74ece7aee10d38ba5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::macho::SymbolEntry::isSwiftSymbol ()</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>


<p>References <a href="#a614b7cc8bdf811b60786c0dba3214906">Name</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>

</div>
</div>

### isUndefinedSymbol() {#a3a63a1935a2580819745fcbbfbe5aab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::macho::SymbolEntry::isUndefinedSymbol ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11a6d2d703f3e79b6904f129d79b5915e7e">llvm::MachO::N_TYPE</a>, <a href="#a05de774a480bbfc1c398d279bbc85965">n_type</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227edac444d073d7dfae9ee37913c3ebc18fa9">llvm::MachO::N_UNDF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#af77b232892df5c7e1321f2885b0c49ef">updateAndRemoveSymbols</a>.</p>

</div>
</div>

### section() {#a33f5d77ab4ce77924f8d8ed6b2b08371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; llvm::objcopy::macho::SymbolEntry::section ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>


<p>References <a href="#a74f5e6f40870c2d8f759bfaa9893e134">n_sect</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3fe4514c83ad4544e3e72db2d9fc33a4a840723dd9839c1d65c8728aa31ee6b08">llvm::MachO::NO_SECT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Index {#a6eabc798ce35f96b9616b355e23b1f34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::objcopy::macho::SymbolEntry::Index</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>

</div>
</div>

### n\_desc {#ad93a3bb12765133a3ec10e11d7916657}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::objcopy::macho::SymbolEntry::n_desc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#afc82faca788f75fcf0a8f60a406342ba">constructSymbolEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#af77b232892df5c7e1321f2885b0c49ef">updateAndRemoveSymbols</a> and <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp/#afb198633cab14d4e8eb44bbcbfae5cde">writeNListEntry</a>.</p>

</div>
</div>

### n\_sect {#a74f5e6f40870c2d8f759bfaa9893e134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::objcopy::macho::SymbolEntry::n_sect</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#afc82faca788f75fcf0a8f60a406342ba">constructSymbolEntry</a>, <a href="#a33f5d77ab4ce77924f8d8ed6b2b08371">section</a> and <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp/#afb198633cab14d4e8eb44bbcbfae5cde">writeNListEntry</a>.</p>

</div>
</div>

### n\_type {#a05de774a480bbfc1c398d279bbc85965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::objcopy::macho::SymbolEntry::n_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#afc82faca788f75fcf0a8f60a406342ba">constructSymbolEntry</a>, <a href="#a0c9d81f91808f0ffb9f2bd3e9af630c1">isExternalSymbol</a>, <a href="#a3a63a1935a2580819745fcbbfbe5aab4">isUndefinedSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#af77b232892df5c7e1321f2885b0c49ef">updateAndRemoveSymbols</a> and <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp/#afb198633cab14d4e8eb44bbcbfae5cde">writeNListEntry</a>.</p>

</div>
</div>

### n\_value {#aa91e6d5d585bde132f3a3af577b6d3a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::objcopy::macho::SymbolEntry::n_value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#afc82faca788f75fcf0a8f60a406342ba">constructSymbolEntry</a> and <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp/#afb198633cab14d4e8eb44bbcbfae5cde">writeNListEntry</a>.</p>

</div>
</div>

### Name {#a614b7cc8bdf811b60786c0dba3214906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::objcopy::macho::SymbolEntry::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#afc82faca788f75fcf0a8f60a406342ba">constructSymbolEntry</a>, <a href="#a4d7d7d589ddcfe74ece7aee10d38ba5d">isSwiftSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#af77b232892df5c7e1321f2885b0c49ef">updateAndRemoveSymbols</a>.</p>

</div>
</div>

### Referenced {#a4be78edc14431bea745a92fd6f25c1d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::macho::SymbolEntry::Referenced = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
