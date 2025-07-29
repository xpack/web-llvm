---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/symboladdressmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SymbolAddressMap` Class

<p>A map of addresses to Symbols. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::SymbolAddressMap { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">llvm/ExecutionEngine/JITLink/JITLink.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb0262d7e29d8e6931e828673164b2e6">SymbolVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> *, 1 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accd9d70c3caa1eb8cdeb536dc89a19b1">addSymbol</a> (Symbol &amp;Sym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a symbol to the <a href="/web-llvm/docs/api/classes/llvm/jitlink/symboladdressmap">SymbolAddressMap</a>. <a href="#accd9d70c3caa1eb8cdeb536dc89a19b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SymbolPtrCollection&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9ffd5531d6187a911efd7354ded9e3d4">addSymbols</a> (SymbolPtrCollection &amp;&amp;Symbols)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add all symbols in a given range to the <a href="/web-llvm/docs/api/classes/llvm/jitlink/symboladdressmap">SymbolAddressMap</a>. <a href="#a9ffd5531d6187a911efd7354ded9e3d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adb0262d7e29d8e6931e828673164b2e6">SymbolVector</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a252c0928618df4ca1bfdd4da7d26b6de">getSymbolsAt</a> (orc::ExecutorAddr Addr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of symbols that start at the given address, or nullptr if no such symbols exist. <a href="#a252c0928618df4ca1bfdd4da7d26b6de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">orc::ExecutorAddr</a>, <a href="#adb0262d7e29d8e6931e828673164b2e6">SymbolVector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3721bae0ec74af3537c93b8d69039bb">AddrToSymbols</a></td>
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

<p>A map of addresses to Symbols.</p>

<p>Definition at line 1800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SymbolVector {#adb0262d7e29d8e6931e828673164b2e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::jitlink::SymbolAddressMap::SymbolVector =  SmallVector&lt;Symbol *, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSymbol() {#accd9d70c3caa1eb8cdeb536dc89a19b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::SymbolAddressMap::addSymbol (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Sym)</td>
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

<p>Add a symbol to the <a href="/web-llvm/docs/api/classes/llvm/jitlink/symboladdressmap">SymbolAddressMap</a>.</p>

<p>Definition at line 1805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a9266b50b560808e8f69eb394690d79c4">llvm::jitlink::Symbol::getAddress</a>.</p>

</div>
</div>

### addSymbols() {#a9ffd5531d6187a911efd7354ded9e3d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SymbolPtrCollection&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::SymbolAddressMap::addSymbols (SymbolPtrCollection &amp;&amp; Symbols)</td>
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

<p>Add all symbols in a given range to the <a href="/web-llvm/docs/api/classes/llvm/jitlink/symboladdressmap">SymbolAddressMap</a>.</p>

<p>Definition at line 1811 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a485a790f83f65357b91f1e369bc194da">addSymbol</a>.</p>

</div>
</div>

### getSymbolsAt() {#a252c0928618df4ca1bfdd4da7d26b6de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SymbolVector * llvm::jitlink::SymbolAddressMap::getSymbolsAt (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">orc::ExecutorAddr</a> Addr)</td>
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

<p>Returns the list of symbols that start at the given address, or nullptr if no such symbols exist.</p>

<p>Definition at line 1818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddrToSymbols {#ac3721bae0ec74af3537c93b8d69039bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;orc::ExecutorAddr, SymbolVector&gt; llvm::jitlink::SymbolAddressMap::AddrToSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
