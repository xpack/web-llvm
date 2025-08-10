---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loongarchtargetelfstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoongArchTargetELFStreamer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::LoongArchTargetELFStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-h">Target/LoongArch/MCTargetDesc/LoongArchELFStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loongarchtargetstreamer">LoongArchTargetStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedd14021422c2f6fba707ef8188d6d28">LoongArchTargetELFStreamer</a> (MCStreamer &amp;S, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer">MCELFStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16d255e2091283a2d8ed0f1fefa66d4e">getStreamer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab951e5358f31ba739b98e3711ad698cc">emitDirectiveOptionPush</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c465a5ed70b36f64518afe9614b17bf">emitDirectiveOptionPop</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5d40610122e98fe3e856dc744a635ab">emitDirectiveOptionRelax</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace77e41900e7755dd0325fb278d40019">emitDirectiveOptionNoRelax</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39c20654e00b2a2b2ff981c7d24b3820">finish</a> () override</td>
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


<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-h">LoongArchELFStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoongArchTargetELFStreamer() {#aedd14021422c2f6fba707ef8188d6d28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoongArchTargetELFStreamer::LoongArchTargetELFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-h">LoongArchELFStreamer.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-cpp">LoongArchELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/loongarchabi/#af00c65f1a835c8452272468c2f09bd18">llvm::LoongArchABI::computeTargetABI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ab01b807c062ac4610366c6772ad5fd16">llvm::MCAssembler::getBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="#a16d255e2091283a2d8ed0f1fefa66d4e">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a1ef6ef4ff039e873e9f66e21e3e55e26">llvm::MCSubtargetInfo::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetstreamer/#ad1c62bfa8a6aed43a3bd48ae35c5943f">llvm::LoongArchTargetStreamer::LoongArchTargetStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetstreamer/#ae8d37ef587cdff4f4f014911326a6ea5">llvm::LoongArchTargetStreamer::setTargetABI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitDirectiveOptionNoRelax() {#ace77e41900e7755dd0325fb278d40019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchTargetELFStreamer::emitDirectiveOptionNoRelax ()</td>
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



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-h">LoongArchELFStreamer.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-cpp">LoongArchELFStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveOptionPop() {#a4c465a5ed70b36f64518afe9614b17bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchTargetELFStreamer::emitDirectiveOptionPop ()</td>
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



<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-h">LoongArchELFStreamer.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-cpp">LoongArchELFStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveOptionPush() {#ab951e5358f31ba739b98e3711ad698cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchTargetELFStreamer::emitDirectiveOptionPush ()</td>
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



<p>Declaration at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-h">LoongArchELFStreamer.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-cpp">LoongArchELFStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveOptionRelax() {#ad5d40610122e98fe3e856dc744a635ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchTargetELFStreamer::emitDirectiveOptionRelax ()</td>
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



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-h">LoongArchELFStreamer.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-cpp">LoongArchELFStreamer.cpp</a>.</p>

</div>
</div>

### finish() {#a39c20654e00b2a2b2ff981c7d24b3820}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchTargetELFStreamer::finish ()</td>
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



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-h">LoongArchELFStreamer.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-cpp">LoongArchELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/loongarchabi/#a19370946dd9514a9d3e18275e9f7b6fba7642477c0b9114a91ab95db52b0bf513">llvm::LoongArchABI::ABI_ILP32D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchabi/#a19370946dd9514a9d3e18275e9f7b6fba63a439edbbd4d87298181cbcf098e233">llvm::LoongArchABI::ABI_ILP32F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchabi/#a19370946dd9514a9d3e18275e9f7b6fba305d5ae54529960b7995ea72126052b9">llvm::LoongArchABI::ABI_ILP32S</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchabi/#a19370946dd9514a9d3e18275e9f7b6fbae688d614de378b5e595020a7ac3c378c">llvm::LoongArchABI::ABI_LP64D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchabi/#a19370946dd9514a9d3e18275e9f7b6fba09b260d81c6fe1cdf0386e65e5e3d5e4">llvm::LoongArchABI::ABI_LP64F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchabi/#a19370946dd9514a9d3e18275e9f7b6fba30063a83b98d2cffbcf49f46a8db223f">llvm::LoongArchABI::ABI_LP64S</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchabi/#a19370946dd9514a9d3e18275e9f7b6fbab3d8d71ca8b3f20b7551c6db0b02a9da">llvm::LoongArchABI::ABI_Unknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa9af75e358d1a762499c86e008ae60beacab43f47cc4137a3c6943f67584dc808">llvm::ELF::EF_LOONGARCH_ABI_DOUBLE_FLOAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa9af75e358d1a762499c86e008ae60bea6193c6bdc604bfc40c345a3cdd2e6b46">llvm::ELF::EF_LOONGARCH_ABI_SINGLE_FLOAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa9af75e358d1a762499c86e008ae60beace8deae684c011e7354548a9b71b9cf4">llvm::ELF::EF_LOONGARCH_ABI_SOFT_FLOAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa9af75e358d1a762499c86e008ae60bea3df3fb0ae9fc5bad498c5a2fa180e004">llvm::ELF::EF_LOONGARCH_OBJABI_V1</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#a7ef22747429dbc0220aa542d347b1cfa">llvm::MCTargetStreamer::finish</a>, <a href="#a16d255e2091283a2d8ed0f1fefa66d4e">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetstreamer/#a3275bdb25ec7a9b468af27cf950adf8f">llvm::LoongArchTargetStreamer::getTargetABI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getStreamer() {#a16d255e2091283a2d8ed0f1fefa66d4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCELFStreamer &amp; LoongArchTargetELFStreamer::getStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-h">LoongArchELFStreamer.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-cpp">LoongArchELFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#ac5c639960b526c507f505f9e3ebb915d">llvm::MCTargetStreamer::Streamer</a>.</p>


<p>Referenced by <a href="#a39c20654e00b2a2b2ff981c7d24b3820">finish</a> and <a href="#aedd14021422c2f6fba707ef8188d6d28">LoongArchTargetELFStreamer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-cpp">LoongArchELFStreamer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchelfstreamer-h">LoongArchELFStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
