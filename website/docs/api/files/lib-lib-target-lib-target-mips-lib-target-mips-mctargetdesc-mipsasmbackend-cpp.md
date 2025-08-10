---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MipsAsmBackend.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MCTargetDesc/MipsAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsabiinfo-h">MCTargetDesc/MipsABIInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsfixupkinds-h">MCTargetDesc/MipsFixupKinds.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-h">MCTargetDesc/MipsMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmbackend-h">llvm/MC/MCAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">llvm/MC/MCAssembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">llvm/MC/MCELFObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">llvm/MC/MCFixupKindInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectwriter-h">llvm/MC/MCObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">llvm/MC/MCTargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-mipsasmbackend-cpp-">anonymous{MipsAsmBackend.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mipsasmbackend-cpp-/windowsmipsasmbackend">WindowsMipsAsmBackend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a419a69e7c102339588b7f4dcebe94387">adjustFixupValue</a> (const MCFixup &amp;Fixup, uint64_t Value, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab6f63e5ba54f992d97d598a1298d38d">needsMMLEByteOrder</a> (unsigned Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53c193f242d181baee037b917d83e3e2">calculateMMLEIndex</a> (unsigned i)</td>
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

### adjustFixupValue() {#a419a69e7c102339588b7f4dcebe94387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned adjustFixupValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp">MipsAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ab5cc10bb4bb0b7c27777cc6d6336ed59">llvm::Mips::fixup_MICROMIPS_26_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a51060e5d732b3b086038dc48f6ec3064">llvm::Mips::fixup_MICROMIPS_GOT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a91fa94291c3d1c568f5e2a3bc10ce94f">llvm::Mips::fixup_MICROMIPS_GOT_DISP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a5d681ebbbf7ccd4ecdf20992c6dcfce9">llvm::Mips::fixup_MICROMIPS_GOT_OFST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a12dd04a6f3222eb075bb7bbb7a877686">llvm::Mips::fixup_MICROMIPS_GOT_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5afcce79f2cce72a302edfee45aa7d4695">llvm::Mips::fixup_MICROMIPS_GPOFF_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a402c60b5bbab1160e7f4af8e4aa9c5a2">llvm::Mips::fixup_MICROMIPS_GPOFF_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a0c89de79bbc8e24d7c8729d3809c2d1d">llvm::Mips::fixup_MICROMIPS_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a2d430e04261f84befeb853879cc7c2d2">llvm::Mips::fixup_MICROMIPS_HIGHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a8a927ca45e8ad03129965f62997df971">llvm::Mips::fixup_MICROMIPS_HIGHEST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a899fa34e895181020ba099bae8a63cb2">llvm::Mips::fixup_MICROMIPS_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a8297df7f9768b5bb575ab89d20b30ff3">llvm::Mips::fixup_MICROMIPS_PC10_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a27da3393b1100b6a207b58257889bb54">llvm::Mips::fixup_MICROMIPS_PC16_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ace202b97f731ed38cb43988dc0699e40">llvm::Mips::fixup_MICROMIPS_PC18_S3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a4bd2e7fe8b6417bbdc61a96bf85a7224">llvm::Mips::fixup_MICROMIPS_PC19_S2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a39ec2eeed1cf046f572cb552fdb6ee2c">llvm::Mips::fixup_MICROMIPS_PC21_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ad6983cbf07a871ee8722596488c5f9cb">llvm::Mips::fixup_MICROMIPS_PC26_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a111b39a21b625c58137cd19b6c21308e">llvm::Mips::fixup_MICROMIPS_PC7_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5af3e67f73426baade7a01c5fc850dcc4a">llvm::Mips::fixup_MICROMIPS_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a462a8407acaf99e32df2276bf05112c9">llvm::Mips::fixup_Mips_26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5aa1da7ac91e24d477f5f1456ea78867ef">llvm::Mips::fixup_Mips_CALL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ab88a975afcf636548981251ccbe94308">llvm::Mips::fixup_Mips_CALL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5adb3fcfd2186ba8a2d087e1dd6aa81835">llvm::Mips::fixup_Mips_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a78e19d4edaf2ec86f2b8c0bad7e880db">llvm::Mips::fixup_Mips_GOT_DISP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a50816e1bb1c03b9f9e78fc51cda22812">llvm::Mips::fixup_Mips_GOT_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ae862242d904102cd8ae48b5e4617e5a0">llvm::Mips::fixup_Mips_GOT_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5aa9c59af1b95c717f8dbb3d368c137033">llvm::Mips::fixup_Mips_GOT_OFST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a6c25bcd83d096682c436213d1c449908">llvm::Mips::fixup_Mips_GOT_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a0944f7b895b814ebef8189a68a7cc18e">llvm::Mips::fixup_Mips_GPOFF_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a400c3fdeb8e0640fba7ceb6974eeb27d">llvm::Mips::fixup_Mips_GPOFF_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a40dd4035924bb1240b2f7ce4852e9393">llvm::Mips::fixup_Mips_GPREL16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a7f5070b2e64fb6be8f7cbb1f9d3720ec">llvm::Mips::fixup_Mips_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a12a25267be170c5dee7f9d696f7761d1">llvm::Mips::fixup_Mips_HIGHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a5e99fde95ca7f0aa830dd98ef0db0b63">llvm::Mips::fixup_Mips_HIGHEST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a055845d89e962573651965ea13667b9b">llvm::Mips::fixup_Mips_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5afac721a28dd1bd12f2fb53010f24f45e">llvm::Mips::fixup_Mips_PC16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a597d2e0218cfdf8e2f9b39af616b7fe5">llvm::Mips::fixup_MIPS_PC18_S3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a8efbc2773d136010014a7b65a31a5605">llvm::Mips::fixup_MIPS_PC19_S2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a537b4ce4509c3dee196ef3f1a98ea3c0">llvm::Mips::fixup_MIPS_PC21_S2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ab3bb518acbac617634c54e31403ad4b4">llvm::Mips::fixup_MIPS_PC26_S2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a5d7eb45487db4b915c25c2e12fb0c949">llvm::Mips::fixup_MIPS_PCHI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5af534b6a07f3786fe4335086ec57851f0">llvm::Mips::fixup_MIPS_PCLO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5adb7dca17c0aa3f4d51bf3fc512383c03">llvm::Mips::fixup_Mips_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d9ad9ac8119a17f5b0d392039449416">llvm::FK_DTPRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5f04203be5ebb87da1ce3b98527bbf7f">llvm::FK_DTPRel_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ab39a952893aef8c5d618b3d6f7d6bc84">llvm::FK_GPRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58aa495238fa611ab89c4323df0081a0eb1">llvm::FK_TPRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ac91b4c1d01ae3cf9d55abd97a6654cb7">llvm::FK_TPRel_8</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>.</p>

</div>
</div>

### calculateMMLEIndex() {#a53c193f242d181baee037b917d83e3e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned calculateMMLEIndex (unsigned i)</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp">MipsAsmBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmbackend/#aa68834049f70b768351aa29223d33a44">llvm::MipsAsmBackend::applyFixup</a>.</p>

</div>
</div>

### needsMMLEByteOrder() {#aab6f63e5ba54f992d97d598a1298d38d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool needsMMLEByteOrder (unsigned Kind)</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp">MipsAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ab5cc10bb4bb0b7c27777cc6d6336ed59">llvm::Mips::fixup_MICROMIPS_26_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a8297df7f9768b5bb575ab89d20b30ff3">llvm::Mips::fixup_MICROMIPS_PC10_S1</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a08a0900a938be83954a85cbf85dba2bd">llvm::Mips::LastTargetFixupKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmbackend/#aa68834049f70b768351aa29223d33a44">llvm::MipsAsmBackend::applyFixup</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
