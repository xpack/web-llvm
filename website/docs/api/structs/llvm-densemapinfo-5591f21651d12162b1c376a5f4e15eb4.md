---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/densemapinfo-5591f21651d12162b1c376a5f4e15eb4
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DenseMapInfo` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::DenseMapInfo&lt;gsym::FileEntry&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/fileentry-h">llvm/DebugInfo/GSYM/FileEntry.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">gsym::FileEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2648b81dbd36a455a01075f36c695c0">getEmptyKey</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">gsym::FileEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcc4b05afdb5aef02ff52d8e3b157a69">getTombstoneKey</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85ceb710030ccf5cf90a0a1679c932d2">getHashValue</a> (const gsym::FileEntry &amp;Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba184a6f1878337298a0f7ab100491ca">isEqual</a> (const gsym::FileEntry &amp;LHS, const gsym::FileEntry &amp;RHS)</td>
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


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/fileentry-h">FileEntry.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### getEmptyKey() {#ae2648b81dbd36a455a01075f36c695c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">gsym::FileEntry llvm::DenseMapInfo&lt; gsym::FileEntry &gt;::getEmptyKey ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/fileentry-h">FileEntry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a1423601a8e4ec304e0756df4e761ebbb">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getEmptyKey</a>.</p>

</div>
</div>

### getHashValue() {#a85ceb710030ccf5cf90a0a1679c932d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DenseMapInfo&lt; gsym::FileEntry &gt;::getHashValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">gsym::FileEntry</a> &amp; Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/fileentry-h">FileEntry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry/#a59868c936c9541093eadc4f035ebd014">llvm::gsym::FileEntry::Base</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry/#ae9efc2fdaa930f2cbdddfd4c553e50a6">llvm::gsym::FileEntry::Dir</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a86544e5fd2336905e43348d2fd546094">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getHashValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>.</p>

</div>
</div>

### getTombstoneKey() {#abcc4b05afdb5aef02ff52d8e3b157a69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">gsym::FileEntry llvm::DenseMapInfo&lt; gsym::FileEntry &gt;::getTombstoneKey ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/fileentry-h">FileEntry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a9571e26b946751eaf015a9b8dc508be9">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getTombstoneKey</a>.</p>

</div>
</div>

### isEqual() {#aba184a6f1878337298a0f7ab100491ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DenseMapInfo&lt; gsym::FileEntry &gt;::isEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">gsym::FileEntry</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">gsym::FileEntry</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/fileentry-h">FileEntry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/fileentry-h">FileEntry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
