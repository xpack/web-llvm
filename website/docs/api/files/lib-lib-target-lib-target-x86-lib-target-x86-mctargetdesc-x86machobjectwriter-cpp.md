---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86machobjectwriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `X86MachObjectWriter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86fixupkinds-h">MCTargetDesc/X86FixupKinds.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-h">MCTargetDesc/X86MCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfodarwin-h">llvm/MC/MCAsmInfoDarwin.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">llvm/MC/MCAssembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">llvm/MC/MCMachObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">llvm/MC/MCSectionMachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86machobjectwriter-cpp-">anonymous{X86MachObjectWriter.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86machobjectwriter-cpp-/x86machobjectwriter">X86MachObjectWriter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf056d6569af177135f5a26bd07316ff">isFixupKindRIPRel</a> (unsigned Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0ae46ffe17cde83585d7b7479f6e2a9">getFixupKindLog2Size</a> (unsigned Kind)</td>
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

### getFixupKindLog2Size() {#af0ae46ffe17cde83585d7b7479f6e2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getFixupKindLog2Size (unsigned Kind)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86machobjectwriter-cpp">X86MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ac6095ed6f2c30887aef8adc449b1efa5">llvm::FK_PCRel_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a11803cd0814af72a9d078ac0f7a33137">llvm::FK_PCRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca3b2a5a68543379e2c0ecada70a114244">llvm::X86::reloc_branch_4byte_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcaea3ac30c46fc4086e0fac8473ece1f8b">llvm::X86::reloc_riprel_4byte</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcacd0ed684ad2d4c067ca938d45567540c">llvm::X86::reloc_riprel_4byte_movq_load</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca303862a22911ad0a16f5f88c89d7c105">llvm::X86::reloc_riprel_4byte_movq_load_rex2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca711b77689359fcf4cb49f96b5571d5c0">llvm::X86::reloc_riprel_4byte_relax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca7b4bcca3a40ad945a73f1c1d199c6362">llvm::X86::reloc_riprel_4byte_relax_evex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca962ed593088a527512dad825d971922e">llvm::X86::reloc_riprel_4byte_relax_rex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcaea71f97aa32a2a3fabf01372d4079a5c">llvm::X86::reloc_riprel_4byte_relax_rex2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca8b029ea6e687fd2d4caf13cbbe2cde08">llvm::X86::reloc_signed_4byte</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca372de3ecc0967f0c818089f93138a0de">llvm::X86::reloc_signed_4byte_relax</a>.</p>

</div>
</div>

### isFixupKindRIPRel() {#adf056d6569af177135f5a26bd07316ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFixupKindRIPRel (unsigned Kind)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86machobjectwriter-cpp">X86MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcaea3ac30c46fc4086e0fac8473ece1f8b">llvm::X86::reloc_riprel_4byte</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcacd0ed684ad2d4c067ca938d45567540c">llvm::X86::reloc_riprel_4byte_movq_load</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca303862a22911ad0a16f5f88c89d7c105">llvm::X86::reloc_riprel_4byte_movq_load_rex2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca711b77689359fcf4cb49f96b5571d5c0">llvm::X86::reloc_riprel_4byte_relax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca7b4bcca3a40ad945a73f1c1d199c6362">llvm::X86::reloc_riprel_4byte_relax_evex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca962ed593088a527512dad825d971922e">llvm::X86::reloc_riprel_4byte_relax_rex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcaea71f97aa32a2a3fabf01372d4079a5c">llvm::X86::reloc_riprel_4byte_relax_rex2</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
