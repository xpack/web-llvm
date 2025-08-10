---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/symmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SymMap` Struct



## Declaration

<div class="doxyDeclaration">
struct SymMap { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a754a8232906949e759f7f2d231f93595">UseECMap</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3e5452193f29d245056cc8e4a63aaf8">Map</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1da8b4bf1fb5b60a5aa6054455c846a0">ECMap</a></td>
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


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### ECMap {#a1da8b4bf1fb5b60a5aa6054455c846a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string, uint16_t&gt; SymMap::ECMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a146d10ed8f323a076ba12323de86902f">computeECSymbolsSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a356355a0c98d7b39551d7473665510f1">computeHeadersSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a1f4394e4fc8872fa8f2a5baca5b3cc4b">getSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a9ffd2185084f74a9992ea31cc78c4ddb">writeECSymbols</a>.</p>

</div>
</div>

### Map {#ac3e5452193f29d245056cc8e4a63aaf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string, uint16_t&gt; SymMap::Map</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aaf3cab2e73302be816886e9c0ba73746">computeSymbolMapSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a1f4394e4fc8872fa8f2a5baca5b3cc4b">getSymbols</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a5b06dd328e277cc107d21a8ee4266e04">writeSymbolMap</a>.</p>

</div>
</div>

### UseECMap {#a754a8232906949e759f7f2d231f93595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SymMap::UseECMap = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a1f4394e4fc8872fa8f2a5baca5b3cc4b">getSymbols</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
