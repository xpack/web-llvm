---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `X86InstrFoldTables.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-h">X86InstrFoldTables.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include &lt;atomic&gt;
#include &lt;vector&gt;
#include "X86GenFoldTables.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86instrfoldtables-cpp-">anonymous{X86InstrFoldTables.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-x86instrfoldtables-cpp-/x86memunfoldtable">X86MemUnfoldTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-x86instrfoldtables-cpp-/x86broadcastfoldtable">X86BroadcastFoldTable</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/x86foldtableentry">X86FoldTableEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9968c8a44bfeea04a9923a6e997d62a">lookupFoldTableImpl</a> (ArrayRef&lt; X86FoldTableEntry &gt; Table, unsigned RegOp)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/x86foldtableentry">X86FoldTableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab520ec8054f420d05e017894a41538ad">BroadcastSizeTable2</a>[]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/x86foldtableentry">X86FoldTableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2f2af3af8be94e94e3004a1689a68ea">BroadcastSizeTable3</a>[] = ...</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac18166052050c8855b5cf3afacbc0841">CHECK_SORTED_UNIQUE</a>(TABLE)&nbsp;&nbsp;&nbsp;...</td>
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


<div class="doxySectionDef">

## Functions

### lookupFoldTableImpl() {#ac9968c8a44bfeea04a9923a6e997d62a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86FoldTableEntry * lookupFoldTableImpl (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/x86foldtableentry">X86FoldTableEntry</a> &gt; Table, unsigned RegOp)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp">X86InstrFoldTables.cpp</a>.</p>


<p>References <a href="#ab520ec8054f420d05e017894a41538ad">BroadcastSizeTable2</a>, <a href="#ac2f2af3af8be94e94e3004a1689a68ea">BroadcastSizeTable3</a>, <a href="#ac18166052050c8855b5cf3afacbc0841">CHECK_SORTED_UNIQUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a29a2141006db02d9668671bb5d7ca482a3c979ad13097cb5cb53a62ff6a706194">llvm::TB_NO_FORWARD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a52adbfeeea3564c3ad245a6e3d4bd13e">llvm::lookupBroadcastFoldTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add4c3804b32bac78e4551544d3cb283f">llvm::lookupFoldTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f9553b46f21ba407c575090242342b5">llvm::lookupTwoAddrFoldTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### BroadcastSizeTable2 {#ab520ec8054f420d05e017894a41538ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86FoldTableEntry BroadcastSizeTable2[]</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp">X86InstrFoldTables.cpp</a>.</p>


<p>Referenced by <a href="#ac9968c8a44bfeea04a9923a6e997d62a">lookupFoldTableImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86instrfoldtables-cpp-/x86broadcastfoldtable/#a59b44b32028cf595eeb5adb2d1669714">anonymous{X86InstrFoldTables.cpp}::X86BroadcastFoldTable::X86BroadcastFoldTable</a>.</p>

</div>
</div>

### BroadcastSizeTable3 {#ac2f2af3af8be94e94e3004a1689a68ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86FoldTableEntry BroadcastSizeTable3[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  { X86::VPTERNLOGDZ128rri,    X86::VPTERNLOGQZ128rmbi,   TB_BCAST_Q },
  { X86::VPTERNLOGDZ256rri,    X86::VPTERNLOGQZ256rmbi,   TB_BCAST_Q },
  { X86::VPTERNLOGDZrri,       X86::VPTERNLOGQZrmbi,      TB_BCAST_Q },
  { X86::VPTERNLOGQZ128rri,    X86::VPTERNLOGDZ128rmbi,   TB_BCAST_D },
  { X86::VPTERNLOGQZ256rri,    X86::VPTERNLOGDZ256rmbi,   TB_BCAST_D },
  { X86::VPTERNLOGQZrri,       X86::VPTERNLOGDZrmbi,      TB_BCAST_D },
}
</div>
</dd>
</dl>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp">X86InstrFoldTables.cpp</a>.</p>


<p>Referenced by <a href="#ac9968c8a44bfeea04a9923a6e997d62a">lookupFoldTableImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86instrfoldtables-cpp-/x86broadcastfoldtable/#a59b44b32028cf595eeb5adb2d1669714">anonymous{X86InstrFoldTables.cpp}::X86BroadcastFoldTable::X86BroadcastFoldTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CHECK\_SORTED\_UNIQUE {#ac18166052050c8855b5cf3afacbc0841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CHECK_SORTED_UNIQUE(TABLE)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>(<a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a>(TABLE) &amp;&amp; #TABLE " is not sorted");                   \
  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>(std::adjacent_find(std::begin(Table), std::end(Table)) ==             \
             std::end(Table) &amp;&amp;                                                \
         #TABLE " is not unique");
</div>
</dd>
</dl>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp">X86InstrFoldTables.cpp</a>.</p>


<p>Referenced by <a href="#ac9968c8a44bfeea04a9923a6e997d62a">lookupFoldTableImpl</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
