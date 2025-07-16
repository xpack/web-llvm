---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcrelocationinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCRelocationInfo` Class Reference

<p>Create MCExprs from relocations found in an object file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCRelocationInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcrelocationinfo-h">llvm/MC/MCDisassembler/MCRelocationInfo.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armmachorelocationinfo-cpp-/armmachorelocationinfo">ARMMachORelocationInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ccf2f87b7d952eaecd1770fe94ecbba">MCRelocationInfo</a> (MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b771e166fbc1c5318386c7d3353719c">MCRelocationInfo</a> (const MCRelocationInfo &amp;)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af37c83f286699a97d70670d7bd1dc613">~MCRelocationInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a045cea44e5edb757dc88b5fe1a4f714d">operator=</a> (const MCRelocationInfo &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4636659aa6c1ac582dedcdd046795f98">createExprForCAPIVariantKind</a> (const MCExpr *SubExpr, unsigned VariantKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for the target-specific <span class="doxyComputerOutput">VariantKind</span>. <a href="#a4636659aa6c1ac582dedcdd046795f98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a997d65e9708d2e269a7f37c6e1efe51a">Ctx</a></td>
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

<p>Create MCExprs from relocations found in an object file.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcrelocationinfo-h">MCRelocationInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCRelocationInfo() {#a0ccf2f87b7d952eaecd1770fe94ecbba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRelocationInfo::MCRelocationInfo (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcrelocationinfo-h">MCRelocationInfo.h</a>, definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/mcrelocationinfo-cpp">MCRelocationInfo.cpp</a>.</p>


<p>Reference <a href="#a997d65e9708d2e269a7f37c6e1efe51a">Ctx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armmachorelocationinfo-cpp-/armmachorelocationinfo/#acba487bd7cb37060bfdd84642600a6b6">anonymous{ARMMachORelocationInfo.cpp}::ARMMachORelocationInfo::ARMMachORelocationInfo</a>, <a href="#a3b771e166fbc1c5318386c7d3353719c">MCRelocationInfo</a> and <a href="#a045cea44e5edb757dc88b5fe1a4f714d">operator=</a>.</p>

</div>
</div>

### MCRelocationInfo() {#a3b771e166fbc1c5318386c7d3353719c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCRelocationInfo::MCRelocationInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcrelocationinfo-h">MCRelocationInfo.h</a>.</p>


<p>Reference <a href="#a0ccf2f87b7d952eaecd1770fe94ecbba">MCRelocationInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MCRelocationInfo() {#af37c83f286699a97d70670d7bd1dc613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRelocationInfo::~MCRelocationInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcrelocationinfo-h">MCRelocationInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a045cea44e5edb757dc88b5fe1a4f714d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRelocationInfo &amp; llvm::MCRelocationInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcrelocationinfo-h">MCRelocationInfo.h</a>.</p>


<p>Reference <a href="#a0ccf2f87b7d952eaecd1770fe94ecbba">MCRelocationInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createExprForCAPIVariantKind() {#a4636659aa6c1ac582dedcdd046795f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * MCRelocationInfo::createExprForCAPIVariantKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * SubExpr, unsigned VariantKind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> for the target-specific <span class="doxyComputerOutput">VariantKind</span>.</p>


<p>The VariantKinds are defined in <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">llvm-c/Disassembler.h</a>. Used by <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer">MCExternalSymbolizer</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>If possible, an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> corresponding to VariantKind, else 0.</p></dd>
</dl>


<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcrelocationinfo-h">MCRelocationInfo.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/mcrelocationinfo-cpp">MCRelocationInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaeb7b3311097fd803536f89c1fd8a5f15">LLVMDisassembler_VariantKind_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armmachorelocationinfo-cpp-/armmachorelocationinfo/#acf3e0563ec30bb753fe338dc8be818b6">anonymous{ARMMachORelocationInfo.cpp}::ARMMachORelocationInfo::createExprForCAPIVariantKind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Ctx {#a997d65e9708d2e269a7f37c6e1efe51a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; llvm::MCRelocationInfo::Ctx</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcrelocationinfo-h">MCRelocationInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armmachorelocationinfo-cpp-/armmachorelocationinfo/#acba487bd7cb37060bfdd84642600a6b6">anonymous{ARMMachORelocationInfo.cpp}::ARMMachORelocationInfo::ARMMachORelocationInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmachorelocationinfo-cpp-/armmachorelocationinfo/#acf3e0563ec30bb753fe338dc8be818b6">anonymous{ARMMachORelocationInfo.cpp}::ARMMachORelocationInfo::createExprForCAPIVariantKind</a> and <a href="#a0ccf2f87b7d952eaecd1770fe94ecbba">MCRelocationInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcrelocationinfo-h">MCRelocationInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/mcrelocationinfo-cpp">MCRelocationInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
