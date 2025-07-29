---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcopy/macho/macholayoutbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachOLayoutBuilder` Class



## Declaration

<div class="doxyDeclaration">
class llvm::objcopy::macho::MachOLayoutBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">ObjCopy/MachO/MachOLayoutBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e92ee4dbc0fbde6eaa0ae4873a5c268">MachOLayoutBuilder</a> (Object &amp;O, bool Is64Bit, StringRef OutputFileName, uint64_t PageSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa37399d000904e315ba0bf8386d930e3">layout</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c388776743ad93302585b2cb45d3965">getStringTableBuilder</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/codesignatureinfo">CodeSignatureInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f1b8bf3f66661199d22cd47ee363c8">getCodeSignature</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa17e1db18d7f64979851ee66524fa227">computeSizeOfCmds</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e199d538d27f64051ce13d68e5ec7f1">constructStringTable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5778d3121906ebe6d2d43e84e3ba707e">updateSymbolIndexes</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaf2bad9f105edb363177410929b3495">updateDySymTab</a> (MachO::macho_load_command &amp;MLC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad826618a128c4ede1f574b3809932bbc">layoutSegments</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1a59527cc7490dfb6133b8d79149a0">layoutRelocations</a> (uint64_t Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a013d20f1a1d37128fe2eb9110d195ae0">layoutTail</a> (uint64_t Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb0556f47b3d3548f1110780c09fe3ed">O</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a811dee3a339abdf7cbdf7b288cf7ee83">Is64Bit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a289032890a8a945065bddcf86272469d">OutputFileName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5bb322280680815bcc6363237f3d605">PageSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/codesignatureinfo">CodeSignatureInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a378c74677cc42a0519b08f62880be8e1">CodeSignature</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/macho/macho-load-command">MachO::macho_load_command</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad327427f0e7060d287f0f5c6e894e76a">LinkEditLoadCommand</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab2b15a9cef9394c12723f2edc407331">StrTableBuilder</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a58c8b5f09afd8827aed05c9a1804e73a">StringTableBuilder::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e9e11a2946d3d5f9e54a6a7d6b05076">getStringTableBuilderKind</a> (const Object &amp;O, bool Is64Bit)</td>
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


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachOLayoutBuilder() {#a8e92ee4dbc0fbde6eaa0ae4873a5c268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcopy::macho::MachOLayoutBuilder::MachOLayoutBuilder (<a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp; O, bool Is64Bit, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OutputFileName, uint64_t PageSize)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCodeSignature() {#a54f1b8bf3f66661199d22cd47ee363c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CodeSignatureInfo &amp; llvm::objcopy::macho::MachOLayoutBuilder::getCodeSignature ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>.</p>

</div>
</div>

### getStringTableBuilder() {#a0c388776743ad93302585b2cb45d3965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder &amp; llvm::objcopy::macho::MachOLayoutBuilder::getStringTableBuilder ()</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>.</p>

</div>
</div>

### layout() {#aa37399d000904e315ba0bf8386d930e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MachOLayoutBuilder::layout ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>, definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-cpp">MachOLayoutBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeSizeOfCmds() {#aa17e1db18d7f64979851ee66524fa227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MachOLayoutBuilder::computeSizeOfCmds ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-cpp">MachOLayoutBuilder.cpp</a>.</p>

</div>
</div>

### constructStringTable() {#a9e199d538d27f64051ce13d68e5ec7f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOLayoutBuilder::constructStringTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-cpp">MachOLayoutBuilder.cpp</a>.</p>

</div>
</div>

### layoutRelocations() {#a2e1a59527cc7490dfb6133b8d79149a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOLayoutBuilder::layoutRelocations (uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-cpp">MachOLayoutBuilder.cpp</a>.</p>

</div>
</div>

### layoutSegments() {#ad826618a128c4ede1f574b3809932bbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOLayoutBuilder::layoutSegments ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-cpp">MachOLayoutBuilder.cpp</a>.</p>

</div>
</div>

### layoutTail() {#a013d20f1a1d37128fe2eb9110d195ae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MachOLayoutBuilder::layoutTail (uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-cpp">MachOLayoutBuilder.cpp</a>.</p>

</div>
</div>

### updateDySymTab() {#abaf2bad9f105edb363177410929b3495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOLayoutBuilder::updateDySymTab (<a href="/web-llvm/docs/api/unions/llvm/macho/macho-load-command">MachO::macho_load_command</a> &amp; MLC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-cpp">MachOLayoutBuilder.cpp</a>.</p>

</div>
</div>

### updateSymbolIndexes() {#a5778d3121906ebe6d2d43e84e3ba707e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOLayoutBuilder::updateSymbolIndexes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-cpp">MachOLayoutBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CodeSignature {#a378c74677cc42a0519b08f62880be8e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeSignatureInfo llvm::objcopy::macho::MachOLayoutBuilder::CodeSignature</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>.</p>

</div>
</div>

### Is64Bit {#a811dee3a339abdf7cbdf7b288cf7ee83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::macho::MachOLayoutBuilder::Is64Bit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>.</p>

</div>
</div>

### LinkEditLoadCommand {#ad327427f0e7060d287f0f5c6e894e76a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::macho_load_command* llvm::objcopy::macho::MachOLayoutBuilder::LinkEditLoadCommand = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>.</p>

</div>
</div>

### O {#adb0556f47b3d3548f1110780c09fe3ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Object&amp; llvm::objcopy::macho::MachOLayoutBuilder::O</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>.</p>

</div>
</div>

### OutputFileName {#a289032890a8a945065bddcf86272469d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::objcopy::macho::MachOLayoutBuilder::OutputFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>.</p>

</div>
</div>

### PageSize {#aa5bb322280680815bcc6363237f3d605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::objcopy::macho::MachOLayoutBuilder::PageSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>.</p>

</div>
</div>

### StrTableBuilder {#aab2b15a9cef9394c12723f2edc407331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder llvm::objcopy::macho::MachOLayoutBuilder::StrTableBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getStringTableBuilderKind() {#a1e9e11a2946d3d5f9e54a6a7d6b05076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder::Kind MachOLayoutBuilder::getStringTableBuilderKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp; O, bool Is64Bit)</td>
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



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-cpp">MachOLayoutBuilder.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-cpp">MachOLayoutBuilder.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
