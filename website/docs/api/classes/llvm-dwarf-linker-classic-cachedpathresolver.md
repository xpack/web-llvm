---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/classic/cachedpathresolver
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CachedPathResolver` Class Reference

<p>Small helper that resolves and caches file paths. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::classic::CachedPathResolver { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkerdeclcontext-h">llvm/DWARFLinker/Classic/DWARFLinkerDeclContext.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83dd2ec674ed050c3d4dd6f9541f8fd4">resolve</a> (const std::string &amp;Path, NonRelocatableStringpool &amp;StringPool)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve a path by calling realpath and cache its result. <a href="#a83dd2ec674ed050c3d4dd6f9541f8fd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af19e0e5ce86c56dd9d9bb3b2ba1b1ff5">ResolvedPaths</a></td>
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

<p>Small helper that resolves and caches file paths.</p>


<p>This helps reduce the number of calls to realpath which is expensive. We assume the input are files, and cache the realpath of their parent. This way we can quickly resolve different files under the same path.</p>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkerdeclcontext-h">DWARFLinkerDeclContext.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### resolve() {#a83dd2ec674ed050c3d4dd6f9541f8fd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::dwarf_linker::classic::CachedPathResolver::resolve (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Path, <a href="/web-llvm/docs/api/classes/llvm/nonrelocatablestringpool">NonRelocatableStringpool</a> &amp; StringPool)</td>
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

<p>Resolve a path by calling realpath and cache its result.</p>


<p>The returned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> is interned in the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/stringpool">StringPool</a></span>.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkerdeclcontext-h">DWARFLinkerDeclContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a5326427c87607b2364a1fcdf13fa0eea">llvm::sys::path::parent_path</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a2363fbfbd0a348f5d81fc3d3223ecae3">llvm::sys::fs::real_path</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ResolvedPaths {#af19e0e5ce86c56dd9d9bb3b2ba1b1ff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::string&gt; llvm::dwarf_linker::classic::CachedPathResolver::ResolvedPaths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkerdeclcontext-h">DWARFLinkerDeclContext.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkerdeclcontext-h">DWARFLinkerDeclContext.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
