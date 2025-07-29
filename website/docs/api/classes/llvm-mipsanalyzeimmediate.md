---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipsanalyzeimmediate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MipsAnalyzeImmediate` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MipsAnalyzeImmediate { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">Target/Mips/MipsAnalyzeImmediate.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a950c182688461d603b8950f9041b5385">InstSeq</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mipsanalyzeimmediate/inst">Inst</a>, 7 &gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada7a6ab1fc8b2f7f1efddf811e660ee2">InstSeqLs</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a950c182688461d603b8950f9041b5385">InstSeq</a>, 5 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a950c182688461d603b8950f9041b5385">InstSeq</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ac42236b215222ea27330943ff3f99">Analyze</a> (uint64_t Imm, unsigned Size, bool LastInstrIsADDiu)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze - Get an instruction sequence to load immediate Imm. <a href="#a80ac42236b215222ea27330943ff3f99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1311342a18d7650deedb2c7388f11b8">AddInstr</a> (InstSeqLs &amp;SeqLs, const Inst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddInstr - Add I to all instruction sequences in SeqLs. <a href="#ab1311342a18d7650deedb2c7388f11b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e53eb0a8cdec326720e4ba6bc3cb785">GetInstSeqLsADDiu</a> (uint64_t Imm, unsigned RemSize, InstSeqLs &amp;SeqLs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetInstSeqLsADDiu - Get instruction sequences which end with an ADDiu to load immediate Imm. <a href="#a7e53eb0a8cdec326720e4ba6bc3cb785">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac4ceb2af75127fdfcc4af447e0d70b2">GetInstSeqLsORi</a> (uint64_t Imm, unsigned RemSize, InstSeqLs &amp;SeqLs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetInstSeqLsORi - Get instrutcion sequences which end with an ORi to load immediate Imm. <a href="#aac4ceb2af75127fdfcc4af447e0d70b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a9d5cd94b0d5acfba9f185ee087cd59">GetInstSeqLsSLL</a> (uint64_t Imm, unsigned RemSize, InstSeqLs &amp;SeqLs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetInstSeqLsSLL - Get instruction sequences which end with a SLL to load immediate Imm. <a href="#a6a9d5cd94b0d5acfba9f185ee087cd59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ab474539795bee8746359dfbfc3f10d">GetInstSeqLs</a> (uint64_t Imm, unsigned RemSize, InstSeqLs &amp;SeqLs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetInstSeqLs - Get instruction sequences to load immediate Imm. <a href="#a7ab474539795bee8746359dfbfc3f10d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a136462e7d57d2da02c4a9a1d563765af">ReplaceADDiuSLLWithLUi</a> (InstSeq &amp;Seq)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReplaceADDiuSLLWithLUi - Replace an ADDiu &amp; SLL pair with a LUi. <a href="#a136462e7d57d2da02c4a9a1d563765af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa916cf6e490b0bb28375d4654b31f335">GetShortestSeq</a> (InstSeqLs &amp;SeqLs, InstSeq &amp;Insts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetShortestSeq - Find the shortest instruction sequence in SeqLs and return it in Insts. <a href="#aa916cf6e490b0bb28375d4654b31f335">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dbfcb903b68ad56f45c97fbdece045e">Size</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addc9e1265ed6f70f9e9d2d444bad07ec">ADDiu</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacccd8de27c432d6ded373d5e4c86cf9">ORi</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8f9b55bd641f6664bcab738ceae1522">SLL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e2151fc99f2407c36fc0b5c3b4fab2b">LUi</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a950c182688461d603b8950f9041b5385">InstSeq</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a526bbffd06e915d231ed6818b9a51610">Insts</a></td>
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


<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### InstSeq {#a950c182688461d603b8950f9041b5385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MipsAnalyzeImmediate::InstSeq =  SmallVector&lt;Inst, 7&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### InstSeqLs {#ada7a6ab1fc8b2f7f1efddf811e660ee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MipsAnalyzeImmediate::InstSeqLs =  SmallVector&lt;InstSeq, 5&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Analyze() {#a80ac42236b215222ea27330943ff3f99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsAnalyzeImmediate::InstSeq &amp; MipsAnalyzeImmediate::Analyze (uint64_t Imm, unsigned Size, bool LastInstrIsADDiu)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze - Get an instruction sequence to load immediate Imm.</p>


<p>The last instruction in the sequence must be an ADDiu if LastInstrIsADDiu is true;</p>


<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-cpp">MipsAnalyzeImmediate.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#aa40f4913df15aca03301144b7f1673df">llvm::MipsSEInstrInfo::loadImmediate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AddInstr() {#ab1311342a18d7650deedb2c7388f11b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAnalyzeImmediate::AddInstr (<a href="/web-llvm/docs/api/classes/llvm/smallvector">InstSeqLs</a> &amp; SeqLs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mipsanalyzeimmediate/inst">Inst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AddInstr - Add I to all instruction sequences in SeqLs.</p>

<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-cpp">MipsAnalyzeImmediate.cpp</a>.</p>

</div>
</div>

### GetInstSeqLs() {#a7ab474539795bee8746359dfbfc3f10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAnalyzeImmediate::GetInstSeqLs (uint64_t Imm, unsigned RemSize, <a href="/web-llvm/docs/api/classes/llvm/smallvector">InstSeqLs</a> &amp; SeqLs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetInstSeqLs - Get instruction sequences to load immediate Imm.</p>

<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-cpp">MipsAnalyzeImmediate.cpp</a>.</p>

</div>
</div>

### GetInstSeqLsADDiu() {#a7e53eb0a8cdec326720e4ba6bc3cb785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAnalyzeImmediate::GetInstSeqLsADDiu (uint64_t Imm, unsigned RemSize, <a href="/web-llvm/docs/api/classes/llvm/smallvector">InstSeqLs</a> &amp; SeqLs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetInstSeqLsADDiu - Get instruction sequences which end with an ADDiu to load immediate Imm.</p>

<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-cpp">MipsAnalyzeImmediate.cpp</a>.</p>

</div>
</div>

### GetInstSeqLsORi() {#aac4ceb2af75127fdfcc4af447e0d70b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAnalyzeImmediate::GetInstSeqLsORi (uint64_t Imm, unsigned RemSize, <a href="/web-llvm/docs/api/classes/llvm/smallvector">InstSeqLs</a> &amp; SeqLs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetInstSeqLsORi - Get instrutcion sequences which end with an ORi to load immediate Imm.</p>

<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-cpp">MipsAnalyzeImmediate.cpp</a>.</p>

</div>
</div>

### GetInstSeqLsSLL() {#a6a9d5cd94b0d5acfba9f185ee087cd59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAnalyzeImmediate::GetInstSeqLsSLL (uint64_t Imm, unsigned RemSize, <a href="/web-llvm/docs/api/classes/llvm/smallvector">InstSeqLs</a> &amp; SeqLs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetInstSeqLsSLL - Get instruction sequences which end with a SLL to load immediate Imm.</p>

<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-cpp">MipsAnalyzeImmediate.cpp</a>.</p>

</div>
</div>

### GetShortestSeq() {#aa916cf6e490b0bb28375d4654b31f335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAnalyzeImmediate::GetShortestSeq (<a href="/web-llvm/docs/api/classes/llvm/smallvector">InstSeqLs</a> &amp; SeqLs, <a href="#a950c182688461d603b8950f9041b5385">InstSeq</a> &amp; Insts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetShortestSeq - Find the shortest instruction sequence in SeqLs and return it in Insts.</p>

<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-cpp">MipsAnalyzeImmediate.cpp</a>.</p>

</div>
</div>

### ReplaceADDiuSLLWithLUi() {#a136462e7d57d2da02c4a9a1d563765af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAnalyzeImmediate::ReplaceADDiuSLLWithLUi (<a href="#a950c182688461d603b8950f9041b5385">InstSeq</a> &amp; Seq)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReplaceADDiuSLLWithLUi - Replace an ADDiu &amp; SLL pair with a LUi.</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-cpp">MipsAnalyzeImmediate.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ADDiu {#addc9e1265ed6f70f9e9d2d444bad07ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MipsAnalyzeImmediate::ADDiu</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>.</p>

</div>
</div>

### Insts {#a526bbffd06e915d231ed6818b9a51610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstSeq llvm::MipsAnalyzeImmediate::Insts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>.</p>

</div>
</div>

### LUi {#a1e2151fc99f2407c36fc0b5c3b4fab2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MipsAnalyzeImmediate::LUi</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>.</p>

</div>
</div>

### ORi {#aacccd8de27c432d6ded373d5e4c86cf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MipsAnalyzeImmediate::ORi</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>.</p>

</div>
</div>

### Size {#a5dbfcb903b68ad56f45c97fbdece045e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MipsAnalyzeImmediate::Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>.</p>

</div>
</div>

### SLL {#ab8f9b55bd641f6664bcab738ceae1522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MipsAnalyzeImmediate::SLL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-cpp">MipsAnalyzeImmediate.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsanalyzeimmediate-h">MipsAnalyzeImmediate.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
