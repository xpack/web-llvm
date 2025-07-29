---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/register
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Register` Class

<p>Wrapper class representing virtual and physical registers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Register { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">llvm/CodeGen/Register.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a228e680d10a53c933898d03cc834e5a0">Register</a> (unsigned Val=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c98da56d9b14f4dc39ca3b79cf1a6e3">Register</a> (MCRegister Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a523e628055b7c11ff382d96d1c0eb180">operator unsigned</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a993e58b2ab75cc8fce1d7131ed66d8d6">operator MCRegister</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26721717ec9cb5a43eefb72586d58ade">operator==</a> (const Register &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Comparisons between register objects. <a href="#a26721717ec9cb5a43eefb72586d58ade">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a340f8e6ea15e93f0b9b7e4e2be8a1950">operator!=</a> (const Register &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0d6bd40f34874d8efce4d7810cd0ab">operator==</a> (const MCRegister &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c77a810ae621665d3fc0e728cf3f5cd">operator!=</a> (const MCRegister &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e152ffdc5cbf1b6f7411b78271cad92">operator==</a> (unsigned Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Comparisons against register constants. <a href="#a6e152ffdc5cbf1b6f7411b78271cad92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab720f315b0c869cd8fc187026e66a1f1">operator!=</a> (unsigned Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaaa2e856fb7c86bf06e6f91a689a40b">operator==</a> (int Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7710311357a0c37d0474988d09b8d269">operator!=</a> (int Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af97a5d0ff1a2cd9e3bf14602a87b8fa2">operator==</a> (MCPhysReg Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab439d486c2b2a3d362918623be867010">operator!=</a> (MCPhysReg Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a049da63f9b7d0bcd1e6aa2b73fe5896c">isStack</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a stack slot. <a href="#a049da63f9b7d0bcd1e6aa2b73fe5896c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab203bbcbc320180b1da9e9a92ee0c784">isVirtual</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified register number is in the virtual register namespace. <a href="#ab203bbcbc320180b1da9e9a92ee0c784">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affdbf5b92ed7e01352e2f39466efbe21">isPhysical</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified register number is in the physical register namespace. <a href="#affdbf5b92ed7e01352e2f39466efbe21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f34bdaea90f8ee41a43a83a0c0e3b4c">virtRegIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a virtual register number to a 0-based index. <a href="#a5f34bdaea90f8ee41a43a83a0c0e3b4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcfb1380ec9ff3f6106193a6ea9313c6">id</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49effcc0d9e7a321043ade70145d11f6">asMCReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility to check-convert this value to a <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a>. <a href="#a49effcc0d9e7a321043ade70145d11f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7407603b3efcdc8d4c2b76697be34528">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea4861d48b32ce99043495fa6972a17b">Reg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a050c8e969ce1fa8c229b074fd07be925">isStackSlot</a> (unsigned Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isStackSlot - Sometimes it is useful to be able to store a non-negative frame index in a variable that normally holds a register. <a href="#a050c8e969ce1fa8c229b074fd07be925">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47caf9a25186eed2215d13171af1f3ca">stackSlot2Index</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the frame index from a register value representing a stack slot. <a href="#a47caf9a25186eed2215d13171af1f3ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92cd11abfd541caadc1fc825b78f9903">index2StackSlot</a> (int FI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a non-negative frame index to a stack slot register value. <a href="#a92cd11abfd541caadc1fc825b78f9903">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afacc26f29d80e10be4785a96ed6444dc">isPhysicalRegister</a> (unsigned Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified register number is in the physical register namespace. <a href="#afacc26f29d80e10be4785a96ed6444dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6bf744f357352cde7578931007c0b6f">isVirtualRegister</a> (unsigned Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified register number is in the virtual register namespace. <a href="#ac6bf744f357352cde7578931007c0b6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4df23dddc646b6a4b36ff483063a4ff8">virtReg2Index</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a virtual register number to a 0-based index. <a href="#a4df23dddc646b6a4b36ff483063a4ff8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1979c563289f871907832e419889f979">index2VirtReg</a> (unsigned Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a 0-based index to a virtual register number. <a href="#a1979c563289f871907832e419889f979">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Wrapper class representing virtual and physical registers.</p>


<p>Should be passed by value.</p>


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Register() {#a228e680d10a53c933898d03cc834e5a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Register::Register (unsigned Val=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Referenced by <a href="#a92cd11abfd541caadc1fc825b78f9903">index2StackSlot</a>, <a href="#a1979c563289f871907832e419889f979">index2VirtReg</a>, <a href="#a340f8e6ea15e93f0b9b7e4e2be8a1950">operator!=</a>, <a href="#a26721717ec9cb5a43eefb72586d58ade">operator==</a>, <a href="#a47caf9a25186eed2215d13171af1f3ca">stackSlot2Index</a> and <a href="#a4df23dddc646b6a4b36ff483063a4ff8">virtReg2Index</a>.</p>

</div>
</div>

### Register() {#a8c98da56d9b14f4dc39ca3b79cf1a6e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Register::Register (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="#afcfb1380ec9ff3f6106193a6ea9313c6">id</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator MCRegister() {#a993e58b2ab75cc8fce1d7131ed66d8d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Register::operator MCRegister ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>

</div>
</div>

### operator unsigned() {#a523e628055b7c11ff382d96d1c0eb180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Register::operator unsigned ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>

</div>
</div>

### operator!=() {#a340f8e6ea15e93f0b9b7e4e2be8a1950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a228e680d10a53c933898d03cc834e5a0">Register</a>.</p>

</div>
</div>

### operator!=() {#a9c77a810ae621665d3fc0e728cf3f5cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator!=() {#ab720f315b0c869cd8fc187026e66a1f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::operator!= (unsigned Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator!=() {#a7710311357a0c37d0474988d09b8d269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::operator!= (int Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator!=() {#ab439d486c2b2a3d362918623be867010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::operator!= (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#a26721717ec9cb5a43eefb72586d58ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Comparisons between register objects.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a228e680d10a53c933898d03cc834e5a0">Register</a>.</p>

</div>
</div>

### operator==() {#a6b0d6bd40f34874d8efce4d7810cd0ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#a6e152ffdc5cbf1b6f7411b78271cad92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::operator== (unsigned Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Comparisons against register constants.</p>


<p>E.g.</p>


<ul class="doxyList ">
<li>R == AArch64::WZR</li>
<li>R == 0</li>
</ul>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#acaaa2e856fb7c86bf06e6f91a689a40b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::operator== (int Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#af97a5d0ff1a2cd9e3bf14602a87b8fa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::operator== (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### asMCReg() {#a49effcc0d9e7a321043ade70145d11f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::Register::asMCReg ()</td>
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

<p>Utility to check-convert this value to a <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a>.</p>


<p>The caller is expected to have already validated that this <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is, indeed, physical.</p>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#affdbf5b92ed7e01352e2f39466efbe21">isPhysical</a> and <a href="#a7407603b3efcdc8d4c2b76697be34528">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#aca0ccc3903ae5fedb32c51eb99d479ca">llvm::TargetRegisterClass::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a01fce66601f12ad1b3bd219ff02c3426">llvm::VirtRegAuxInfo::copyHint</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a64ee9ca87205e764e0382240030f87ee">llvm::BitTracker::MachineEvaluator::getRegBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#acfdb7e9be44e0d08b3b97b9177b8239e">isCopyFeedingInvariantStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ab5dddfd4ef6db864a18ecdbe51331b92">llvm::TargetRegisterInfo::regsOverlap</a> and <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#a22414e0619deaa2a695fd6d31002bb9d">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateTailPredicate</a>.</p>

</div>
</div>

### id() {#afcfb1380ec9ff3f6106193a6ea9313c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Register::id ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbankconflicthazardrecognizer/#abd3b799a5199979babb67c1211b73c7c">llvm::ARMBankConflictHazardRecognizer::getHazardType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ac4353ee1069000ba0e78e584368bf1f2">getLibCallID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ae4ad01c7c2990a944ca190cd409a60d5">getMaxPushPopReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a8bc629292d5cf14604e9b35b42ac4706">llvm::MachineRegisterInfo::getRegAllocationHint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp/#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#a64ef2d014c82249a7bc8cb033757d7f1">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#ae87b9efb9db9ad27a0f5f7d753ce45fd">llvm::LoongArchAsmPrinter::PrintAsmOperand</a>, <a href="#a8c98da56d9b14f4dc39ca3b79cf1a6e3">Register</a> and <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/graphmetadata/#a5fcef5a425faf54a4b3b3276419226fd">llvm::PBQP::RegAlloc::GraphMetadata::setNodeIdForVReg</a>.</p>

</div>
</div>

### isPhysical() {#affdbf5b92ed7e01352e2f39466efbe21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::isPhysical ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified register number is in the physical register namespace.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="#afacc26f29d80e10be4785a96ed6444dc">isPhysicalRegister</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a57484713254f31f8412d08ff85259761">llvm::DwarfExpression::addMachineReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afda2c0f22be043ae42b0ec71b661f565">llvm::MachineInstr::addRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a34ace715436fcbc42e83e196957b9f16">llvm::AnalyzePhysRegInBundle</a>, <a href="#a49effcc0d9e7a321043ade70145d11f6">asMCReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a848f5b2d82a5d809fe4785b96e6bdb95">canFoldCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a708b9606a37961be41adad607c81c532">llvm::canReplaceReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#a5290bdffbf68a26e47345d1bb2abb246">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::collectCandidateRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp/#aef8f01c925c0c7beb94976a8f86a9af1">collectRegDefs</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#ab47a3d3cac0564876929e77389dbe569">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::collectWaterfallCandidateRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#adf4d05c8ea2fc82ae12300ef5fb48951">llvm::TargetInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#aca0ccc3903ae5fedb32c51eb99d479ca">llvm::TargetRegisterClass::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a40c836e17635ff1fde99148b3a54ce80">llvm::X86InstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aeeed341d0f3c7220d070d766e3a0f584">llvm::MachineInstr::findRegisterDefOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aec4538d6aec6f79de5c3b56115fd2c78">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a561542857883d396fc0c5dc9a1de342f">foldVGPRCopyIntoRegSequence</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a9a70d4969d8d43a9c9b324f692bc8ecd">llvm::BitTracker::MachineEvaluator::getCell</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-utils-cpp-/#a3fb5a21e3d12a4f09da156333cdef568">anonymous{Utils.cpp}::getConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a8e8f884db0a3faadefc981023902a1ec">llvm::SIInstrInfo::getInstructionUniformity</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siformmemoryclauses-cpp/#ae42ae7520e86040563aa828fc9d5eb91">getMopState</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a4cbbdd3795a958b1e24bd85cf48a0519">llvm::HexagonInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a77b81cc14aafd09d0e380b123cd06d51">llvm::ARMBaseRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#ad490ad7663a07141538a6f4049299550">llvm::RISCVRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a31e904f48ac2baf80f9222c49059ef63">llvm::SystemZRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#afc99d2835eb4b8cde9e81db9abca597c">llvm::TargetRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ada2b3cb4854ef22758c48e3721ddb1e2">llvm::X86RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a64ee9ca87205e764e0382240030f87ee">llvm::BitTracker::MachineEvaluator::getRegBitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5bbb47ecb2be0bf50b8cafb94dee081">llvm::getRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad526a98b9842792511d37f5499693349">llvm::X86InstrInfo::getUndefRegClearance</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandpostrapseudos-cpp/#a406c74892c483b9ba9532bc070ceda6f">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#aea53813ca1c1efc9ef06b5b9844be967">isIdenticalOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrcopyreplacer/#ae9856bdc6cd6e8cadf3b67fad21cb839">anonymous{X86DomainReassignment.cpp}::InstrCOPYReplacer::isLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a4ad934d9334200ff676c9568774206cd">isLibCallInTailPosition</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a272a95f31ec948e680a3c7dffd3c7f80">isLocalCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smepeepholeopt-cpp/#a7ee076808f65d7b724d9a94d48b2cee8">isMatchingStartStopPair</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a203e9048ad3087cf61713d0d307a246c">llvm::SITargetLowering::legalizeTargetIndependentNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a81fe15801547c074b2c33034c00df067">llvm::ARMBaseInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a1eeb397bafd16951ce8898c83f21c5e4">llvm::Thumb1InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab1601d92ffdfcf6fe48b40b6a7cf8d59">loadRegPairFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a68b7b9c491045c788173e83be1ba5d2b">llvm::TargetInstrInfo::lowerCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegencommonisel-cpp/#ad007531739421e7b54a41c3fefaefa4e">MIIsInTerminatorSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a241b0b6bb1961190125114fb88db4a27">llvm::SIInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a8b67fcf985704c812d104989a617a939">llvm::HexagonFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ab5dddfd4ef6db864a18ecdbe51331b92">llvm::TargetRegisterInfo::regsOverlap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#af16c39ee36e4633f821b6820f8bd52ef">llvm::MachineRegisterInfo::replaceRegWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kernelrewriter/#a2e7a99d381fd8c317ade905833ae3138">anonymous{ModuloSchedule.cpp}::KernelRewriter::rewrite</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a933b079df28c77f3850ed1edf94c6ed8">selectCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arminstructionselector-cpp/#a933b079df28c77f3850ed1edf94c6ed8">selectCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppcinstructionselector-cpp/#a933b079df28c77f3850ed1edf94c6ed8">selectCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#afb4c3921369b6b1fef886bfa979b6d2a">storeRegPairToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a952f199f7cb8a257a40193bcd67a976d">llvm::Thumb1InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9f59e1f6dd6677348ba082a10fc09061">llvm::MachineInstr::substituteRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#ac9ca747a6b6297f53d182bfe78514963">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldFoldableCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#aac5e465289c9bc7adb88b6b682fdf85b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### isStack() {#a049da63f9b7d0bcd1e6aa2b73fe5896c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::isStack ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this is a stack slot.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a01c52fcd65bb831db823ecd35cf0a3ba">llvm::MCRegister::isStackSlot</a>.</p>

</div>
</div>

### isValid() {#a7407603b3efcdc8d4c2b76697be34528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::isValid ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a4aa6aac0f36c1123df3686f7b4150d2c">llvm::MCRegister::NoRegister</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a9a91b779e07acc1400574b81f1ba1a70">addConstantsToTrack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp/#a099dfc173455c7f27311d9c9cfa9cd62">addOpsFromMDNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/giseladdressing/#a140cb977d5598588fb9e0079cd1aabf9">llvm::GISelAddressing::aliasIsKnownForLoadStore</a>, <a href="#a49effcc0d9e7a321043ade70145d11f6">asMCReg</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#adc3de6cf6278fe59671bbdd02e4c1516">llvm::HexagonFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7380fc2046fc70f0b6040466a1a535af">llvm::buildBarrierInst</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a6aee777d2869b23ba59b88b9ceb32cfe">llvm::SPIRVGlobalRegistry::buildConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#affb04c244423615aa0df24ee36f2de20">llvm::SPIRVGlobalRegistry::buildConstantInt</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4280c0cdf83d31309a8ad8d0d6815e66">llvm::SPIRVGlobalRegistry::buildConstantSampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92b7677cd4ee158a68f41214d43bfae4">llvm::buildMemSemanticsReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3da6d300541b1f353472e9494bbdb11b">llvm::buildScopeReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblydebugvaluemanager/#a93c989266fe445bd8d6466480699665e">llvm::WebAssemblyDebugValueManager::cloneSink</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a9acef535219004fa4c89f4f996343b6f">copySubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a9c2ee381172db4d044e61d3438031d6b">llvm::HexagonDAGToDAGISel::emitFunctionEntryCode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aed0535a6ce0e4e5969a60a1635d0b18a">llvm::SIInstrInfo::getAddNoCarry</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af99db04834e1ae3fc23466a80045a4d9">llvm::SPIRVGlobalRegistry::getOrCreateConstNullPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a69f73e1b5f8a3e376c63293408b6786e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeByOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acbccd3fb66e9075690f45dea7440cf9e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeCoopMatr</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a35c2ba2ad91e2fe027f8f64e92a7502f">llvm::SPIRVGlobalRegistry::getOrCreateUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a7a7237cd5cb35f9159b32a96f4b14541">llvm::X86TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a3372d351ec7fac9fb1066e77d36f1276">llvm::HexagonRegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a376f5aa1990808e8e65cc77dd462c677">getTestBitReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/loadstoreopt-cpp/#a862473b9c3e242287a712fdb1171ccb3">getTruncStoreByteOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a4af3414dbf16e5eb1b862c7cf35ed83c">llvm::VirtRegMap::hasPreferredPhys</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertreadwritecsr-cpp/#a93ca2859094e3f43227290d2f88472c9">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelateinstrscleanup-cpp/#a1705fe175d6d933d516bee5ba700abaa">isCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a805950c6af7deaddb2d8fbcaf4ea011b">llvm::AMDGPULegalizerInfo::legalizeAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aef098c9f09dc6ea1e32e64d79091a237">llvm::AArch64InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmcinstlower/#a6d050903b1d4eb1403389e782f6cec1c">llvm::SPIRVMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a0321e28cc3da73c666a6f5e58a541de8">llvm::PhiLoweringHelper::lowerPhis</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a76df0b752eddd8b0711d1af16a3658ad">llvm::LegalizerHelper::lowerReadWriteRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aebbd8556be493cfb10fce51e933d7e2e">llvm::CombinerHelper::matchCombineAnyExtTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aab86990eacd037e1c72749c3342d410e">llvm::CombinerHelper::matchHoistLogicOpWithSameOpcodeHands</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#afc046e9fee2ff69250264feef8baaf15">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputExecutionMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#af3659f9d7092d775e6bb2451b39aa440">popRegsFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a8b67fcf985704c812d104989a617a939">llvm::HexagonFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#af352e338e2b9a8cd58a97aca55d421e4">processNewInstrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbankselect-cpp-/amdgpuregbankselect/#abceb824dea15a0f50ab19fc7126f618f">anonymous{AMDGPURegBankSelect.cpp}::AMDGPURegBankSelect::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86argumentstackslotrebase-cpp-/x86argumentstackslotpass/#af787e4cab9e64467b9aa0a253171fa88">anonymous{X86ArgumentStackSlotRebase.cpp}::X86ArgumentStackSlotPass::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-riscvexpandatomicpseudoinsts-cpp-/#aa167eef8fffa86a11c06e11e5cfbc692">anonymous{RISCVExpandAtomicPseudoInsts.cpp}::tryToFoldBNEOnCmpXchgResult</a>.</p>

</div>
</div>

### isVirtual() {#ab203bbcbc320180b1da9e9a92ee0c784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Register::isVirtual ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified register number is in the virtual register namespace.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="#ac6bf744f357352cde7578931007c0b6f">isVirtualRegister</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#abc82dfed5cd6e963934d2d0f8d6e7272">llvm::MachineRegisterInfo::addRegAllocationHint</a>, <a href="/web-llvm/docs/api/classes/combiner/worklistmaintainerimpl/#afe3f48a41bbbfc79a0c7160865d61ea9">llvm::Combiner::WorkListMaintainerImpl&lt; Lvl &gt;::addUsersToWorkList</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a8affa4b2a934ff08aa04e63253a00126">llvm::RegisterOperands::adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#ac35fef2aafb20ef4b079d0819394e87d">llvm::RegAllocBase::allocatePhysRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a7483a2fa0354b8fa3298ab99f41ce0d4">llvm::VirtRegMap::assignVirt2Phys</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a1ae60b2416ed4d106a241c6874c1992d">llvm::VirtRegMap::assignVirt2StackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#aff9636d75b520f38c5860a95791331c8">llvm::VirtRegMap::assignVirt2StackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#ab07fa640d6b044c04371e8cc8bde6a02">attemptDebugCopyProp</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76a671b685940387f88a924858a371d4">llvm::SIInstrInfo::buildExtractSubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a41d64a5fd52ca16e16ee50f916ab845a">canCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a8a77823ca1d474b22f9b923674749a14">canCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#ae77d286780a8c426db7adb6c10b9a643">canCombineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a848f5b2d82a5d809fe4785b96e6bdb95">canFoldCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmacrofusion-cpp-/#a148883092b4d2dfdc994bc095ec153d7">anonymous{PPCMacroFusion.cpp}::checkOpConstraints</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a2d25688d9c61100ba6a5dea48771ecde">llvm::VirtRegMap::clearVirt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6b1057a57ff0d013cd3a78bb69f43db2">cloneInstr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a8853b2033702691c17576d5acc430460">anonymous{PPCMIPeephole.cpp}::collectUnprimedAccPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a01fce66601f12ad1b3bd219ff02c3426">llvm::VirtRegAuxInfo::copyHint</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a8be157bc7b2bed40b10198e8b6a2bfcf">anonymous{PPCMIPeephole.cpp}::eligibleForCompareElimination</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a6f318a4b1d38e66b324c0748304e60de">llvm::ARMBaseRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a3098f3c7fe942574303f81224b526094">llvm::R600TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a6b20576c7fe76b2d05f77b4d9d5005c6">llvm::ThumbRegisterInfo::emitLoadConstPool</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2e99e64e510ba34954d7fe85b1e30119">llvm::PPCTargetLowering::EmitPartwordAtomicBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a4c17381dc1cacb65f1dd6d31d15100e0">emitThumbRegPlusImmInReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktaggingprera-cpp-/aarch64stacktaggingprera/#a7e7be476481e8e24c35c332a9e6e26ad">anonymous{AArch64StackTaggingPreRA.cpp}::AArch64StackTaggingPreRA::findFirstSlotCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a13ac240bf32d04a19ef44ba47f40407c">findRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#acced35ebfd644d56dc0bcc060bb1bd8d">llvm::SystemZInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a64505b70265bcadc4993631d532a5fd5">llvm::AArch64InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aba962e46a3ab42206182058420cb876f">llvm::SIInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#acf5910da93c4e01390c1e29b4a72836f">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldShiftedOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#af64fc386f3fc81f753830641399254b9">genFNegatedMAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad7dacfdd99d94fce20ccc2450bf5eb76">genFusedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6893512d8a2c2aaf9d6758440d1bc583">genMaddR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsoptimizepiccall-cpp/#a5f4001f2227b1489a7588246ba7c8d54">getCallTargetRegOpnd</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a9a70d4969d8d43a9c9b324f692bc8ecd">llvm::BitTracker::MachineEvaluator::getCell</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a01bc1ea0c681b4b2c171cc164805cf5a">getCopyRegClasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a827d52327fbe1bd7bf22242e7c18847d">getDefRegMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a8e3ebf47bfdde7c6ce8235ca71190e1b">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getFinalVRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0df98b068b652d32c3529381db723b9c">llvm::PPCInstrInfo::getFMAPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a56884e76d8fbf3b9f59ed904d50ba245">getFMULPatterns</a>, <a href="/web-llvm/docs/api/structs/llvm/machineinstrexpressiontrait/#a3344d356ddabbe21340a4b078300a789">llvm::MachineInstrExpressionTrait::getHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a339e0ad5e938860dcbd0c510ce212c4b">getIndVarInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#abb21f77ed3dc15eb330b93b3efaa94ba">llvm::AMDGPURegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#af22048866afa263f60942281802899e5">getLanesWithProperty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#ad17df702dc2863df688cbe4b9d7fe0ba">getLanesWithProperty</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0c35b9011bab80878520faf9afcd601a">llvm::SIInstrInfo::getLiveRangeSplitOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a785a4e2daf4e5bf3f0836adbc4fb7e65">llvm::VirtRegMap::getPhys</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a8bc629292d5cf14604e9b35b42ac4706">llvm::MachineRegisterInfo::getRegAllocationHint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#aae2826c4edd4248c272fa91a0a3e80f6">llvm::MachineRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a09a1c19b999c807cb52c21541a2c7de4">llvm::PPCRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#afc99d2835eb4b8cde9e81db9abca597c">llvm::TargetRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a64ee9ca87205e764e0382240030f87ee">llvm::BitTracker::MachineEvaluator::getRegBitWidth</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a3cb505493f51b96cbb394d89b93f686e">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::getRegSeqInit</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a5bdec6932a16e4d542bd8773fcb50acb">llvm::VirtRegMap::getShape</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a021a3cabd072c6984bf30b0f8a3fc0a6">llvm::MachineRegisterInfo::getSimpleHint</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a32846fd2d98022e7b336962f85411a42">llvm::VirtRegMap::getStackSlot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7ca6bbc21c19a9a6b005aff44ca8562f">llvm::getVRegSubRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#acc4b9161e5bdda1e0f5482ad8b9a64ba">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#aaa5ecbb121a4af66e98e1ddbff7b925d">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a4af3414dbf16e5eb1b862c7cf35ed83c">llvm::VirtRegMap::hasPreferredPhys</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab7919507c578187e698ff01a1f204478">llvm::RISCVInstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6034cfb230c4698caa60bdc3a9bf209b">llvm::TargetInstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp/#a9de31756d24ba6d5dbe75c2d425720d4">hasSameValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonpeephole-cpp/#a75858997548ce7f9cc07ce26843356c6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a474e65b5df97bf9cf404aa9b85eb6262">llvm::RegPressureTracker::initLiveThru</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a58db20676cb0ff354eca34b86f0c3ab1">isAGPRCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a1403d0f29e96c05811fe277c8c68eae6">llvm::WebAssembly::isChild</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#acfdb7e9be44e0d08b3b97b9177b8239e">isCopyFeedingInvariantStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aab9a96f10af025498520e00ff044bec1">llvm::MachineInstr::isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a4ad934d9334200ff676c9568774206cd">isLibCallInTailPosition</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ab671544f7af287b25a5e612f6e919975">llvm::TargetInstrInfo::isReallyTriviallyReMaterializable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#a7b61861295f70647f6dd85931782b93d">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#a333d3161d9b4420d11b777bd154148bf">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastpretileconfig-cpp/#a615f09a9d7f696517872c55ae51e0f58">isTileRegDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#adf3ae590ab5d562772498428b6ad8e60">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::isTransparentCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#a544e5e236fec930c7f0478c3f6e3b43e">isVirtualRegisterOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#ab527804ff82cb87d1229cbec56e95778">IsWritingToVCCR</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09787033a63326e79a0d1445d3e0de13">llvm::SIInstrInfo::legalizeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae63198baedfab72494f0d79823e99b75">llvm::AMDGPULegalizerInfo::loadInputValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aef098c9f09dc6ea1e32e64d79091a237">llvm::AArch64InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abe4a49e8ceb6213fe44eb0ebc9869eb1">llvm::SIInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/#a24fbb3a26fc0fcefed74db2072222bb5">anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::lookThroughCRCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a965fc42d34bd3c15f23cd8cfd31d6ad6">llvm::TargetRegisterInfo::lookThruCopyLike</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a56f7f2867c8f943ceb672823c013df28">llvm::TargetRegisterInfo::lookThruSingleUseCopyChain</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#aff4b98ad5bdf4630720ecebfeb5253bd">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::lowerSpecialCase</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#a5c8e1e68d0b79b7c31776fa78023d667">llvm::LiveDebugVariables::LDVImpl::mapVirtReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a313bdf934f1f8454b6800d8d997801d2">MatchingStackOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a8767a2aae4c035e715b572ce4b4c5acd">llvm::BitTracker::RegisterCell::meet</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#adbc2dabbd1e76342acf894af01937c8a">oneUseDominatesOtherUses</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af0bbac5dd9f698f2c73477c4e5f36b60">llvm::AArch64InstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a680a4b1885f1217b238bbada1e936512">llvm::Thumb2InstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/constgeneration/#ad75859c9c313d495322193cbaece6246">anonymous{HexagonBitSimplify.cpp}::ConstGeneration::processBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a62a1e2af50ab6132cd2d8d168835ef57">llvm::PPCInstrInfo::promoteInstr32To64ForElimEXTSW</a>, <a href="/web-llvm/docs/api/classes/llvm/psetiterator/#a592bf3df803ffac98c7328a523769bac">llvm::PSetIterator::PSetIterator</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a8944fc547212f985ad3f9706eb5b8725">llvm::BitTracker::MachineEvaluator::putCell</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a126f33e8085746e4f69b4411b61102dc">llvm::RegPressureTracker::recede</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#afb605ebf6dc090e58e5d3dd1a9125d33">regIsPICBase</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a4c5b93703bfd35ff033b6fd30c2b8ee7">llvm::WebAssemblyAsmPrinter::regToString</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#ac3f3d9a5627dfe20e78c7c97be2f994f">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::replaceReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#afe35af7dba73067927cded21f9d9cbed">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::replaceRegWithSub</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a8d428a5da0576a43b8ddc27e32c313f0">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::replaceSubWithSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mircanonicalizerpass-cpp/#aed1c1aa1329f36eef4940283a1d30859">rescheduleCanonically</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a70e16ebf8bd9b6d4b89331190206e635">resultDependsOnExec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructions/#a2d4969e8e07a8085b166f5b83efc5a8c">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmaskingprera-cpp-/sioptimizeexecmaskingprera/#a7e75a4f6568424bf0940a7c509a6d18c">anonymous{SIOptimizeExecMaskingPreRA.cpp}::SIOptimizeExecMaskingPreRA::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#ad24ed71e13d2eb4173a1efeefb659dc2">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setAVLRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a8e27d94e24a9bc2d6c7d719bed9637e3">llvm::MachineRegisterInfo::setRegAllocationHint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a4214f202c6a3b5b3933489a6edc49b6b">llvm::MachineRegisterInfo::shouldTrackSubRegLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcregisterinfo-cpp/#aaa14cbf6168e04cf996c5ab314430bb5">spillRegPairs</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a92e31a04c0a1b5d17db90c99fa48f6aa">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::splitTwoPartImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aeba4e73d60d1b4cedc120d06114c0620">llvm::AArch64InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6ec207a1c12adfc61c6566436e5a2cd7">llvm::SIInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3e0753735e274deee756f4b8961b88b2">llvm::Thumb2InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a7c8714527422f164b52d6daaa65850e8">tryChangeVGPRtoSGPRinCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a3eb465a2b7eef72ebd92bf15445c5903">llvm::LegalizationArtifactCombiner::tryCombineInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#ac9ca747a6b6297f53d182bfe78514963">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldFoldableCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a2e4e7b801f3b166aebe037d065fa6923">llvm::ARMBaseRegisterInfo::updateRegAllocHint</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a1f6067626e3318b8569835d83acbd92e">llvm::SIInstrInfo::usesConstantBus</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa4f08d12a02cc1685e8ea788f818ac1a">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSviGPR</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa54146eb85b736f6f42bba1e44963eb7">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitORR</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a>.</p>

</div>
</div>

### virtRegIndex() {#a5f34bdaea90f8ee41a43a83a0c0e3b4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Register::virtRegIndex ()</td>
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

<p>Convert a virtual register number to a 0-based index.</p>


<p>The first virtual register in a function will get the index 0.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="#a4df23dddc646b6a4b36ff483063a4ff8">virtReg2Index</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Reg {#aea4861d48b32ce99043495fa6972a17b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Register::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### index2StackSlot() {#a92cd11abfd541caadc1fc825b78f9903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::Register::index2StackSlot (int FI)</td>
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

<p>Convert a non-negative frame index to a stack slot register value.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#aa1488905836839f8cd3600810410ae61">llvm::MCRegister::FirstStackSlot</a>, <a href="#a228e680d10a53c933898d03cc834e5a0">Register</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/livestacks/#a77ec673a7fde73e91e8fa6be83a82b01">llvm::LiveStacks::getOrCreateInterval</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#a112859e582ad6783c922bac9f63d377c">llvm::rdf::PhysicalRegisterInfo::getRegMaskId</a>.</p>

</div>
</div>

### index2VirtReg() {#a1979c563289f871907832e419889f979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::Register::index2VirtReg (unsigned Index)</td>
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

<p>Convert a 0-based index to a virtual register number.</p>


<p>This is the inverse operation of <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor">VirtReg2IndexFunctor</a> below.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a228e680d10a53c933898d03cc834e5a0">Register</a> and <a href="/web-llvm/docs/api/classes/llvm/mcregister/#aeaac7abf0e2e4881cc7158ab6cdb0019">llvm::MCRegister::VirtualRegFlag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixirreduciblecontrolflow-cpp/#a0cad575df04ef66a39c5d0d0501cf267">addImplicitDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#afbcff91139fc89e3e8c0dda857e7b128">llvm::LiveVariables::addNewBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#afc347ae9e7fcba69b04162d7b4a73635">llvm::LiveVariables::addNewBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#abc82dfed5cd6e963934d2d0f8d6e7272">llvm::MachineRegisterInfo::addRegAllocationHint</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a394261440649abcae4183f645af90a6d">llvm::VirtRegAuxInfo::calculateSpillWeightsAndHints</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a7e2e403e3e1f758b87c25302090c96c2">llvm::MachineRegisterInfo::clearVirtRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/deadlanedetector/#a1a88b4246b710c6aa48b42fe8c912fd3">llvm::DeadLaneDetector::computeSubRegisterLaneBitInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#ae0bc43ffc97603d2acaf34479afbe0c8">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a7ed74de0e85d45f32fe8aca572f0c63d">llvm::MachineRegisterInfo::createIncompleteVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa5ee374b5dd8bd37ca7876c4bfb24bbf">llvm::SITargetLowering::finalizeLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalize-cpp/#a7d4da10beff712762d6e9ebbf51b339a">getAnySgprS1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acaa1b5dff8de1c3bc2e3e9fee3ef7459">llvm::getLiveRegMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62ab92d2e2752422a6a0995188d64b77">llvm::getLiveRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/spirv/moduleanalysisinfo/#a636ee8de87b2754d3a2a3d0733e0120f">llvm::SPIRV::ModuleAnalysisInfo::getOrCreateMBBRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#a597bb5d7ef9a22f44dbe867d8eaa7fd6">anonymous{InlineSpiller.cpp}::HoistSpillHelper::hoistAllSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp/#a3739959eaa5952384fc45bcc0d9a92da">isSSA</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ae7cde99972870aa99be89218096b3ccf">llvm::LiveIntervals::print</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a78798d8de583a196655b3cfb347da991">llvm::LiveVariables::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af33634fb6c71e0e2e25241c94baf8c26">llvm::print</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a7fa4b2ab2c4e30ebbb80c8384dc9ddd3">llvm::VirtRegMap::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-phielimination-cpp-/phieliminationimpl/#aab3db5c9e390ca00331b7d432c735dcd">anonymous{PHIElimination.cpp}::PHIEliminationImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnpreraoptimizations-cpp-/gcnpreraoptimizations/#a579b1d5abab1d9f7ada407f49d3a56a1">anonymous{GCNPreRAOptimizations.cpp}::GCNPreRAOptimizations::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnrewritepartialreguses-cpp-/gcnrewritepartialreguses/#adf18d032626767c9b0590624712d3ac1">anonymous{GCNRewritePartialRegUses.cpp}::GCNRewritePartialRegUses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-renameindependentsubregs-cpp-/renameindependentsubregs/#a5a7168c10662c11aea9894ec2b7481bb">anonymous{RenameIndependentSubregs.cpp}::RenameIndependentSubregs::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ac27e962fff6fda4c4419bc22281f38dd">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/x86domainreassignment/#acab3ec701472799353f6542ba0affd6a">anonymous{X86DomainReassignment.cpp}::X86DomainReassignment::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a8e27d94e24a9bc2d6c7d719bed9637e3">llvm::MachineRegisterInfo::setRegAllocationHint</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a024479869943dfba001bb5701d62a243">llvm::SIMachineFunctionInfo::usesAGPRs</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a42f45acfa351a67ac2975773261005d7">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveIntervals</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a3f673ecaaa953b4589aa7d0f5f2320bb">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveVariables</a> and <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a12fa9d44c84f7cadd81bf4758a22e1e9">llvm::MachineRegisterInfo::verifyUseLists</a>.</p>

</div>
</div>

### isPhysicalRegister() {#afacc26f29d80e10be4785a96ed6444dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::Register::isPhysicalRegister (unsigned Reg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified register number is in the physical register namespace.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a59fff9e18d767c9e62ab37b4b87830bd">llvm::MCRegister::isPhysicalRegister</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a396ce0a5b70320d155c9959a080d543f">llvm::ARMBaseInstrInfo::AddDReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c5e19523172e41e6a320be6fd748e17">llvm::calculateDbgEntityHistory</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonnewvaluejump-cpp/#a364fb004e57163fc1a3e2adc754af9b1">canCompareBeNewValueJump</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a5184df56e270750a839acad50a1b8501">llvm::SelectionDAGBuilder::CopyValueToVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#a97c8d0c6028ffa258758bd49f68f2e28">llvm::M68kRegisterInfo::getMaximalPhysRegClass</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/copypropagation/#ab12951430f2984b5f0b26e265ccb8ac7">llvm::rdf::CopyPropagation::interpretAsCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a661b945147a53ef2ecf91646a481e67c">isEvenReg</a>, <a href="#affdbf5b92ed7e01352e2f39466efbe21">isPhysical</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a987ae88dea5396b51031fe9a52d8388a">llvm::rdf::RegisterRef::isRegId</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad04f609cdff2331741525e5328836598">llvm::GenericScheduler::reschedulePhysReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a59b6a751c071a2b0a6c3d5617fb83719">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### isStackSlot() {#a050c8e969ce1fa8c229b074fd07be925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::Register::isStackSlot (unsigned Reg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isStackSlot - Sometimes it is useful to be able to store a non-negative frame index in a variable that normally holds a register.</p>


<p><a href="#a050c8e969ce1fa8c229b074fd07be925">isStackSlot()</a> returns true if Reg is in the range used for stack slots.</p>


<p>FIXME: remove in favor of member.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a01c52fcd65bb831db823ecd35cf0a3ba">llvm::MCRegister::isStackSlot</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a7a6e00a1aed89e42fd185379d3309666">llvm::rdf::RegisterRef::isMaskId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a> and <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/inlinespiller/#af74cc1b6ed58474b37bafc059339a964">anonymous{InlineSpiller.cpp}::InlineSpiller::spill</a>.</p>

</div>
</div>

### isVirtualRegister() {#ac6bf744f357352cde7578931007c0b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::Register::isVirtualRegister (unsigned Reg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified register number is in the virtual register namespace.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcregister/#aeaac7abf0e2e4881cc7158ab6cdb0019">llvm::MCRegister::VirtualRegFlag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#a73e723a22ad556552ca99f7e7a90a780">llvm::RegsForValue::AddInlineAsmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#aada0fcd484288f5ec37cd301cd7c100b">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::addMItoCopyList</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv/#ad73f79350d54fe535469c4a148943e3a">anonymous{EarlyIfConversion.cpp}::SSAIfConv::canConvertIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aef21a685c4183683271cbaa741991f12">canFoldIntoCSel</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#a7d574da13bc65b93810a42059eada04f">CheckForPhysRegDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ae7e825d2af275c631d66e063c4eff615">llvm::ScheduleDAGSDNodes::computeOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstrinfo/#a9eb8b24be429abb7d52e2f41f9923e08">llvm::WebAssemblyInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinetracemetrics-cpp-/datadep/#aa00496b615b9f981c925d33e5c6b54e2">anonymous{MachineTraceMetrics.cpp}::DataDep::DataDep</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#af30edca8f8a971b32190acd67f8dbd1d">definedBySignExtendingOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#a0c84571aa2288f85c80d91fe64f97926">definedByZeroExtendingOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcoptaddrmode-cpp/#a488daa300aea64109710b4e2fe0cbc44">dominatesAllUsesOf</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a03ab338e9e5f4ea24b2049ab525525bf">llvm::FastISel::fastEmitInst_extractsubreg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a64505b70265bcadc4993631d532a5fd5">llvm::AArch64InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6893512d8a2c2aaf9d6758440d1bc583">genMaddR</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#ad782fe84b36a1c379ac9f1ac367706e1">llvm::RegsForValue::getCopyFromRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a923798c288aeebf99a43eb7191492fe2">getLiveRange</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#aff059e4f5e8216de3172acd39a6e0ff8">anonymous{PPCMIPeephole.cpp}::getSrcVReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#afb944a33b354e4709fb99864f82b9c16">if</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#ac67ddee154305e17ed2acb0303fe4f80">isFPR64</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxcopy-cpp-/ppcvsxcopy/#a32193820add51ccf1ce4a89b83ea3cc8">anonymous{PPCVSXCopy.cpp}::PPCVSXCopy::IsRegInClass</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a78b9ad4b9b246aab32ff14d856f5769a">llvm::PPCInstrInfo::isSignOrZeroExtended</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#aaaa495ab731d5c7de060f932c8bbc869">llvm::rdf::RegisterRef::isUnitId</a>, <a href="#ab203bbcbc320180b1da9e9a92ee0c784">isVirtual</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit/#a18e324aefc6383c44d175158f5954246">llvm::VirtRegOrUnit::isVirtualReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/#a24fbb3a26fc0fcefed74db2072222bb5">anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::lookThroughCRCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#ab268a162e6da94b8012d8366563ae9f7">MatchingStackOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a788c5905de970028eb0efa2266bd10bf">llvm::printVRegOrUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a18f4a66d99dba4cf2a2c1054d796cf9c">removeCopies</a>, <a href="/web-llvm/docs/api/classes/anonymous-avriseldagtodag-cpp-/avrdagtodagisel/#af1389c2a1baf930223956103b615a838">anonymous{AVRISelDAGToDAG.cpp}::AVRDAGToDAGISel::SelectInlineAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp/#aeb309e71b02f8298a437ec465645fe99">stripValuesNotDefiningMask</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregorunit/#a3788ce750e38720430876f7b339a36e8">llvm::VirtRegOrUnit::VirtRegOrUnit</a>.</p>

</div>
</div>

### stackSlot2Index() {#a47caf9a25186eed2215d13171af1f3ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::Register::stackSlot2Index (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Compute the frame index from a register value representing a stack slot.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#aa1488905836839f8cd3600810410ae61">llvm::MCRegister::FirstStackSlot</a> and <a href="#a228e680d10a53c933898d03cc834e5a0">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#a0b41fbff427a806361170cffabc62e41">llvm::rdf::PhysicalRegisterInfo::getMaskUnits</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#a7ed460e206904e6731fb5a812a74d874">llvm::rdf::PhysicalRegisterInfo::getRegMaskBits</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#a35ed7153814f84233fc75351452cf30c">llvm::rdf::PhysicalRegisterInfo::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#adb457e87e019538757ec91bec7a7e5f0">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::runOnMachineFunction</a>.</p>

</div>
</div>

### virtReg2Index() {#a4df23dddc646b6a4b36ff483063a4ff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Register::virtReg2Index (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Convert a virtual register number to a 0-based index.</p>


<p>The first virtual register in a function will get the index 0.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a228e680d10a53c933898d03cc834e5a0">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyexplicitlocals-cpp/#a6f95f7127e378cb5b033191ab8cf2286">checkFrameBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmccodeemitter-cpp/#a4d70c868bafbd7d427233717f0738f87">emitOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/vregfilter/#a7e8736b28b4391ab04842fa61209e86b">anonymous{MachineVerifier.cpp}::VRegFilter::filterAndAdd</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktaggingprera-cpp-/aarch64stacktaggingprera/#a7e7be476481e8e24c35c332a9e6e26ad">anonymous{AArch64StackTaggingPreRA.cpp}::AArch64StackTaggingPreRA::findFirstSlotCandidate</a>, <a href="/web-llvm/docs/api/structs/llvm/vreg2sunit/#a8888c23f68696106ebdc5a796f330f49">llvm::VReg2SUnit::getSparseSetIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#a3277254e3876da271eac5f78dd9cab50">llvm::WebAssemblyFunctionInfo::getWAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#a06bf1d7d3fad0e5185a4ff892c7ad4a5">llvm::WebAssemblyFunctionInfo::isVRegStackified</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/cellmapshadow/#a8a81ab6db58a045800b4b0c35b44c4e3">anonymous{HexagonGenInsert.cpp}::CellMapShadow::lookup</a>, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor/#a02caf38e654ee6b238b90b465fee7a7c">llvm::VirtReg2IndexFunctor::operator()</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-bittracker-cpp-/#a4327563820fb30c4c4102882f7b56215">anonymous{BitTracker.cpp}::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#a27c4a87f88c20ac4710c4e092dadb6fb">llvm::SPIRVInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a788c5905de970028eb0efa2266bd10bf">llvm::printVRegOrUnit</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagongeninsert-cpp-/hexagongeninsert/#a37b356976dd89ab9dc3212616667218e">anonymous{HexagonGenInsert.cpp}::HexagonGenInsert::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ac27e962fff6fda4c4419bc22281f38dd">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a9029683bf2a81e8247c168501e85a8b4">scavengeFrameVirtualRegsInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#a6c521472c6da6834fae5613839fc5ef9">llvm::WebAssemblyFunctionInfo::setWAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#aad1e6bd59a78c4d3a467566dc6a0eb27">llvm::WebAssemblyFunctionInfo::stackifyVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/deadlanedetector/#a0507a9e0fb3ad8b5cbe21a6f19c8714c">llvm::DeadLaneDetector::transferUsedLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#aa870a43262a6c6954f59b6febc736ab5">llvm::WebAssemblyFunctionInfo::unstackifyVReg</a> and <a href="#a5f34bdaea90f8ee41a43a83a0c0e3b4c">virtRegIndex</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">Register.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
