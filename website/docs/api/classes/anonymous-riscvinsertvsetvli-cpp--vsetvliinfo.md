---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VSETVLIInfo` Class Reference

<p>Defines the abstract state with which the forward dataflow models the values of the VL and VTYPE registers after insertion. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint8_t { <a href="#aadc74c9a58007dc1be930751e5502485">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93bf89ac71202629a6786d6491092131">operator==</a> (const VSETVLIInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1390d3fa43ef94e63f8415a20aa9649e">operator!=</a> (const VSETVLIInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab493b5628399b1140af4094f7af919e">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement operator&lt;&lt;. <a href="#aab493b5628399b1140af4094f7af919e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9d47a4e0577208cd4d6cfc3bde38e7e">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb2f8d2efedfc2ef075a1824c4221c2c">setUnknown</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c94f3aa009a794f71dadd0b090d806">isUnknown</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad24ed71e13d2eb4173a1efeefb659dc2">setAVLRegDef</a> (const VNInfo *VNInfo, Register AVLReg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f75ef7051a0287b38299a80a1972909">setAVLImm</a> (unsigned Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2722afd1903d75b7ab12c8700473e9e">setAVLVLMAX</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace9a2e84c6d6f036b3865aabc6c58265">hasAVLImm</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08929f8cb7f9823f29a79053bb05652d">hasAVLReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2b4ce7e30b9b88a3bc647d0ede1033b">hasAVLVLMAX</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34228acc92d686ec244da04ce11a76d4">getAVLReg</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a37225cf903ed6441d2581f100aaf61">getAVLImm</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a7bdf8814caff1865de7ae998d0ad7b">getAVLVNInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58659e9d9d29818cd6d0ad0d4abbd107">getAVLDefMI</a> (const LiveIntervals *LIS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a195c20c058576ca52259e33600717fcb">setAVL</a> (const VSETVLIInfo &amp;Info)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a0d3c45d1c15e0603be01779ba0ae7">getSEW</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1c">RISCVII::VLMUL</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5349f842c35c8f29fabedcc3dc30fe2">getVLMUL</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168a213dbf66e66f732831d62bb8d007">getTailAgnostic</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b83340c879e61707be7df63f0be1cea">getMaskAgnostic</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b9c5d8f1e5e26cc1a93b263a223cbe5">hasNonZeroAVL</a> (const LiveIntervals *LIS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0a1d82035f4548bb2ca4c31d1d6b138">hasEquallyZeroAVL</a> (const VSETVLIInfo &amp;Other, const LiveIntervals *LIS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0511dde9405ade74332c3c7505a41fd7">hasSameAVLLatticeValue</a> (const VSETVLIInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e3c33515538e1c3dcfd49d6fa1f6466">hasSameAVL</a> (const VSETVLIInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4ed778e7cf004e26e2bd53b5b5de8a1">setVTYPE</a> (unsigned VType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7715801da0e918c5f258f40246742a1a">setVTYPE</a> (RISCVII::VLMUL L, unsigned S, bool TA, bool MA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a180903db6abbec26172d57dfc24e608a">setVLMul</a> (RISCVII::VLMUL VLMul)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3af1ce05932756a9695dbe24512cb40e">encodeVTYPE</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7716dc1a76110d4ec9afcee188c2f3fb">hasSEWLMULRatioOnly</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2b86fba641fa9cf7caaf314b2dc9b49">hasSameVTYPE</a> (const VSETVLIInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78b447d6a130e6102f95a35c58bef9e">getSEWLMULRatio</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3428818c38247f58e3b497e10d49df12">hasSameVLMAX</a> (const VSETVLIInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e698ea29321753719288e1308a3746e">hasCompatibleVTYPE</a> (const DemandedFields &amp;Used, const VSETVLIInfo &amp;Require) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2c46f20e8b768f86d9bbc78c610defc">isCompatible</a> (const DemandedFields &amp;Used, const VSETVLIInfo &amp;Require, const LiveIntervals *LIS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo">VSETVLIInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8b853a0e5f59f4df074f6ca1f6215cd">intersect</a> (const VSETVLIInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238a21f94d9186543c9d7656c55837fb">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support for debugging, callable in GDB: V-&gt;<a href="#a238a21f94d9186543c9d7656c55837fb">dump()</a> <a href="#a238a21f94d9186543c9d7656c55837fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">AVLDef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5b7a96d251b7b94d3080770cc91fcd8">AVLRegDef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe9fc29b991e5aaaae8e223ed59957dc">AVLImm</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{RISCVInsertVSETVLI.cpp}<a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">::VSETVLIInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5607fbe4c7cde00d77fde1c24649e3a0"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{RISCVInsertVSETVLI.cpp}<a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">::VSETVLIInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9570b622fe5bb4d1334f410f40a5e515">State</a> = Uninitialized</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1c">RISCVII::VLMUL</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61473febcf33944e68b8893f67251f2b">VLMul</a> = RISCVII::LMUL_1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51806bfb8d4d8c5fd80b612221702511">SEW</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdeb47db2ae9607b92adbbbefaf57dad">TailAgnostic</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2559b37433c094f83782c73059f00b4f">MaskAgnostic</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9835f24b04ece5dd2d0da5f8cd59250">SEWLMULRatioOnly</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo">VSETVLIInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac905849b67c47f11df62568e7e5ffbbe">getUnknown</a> ()</td>
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

<p>Defines the abstract state with which the forward dataflow models the values of the VL and VTYPE registers after insertion.</p>

<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#aadc74c9a58007dc1be930751e5502485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint8_t</td>
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
<td class="doxyEnumItemName">Uninitialized<a id="aadc74c9a58007dc1be930751e5502485abd41c35a79b441f52b9d28b646fb3e7a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVLIsReg<a id="aadc74c9a58007dc1be930751e5502485a4b3039c1391730401bf56878c376ccad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVLIsImm<a id="aadc74c9a58007dc1be930751e5502485a0337ae3ba42996ae983e686b6fdb756a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVLIsVLMAX<a id="aadc74c9a58007dc1be930751e5502485a82d442080c3f8184475324802273a552"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unknown<a id="aadc74c9a58007dc1be930751e5502485aa041e8e7a087bb1d6799daf9e1008584"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VSETVLIInfo() {#ae9ac2063456ee6f8d62ff1b0ccf41ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::VSETVLIInfo ()</td>
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



<p>Definition at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Reference <a href="#abe9fc29b991e5aaaae8e223ed59957dc">AVLImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp/#a29c512a9a215945f15f473648f57537c">adjustIncoming</a>, <a href="#ac905849b67c47f11df62568e7e5ffbbe">getUnknown</a>, <a href="#a3e698ea29321753719288e1308a3746e">hasCompatibleVTYPE</a>, <a href="#ac0a1d82035f4548bb2ca4c31d1d6b138">hasEquallyZeroAVL</a>, <a href="#a3e3c33515538e1c3dcfd49d6fa1f6466">hasSameAVL</a>, <a href="#a0511dde9405ade74332c3c7505a41fd7">hasSameAVLLatticeValue</a>, <a href="#a3428818c38247f58e3b497e10d49df12">hasSameVLMAX</a>, <a href="#ab2b86fba641fa9cf7caaf314b2dc9b49">hasSameVTYPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp/#aeab9aaa0283d5249c25d93393677af94">INITIALIZE_PASS</a>, <a href="#ac8b853a0e5f59f4df074f6ca1f6215cd">intersect</a>, <a href="#af2c46f20e8b768f86d9bbc78c610defc">isCompatible</a>, <a href="#a1390d3fa43ef94e63f8415a20aa9649e">operator!=</a>, <a href="#a93bf89ac71202629a6786d6491092131">operator==</a> and <a href="#a195c20c058576ca52259e33600717fcb">setAVL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a1390d3fa43ef94e63f8415a20aa9649e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo">VSETVLIInfo</a> &amp; Other)</td>
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



<p>Definition at line 816 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a>.</p>

</div>
</div>

### operator==() {#a93bf89ac71202629a6786d6491092131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo">VSETVLIInfo</a> &amp; Other)</td>
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



<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="#a0511dde9405ade74332c3c7505a41fd7">hasSameAVLLatticeValue</a>, <a href="#a3428818c38247f58e3b497e10d49df12">hasSameVLMAX</a>, <a href="#ab2b86fba641fa9cf7caaf314b2dc9b49">hasSameVTYPE</a>, <a href="#a41c94f3aa009a794f71dadd0b090d806">isUnknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### print() {#aab493b5628399b1140af4094f7af919e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Implement operator&lt;&lt;.</p>

<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="#abe9fc29b991e5aaaae8e223ed59957dc">AVLImm</a>, <a href="#a34228acc92d686ec244da04ce11a76d4">getAVLReg</a>, <a href="#ace9a2e84c6d6f036b3865aabc6c58265">hasAVLImm</a>, <a href="#a08929f8cb7f9823f29a79053bb05652d">hasAVLReg</a>, <a href="#af2b4ce7e30b9b88a3bc647d0ede1033b">hasAVLVLMAX</a>, <a href="#a41c94f3aa009a794f71dadd0b090d806">isUnknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a238a21f94d9186543c9d7656c55837fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::dump ()</td>
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

<p>Support for debugging, callable in GDB: V-&gt;<a href="#a238a21f94d9186543c9d7656c55837fb">dump()</a></p>

<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### encodeVTYPE() {#a3af1ce05932756a9695dbe24512cb40e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::encodeVTYPE ()</td>
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



<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#ad3636219b4d0045029530c6a16c160dc">llvm::RISCVVType::encodeVTYPE</a>, <a href="#a41c94f3aa009a794f71dadd0b090d806">isUnknown</a> and <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>.</p>


<p>Referenced by <a href="#a3e698ea29321753719288e1308a3746e">hasCompatibleVTYPE</a>.</p>

</div>
</div>

### getAVLDefMI() {#a58659e9d9d29818cd6d0ad0d4abbd107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr * anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::getAVLDefMI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS)</td>
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



<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8a7bdf8814caff1865de7ae998d0ad7b">getAVLVNInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a1882fe2a570964e4c6abb0eac322beab">llvm::LiveIntervals::getInstructionFromIndex</a>, <a href="#a08929f8cb7f9823f29a79053bb05652d">hasAVLReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a9b9c5d8f1e5e26cc1a93b263a223cbe5">hasNonZeroAVL</a>.</p>

</div>
</div>

### getAVLImm() {#a3a37225cf903ed6441d2581f100aaf61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::getAVLImm ()</td>
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



<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abe9fc29b991e5aaaae8e223ed59957dc">AVLImm</a> and <a href="#ace9a2e84c6d6f036b3865aabc6c58265">hasAVLImm</a>.</p>


<p>Referenced by <a href="#a9b9c5d8f1e5e26cc1a93b263a223cbe5">hasNonZeroAVL</a> and <a href="#a0511dde9405ade74332c3c7505a41fd7">hasSameAVLLatticeValue</a>.</p>

</div>
</div>

### getAVLReg() {#a34228acc92d686ec244da04ce11a76d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::getAVLReg ()</td>
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



<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af5b7a96d251b7b94d3080770cc91fcd8">AVLRegDef</a> and <a href="#a08929f8cb7f9823f29a79053bb05652d">hasAVLReg</a>.</p>


<p>Referenced by <a href="#a0511dde9405ade74332c3c7505a41fd7">hasSameAVLLatticeValue</a> and <a href="#aab493b5628399b1140af4094f7af919e">print</a>.</p>

</div>
</div>

### getAVLVNInfo() {#a8a7bdf8814caff1865de7ae998d0ad7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VNInfo * anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::getAVLVNInfo ()</td>
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



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af5b7a96d251b7b94d3080770cc91fcd8">AVLRegDef</a> and <a href="#a08929f8cb7f9823f29a79053bb05652d">hasAVLReg</a>.</p>


<p>Referenced by <a href="#a58659e9d9d29818cd6d0ad0d4abbd107">getAVLDefMI</a>, <a href="#a3e3c33515538e1c3dcfd49d6fa1f6466">hasSameAVL</a> and <a href="#a0511dde9405ade74332c3c7505a41fd7">hasSameAVLLatticeValue</a>.</p>

</div>
</div>

### getMaskAgnostic() {#a9b83340c879e61707be7df63f0be1cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::getMaskAgnostic ()</td>
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



<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

### getSEW() {#aa7a0d3c45d1c15e0603be01779ba0ae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::getSEW ()</td>
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



<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

### getSEWLMULRatio() {#ad78b447d6a130e6102f95a35c58bef9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::getSEWLMULRatio ()</td>
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



<p>Definition at line 741 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#a51c33217fc9f7cae7a19701e421dc70f">llvm::RISCVVType::getSEWLMULRatio</a>, <a href="#a41c94f3aa009a794f71dadd0b090d806">isUnknown</a> and <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>.</p>


<p>Referenced by <a href="#a3428818c38247f58e3b497e10d49df12">hasSameVLMAX</a>.</p>

</div>
</div>

### getTailAgnostic() {#a168a213dbf66e66f732831d62bb8d007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::getTailAgnostic ()</td>
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



<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

### getVLMUL() {#aa5349f842c35c8f29fabedcc3dc30fe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVII::VLMUL anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::getVLMUL ()</td>
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



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

### hasAVLImm() {#ace9a2e84c6d6f036b3865aabc6c58265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasAVLImm ()</td>
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



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a3a37225cf903ed6441d2581f100aaf61">getAVLImm</a>, <a href="#a9b9c5d8f1e5e26cc1a93b263a223cbe5">hasNonZeroAVL</a>, <a href="#a0511dde9405ade74332c3c7505a41fd7">hasSameAVLLatticeValue</a> and <a href="#aab493b5628399b1140af4094f7af919e">print</a>.</p>

</div>
</div>

### hasAVLReg() {#a08929f8cb7f9823f29a79053bb05652d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasAVLReg ()</td>
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



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a58659e9d9d29818cd6d0ad0d4abbd107">getAVLDefMI</a>, <a href="#a34228acc92d686ec244da04ce11a76d4">getAVLReg</a>, <a href="#a8a7bdf8814caff1865de7ae998d0ad7b">getAVLVNInfo</a>, <a href="#a9b9c5d8f1e5e26cc1a93b263a223cbe5">hasNonZeroAVL</a>, <a href="#a3e3c33515538e1c3dcfd49d6fa1f6466">hasSameAVL</a>, <a href="#a0511dde9405ade74332c3c7505a41fd7">hasSameAVLLatticeValue</a> and <a href="#aab493b5628399b1140af4094f7af919e">print</a>.</p>

</div>
</div>

### hasAVLVLMAX() {#af2b4ce7e30b9b88a3bc647d0ede1033b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasAVLVLMAX ()</td>
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



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a9b9c5d8f1e5e26cc1a93b263a223cbe5">hasNonZeroAVL</a>, <a href="#a0511dde9405ade74332c3c7505a41fd7">hasSameAVLLatticeValue</a> and <a href="#aab493b5628399b1140af4094f7af919e">print</a>.</p>

</div>
</div>

### hasCompatibleVTYPE() {#a3e698ea29321753719288e1308a3746e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasCompatibleVTYPE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvinsertvsetvli-cpp-/demandedfields">DemandedFields</a> &amp; Used, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo">VSETVLIInfo</a> &amp; Require)</td>
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



<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#aa4bfcbb7dbb18b0413a59da72b0d4a89">anonymous{RISCVInsertVSETVLI.cpp}::areCompatibleVTYPEs</a>, <a href="#a3af1ce05932756a9695dbe24512cb40e">encodeVTYPE</a> and <a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a>.</p>


<p>Referenced by <a href="#af2c46f20e8b768f86d9bbc78c610defc">isCompatible</a>.</p>

</div>
</div>

### hasEquallyZeroAVL() {#ac0a1d82035f4548bb2ca4c31d1d6b138}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasEquallyZeroAVL (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo">VSETVLIInfo</a> &amp; Other, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS)</td>
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



<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="#a9b9c5d8f1e5e26cc1a93b263a223cbe5">hasNonZeroAVL</a>, <a href="#a3e3c33515538e1c3dcfd49d6fa1f6466">hasSameAVL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a>.</p>


<p>Referenced by <a href="#af2c46f20e8b768f86d9bbc78c610defc">isCompatible</a>.</p>

</div>
</div>

### hasNonZeroAVL() {#a9b9c5d8f1e5e26cc1a93b263a223cbe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasNonZeroAVL (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS)</td>
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



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="#a58659e9d9d29818cd6d0ad0d4abbd107">getAVLDefMI</a>, <a href="#a3a37225cf903ed6441d2581f100aaf61">getAVLImm</a>, <a href="#ace9a2e84c6d6f036b3865aabc6c58265">hasAVLImm</a>, <a href="#a08929f8cb7f9823f29a79053bb05652d">hasAVLReg</a>, <a href="#af2b4ce7e30b9b88a3bc647d0ede1033b">hasAVLVLMAX</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#a3b02021586e4c4af64216058ea171af7">anonymous{RISCVInsertVSETVLI.cpp}::isNonZeroLoadImmediate</a>.</p>


<p>Referenced by <a href="#ac0a1d82035f4548bb2ca4c31d1d6b138">hasEquallyZeroAVL</a>.</p>

</div>
</div>

### hasSameAVL() {#a3e3c33515538e1c3dcfd49d6fa1f6466}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasSameAVL (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo">VSETVLIInfo</a> &amp; Other)</td>
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



<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8a7bdf8814caff1865de7ae998d0ad7b">getAVLVNInfo</a>, <a href="#a08929f8cb7f9823f29a79053bb05652d">hasAVLReg</a>, <a href="#a0511dde9405ade74332c3c7505a41fd7">hasSameAVLLatticeValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a>.</p>


<p>Referenced by <a href="#ac0a1d82035f4548bb2ca4c31d1d6b138">hasEquallyZeroAVL</a>, <a href="#ac8b853a0e5f59f4df074f6ca1f6215cd">intersect</a> and <a href="#af2c46f20e8b768f86d9bbc78c610defc">isCompatible</a>.</p>

</div>
</div>

### hasSameAVLLatticeValue() {#a0511dde9405ade74332c3c7505a41fd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasSameAVLLatticeValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo">VSETVLIInfo</a> &amp; Other)</td>
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



<p>Definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3a37225cf903ed6441d2581f100aaf61">getAVLImm</a>, <a href="#a34228acc92d686ec244da04ce11a76d4">getAVLReg</a>, <a href="#a8a7bdf8814caff1865de7ae998d0ad7b">getAVLVNInfo</a>, <a href="#ace9a2e84c6d6f036b3865aabc6c58265">hasAVLImm</a>, <a href="#a08929f8cb7f9823f29a79053bb05652d">hasAVLReg</a>, <a href="#af2b4ce7e30b9b88a3bc647d0ede1033b">hasAVLVLMAX</a>, <a href="#a3428818c38247f58e3b497e10d49df12">hasSameVLMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a>.</p>


<p>Referenced by <a href="#a3e3c33515538e1c3dcfd49d6fa1f6466">hasSameAVL</a> and <a href="#a93bf89ac71202629a6786d6491092131">operator==</a>.</p>

</div>
</div>

### hasSameVLMAX() {#a3428818c38247f58e3b497e10d49df12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasSameVLMAX (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo">VSETVLIInfo</a> &amp; Other)</td>
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



<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad78b447d6a130e6102f95a35c58bef9e">getSEWLMULRatio</a>, <a href="#a41c94f3aa009a794f71dadd0b090d806">isUnknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a>.</p>


<p>Referenced by <a href="#a0511dde9405ade74332c3c7505a41fd7">hasSameAVLLatticeValue</a>, <a href="#ac8b853a0e5f59f4df074f6ca1f6215cd">intersect</a>, <a href="#af2c46f20e8b768f86d9bbc78c610defc">isCompatible</a> and <a href="#a93bf89ac71202629a6786d6491092131">operator==</a>.</p>

</div>
</div>

### hasSameVTYPE() {#ab2b86fba641fa9cf7caaf314b2dc9b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasSameVTYPE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo">VSETVLIInfo</a> &amp; Other)</td>
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



<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a41c94f3aa009a794f71dadd0b090d806">isUnknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a>.</p>


<p>Referenced by <a href="#a93bf89ac71202629a6786d6491092131">operator==</a>.</p>

</div>
</div>

### hasSEWLMULRatioOnly() {#a7716dc1a76110d4ec9afcee188c2f3fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasSEWLMULRatioOnly ()</td>
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



<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

### intersect() {#ac8b853a0e5f59f4df074f6ca1f6215cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VSETVLIInfo anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::intersect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo">VSETVLIInfo</a> &amp; Other)</td>
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



<p>Definition at line 822 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="#ac905849b67c47f11df62568e7e5ffbbe">getUnknown</a>, <a href="#a3e3c33515538e1c3dcfd49d6fa1f6466">hasSameAVL</a>, <a href="#a3428818c38247f58e3b497e10d49df12">hasSameVLMAX</a>, <a href="#a41c94f3aa009a794f71dadd0b090d806">isUnknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a>.</p>

</div>
</div>

### isCompatible() {#af2c46f20e8b768f86d9bbc78c610defc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::isCompatible (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvinsertvsetvli-cpp-/demandedfields">DemandedFields</a> &amp; Used, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo">VSETVLIInfo</a> &amp; Require, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS)</td>
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



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3e698ea29321753719288e1308a3746e">hasCompatibleVTYPE</a>, <a href="#ac0a1d82035f4548bb2ca4c31d1d6b138">hasEquallyZeroAVL</a>, <a href="#a3e3c33515538e1c3dcfd49d6fa1f6466">hasSameAVL</a>, <a href="#a3428818c38247f58e3b497e10d49df12">hasSameVLMAX</a>, <a href="#a41c94f3aa009a794f71dadd0b090d806">isUnknown</a>, <a href="#aa9d47a4e0577208cd4d6cfc3bde38e7e">isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a> and <a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a>.</p>

</div>
</div>

### isUnknown() {#a41c94f3aa009a794f71dadd0b090d806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::isUnknown ()</td>
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



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a3af1ce05932756a9695dbe24512cb40e">encodeVTYPE</a>, <a href="#ad78b447d6a130e6102f95a35c58bef9e">getSEWLMULRatio</a>, <a href="#a3428818c38247f58e3b497e10d49df12">hasSameVLMAX</a>, <a href="#ab2b86fba641fa9cf7caaf314b2dc9b49">hasSameVTYPE</a>, <a href="#ac8b853a0e5f59f4df074f6ca1f6215cd">intersect</a>, <a href="#af2c46f20e8b768f86d9bbc78c610defc">isCompatible</a>, <a href="#a93bf89ac71202629a6786d6491092131">operator==</a>, <a href="#aab493b5628399b1140af4094f7af919e">print</a>, <a href="#a7715801da0e918c5f258f40246742a1a">setVTYPE</a> and <a href="#aa4ed778e7cf004e26e2bd53b5b5de8a1">setVTYPE</a>.</p>

</div>
</div>

### isValid() {#aa9d47a4e0577208cd4d6cfc3bde38e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::isValid ()</td>
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



<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#af2c46f20e8b768f86d9bbc78c610defc">isCompatible</a>.</p>

</div>
</div>

### setAVL() {#a195c20c058576ca52259e33600717fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setAVL (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo">VSETVLIInfo</a> &amp; Info)</td>
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



<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6f75ef7051a0287b38299a80a1972909">setAVLImm</a>, <a href="#ad24ed71e13d2eb4173a1efeefb659dc2">setAVLRegDef</a>, <a href="#ae2722afd1903d75b7ab12c8700473e9e">setAVLVLMAX</a>, <a href="#abb2f8d2efedfc2ef075a1824c4221c2c">setUnknown</a> and <a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a>.</p>

</div>
</div>

### setAVLImm() {#a6f75ef7051a0287b38299a80a1972909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setAVLImm (unsigned Imm)</td>
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



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Reference <a href="#abe9fc29b991e5aaaae8e223ed59957dc">AVLImm</a>.</p>


<p>Referenced by <a href="#a195c20c058576ca52259e33600717fcb">setAVL</a>.</p>

</div>
</div>

### setAVLRegDef() {#ad24ed71e13d2eb4173a1efeefb659dc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setAVLRegDef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * VNInfo, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> AVLReg)</td>
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



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af5b7a96d251b7b94d3080770cc91fcd8">AVLRegDef</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>.</p>


<p>Referenced by <a href="#a195c20c058576ca52259e33600717fcb">setAVL</a>.</p>

</div>
</div>

### setAVLVLMAX() {#ae2722afd1903d75b7ab12c8700473e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setAVLVLMAX ()</td>
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



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a195c20c058576ca52259e33600717fcb">setAVL</a>.</p>

</div>
</div>

### setUnknown() {#abb2f8d2efedfc2ef075a1824c4221c2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setUnknown ()</td>
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



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a195c20c058576ca52259e33600717fcb">setAVL</a>.</p>

</div>
</div>

### setVLMul() {#a180903db6abbec26172d57dfc24e608a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setVLMul (<a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1c">RISCVII::VLMUL</a> VLMul)</td>
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



<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

### setVTYPE() {#aa4ed778e7cf004e26e2bd53b5b5de8a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setVTYPE (unsigned VType)</td>
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



<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#af5af8d664535a4bfbb71f0243ed9ae3a">llvm::RISCVVType::getSEW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#a12465125c9315bf864c53298cccde08a">llvm::RISCVVType::getVLMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#a7dc0d6840d44bc9348088a786932fc68">llvm::RISCVVType::isMaskAgnostic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#a08cfea4b8c9e0a6118dc031cafeb0773">llvm::RISCVVType::isTailAgnostic</a>, <a href="#a41c94f3aa009a794f71dadd0b090d806">isUnknown</a> and <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>.</p>

</div>
</div>

### setVTYPE() {#a7715801da0e918c5f258f40246742a1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setVTYPE (<a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1c">RISCVII::VLMUL</a> L, unsigned S, bool TA, bool MA)</td>
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



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a41c94f3aa009a794f71dadd0b090d806">isUnknown</a> and <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AVLImm {#abe9fc29b991e5aaaae8e223ed59957dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::AVLImm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a3a37225cf903ed6441d2581f100aaf61">getAVLImm</a>, <a href="#aab493b5628399b1140af4094f7af919e">print</a>, <a href="#a6f75ef7051a0287b38299a80a1972909">setAVLImm</a> and <a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a>.</p>

</div>
</div>

### AVLRegDef {#af5b7a96d251b7b94d3080770cc91fcd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AVLDef anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::AVLRegDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Referenced by <a href="#a34228acc92d686ec244da04ce11a76d4">getAVLReg</a>, <a href="#a8a7bdf8814caff1865de7ae998d0ad7b">getAVLVNInfo</a> and <a href="#ad24ed71e13d2eb4173a1efeefb659dc2">setAVLRegDef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#a5607fbe4c7cde00d77fde1c24649e3a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

### MaskAgnostic {#a2559b37433c094f83782c73059f00b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::MaskAgnostic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

### SEW {#a51806bfb8d4d8c5fd80b612221702511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::SEW = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

### SEWLMULRatioOnly {#aa9835f24b04ece5dd2d0da5f8cd59250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::SEWLMULRatioOnly</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

### State {#a9570b622fe5bb4d1334f410f40a5e515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::State = Uninitialized</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

### TailAgnostic {#afdeb47db2ae9607b92adbbbefaf57dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::TailAgnostic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

### VLMul {#a61473febcf33944e68b8893f67251f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVII::VLMUL anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::VLMul = RISCVII::LMUL_1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getUnknown() {#ac905849b67c47f11df62568e7e5ffbbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VSETVLIInfo anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::getUnknown ()</td>
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



<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a>.</p>


<p>Reference <a href="#ae9ac2063456ee6f8d62ff1b0ccf41ce4">VSETVLIInfo</a>.</p>


<p>Referenced by <a href="#ac8b853a0e5f59f4df074f6ca1f6215cd">intersect</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp">RISCVInsertVSETVLI.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
