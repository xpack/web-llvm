---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ppctargetlowering/callflags
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CallFlags` Struct Reference

<p>Structure that collects some common arguments that get passed around between the functions for call lowering. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::PPCTargetLowering::CallFlags { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">Target/PowerPC/PPCISelLowering.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbc5ca83d58067e92846f8181257b33b">CallFlags</a> (CallingConv::ID CC, bool IsTailCall, bool IsVarArg, bool IsPatchPoint, bool IsIndirect, bool HasNest, bool NoMerge)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2db3e19dc2ffa8c67cf481a8f197dd5">CallConv</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade4d56b32521a7e9beee5827a349baa4">IsTailCall</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f9d611fd81427bb77bed0744af981e">IsVarArg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a103e605f56024aed192adba2dbb72316">IsPatchPoint</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c9e4ca12154076c8da225efd722b48e">IsIndirect</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74e18bdef06bd9e6b703302ba5ccbdee">HasNest</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafbac60b086e1b61c82f471dbd81bf93">NoMerge</a></td>
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

<p>Structure that collects some common arguments that get passed around between the functions for call lowering.</p>

<p>Definition at line 1178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CallFlags() {#adbc5ca83d58067e92846f8181257b33b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PPCTargetLowering::CallFlags::CallFlags (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, bool IsTailCall, bool IsVarArg, bool IsPatchPoint, bool IsIndirect, bool HasNest, bool NoMerge)</td>
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



<p>Definition at line 1187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>References <a href="#af2db3e19dc2ffa8c67cf481a8f197dd5">CallConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a74e18bdef06bd9e6b703302ba5ccbdee">HasNest</a>, <a href="#a2c9e4ca12154076c8da225efd722b48e">IsIndirect</a>, <a href="#a103e605f56024aed192adba2dbb72316">IsPatchPoint</a>, <a href="#ade4d56b32521a7e9beee5827a349baa4">IsTailCall</a>, <a href="#a35f9d611fd81427bb77bed0744af981e">IsVarArg</a> and <a href="#aafbac60b086e1b61c82f471dbd81bf93">NoMerge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CallConv {#af2db3e19dc2ffa8c67cf481a8f197dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallingConv::ID llvm::PPCTargetLowering::CallFlags::CallConv</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a> and <a href="#adbc5ca83d58067e92846f8181257b33b">CallFlags</a>.</p>

</div>
</div>

### HasNest {#a74e18bdef06bd9e6b703302ba5ccbdee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::PPCTargetLowering::CallFlags::HasNest</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a> and <a href="#adbc5ca83d58067e92846f8181257b33b">CallFlags</a>.</p>

</div>
</div>

### IsIndirect {#a2c9e4ca12154076c8da225efd722b48e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::PPCTargetLowering::CallFlags::IsIndirect</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>, <a href="#adbc5ca83d58067e92846f8181257b33b">CallFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a04db783920e3a77ee7d48c5bc4d10b9a">getCallOpcode</a>.</p>

</div>
</div>

### IsPatchPoint {#a103e605f56024aed192adba2dbb72316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::PPCTargetLowering::CallFlags::IsPatchPoint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a> and <a href="#adbc5ca83d58067e92846f8181257b33b">CallFlags</a>.</p>

</div>
</div>

### IsTailCall {#ade4d56b32521a7e9beee5827a349baa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::PPCTargetLowering::CallFlags::IsTailCall</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>, <a href="#adbc5ca83d58067e92846f8181257b33b">CallFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a04db783920e3a77ee7d48c5bc4d10b9a">getCallOpcode</a>.</p>

</div>
</div>

### IsVarArg {#a35f9d611fd81427bb77bed0744af981e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::PPCTargetLowering::CallFlags::IsVarArg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a> and <a href="#adbc5ca83d58067e92846f8181257b33b">CallFlags</a>.</p>

</div>
</div>

### NoMerge {#aafbac60b086e1b61c82f471dbd81bf93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::PPCTargetLowering::CallFlags::NoMerge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>Referenced by <a href="#adbc5ca83d58067e92846f8181257b33b">CallFlags</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
