---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-armmachorelocationinfo-cpp-/armmachorelocationinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMMachORelocationInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{ARMMachORelocationInfo.cpp}::ARMMachORelocationInfo { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create MCExprs from relocations found in an object file. <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acba487bd7cb37060bfdd84642600a6b6">ARMMachORelocationInfo</a> (MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf3e0563ec30bb753fe338dc8be818b6">createExprForCAPIVariantKind</a> (const MCExpr *SubExpr, unsigned VariantKind) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an MCExpr for the target-specific <span class="doxyComputerOutput">VariantKind</span>. <a href="#acf3e0563ec30bb753fe338dc8be818b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmachorelocationinfo-cpp">ARMMachORelocationInfo.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMMachORelocationInfo() {#acba487bd7cb37060bfdd84642600a6b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMMachORelocationInfo.cpp}::ARMMachORelocationInfo::ARMMachORelocationInfo (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmachorelocationinfo-cpp">ARMMachORelocationInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo/#a997d65e9708d2e269a7f37c6e1efe51a">llvm::MCRelocationInfo::Ctx</a> and <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo/#a0ccf2f87b7d952eaecd1770fe94ecbba">llvm::MCRelocationInfo::MCRelocationInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a58c68eb297c7b818c8c9c11b5aef45f3">llvm::createARMMachORelocationInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createExprForCAPIVariantKind() {#acf3e0563ec30bb753fe338dc8be818b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * anonymous{ARMMachORelocationInfo.cpp}::ARMMachORelocationInfo::createExprForCAPIVariantKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * SubExpr, unsigned VariantKind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an MCExpr for the target-specific <span class="doxyComputerOutput">VariantKind</span>.</p>


<p>The VariantKinds are defined in <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">llvm-c/Disassembler.h</a>. Used by MCExternalSymbolizer.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>If possible, an MCExpr corresponding to VariantKind, else 0.</p></dd>
</dl>


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmachorelocationinfo-cpp">ARMMachORelocationInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo/#a4636659aa6c1ac582dedcdd046795f98">llvm::MCRelocationInfo::createExprForCAPIVariantKind</a>, <a href="/web-llvm/docs/api/classes/llvm/armmcexpr/#aaf486dcfcfa44e3ca26f8b463631936d">llvm::ARMMCExpr::createLower16</a>, <a href="/web-llvm/docs/api/classes/llvm/armmcexpr/#ab1018245b6c97eab91ce62685bae306d">llvm::ARMMCExpr::createUpper16</a>, <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo/#a997d65e9708d2e269a7f37c6e1efe51a">llvm::MCRelocationInfo::Ctx</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga18c0e1aa1f200a0154c9301841a4d7ba">LLVMDisassembler_VariantKind_ARM_HI16</a> and <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga518d82ae8838203f9aa0f8566a5ca51c">LLVMDisassembler_VariantKind_ARM_LO16</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmachorelocationinfo-cpp">ARMMachORelocationInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
