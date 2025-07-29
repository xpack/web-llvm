---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/riscvdagtodagisel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RISCVDAGToDAGISel` Class



## Declaration

<div class="doxyDeclaration">
class llvm::RISCVDAGToDAGISel { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">Target/RISCV/RISCVISelDAGToDAG.h</a>"
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a2f31a49799bb6be312837805a95127">RISCVDAGToDAGISel</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a368f6642527e92c99ed4fc152b076bc4">RISCVDAGToDAGISel</a> (RISCVTargetMachine &amp;TargetMachine, CodeGenOptLevel OptLevel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc72c6519e1e43f155319c3130fc688">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa2c4df9fd69696ef41afd841661bb7">PreprocessISelDAG</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PreprocessISelDAG - This hook allows targets to hack on the graph before instruction selection starts. <a href="#a6aa2c4df9fd69696ef41afd841661bb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a838f903d98be09e801b17c933b89fe27">PostprocessISelDAG</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a838f903d98be09e801b17c933b89fe27">PostprocessISelDAG()</a> - This hook allows the target to hack on the graph right after selection. <a href="#a838f903d98be09e801b17c933b89fe27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a> (SDNode *Node) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main hook for targets to transform nodes into machine nodes. <a href="#a7d60a41c0d5e450f770042d3427928d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c6e604c1448af21dd7165a086728b31">SelectInlineAsmMemoryOperand</a> (const SDValue &amp;Op, InlineAsm::ConstraintCode ConstraintID, std::vector&lt; SDValue &gt; &amp;OutOps) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectInlineAsmMemoryOperand - Select the specified address as a target addressing mode, according to the specified constraint. <a href="#a5c6e604c1448af21dd7165a086728b31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6717d53904bf236f07c08d32f3caeab3">SelectAddrFrameIndex</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030eaafa553ffa2a996481cff1e7aaa8">SelectAddrRegImm</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset, bool IsRV32Zdinx=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f4040f9efb6f772dd5b95c7384ceac3">SelectAddrRegImmRV32Zdinx</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a185b481cf26bfc5e6ed78a7d07519301">SelectAddrRegImmLsb00000</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to SelectAddrRegImm, except that the least significant 5 bits of Offset should be all zeros. <a href="#a185b481cf26bfc5e6ed78a7d07519301">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae779832c7d1fe14084a195e6826071">SelectAddrRegRegScale</a> (SDValue Addr, unsigned MaxShiftAmount, SDValue &amp;Base, SDValue &amp;Index, SDValue &amp;Scale)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned MaxShift&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a975241c41be7cb620381b658bc23a6ff">SelectAddrRegRegScale</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Index, SDValue &amp;Scale)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned MaxShift, unsigned Bits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad989a7218cfa7a00228458266da30775">SelectAddrRegZextRegScale</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Index, SDValue &amp;Scale)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2af215cb308965561cd20b6d6dc7798b">SelectAddrRegReg</a> (SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92a75fbae3b487187668a2099271d1a0">tryShrinkShlLogicImm</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3196a845dd9ce40f3b0766ee99dea7e">trySignedBitfieldExtract</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa371a03066103bb85f89636e86686d7">tryIndexedLoad</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af619c526b5e90968d76fbd4fe4c861cb">selectShiftMask</a> (SDValue N, unsigned ShiftWidth, SDValue &amp;ShAmt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e9216876c10fd17e43217bab282a4d8">selectShiftMaskXLen</a> (SDValue N, SDValue &amp;ShAmt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a218b6638506d322e84bf0e7a4fabff">selectShiftMask32</a> (SDValue N, SDValue &amp;ShAmt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a007b16805afc4c07d06f494804c588a0">selectSETCC</a> (SDValue N, ISD::CondCode ExpectedCCVal, SDValue &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RISC-V doesn't have general instructions for integer setne/seteq, but we can check for equality with 0. <a href="#a007b16805afc4c07d06f494804c588a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9399b0bae995e0f6e829909d253b252f">selectSETNE</a> (SDValue N, SDValue &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a335dea545b19d321b4ef1e77fc1f77e7">selectSETEQ</a> (SDValue N, SDValue &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a015f92412cbdc26fe3f1f398afb3575b">selectSExtBits</a> (SDValue N, unsigned Bits, SDValue &amp;Val)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a79ac751b1d22b0f304884dfabe120e05">selectSExtBits</a> (SDValue N, SDValue &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b5cba8cfdcec8f2d1dafb06fb63ab5">selectZExtBits</a> (SDValue N, unsigned Bits, SDValue &amp;Val)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af01870e7e19b1220afa10a19f526c533">selectZExtBits</a> (SDValue N, SDValue &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a2bb077674a4de01b665b694b7f77f">selectSHXADDOp</a> (SDValue N, unsigned ShAmt, SDValue &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look for various patterns that can be done with a SHL that can be folded into a SHXADD. <a href="#af9a2bb077674a4de01b665b694b7f77f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ShAmt&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae9ab615e80a0eef48a4c044b66d9c04f">selectSHXADDOp</a> (SDValue N, SDValue &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a0bdd0c07878ba4d61fa3b1b0453b1">selectSHXADD_UWOp</a> (SDValue N, unsigned ShAmt, SDValue &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look for various patterns that can be done with a SHL that can be folded into a SHXADD_UW. <a href="#a06a0bdd0c07878ba4d61fa3b1b0453b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ShAmt&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a03a1b1ee1fea2b1c4911d4e5e6bb7a2a">selectSHXADD_UWOp</a> (SDValue N, SDValue &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ed9eee21fb8cd7cc428eeafae6b28bc">selectInvLogicImm</a> (SDValue N, SDValue &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c47c47ebffcc56ccf426575cc7688f1">hasAllNBitUsers</a> (SDNode *Node, unsigned Bits, const unsigned Depth=0) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a874647ac6d0cd4cc31e8f3f335f014a5">hasAllBUsers</a> (SDNode *Node) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bd868d175a4cfe28c31e8bd58380090">hasAllHUsers</a> (SDNode *Node) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68fe5706b6c5ab0df6fc48ecf12dec30">hasAllWUsers</a> (SDNode *Node) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48c6bde78599716905a0196844dc5c9c">selectSimm5Shl2</a> (SDValue N, SDValue &amp;Simm5, SDValue &amp;Shl2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dd913520cec32052ff63c8735efad5c">selectVLOp</a> (SDValue N, SDValue &amp;VL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81db6a638b456bb26ffa634a27e52798">selectVSplat</a> (SDValue N, SDValue &amp;SplatVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60c150f4b46cf5dc8dd1af9653ddde43">selectVSplatSimm5</a> (SDValue N, SDValue &amp;SplatVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff942d6f8939b769939917efd741bde5">selectVSplatUimm</a> (SDValue N, unsigned Bits, SDValue &amp;SplatVal)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0fe3090ddbfdb18ba09417cd06334349">selectVSplatUimmBits</a> (SDValue N, SDValue &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1135c7a8ff766bc0ec72c55e1049d87">selectVSplatSimm5Plus1</a> (SDValue N, SDValue &amp;SplatVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfe913dce113bf8f5d20f5e1fe1966b2">selectVSplatSimm5Plus1NonZero</a> (SDValue N, SDValue &amp;SplatVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59b8897a5959dc1ad5ff6311eae5e9b2">selectLow8BitsVSplat</a> (SDValue N, SDValue &amp;SplatVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8414362458bfc0acef16b0440665faa1">selectScalarFPAsInt</a> (SDValue N, SDValue &amp;Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a656b650a40d5acec00fc5a95ed5c71af">selectRVVSimm5</a> (SDValue N, unsigned Width, SDValue &amp;Imm)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Width&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab56dfbd0e6d276051f48a8aaca6162b5">selectRVVSimm5</a> (SDValue N, SDValue &amp;Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a824579538728c6e67cf9a6191e5894e3">addVectorLoadStoreOperands</a> (SDNode *Node, unsigned SEWImm, const SDLoc &amp;DL, unsigned CurOp, bool IsMasked, bool IsStridedOrIndexed, SmallVectorImpl&lt; SDValue &gt; &amp;Operands, bool IsLoad=false, MVT *IndexVT=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fa52705ef408e923efaab38cd62597a">selectVLSEG</a> (SDNode *Node, unsigned NF, bool IsMasked, bool IsStrided)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4165c3b90d08f85ae15b915d4d4bdf65">selectVLSEGFF</a> (SDNode *Node, unsigned NF, bool IsMasked)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af390be4480c0588fa6c3fc6cd05e4166">selectVLXSEG</a> (SDNode *Node, unsigned NF, bool IsMasked, bool IsOrdered)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf23f63b97b9f5f99c3dd3c3a986e418">selectVSSEG</a> (SDNode *Node, unsigned NF, bool IsMasked, bool IsStrided)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35a4f3715a02bc5b5d9ced3b5324f439">selectVSXSEG</a> (SDNode *Node, unsigned NF, bool IsMasked, bool IsOrdered)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a91b8b1f7d203b918218d0db9cec5d">selectVSETVLI</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a491dd364e0fd3440074a55eeec66b267">selectSF_VC_X_SE</a> (SDNode *Node)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acafa4f39ff5b552aebc591881c7d8228">doPeepholeSExtW</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53c54937d0533922a882ec6e34c32fd1">doPeepholeMaskedRVV</a> (MachineSDNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc75be5ae6066c2bd794ca92cff5da7b">doPeepholeMergeVVMFold</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47bfccc8301db8b0f7a86953b0295c61">doPeepholeNoRegPassThru</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If our passthru is an implicit_def, use noreg instead. <a href="#a47bfccc8301db8b0f7a86953b0295c61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcbf4fdfaeac8713f4f267124c22c45c">performCombineVMergeAndVOps</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57c98913ddf92cf8fb8329df22d1a904">Subtarget</a> = nullptr</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976">RISCVCC::CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe653782963dc86ef7f61b60b21dab8b">getRISCVCCForIntCC</a> (ISD::CondCode CC)</td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVDAGToDAGISel() {#a7a2f31a49799bb6be312837805a95127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RISCVDAGToDAGISel::RISCVDAGToDAGISel ()</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>

</div>
</div>

### RISCVDAGToDAGISel() {#a368f6642527e92c99ed4fc152b076bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RISCVDAGToDAGISel::RISCVDAGToDAGISel (<a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine">RISCVTargetMachine</a> &amp; TargetMachine, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OptLevel)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a5386ceeb71599848944185c0035e0e94">llvm::SelectionDAGISel::OptLevel</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aeac54a65abd3a93279e58b0f474028fc">llvm::SelectionDAGISel::SelectionDAGISel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addVectorLoadStoreOperands() {#a824579538728c6e67cf9a6191e5894e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVDAGToDAGISel::addVectorLoadStoreOperands (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, unsigned SEWImm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, unsigned CurOp, bool IsMasked, bool IsStridedOrIndexed, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Operands, bool IsLoad=false, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> * IndexVT=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a0223dd30dc4a3c2eabb5bd5ce315e065a1d96428e9ed63333f145e92079ab267d">llvm::RISCVII::MASK_AGNOSTIC</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#a9dd913520cec32052ff63c8735efad5c">selectVLOp</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>, <a href="#a8fa52705ef408e923efaab38cd62597a">selectVLSEG</a>, <a href="#a4165c3b90d08f85ae15b915d4d4bdf65">selectVLSEGFF</a>, <a href="#af390be4480c0588fa6c3fc6cd05e4166">selectVLXSEG</a>, <a href="#abf23f63b97b9f5f99c3dd3c3a986e418">selectVSSEG</a> and <a href="#a35a4f3715a02bc5b5d9ced3b5324f439">selectVSXSEG</a>.</p>

</div>
</div>

### hasAllBUsers() {#a874647ac6d0cd4cc31e8f3f335f014a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::hasAllBUsers (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>Reference <a href="#a0c47c47ebffcc56ccf426575cc7688f1">hasAllNBitUsers</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

### hasAllHUsers() {#a5bd868d175a4cfe28c31e8bd58380090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::hasAllHUsers (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>Reference <a href="#a0c47c47ebffcc56ccf426575cc7688f1">hasAllNBitUsers</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

### hasAllNBitUsers() {#a0c47c47ebffcc56ccf426575cc7688f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::hasAllNBitUsers (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, unsigned Bits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37c1fdede126353d80c3753dfe06f3c7">llvm::bit_width</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/use/#a541187eb976df2189b40b3f62ed2cee0">llvm::Use::getOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/use/#a53a48d67682705c5f7f06ffc850fd622">llvm::Use::getUser</a>, <a href="#a0c47c47ebffcc56ccf426575cc7688f1">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4d5e16cbde22f5e6f007940d57a428fd">llvm::SelectionDAG::MaxRecursionDepth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a530363b25d555de667bf4f23bc6349a6">llvm::SelectionDAGISel::TII</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#aadd8c5bb4ccd3134cdde19afc01eb291">vectorPseudoHasAllNBitUsers</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>.</p>


<p>Referenced by <a href="#a874647ac6d0cd4cc31e8f3f335f014a5">hasAllBUsers</a>, <a href="#a5bd868d175a4cfe28c31e8bd58380090">hasAllHUsers</a>, <a href="#a0c47c47ebffcc56ccf426575cc7688f1">hasAllNBitUsers</a> and <a href="#a68fe5706b6c5ab0df6fc48ecf12dec30">hasAllWUsers</a>.</p>

</div>
</div>

### hasAllWUsers() {#a68fe5706b6c5ab0df6fc48ecf12dec30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::hasAllWUsers (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>Reference <a href="#a0c47c47ebffcc56ccf426575cc7688f1">hasAllNBitUsers</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

### PostprocessISelDAG() {#a838f903d98be09e801b17c933b89fe27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVDAGToDAGISel::PostprocessISelDAG ()</td>
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

<p><a href="#a838f903d98be09e801b17c933b89fe27">PostprocessISelDAG()</a> - This hook allows the target to hack on the graph right after selection.</p>

<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### PreprocessISelDAG() {#a6aa2c4df9fd69696ef41afd841661bb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVDAGToDAGISel::PreprocessISelDAG ()</td>
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

<p>PreprocessISelDAG - This hook allows targets to hack on the graph before instruction selection starts.</p>

<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a9459055a98e20980521289e8d20fcc7e">llvm::MachinePointerInfo::getWithOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a437cf7bc875369cbe0ea62f949626f0b">llvm::MVT::isInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a447ebcc5de7a1d9bc163862bf2c78e41">llvm::MVT::isScalableVector</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">llvm::ISD::SPLAT_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882aa282e2548f435b7fdd280b478a3623aa">llvm::RISCVISD::SPLAT_VECTOR_SPLIT_I64_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a3d046b0b663cacd2116c6d35498ab5ab">llvm::RISCVISD::VFMV_V_F_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a127afe58529ef366a343a51786dcc3d4">llvm::RISCVISD::VMV_V_X_VL</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a6cc72c6519e1e43f155319c3130fc688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>.</p>

</div>
</div>

### Select() {#a7d60a41c0d5e450f770042d3427928d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVDAGToDAGISel::Select (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Main hook for targets to transform nodes into machine nodes.</p>

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 841 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a824579538728c6e67cf9a6191e5894e3">addVectorLoadStoreOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37c1fdede126353d80c3753dfe06f3c7">llvm::bit_width</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a7ad8eae84b0d5313d06e6662a823dd1e">llvm::RISCVISD::BuildGPRPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a706088c700a61880a610f9ba149a6d03">llvm::RISCVISD::BuildPairF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a59f6c404da0aa484a98ff96ec0304125">CASE_VMNAND_VMSET_OPCODES</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#abbb63ad110da07deeee196ee737999d1">CASE_VMSLT_OPCODES</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a8ba64312e06ecc1161e8da80e17fc4f5">CASE_VMXOR_VMANDN_VMOR_OPCODES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aac2f0a84dd2aa5ee4c3f1385e9565f5e">llvm::ISD::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1be4c8da7c68a4c683de1a98b5cc5b9d">llvm::ISD::ConstantFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a239abca11deebf2731206dd41cf43c0e">llvm::countr_one</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a01ee44fd979fc25e2afe3d23a2079494">llvm::RISCVTargetLowering::decomposeSubvectorInsertExtractToSubRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/node/#a3a50a546aa28bc9ebd20afd6aff7588d">Node::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ac969b6c833cfa44c1b4fcd5790268340">llvm::SDValue::getConstantOperandVal</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac27709ca33b27034fb25d6fb83cb5fb1">llvm::RISCVTargetLowering::getLMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a78d9c499deb0a2aadbf8e7ed5e717a8e">llvm::RISCVTargetLowering::getRegClassIDForVecVT</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a5fd620f2446d1a4cb0d55a12d182bb34">llvm::TypeSize::getScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a9d21b6fd19243e696e086f5f4c5717f5">getSegInstNF</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#acbcc973a299b6f8733774668210b5227">llvm::SDValue::getSimpleValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a1572b31fadbd0d758314b8d35a050410">llvm::EVT::getStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ab8e1af73424a59a00656c9ffd505c03f">llvm::MVT::getStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aa1abe2e0d36a43d780ce54ea3b197217">llvm::MVT::getVectorElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="#a874647ac6d0cd4cc31e8f3f335f014a5">hasAllBUsers</a>, <a href="#a5bd868d175a4cfe28c31e8bd58380090">hasAllHUsers</a>, <a href="#a68fe5706b6c5ab0df6fc48ecf12dec30">hasAllWUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a342c0d4e8e59b30daefe9a05bc2098bd">llvm::SDValue::hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a98049e07856ff1288295bc58e232518b">llvm::MVT::isFixedLengthVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a98c172c9b66de1264ee2123e4f1a3df2">llvm::SelectionDAGISel::IsLegalToFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82a9558b6319303ae62f59dab9669685">llvm::isMask_64</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ad57f69ac4fa1d889dc657d52e8a51ef1">llvm::APFloat::isNegZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac926ae0b6871c2207db3e787f6dbcb80">llvm::isOneConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ac37cd93f2c41a818a278e99de784ba1d">llvm::APFloat::isPosZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a877a33bf451c611191b8f8dcbbaed4ca">llvm::SelectionDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a447ebcc5de7a1d9bc163862bf2c78e41">llvm::MVT::isScalableVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a582e08755c7a8d1b0bf6c5dcb765aaa8">llvm::isShiftedMask_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9aaed17970b55e9e1bfa906822ea7b71">llvm::APFloat::isZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1caf5395daef0a34ae8d78919a587eee448">llvm::RISCVII::LMUL_F2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1caea5ed9248acd465f986c64e15db529e5">llvm::RISCVII::LMUL_F4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1ca61d90764106d2ac6346f4bc1ae1bd3fd">llvm::RISCVII::LMUL_F8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a58328e0582aabaf012bf9bc6f36c9e04">llvm::M1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a0223dd30dc4a3c2eabb5bd5ce315e065a1d96428e9ed63333f145e92079ab267d">llvm::RISCVII::MASK_AGNOSTIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a32d8533843aab2ce0254e2e2389c9c">llvm::maskTrailingZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda8d09c51969b0954512ed65ee26551081">llvm::MachineMemOperand::MONonTemporal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b03276ac1b0cdef6875ab7640197511">llvm::MONontemporalBit0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a10f12756e22ab1f56769768496914491">llvm::MONontemporalBit1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31a866c29237765ff291c9503abbdca60e1">llvm::ISD::POST_INC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a691a4c9004e9bd04d1c0bebc5df57443">llvm::ISD::PREFETCH</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a84e771c0f56c984d8ee4a85c0cb46ed3">llvm::SelectionDAGISel::ReplaceUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvfprndmode/#a9214a4f7f7322f485189dd3726776b76af4acf467b6b1c729666f8735cb3f61fb">llvm::RISCVFPRndMode::RNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#ad53ed145f88b1e1c966ff68df9029e7f">llvm::RISCV::RVVBitsPerBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a2b20fa727cb3be2d7338de943bc81490">selectImm</a>, <a href="#a491dd364e0fd3440074a55eeec66b267">selectSF_VC_X_SE</a>, <a href="#a9dd913520cec32052ff63c8735efad5c">selectVLOp</a>, <a href="#a8fa52705ef408e923efaab38cd62597a">selectVLSEG</a>, <a href="#a4165c3b90d08f85ae15b915d4d4bdf65">selectVLSEGFF</a>, <a href="#af390be4480c0588fa6c3fc6cd05e4166">selectVLXSEG</a>, <a href="#a97a91b8b1f7d203b918218d0db9cec5d">selectVSETVLI</a>, <a href="#abf23f63b97b9f5f99c3dd3c3a986e418">selectVSSEG</a>, <a href="#a35a4f3715a02bc5b5d9ced3b5324f439">selectVSXSEG</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aadac6e7fd2d1087b6489906659bb8afb">llvm::MachineMemOperand::setFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a02503efde5e7e2b5b037d10199834356">llvm::RISCVISD::SplitF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882aa4911c97824c2f6defbba3953ebbc370">llvm::RISCVISD::SplitGPRPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a0223dd30dc4a3c2eabb5bd5ce315e065abdc0a80d5e4b58676f861ffaa296bd1b">llvm::RISCVII::TAIL_AGNOSTIC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a1ed864be04c93653277b0f5112a4f305">llvm::SelectionDAGISel::TLI</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a0ead78650333eefc4d5591ca3db9ed4b">llvm::SelectionDAGISel::TM</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="#afa371a03066103bb85f89636e86686d7">tryIndexedLoad</a>, <a href="#a92a75fbae3b487187668a2099271d1a0">tryShrinkShlLogicImm</a>, <a href="#aa3196a845dd9ce40f3b0766ee99dea7e">trySignedBitfieldExtract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882af5cd9f36ca49bedc10a803bc45e3c42b">llvm::RISCVISD::TUPLE_EXTRACT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ae47a7836f9d335899c477da04c5e56f4">llvm::RISCVISD::TUPLE_INSERT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a41320aaa5a0fc5f6704fba144635bcab">llvm::RISCVISD::VFMV_S_F_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a3d046b0b663cacd2116c6d35498ab5ab">llvm::RISCVISD::VFMV_V_F_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a55a5f5a5eb10f4ca81928a4cee11ab52">llvm::RISCVISD::VMV_S_X_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a127afe58529ef366a343a51786dcc3d4">llvm::RISCVISD::VMV_V_X_VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>.</p>

</div>
</div>

### SelectAddrFrameIndex() {#a6717d53904bf236f07c08d32f3caeab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::SelectAddrFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 2523 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a030eaafa553ffa2a996481cff1e7aaa8">SelectAddrRegImm</a> and <a href="#a185b481cf26bfc5e6ed78a7d07519301">SelectAddrRegImmLsb00000</a>.</p>

</div>
</div>

### SelectAddrRegImm() {#a030eaafa553ffa2a996481cff1e7aaa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::SelectAddrRegImm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, bool IsRV32Zdinx=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 2669 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882af67faecb539beaa37dfcfff1252c9c60">llvm::RISCVISD::ADD_LO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd6aa057934751aaac54e5c18bcc18eb">llvm::commonAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#acbcc973a299b6f8733774668210b5227">llvm::SDValue::getSimpleValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a641563566f08db6108848bf61de2f323">isWorthFoldingAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a6717d53904bf236f07c08d32f3caeab3">SelectAddrFrameIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a2bdacd126c6e2d17f0f5a195043c9aa3">selectConstantAddr</a>.</p>


<p>Referenced by <a href="#a5f4040f9efb6f772dd5b95c7384ceac3">SelectAddrRegImmRV32Zdinx</a> and <a href="#a5c6e604c1448af21dd7165a086728b31">SelectInlineAsmMemoryOperand</a>.</p>

</div>
</div>

### SelectAddrRegImmLsb00000() {#a185b481cf26bfc5e6ed78a7d07519301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::SelectAddrRegImmLsb00000 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to SelectAddrRegImm, except that the least significant 5 bits of Offset should be all zeros.</p>

<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 2789 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#acbcc973a299b6f8733774668210b5227">llvm::SDValue::getSimpleValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a6717d53904bf236f07c08d32f3caeab3">SelectAddrFrameIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a2bdacd126c6e2d17f0f5a195043c9aa3">selectConstantAddr</a>.</p>

</div>
</div>

### SelectAddrRegImmRV32Zdinx() {#a5f4040f9efb6f772dd5b95c7384ceac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::SelectAddrRegImmRV32Zdinx (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a030eaafa553ffa2a996481cff1e7aaa8">SelectAddrRegImm</a>.</p>

</div>
</div>

### SelectAddrRegReg() {#a2af215cb308965561cd20b6d6dc7798b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::SelectAddrRegReg (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 2855 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### SelectAddrRegRegScale() {#afae779832c7d1fe14084a195e6826071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::SelectAddrRegRegScale (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, unsigned MaxShiftAmount, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Scale)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 2615 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#acbcc973a299b6f8733774668210b5227">llvm::SDValue::getSimpleValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>.</p>


<p>Referenced by <a href="#a975241c41be7cb620381b658bc23a6ff">SelectAddrRegRegScale</a> and <a href="#ad989a7218cfa7a00228458266da30775">SelectAddrRegZextRegScale</a>.</p>

</div>
</div>

### SelectAddrRegRegScale() {#a975241c41be7cb620381b658bc23a6ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned MaxShift&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::SelectAddrRegRegScale (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Scale)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a> and <a href="#afae779832c7d1fe14084a195e6826071">SelectAddrRegRegScale</a>.</p>

</div>
</div>

### SelectAddrRegZextRegScale() {#ad989a7218cfa7a00228458266da30775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned MaxShift, unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::SelectAddrRegZextRegScale (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Scale)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a> and <a href="#afae779832c7d1fe14084a195e6826071">SelectAddrRegRegScale</a>.</p>

</div>
</div>

### SelectInlineAsmMemoryOperand() {#a5c6e604c1448af21dd7165a086728b31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::SelectInlineAsmMemoryOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Op, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a> ConstraintID, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutOps)</td>
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


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 2495 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a7fc56270e7a70fa81a5935b72eacbe29">llvm::InlineAsm::A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#ade110db5cd02d02d8d11534fa679b52b">llvm::InlineAsm::getMemConstraintName</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a6f8f57715090da2632453988d9a1501b">llvm::InlineAsm::m</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0ad95679752134a2d9eb61dbd7b91c4bcc">llvm::InlineAsm::o</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="#a030eaafa553ffa2a996481cff1e7aaa8">SelectAddrRegImm</a>.</p>

</div>
</div>

### selectInvLogicImm() {#a6ed9eee21fb8cd7cc428eeafae6b28bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectInvLogicImm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a392b6c8a7962feed988bf14017205f4b">llvm::RISCVMatInt::getIntMatCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a2b20fa727cb3be2d7338de943bc81490">selectImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a127afe58529ef366a343a51786dcc3d4">llvm::RISCVISD::VMV_V_X_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>.</p>

</div>
</div>

### selectLow8BitsVSplat() {#a59b8897a5959dc1ad5ff6311eae5e9b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectLow8BitsVSplat (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SplatVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a81db6a638b456bb26ffa634a27e52798">selectVSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882aa6e01bc76a36f1f8564b7dc17c32982e">llvm::RISCVISD::TRUNCATE_VECTOR_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2be5d0001da98e7c524aa9d212419f7d">llvm::RISCVISD::VSEXT_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882aab563d8b09e3a65dbc2bd73051b074cc">llvm::RISCVISD::VZEXT_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### selectRVVSimm5() {#a656b650a40d5acec00fc5a95ed5c71af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectRVVSimm5 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, unsigned Width, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3657 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>


<p>Referenced by <a href="#ab56dfbd0e6d276051f48a8aaca6162b5">selectRVVSimm5</a>.</p>

</div>
</div>

### selectRVVSimm5() {#ab56dfbd0e6d276051f48a8aaca6162b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Width&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::selectRVVSimm5 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm)</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a656b650a40d5acec00fc5a95ed5c71af">selectRVVSimm5</a>.</p>

</div>
</div>

### selectScalarFPAsInt() {#a8414362458bfc0acef16b0440665faa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectScalarFPAsInt (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3621 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a8133bf609ca1e40ecb0622ed5e559fcc">llvm::RISCVISD::FMV_H_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882af4707e0cbdd66af52d6f4ea39d7c2cdf">llvm::RISCVISD::FMV_W_X_RV64</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7a6096cff14db41b299758115c6e261c">llvm::SDNode::getSimpleValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode/#a04bc59ba29c90155e6184cdcd37ce175">llvm::ConstantFPSDNode::getValueAPF</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ad57f69ac4fa1d889dc657d52e8a51ef1">llvm::APFloat::isNegZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ac37cd93f2c41a818a278e99de784ba1d">llvm::APFloat::isPosZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a2b20fa727cb3be2d7338de943bc81490">selectImm</a>.</p>

</div>
</div>

### selectSETCC() {#a007b16805afc4c07d06f494804c588a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectSETCC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> ExpectedCCVal, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RISC-V doesn't have general instructions for integer setne/seteq, but we can check for equality with 0.</p>


<p>This function emits instructions that convert the seteq/setne into something that can be compared with 0. <span class="doxyComputerOutput">ExpectedCCVal</span> indicates the condition code to attempt to match (e.g. <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">ISD::SETNE</a>).</p>


<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 2945 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#afda64d97fb7fe554744b7a68c304c224">llvm::ISD::isIntEqualitySetCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f42ed6fd2569fa43f03814a17f9d94a">llvm::Log2_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>.</p>


<p>Referenced by <a href="#a335dea545b19d321b4ef1e77fc1f77e7">selectSETEQ</a> and <a href="#a9399b0bae995e0f6e829909d253b252f">selectSETNE</a>.</p>

</div>
</div>

### selectSETEQ() {#a335dea545b19d321b4ef1e77fc1f77e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::selectSETEQ (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Val)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a007b16805afc4c07d06f494804c588a0">selectSETCC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>.</p>

</div>
</div>

### selectSETNE() {#a9399b0bae995e0f6e829909d253b252f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::selectSETNE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Val)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a007b16805afc4c07d06f494804c588a0">selectSETCC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>.</p>

</div>
</div>

### selectSExtBits() {#a015f92412cbdc26fe3f1f398afb3575b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectSExtBits (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, unsigned Bits, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3012 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ac969b6c833cfa44c1b4fcd5790268340">llvm::SDValue::getConstantOperandVal</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>.</p>


<p>Referenced by <a href="#a79ac751b1d22b0f304884dfabe120e05">selectSExtBits</a>.</p>

</div>
</div>

### selectSExtBits() {#a79ac751b1d22b0f304884dfabe120e05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::selectSExtBits (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Val)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a015f92412cbdc26fe3f1f398afb3575b">selectSExtBits</a>.</p>

</div>
</div>

### selectSF\_VC\_X\_SE() {#a491dd364e0fd3440074a55eeec66b267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVDAGToDAGISel::selectSF_VC_X_SE (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

### selectShiftMask() {#af619c526b5e90968d76fbd4fe4c861cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectShiftMask (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, unsigned ShiftWidth, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; ShAmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 2868 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#abb7cd0abf43d415da943eb8e4fe4f01b">llvm::SDValue::getConstantOperandAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ac969b6c833cfa44c1b4fcd5790268340">llvm::SDValue::getConstantOperandVal</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acfae9bdee6027ffa8ffe244cc22e3a76">llvm::APInt::isSubsetOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>


<p>Referenced by <a href="#a9a218b6638506d322e84bf0e7a4fabff">selectShiftMask32</a> and <a href="#a1e9216876c10fd17e43217bab282a4d8">selectShiftMaskXLen</a>.</p>

</div>
</div>

### selectShiftMask32() {#a9a218b6638506d322e84bf0e7a4fabff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::selectShiftMask32 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; ShAmt)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#af619c526b5e90968d76fbd4fe4c861cb">selectShiftMask</a>.</p>

</div>
</div>

### selectShiftMaskXLen() {#a1e9216876c10fd17e43217bab282a4d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::selectShiftMaskXLen (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; ShAmt)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#af619c526b5e90968d76fbd4fe4c861cb">selectShiftMask</a>.</p>

</div>
</div>

### selectSHXADD\_UWOp() {#a06a0bdd0c07878ba4d61fa3b1b0453b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectSHXADD_UWOp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, unsigned ShAmt, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look for various patterns that can be done with a SHL that can be folded into a SHXADD_UW.</p>


<p><span class="doxyComputerOutput">ShAmt</span> contains 1, 2, or 3 and is set based on which SHXADD_UW we are trying to match.</p>


<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ac969b6c833cfa44c1b4fcd5790268340">llvm::SDValue::getConstantOperandVal</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a342c0d4e8e59b30daefe9a05bc2098bd">llvm::SDValue::hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a582e08755c7a8d1b0bf6c5dcb765aaa8">llvm::isShiftedMask_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a32d8533843aab2ce0254e2e2389c9c">llvm::maskTrailingZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>.</p>


<p>Referenced by <a href="#a03a1b1ee1fea2b1c4911d4e5e6bb7a2a">selectSHXADD_UWOp</a>.</p>

</div>
</div>

### selectSHXADD\_UWOp() {#a03a1b1ee1fea2b1c4911d4e5e6bb7a2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ShAmt&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::selectSHXADD_UWOp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Val)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a06a0bdd0c07878ba4d61fa3b1b0453b1">selectSHXADD_UWOp</a>.</p>

</div>
</div>

### selectSHXADDOp() {#af9a2bb077674a4de01b665b694b7f77f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectSHXADDOp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, unsigned ShAmt, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look for various patterns that can be done with a SHL that can be folded into a SHXADD.</p>


<p><span class="doxyComputerOutput">ShAmt</span> contains 1, 2, or 3 and is set based on which SHXADD we are trying to match.</p>


<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3062 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37c1fdede126353d80c3753dfe06f3c7">llvm::bit_width</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ac969b6c833cfa44c1b4fcd5790268340">llvm::SDValue::getConstantOperandVal</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a342c0d4e8e59b30daefe9a05bc2098bd">llvm::SDValue::hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a582e08755c7a8d1b0bf6c5dcb765aaa8">llvm::isShiftedMask_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a32d8533843aab2ce0254e2e2389c9c">llvm::maskTrailingZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>.</p>


<p>Referenced by <a href="#ae9ab615e80a0eef48a4c044b66d9c04f">selectSHXADDOp</a>.</p>

</div>
</div>

### selectSHXADDOp() {#ae9ab615e80a0eef48a4c044b66d9c04f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ShAmt&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::selectSHXADDOp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Val)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#af9a2bb077674a4de01b665b694b7f77f">selectSHXADDOp</a>.</p>

</div>
</div>

### selectSimm5Shl2() {#a48c6bde78599716905a0196844dc5c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectSimm5Shl2 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Simm5, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Shl2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### selectVLOp() {#a9dd913520cec32052ff63c8735efad5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectVLOp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; VL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#ae746649c43bf0f652d04addefd39a55e">llvm::RISCV::VLMaxSentinel</a>.</p>


<p>Referenced by <a href="#a824579538728c6e67cf9a6191e5894e3">addVectorLoadStoreOperands</a> and <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

### selectVLSEG() {#a8fa52705ef408e923efaab38cd62597a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVDAGToDAGISel::selectVLSEG (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, unsigned NF, bool IsMasked, bool IsStrided)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a824579538728c6e67cf9a6191e5894e3">addVectorLoadStoreOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac27709ca33b27034fb25d6fb83cb5fb1">llvm::RISCVTargetLowering::getLMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a84e771c0f56c984d8ee4a85c0cb46ed3">llvm::SelectionDAGISel::ReplaceUses</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

### selectVLSEGFF() {#a4165c3b90d08f85ae15b915d4d4bdf65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVDAGToDAGISel::selectVLSEGFF (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, unsigned NF, bool IsMasked)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a824579538728c6e67cf9a6191e5894e3">addVectorLoadStoreOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac27709ca33b27034fb25d6fb83cb5fb1">llvm::RISCVTargetLowering::getLMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a84e771c0f56c984d8ee4a85c0cb46ed3">llvm::SelectionDAGISel::ReplaceUses</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

### selectVLXSEG() {#af390be4480c0588fa6c3fc6cd05e4166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVDAGToDAGISel::selectVLXSEG (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, unsigned NF, bool IsMasked, bool IsOrdered)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a824579538728c6e67cf9a6191e5894e3">addVectorLoadStoreOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#a5144889af710ec49f5eeff7be79e671d">llvm::RISCVVType::decodeVLMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac27709ca33b27034fb25d6fb83cb5fb1">llvm::RISCVTargetLowering::getLMUL</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a1eb420ba23c865af3024a336e491b983">llvm::MVT::getVectorMinNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a84e771c0f56c984d8ee4a85c0cb46ed3">llvm::SelectionDAGISel::ReplaceUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#ad53ed145f88b1e1c966ff68df9029e7f">llvm::RISCV::RVVBitsPerBlock</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

### selectVSETVLI() {#a97a91b8b1f7d203b918218d0db9cec5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVDAGToDAGISel::selectVSETVLI (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#a291f15cffaa5063b9056d0160413bc82">llvm::RISCVVType::decodeVSEW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#ad3636219b4d0045029530c6a16c160dc">llvm::RISCVVType::encodeVTYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#a51c33217fc9f7cae7a19701e421dc70f">llvm::RISCVVType::getSEWLMULRatio</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af8b512107b41f4ccaf001e31218135c3">llvm::isAllOnesConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

### selectVSplat() {#a81db6a638b456bb26ffa634a27e52798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectVSplat (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SplatVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#ae0bac4d8677c9b1ee6a8626a4eca85d0">findVSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a5b9bf50c6579a978e5c1104bf8787651">llvm::Splat</a>.</p>


<p>Referenced by <a href="#a59b8897a5959dc1ad5ff6311eae5e9b2">selectLow8BitsVSplat</a>.</p>

</div>
</div>

### selectVSplatSimm5() {#a60c150f4b46cf5dc8dd1af9653ddde43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectVSplatSimm5 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SplatVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3569 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#ae4864665b5082511864fa8b4ad9ea5f9">selectVSplatImmHelper</a>.</p>

</div>
</div>

### selectVSplatSimm5Plus1() {#ab1135c7a8ff766bc0ec72c55e1049d87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectVSplatSimm5Plus1 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SplatVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3574 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#ae4864665b5082511864fa8b4ad9ea5f9">selectVSplatImmHelper</a>.</p>

</div>
</div>

### selectVSplatSimm5Plus1NonZero() {#abfe913dce113bf8f5d20f5e1fe1966b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectVSplatSimm5Plus1NonZero (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SplatVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3580 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#ae4864665b5082511864fa8b4ad9ea5f9">selectVSplatImmHelper</a>.</p>

</div>
</div>

### selectVSplatUimm() {#aff942d6f8939b769939917efd741bde5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectVSplatUimm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, unsigned Bits, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SplatVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a995470163b6d76695cba5bc8dfb529">llvm::isUIntN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#ae4864665b5082511864fa8b4ad9ea5f9">selectVSplatImmHelper</a>.</p>


<p>Referenced by <a href="#a0fe3090ddbfdb18ba09417cd06334349">selectVSplatUimmBits</a>.</p>

</div>
</div>

### selectVSplatUimmBits() {#a0fe3090ddbfdb18ba09417cd06334349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::selectVSplatUimmBits (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Val)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#aff942d6f8939b769939917efd741bde5">selectVSplatUimm</a>.</p>

</div>
</div>

### selectVSSEG() {#abf23f63b97b9f5f99c3dd3c3a986e418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVDAGToDAGISel::selectVSSEG (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, unsigned NF, bool IsMasked, bool IsStrided)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a824579538728c6e67cf9a6191e5894e3">addVectorLoadStoreOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac27709ca33b27034fb25d6fb83cb5fb1">llvm::RISCVTargetLowering::getLMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

### selectVSXSEG() {#a35a4f3715a02bc5b5d9ced3b5324f439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVDAGToDAGISel::selectVSXSEG (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, unsigned NF, bool IsMasked, bool IsOrdered)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a824579538728c6e67cf9a6191e5894e3">addVectorLoadStoreOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#a5144889af710ec49f5eeff7be79e671d">llvm::RISCVVType::decodeVLMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac27709ca33b27034fb25d6fb83cb5fb1">llvm::RISCVTargetLowering::getLMUL</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a1eb420ba23c865af3024a336e491b983">llvm::MVT::getVectorMinNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#ad53ed145f88b1e1c966ff68df9029e7f">llvm::RISCV::RVVBitsPerBlock</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

### selectZExtBits() {#a05b5cba8cfdcec8f2d1dafb06fb63ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::selectZExtBits (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, unsigned Bits, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3041 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aeaf22e8d92fd978a5eca9ab031994399">llvm::APInt::getBitsSetFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#af01870e7e19b1220afa10a19f526c533">selectZExtBits</a>.</p>

</div>
</div>

### selectZExtBits() {#af01870e7e19b1220afa10a19f526c533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVDAGToDAGISel::selectZExtBits (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Val)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a05b5cba8cfdcec8f2d1dafb06fb63ab5">selectZExtBits</a>.</p>

</div>
</div>

### tryIndexedLoad() {#afa371a03066103bb85f89636e86686d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::tryIndexedLoad (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode/#a4030b40c584191b8fd4ad3febacfc082">llvm::LSBaseSDNode::getAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#a20fd5ba47db6a4cc8ad9d197fc1bbbee">llvm::LoadSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ab858661e16a61c4fc6b27b6b26aac17b">llvm::MemSDNode::getChain</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#ad85ec82447c2f1824538de9b449ffed0">llvm::LoadSDNode::getExtensionType</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aee0e58997cd08983518f051e79b855d9">llvm::MemSDNode::getMemoryVT</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#a71689ed396153740b31ac1a182364651">llvm::LoadSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac0a534d63ac5c5b87f36acdade953fbe">llvm::SDNode::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31a866c29237765ff291c9503abbdca60e1">llvm::ISD::POST_INC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31ab5bb854fadd42503c849c4a48d7f3d90">llvm::ISD::PRE_INC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31ade1c53e7b8a373e22ec53ff7bcbace9f">llvm::ISD::UNINDEXED</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

### tryShrinkShlLogicImm() {#a92a75fbae3b487187668a2099271d1a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::tryShrinkShlLogicImm (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a75d113cb1b8cc3c14b601d928dccee40">llvm::ConstantSDNode::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a5cb49674ec65724b4d9aecb48588a13a">llvm::ConstantSDNode::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a342c0d4e8e59b30daefe9a05bc2098bd">llvm::SDValue::hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

### trySignedBitfieldExtract() {#aa3196a845dd9ce40f3b0766ee99dea7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::trySignedBitfieldExtract (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a342c0d4e8e59b30daefe9a05bc2098bd">llvm::SDValue::hasOneUse</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>.</p>


<p>Referenced by <a href="#a7d60a41c0d5e450f770042d3427928d0">Select</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### doPeepholeMaskedRVV() {#a53c54937d0533922a882ec6e34c32fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::doPeepholeMaskedRVV (<a href="/web-llvm/docs/api/classes/llvm/machinesdnode">MachineSDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3815 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### doPeepholeMergeVVMFold() {#acc75be5ae6066c2bd794ca92cff5da7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::doPeepholeMergeVVMFold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 4080 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### doPeepholeNoRegPassThru() {#a47bfccc8301db8b0f7a86953b0295c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::doPeepholeNoRegPassThru ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If our passthru is an implicit_def, use noreg instead.</p>


<p>This side steps issues with MachineCSE not being able to CSE expressions with IMPLICIT_DEF operands while preserving the semantic intent. See pr64282 for context. Note that this transform is the last one performed at ISEL DAG to DAG.</p>


<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 4100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### doPeepholeSExtW() {#acafa4f39ff5b552aebc591881c7d8228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::doPeepholeSExtW (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3675 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### performCombineVMergeAndVOps() {#afcbf4fdfaeac8713f4f267124c22c45c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVDAGToDAGISel::performCombineVMergeAndVOps (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>, definition at line 3892 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Subtarget {#a57c98913ddf92cf8fb8329df22d1a904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVSubtarget* llvm::RISCVDAGToDAGISel::Subtarget = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getRISCVCCForIntCC() {#afe653782963dc86ef7f61b60b21dab8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVCC::CondCode llvm::RISCVDAGToDAGISel::getRISCVCCForIntCC (<a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> CC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976a57d7c413055b2060a90dc73ab8f1a512">llvm::RISCVCC::COND_EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976a9e7c8526fc843e319e53e5c3174296cc">llvm::RISCVCC::COND_GE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976a12fd715db7ef1428e9cf7b6af55997b8">llvm::RISCVCC::COND_GEU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976a442618536f16dd10730e054e0825b482">llvm::RISCVCC::COND_LT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976aefa5b6a280d2aec8bf02b490b207a3cb">llvm::RISCVCC::COND_LTU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976a11bb96a4ca4e914a149e9a63e6875ea6">llvm::RISCVCC::COND_NE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a7f47862de23f7210f88ccf98ae1efbe4">llvm::ISD::SETGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a6f05a09edb671910f85f8665981cbde9">llvm::ISD::SETLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a9dff1dcbac65852b71473818c11869b1">llvm::ISD::SETUGE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a473200f06bdd611fdbed43d908b84305">llvm::ISD::SETULT</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
