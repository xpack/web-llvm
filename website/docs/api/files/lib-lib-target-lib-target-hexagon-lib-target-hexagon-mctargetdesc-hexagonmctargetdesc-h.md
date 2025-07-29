---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `HexagonMCTargetDesc.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include &lt;cstdint&gt;
#include "HexagonGenRegisterInfo.inc"
#include "HexagonGenInstrInfo.inc"
#include "HexagonGenSubtargetInfo.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc">Hexagon_MC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a488961bc7e64a2ed2db3af3876527dc2">Hexagon_POINTER_SIZE</a>&nbsp;&nbsp;&nbsp;4</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d8fb7f88a89f6400481f2387a9a5434">Hexagon_PointerSize</a>&nbsp;&nbsp;&nbsp;(<a href="#a488961bc7e64a2ed2db3af3876527dc2">Hexagon_POINTER_SIZE</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa87e50b38b9e4f4310b592e1075ec933">Hexagon_PointerSize_Bits</a>&nbsp;&nbsp;&nbsp;(<a href="#a488961bc7e64a2ed2db3af3876527dc2">Hexagon_POINTER_SIZE</a> * 8)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8219e6ca087e6d3049cabab930d99466">Hexagon_WordSize</a>&nbsp;&nbsp;&nbsp;<a href="#a0d8fb7f88a89f6400481f2387a9a5434">Hexagon_PointerSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad27bad8ce2d8f9ec0ffbc72785789177">Hexagon_WordSize_Bits</a>&nbsp;&nbsp;&nbsp;<a href="#aa87e50b38b9e4f4310b592e1075ec933">Hexagon_PointerSize_Bits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39298692b00c8dc4bb83650c5414b83b">HEXAGON_LRFP_SIZE</a>&nbsp;&nbsp;&nbsp;8</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3161e980be30851bf3f346ca0550ce">HEXAGON_INSTR_SIZE</a>&nbsp;&nbsp;&nbsp;4</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f76c0f5e34856920717e06ebc5f4dc3">HEXAGON_PACKET_SIZE</a>&nbsp;&nbsp;&nbsp;4</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033904b52204dcda98d7bfac83b6c679">HEXAGON_MAX_PACKET_SIZE</a>&nbsp;&nbsp;&nbsp;(<a href="#a8f76c0f5e34856920717e06ebc5f4dc3">HEXAGON_PACKET_SIZE</a> * <a href="#a8b3161e980be30851bf3f346ca0550ce">HEXAGON_INSTR_SIZE</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a558f9682c979b92bd33ddb69246dac31">HEXAGON_PACKET_INNER_SIZE</a>&nbsp;&nbsp;&nbsp;2</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a265d3c2f472273a5dd0c00f6472f6852">HEXAGON_PACKET_OUTER_SIZE</a>&nbsp;&nbsp;&nbsp;3</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4997a2808cebb7b14e08a5429558dc1">HEXAGON_PRESHUFFLE_PACKET_SIZE</a>&nbsp;&nbsp;&nbsp;(<a href="#a8f76c0f5e34856920717e06ebc5f4dc3">HEXAGON_PACKET_SIZE</a> + 3)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c9f94755fc7e265a71d0ada398e1d18">HEXAGON_GOT_SYM_NAME</a>&nbsp;&nbsp;&nbsp;"_GLOBAL_OFFSET_TABLE_"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08a185753458ada847ed2d41b47ac1d1">GET_REGINFO_ENUM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2433e9e503264e8ca019761dad9d06d1">GET_INSTRINFO_ENUM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d3b83a2fba56a1d4c1572a9f988db2">GET_INSTRINFO_SCHED_ENUM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d75935b44738c70f8b1cff3165755a">GET_INSTRINFO_MC_HELPER_DECLS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8e5d5d8b20c7c3550c60ac4a04e3c64">GET_SUBTARGETINFO_ENUM</a></td>
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

## Macro Definitions

### GET\_INSTRINFO\_ENUM {#a2433e9e503264e8ca019761dad9d06d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_ENUM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>

</div>
</div>

### GET\_INSTRINFO\_MC\_HELPER\_DECLS {#a30d75935b44738c70f8b1cff3165755a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_MC_HELPER_DECLS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>

</div>
</div>

### GET\_INSTRINFO\_SCHED\_ENUM {#a99d3b83a2fba56a1d4c1572a9f988db2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_SCHED_ENUM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>

</div>
</div>

### GET\_REGINFO\_ENUM {#a08a185753458ada847ed2d41b47ac1d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_REGINFO_ENUM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>

</div>
</div>

### GET\_SUBTARGETINFO\_ENUM {#ae8e5d5d8b20c7c3550c60ac4a04e3c64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_SUBTARGETINFO_ENUM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>

</div>
</div>

### HEXAGON\_GOT\_SYM\_NAME {#a9c9f94755fc7e265a71d0ada398e1d18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEXAGON_GOT_SYM_NAME&nbsp;&nbsp;&nbsp;"_GLOBAL_OFFSET_TABLE_"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a0dd725f6e5a4cd913d7baab3b49a78d0">llvm::HexagonTargetLowering::LowerGLOBAL_OFFSET_TABLE</a>.</p>

</div>
</div>

### HEXAGON\_INSTR\_SIZE {#a8b3161e980be30851bf3f346ca0550ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEXAGON_INSTR_SIZE&nbsp;&nbsp;&nbsp;4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmccodeemitter/#afc35abf7d94e2a6c70fe2227fbf2a7ce">llvm::HexagonMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#aabc01e9899fccd76ffd3a0c7da023fb5">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#a963b35ab133a680b8e40743b1780d099">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#aab2e617786f0429ea73422f70fdb0606">llvm::HexagonInstrInfo::getSize</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a4c00c27f8d0dd1c66b06b38458748a29">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::writeNopData</a>.</p>

</div>
</div>

### HEXAGON\_LRFP\_SIZE {#a39298692b00c8dc4bb83650c5414b83b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEXAGON_LRFP_SIZE&nbsp;&nbsp;&nbsp;8</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2c4c903d0a03629b92e4bcc894bbd793">llvm::HexagonPacketizerList::useCalleesSP</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#abf8fdc79c6fcc0fb997214d040de1063">llvm::HexagonPacketizerList::useCallersSP</a>.</p>

</div>
</div>

### HEXAGON\_MAX\_PACKET\_SIZE {#a033904b52204dcda98d7bfac83b6c679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEXAGON_MAX_PACKET_SIZE&nbsp;&nbsp;&nbsp;(<a href="#a8f76c0f5e34856920717e06ebc5f4dc3">HEXAGON_PACKET_SIZE</a> * <a href="#a8b3161e980be30851bf3f346ca0550ce">HEXAGON_INSTR_SIZE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#a963b35ab133a680b8e40743b1780d099">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getInstruction</a>.</p>

</div>
</div>

### HEXAGON\_PACKET\_INNER\_SIZE {#a558f9682c979b92bd33ddb69246dac31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEXAGON_PACKET_INNER_SIZE&nbsp;&nbsp;&nbsp;2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a64c7c69f960b66bee56f0df768811175">llvm::HexagonMCInstrInfo::LoopNeedsPadding</a>.</p>

</div>
</div>

### HEXAGON\_PACKET\_OUTER\_SIZE {#a265d3c2f472273a5dd0c00f6472f6852}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEXAGON_PACKET_OUTER_SIZE&nbsp;&nbsp;&nbsp;3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a64c7c69f960b66bee56f0df768811175">llvm::HexagonMCInstrInfo::LoopNeedsPadding</a>.</p>

</div>
</div>

### HEXAGON\_PACKET\_SIZE {#a8f76c0f5e34856920717e06ebc5f4dc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEXAGON_PACKET_SIZE&nbsp;&nbsp;&nbsp;4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonshuffler-cpp-/hexagonunitauction/#abb3e4a9e5557adcaaceabb13c1180495">anonymous{HexagonShuffler.cpp}::HexagonUnitAuction::bid</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmcinstrinfo-cpp-/#abda7c7a2d206ce064b97412b007ea5af">anonymous{HexagonMCInstrInfo.cpp}::canonicalizePacketImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a706aa084f85cdf448e79ad2d8be30bff">llvm::HexagonMCELFStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a11f3e864193e615bb8e8bda2cca24ff3">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::finishLayout</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#aabc01e9899fccd76ffd3a0c7da023fb5">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59e0da5b8f32f10d8fd69cb090730ecb">llvm::HexagonMCShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ad6600c9ef01f540a9d8a3991c2b13d25">llvm::HexagonMCInstrInfo::packetSizeSlots</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetasmstreamer/#ad17bf01008144e718fa39ffa0ef84733">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetAsmStreamer::prettyPrintAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#aa26f3ffae0b86b636abd35ddeda5d523">llvm::HexagonInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#af22c9938ad82cf97ee6cc8cf00d265cc">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonresource/#ae672a81b4fde62e83ed5bc647ff61ff2">llvm::HexagonResource::setAllUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonresource/#ad538abdb8f1c5e68c9211f06e5e52c49">llvm::HexagonResource::setUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a572425344ad3846264384af43858a5e1">llvm::HexagonShuffler::shuffle</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a714f31724f5b3410c7a947afeeb1b0f1">SlotMaskToText</a>.</p>

</div>
</div>

### Hexagon\_POINTER\_SIZE {#a488961bc7e64a2ed2db3af3876527dc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define Hexagon_POINTER_SIZE&nbsp;&nbsp;&nbsp;4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>

</div>
</div>

### Hexagon\_PointerSize {#a0d8fb7f88a89f6400481f2387a9a5434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define Hexagon_PointerSize&nbsp;&nbsp;&nbsp;(<a href="#a488961bc7e64a2ed2db3af3876527dc2">Hexagon_POINTER_SIZE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>.</p>

</div>
</div>

### Hexagon\_PointerSize\_Bits {#aa87e50b38b9e4f4310b592e1075ec933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define Hexagon_PointerSize_Bits&nbsp;&nbsp;&nbsp;(<a href="#a488961bc7e64a2ed2db3af3876527dc2">Hexagon_POINTER_SIZE</a> * 8)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>

</div>
</div>

### HEXAGON\_PRESHUFFLE\_PACKET\_SIZE {#ac4997a2808cebb7b14e08a5429558dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEXAGON_PRESHUFFLE_PACKET_SIZE&nbsp;&nbsp;&nbsp;(<a href="#a8f76c0f5e34856920717e06ebc5f4dc3">HEXAGON_PACKET_SIZE</a> + 3)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#adda8e3193ca3d31e415a2e4ac6089d50">llvm::HexagonMCInstrInfo::instruction</a>.</p>

</div>
</div>

### Hexagon\_WordSize {#a8219e6ca087e6d3049cabab930d99466}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define Hexagon_WordSize&nbsp;&nbsp;&nbsp;<a href="#a0d8fb7f88a89f6400481f2387a9a5434">Hexagon_PointerSize</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>

</div>
</div>

### Hexagon\_WordSize\_Bits {#ad27bad8ce2d8f9ec0ffbc72785789177}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define Hexagon_WordSize_Bits&nbsp;&nbsp;&nbsp;<a href="#aa87e50b38b9e4f4310b592e1075ec933">Hexagon_PointerSize_Bits</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
