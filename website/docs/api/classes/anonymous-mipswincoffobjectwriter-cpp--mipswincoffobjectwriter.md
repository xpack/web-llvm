---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-mipswincoffobjectwriter-cpp-/mipswincoffobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MipsWinCOFFObjectWriter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{MipsWinCOFFObjectWriter.cpp}::MipsWinCOFFObjectWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcwincoffobjecttargetwriter">MCWinCOFFObjectTargetWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe921403ee48a98d9813f8795de28092">MipsWinCOFFObjectWriter</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a632527f1e63c3a9e06ed64fc7e0cd51c">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsCrossSection, const MCAsmBackend &amp;MAB) const override</td>
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


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipswincoffobjectwriter-cpp">MipsWinCOFFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MipsWinCOFFObjectWriter() {#afe921403ee48a98d9813f8795de28092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsWinCOFFObjectWriter::MipsWinCOFFObjectWriter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipswincoffobjectwriter-cpp">MipsWinCOFFObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcwincoffobjecttargetwriter/#a1a0a17e6c398aabca7cb280e753ca9de">llvm::MCWinCOFFObjectTargetWriter::MCWinCOFFObjectTargetWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRelocType() {#a632527f1e63c3a9e06ed64fc7e0cd51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsWinCOFFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsCrossSection, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &amp; MAB)</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipswincoffobjectwriter-cpp">MipsWinCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a462a8407acaf99e32df2276bf05112c9">llvm::Mips::fixup_Mips_26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a7f5070b2e64fb6be8f7cbb1f9d3720ec">llvm::Mips::fixup_Mips_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a055845d89e962573651965ea13667b9b">llvm::Mips::fixup_Mips_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3d3a355228d2f64fa312abbd7abfbf">llvm::FixupKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a128346d352fde2e704c07867f4d82eef">llvm::FK_SecRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a8b2acba82b6d0830ab47d67eb8f1ccf0">llvm::FK_SecRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a2a5fd940ffde686f89fd39f338cb8e7ba4729ea2a2591b7de1353a728345b6f3e">llvm::COFF::IMAGE_REL_MIPS_JMPADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a2a5fd940ffde686f89fd39f338cb8e7ba4a1fb04b4071332202dbb31dec920001">llvm::COFF::IMAGE_REL_MIPS_REFHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a2a5fd940ffde686f89fd39f338cb8e7ba4b12f4fabae25b5cbfc715d74a8d1a6f">llvm::COFF::IMAGE_REL_MIPS_REFLO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a2a5fd940ffde686f89fd39f338cb8e7badccf394fc664fafc6eb0a9027ad98bf7">llvm::COFF::IMAGE_REL_MIPS_REFWORD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a2a5fd940ffde686f89fd39f338cb8e7baeb28d4a870ef2359d139a6c6eb1b5c3f">llvm::COFF::IMAGE_REL_MIPS_SECREL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a2a5fd940ffde686f89fd39f338cb8e7baff5652ba6a78f8235c60c1060afc7524">llvm::COFF::IMAGE_REL_MIPS_SECTION</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipswincoffobjectwriter-cpp">MipsWinCOFFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
