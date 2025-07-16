---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/objcopy/newsectioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `NewSectionInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::objcopy::NewSectionInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">llvm/ObjCopy/CommonConfig.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c6195dcd3d0a75cb9d2722f299c4db5">NewSectionInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ea180bdd685838ea592c839a304eaed">NewSectionInfo</a> (StringRef Name, std::unique_ptr&lt; MemoryBuffer &gt; &amp;&amp;Buffer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05c34cfa6560e1e8b1aa9a540d5505e3">SectionName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a641257caac84236fba46e30aa91f6c7a">SectionData</a></td>
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


<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NewSectionInfo() {#a8c6195dcd3d0a75cb9d2722f299c4db5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcopy::NewSectionInfo::NewSectionInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a>.</p>

</div>
</div>

### NewSectionInfo() {#a8ea180bdd685838ea592c839a304eaed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcopy::NewSectionInfo::NewSectionInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &amp;&amp; Buffer)</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a641257caac84236fba46e30aa91f6c7a">SectionData</a> and <a href="#a05c34cfa6560e1e8b1aa9a540d5505e3">SectionName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### SectionData {#a641257caac84236fba46e30aa91f6c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;MemoryBuffer&gt; llvm::objcopy::NewSectionInfo::SectionData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#aa6138676e4615546fc1c7d559029916a">addSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#aaa859579ac4adb9cbcebf0ddc98a085b">llvm::objcopy::coff::handleArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a42dbc5cc7c04f8d8738edf9699d75654">llvm::objcopy::wasm::handleArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a4454edff33cc45fad3f75d835f91cb37">handleUserSection</a>, <a href="#a8ea180bdd685838ea592c839a304eaed">NewSectionInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#afcfed892d87764504587749693efe357">updateSection</a>.</p>

</div>
</div>

### SectionName {#a05c34cfa6560e1e8b1aa9a540d5505e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::objcopy::NewSectionInfo::SectionName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#aa6138676e4615546fc1c7d559029916a">addSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#a8fdf1b59602b3fa2d23286e468abb8a9">handleArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#aaa859579ac4adb9cbcebf0ddc98a085b">llvm::objcopy::coff::handleArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a42dbc5cc7c04f8d8738edf9699d75654">llvm::objcopy::wasm::handleArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a4454edff33cc45fad3f75d835f91cb37">handleUserSection</a>, <a href="#a8ea180bdd685838ea592c839a304eaed">NewSectionInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#afcfed892d87764504587749693efe357">updateSection</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
