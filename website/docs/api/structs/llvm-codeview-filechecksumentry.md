---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/codeview/filechecksumentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FileChecksumEntry` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::codeview::FileChecksumEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugchecksumssubsection-h">llvm/DebugInfo/CodeView/DebugChecksumsSubsection.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07a498fcd876bdc77f36ee3c29f98ce4">FileNameOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac62eaa823ce96895afe82d6676aaae21">FileChecksumKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a547715a93f80c48c1f0d683b81b334b1">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af59eceeffd95dc0b17cfc7b3e0b4f5aa">Checksum</a></td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugchecksumssubsection-h">DebugChecksumsSubsection.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Checksum {#af59eceeffd95dc0b17cfc7b3e0b4f5aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::codeview::FileChecksumEntry::Checksum</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugchecksumssubsection-h">DebugChecksumsSubsection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp/#a7dccd1a95b77bf5792bba098da658c60">convertOneChecksum</a> and <a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor/#a4e7a87abc173694df4fd4f9255636528">llvm::VarStreamArrayExtractor&lt; T &gt;::operator()</a>.</p>

</div>
</div>

### FileNameOffset {#a07a498fcd876bdc77f36ee3c29f98ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::FileChecksumEntry::FileNameOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugchecksumssubsection-h">DebugChecksumsSubsection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp/#a7dccd1a95b77bf5792bba098da658c60">convertOneChecksum</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolcache/#a4f701c72d78d102b7b1041cc59a15d9a">llvm::pdb::SymbolCache::getOrCreateSourceFile</a> and <a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor/#a4e7a87abc173694df4fd4f9255636528">llvm::VarStreamArrayExtractor&lt; T &gt;::operator()</a>.</p>

</div>
</div>

### Kind {#a547715a93f80c48c1f0d683b81b334b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileChecksumKind llvm::codeview::FileChecksumEntry::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugchecksumssubsection-h">DebugChecksumsSubsection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp/#a7dccd1a95b77bf5792bba098da658c60">convertOneChecksum</a> and <a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor/#a4e7a87abc173694df4fd4f9255636528">llvm::VarStreamArrayExtractor&lt; T &gt;::operator()</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugchecksumssubsection-h">DebugChecksumsSubsection.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
