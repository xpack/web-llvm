---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcasmbackend-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SystemZMCAsmBackend.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcfixups-h">MCTargetDesc/SystemZMCFixups.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-h">MCTargetDesc/SystemZMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmbackend-h">llvm/MC/MCAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">llvm/MC/MCAssembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">llvm/MC/MCELFObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">llvm/MC/MCFixupKindInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectwriter-h">llvm/MC/MCObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "llvm/BinaryFormat/ELFRelocs/SystemZ.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-systemzmcasmbackend-cpp-">anonymous{SystemZMCAsmBackend.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-systemzmcasmbackend-cpp-/systemzmcasmbackend">SystemZMCAsmBackend</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-systemzmcasmbackend-cpp-/elfsystemzasmbackend">ELFSystemZAsmBackend</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-systemzmcasmbackend-cpp-/goffsystemzasmbackend">GOFFSystemZAsmBackend</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168829419d2b83e6f25315bba6ccd103">extractBitsForFixup</a> (MCFixupKind Kind, uint64_t Value, const MCFixup &amp;Fixup, MCContext &amp;Ctx)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a849ad88f43c60318de4376137d8e2afc">ELF_RELOC</a>(X, Y)&nbsp;&nbsp;&nbsp;.Case(#<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>)</td>
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

### extractBitsForFixup() {#a168829419d2b83e6f25315bba6ccd103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t extractBitsForFixup (<a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind, uint64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcasmbackend-cpp">SystemZMCAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a02772a67f2052ae04bb9ef1ff9dc3cf8">llvm::FirstTargetFixupKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1faba9cfa22a7020a21476cff5ab2f0fb10">llvm::SystemZ::FK_390_PC12DBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa7d3a87e2217d3174daf923e3e9d22950">llvm::SystemZ::FK_390_PC16DBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa81be4ca2ec8b11ae402b2e5d23fd2807">llvm::SystemZ::FK_390_PC24DBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa5a1d88ad9be241f013a5ff3fee254aa3">llvm::SystemZ::FK_390_PC32DBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa38ee2bc508a03f304fe345c0ec73b49d">llvm::SystemZ::FK_390_S16Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa6a7e1d749e592d2f7472836b629ba6e4">llvm::SystemZ::FK_390_S20Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fac9cd9d899f6c5542f640727a266a28d8">llvm::SystemZ::FK_390_S32Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fae1887e29eee4dcca67d9ef67f1e9f16f">llvm::SystemZ::FK_390_S8Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fab7ecc8ff7e95f6afadd1e92b80f7910e">llvm::SystemZ::FK_390_TLS_CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa4e4c0e7e027d837898b944c120704e85">llvm::SystemZ::FK_390_U12Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa586fe3a11b9df944bcc112a6f714afe9">llvm::SystemZ::FK_390_U16Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1faee7731e49a678c8cc74d0130cc15cb6a">llvm::SystemZ::FK_390_U1Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa69a869f7e5f4ce07ede4156252979df1">llvm::SystemZ::FK_390_U2Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa1e07df5fd3b4dfca3758016e9b8ab13e">llvm::SystemZ::FK_390_U32Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa780a8e9dd0193e538dd218d07d1474af">llvm::SystemZ::FK_390_U3Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1faa746115cc0354ae7dbbc1cb36b5af6ca">llvm::SystemZ::FK_390_U48Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fadf56ccfe2b002a3ad2fda4c0480b63b4">llvm::SystemZ::FK_390_U4Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#acdd1cc3b030808a5dfb5391dd85c9c1fa090768997a29e237dc6f8fc9f1897c8b">llvm::SystemZ::FK_390_U8Imm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08b6d5c69d7933ac65aae84e1b50fa62">llvm::maxIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af80bd4ec8a9b2f8e7d9d75ab708a55c2">llvm::maxUIntN</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab9a9168454d9535e1d4ef88fb4a3592d">llvm::minIntN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemzmcasmbackend-cpp-/systemzmcasmbackend/#a9b897519cd359a1020496070eab065a5">anonymous{SystemZMCAsmBackend.cpp}::SystemZMCAsmBackend::applyFixup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ELF\_RELOC {#a849ad88f43c60318de4376137d8e2afc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ELF_RELOC(X, Y)&nbsp;&nbsp;&nbsp;.Case(#<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcasmbackend-cpp">SystemZMCAsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
