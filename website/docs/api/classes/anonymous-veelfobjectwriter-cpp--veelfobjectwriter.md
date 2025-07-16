---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-veelfobjectwriter-cpp-/veelfobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VEELFObjectWriter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{VEELFObjectWriter.cpp}::VEELFObjectWriter { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68ab80ae191d28db0fbacb3ce5e85716">VEELFObjectWriter</a> (uint8_t OSABI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada316bc5de740b209894e1fae6e0fad7">~VEELFObjectWriter</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f6d77fdd397bc5312da8d6ffa4e782">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsPCRel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a408a8b811f3959a41ececdaee0496ba9">needsRelocateWithSymbol</a> (const MCValue &amp;Val, const MCSymbol &amp;Sym, unsigned Type) const override</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/veelfobjectwriter-cpp">VEELFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VEELFObjectWriter() {#a68ab80ae191d28db0fbacb3ce5e85716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{VEELFObjectWriter.cpp}::VEELFObjectWriter::VEELFObjectWriter (uint8_t OSABI)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/veelfobjectwriter-cpp">VEELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#ae6c6e76c9d8e0c912542fe4f8375e8ce">llvm::MCELFObjectTargetWriter::MCELFObjectTargetWriter</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VEELFObjectWriter() {#ada316bc5de740b209894e1fae6e0fad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{VEELFObjectWriter.cpp}::VEELFObjectWriter::~VEELFObjectWriter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/veelfobjectwriter-cpp">VEELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="#a81f6d77fdd397bc5312da8d6ffa4e782">getRelocType</a> and <a href="#a408a8b811f3959a41ececdaee0496ba9">needsRelocateWithSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getRelocType() {#a81f6d77fdd397bc5312da8d6ffa4e782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned VEELFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsPCRel)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/veelfobjectwriter-cpp">VEELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa2ad67f23f486e531ca82d71890a68a01">llvm::VE::fixup_ve_got_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa5405339da89126a4026867f540e33441">llvm::VE::fixup_ve_got_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa401919b7d910ed497dbe04087ffb51c0">llvm::VE::fixup_ve_gotoff_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa8a34234c9b623e8c9c425c81be4cb62c">llvm::VE::fixup_ve_gotoff_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aaa5364c6e73ddba627ce657e4356d0b49">llvm::VE::fixup_ve_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa78d516c790863298415e6177345d5ff8">llvm::VE::fixup_ve_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa667f7a97724598853fb6d3cebb1e27d3">llvm::VE::fixup_ve_pc_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aaaf6751559269bc22d124be47cec2bdb2">llvm::VE::fixup_ve_pc_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aade9959851c0f191c677111084c14698f">llvm::VE::fixup_ve_plt_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa122241fcebbf6c6cef07b513c0191a7c">llvm::VE::fixup_ve_plt_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aaf3cea4fe606bf2531f03ca6576c51961">llvm::VE::fixup_ve_reflong</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa060875c5f3e38d17d606f502fa3e06c1">llvm::VE::fixup_ve_srel32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aafc47658a501eaa76ba863b76fadd9735">llvm::VE::fixup_ve_tls_gd_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aafa85f01d7cc2698698e63aa36c528204">llvm::VE::fixup_ve_tls_gd_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aa0312ddb55e9fd7d4e1288f15f6ac4246">llvm::VE::fixup_ve_tpoff_hi32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ve/#a3849fee8bddaabf813c7e8755415178aac8d006c70ba7b24159949d6159dcf08c">llvm::VE::fixup_ve_tpoff_lo32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ac6095ed6f2c30887aef8adc449b1efa5">llvm::FK_PCRel_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a11803cd0814af72a9d078ac0f7a33137">llvm::FK_PCRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a7fa4d5bb1573ffbf54e99ae1fe36ad6e">llvm::FK_PCRel_8</a> and <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#af04d361a436f54db54865f22611d8844a110a79048757760c151612423dbf4064">llvm::VEMCExpr::VK_VE_PC_LO32</a>.</p>


<p>Referenced by <a href="#ada316bc5de740b209894e1fae6e0fad7">~VEELFObjectWriter</a>.</p>

</div>
</div>

### needsRelocateWithSymbol() {#a408a8b811f3959a41ececdaee0496ba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VEELFObjectWriter::needsRelocateWithSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym, unsigned Type)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/veelfobjectwriter-cpp">VEELFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#ada316bc5de740b209894e1fae6e0fad7">~VEELFObjectWriter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/veelfobjectwriter-cpp">VEELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
