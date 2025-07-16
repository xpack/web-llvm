---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64wincoffobjectwriter-cpp-/aarch64wincoffobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AArch64WinCOFFObjectWriter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64WinCOFFObjectWriter.cpp}::AArch64WinCOFFObjectWriter { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0589c9406d7f2f4fc3a1a0e34d9ac02">AArch64WinCOFFObjectWriter</a> (const Triple &amp;TheTriple)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ea9da5e7c4b94572f69b7dfd74cb64f">~AArch64WinCOFFObjectWriter</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4bbe9cdad8b662d3467e8cb63d87b74">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsCrossSection, const MCAsmBackend &amp;MAB) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a432080a1f772c4079dba8c63432e30d8">recordRelocation</a> (const MCFixup &amp;) const override</td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64wincoffobjectwriter-cpp">AArch64WinCOFFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64WinCOFFObjectWriter() {#af0589c9406d7f2f4fc3a1a0e34d9ac02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64WinCOFFObjectWriter.cpp}::AArch64WinCOFFObjectWriter::AArch64WinCOFFObjectWriter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TheTriple)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64wincoffobjectwriter-cpp">AArch64WinCOFFObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcwincoffobjecttargetwriter/#a1a0a17e6c398aabca7cb280e753ca9de">llvm::MCWinCOFFObjectTargetWriter::MCWinCOFFObjectTargetWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AArch64WinCOFFObjectWriter() {#a1ea9da5e7c4b94572f69b7dfd74cb64f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64WinCOFFObjectWriter.cpp}::AArch64WinCOFFObjectWriter::~AArch64WinCOFFObjectWriter ()</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64wincoffobjectwriter-cpp">AArch64WinCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="#ac4bbe9cdad8b662d3467e8cb63d87b74">getRelocType</a> and <a href="#a432080a1f772c4079dba8c63432e30d8">recordRelocation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRelocType() {#ac4bbe9cdad8b662d3467e8cb63d87b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64WinCOFFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsCrossSection, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &amp; MAB)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64wincoffobjectwriter-cpp">AArch64WinCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9ad535858a360e48fa51bd9c5ac0956162">llvm::AArch64::fixup_aarch64_add_imm12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9ae794060e936aea9d09bdd85bb99dcf80">llvm::AArch64::fixup_aarch64_ldst_imm12_scale1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9ac2e74dcdf3c97291d6ce9fc8032d2e4f">llvm::AArch64::fixup_aarch64_ldst_imm12_scale16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9aa7eca8a3014a1980664443a7d07edec5">llvm::AArch64::fixup_aarch64_ldst_imm12_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a1d9670f8c96a7890ee1396fc8596e5a4">llvm::AArch64::fixup_aarch64_ldst_imm12_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9adaa9de7bb7ea352fc17fcb5adec2a9f5">llvm::AArch64::fixup_aarch64_ldst_imm12_scale8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a9a9d665cbb724cea9ad2aae20668e464">llvm::AArch64::fixup_aarch64_pcrel_adr_imm21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9ad31b24bfe1fb4471f899fbfa37d240f7">llvm::AArch64::fixup_aarch64_pcrel_adrp_imm21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a9cfa836f3def950d2b4a9cc69a5de67c">llvm::AArch64::fixup_aarch64_pcrel_branch14</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a87e08dcaf47dcab2f388f1d348002f3f">llvm::AArch64::fixup_aarch64_pcrel_branch19</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a74a32a0e3d43c7e6b0ef010ebffa5f23">llvm::AArch64::fixup_aarch64_pcrel_branch26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a572647824895bc24ec60e6ed94fc2b05">llvm::AArch64::fixup_aarch64_pcrel_call26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3d3a355228d2f64fa312abbd7abfbf">llvm::FixupKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a128346d352fde2e704c07867f4d82eef">llvm::FK_SecRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a8b2acba82b6d0830ab47d67eb8f1ccf0">llvm::FK_SecRel_4</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad4777f004ef52f665e6ec6defc1cb32a">llvm::MCAsmBackend::getFixupKindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#a07e3d0ae8a67b027d48dbb2a51ed6e9a">llvm::AArch64MCExpr::getSymbolLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eaaf8d91439b6c0c905ee9cd3eca3cea1c">llvm::COFF::IMAGE_REL_ARM64_ABSOLUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea5eef7fcc1ce4e904b4674667edcb05d1">llvm::COFF::IMAGE_REL_ARM64_ADDR32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eae2871250d400787e7f8ec6fd55f1ba40">llvm::COFF::IMAGE_REL_ARM64_ADDR32NB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eafe178efa3ce63a8ff56cc587a18db82c">llvm::COFF::IMAGE_REL_ARM64_ADDR64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eac43ef804249b1c1f07711a9866299819">llvm::COFF::IMAGE_REL_ARM64_BRANCH14</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea097bfbb62502b9566c9e1985a04b5c6b">llvm::COFF::IMAGE_REL_ARM64_BRANCH19</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eac53ed10f9401665d19e5eefa59984bd9">llvm::COFF::IMAGE_REL_ARM64_BRANCH26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eaf208e10668d261aed713825f256f420d">llvm::COFF::IMAGE_REL_ARM64_PAGEBASE_REL21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eaafd0e1b4a38680cf94e03fa4c1d29957">llvm::COFF::IMAGE_REL_ARM64_PAGEOFFSET_12A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eacb363e20befbd3ed6e3e871ddf982aa8">llvm::COFF::IMAGE_REL_ARM64_PAGEOFFSET_12L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eaf22de55fb18b610776fa84d8f4e956ca">llvm::COFF::IMAGE_REL_ARM64_REL21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea1dde8be4528eebd8bfb4962a11b91d36">llvm::COFF::IMAGE_REL_ARM64_REL32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea079834a37edaf463583319d7578077fd">llvm::COFF::IMAGE_REL_ARM64_SECREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea87d81b3a2cd85bf5220240d7c9fa52bc">llvm::COFF::IMAGE_REL_ARM64_SECREL_HIGH12A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea3ecf90c2cbc293af2d292546431cc58f">llvm::COFF::IMAGE_REL_ARM64_SECREL_LOW12A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ead15cb0dcf3d1616aba55b96a70dc0c6f">llvm::COFF::IMAGE_REL_ARM64_SECREL_LOW12L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea6a6d329033fe824d392778107e5349a9">llvm::COFF::IMAGE_REL_ARM64_SECTION</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa873476895e81395d69f2a8a5e9f298cf">llvm::AArch64MCExpr::VK_ABS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">llvm::MCSymbolRefExpr::VK_COFF_IMGREL32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaec64aa7810f0b31023d490a86d01d415">llvm::AArch64MCExpr::VK_SECREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a0cca43f5b196466926fb823727bd8902">llvm::MCSymbolRefExpr::VK_SECREL</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfad8bf44f54a45b38024a2cdc10226cb3a">llvm::AArch64MCExpr::VK_SECREL_HI12</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaee5e353993b28f25d23e1b76e1b295a2">llvm::AArch64MCExpr::VK_SECREL_LO12</a>.</p>


<p>Referenced by <a href="#a1ea9da5e7c4b94572f69b7dfd74cb64f">~AArch64WinCOFFObjectWriter</a>.</p>

</div>
</div>

### recordRelocation() {#a432080a1f772c4079dba8c63432e30d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64WinCOFFObjectWriter::recordRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64wincoffobjectwriter-cpp">AArch64WinCOFFObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>.</p>


<p>Referenced by <a href="#a1ea9da5e7c4b94572f69b7dfd74cb64f">~AArch64WinCOFFObjectWriter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64wincoffobjectwriter-cpp">AArch64WinCOFFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
