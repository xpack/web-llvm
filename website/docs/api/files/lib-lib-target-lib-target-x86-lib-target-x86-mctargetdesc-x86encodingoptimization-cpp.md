---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `X86EncodingOptimization.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-h">X86EncodingOptimization.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "X86EncodingOptimizationForImmediate.def"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6dbd93dfb585d2714b508b45e7c72ad">isARegister</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a714428af145d6964f0312a163f7d3bf0">optimizeToFixedRegisterForm</a> (MCInst &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simplify FOO $imm, %{al,ax,eax,rax} to FOO $imm, for instruction with a short fixed-register form. <a href="#a714428af145d6964f0312a163f7d3bf0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35779cde38be2f4c81791032dcf33b10">optimizeToShortImmediateForm</a> (MCInst &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64c5a9b119e0a1455b1889cf280e9de9">FROM_TO</a>(FROM, TO, IDX1, IDX2)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a997d8e46d018e151ea881069ba44e495">TO_REV</a>(FROM)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp/#ad790a2acf0d13589ceee65dc44f25e62">FROM_TO</a>(FROM, FROM##_REV, 0, 1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad502dbb7ec314066f406b4b7c927cd2b">TO_REV</a>(FROM)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp/#ad790a2acf0d13589ceee65dc44f25e62">FROM_TO</a>(FROM, FROM##_REV, 0, 2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8594870b8d76b0c22f33b1e5799456fe">TO_IMM1</a>(FROM)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1aa21d0c7dd2c3185ce6b9ecd2c7309">TO_IMM1</a>(FROM)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a995983651045e600e1f16e6815eaafe8">FROM_TO</a>(FROM, TO1, TO2)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77b7d8b401851e2f931cd1564ecea545">FROM_TO</a>(FROM, TO, R0, R1)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b576f02c2584fb0e15116c5b31f596c">FROM_TO</a>(FROM, TO)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40616d363fa7276f632ba9f76ffc414a">ENTRY</a>(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f5717f69b981422654175b2583579dc">ENTRYS</a>(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ad4051bc9b0090859d6667a9de01a4">ENTRYS</a>(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9f07be81f3b1275592b2bc9dc264fe4">ENTRYS</a>(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1404bb05a3f174844c7972f076150ef0">ENTRY</a>(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97fa3070f086430ed0f249f371287b4d">ENTRYS</a>(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a662ae64c92743036ecf3b32c12257e4b">ENTRYS</a>(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ee01f9672017c58d0b1e58d88f6bea7">ENTRYS</a>(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a860fd482f30c8952f3426bace6d62ea9">ENTRY</a>(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f2164c6ca4bcbc59a0cfc01de395b89">ENTRYS</a>(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07cf126f78b0172885996f437a396a1b">ENTRYS</a>(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbf49b4b672bef7e655aa1dce3915909">ENTRYS</a>(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
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

### isARegister() {#ab6dbd93dfb585d2714b508b45e7c72ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isARegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a3e5a30d596e5e8933a926e2d14d5227f">llvm::X86::optimizeMOV</a> and <a href="#a714428af145d6964f0312a163f7d3bf0">optimizeToFixedRegisterForm</a>.</p>

</div>
</div>

### optimizeToFixedRegisterForm() {#a714428af145d6964f0312a163f7d3bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool optimizeToFixedRegisterForm (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
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

<p>Simplify FOO $imm, %{al,ax,eax,rax} to FOO $imm, for instruction with a short fixed-register form.</p>

<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>References <a href="#a64c5a9b119e0a1455b1889cf280e9de9">FROM_TO</a>, <a href="#ab6dbd93dfb585d2714b508b45e7c72ad">isARegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/fixupstatepointcallersaved-cpp/#ad94b44823fa05679a48c3addadb05c75">Saved</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a0256d671ff2830d0ada28b07b9c7ab25">llvm::X86::optimizeToFixedRegisterOrShortImmediateForm</a>.</p>

</div>
</div>

### optimizeToShortImmediateForm() {#a35779cde38be2f4c81791032dcf33b10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool optimizeToShortImmediateForm (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
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



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#ad860e326e495f296cdee70606908a6b1">llvm::MCSymbolRefExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a02786fddb19ccf9f05859236b8d4d23f">llvm::MCSymbolRefExpr::VK_X86_ABS8</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a0256d671ff2830d0ada28b07b9c7ab25">llvm::X86::optimizeToFixedRegisterOrShortImmediateForm</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ENTRY {#a40616d363fa7276f632ba9f76ffc414a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case X86::LONG:                                                              \
    return X86::SHORT;
</div>
</dd>
</dl>

<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>

</div>
</div>

### ENTRY {#a1404bb05a3f174844c7972f076150ef0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case X86::SHORT:                                                             \
    return X86::LONG;
</div>
</dd>
</dl>

<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>

</div>
</div>

### ENTRY {#a860fd482f30c8952f3426bace6d62ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case X86::LONG:                                                              \
    NewOpc = X86::SHORT;                                                       \
    break;
</div>
</dd>
</dl>

<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>

</div>
</div>

### ENTRYS {#a1f5717f69b981422654175b2583579dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRYS(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG, SHORT)                                                           \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_EVEX, SHORT##_EVEX)                                             \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_NF, SHORT##_NF)                                                 \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_ND, SHORT##_ND)                                                 \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_NF_ND, SHORT##_NF_ND)
</div>
</dd>
</dl>
</div>
</div>

### ENTRYS {#a48ad4051bc9b0090859d6667a9de01a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRYS(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG, SHORT)                                                           \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_EVEX, SHORT##_EVEX)                                             \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_NF, SHORT##_NF)
</div>
</dd>
</dl>
</div>
</div>

### ENTRYS {#ad9f07be81f3b1275592b2bc9dc264fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRYS(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG, SHORT)                                                           \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_EVEX, SHORT##_EVEX)                                             \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_ND, SHORT##_ND)
</div>
</dd>
</dl>
</div>
</div>

### ENTRYS {#a97fa3070f086430ed0f249f371287b4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRYS(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG, SHORT)                                                           \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_EVEX, SHORT##_EVEX)                                             \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_NF, SHORT##_NF)                                                 \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_ND, SHORT##_ND)                                                 \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_NF_ND, SHORT##_NF_ND)
</div>
</dd>
</dl>
</div>
</div>

### ENTRYS {#a662ae64c92743036ecf3b32c12257e4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRYS(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG, SHORT)                                                           \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_EVEX, SHORT##_EVEX)                                             \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_NF, SHORT##_NF)
</div>
</dd>
</dl>
</div>
</div>

### ENTRYS {#a6ee01f9672017c58d0b1e58d88f6bea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRYS(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG, SHORT)                                                           \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_EVEX, SHORT##_EVEX)                                             \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_ND, SHORT##_ND)
</div>
</dd>
</dl>
</div>
</div>

### ENTRYS {#a0f2164c6ca4bcbc59a0cfc01de395b89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRYS(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG, SHORT)                                                           \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_EVEX, SHORT##_EVEX)                                             \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_NF, SHORT##_NF)                                                 \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_ND, SHORT##_ND)                                                 \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_NF_ND, SHORT##_NF_ND)
</div>
</dd>
</dl>
</div>
</div>

### ENTRYS {#a07cf126f78b0172885996f437a396a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRYS(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG, SHORT)                                                           \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_EVEX, SHORT##_EVEX)                                             \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_NF, SHORT##_NF)
</div>
</dd>
</dl>
</div>
</div>

### ENTRYS {#abbf49b4b672bef7e655aa1dce3915909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRYS(LONG, SHORT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG, SHORT)                                                           \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_EVEX, SHORT##_EVEX)                                             \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(LONG##_ND, SHORT##_ND)
</div>
</dd>
</dl>
</div>
</div>

### FROM\_TO {#a64c5a9b119e0a1455b1889cf280e9de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FROM_TO(FROM, TO, IDX1, IDX2)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case X86::FROM:                                                              \
    NewOpc = X86::TO;                                                          \
    OpIdx1 = IDX1;                                                             \
    OpIdx2 = IDX2;                                                             \
    break;
</div>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ae0e27cbc3acd22d76564e1f3ac9b8311">llvm::X86::optimizeINCDEC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#aade8574cba756ffdc426344718ada414">llvm::X86::optimizeInstFromVEX3ToVEX2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a3e5a30d596e5e8933a926e2d14d5227f">llvm::X86::optimizeMOV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a690516c8cb802c97acc69f6363735984">llvm::X86::optimizeMOVSX</a>, <a href="#a714428af145d6964f0312a163f7d3bf0">optimizeToFixedRegisterForm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a76d5022aceb3599fdcaf0ef25ee3ce73">llvm::X86::optimizeVPCMPWithImmediateOneOrSix</a>.</p>

</div>
</div>

### FROM\_TO {#a995983651045e600e1f16e6815eaafe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FROM_TO(FROM, TO1, TO2)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case X86::FROM:                                                              \
    Opc1 = X86::TO1;                                                           \
    Opc2 = X86::TO2;                                                           \
    break;
</div>
</dd>
</dl>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>

</div>
</div>

### FROM\_TO {#a77b7d8b401851e2f931cd1564ecea545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FROM_TO(FROM, TO, R0, R1)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case X86::FROM:                                                              \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (MI.getOperand(0).<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>() != X86::R0 ||                                \
        MI.getOperand(1).<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>() != X86::R1)                                  \
      return false;                                                            \
    NewOpc = X86::TO;                                                          \
    break;
</div>
</dd>
</dl>

<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>

</div>
</div>

### FROM\_TO {#a4b576f02c2584fb0e15116c5b31f596c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FROM_TO(FROM, TO)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case X86::FROM:                                                              \
    NewOpc = X86::TO;                                                          \
    break;
</div>
</dd>
</dl>

<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>

</div>
</div>

### TO\_IMM1 {#a8594870b8d76b0c22f33b1e5799456fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TO_IMM1(FROM)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case X86::FROM##i:                                                           \
    NewOpc = X86::FROM##1;                                                     \
    break;                                                                     \
  case X86::FROM##i_EVEX:                                                      \
    NewOpc = X86::FROM##1_EVEX;                                                \
    break;                                                                     \
  case X86::FROM##i_ND:                                                        \
    NewOpc = X86::FROM##1_ND;                                                  \
    break;
</div>
</dd>
</dl>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a88575ba0f198af79c61ba3a8c27a69d8">llvm::X86::optimizeShiftRotateWithImmediateOne</a>.</p>

</div>
</div>

### TO\_IMM1 {#af1aa21d0c7dd2c3185ce6b9ecd2c7309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TO_IMM1(FROM)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case X86::FROM##i:                                                           \
    NewOpc = X86::FROM##1;                                                     \
    break;                                                                     \
  case X86::FROM##i_EVEX:                                                      \
    NewOpc = X86::FROM##1_EVEX;                                                \
    break;                                                                     \
  case X86::FROM##i_NF:                                                        \
    NewOpc = X86::FROM##1_NF;                                                  \
    break;                                                                     \
  case X86::FROM##i_ND:                                                        \
    NewOpc = X86::FROM##1_ND;                                                  \
    break;                                                                     \
  case X86::FROM##i_NF_ND:                                                     \
    NewOpc = X86::FROM##1_NF_ND;                                               \
    break;
</div>
</dd>
</dl>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>

</div>
</div>

### TO\_REV {#a997d8e46d018e151ea881069ba44e495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TO_REV(FROM)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp/#ad790a2acf0d13589ceee65dc44f25e62">FROM_TO</a>(FROM, FROM##_REV, 0, 1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/x86/#aade8574cba756ffdc426344718ada414">llvm::X86::optimizeInstFromVEX3ToVEX2</a>.</p>

</div>
</div>

### TO\_REV {#ad502dbb7ec314066f406b4b7c927cd2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TO_REV(FROM)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp/#ad790a2acf0d13589ceee65dc44f25e62">FROM_TO</a>(FROM, FROM##_REV, 0, 2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
