---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/bittracker/bitvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `BitValue` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::BitTracker::BitValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">Target/Hexagon/BitTracker.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ValueType { <a href="#a8e191c51f58f07f7efa53510f3bdda94">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf49831b316ebf268837d62a1f22385">operator&lt;&lt;</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee974ecd21a533055fdd11ec27e4febc">BitValue</a> (ValueType T=Top)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae82441d5561744e553d3bb4c80dafb5">BitValue</a> (bool B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3cf0a47fd46d1e90659df084cad7945">BitValue</a> (unsigned Reg, uint16_t Pos)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9885b33e0b43c4d592c8cc4387e949bf">operator==</a> (const BitValue &amp;V) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3366f997072ee07a81c1eacfb236f9">operator!=</a> (const BitValue &amp;V) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d3cb71148daa6a880eb2888b4a5a61a">operator bool</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdda211d574b7a9074aa1cdb1b0b204b">is</a> (unsigned T) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afce9aa6fea3ff538f2a94c8c56a34e04">meet</a> (const BitValue &amp;V, const BitRef &amp;Self)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcd0b7d53f566f3bfb0ede8423b08e28">num</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8e191c51f58f07f7efa53510f3bdda94">ValueType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a093eda80cf560688e6c3578e8b7fd674">Type</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/bitref">BitRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6430b3f9e35d7d7e83399a565cfd143e">RefI</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue">BitValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a701348c13b6afb4d3ee38ec978ea0e49">ref</a> (const BitValue &amp;V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue">BitValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad20a19c881ef4af1b3a270bf06fa8d89">self</a> (const BitRef &amp;Self=BitRef())</td>
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


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ValueType {#a8e191c51f58f07f7efa53510f3bdda94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::BitTracker::BitValue::ValueType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Top<a id="a8e191c51f58f07f7efa53510f3bdda94ac09b1529fd94175201a6edddd3a27c37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Zero<a id="a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">One<a id="a8e191c51f58f07f7efa53510f3bdda94a86e84878fc26bf4a4fd39f94424b730b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ref<a id="a8e191c51f58f07f7efa53510f3bdda94a92811673861e6cd90e002880ed0ea153"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#aedf49831b316ebf268837d62a1f22385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue">BitValue</a> &amp; BV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitref/#ab66cddedf2717fe3649ae4aecc6232c5">llvm::BitTracker::BitRef::Pos</a>, <a href="#a6430b3f9e35d7d7e83399a565cfd143e">RefI</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitref/#a40e257127c0ff61f7ce778d68468096c">llvm::BitTracker::BitRef::Reg</a> and <a href="#a093eda80cf560688e6c3578e8b7fd674">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BitValue() {#aee974ecd21a533055fdd11ec27e4febc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitTracker::BitValue::BitValue (<a href="#a8e191c51f58f07f7efa53510f3bdda94">ValueType</a> T=<a href="#a8e191c51f58f07f7efa53510f3bdda94ac09b1529fd94175201a6edddd3a27c37">Top</a>)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#a8e191c51f58f07f7efa53510f3bdda94ac09b1529fd94175201a6edddd3a27c37">Top</a> and <a href="#a093eda80cf560688e6c3578e8b7fd674">Type</a>.</p>


<p>Referenced by <a href="#afce9aa6fea3ff538f2a94c8c56a34e04">meet</a>, <a href="#a0e3366f997072ee07a81c1eacfb236f9">operator!=</a>, <a href="#a9885b33e0b43c4d592c8cc4387e949bf">operator==</a>, <a href="#a701348c13b6afb4d3ee38ec978ea0e49">ref</a> and <a href="#ad20a19c881ef4af1b3a270bf06fa8d89">self</a>.</p>

</div>
</div>

### BitValue() {#aae82441d5561744e553d3bb4c80dafb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitTracker::BitValue::BitValue (bool B)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a8e191c51f58f07f7efa53510f3bdda94a86e84878fc26bf4a4fd39f94424b730b">One</a>, <a href="#a093eda80cf560688e6c3578e8b7fd674">Type</a> and <a href="#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">Zero</a>.</p>

</div>
</div>

### BitValue() {#ab3cf0a47fd46d1e90659df084cad7945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitTracker::BitValue::BitValue (unsigned Reg, uint16_t Pos)</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="#a8e191c51f58f07f7efa53510f3bdda94a92811673861e6cd90e002880ed0ea153">Ref</a>, <a href="#a6430b3f9e35d7d7e83399a565cfd143e">RefI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="#a093eda80cf560688e6c3578e8b7fd674">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a6d3cb71148daa6a880eb2888b4a5a61a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitTracker::BitValue::operator bool ()</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8e191c51f58f07f7efa53510f3bdda94a86e84878fc26bf4a4fd39f94424b730b">One</a>, <a href="#a093eda80cf560688e6c3578e8b7fd674">Type</a> and <a href="#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">Zero</a>.</p>

</div>
</div>

### operator!=() {#a0e3366f997072ee07a81c1eacfb236f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitTracker::BitValue::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue">BitValue</a> &amp; V)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="#aee974ecd21a533055fdd11ec27e4febc">BitValue</a> and <a href="#a9885b33e0b43c4d592c8cc4387e949bf">operator==</a>.</p>

</div>
</div>

### operator==() {#a9885b33e0b43c4d592c8cc4387e949bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitTracker::BitValue::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue">BitValue</a> &amp; V)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="#aee974ecd21a533055fdd11ec27e4febc">BitValue</a>, <a href="#a8e191c51f58f07f7efa53510f3bdda94a92811673861e6cd90e002880ed0ea153">Ref</a>, <a href="#a6430b3f9e35d7d7e83399a565cfd143e">RefI</a> and <a href="#a093eda80cf560688e6c3578e8b7fd674">Type</a>.</p>


<p>Referenced by <a href="#a0e3366f997072ee07a81c1eacfb236f9">operator!=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### is() {#abdda211d574b7a9074aa1cdb1b0b204b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitTracker::BitValue::is (unsigned T)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8e191c51f58f07f7efa53510f3bdda94a86e84878fc26bf4a4fd39f94424b730b">One</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#a093eda80cf560688e6c3578e8b7fd674">Type</a> and <a href="#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#adbf082422e6f7a82cea21dfa3273811d">llvm::BitTracker::MachineEvaluator::eADD</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#ab4b48cf5ad86cd432b03b6f5b254f227">llvm::BitTracker::MachineEvaluator::eAND</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#abe57eebc5c101a825f3c31712fdd617b">llvm::BitTracker::MachineEvaluator::eORL</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#add47c55cf111a92da1ded367147668eb">llvm::BitTracker::MachineEvaluator::eSUB</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a2c519d1784e4a4beee0fd668ed8d3900">llvm::BitTracker::MachineEvaluator::eXOR</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#aaee53452baac84a9ca49c3eda557ba3d">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getConst</a> and <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/bitvalueordering/#a79d74e7a161f1e6c0e5ec74bc7044e31">anonymous{HexagonGenInsert.cpp}::BitValueOrdering::operator()</a>.</p>

</div>
</div>

### meet() {#afce9aa6fea3ff538f2a94c8c56a34e04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitTracker::BitValue::meet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue">BitValue</a> &amp; V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitref">BitRef</a> &amp; Self)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="#aee974ecd21a533055fdd11ec27e4febc">BitValue</a>, <a href="#a8e191c51f58f07f7efa53510f3bdda94a92811673861e6cd90e002880ed0ea153">Ref</a>, <a href="#a6430b3f9e35d7d7e83399a565cfd143e">RefI</a>, <a href="#a8e191c51f58f07f7efa53510f3bdda94ac09b1529fd94175201a6edddd3a27c37">Top</a> and <a href="#a093eda80cf560688e6c3578e8b7fd674">Type</a>.</p>

</div>
</div>

### num() {#adcd0b7d53f566f3bfb0ede8423b08e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitTracker::BitValue::num ()</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="#a8e191c51f58f07f7efa53510f3bdda94a86e84878fc26bf4a4fd39f94424b730b">One</a>, <a href="#a093eda80cf560688e6c3578e8b7fd674">Type</a> and <a href="#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#adbf082422e6f7a82cea21dfa3273811d">llvm::BitTracker::MachineEvaluator::eADD</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#add47c55cf111a92da1ded367147668eb">llvm::BitTracker::MachineEvaluator::eSUB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### RefI {#a6430b3f9e35d7d7e83399a565cfd143e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitRef llvm::BitTracker::BitValue::RefI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Referenced by <a href="#ab3cf0a47fd46d1e90659df084cad7945">BitValue</a>, <a href="#afce9aa6fea3ff538f2a94c8c56a34e04">meet</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/bitvalueordering/#a79d74e7a161f1e6c0e5ec74bc7044e31">anonymous{HexagonGenInsert.cpp}::BitValueOrdering::operator()</a>, <a href="#aedf49831b316ebf268837d62a1f22385">operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a125f77300db175faeae41d9a628194d6">llvm::BitTracker::RegisterCell::operator&lt;&lt;</a>, <a href="#a9885b33e0b43c4d592c8cc4387e949bf">operator==</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#aa6e2cfce750a7dddf5e3bc60ad55f1b1">llvm::BitTracker::RegisterCell::regify</a>.</p>

</div>
</div>

### Type {#a093eda80cf560688e6c3578e8b7fd674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueType llvm::BitTracker::BitValue::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Referenced by <a href="#aae82441d5561744e553d3bb4c80dafb5">BitValue</a>, <a href="#ab3cf0a47fd46d1e90659df084cad7945">BitValue</a>, <a href="#aee974ecd21a533055fdd11ec27e4febc">BitValue</a>, <a href="#abdda211d574b7a9074aa1cdb1b0b204b">is</a>, <a href="#afce9aa6fea3ff538f2a94c8c56a34e04">meet</a>, <a href="#adcd0b7d53f566f3bfb0ede8423b08e28">num</a>, <a href="#a6d3cb71148daa6a880eb2888b4a5a61a">operator bool</a>, <a href="#aedf49831b316ebf268837d62a1f22385">operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a125f77300db175faeae41d9a628194d6">llvm::BitTracker::RegisterCell::operator&lt;&lt;</a> and <a href="#a9885b33e0b43c4d592c8cc4387e949bf">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### ref() {#a701348c13b6afb4d3ee38ec978ea0e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitTracker::BitValue llvm::BitTracker::BitValue::ref (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue">BitValue</a> &amp; V)</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="#aee974ecd21a533055fdd11ec27e4febc">BitValue</a>, <a href="#a8e191c51f58f07f7efa53510f3bdda94a92811673861e6cd90e002880ed0ea153">Ref</a> and <a href="#ad20a19c881ef4af1b3a270bf06fa8d89">self</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#adbf082422e6f7a82cea21dfa3273811d">llvm::BitTracker::MachineEvaluator::eADD</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#ab4b48cf5ad86cd432b03b6f5b254f227">llvm::BitTracker::MachineEvaluator::eAND</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#abe57eebc5c101a825f3c31712fdd617b">llvm::BitTracker::MachineEvaluator::eORL</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#add47c55cf111a92da1ded367147668eb">llvm::BitTracker::MachineEvaluator::eSUB</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a2c519d1784e4a4beee0fd668ed8d3900">llvm::BitTracker::MachineEvaluator::eXOR</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4e73984cdacfb5cd24df684bbe6af7a7">llvm::BitTracker::RegisterCell::ref</a>.</p>

</div>
</div>

### self() {#ad20a19c881ef4af1b3a270bf06fa8d89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitTracker::BitValue llvm::BitTracker::BitValue::self (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitref">BitRef</a> &amp; Self=<a href="/web-llvm/docs/api/structs/llvm/bittracker/bitref">BitRef</a>())</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="#aee974ecd21a533055fdd11ec27e4febc">BitValue</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitref/#ab66cddedf2717fe3649ae4aecc6232c5">llvm::BitTracker::BitRef::Pos</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitref/#a40e257127c0ff61f7ce778d68468096c">llvm::BitTracker::BitRef::Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#adbf082422e6f7a82cea21dfa3273811d">llvm::BitTracker::MachineEvaluator::eADD</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#ab4b48cf5ad86cd432b03b6f5b254f227">llvm::BitTracker::MachineEvaluator::eAND</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a6032f746ffa25df648aa38680d1e891e">llvm::BitTracker::MachineEvaluator::eMLS</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a518631233431d2324f15075cf91ffab2">llvm::BitTracker::MachineEvaluator::eMLU</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a4aa1e4c6871a0b6056bba979f7c546bb">llvm::BitTracker::MachineEvaluator::eNOT</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#abe57eebc5c101a825f3c31712fdd617b">llvm::BitTracker::MachineEvaluator::eORL</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#add47c55cf111a92da1ded367147668eb">llvm::BitTracker::MachineEvaluator::eSUB</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a2c519d1784e4a4beee0fd668ed8d3900">llvm::BitTracker::MachineEvaluator::eXOR</a>, <a href="#a701348c13b6afb4d3ee38ec978ea0e49">ref</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4b372ece8559169470a7fcfb471c2302">llvm::BitTracker::RegisterCell::self</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
