---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-armwincoffobjectwriter-cpp-/armwincoffobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMWinCOFFObjectWriter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{ARMWinCOFFObjectWriter.cpp}::ARMWinCOFFObjectWriter { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a883895d0e85d6a8bd9671e9658d3fc57">ARMWinCOFFObjectWriter</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae260158901d71c97b28071295ce757c9">~ARMWinCOFFObjectWriter</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe849d4183df6b5464a0db9b6a2a8b35">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsCrossSection, const MCAsmBackend &amp;MAB) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9144cb4b03f7d3996b85fbffd65b9247">recordRelocation</a> (const MCFixup &amp;) const override</td>
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


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffobjectwriter-cpp">ARMWinCOFFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMWinCOFFObjectWriter() {#a883895d0e85d6a8bd9671e9658d3fc57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMWinCOFFObjectWriter.cpp}::ARMWinCOFFObjectWriter::ARMWinCOFFObjectWriter ()</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffobjectwriter-cpp">ARMWinCOFFObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcwincoffobjecttargetwriter/#a1a0a17e6c398aabca7cb280e753ca9de">llvm::MCWinCOFFObjectTargetWriter::MCWinCOFFObjectTargetWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ARMWinCOFFObjectWriter() {#ae260158901d71c97b28071295ce757c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMWinCOFFObjectWriter.cpp}::ARMWinCOFFObjectWriter::~ARMWinCOFFObjectWriter ()</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffobjectwriter-cpp">ARMWinCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="#abe849d4183df6b5464a0db9b6a2a8b35">getRelocType</a> and <a href="#a9144cb4b03f7d3996b85fbffd65b9247">recordRelocation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRelocType() {#abe849d4183df6b5464a0db9b6a2a8b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMWinCOFFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsCrossSection, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &amp; MAB)</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffobjectwriter-cpp">ARMWinCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0adb86ef3fcfce8098efef7cb48f3ae98d">llvm::ARM::fixup_arm_thumb_bl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a78f923cec6a90c05ba09b4cf99112b93">llvm::ARM::fixup_arm_thumb_blx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0abd8de06471430072373886fe44229083">llvm::ARM::fixup_t2_condbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a3175e012a680bfa04176f1073d837f78">llvm::ARM::fixup_t2_movt_hi16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0af29359bd1f79d7f6aec8e2c9275f44d1">llvm::ARM::fixup_t2_movw_lo16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a81dbbcf6c6a3e2c7c87af5dc5b9301d3">llvm::ARM::fixup_t2_uncondbranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3d3a355228d2f64fa312abbd7abfbf">llvm::FixupKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a128346d352fde2e704c07867f4d82eef">llvm::FK_SecRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a8b2acba82b6d0830ab47d67eb8f1ccf0">llvm::FK_SecRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a905028c6320edfd212e3cffd365e6cf4">llvm::COFF::IMAGE_REL_ARM_ABSOLUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a746d514c28aa512d8ddd56dc058e8faf">llvm::COFF::IMAGE_REL_ARM_ADDR32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a4674ff1d84292a919b54e9ebd3d5fd46">llvm::COFF::IMAGE_REL_ARM_ADDR32NB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a99ba87de124124cda61beaeeef90e547">llvm::COFF::IMAGE_REL_ARM_BLX23T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a3ebd5ea614167c6fccba3b326dd215be">llvm::COFF::IMAGE_REL_ARM_BRANCH20T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a8898d58c6174b9ced49e3092764a27b5">llvm::COFF::IMAGE_REL_ARM_BRANCH24T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a865cc9cadbef2c0b2034ed1f7d49a8d3">llvm::COFF::IMAGE_REL_ARM_MOV32T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a966485b6e6aca96a28c699566244f1a5">llvm::COFF::IMAGE_REL_ARM_REL32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5aa3675a902af589d1fe8239cb229e834c">llvm::COFF::IMAGE_REL_ARM_SECREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5aa99263a4ddef9c6522025169308d6d80">llvm::COFF::IMAGE_REL_ARM_SECTION</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">llvm::MCSymbolRefExpr::VK_COFF_IMGREL32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a0cca43f5b196466926fb823727bd8902">llvm::MCSymbolRefExpr::VK_SECREL</a>.</p>


<p>Referenced by <a href="#ae260158901d71c97b28071295ce757c9">~ARMWinCOFFObjectWriter</a>.</p>

</div>
</div>

### recordRelocation() {#a9144cb4b03f7d3996b85fbffd65b9247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMWinCOFFObjectWriter::recordRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffobjectwriter-cpp">ARMWinCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad950a20a6062ddd7f336a9eede28bdf0a3175e012a680bfa04176f1073d837f78">llvm::ARM::fixup_t2_movt_hi16</a>.</p>


<p>Referenced by <a href="#ae260158901d71c97b28071295ce757c9">~ARMWinCOFFObjectWriter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffobjectwriter-cpp">ARMWinCOFFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
