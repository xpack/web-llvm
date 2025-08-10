---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `NVPTXTargetStreamer.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-h">NVPTXTargetStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxutilities-h">NVPTXUtilities.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">llvm/MC/MCObjectFileInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a336e03e121f34089ff6070a522fa93">isDwarfSection</a> (const MCObjectFileInfo *FI, const MCSection *Section)</td>
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

### isDwarfSection() {#a1a336e03e121f34089ff6070a522fa93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isDwarfSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a> * FI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxtargetstreamer-cpp">NVPTXTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ab7b38278009d729724c809dcbc9d5b4f">llvm::MCObjectFileInfo::getDwarfAbbrevDWOSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ac10c6a9d85782db274d19ef8f828d9fc">llvm::MCObjectFileInfo::getDwarfAbbrevSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a38d14819d39b592f82540549231ed94e">llvm::MCObjectFileInfo::getDwarfAccelNamespaceSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ab0a98f2924de06f55315c207f3c0eac1">llvm::MCObjectFileInfo::getDwarfAccelNamesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ae1a65d3a4229133502a782ab58741e60">llvm::MCObjectFileInfo::getDwarfAccelObjCSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a0f1b3ba79882a148045283d71753897a">llvm::MCObjectFileInfo::getDwarfAccelTypesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a7dd91b8042158479671aa8f357fd5f62">llvm::MCObjectFileInfo::getDwarfAddrSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ae17df2cce5c5b2cb1688d22f2d90820c">llvm::MCObjectFileInfo::getDwarfARangesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#adc1a8b3a5ab5c4c460feb4a00dd2a71c">llvm::MCObjectFileInfo::getDwarfCUIndexSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a9ba4c71757b3cefaeefeb6d440d0ee91">llvm::MCObjectFileInfo::getDwarfDebugInlineSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a7031b56e11bd03c7a1f7ab2e68d5d095">llvm::MCObjectFileInfo::getDwarfDebugNamesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a8357c20a6fa8dd32020a98ed65971587">llvm::MCObjectFileInfo::getDwarfFrameSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a29cddb4a82114802b9020d33d7e4dbd8">llvm::MCObjectFileInfo::getDwarfGnuPubNamesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a9eaa64fd2b7b36baec3fb81e574b6b8a">llvm::MCObjectFileInfo::getDwarfGnuPubTypesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a3d9643e39995d567cfd19465abcfabaf">llvm::MCObjectFileInfo::getDwarfInfoDWOSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a82d739b35c6534d476fc5bf7d2ee57cb">llvm::MCObjectFileInfo::getDwarfInfoSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a3b7d7a8e94a349e8343c52c9759bceb4">llvm::MCObjectFileInfo::getDwarfLineDWOSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a82d3abaa97d9734f17bdd52cfdf00fb7">llvm::MCObjectFileInfo::getDwarfLineSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a5e2906ef9fe9b6b1bef3e104b1519cd0">llvm::MCObjectFileInfo::getDwarfLineStrSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ae0c42bab7cf6d48b020adbec53263a2c">llvm::MCObjectFileInfo::getDwarfLocDWOSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ae7548b994352e41c0a628936d3f75c61">llvm::MCObjectFileInfo::getDwarfLocSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ae04d121e734cd5ad456233e5d6ebbb3c">llvm::MCObjectFileInfo::getDwarfMacinfoSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a49eb3fca43b2ceca3ff8c706fae7ddab">llvm::MCObjectFileInfo::getDwarfPubNamesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a97622da3f5114dfa0bb2f2285bf37cea">llvm::MCObjectFileInfo::getDwarfPubTypesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a31df4edd580fc4f6e43318cd9c5ed5bc">llvm::MCObjectFileInfo::getDwarfRangesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#aa89ba1b4a04c6aab9e36521b0af3212e">llvm::MCObjectFileInfo::getDwarfStrDWOSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a2be455ebf2215c76244c7d1cc4697492">llvm::MCObjectFileInfo::getDwarfStrOffDWOSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a3d677a1ab07bb4796933369f69396459">llvm::MCObjectFileInfo::getDwarfStrOffSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a5915c91abcb7f7eb43cae094ec8b4ec7">llvm::MCObjectFileInfo::getDwarfStrSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ac28a6e4a483c4c56f254884ed9024648">llvm::MCObjectFileInfo::getDwarfSwiftASTSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a6f7b6409e225107d1b3e430471b80c50">llvm::MCObjectFileInfo::getDwarfTUIndexSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a47aba8387dcc1520ee5846c047be762d">llvm::MCObjectFileInfo::getDwarfTypesDWOSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetstreamer/#ab7ccb3b4d754b7e2ab62aca1113ab56d">llvm::NVPTXTargetStreamer::changeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a3d2f87d599884cbc4bbdbd1fa68052f9">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFType&lt; DataEndianness, false &gt; &gt;::forEachRelaRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a9b05ea912d8cd67c968c579e3d81cef7">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFType&lt; DataEndianness, false &gt; &gt;::forEachRelRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#af3ffb18516cfadbf9131f7d6b17fad71">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySections</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
