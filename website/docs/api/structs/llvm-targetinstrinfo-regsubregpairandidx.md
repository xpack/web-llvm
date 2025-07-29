---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targetinstrinfo/regsubregpairandidx
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `RegSubRegPairAndIdx` Struct

<p>A pair composed of a pair of a register and a sub-register index, and another sub-register index. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::TargetInstrInfo::RegSubRegPairAndIdx { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">RegSubRegPair</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pair composed of a register and a sub-register index. <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeba84752b0c5f2618082f6b4fff58a6d">RegSubRegPairAndIdx</a> (Register Reg=Register(), unsigned SubReg=0, unsigned SubIdx=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f62bad8eb5dce2e4a7d7518fc5c21ac">SubIdx</a></td>
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

<p>A pair composed of a pair of a register and a sub-register index, and another sub-register index.</p>


<p>Used to give some type checking when modeling Reg:SubReg1, SubReg2.</p>


<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegSubRegPairAndIdx() {#aeba84752b0c5f2618082f6b4fff58a6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetInstrInfo::RegSubRegPairAndIdx::RegSubRegPairAndIdx (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg=<a href="/web-llvm/docs/api/classes/llvm/register">Register</a>(), unsigned SubReg=0, unsigned SubIdx=0)</td>
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



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#aad7e848e562b1368d6ee4794d84957c6">llvm::TargetInstrInfo::RegSubRegPair::Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#ab32a5218f8372542d0cef14c9bed969a">llvm::TargetInstrInfo::RegSubRegPair::RegSubRegPair</a>, <a href="#a7f62bad8eb5dce2e4a7d7518fc5c21ac">SubIdx</a> and <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#a66f92cf2247d7b3c3a351ff48dd42d7d">llvm::TargetInstrInfo::RegSubRegPair::SubReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### SubIdx {#a7f62bad8eb5dce2e4a7d7518fc5c21ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetInstrInfo::RegSubRegPairAndIdx::SubIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#af1743a67877bf4ba56d53b235d3573e0">llvm::TargetInstrInfo::getExtractSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#afc76a889f289a0e841775d80aa0338ba">llvm::ARMBaseInstrInfo::getExtractSubregLikeInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#abea536f043de7994bc9b67c634a7c879">llvm::TargetInstrInfo::getInsertSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abc8556ad731efc2f7a407169624d812e">llvm::ARMBaseInstrInfo::getInsertSubregLikeInputs</a> and <a href="#aeba84752b0c5f2618082f6b4fff58a6d">RegSubRegPairAndIdx</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
