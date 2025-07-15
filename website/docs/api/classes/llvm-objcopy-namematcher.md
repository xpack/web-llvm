---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcopy/namematcher
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `NameMatcher` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::objcopy::NameMatcher { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">llvm/ObjCopy/CommonConfig.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec79fe06f3234497d78f290c50389b2f">addMatcher</a> (Expected&lt; NameOrPattern &gt; Matcher)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fe6d6e80304c85e35c03066ae1bcfa9">matches</a> (StringRef S) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae37fd1e51553e31998f280b07d853e77">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cachedhashstringref">CachedHashStringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e9b32552bce0176c499a278ca0522e8">PosNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/objcopy/nameorpattern">NameOrPattern</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a902ac4d1fbf55f2f8122a61254d401c9">PosPatterns</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/objcopy/nameorpattern">NameOrPattern</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab64a26e74ce6ac281dbca136108dea8b">NegMatchers</a></td>
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


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### addMatcher() {#aec79fe06f3234497d78f290c50389b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::objcopy::NameMatcher::addMatcher (<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/objcopy/nameorpattern">NameOrPattern</a> &gt; Matcher)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### empty() {#ae37fd1e51553e31998f280b07d853e77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::NameMatcher::empty ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#aaa859579ac4adb9cbcebf0ddc98a085b">llvm::objcopy::coff::handleArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a128c16fdb808e0e243d89ae57ed3717d">llvm::objcopy::wasm::removeSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#a918836be9d98b9555fa33b3153155511">removeSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a0caf08c068a9900ddcabffcf9f004b41">replaceAndRemoveSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a4a8b0267a862203c3082ed955abd326c">updateAndRemoveSymbols</a> and <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#af77b232892df5c7e1321f2885b0c49ef">updateAndRemoveSymbols</a>.</p>

</div>
</div>

### matches() {#a8fe6d6e80304c85e35c03066ae1bcfa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::NameMatcher::matches (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#aaa859579ac4adb9cbcebf0ddc98a085b">llvm::objcopy::coff::handleArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a128c16fdb808e0e243d89ae57ed3717d">llvm::objcopy::wasm::removeSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#a918836be9d98b9555fa33b3153155511">removeSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a0caf08c068a9900ddcabffcf9f004b41">replaceAndRemoveSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a4a8b0267a862203c3082ed955abd326c">updateAndRemoveSymbols</a> and <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#af77b232892df5c7e1321f2885b0c49ef">updateAndRemoveSymbols</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NegMatchers {#ab64a26e74ce6ac281dbca136108dea8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;NameOrPattern, 0&gt; llvm::objcopy::NameMatcher::NegMatchers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a>.</p>

</div>
</div>

### PosNames {#a5e9b32552bce0176c499a278ca0522e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;CachedHashStringRef&gt; llvm::objcopy::NameMatcher::PosNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a>.</p>

</div>
</div>

### PosPatterns {#a902ac4d1fbf55f2f8122a61254d401c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;NameOrPattern, 0&gt; llvm::objcopy::NameMatcher::PosPatterns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">CommonConfig.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
