---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loongarchelfobjectwriter-cpp-/loongarchelfobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoongArchELFObjectWriter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{LoongArchELFObjectWriter.cpp}::LoongArchELFObjectWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter">MCELFObjectTargetWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5566d58c413e66fba4f9ac1f944a48bd">LoongArchELFObjectWriter</a> (uint8_t OSABI, bool Is64Bit, bool EnableRelax)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b72ebd19dfddeed5e60aa49e011859">~LoongArchELFObjectWriter</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f55413e09cd08509f17aa6ec9f72e16">needsRelocateWithSymbol</a> (const MCValue &amp;Val, const MCSymbol &amp;Sym, unsigned Type) const override</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab173c1990abd5bd3bd9b397cab725eec">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsPCRel) const override</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55eefa14b71be01db744d70ee2a83e73">EnableRelax</a></td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfobjectwriter-cpp">LoongArchELFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoongArchELFObjectWriter() {#a5566d58c413e66fba4f9ac1f944a48bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoongArchELFObjectWriter::LoongArchELFObjectWriter (uint8_t OSABI, bool Is64Bit, bool EnableRelax)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfobjectwriter-cpp">LoongArchELFObjectWriter.cpp</a>.</p>


<p>References <a href="#a55eefa14b71be01db744d70ee2a83e73">EnableRelax</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#ae6c6e76c9d8e0c912542fe4f8375e8ce">llvm::MCELFObjectTargetWriter::MCELFObjectTargetWriter</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LoongArchELFObjectWriter() {#a07b72ebd19dfddeed5e60aa49e011859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoongArchELFObjectWriter::~LoongArchELFObjectWriter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfobjectwriter-cpp">LoongArchELFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### needsRelocateWithSymbol() {#a6f55413e09cd08509f17aa6ec9f72e16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchELFObjectWriter.cpp}::LoongArchELFObjectWriter::needsRelocateWithSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym, unsigned Type)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfobjectwriter-cpp">LoongArchELFObjectWriter.cpp</a>.</p>


<p>Reference <a href="#a55eefa14b71be01db744d70ee2a83e73">EnableRelax</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getRelocType() {#ab173c1990abd5bd3bd9b397cab725eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LoongArchELFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsPCRel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfobjectwriter-cpp">LoongArchELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a182008c1f6c332cb2cfd8c3d3ffada3e">llvm::LoongArch::fixup_loongarch_abs64_hi12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a5781daab526ee6f78c11cef621710a2d">llvm::LoongArch::fixup_loongarch_abs64_lo20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a21687a5a7d599a51082b61a1d0a6460b">llvm::LoongArch::fixup_loongarch_abs_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a343c4c51960b95f6932cb1ba63ed48cf">llvm::LoongArch::fixup_loongarch_abs_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a3f224f26aafd12d872689f8eb64ca9ff">llvm::LoongArch::fixup_loongarch_b16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a6a204b67935b35bfa83298c90529c8a5">llvm::LoongArch::fixup_loongarch_b21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a392f7ae3052bbb64a2fe93f149406d91">llvm::LoongArch::fixup_loongarch_b26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a59970f56c58d60df377c56b5e91a0bdc">llvm::LoongArch::fixup_loongarch_call36</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a70bee6eb9030175a97edc63e692efdf1">llvm::LoongArch::fixup_loongarch_tls_le64_hi12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a814739c18efc36fceba5e291301c7c68">llvm::LoongArch::fixup_loongarch_tls_le64_lo20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442ada76942b1c8dba41d75a85b4fc7c5008">llvm::LoongArch::fixup_loongarch_tls_le_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a212dc9b5723f913647b5fdfede3f81d6">llvm::LoongArch::fixup_loongarch_tls_le_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### EnableRelax {#a55eefa14b71be01db744d70ee2a83e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchELFObjectWriter.cpp}::LoongArchELFObjectWriter::EnableRelax</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfobjectwriter-cpp">LoongArchELFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#a5566d58c413e66fba4f9ac1f944a48bd">LoongArchELFObjectWriter</a> and <a href="#a6f55413e09cd08509f17aa6ec9f72e16">needsRelocateWithSymbol</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfobjectwriter-cpp">LoongArchELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
