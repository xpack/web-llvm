---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86fastisel-cpp-/x86fastisel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86FastISel` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{X86FastISel.cpp}::X86FastISel { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a fast-path instruction selection class that generates poor code and doesn't support illegal types or non-trivial lowering, but runs quickly. <a href="/web-llvm/docs/api/classes/llvm/fastisel/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2401a1ee0b3876ea3c1cdfe7cd643bf">X86FastISel</a> (FunctionLoweringInfo &amp;funcInfo, const TargetLibraryInfo *libInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a246d108e7d516b651024d7ab2a75e9be">fastSelectInstruction</a> (const Instruction *I) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code when the normal FastISel process fails to select an instruction. <a href="#a246d108e7d516b651024d7ab2a75e9be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1616cca9834ae9c228730c62f4f8b43">tryToFoldLoadIntoMI</a> (MachineInstr *MI, unsigned OpNo, const LoadInst *LI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specified machine instr operand is a vreg, and that vreg is being provided by the specified load instruction. <a href="#aa1616cca9834ae9c228730c62f4f8b43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70544884c11636f144c5b3fa4bb939d8">fastLowerArguments</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code to do target- specific argument lowering. <a href="#a70544884c11636f144c5b3fa4bb939d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae60af15492a05f50005ff05276750228">fastLowerCall</a> (CallLoweringInfo &amp;CLI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code to do target- specific call lowering. <a href="#ae60af15492a05f50005ff05276750228">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d9eb53bc6802953e1a03c1acc8feb7b">fastLowerIntrinsicCall</a> (const IntrinsicInst *II) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by target-independent code to do target- specific intrinsic lowering. <a href="#a3d9eb53bc6802953e1a03c1acc8feb7b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b406abe592f8341e17357ecacbf7d1a">X86FastEmitCompare</a> (const Value *LHS, const Value *RHS, EVT VT, const DebugLoc &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02fe2fd73f8951505e7ebc0a3d42ed7a">X86FastEmitLoad</a> (MVT VT, X86AddressMode &amp;AM, MachineMemOperand *MMO, unsigned &amp;ResultReg, unsigned Alignment=1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>X86FastEmitLoad - Emit a machine instruction to load a value of type VT. <a href="#a02fe2fd73f8951505e7ebc0a3d42ed7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6954e957a743718f0a9209bbee478b22">X86FastEmitStore</a> (EVT VT, const Value *Val, X86AddressMode &amp;AM, MachineMemOperand *MMO=nullptr, bool Aligned=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0646c5831013896b2c27c57d90cef4e0">X86FastEmitStore</a> (EVT VT, unsigned ValReg, X86AddressMode &amp;AM, MachineMemOperand *MMO=nullptr, bool Aligned=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>X86FastEmitStore - Emit a machine instruction to store a value Val of type VT. <a href="#a0646c5831013896b2c27c57d90cef4e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11c9e5b11eb44e5204a9737dc93a4e8">X86FastEmitExtend</a> (ISD::NodeType Opc, EVT DstVT, unsigned Src, EVT SrcVT, unsigned &amp;ResultReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>X86FastEmitExtend - Emit a machine instruction to extend a value Src of type SrcVT to type DstVT using the specified extension opcode Opc (e.g. <a href="#af11c9e5b11eb44e5204a9737dc93a4e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fa82a5b15a96d83137e33f5c4761276">X86SelectAddress</a> (const Value *V, X86AddressMode &amp;AM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>X86SelectAddress - Attempt to fill in an address from the given value. <a href="#a4fa82a5b15a96d83137e33f5c4761276">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7ffe0d982659dfffee8d34226981f1e">X86SelectCallAddress</a> (const Value *V, X86AddressMode &amp;AM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>X86SelectCallAddress - Attempt to fill in an address from the given value. <a href="#ae7ffe0d982659dfffee8d34226981f1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cafdef3e474c19f9ce272dfc859e1d7">X86SelectLoad</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>X86SelectLoad - Select and emit code to implement load instructions. <a href="#a1cafdef3e474c19f9ce272dfc859e1d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5785c8325cd90987340a77418fd4b0af">X86SelectStore</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>X86SelectStore - Select and emit code to implement store instructions. <a href="#a5785c8325cd90987340a77418fd4b0af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad925eb58afe05cacb4f0d6a19868a5aa">X86SelectRet</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>X86SelectRet - Select and emit code to implement ret instructions. <a href="#ad925eb58afe05cacb4f0d6a19868a5aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a70f5e6a858b67c4a1f4b7a1b6179d5">X86SelectCmp</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f58e684be3709b97141ebe542f3a830">X86SelectZExt</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac03d535da822f42e85d794c13b891ec3">X86SelectSExt</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace050dbc3437b5ffbc3a3284eb7bb4a5">X86SelectBranch</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefad1eae7d509c4833b5c8e554943c8e">X86SelectShift</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ec8dc61333b07f62cf0804c8cc22e7">X86SelectDivRem</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdb76f00698c083a38e61ef9e504e960">X86FastEmitCMoveSelect</a> (MVT RetVT, const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a conditional move instruction (if the are supported) to lower the select. <a href="#afdb76f00698c083a38e61ef9e504e960">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fecf06b6807cc0e43b5b04653980521">X86FastEmitSSESelect</a> (MVT RetVT, const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit SSE or AVX instructions to lower the select. <a href="#a3fecf06b6807cc0e43b5b04653980521">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa31504981ba8f21e6653874fe7b79023">X86FastEmitPseudoSelect</a> (MVT RetVT, const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df9e6413891ac27ea6fd9933def8e19">X86SelectSelect</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd03c7d65c7e497e10b366c5ab74a284">X86SelectTrunc</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa02d2903053f6cd10ad0490b680e3492">X86SelectFPExtOrFPTrunc</a> (const Instruction *I, unsigned Opc, const TargetRegisterClass *RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f3634d42c2b5cdfb92dcf62ece8aefe">X86SelectFPExt</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fef9a862bd0655af023602ae1459488">X86SelectFPTrunc</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b86107bb77bb80750fde86c06a322c4">X86SelectSIToFP</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f357eae8836ef17c8a50c7d4d1d5621">X86SelectUIToFP</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b5f83944d87f6c8dd874baa681cd57e">X86SelectIntToFP</a> (const Instruction *I, bool IsSigned)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo">X86InstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63341c9cd646d9a6186b27329502bf24">getInstrInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine">X86TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a069b771a121be8666c3ca19abb94e72b">getTargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5e3bd88acd48c4fb3641576d3b0a218">handleConstantAddresses</a> (const Value *V, X86AddressMode &amp;AM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad72209c42f212df25ade2d762e6010e3">X86MaterializeInt</a> (const ConstantInt *CI, MVT VT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a315e2bea9c5f995d9a639b8e1ae01d07">X86MaterializeFP</a> (const ConstantFP *CFP, MVT VT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac238cb2c8ede3a65050b1ac398dac4b8">X86MaterializeGV</a> (const GlobalValue *GV, MVT VT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb4c2f003552b4e339a56787aa4cee36">fastMaterializeConstant</a> (const Constant *C) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a constant in a register using target-specific logic, such as constant pool loads. <a href="#acb4c2f003552b4e339a56787aa4cee36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3948fe0992cecd3f3c4ae4102a1abc9c">fastMaterializeAlloca</a> (const AllocaInst *C) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an alloca address in a register using target-specific logic. <a href="#a3948fe0992cecd3f3c4ae4102a1abc9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd153e8f9bf82e4596e18243741c608b">fastMaterializeFloatZero</a> (const ConstantFP *CF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the floating-point constant +0.0 in a register using target- specific logic. <a href="#afd153e8f9bf82e4596e18243741c608b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86a5db212e636ecf9828f22c8b9474cf">isScalarFPTypeInSSEReg</a> (EVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isScalarFPTypeInSSEReg - Return true if the specified scalar FP type is computed in an SSE register, not on the X87 floating point stack. <a href="#a86a5db212e636ecf9828f22c8b9474cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dd62abeff32c9bc6918d90b10910195">isTypeLegal</a> (Type *Ty, MVT &amp;VT, bool AllowI1=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea3ce4122ad8091034b916c8debfc9f8">IsMemcpySmall</a> (uint64_t Len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c4a50b4092658a31e726c8856860880">TryEmitSmallMemcpy</a> (X86AddressMode DestAM, X86AddressMode SrcAM, uint64_t Len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f39bd86327221792e9c6366aff9c95">foldX86XALUIntrinsic</a> (X86::CondCode &amp;CC, const Instruction *I, const Value *Cond)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if it is possible to fold the condition from the XALU intrinsic into the user. <a href="#a56f39bd86327221792e9c6366aff9c95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c9eea26c641feaf5808a6a18d4329fc">addFullAddress</a> (const MachineInstrBuilder &amp;MIB, X86AddressMode &amp;AM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a complex addressing mode to the given machine instr builder. <a href="#a1c9eea26c641feaf5808a6a18d4329fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14163612e77128ffe0e0c9d051eebbd1">fastEmitInst_rrrr</a> (unsigned MachineInstOpcode, const TargetRegisterClass *RC, unsigned Op0, unsigned Op1, unsigned Op2, unsigned Op3)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b2be7763eaa6501d59e6bb35853f4a9">Subtarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtarget - Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> around so that we can make the right decision when generating code for different targets. <a href="#a0b2be7763eaa6501d59e6bb35853f4a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86FastISel() {#aa2401a1ee0b3876ea3c1cdfe7cd643bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86FastISel.cpp}::X86FastISel::X86FastISel (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; funcInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * libInfo)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac447d383d507dc43c984bd02ff8e74ff">llvm::FastISel::FastISel</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a> and <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#ac9287d39f216ac61b351d95a4f7e3df3">llvm::FunctionLoweringInfo::MF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### fastLowerArguments() {#a70544884c11636f144c5b3fa4bb939d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::fastLowerArguments ()</td>
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

<p>This method is called by target-independent code to do target- specific argument lowering.</p>


<p>It returns true if it was successful.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a981679659ff46a72dc913da01553667a">llvm::FastISel::createResultReg</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a067a743bcdf919af7f64f48631be87fd">llvm::FastISel::DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aaa436dd9de743a96bbb98e9ca6065973">llvm::FastISel::FuncInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a2a394517076e7dd2bdcd7dde33dfcb7d">llvm::Type::isArrayTy</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a81eef9d7336f7ee43be79630d8e8ec86">llvm::Type::isStructTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ada788110c53e1082a0d10bb8cb379cce">llvm::FastISel::MIMD</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a9c3ffb1ecca8596b6653cc1ffdce8296">llvm::FastISel::TII</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#accec713e7a93d7b67101624dadf04c98">llvm::FastISel::TLI</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac32081d2d2bf0593aebb564fd7e11d8b">llvm::FastISel::updateValueMap</a>.</p>

</div>
</div>

### fastLowerCall() {#ae60af15492a05f50005ff05276750228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::fastLowerCall (<a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo">CallLoweringInfo</a> &amp; CLI)</td>
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

<p>This method is called by target-independent code to do target- specific call lowering.</p>


<p>It returns true if it was successful.</p>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e8b1da7820b3f19cfb702d4312410ce">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a9117be19af857a7bdcee7bdf0279024c">llvm::MachineInstrBuilder::addGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a8880ccaea51a4ee9b48c3c8d7fbfebf4">llvm::MachineInstrBuilder::addRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7ffeb5b3940506a54e69e72e26e2a6cd">llvm::MachineInstrBuilder::addSym</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45acc07b91f72979f3e9b12c2e0c355db46">llvm::CCValAssign::AExt</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45aeada2602a598f9b877f1b75ed7dd9e4a">llvm::CCValAssign::AExtUpper</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a808eee3ccda95974f0ac2b1c318ec336">llvm::CCState::AllocateStack</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a919797ac95a1d84d08e4f43eedededa4">llvm::CCState::AnalyzeCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a34218a663a02de9dc2d26a5639f58ebe">llvm::CCState::AnalyzeCallResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode/#a17a6d6e90566fa2abeb797273f9acc36">llvm::X86AddressMode::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a0f94adbbe71c94edaa533a25973bbffc">llvm::CCValAssign::BCvt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a83235b3d69702bbb34da1aaf32c5d683">llvm::FastISel::CallLoweringInfo::Call</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a308acf766fe89d05cbfc2f59581439b3">llvm::FastISel::CallLoweringInfo::CallConv</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a6d8e0bdad594214f654b1bb5bbd40f0a">llvm::FastISel::CallLoweringInfo::Callee</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a72f539529045e72c96f0712e812e4168">llvm::FastISel::CallLoweringInfo::CB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af275c1ff19bf83bb2a9001bc27e68e67">llvm::CC_X86</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp/#a494dabe67c8e93868fed4e59fbd49150">computeBytesPoppedByCalleeForSRet</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a981679659ff46a72dc913da01553667a">llvm::FastISel::createResultReg</a>, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode/#a883f2182cecc59883f24a9b886ffeb74">llvm::X86AddressMode::Disp</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a067a743bcdf919af7f64f48631be87fd">llvm::FastISel::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#af2202cab3109536077a683bcd326fe55">llvm::FastISel::fastEmit_r</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a3c42eef34e00640e9c0edc553e50d5dd">llvm::FastISel::fastEmit_ri</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ad9378963a44c6d0e07ea95c821442cc5">llvm::FastISel::fastEmitZExtFromI1</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45ac52f457c429c17250b13662a5ddd0c4a">llvm::CCValAssign::FPExt</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a8b73d77b9e54663c2e80a48d0917dce1">llvm::CCValAssign::Full</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aaa436dd9de743a96bbb98e9ca6065973">llvm::FastISel::FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#add9242b21eb68884a16629e9f7997479">llvm::CCState::getAlignedCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a191a65cff7d80b2651df427db2bbf908">llvm::CCState::getFirstUnallocated</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2897ab064cc53e41f2b6ae3d69902abc">llvm::CCValAssign::getLocInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#aa531ef30c8af299cbbd1a6660b3cf225">llvm::CCValAssign::getLocMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a17dbc2feaea84ef8d353095d6e618f29">llvm::CCValAssign::getLocReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#ab7c2e47e51795ce2f60500846109d5a7">llvm::CCValAssign::getLocVT</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5cec24eb4eadf1232a1463fdbb1cc1a0">llvm::FastISel::getRegForValue</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a2f877286c09d06ac6b9c5534736433d9">llvm::MachinePointerInfo::getStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ab8e1af73424a59a00656c9ffd505c03f">llvm::MVT::getStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#aad6f82d490b016e27d3a4cd7ab7efdf6">llvm::CCValAssign::getValNo</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5972ab02a98f9b5ce46e7f55fd711982">llvm::CCValAssign::getValVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode/#a69cfaa345b14e467ea8934fe48cc3365">llvm::X86AddressMode::GV</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a140af9f05b67d6b2a3b7cc8513254e2f">llvm::CallBase::hasInAllocaArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45aacf7e7d80f766b55b2bbdaf3d354c39e">llvm::CCValAssign::Indirect</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#ad174f5cc68bbbe72a8b902c289320b45">llvm::FastISel::CallLoweringInfo::InRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#afceb1c03b606771c10a049ef11f53d54">llvm::FastISel::CallLoweringInfo::Ins</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a98bec313edd88412de74ae369ce47005">llvm::X86::isCalleePop</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a437cf7bc875369cbe0ea62f949626f0b">llvm::MVT::isInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5bb903a1b21cafe8f73ce95ed629882e">llvm::CCValAssign::isMemLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a07dddcff2886a2b840f993f7ce17dd28">llvm::CCValAssign::isRegLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a5633911fe4a62451aa4b7f69454a5751">llvm::FastISel::CallLoweringInfo::IsTailCall</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a3e2a0b115bdda6287fac43fb71ff7352">llvm::FastISel::CallLoweringInfo::IsVarArg</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a79b79f09f234c1ef637c6d5a4b91e4cc">llvm::FastISel::MFI</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ada788110c53e1082a0d10bb8cb379cce">llvm::FastISel::MIMD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a59da9a9089b55f8b8353fda32a609457">llvm::X86II::MO_COFFSTUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ac7366ddd1a9010fa97b002cad95c3044">llvm::X86II::MO_DLLIMPORT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ae39565b585476b7142228e439e80372e">llvm::X86II::MO_GOTPCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a115ba6fe8930383c25e51d587e6a333b">llvm::X86II::MO_GOTPCREL_NORELAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ab9508856c635578f8aaed9dd83c3f347">llvm::X86II::MO_NO_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ab2b21d9c332e616e0a11c3ff76ce0bdf">llvm::X86II::MO_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a40c6e80d35c80d65edc16ffa7ab0d39d">llvm::FastISel::CallLoweringInfo::NumResultRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9cadb925bc2eb2c117b3ec0b76d1e267127">llvm::LLVMContext::OB_kcfi</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a333d2c82c193e4c258195e5f7ba3aed6">llvm::FastISel::CallLoweringInfo::OutFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a5370ad419a3bd87b4499e92b1e160736">llvm::FastISel::CallLoweringInfo::OutRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a3d86d7e9ef4938e1192b4bb4e2a6507d">llvm::FastISel::CallLoweringInfo::OutVals</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode/#abdbb5443e06c46eba409abb252121105">llvm::X86AddressMode::Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a236216be5ea40fdc49efb658bf58e67b">llvm::FastISel::CallLoweringInfo::ResultReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a1021f8433bfd1bad9e48d7c477a79b">llvm::RetCC_X86</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a35d74a4f3f503bb98e00ece4a618b2cf">llvm::FastISel::CallLoweringInfo::RetTy</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a7fd25972cdb14499949c7726499e0cb6">llvm::CCValAssign::SExt</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45aec09697a16bc3cc461d29f0f551e63c0">llvm::CCValAssign::SExtUpper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a2102fa713297236bf4339c5f0bf0f39d">llvm::Reloc::Static</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca2740493172a4ce246941c8cff95e0f83">llvm::CallingConv::Swift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#ac5d9d3725e9cf5db27852d455856d54c">llvm::FastISel::CallLoweringInfo::Symbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad6e9c0ff694f0fca0222e79e772b647e">llvm::CallingConv::Tail</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a9c3ffb1ecca8596b6653cc1ffdce8296">llvm::FastISel::TII</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ad1634563b73a5a9df8b459d913fa4943">llvm::FastISel::TM</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#afe0bba218f685c37e6c1ca4b49d2d1f1">llvm::FastISel::TRI</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a467b8d92c7df0dbb83e53cf2694920c4">llvm::CCValAssign::Trunc</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45aac6bf1a4743f81c8ee1cb10ef85ce063">llvm::CCValAssign::VExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae41511c1ad4197da36cef403f34bac72">llvm::CallingConv::Win64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca10f11fb587acddab17f3ad85eb698fbe">llvm::CallingConv::X86_64_SysV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafde87569738f9e23963e8735f71c33eb">llvm::CallingConv::X86_FastCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caa88ccf4313b5bc700dec76fd9bc5d40e">llvm::CallingConv::X86_StdCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca97109ccd68cac64fb38dbd24fc4589c6">llvm::CallingConv::X86_ThisCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a807a4e133d7f743724d809a3f3875aa2">llvm::CCValAssign::ZExt</a> and <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a17dad9007e52963b27d90b46bfab8cb5">llvm::CCValAssign::ZExtUpper</a>.</p>

</div>
</div>

### fastLowerIntrinsicCall() {#a3d9eb53bc6802953e1a03c1acc8feb7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::fastLowerIntrinsicCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II)</td>
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

<p>This method is called by target-independent code to do target- specific intrinsic lowering.</p>


<p>It returns true if it was successful.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff98f30548a2233baed77a73408842a2">llvm::addDirectMem</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2eac9ae7c779ffc6865536d9f164ebf09b9">llvm::X86::COND_B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2ea914c19eb31606e70fd4f8dfff6d86038">llvm::X86::COND_O</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a981679659ff46a72dc913da01553667a">llvm::FastISel::createResultReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a067a743bcdf919af7f64f48631be87fd">llvm::FastISel::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#af2202cab3109536077a683bcd326fe55">llvm::FastISel::fastEmit_r</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a3c42eef34e00640e9c0edc553e50d5dd">llvm::FastISel::fastEmit_ri</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#acfe921ad48553b0de6fe092d66e54671">llvm::FastISel::fastEmit_rr</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a03ab338e9e5f4ea24b2049ab525525bf">llvm::FastISel::fastEmitInst_extractsubreg</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a43873dfd861406dc9da68ddcd2bfe1bc">llvm::FastISel::fastEmitInst_r</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aef1cb331526de21d6b1729a42a72d74f">llvm::FastISel::fastEmitInst_ri</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a8d85017ca59fd0d13bde23551dfc5f90">llvm::FastISel::fastEmitInst_rr</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aaa436dd9de743a96bbb98e9ca6065973">llvm::FastISel::FuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp/#a23ffb844d0a50f112dc26ac2d0e41910">GET_EGPR_IF_ENABLED</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgdeclareinst/#a3dd0197b425429468709af927dd71f08">llvm::DbgDeclareInst::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#ad118358d398f591303b00c2e5462e3a9">llvm::MemIntrinsicBase&lt; Derived &gt;::getDestAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#ad1707c1c1ab1f3278424f265893c87fb">llvm::DbgVariableIntrinsic::getExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a0fef04103987e9763468d19eb680b223">llvm::MemIntrinsicBase&lt; Derived &gt;::getLength</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a18d6accbeb5cb7b8051219b8b4ddd4f7">llvm::MemIntrinsicBase&lt; Derived &gt;::getRawDest</a>, <a href="/web-llvm/docs/api/classes/llvm/memtransferbase/#aa3c771310b66362b6a032071f63776bb">llvm::MemTransferBase&lt; BaseCL &gt;::getRawSource</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5cec24eb4eadf1232a1463fdbb1cc1a0">llvm::FastISel::getRegForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/memtransferbase/#aa4905f44616de7dcca8ce3d51685a60b">llvm::MemTransferBase&lt; BaseCL &gt;::getSourceAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a854857be09a21f27fb21ba872fe6f639">llvm::DbgVariableIntrinsic::getVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#ac8c4cb4dde7067286d3e3ce80bf77224">llvm::DILocalVariable::isValidLocationForIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsic/#ada78af22b202d8b7d9fe772c2c9476ce">llvm::MemIntrinsic::isVolatile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a429785d5b6015aff39a7a998d9e70fa3">llvm::FastISel::lowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a79d5f0dde17b382c909b9806e9436592">llvm::FastISel::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a79b79f09f234c1ef637c6d5a4b91e4cc">llvm::FastISel::MFI</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ada788110c53e1082a0d10bb8cb379cce">llvm::FastISel::MIMD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7ae4b4652e07c1ad3ff57c36e3f04f89">llvm::X86ISD::SMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a9c3ffb1ecca8596b6653cc1ffdce8296">llvm::FastISel::TII</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#accec713e7a93d7b67101624dadf04c98">llvm::FastISel::TLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac459a26428cf593d442a86904673b560">llvm::X86ISD::UMUL</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac32081d2d2bf0593aebb564fd7e11d8b">llvm::FastISel::updateValueMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### fastSelectInstruction() {#a246d108e7d516b651024d7ab2a75e9be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::fastSelectInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>This method is called by target-independent code when the normal FastISel process fails to select an instruction.</p>


<p>This gives targets a chance to emit code for anything that doesn't fit into FastISel's framework. It returns true if it was successful.</p>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3ad406477784397709a339d5a2957b43">llvm::EVT::bitsGT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3bf257bfbd279ecfad670be03b00210e">llvm::EVT::bitsLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a981679659ff46a72dc913da01553667a">llvm::FastISel::createResultReg</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a067a743bcdf919af7f64f48631be87fd">llvm::FastISel::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aaa436dd9de743a96bbb98e9ca6065973">llvm::FastISel::FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5cec24eb4eadf1232a1463fdbb1cc1a0">llvm::FastISel::getRegForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ada788110c53e1082a0d10bb8cb379cce">llvm::FastISel::MIMD</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a9c3ffb1ecca8596b6653cc1ffdce8296">llvm::FastISel::TII</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#accec713e7a93d7b67101624dadf04c98">llvm::FastISel::TLI</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac32081d2d2bf0593aebb564fd7e11d8b">llvm::FastISel::updateValueMap</a>.</p>

</div>
</div>

### tryToFoldLoadIntoMI() {#aa1616cca9834ae9c228730c62f4f8b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::tryToFoldLoadIntoMI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI)</td>
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

<p>The specified machine instr operand is a vreg, and that vreg is being provided by the specified load instruction.</p>


<p>If possible, try to fold the load as an operand to the instruction, returning true if possible.</p>


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a6bec3fdf48dcde80a42b76f09d151a03">llvm::FastISel::createMachineMemOperandFor</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a067a743bcdf919af7f64f48631be87fd">llvm::FastISel::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a7cfc0ecfec922ebf19bd023f3b675604">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aaa436dd9de743a96bbb98e9ca6065973">llvm::FastISel::FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#af51c113a039c82f6870df5dc9666b5e3">llvm::LoadInst::getAlign</a>, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode/#a593e839307453b63de7b7021e8cc059a">llvm::X86AddressMode::getFullAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode/#af1965b0188d8595d0aaf002d0eb6d009">llvm::X86AddressMode::IndexReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a6066bf2100d34651261866662b42114e">llvm::FastISel::removeDeadCode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a9c3ffb1ecca8596b6653cc1ffdce8296">llvm::FastISel::TII</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addFullAddress() {#a1c9eea26c641feaf5808a6a18d4329fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; X86FastISel::addFullAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode">X86AddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds a complex addressing mode to the given machine instr builder.</p>


<p>Note, this will constrain the index register. If its not possible to constrain the given index register, then a new one will be created. The IndexReg field of the addressing mode will be updated to match in this case.</p>


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### fastEmitInst\_rrrr() {#a14163612e77128ffe0e0c9d051eebbd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86FastISel::fastEmitInst_rrrr (unsigned MachineInstOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned Op0, unsigned Op1, unsigned Op2, unsigned Op3)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### fastMaterializeAlloca() {#a3948fe0992cecd3f3c4ae4102a1abc9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86FastISel::fastMaterializeAlloca (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * C)</td>
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

<p>Emit an alloca address in a register using target-specific logic.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### fastMaterializeConstant() {#acb4c2f003552b4e339a56787aa4cee36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86FastISel::fastMaterializeConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
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

<p>Emit a constant in a register using target-specific logic, such as constant pool loads.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### fastMaterializeFloatZero() {#afd153e8f9bf82e4596e18243741c608b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86FastISel::fastMaterializeFloatZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * CF)</td>
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

<p>Emit the floating-point constant +0.0 in a register using target- specific logic.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### foldX86XALUIntrinsic() {#a56f39bd86327221792e9c6366aff9c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::foldX86XALUIntrinsic (<a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2e">X86::CondCode</a> &amp; CC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if it is possible to fold the condition from the XALU intrinsic into the user.</p>


<p>The condition code will only be updated on success.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### getInstrInfo() {#a63341c9cd646d9a6186b27329502bf24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86InstrInfo * anonymous{X86FastISel.cpp}::X86FastISel::getInstrInfo ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### getTargetMachine() {#a069b771a121be8666c3ca19abb94e72b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86TargetMachine * anonymous{X86FastISel.cpp}::X86FastISel::getTargetMachine ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### handleConstantAddresses() {#ad5e3bd88acd48c4fb3641576d3b0a218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::handleConstantAddresses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode">X86AddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### IsMemcpySmall() {#aea3ce4122ad8091034b916c8debfc9f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::IsMemcpySmall (uint64_t Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### isScalarFPTypeInSSEReg() {#a86a5db212e636ecf9828f22c8b9474cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86FastISel.cpp}::X86FastISel::isScalarFPTypeInSSEReg (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>isScalarFPTypeInSSEReg - Return true if the specified scalar FP type is computed in an SSE register, not on the X87 floating point stack.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### isTypeLegal() {#a3dd62abeff32c9bc6918d90b10910195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::isTypeLegal (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; VT, bool AllowI1=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### TryEmitSmallMemcpy() {#a5c4a50b4092658a31e726c8856860880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::TryEmitSmallMemcpy (<a href="/web-llvm/docs/api/structs/llvm/x86addressmode">X86AddressMode</a> DestAM, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode">X86AddressMode</a> SrcAM, uint64_t Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86FastEmitCMoveSelect() {#afdb76f00698c083a38e61ef9e504e960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86FastEmitCMoveSelect (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> RetVT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a conditional move instruction (if the are supported) to lower the select.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86FastEmitCompare() {#a0b406abe592f8341e17357ecacbf7d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86FastEmitCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86FastEmitExtend() {#af11c9e5b11eb44e5204a9737dc93a4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86FastEmitExtend (<a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a> Opc, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> DstVT, unsigned Src, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SrcVT, unsigned &amp; ResultReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>X86FastEmitExtend - Emit a machine instruction to extend a value Src of type SrcVT to type DstVT using the specified extension opcode Opc (e.g.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">ISD::SIGN_EXTEND</a>).</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86FastEmitLoad() {#a02fe2fd73f8951505e7ebc0a3d42ed7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86FastEmitLoad (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode">X86AddressMode</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO, unsigned &amp; ResultReg, unsigned Alignment=1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>X86FastEmitLoad - Emit a machine instruction to load a value of type VT.</p>


<p>The address is either pre-computed, i.e. Ptr, or a GlobalAddress, i.e. GV. Return true and the result register by reference if it is possible.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86FastEmitPseudoSelect() {#aa31504981ba8f21e6653874fe7b79023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86FastEmitPseudoSelect (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> RetVT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86FastEmitSSESelect() {#a3fecf06b6807cc0e43b5b04653980521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86FastEmitSSESelect (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> RetVT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit SSE or AVX instructions to lower the select.</p>


<p>Try to use SSE1/SSE2 instructions to simulate a select without branches. This lowers fp selects into a CMP/AND/ANDN/OR sequence when the necessary SSE instructions are available. If AVX is available, try to use a VBLENDV.</p>


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86FastEmitStore() {#a6954e957a743718f0a9209bbee478b22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86FastEmitStore (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode">X86AddressMode</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO=nullptr, bool Aligned=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86FastEmitStore() {#a0646c5831013896b2c27c57d90cef4e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86FastEmitStore (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned ValReg, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode">X86AddressMode</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO=nullptr, bool Aligned=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>X86FastEmitStore - Emit a machine instruction to store a value Val of type VT.</p>


<p>The address is either pre-computed, consisted of a base ptr, Ptr and a displacement offset, or a GlobalAddress, i.e. V. Return true if it is possible.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86MaterializeFP() {#a315e2bea9c5f995d9a639b8e1ae01d07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86FastISel::X86MaterializeFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * CFP, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86MaterializeGV() {#ac238cb2c8ede3a65050b1ac398dac4b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86FastISel::X86MaterializeGV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86MaterializeInt() {#ad72209c42f212df25ade2d762e6010e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86FastISel::X86MaterializeInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectAddress() {#a4fa82a5b15a96d83137e33f5c4761276}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode">X86AddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>X86SelectAddress - Attempt to fill in an address from the given value.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectBranch() {#ace050dbc3437b5ffbc3a3284eb7bb4a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectBranch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectCallAddress() {#ae7ffe0d982659dfffee8d34226981f1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectCallAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode">X86AddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>X86SelectCallAddress - Attempt to fill in an address from the given value.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectCmp() {#a4a70f5e6a858b67c4a1f4b7a1b6179d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectCmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectDivRem() {#ab8ec8dc61333b07f62cf0804c8cc22e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectDivRem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectFPExt() {#a4f3634d42c2b5cdfb92dcf62ece8aefe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectFPExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectFPExtOrFPTrunc() {#aa02d2903053f6cd10ad0490b680e3492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectFPExtOrFPTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, unsigned Opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectFPTrunc() {#a0fef9a862bd0655af023602ae1459488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectFPTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectIntToFP() {#a6b5f83944d87f6c8dd874baa681cd57e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectIntToFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, bool IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectLoad() {#a1cafdef3e474c19f9ce272dfc859e1d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>X86SelectLoad - Select and emit code to implement load instructions.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectRet() {#ad925eb58afe05cacb4f0d6a19868a5aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectRet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>X86SelectRet - Select and emit code to implement ret instructions.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectSelect() {#a7df9e6413891ac27ea6fd9933def8e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectSelect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectSExt() {#ac03d535da822f42e85d794c13b891ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectSExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectShift() {#aefad1eae7d509c4833b5c8e554943c8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectShift (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectSIToFP() {#a5b86107bb77bb80750fde86c06a322c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectSIToFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectStore() {#a5785c8325cd90987340a77418fd4b0af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>X86SelectStore - Select and emit code to implement store instructions.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectTrunc() {#abd03c7d65c7e497e10b366c5ab74a284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectUIToFP() {#a3f357eae8836ef17c8a50c7d4d1d5621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectUIToFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

### X86SelectZExt() {#a4f58e684be3709b97141ebe542f3a830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86FastISel::X86SelectZExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Subtarget {#a0b2be7763eaa6501d59e6bb35853f4a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86Subtarget* anonymous{X86FastISel.cpp}::X86FastISel::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subtarget - Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> around so that we can make the right decision when generating code for different targets.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
