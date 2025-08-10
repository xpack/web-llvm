---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `HexagonMCCodeEmitter.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-h">MCTargetDesc/HexagonMCCodeEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonbaseinfo-h">MCTargetDesc/HexagonBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonfixupkinds-h">MCTargetDesc/HexagonFixupKinds.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">MCTargetDesc/HexagonMCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">MCTargetDesc/HexagonMCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">MCTargetDesc/HexagonMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">llvm/MC/MCFixup.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">llvm/Support/EndianStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;map&gt;
#include &lt;string&gt;
#include &lt;vector&gt;
#include "HexagonGenMCCodeEmitter.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab011e01ce4f38acbf30a95de5c65db77">STATISTIC</a> (MCNumEmitted, "Number of MC instructions emitted")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a274bccca247b2503b7fe53c48154e9de">RegisterMatches</a> (MCRegister Consumer, MCRegister Producer, MCRegister Producer2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f0a58c66ed5816ddf1c3f461f6b9c7">raise_relocation_error</a> (unsigned Width, unsigned Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4a04635b13a1e1f8bcdd008f64953b0">isPCRel</a> (unsigned Kind)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a06108e2c3151def44cbf211c24d915">fixup_Invalid</a> = ~0u</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::map&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1752a7e5cae3d8df53aa4f986443e358">ExtFixups</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::map&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6d788cab200ab55334f06329fb70580">StdFixups</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"mccodeemitter"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>&nbsp;&nbsp;&nbsp;<a href="#a2a06108e2c3151def44cbf211c24d915">fixup_Invalid</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a82c4835f55136d206fd9b693eaed81">P</a>(x)&nbsp;&nbsp;&nbsp;Hexagon::fixup_Hexagon##x</td>
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

### isPCRel() {#ab4a04635b13a1e1f8bcdd008f64953b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isPCRel (unsigned Kind)</td>
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



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp">HexagonMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa58d886d876663e910bb42d4711cd3a47">llvm::Hexagon::fixup_Hexagon_32_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa94c391478d4495def35b608d8d49aecd">llvm::Hexagon::fixup_Hexagon_6_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa3892bebaed52b6bb7704fb4705bfd3ea">llvm::Hexagon::fixup_Hexagon_B13_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa5742fbb01e95827aa1d4fed0e8bf49db">llvm::Hexagon::fixup_Hexagon_B13_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8e7f405b8420c4b38d640cd008c0f1b5">llvm::Hexagon::fixup_Hexagon_B15_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fadba6b69224d9575e3845b5a1d5fbf437">llvm::Hexagon::fixup_Hexagon_B15_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9d43956f2ba0ad2b6a14b6f15d8a9d1b">llvm::Hexagon::fixup_Hexagon_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fadfd8c0fda1dc285ceabeb34ddcd3a226">llvm::Hexagon::fixup_Hexagon_B22_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa659fb706c1401f9541effc64fa54ba68">llvm::Hexagon::fixup_Hexagon_B32_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faec512985edaee90285f046598a99c063">llvm::Hexagon::fixup_Hexagon_B7_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa2fc452a2d9e80df1f68ec27693e9632c">llvm::Hexagon::fixup_Hexagon_B7_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8433e062504192a5113a2e9d08e911e2">llvm::Hexagon::fixup_Hexagon_B9_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faf7ad305a417f6572f3ecc7d3d73179ca">llvm::Hexagon::fixup_Hexagon_B9_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9a689f3ed64b9083dc9b5b9d8cfaaf68">llvm::Hexagon::fixup_Hexagon_GD_PLT_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa95bb47d6433e0d1496f52a00247731dd">llvm::Hexagon::fixup_Hexagon_GD_PLT_B22_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa1d78e3d110cd9b108eae5c7dfe20b9c3">llvm::Hexagon::fixup_Hexagon_LD_PLT_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa43847e6cd11cfe076051a9997931709a">llvm::Hexagon::fixup_Hexagon_LD_PLT_B22_PCREL_X</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa5de78d76e447c09d64aff72960145cd2">llvm::Hexagon::fixup_Hexagon_PLT_B22_PCREL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0fa713c521bb3fb8e554dd2a1abd8623">llvm::getFixupForSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a2f19df74000cc1d12eb853e57c867afb">getImmFixupKind</a>.</p>

</div>
</div>

### raise\_relocation\_error() {#a54f0a58c66ed5816ddf1c3f461f6b9c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raise_relocation_error (unsigned Width, unsigned Kind)</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp">HexagonMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>

</div>
</div>

### RegisterMatches() {#a274bccca247b2503b7fe53c48154e9de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterMatches (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Consumer, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Producer, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Producer2)</td>
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



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp">HexagonMCCodeEmitter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a32abefbdb58d94344aae7e32f982b037">llvm::HexagonMCInstrInfo::IsSingleConsumerRefPairProducer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#a8060e25eb66776205e632d4368d1d955">llvm::HexagonMCCodeEmitter::getMachineOpValue</a>.</p>

</div>
</div>

### STATISTIC() {#ab011e01ce4f38acbf30a95de5c65db77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (MCNumEmitted, "Number of MC <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> emitted")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp">HexagonMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ExtFixups {#a1752a7e5cae3d8df53aa4f986443e358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::map&lt;unsigned, std::vector&lt;unsigned&gt; &gt; ExtFixups</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp">HexagonMCCodeEmitter.cpp</a>.</p>

</div>
</div>

### fixup\_Invalid {#a2a06108e2c3151def44cbf211c24d915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned fixup_Invalid = ~0u</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp">HexagonMCCodeEmitter.cpp</a>.</p>

</div>
</div>

### StdFixups {#ad6d788cab200ab55334f06329fb70580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::map&lt;unsigned, std::vector&lt;unsigned&gt; &gt; StdFixups</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp">HexagonMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### \_ {#ae4dfd7b0d66121016d6466d2ff10e8ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _&nbsp;&nbsp;&nbsp;<a href="#a2a06108e2c3151def44cbf211c24d915">fixup_Invalid</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp">HexagonMCCodeEmitter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aa10cee1a6cc1fbb381e3dab0c92c4cb2">canFoldStoreIntoLibCallOutputPointers</a>, <a href="/web-llvm/docs/api/classes/llvm/ctxprofanalysis/#a4dd66bb1f3a24ebaf94d2f204a700e4a">llvm::CtxProfAnalysis::collectIndirectCallPromotionList</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#afcbf4a19be078644e784b539379d59b7">llvm::LoopVectorizationCostModel::collectInstsToScalarize</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a8dc41af84f49f4b418bddf15547755af">llvm::VPRecipeBuilder::collectScaledReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a0ac5df8f0304981180d602dacb13512c">llvm::LoopVectorizationCostModel::collectValuesToIgnore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a436965f98f9e4301e33096c32ed6dbd2">llvm::RISCVInstrInfo::copyPhysRegVector</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream/#a15311330f8fe55f5a39073ea9eab65a3">llvm::raw_socket_stream::createConnectedUnix</a>, <a href="/web-llvm/docs/api/classes/llvm/listeningsocket/#a22cd57e089541409aa05153237a44729">llvm::ListeningSocket::createUnix</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#aba8001b30fa09b1b983c01fb4f4f76f5">llvm::ModuleSummaryIndex::exportToDot</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/recordsslice/#a0c99d02cd99463b4161265f0c6cb30fd">llvm::MachO::RecordsSlice::findObjCIVar</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter/#a5796fcdd25688200886925c4f3878799">anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::forEachModule</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofcontext/#a3cbd01f1befb9ced15aca648c6b5b963">llvm::PGOCtxProfContext::getContainedGuids</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaaresult/#accb256ada9f5d92e5a776e459618cd1d">llvm::BasicAAResult::getModRefInfoMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a25e479981fb1f791dba4f32a891d6ff2">inferInitializes</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofcontext/#a3ac7c86a99f1701c23abde84be3db23d">llvm::PGOCtxProfContext::ingestAllContexts</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#ad5393f64ef6c65d1f090169819b68598">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::instrumentAsmArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#aa89c785d5856324faf763817eb091191">llvm::Record::isSubClassOf</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a9b4a7a3640fe5f917ba40dedfaa50e28">llvm::Record::isSubClassOf</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a4172c40c16e915c478ab94311e76e1a8">llvm::MCAssembler::layout</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a0dd10d6063d14925c308957d2c642fea">llvm::orc::LLJIT::LLJIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#a5430de9bfca0f2700d4afb0121e156fe">LLTToBId</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ad2488daf071559b63411016a2bf09b95">LLTToId</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#adcd2edb47f46a28037d9f738f0cd1aa8">llvm::orc::ExecutionSession::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#add44d478a1c329e77659000039f6ae74">llvm::CombinerHelper::matchConstantFoldFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ac2bfcc1d9b7f5effd45c65a5f973df13">matchUniformityAndLLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae69dd69c07ac063e85030679ceba2f93">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp/#a06c425cae4fdc2e2a65d456ec177907a">preorderVisit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9469fd548994812c12e4c10d42ec82a3">llvm::promoteCallWithIfThenElse</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/requireallmachinefunctionpropertiespass/#ab20042dac1f44de9b970b8c05fc0bc8d">anonymous{PassBuilder.cpp}::RequireAllMachineFunctionPropertiesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ctxprofanalysis/#a0cbc02f8988e793203b0a4f7e75587c0">llvm::CtxProfAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndppcombinepass/#a91369071e0136a16498790096d679182">llvm::GCNDPPCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariablesanalysis/#a9fefe50c560d6fab257603f7e8b20ecc">llvm::LiveDebugVariablesAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machinecsepass/#a495f06046288f4b8207cd36d72d19939">llvm::MachineCSEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/peepholeoptimizerpass/#a80af47b78e07ddb33af6e7d86af034df">llvm::PeepholeOptimizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocfastpass/#a8e1ca8e01852af346174b94ad5d8630c">llvm::RegAllocFastPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/siloadstoreoptimizerpass/#a73bd665c6e03c1dc196c107a450e228a">llvm::SILoadStoreOptimizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/silowersgprspillspass/#acc251fdad2ff98bf8f116ecbd8e93b14">llvm::SILowerSGPRSpillsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sioptimizevgprliverangepass/#a7bf8baafeef111584b003c06f997080a">llvm::SIOptimizeVGPRLiveRangePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicatepassbase/#a0780ac5d6a2962adf46e1c611e6ca6fa">llvm::TailDuplicatePassBase&lt; DerivedT, PreRegAlloc &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/twoaddressinstructionpass/#ab9a6f420b6121320d58d159773b8d92a">llvm::TwoAddressInstructionPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/sroalegacypass/#a8e87a8ac1e3d62aaa253240fc597f797">anonymous{SROA.cpp}::SROALegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8413a9136fa25e3dfdebc5cb8c111002">llvm::simplifyLoopIVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#af376f4f0e0b55e40407912678b736863">SRAGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#af4ef065f1b58988c5bb0b6ec76846366">llvm::RISCVISAInfo::toFeatures</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pgoctxprofreader-cpp-/#a857d77a5beee71976041ebb6050964df">anonymous{PGOCtxProfReader.cpp}::toYaml</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a352cfb70ee9de3e1b38106be8cb05a87">llvm::MCSection::~MCSection</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader/#afa3aedfb1ee64ce5ef518842c822ef9e">llvm::memprof::RawMemProfReader::~RawMemProfReader</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/simplelazyreexportsspeculator/#a1165ef634a4a27cc234bcc1cd60f98ed">llvm::orc::SimpleLazyReexportsSpeculator::~SimpleLazyReexportsSpeculator</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"mccodeemitter"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp">HexagonMCCodeEmitter.cpp</a>.</p>

</div>
</div>

### P {#a1a82c4835f55136d206fd9b693eaed81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define P(x)&nbsp;&nbsp;&nbsp;Hexagon::fixup_Hexagon##x</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp">HexagonMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
