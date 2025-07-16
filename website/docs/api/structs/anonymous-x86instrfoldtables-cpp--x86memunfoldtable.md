---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-x86instrfoldtables-cpp-/x86memunfoldtable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `X86MemUnfoldTable` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{X86InstrFoldTables.cpp}::X86MemUnfoldTable { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2f576f417a7ea5ff86df8304ce8a928">X86MemUnfoldTable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f86961dd463744c4ef9fda579a6753c">addTableEntry</a> (const X86FoldTableEntry &amp;Entry, uint16_t ExtraFlags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/x86foldtableentry">X86FoldTableEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9c82da518bf1ac662200fb14ff5d1f6">Table</a></td>
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


<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp">X86InstrFoldTables.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86MemUnfoldTable() {#aa2f576f417a7ea5ff86df8304ce8a928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86InstrFoldTables.cpp}::X86MemUnfoldTable::X86MemUnfoldTable ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp">X86InstrFoldTables.cpp</a>.</p>


<p>References <a href="#a7f86961dd463744c4ef9fda579a6753c">addTableEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add1eb5637dd671428b6f138ed3db6428">llvm::array_pod_sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad9c82da518bf1ac662200fb14ff5d1f6">Table</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29a2141006db02d9668671bb5d7ca482a7b903091e4c353176eb5262ca703c1a6">llvm::TB_FOLDED_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29a2141006db02d9668671bb5d7ca482a7ee73885c18c45ccdc0925a2580c4a8d">llvm::TB_FOLDED_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29a2141006db02d9668671bb5d7ca482aab83411d5cbdfd01f204a4e5da6f6974">llvm::TB_INDEX_0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29a2141006db02d9668671bb5d7ca482a9d7bf67c61e7357b1eee2c680ede0108">llvm::TB_INDEX_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29a2141006db02d9668671bb5d7ca482a16acf2d99f8e3a751c0de8f6bc8a8631">llvm::TB_INDEX_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29a2141006db02d9668671bb5d7ca482a01e8b454e398dfee88e7917058ee2cc1">llvm::TB_INDEX_3</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a29a2141006db02d9668671bb5d7ca482aba2e99f3194a879f01d0da4e9ba36d8c">llvm::TB_INDEX_4</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abc6f911b909c49d0f76ca616174a0fcb">llvm::lookupUnfoldTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addTableEntry() {#a7f86961dd463744c4ef9fda579a6753c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86InstrFoldTables.cpp}::X86MemUnfoldTable::addTableEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/x86foldtableentry">X86FoldTableEntry</a> &amp; Entry, uint16_t ExtraFlags)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp">X86InstrFoldTables.cpp</a>.</p>


<p>References <a href="#ad9c82da518bf1ac662200fb14ff5d1f6">Table</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a29a2141006db02d9668671bb5d7ca482af6fbf6d6d521683c803b1f1e22d50a5e">llvm::TB_NO_REVERSE</a>.</p>


<p>Referenced by <a href="#aa2f576f417a7ea5ff86df8304ce8a928">X86MemUnfoldTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Table {#ad9c82da518bf1ac662200fb14ff5d1f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;X86FoldTableEntry&gt; anonymous{X86InstrFoldTables.cpp}::X86MemUnfoldTable::Table</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp">X86InstrFoldTables.cpp</a>.</p>


<p>Referenced by <a href="#a7f86961dd463744c4ef9fda579a6753c">addTableEntry</a> and <a href="#aa2f576f417a7ea5ff86df8304ce8a928">X86MemUnfoldTable</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp">X86InstrFoldTables.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
