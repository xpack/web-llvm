---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-x86instrfoldtables-cpp-/x86broadcastfoldtable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `X86BroadcastFoldTable` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{X86InstrFoldTables.cpp}::X86BroadcastFoldTable { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59b44b32028cf595eeb5adb2d1669714">X86BroadcastFoldTable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae85927bea45d8ebbe2a47bb00e8f940c">Table</a></td>
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


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp">X86InstrFoldTables.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86BroadcastFoldTable() {#a59b44b32028cf595eeb5adb2d1669714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86InstrFoldTables.cpp}::X86BroadcastFoldTable::X86BroadcastFoldTable ()</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp">X86InstrFoldTables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#add1eb5637dd671428b6f138ed3db6428">llvm::array_pod_sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp/#ab520ec8054f420d05e017894a41538ad">BroadcastSizeTable2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp/#ac2f2af3af8be94e94e3004a1689a68ea">BroadcastSizeTable3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add4c3804b32bac78e4551544d3cb283f">llvm::lookupFoldTable</a>, <a href="#ae85927bea45d8ebbe2a47bb00e8f940c">Table</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29a2141006db02d9668671bb5d7ca482a7b903091e4c353176eb5262ca703c1a6">llvm::TB_FOLDED_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29a2141006db02d9668671bb5d7ca482a16acf2d99f8e3a751c0de8f6bc8a8631">llvm::TB_INDEX_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29a2141006db02d9668671bb5d7ca482a01e8b454e398dfee88e7917058ee2cc1">llvm::TB_INDEX_3</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a29a2141006db02d9668671bb5d7ca482aba2e99f3194a879f01d0da4e9ba36d8c">llvm::TB_INDEX_4</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a167b534725d841e143185971e9719ad4">llvm::lookupBroadcastFoldTableBySize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Table {#ae85927bea45d8ebbe2a47bb00e8f940c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;X86FoldTableEntry&gt; anonymous{X86InstrFoldTables.cpp}::X86BroadcastFoldTable::Table</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp">X86InstrFoldTables.cpp</a>.</p>


<p>Referenced by <a href="#a59b44b32028cf595eeb5adb2d1669714">X86BroadcastFoldTable</a>.</p>

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
