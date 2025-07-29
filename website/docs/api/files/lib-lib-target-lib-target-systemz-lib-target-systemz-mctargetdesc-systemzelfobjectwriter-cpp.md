---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzelfobjectwriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `SystemZELFObjectWriter.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcfixups-h">MCTargetDesc/SystemZMCFixups.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-h">MCTargetDesc/SystemZMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">llvm/MC/MCELFObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">llvm/MC/MCFixup.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectwriter-h">llvm/MC/MCObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;memory&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-systemzelfobjectwriter-cpp-">anonymous{SystemZELFObjectWriter.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-systemzelfobjectwriter-cpp-/systemzelfobjectwriter">SystemZELFObjectWriter</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac39df264f25bf06887e26e27eb1e0f98">getAbsoluteReloc</a> (MCContext &amp;Ctx, SMLoc Loc, unsigned Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a562793995bfb40274f58c7115934d541">getPCRelReloc</a> (MCContext &amp;Ctx, SMLoc Loc, unsigned Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5038fa39ee357c16d42740d2cb46ad7">getTLSLEReloc</a> (MCContext &amp;Ctx, SMLoc Loc, unsigned Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e65d4b4e23ac87be255c2d9f4fbd5cb">getTLSLDOReloc</a> (MCContext &amp;Ctx, SMLoc Loc, unsigned Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76cdcbe8adf4a2e914e58d94b0cd4972">getTLSLDMReloc</a> (MCContext &amp;Ctx, SMLoc Loc, unsigned Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bfebdb698abe528330458b119420708">getTLSGDReloc</a> (MCContext &amp;Ctx, SMLoc Loc, unsigned Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38abb95c889f9a774f6dd48f7d249a6b">getPLTReloc</a> (MCContext &amp;Ctx, SMLoc Loc, unsigned Kind)</td>
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


<div class="doxySectionDef">

## Functions

### getAbsoluteReloc() {#ac39df264f25bf06887e26e27eb1e0f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getAbsoluteReloc (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, unsigned Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzelfobjectwriter-cpp">SystemZELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa38ee2bc508a03f304fe345c0ec73b49d">llvm::SystemZ::FK_390_S16Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa6a7e1d749e592d2f7472836b629ba6e4">llvm::SystemZ::FK_390_S20Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fac9cd9d899f6c5542f640727a266a28d8">llvm::SystemZ::FK_390_S32Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fae1887e29eee4dcca67d9ef67f1e9f16f">llvm::SystemZ::FK_390_S8Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa4e4c0e7e027d837898b944c120704e85">llvm::SystemZ::FK_390_U12Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa586fe3a11b9df944bcc112a6f714afe9">llvm::SystemZ::FK_390_U16Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa1e07df5fd3b4dfca3758016e9b8ab13e">llvm::SystemZ::FK_390_U32Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa090768997a29e237dc6f8fc9f1897c8b">llvm::SystemZ::FK_390_U8Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemzelfobjectwriter-cpp-/systemzelfobjectwriter/#ae6894dac4d7b06693f2eedb5432d5b6d">anonymous{SystemZELFObjectWriter.cpp}::SystemZELFObjectWriter::getRelocType</a>.</p>

</div>
</div>

### getPCRelReloc() {#a562793995bfb40274f58c7115934d541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getPCRelReloc (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, unsigned Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzelfobjectwriter-cpp">SystemZELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1faba9cfa22a7020a21476cff5ab2f0fb10">llvm::SystemZ::FK_390_PC12DBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa7d3a87e2217d3174daf923e3e9d22950">llvm::SystemZ::FK_390_PC16DBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa81be4ca2ec8b11ae402b2e5d23fd2807">llvm::SystemZ::FK_390_PC24DBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa5a1d88ad9be241f013a5ff3fee254aa3">llvm::SystemZ::FK_390_PC32DBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa38ee2bc508a03f304fe345c0ec73b49d">llvm::SystemZ::FK_390_S16Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fac9cd9d899f6c5542f640727a266a28d8">llvm::SystemZ::FK_390_S32Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa586fe3a11b9df944bcc112a6f714afe9">llvm::SystemZ::FK_390_U16Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa1e07df5fd3b4dfca3758016e9b8ab13e">llvm::SystemZ::FK_390_U32Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemzelfobjectwriter-cpp-/systemzelfobjectwriter/#ae6894dac4d7b06693f2eedb5432d5b6d">anonymous{SystemZELFObjectWriter.cpp}::SystemZELFObjectWriter::getRelocType</a>.</p>

</div>
</div>

### getPLTReloc() {#a38abb95c889f9a774f6dd48f7d249a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getPLTReloc (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, unsigned Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzelfobjectwriter-cpp">SystemZELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1faba9cfa22a7020a21476cff5ab2f0fb10">llvm::SystemZ::FK_390_PC12DBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa7d3a87e2217d3174daf923e3e9d22950">llvm::SystemZ::FK_390_PC16DBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa81be4ca2ec8b11ae402b2e5d23fd2807">llvm::SystemZ::FK_390_PC24DBL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa5a1d88ad9be241f013a5ff3fee254aa3">llvm::SystemZ::FK_390_PC32DBL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemzelfobjectwriter-cpp-/systemzelfobjectwriter/#ae6894dac4d7b06693f2eedb5432d5b6d">anonymous{SystemZELFObjectWriter.cpp}::SystemZELFObjectWriter::getRelocType</a>.</p>

</div>
</div>

### getTLSGDReloc() {#a3bfebdb698abe528330458b119420708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getTLSGDReloc (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, unsigned Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzelfobjectwriter-cpp">SystemZELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fab7ecc8ff7e95f6afadd1e92b80f7910e">llvm::SystemZ::FK_390_TLS_CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemzelfobjectwriter-cpp-/systemzelfobjectwriter/#ae6894dac4d7b06693f2eedb5432d5b6d">anonymous{SystemZELFObjectWriter.cpp}::SystemZELFObjectWriter::getRelocType</a>.</p>

</div>
</div>

### getTLSLDMReloc() {#a76cdcbe8adf4a2e914e58d94b0cd4972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getTLSLDMReloc (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, unsigned Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzelfobjectwriter-cpp">SystemZELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fab7ecc8ff7e95f6afadd1e92b80f7910e">llvm::SystemZ::FK_390_TLS_CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemzelfobjectwriter-cpp-/systemzelfobjectwriter/#ae6894dac4d7b06693f2eedb5432d5b6d">anonymous{SystemZELFObjectWriter.cpp}::SystemZELFObjectWriter::getRelocType</a>.</p>

</div>
</div>

### getTLSLDOReloc() {#a5e65d4b4e23ac87be255c2d9f4fbd5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getTLSLDOReloc (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, unsigned Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzelfobjectwriter-cpp">SystemZELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemzelfobjectwriter-cpp-/systemzelfobjectwriter/#ae6894dac4d7b06693f2eedb5432d5b6d">anonymous{SystemZELFObjectWriter.cpp}::SystemZELFObjectWriter::getRelocType</a>.</p>

</div>
</div>

### getTLSLEReloc() {#ac5038fa39ee357c16d42740d2cb46ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getTLSLEReloc (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, unsigned Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzelfobjectwriter-cpp">SystemZELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemzelfobjectwriter-cpp-/systemzelfobjectwriter/#ae6894dac4d7b06693f2eedb5432d5b6d">anonymous{SystemZELFObjectWriter.cpp}::SystemZELFObjectWriter::getRelocType</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
