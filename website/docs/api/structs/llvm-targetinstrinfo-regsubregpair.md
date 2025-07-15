---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targetinstrinfo/regsubregpair
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RegSubRegPair` Struct Reference

<p>A pair composed of a register and a sub-register index. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::TargetInstrInfo::RegSubRegPair { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx">RegSubRegPairAndIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pair composed of a pair of a register and a sub-register index, and another sub-register index. <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab32a5218f8372542d0cef14c9bed969a">RegSubRegPair</a> (Register Reg=Register(), unsigned SubReg=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29bf4043c6ab960c1d334fd6b7c83255">operator==</a> (const RegSubRegPair &amp;P) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb0092f47474b24c5150943c56518515">operator!=</a> (const RegSubRegPair &amp;P) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad7e848e562b1368d6ee4794d84957c6">Reg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66f92cf2247d7b3c3a351ff48dd42d7d">SubReg</a></td>
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

<p>A pair composed of a register and a sub-register index.</p>


<p>Used to give some type checking when modeling Reg:SubReg.</p>


<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegSubRegPair() {#ab32a5218f8372542d0cef14c9bed969a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetInstrInfo::RegSubRegPair::RegSubRegPair (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg=<a href="/web-llvm/docs/api/classes/llvm/register">Register</a>(), unsigned SubReg=0)</td>
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



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="#aad7e848e562b1368d6ee4794d84957c6">Reg</a> and <a href="#a66f92cf2247d7b3c3a351ff48dd42d7d">SubReg</a>.</p>


<p>Referenced by <a href="#afb0092f47474b24c5150943c56518515">operator!=</a>, <a href="#a29bf4043c6ab960c1d334fd6b7c83255">operator==</a> and <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx/#aeba84752b0c5f2618082f6b4fff58a6d">llvm::TargetInstrInfo::RegSubRegPairAndIdx::RegSubRegPairAndIdx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#afb0092f47474b24c5150943c56518515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetInstrInfo::RegSubRegPair::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">RegSubRegPair</a> &amp; P)</td>
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



<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#ab32a5218f8372542d0cef14c9bed969a">RegSubRegPair</a>.</p>

</div>
</div>

### operator==() {#a29bf4043c6ab960c1d334fd6b7c83255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetInstrInfo::RegSubRegPair::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">RegSubRegPair</a> &amp; P)</td>
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



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#aad7e848e562b1368d6ee4794d84957c6">Reg</a>, <a href="#ab32a5218f8372542d0cef14c9bed969a">RegSubRegPair</a> and <a href="#a66f92cf2247d7b3c3a351ff48dd42d7d">SubReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Reg {#aad7e848e562b1368d6ee4794d84957c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::TargetInstrInfo::RegSubRegPair::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a2e6a9e9fbac652264287bcc4542f8b54">followSubRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#af1743a67877bf4ba56d53b235d3573e0">llvm::TargetInstrInfo::getExtractSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#afc76a889f289a0e841775d80aa0338ba">llvm::ARMBaseInstrInfo::getExtractSubregLikeInputs</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-6d820381112462a5bb6b93e4ae7ccfa6/#a3d4315dd5a3e784903ff1a7e7a546528">llvm::DenseMapInfo&lt; TargetInstrInfo::RegSubRegPair &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#abea536f043de7994bc9b67c634a7c879">llvm::TargetInstrInfo::getInsertSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abc8556ad731efc2f7a407169624d812e">llvm::ARMBaseInstrInfo::getInsertSubregLikeInputs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#af58cbab9cb762f2d2a4baae6177e30e4">getNewSource</a>, <a href="#a29bf4043c6ab960c1d334fd6b7c83255">operator==</a>, <a href="#ab32a5218f8372542d0cef14c9bed969a">RegSubRegPair</a> and <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx/#aeba84752b0c5f2618082f6b4fff58a6d">llvm::TargetInstrInfo::RegSubRegPairAndIdx::RegSubRegPairAndIdx</a>.</p>

</div>
</div>

### SubReg {#a66f92cf2247d7b3c3a351ff48dd42d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetInstrInfo::RegSubRegPair::SubReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a2e6a9e9fbac652264287bcc4542f8b54">followSubRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#af1743a67877bf4ba56d53b235d3573e0">llvm::TargetInstrInfo::getExtractSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#afc76a889f289a0e841775d80aa0338ba">llvm::ARMBaseInstrInfo::getExtractSubregLikeInputs</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-6d820381112462a5bb6b93e4ae7ccfa6/#a3d4315dd5a3e784903ff1a7e7a546528">llvm::DenseMapInfo&lt; TargetInstrInfo::RegSubRegPair &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#abea536f043de7994bc9b67c634a7c879">llvm::TargetInstrInfo::getInsertSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abc8556ad731efc2f7a407169624d812e">llvm::ARMBaseInstrInfo::getInsertSubregLikeInputs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#af58cbab9cb762f2d2a4baae6177e30e4">getNewSource</a>, <a href="#a29bf4043c6ab960c1d334fd6b7c83255">operator==</a>, <a href="#ab32a5218f8372542d0cef14c9bed969a">RegSubRegPair</a> and <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpairandidx/#aeba84752b0c5f2618082f6b4fff58a6d">llvm::TargetInstrInfo::RegSubRegPairAndIdx::RegSubRegPairAndIdx</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
