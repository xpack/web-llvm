---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/riscvtargetstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RISCVTargetStreamer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RISCVTargetStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">Target/RISCV/MCTargetDesc/RISCVTargetStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> specific streamer interface. <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/riscvtargetasmstreamer">RISCVTargetAsmStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer">RISCVTargetELFStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac83b5860adb86b38401ac54720a7c18a">RISCVTargetStreamer</a> (MCStreamer &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae02d35db34523a188c216a682f82d873">finish</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2610f65cf56dce6f9e958d4a11f8d5e">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adce8956519aaedfe45456b455a9483f3">emitDirectiveOptionPush</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d2a6ad6e0f224c286d671bf3f70109">emitDirectiveOptionPop</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d9cf44559c3d0f3b63d31774bf6e98d">emitDirectiveOptionPIC</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5e37406200ae6ec38752959de7f2813">emitDirectiveOptionNoPIC</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdafc0d21f8b56e1bef93ff919cc0f86">emitDirectiveOptionRVC</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af57053f6636ae936830651bebc6ff1b7">emitDirectiveOptionNoRVC</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bd44b0a79a41c84bd94f151725b317">emitDirectiveOptionRelax</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33e44ce2b1d4c9ce9218143601a23de4">emitDirectiveOptionNoRelax</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb72aeaf1ca10e92361146626de0dda1">emitDirectiveOptionArch</a> (ArrayRef&lt; RISCVOptionArchArg &gt; Args)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6db464b4868f1f28b4345661fad4a1e4">emitDirectiveVariantCC</a> (MCSymbol &amp;Symbol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a548539cdde094b2131ec9ef845c9e2a7">emitAttribute</a> (unsigned Attribute, unsigned Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad672f96e296c202a0a34c296a1c19400">finishAttributeSection</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b7bc2393ec346c75b9bfe01e817ef23">emitTextAttribute</a> (unsigned Attribute, StringRef String)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8154b83e24f25781477854c2e16b7f7c">emitIntTextAttribute</a> (unsigned Attribute, unsigned IntValue, StringRef StringValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a762f3b75bc1c039e73a809ddabc26065">emitTargetAttributes</a> (const MCSubtargetInfo &amp;STI, bool EmitStackAlign)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac40598db79afc18796b74db7191b7cec">setTargetABI</a> (RISCVABI::ABI ABI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9">RISCVABI::ABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b18e59e7298f6b2e6a177b1293cd5aa">getTargetABI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77c52829c20b2ac68628b01d1cc5cdf3">setFlagsFromFeatures</a> (const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e31345063654cc76ef62209b31b2f1f">hasRVC</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49cc32e8b3e0ea94996137b137a855f7">hasTSO</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9">RISCVABI::ABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab00447f3488c1de7611c88ad73e7552f">TargetABI</a> = <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9a8f595b6bd8825688b9ac7939a949c829">RISCVABI::ABI_Unknown</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78fee9def29f7fbdeda380cce7a853c5">HasRVC</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e13a03262f77d4086f8be8499f2c891">HasTSO</a> = false</td>
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


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVTargetStreamer() {#ac83b5860adb86b38401ac54720a7c18a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVTargetStreamer::RISCVTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#acfff4f9a518231ee043200a694fcbafa">llvm::MCTargetStreamer::MCTargetStreamer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetasmstreamer/#a6e055b7d58f23a707e7b43b03ffef737">llvm::RISCVTargetAsmStreamer::RISCVTargetAsmStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer/#a9c657032eafd38a8fa07606efe9af3a7">llvm::RISCVTargetELFStreamer::RISCVTargetELFStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitAttribute() {#a548539cdde094b2131ec9ef845c9e2a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitAttribute (unsigned Attribute, unsigned Value)</td>
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



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="#a762f3b75bc1c039e73a809ddabc26065">emitTargetAttributes</a>.</p>

</div>
</div>

### emitDirectiveOptionArch() {#acb72aeaf1ca10e92361146626de0dda1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitDirectiveOptionArch (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/riscvoptionarcharg">RISCVOptionArchArg</a> &gt; Args)</td>
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



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#ada43bee484c2300200c9ab0884003563">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitDirectiveOptionArch</a>.</p>

</div>
</div>

### emitDirectiveOptionNoPIC() {#ab5e37406200ae6ec38752959de7f2813}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitDirectiveOptionNoPIC ()</td>
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



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveOptionNoRelax() {#a33e44ce2b1d4c9ce9218143601a23de4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitDirectiveOptionNoRelax ()</td>
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



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveOptionNoRVC() {#af57053f6636ae936830651bebc6ff1b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitDirectiveOptionNoRVC ()</td>
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



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveOptionPIC() {#a1d9cf44559c3d0f3b63d31774bf6e98d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitDirectiveOptionPIC ()</td>
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



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveOptionPop() {#aa0d2a6ad6e0f224c286d671bf3f70109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitDirectiveOptionPop ()</td>
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



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveOptionPush() {#adce8956519aaedfe45456b455a9483f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitDirectiveOptionPush ()</td>
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



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#ada43bee484c2300200c9ab0884003563">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitDirectiveOptionArch</a>.</p>

</div>
</div>

### emitDirectiveOptionRelax() {#ae8bd44b0a79a41c84bd94f151725b317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitDirectiveOptionRelax ()</td>
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



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveOptionRVC() {#afdafc0d21f8b56e1bef93ff919cc0f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitDirectiveOptionRVC ()</td>
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



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitDirectiveVariantCC() {#a6db464b4868f1f28b4345661fad4a1e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitDirectiveVariantCC (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Symbol)</td>
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



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a97987d0c2e034c4a02c3368e8372a5d9">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitFunctionEntryLabel</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a046ce1a28d601dbc32167434da7ce4cd">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::EmitHwasanMemaccessSymbols</a>.</p>

</div>
</div>

### emitIntTextAttribute() {#a8154b83e24f25781477854c2e16b7f7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitIntTextAttribute (unsigned Attribute, unsigned IntValue, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StringValue)</td>
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



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitTargetAttributes() {#a762f3b75bc1c039e73a809ddabc26065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitTargetAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, bool EmitStackAlign)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/riscvattrs/#a690f0d5292c1bf862c1ec8fb3126bacba9214e1300943d45ef0124bc7ba9770c9">llvm::RISCVAttrs::A6C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvattrs/#a690f0d5292c1bf862c1ec8fb3126bacba5e5e1c382c45b7ed86f9849450029595">llvm::RISCVAttrs::A6S</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9a9e062b1814798f2a29e2b28e74a36bc1">llvm::RISCVABI::ABI_ILP32E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9adc7da95e1193beba354466672c1cdb38">llvm::RISCVABI::ABI_LP64E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvattrs/#ac0e6d65dbd5acd98356e49a2ea9c4e72a0100b4efc71f09c9d6a16d6f32ff9daa">llvm::RISCVAttrs::ARCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvattrs/#ac0e6d65dbd5acd98356e49a2ea9c4e72a4794d2bd27775559be203df4503d3880">llvm::RISCVAttrs::ATOMIC_ABI</a>, <a href="#a548539cdde094b2131ec9ef845c9e2a7">emitAttribute</a>, <a href="#a6b7bc2393ec346c75b9bfe01e817ef23">emitTextAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvfeatures/#aeff18ccfe73c98dd2078d7523eb4db04">llvm::RISCVFeatures::parseFeatureBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp/#a7bf92252ab98dfda8031b6fb068fc988">RiscvAbiAttr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvattrs/#ac0e6d65dbd5acd98356e49a2ea9c4e72a35adc9b32c5d6aafb557089b94f65405">llvm::RISCVAttrs::STACK_ALIGN</a>.</p>

</div>
</div>

### emitTextAttribute() {#a6b7bc2393ec346c75b9bfe01e817ef23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::emitTextAttribute (unsigned Attribute, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> String)</td>
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



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>


<p>Referenced by <a href="#a762f3b75bc1c039e73a809ddabc26065">emitTargetAttributes</a>.</p>

</div>
</div>

### finish() {#ae02d35db34523a188c216a682f82d873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::finish ()</td>
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



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#ad672f96e296c202a0a34c296a1c19400">finishAttributeSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer/#ad53a4c9271ebddb1171b900ee01381fd">llvm::RISCVTargetELFStreamer::finish</a>.</p>

</div>
</div>

### finishAttributeSection() {#ad672f96e296c202a0a34c296a1c19400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::finishAttributeSection ()</td>
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



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a6a107fc2138c3f071a960cbc65dc21f3">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitEndOfAsmFile</a> and <a href="#ae02d35db34523a188c216a682f82d873">finish</a>.</p>

</div>
</div>

### getTargetABI() {#a5b18e59e7298f6b2e6a177b1293cd5aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVABI::ABI llvm::RISCVTargetStreamer::getTargetABI ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer/#ad53a4c9271ebddb1171b900ee01381fd">llvm::RISCVTargetELFStreamer::finish</a>.</p>

</div>
</div>

### hasRVC() {#a0e31345063654cc76ef62209b31b2f1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVTargetStreamer::hasRVC ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer/#ad53a4c9271ebddb1171b900ee01381fd">llvm::RISCVTargetELFStreamer::finish</a>.</p>

</div>
</div>

### hasTSO() {#a49cc32e8b3e0ea94996137b137a855f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVTargetStreamer::hasTSO ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer/#ad53a4c9271ebddb1171b900ee01381fd">llvm::RISCVTargetELFStreamer::finish</a>.</p>

</div>
</div>

### reset() {#ad2610f65cf56dce6f9e958d4a11f8d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::reset ()</td>
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



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>

</div>
</div>

### setFlagsFromFeatures() {#a77c52829c20b2ac68628b01d1cc5cdf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::setFlagsFromFeatures (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#ada96d67c594bff6ca1c65fb281f82ca5">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitStartOfAsmFile</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer/#a9c657032eafd38a8fa07606efe9af3a7">llvm::RISCVTargetELFStreamer::RISCVTargetELFStreamer</a>.</p>

</div>
</div>

### setTargetABI() {#ac40598db79afc18796b74db7191b7cec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVTargetStreamer::setTargetABI (<a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9">RISCVABI::ABI</a> ABI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9a8f595b6bd8825688b9ac7939a949c829">llvm::RISCVABI::ABI_Unknown</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#ada96d67c594bff6ca1c65fb281f82ca5">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitStartOfAsmFile</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetelfstreamer/#a9c657032eafd38a8fa07606efe9af3a7">llvm::RISCVTargetELFStreamer::RISCVTargetELFStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasRVC {#a78fee9def29f7fbdeda380cce7a853c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVTargetStreamer::HasRVC = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>.</p>

</div>
</div>

### HasTSO {#a4e13a03262f77d4086f8be8499f2c891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVTargetStreamer::HasTSO = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>.</p>

</div>
</div>

### TargetABI {#ab00447f3488c1de7611c88ad73e7552f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVABI::ABI llvm::RISCVTargetStreamer::TargetABI = <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9a8f595b6bd8825688b9ac7939a949c829">RISCVABI::ABI_Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-cpp">RISCVTargetStreamer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">RISCVTargetStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
