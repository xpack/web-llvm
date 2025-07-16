---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipsdagtodagisel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MipsDAGToDAGISel` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MipsDAGToDAGISel { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">Target/Mips/MipsISelDAGToDAG.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a> - This is the common base class used for SelectionDAG-based pattern-matching instruction selectors. <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mips16dagtodagisel">Mips16DAGToDAGISel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipssedagtodagisel">MipsSEDAGToDAGISel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3931d9b23cbb2ff915d15fc6b0b03370">MipsDAGToDAGISel</a> ()=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afee3aae4be37ccc4663f59177052423d">MipsDAGToDAGISel</a> (MipsTargetMachine &amp;TM, CodeGenOptLevel OL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a2d92bd3c713509518df298adad4c7">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7458beece4ee2d29e63e8e34bb268b6c">getGlobalBaseReg</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getGlobalBaseReg - Output the instructions required to put the GOT address into a register. <a href="#a7458beece4ee2d29e63e8e34bb268b6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9da26514e523213f2571930e19fe430">selectAddrRegImm</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>(reg + imm). <a href="#af9da26514e523213f2571930e19fe430">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d8acd67c2dac470a96d2a8207baa58d">selectAddrDefault</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fall back on this function if all else fails. <a href="#a7d8acd67c2dac470a96d2a8207baa58d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b5344bf4408832e04dd9ee490a5421">selectIntAddr</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match integer address pattern. <a href="#a13b5344bf4408832e04dd9ee490a5421">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a246e09362507f1bc278a1b58f13fd209">selectIntAddr11MM</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab01160df04c733dcd7e9e8e3170611b6">selectIntAddr12MM</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bdb993d158bf2bc6471e73dac5f12b4">selectIntAddr16MM</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad42b70163c1f07c1ba98d7c35e370314">selectIntAddrLSL2MM</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1607d3db08b250f5a0a81940dbc685f">selectIntAddrSImm10</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match addr+simm10 and addr. <a href="#ad1607d3db08b250f5a0a81940dbc685f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af088ce2704da954d1b863236eddef180">selectIntAddrSImm10Lsl1</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b52df603933d8199a2c4680a1c2a88d">selectIntAddrSImm10Lsl2</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f6ec3a30ed271376c3203fe93ff3bac">selectIntAddrSImm10Lsl3</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45adce0213a9dc2993751db2dbb08740">selectAddr16</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afffe0c02a3bca97761157a3b2974c5ce">selectAddr16SP</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a30faa1d3556298ee80328e87061b3">selectVSplat</a> (SDNode *N, APInt &amp;Imm, unsigned MinSizeInBits) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select constant vector splats. <a href="#ad3a30faa1d3556298ee80328e87061b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a191efb65a549ffe2ff9f848b744d6503">selectVSplatCommon</a> (SDValue N, SDValue &amp;Imm, bool Signed, unsigned ImmBitSize) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Bits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a066e3c2504d743f87fd825c60bd46b1a">selectVSplatUimm</a> (SDValue N, SDValue &amp;Imm) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select constant vector splats whose value fits in a uimm&lt;Bits&gt;. <a href="#a066e3c2504d743f87fd825c60bd46b1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Bits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0099ba7f1e3ec6cbbb76939b4b537a3e">selectVSplatSimm</a> (SDValue N, SDValue &amp;Imm) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select constant vector splats whose value fits in a simm&lt;Bits&gt;. <a href="#a0099ba7f1e3ec6cbbb76939b4b537a3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2ad9f8818526d01a9fcb8c570fe10fc">selectVSplatUimmPow2</a> (SDValue N, SDValue &amp;Imm) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select constant vector splats whose value is a power of 2. <a href="#af2ad9f8818526d01a9fcb8c570fe10fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af31bbe39e195ade38084175f6a48da51">selectVSplatUimmInvPow2</a> (SDValue N, SDValue &amp;Imm) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select constant vector splats whose value is the inverse of a power of 2. <a href="#af31bbe39e195ade38084175f6a48da51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bb02f8a0058f2ee9ef9821e89a2381a">selectVSplatMaskL</a> (SDValue N, SDValue &amp;Imm) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select constant vector splats whose value is a run of set bits ending at the most significant bit. <a href="#a7bb02f8a0058f2ee9ef9821e89a2381a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf49b3db0bc76b496251125fe1a490d7">selectVSplatMaskR</a> (SDValue N, SDValue &amp;Imm) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select constant vector splats whose value is a run of set bits starting at bit zero. <a href="#adf49b3db0bc76b496251125fe1a490d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7285fcd88a0086b98851b99384bffe6">selectVSplatImmEq1</a> (SDValue N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select constant vector splats whose value is 1. <a href="#ad7285fcd88a0086b98851b99384bffe6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e76b7205c42d71d48432a1c0d62fd90">selectVecAddAsVecSubIfProfitable</a> (SDNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert vector addition with vector subtraction if that allows to encode constant as an immediate and thus avoid extra 'ldi' instruction. <a href="#a2e76b7205c42d71d48432a1c0d62fd90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa8eb8065ff06d86b665dcee6f355d6d">Select</a> (SDNode *N) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select instructions not customized! <a href="#afa8eb8065ff06d86b665dcee6f355d6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fbd6f183292f11f84a9a17829d8b6b1">trySelect</a> (SDNode *Node)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a215bafbdd87070b8bebd4308ccaa29f8">getImm</a> (const SDNode *Node, uint64_t Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c00086d4790163bfe01b65a43e37e8e">getSignedImm</a> (const SDNode *Node, int64_t Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca0595ff100ffc1963fc15a5e9ef8971">processFunctionAfterISel</a> (MachineFunction &amp;MF)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15710e4ab0233aa08e1d6eb9d02a770a">SelectInlineAsmMemoryOperand</a> (const SDValue &amp;Op, InlineAsm::ConstraintCode ConstraintID, std::vector&lt; SDValue &gt; &amp;OutOps) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectInlineAsmMemoryOperand - Select the specified address as a target addressing mode, according to the specified constraint. <a href="#a15710e4ab0233aa08e1d6eb9d02a770a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f93cb35828352d4711f05ac766f9c39">isUnneededShiftMask</a> (SDNode *N, unsigned ShAmtBits) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget">MipsSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a482c44b03f471717a4134634ad2df9dc">Subtarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget">MipsSubtarget</a> around so that we can make the right decision when generating code for different targets. <a href="#a482c44b03f471717a4134634ad2df9dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MipsDAGToDAGISel() {#a3931d9b23cbb2ff915d15fc6b0b03370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MipsDAGToDAGISel::MipsDAGToDAGISel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mips16dagtodagisel/#ada12cb0a2af516c66665c8d044a0712f">llvm::Mips16DAGToDAGISel::Mips16DAGToDAGISel</a> and <a href="/web-llvm/docs/api/classes/llvm/mipssedagtodagisel/#abca770f376b08f30a6534fae08029c7c">llvm::MipsSEDAGToDAGISel::MipsSEDAGToDAGISel</a>.</p>

</div>
</div>

### MipsDAGToDAGISel() {#afee3aae4be37ccc4663f59177052423d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MipsDAGToDAGISel::MipsDAGToDAGISel (<a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine">MipsTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aeac54a65abd3a93279e58b0f474028fc">llvm::SelectionDAGISel::SelectionDAGISel</a>, <a href="#a482c44b03f471717a4134634ad2df9dc">Subtarget</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a0ead78650333eefc4d5591ca3db9ed4b">llvm::SelectionDAGISel::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runOnMachineFunction() {#a31a2d92bd3c713509518df298adad4c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a> and <a href="#a482c44b03f471717a4134634ad2df9dc">Subtarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getGlobalBaseReg() {#a7458beece4ee2d29e63e8e34bb268b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * MipsDAGToDAGISel::getGlobalBaseReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getGlobalBaseReg - Output the instructions required to put the GOT address into a register.</p>

<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="#a7458beece4ee2d29e63e8e34bb268b6c">getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af5bffbb8254140e8679a9b7c0766f9e2">llvm::SelectionDAGISel::getTargetLowering</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>.</p>


<p>Referenced by <a href="#a7458beece4ee2d29e63e8e34bb268b6c">getGlobalBaseReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getImm() {#a215bafbdd87070b8bebd4308ccaa29f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::MipsDAGToDAGISel::getImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, uint64_t Imm)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>.</p>

</div>
</div>

### getSignedImm() {#a5c00086d4790163bfe01b65a43e37e8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::MipsDAGToDAGISel::getSignedImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, int64_t Imm)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>.</p>

</div>
</div>

### isUnneededShiftMask() {#a6f93cb35828352d4711f05ac766f9c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::isUnneededShiftMask (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned ShAmtBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### processFunctionAfterISel() {#aca0595ff100ffc1963fc15a5e9ef8971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MipsDAGToDAGISel::processFunctionAfterISel (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>.</p>

</div>
</div>

### Select() {#afa8eb8065ff06d86b665dcee6f355d6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsDAGToDAGISel::Select (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
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

<p>Select instructions not customized!</p>


<p>Used for expanded, promoted and normal instructions</p>


<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectAddr16() {#a45adce0213a9dc2993751db2dbb08740}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectAddr16 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectAddr16SP() {#afffe0c02a3bca97761157a3b2974c5ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectAddr16SP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectAddrDefault() {#a7d8acd67c2dac470a96d2a8207baa58d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectAddrDefault (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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

<p>Fall back on this function if all else fails.</p>

<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectAddrRegImm() {#af9da26514e523213f2571930e19fe430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectAddrRegImm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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

<p>(reg + imm).</p>


<p>ComplexPattern used on <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo">MipsInstrInfo</a> Used on <a href="/web-llvm/docs/api/namespaces/llvm/mips">Mips</a> Load/Store instructions.</p>


<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectInlineAsmMemoryOperand() {#a15710e4ab0233aa08e1d6eb9d02a770a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::SelectInlineAsmMemoryOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Op, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a> ConstraintID, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutOps)</td>
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

<p>SelectInlineAsmMemoryOperand - Select the specified address as a target addressing mode, according to the specified constraint.</p>


<p>If this does not match or is not implemented, return true. The resultant operands (which will appear in the machine instruction) should be added to the OutOps vector.</p>


<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectIntAddr() {#a13b5344bf4408832e04dd9ee490a5421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectIntAddr (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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

<p>Match integer address pattern.</p>

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectIntAddr11MM() {#a246e09362507f1bc278a1b58f13fd209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectIntAddr11MM (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectIntAddr12MM() {#ab01160df04c733dcd7e9e8e3170611b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectIntAddr12MM (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectIntAddr16MM() {#a6bdb993d158bf2bc6471e73dac5f12b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectIntAddr16MM (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectIntAddrLSL2MM() {#ad42b70163c1f07c1ba98d7c35e370314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectIntAddrLSL2MM (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectIntAddrSImm10() {#ad1607d3db08b250f5a0a81940dbc685f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectIntAddrSImm10 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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

<p>Match addr+simm10 and addr.</p>

<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectIntAddrSImm10Lsl1() {#af088ce2704da954d1b863236eddef180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectIntAddrSImm10Lsl1 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectIntAddrSImm10Lsl2() {#a3b52df603933d8199a2c4680a1c2a88d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectIntAddrSImm10Lsl2 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectIntAddrSImm10Lsl3() {#a0f6ec3a30ed271376c3203fe93ff3bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectIntAddrSImm10Lsl3 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectVecAddAsVecSubIfProfitable() {#a2e76b7205c42d71d48432a1c0d62fd90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectVecAddAsVecSubIfProfitable (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert vector addition with vector subtraction if that allows to encode constant as an immediate and thus avoid extra 'ldi' instruction.</p>


<p>add X, &lt;-1, -1...&gt; --&gt; sub X, &lt;1, 1...&gt;</p>


<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectVSplat() {#ad3a30faa1d3556298ee80328e87061b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectVSplat (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm, unsigned MinSizeInBits)</td>
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

<p>Select constant vector splats.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectVSplatCommon() {#a191efb65a549ffe2ff9f848b744d6503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectVSplatCommon (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm, bool Signed, unsigned ImmBitSize)</td>
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



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectVSplatImmEq1() {#ad7285fcd88a0086b98851b99384bffe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectVSplatImmEq1 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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

<p>Select constant vector splats whose value is 1.</p>

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectVSplatMaskL() {#a7bb02f8a0058f2ee9ef9821e89a2381a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectVSplatMaskL (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm)</td>
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

<p>Select constant vector splats whose value is a run of set bits ending at the most significant bit.</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectVSplatMaskR() {#adf49b3db0bc76b496251125fe1a490d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectVSplatMaskR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm)</td>
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

<p>Select constant vector splats whose value is a run of set bits starting at bit zero.</p>

<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectVSplatSimm() {#a0099ba7f1e3ec6cbbb76939b4b537a3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsDAGToDAGISel::selectVSplatSimm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm)</td>
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

<p>Select constant vector splats whose value fits in a simm&lt;Bits&gt;.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>.</p>

</div>
</div>

### selectVSplatUimm() {#a066e3c2504d743f87fd825c60bd46b1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsDAGToDAGISel::selectVSplatUimm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm)</td>
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

<p>Select constant vector splats whose value fits in a uimm&lt;Bits&gt;.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>.</p>

</div>
</div>

### selectVSplatUimmInvPow2() {#af31bbe39e195ade38084175f6a48da51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectVSplatUimmInvPow2 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm)</td>
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

<p>Select constant vector splats whose value is the inverse of a power of 2.</p>

<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectVSplatUimmPow2() {#af2ad9f8818526d01a9fcb8c570fe10fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDAGToDAGISel::selectVSplatUimmPow2 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm)</td>
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

<p>Select constant vector splats whose value is a power of 2.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### trySelect() {#a9fbd6f183292f11f84a9a17829d8b6b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MipsDAGToDAGISel::trySelect (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Subtarget {#a482c44b03f471717a4134634ad2df9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsSubtarget* llvm::MipsDAGToDAGISel::Subtarget</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget">MipsSubtarget</a> around so that we can make the right decision when generating code for different targets.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a>.</p>


<p>Referenced by <a href="#afee3aae4be37ccc4663f59177052423d">MipsDAGToDAGISel</a> and <a href="#a31a2d92bd3c713509518df298adad4c7">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-cpp">MipsISelDAGToDAG.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsiseldagtodag-h">MipsISelDAGToDAG.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
