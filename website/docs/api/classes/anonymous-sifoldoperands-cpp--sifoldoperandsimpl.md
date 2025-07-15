---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SIFoldOperandsImpl` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4831aecc1c400c0f6fc9be32b378523a">SIFoldOperandsImpl</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66eb61143b269793cb50e67646375778">frameIndexMayFold</a> (const MachineInstr &amp;UseMI, int OpNo, const MachineOperand &amp;OpToFold) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a475c646660977940514023300390c93a">convertToVALUOp</a> (unsigned Opc, bool UseVOP3=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64c6eca16f58ce5cef19b84d78d3adb7">foldCopyToVGPROfScalarAddOfFrameIndex</a> (Register DstReg, Register SrcReg, MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fold vgpr = COPY (S_ADD_I32 x, frameindex) <a href="#a64c6eca16f58ce5cef19b84d78d3adb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c7d1732461b6f0d88e719eebadf9f2a">updateOperand</a> (FoldCandidate &amp;Fold) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa577b8bdb7ed00babf58c076a4978f38">canUseImmWithOpSel</a> (FoldCandidate &amp;Fold) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35b932e3e318fc132ddc4eba034d9a12">tryFoldImmWithOpSel</a> (FoldCandidate &amp;Fold) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f87ab4ea0d4b9807d9a5318edcb205b">tryAddToFoldList</a> (SmallVectorImpl&lt; FoldCandidate &gt; &amp;FoldList, MachineInstr *MI, unsigned OpNo, MachineOperand *OpToFold) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51dc84de00cc6a5bf725b831737c8296">isUseSafeToFold</a> (const MachineInstr &amp;MI, const MachineOperand &amp;UseMO) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cb505493f51b96cbb394d89b93f686e">getRegSeqInit</a> (SmallVectorImpl&lt; std::pair&lt; MachineOperand *, unsigned &gt; &gt; &amp;Defs, Register UseReg, uint8_t OpTy) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd13e2195957a8e92e36d055dde1ffb8">tryToFoldACImm</a> (const MachineOperand &amp;OpToFold, MachineInstr *UseMI, unsigned UseOpIdx, SmallVectorImpl&lt; FoldCandidate &gt; &amp;FoldList) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a> (MachineOperand &amp;OpToFold, MachineInstr *UseMI, int UseOpIdx, SmallVectorImpl&lt; FoldCandidate &gt; &amp;FoldList, SmallVectorImpl&lt; MachineInstr * &gt; &amp;CopiesToReplace) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdc089f7e9f2dddcf2412615f90690a9">getImmOrMaterializedImm</a> (MachineOperand &amp;Op) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1124ea4e69342296db6a2b6628121436">tryConstantFoldOp</a> (MachineInstr *MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2929348b6b6f3ad543717d42b201640d">tryFoldCndMask</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acab876eafd3f522831a5d002faecc72b">tryFoldZeroHighBits</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a727184c28151d2b605686087351b8d7b">foldInstOperand</a> (MachineInstr &amp;MI, MachineOperand &amp;OpToFold) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9ca747a6b6297f53d182bfe78514963">tryFoldFoldableCopy</a> (MachineInstr &amp;MI, MachineOperand *&amp;CurrentKnownM0Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fbf0d819e9a71ced3199693268238ce">isClamp</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08bf0b055eab1a86300c18c2b0f9fc7e">tryFoldClamp</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e62a05741edcd4375c97fd4906b419d">isOMod</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e1eb00d7eee7258726795f01822d491">tryFoldOMod</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a553d8629e18f8acb82dbadd0a160b877">tryFoldRegSequence</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17772fd1beeccd740ec6412abad098f9">tryFoldPhiAGPR</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac5e465289c9bc7adb88b6b682fdf85b">tryFoldLoad</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8562a883d9494266aca5d1b2f8b5dc5e">tryOptimizeAGPRPhis</a> (MachineBasicBlock &amp;MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a091988829e1f57d6a9710575591f4845">run</a> (MachineFunction &amp;MF)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6917282da348ebaf7919a7c0e66b1c93">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a1e046b8ad8a2f498a2c1fadbbe1edc">ST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo">SIMachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b7d1f6255a7a32f8a5b0ebfa1debca">MFI</a></td>
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


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIFoldOperandsImpl() {#a4831aecc1c400c0f6fc9be32b378523a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::SIFoldOperandsImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Reference <a href="#a091988829e1f57d6a9710575591f4845">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canUseImmWithOpSel() {#aa577b8bdb7ed00babf58c076a4978f38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::canUseImmWithOpSel (<a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate">FoldCandidate</a> &amp; Fold)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecabd8ac36f299f3add1ff63d49475d51a5">llvm::SIInstrFlags::IsDOT</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a2e26fd696a0dc5122dea22f2858c40a0">anonymous{SIFoldOperands.cpp}::FoldCandidate::isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaa0bc33f3818c02a577a8b209d98766cb">llvm::SIInstrFlags::IsMAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaacf639f4528a313767923c5575e1828e">llvm::SIInstrFlags::IsPacked</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca2b696c2aeb385ace4a1088a1169606a4">llvm::SIInstrFlags::IsSWMMAC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecadb719433b001db91973f66b4bc3b6dc8">llvm::SIInstrFlags::IsWMMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a69bbd47f175c95849d7a6086a6550a66">llvm::AMDGPU::OPERAND_REG_IMM_V2BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a20958300f68759315cb6cb2491d42cec">llvm::AMDGPU::OPERAND_REG_IMM_V2FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a455e964e5660b09e16a498dd96cf0bd6">llvm::AMDGPU::OPERAND_REG_IMM_V2INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a431ef474cd3520ce1676091d1297cbac">llvm::AMDGPU::OPERAND_REG_INLINE_C_V2BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9babf1fd52dcf14ed0effdd6fe207007">llvm::AMDGPU::OPERAND_REG_INLINE_C_V2FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ad6dad922f054838a22df6973a79987be">llvm::AMDGPU::OPERAND_REG_INLINE_C_V2INT16</a>, <a href="#a7a1e046b8ad8a2f498a2c1fadbbe1edc">ST</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#aa00fe1221e478602346344c7315f057a">anonymous{SIFoldOperands.cpp}::FoldCandidate::UseMI</a> and <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a67061b2f666f6aaacf5bf3dd623dc30e">anonymous{SIFoldOperands.cpp}::FoldCandidate::UseOpNo</a>.</p>


<p>Referenced by <a href="#a1f87ab4ea0d4b9807d9a5318edcb205b">tryAddToFoldList</a> and <a href="#a0c7d1732461b6f0d88e719eebadf9f2a">updateOperand</a>.</p>

</div>
</div>

### convertToVALUOp() {#a475c646660977940514023300390c93a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::convertToVALUOp (unsigned Opc, bool UseVOP3=false)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Reference <a href="#a7a1e046b8ad8a2f498a2c1fadbbe1edc">ST</a>.</p>


<p>Referenced by <a href="#a64c6eca16f58ce5cef19b84d78d3adb7">foldCopyToVGPROfScalarAddOfFrameIndex</a>.</p>

</div>
</div>

### foldCopyToVGPROfScalarAddOfFrameIndex() {#a64c6eca16f58ce5cef19b84d78d3adb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::foldCopyToVGPROfScalarAddOfFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fold vgpr = COPY (S_ADD_I32 x, frameindex)</p>


<p>=&gt; vgpr = V_ADD_U32 x, frameindex</p>


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#a475c646660977940514023300390c93a">convertToVALUOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a2fee1a7db4e84247a193a9af1f907013">llvm::RegState::Dead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#af0288e181965a5ff9f0c7a75201fd142a092531ae27becd74d96d4a6fae76f863">llvm::MachineBasicBlock::LQR_Dead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#adf25b569ca308aacc819a2331626ed5d">llvm::MachineInstrBuilder::setMIFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a45ffb8b95e5b75eeb68be7d300eb9618">llvm::MachineInstrBuilder::setOperandDead</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a> and <a href="#a6917282da348ebaf7919a7c0e66b1c93">TRI</a>.</p>


<p>Referenced by <a href="#ac9ca747a6b6297f53d182bfe78514963">tryFoldFoldableCopy</a>.</p>

</div>
</div>

### foldInstOperand() {#a727184c28151d2b605686087351b8d7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::foldInstOperand (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; OpToFold)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a20c762703f9faa4263464684aae1ad">llvm::execMayBeModifiedBeforeUse</a>, <a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>, <a href="#a6917282da348ebaf7919a7c0e66b1c93">TRI</a>, <a href="#a1124ea4e69342296db6a2b6628121436">tryConstantFoldOp</a>, <a href="#a0c7d1732461b6f0d88e719eebadf9f2a">updateOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="#ac9ca747a6b6297f53d182bfe78514963">tryFoldFoldableCopy</a>.</p>

</div>
</div>

### foldOperand() {#a96e06941b1694e3eb5cfd4efb2d69b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIFoldOperandsImpl::foldOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; OpToFold, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * UseMI, int UseOpIdx, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate">FoldCandidate</a> &gt; &amp; FoldList, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; CopiesToReplace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a60b6974966381f08079722f2258a0039">llvm::TargetRegisterClass::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a20c762703f9faa4263464684aae1ad">llvm::execMayBeModifiedBeforeUse</a>, <a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a>, <a href="#a66eb61143b269793cb50e67646375778">frameIndexMayFold</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a75a5f7e3b3d4ec79610b4e556d2f35ce">llvm::MachineInstr::getDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae86326b2bc0ff967b391246b7c63b46f">llvm::AMDGPU::getFlatScratchInstSSfromSV</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a5574b8f058874009cab01e055a44338a">llvm::MachineInstr::getOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#acc8a2c40a5d623bd8c7c28e93eda91d3">llvm::AMDGPU::getRegBitWidth</a>, <a href="#a3cb505493f51b96cbb394d89b93f686e">getRegSeqInit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08d85ca884294cf7a067290c1593fd50">llvm::getRegSubRegPair</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="#a51dc84de00cc6a5bf725b831737c8296">isUseSafeToFold</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#ade5781c13cce7ee39fe5cc54dcebccd8">llvm::MCInstrDesc::isVariadic</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a28b7d1f6255a7a32f8a5b0ebfa1debca">MFI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ad670957823c39ba1006b962d2023a19a">llvm::AMDGPU::OPERAND_REG_INLINE_C_INT32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0f4e09a761d45bf0914f26d4c149ddeb">llvm::MCInstrDesc::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair/#aad7e848e562b1368d6ee4794d84957c6">llvm::TargetInstrInfo::RegSubRegPair::Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a7a1e046b8ad8a2f498a2c1fadbbe1edc">ST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>, <a href="#a6917282da348ebaf7919a7c0e66b1c93">TRI</a>, <a href="#a1f87ab4ea0d4b9807d9a5318edcb205b">tryAddToFoldList</a>, <a href="#acd13e2195957a8e92e36d055dde1ffb8">tryToFoldACImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a02230ca194a9c8e52170cc7c426decb2">UseReg</a>.</p>


<p>Referenced by <a href="#a727184c28151d2b605686087351b8d7b">foldInstOperand</a> and <a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a>.</p>

</div>
</div>

### frameIndexMayFold() {#a66eb61143b269793cb50e67646375778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::frameIndexMayFold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI, int OpNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; OpToFold)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a>.</p>

</div>
</div>

### getImmOrMaterializedImm() {#acdc089f7e9f2dddcf2412615f90690a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand * SIFoldOperandsImpl::getImmOrMaterializedImm (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a> and <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>.</p>


<p>Referenced by <a href="#a1124ea4e69342296db6a2b6628121436">tryConstantFoldOp</a>, <a href="#a2929348b6b6f3ad543717d42b201640d">tryFoldCndMask</a> and <a href="#acab876eafd3f522831a5d002faecc72b">tryFoldZeroHighBits</a>.</p>

</div>
</div>

### getRegSeqInit() {#a3cb505493f51b96cbb394d89b93f686e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::getRegSeqInit (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *, unsigned &gt; &gt; &amp; Defs, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> UseReg, uint8_t OpTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a02230ca194a9c8e52170cc7c426decb2">UseReg</a>.</p>


<p>Referenced by <a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a>, <a href="#a553d8629e18f8acb82dbadd0a160b877">tryFoldRegSequence</a> and <a href="#acd13e2195957a8e92e36d055dde1ffb8">tryToFoldACImm</a>.</p>

</div>
</div>

### isClamp() {#a6fbf0d819e9a71ced3199693268238ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineOperand * SIFoldOperandsImpl::isClamp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442af0e8126187c47c5b74a1bdc635158144">llvm::SISrcMods::OP_SEL_1</a> and <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>.</p>


<p>Referenced by <a href="#a08bf0b055eab1a86300c18c2b0f9fc7e">tryFoldClamp</a>.</p>

</div>
</div>

### isOMod() {#a7e62a05741edcd4375c97fd4906b419d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const MachineOperand *, int &gt; SIFoldOperandsImpl::isOMod (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a8e5c6bb3d83cf635ab329574d36a2517">getOModValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="#a28b7d1f6255a7a32f8a5b0ebfa1debca">MFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sioutmods/#a21f5743aa1ed4b0e3c7bb800c55509c2a6331f8be2ffd9ba4cb0d472c87e3848b">llvm::SIOutMods::MUL2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sioutmods/#a21f5743aa1ed4b0e3c7bb800c55509c2a5d23498485b506b1e1d273dc41bcb517">llvm::SIOutMods::NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893a40bc80ae1d362a1461703637e946cbd8">llvm::DenormalMode::PreserveSign</a> and <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>.</p>


<p>Referenced by <a href="#a5e1eb00d7eee7258726795f01822d491">tryFoldOMod</a>.</p>

</div>
</div>

### isUseSafeToFold() {#a51dc84de00cc6a5bf725b831737c8296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::isUseSafeToFold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; UseMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>.</p>


<p>Referenced by <a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a>.</p>

</div>
</div>

### run() {#a091988829e1f57d6a9710575591f4845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::run (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518adc42a7d40f8bd9c7f1a9c2beb0135fdc">llvm::MachineInstr::FmNsz</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a28b7d1f6255a7a32f8a5b0ebfa1debca">MFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="#a7a1e046b8ad8a2f498a2c1fadbbe1edc">ST</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>, <a href="#a6917282da348ebaf7919a7c0e66b1c93">TRI</a>, <a href="#a08bf0b055eab1a86300c18c2b0f9fc7e">tryFoldClamp</a>, <a href="#a2929348b6b6f3ad543717d42b201640d">tryFoldCndMask</a>, <a href="#ac9ca747a6b6297f53d182bfe78514963">tryFoldFoldableCopy</a>, <a href="#aac5e465289c9bc7adb88b6b682fdf85b">tryFoldLoad</a>, <a href="#a5e1eb00d7eee7258726795f01822d491">tryFoldOMod</a>, <a href="#a17772fd1beeccd740ec6412abad098f9">tryFoldPhiAGPR</a>, <a href="#a553d8629e18f8acb82dbadd0a160b877">tryFoldRegSequence</a>, <a href="#acab876eafd3f522831a5d002faecc72b">tryFoldZeroHighBits</a> and <a href="#a8562a883d9494266aca5d1b2f8b5dc5e">tryOptimizeAGPRPhis</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandslegacy/#a6cbe7b0ff44391a912974e451dfec364">anonymous{SIFoldOperands.cpp}::SIFoldOperandsLegacy::runOnMachineFunction</a> and <a href="#a4831aecc1c400c0f6fc9be32b378523a">SIFoldOperandsImpl</a>.</p>

</div>
</div>

### tryAddToFoldList() {#a1f87ab4ea0d4b9807d9a5318edcb205b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::tryAddToFoldList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate">FoldCandidate</a> &gt; &amp; FoldList, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * OpToFold)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#ae7219027f4e8fe1dea7fcce6cf4b5002">appendFoldCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa577b8bdb7ed00babf58c076a4978f38">canUseImmWithOpSel</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a7b39ecfd6793534206dbb095b0d464c7">llvm::MachineOperand::ChangeToImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9404d5d9e4be534bb544777aae216691">llvm::MachineOperand::ChangeToRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae73e2be2b66dc9e4f2f90d56076d7ea9">llvm::TargetInstrInfo::CommuteAnyOperandIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0ca904e64ee29c8812ed34e632d3c947">llvm::MCInstrDesc::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a17fda9e2f2cb60c24bfdec02d7793b86">llvm::AMDGPU::getVOPe32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#aa137c30663832a1bffc5ef7eda4d60da">isUseMIInFoldList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a15912d7957912bd92c8c86626c1e3a12">macToMad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0f4e09a761d45bf0914f26d4c149ddeb">llvm::MCInstrDesc::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a> and <a href="#a1f87ab4ea0d4b9807d9a5318edcb205b">tryAddToFoldList</a>.</p>


<p>Referenced by <a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a> and <a href="#a1f87ab4ea0d4b9807d9a5318edcb205b">tryAddToFoldList</a>.</p>

</div>
</div>

### tryConstantFoldOp() {#a1124ea4e69342296db6a2b6628121436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::tryConstantFoldOp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a8dafe155e3977305d2afe9d5086b9c32">evalBinaryInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#acdc089f7e9f2dddcf2412615f90690a9">getImmOrMaterializedImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#aa1b0727e99dbdac255080448f1a4fba2">getMovOpc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#aaeadcc450219215781c8481960357aef">mutateCopyOp</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a> and <a href="#a6917282da348ebaf7919a7c0e66b1c93">TRI</a>.</p>


<p>Referenced by <a href="#a727184c28151d2b605686087351b8d7b">foldInstOperand</a>.</p>

</div>
</div>

### tryFoldClamp() {#a08bf0b055eab1a86300c18c2b0f9fc7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::tryFoldClamp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a6fbf0d819e9a71ced3199693268238ce">isClamp</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a> and <a href="#a6917282da348ebaf7919a7c0e66b1c93">TRI</a>.</p>


<p>Referenced by <a href="#a091988829e1f57d6a9710575591f4845">run</a>.</p>

</div>
</div>

### tryFoldCndMask() {#a2929348b6b6f3ad543717d42b201640d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::tryFoldCndMask (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#acdc089f7e9f2dddcf2412615f90690a9">getImmOrMaterializedImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#aa1b0727e99dbdac255080448f1a4fba2">getMovOpc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7f2dc64214551418f486026ffc95fa4">llvm::MachineOperand::isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#aaeadcc450219215781c8481960357aef">mutateCopyOp</a> and <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>.</p>


<p>Referenced by <a href="#a091988829e1f57d6a9710575591f4845">run</a>.</p>

</div>
</div>

### tryFoldFoldableCopy() {#ac9ca747a6b6297f53d182bfe78514963}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::tryFoldFoldableCopy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *&amp; CurrentKnownM0Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="#a64c6eca16f58ce5cef19b84d78d3adb7">foldCopyToVGPROfScalarAddOfFrameIndex</a>, <a href="#a727184c28151d2b605686087351b8d7b">foldInstOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#ae229785d0c8a8ce25d34be18fe150a54">llvm::SrcOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7f2dc64214551418f486026ffc95fa4">llvm::MachineOperand::isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a> and <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>.</p>


<p>Referenced by <a href="#a091988829e1f57d6a9710575591f4845">run</a>.</p>

</div>
</div>

### tryFoldImmWithOpSel() {#a35b932e3e318fc132ddc4eba034d9a12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::tryFoldImmWithOpSel (<a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate">FoldCandidate</a> &amp; Fold)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a7b39ecfd6793534206dbb095b0d464c7">llvm::MachineOperand::ChangeToImmediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a2b28be2794e9b45d6a00a7ad0cb0c88e">anonymous{SIFoldOperands.cpp}::FoldCandidate::ImmToFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0a9b91eee2733c432bd30c44907efae6">llvm::AMDGPU::isInlinableLiteralV216</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a3b095994a942145ccaaed4f175c7172a">llvm::SISrcMods::OP_SEL_0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442af0e8126187c47c5b74a1bdc635158144">llvm::SISrcMods::OP_SEL_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a455e964e5660b09e16a498dd96cf0bd6">llvm::AMDGPU::OPERAND_REG_IMM_V2INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9dfb8a7518a9154161c7a05b644e6e47">llvm::AMDGPU::OPERAND_REG_INLINE_AC_V2INT16</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#aa00fe1221e478602346344c7315f057a">anonymous{SIFoldOperands.cpp}::FoldCandidate::UseMI</a> and <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a67061b2f666f6aaacf5bf3dd623dc30e">anonymous{SIFoldOperands.cpp}::FoldCandidate::UseOpNo</a>.</p>


<p>Referenced by <a href="#a0c7d1732461b6f0d88e719eebadf9f2a">updateOperand</a>.</p>

</div>
</div>

### tryFoldLoad() {#aac5e465289c9bc7adb88b6b682fdf85b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::tryFoldLoad (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a7a1e046b8ad8a2f498a2c1fadbbe1edc">ST</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>, <a href="#a6917282da348ebaf7919a7c0e66b1c93">TRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#a4e5b9edb51eec9dbca592075eb64dfcb">Users</a>.</p>


<p>Referenced by <a href="#a091988829e1f57d6a9710575591f4845">run</a>.</p>

</div>
</div>

### tryFoldOMod() {#a5e1eb00d7eee7258726795f01822d491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::tryFoldOMod (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="#a7e62a05741edcd4375c97fd4906b419d">isOMod</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sioutmods/#a21f5743aa1ed4b0e3c7bb800c55509c2a5d23498485b506b1e1d273dc41bcb517">llvm::SIOutMods::NONE</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a> and <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>.</p>


<p>Referenced by <a href="#a091988829e1f57d6a9710575591f4845">run</a>.</p>

</div>
</div>

### tryFoldPhiAGPR() {#a17772fd1beeccd740ec6412abad098f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::tryFoldPhiAGPR (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a7f0521fa2de44271fd4b909ea7351ef3">llvm::MachineBasicBlock::getFirstTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0c893675dfd5d1b1e4aea1e8211217c7">llvm::MachineOperand::getOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a8ea8ce186fc4a70ad542e74d015d84ed">llvm::TargetRegisterClass::hasSubClassEq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a58db20676cb0ff354eca34b86f0c3ab1">isAGPRCopy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a001d31fcea92be51d2999826b806606f">llvm::MachineOperand::setSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5d8a45757c9861d499cba1a0d54e2c1e">llvm::MachineBasicBlock::SkipPHIsLabelsAndDebug</a>, <a href="#a7a1e046b8ad8a2f498a2c1fadbbe1edc">ST</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a> and <a href="#a6917282da348ebaf7919a7c0e66b1c93">TRI</a>.</p>


<p>Referenced by <a href="#a091988829e1f57d6a9710575591f4845">run</a>.</p>

</div>
</div>

### tryFoldRegSequence() {#a553d8629e18f8acb82dbadd0a160b877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::tryFoldRegSequence (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a3cb505493f51b96cbb394d89b93f686e">getRegSeqInit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1912d4fbc40c61a12b1f770ad54dfd74">llvm::MachineInstr::isCopy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da62a6ddcdddcce55f836b1720d29f90dc">llvm::MCOI::OPERAND_REGISTER</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a>, <a href="#a7a1e046b8ad8a2f498a2c1fadbbe1edc">ST</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>, <a href="#a6917282da348ebaf7919a7c0e66b1c93">TRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="#a091988829e1f57d6a9710575591f4845">run</a>.</p>

</div>
</div>

### tryFoldZeroHighBits() {#acab876eafd3f522831a5d002faecc72b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::tryFoldZeroHighBits (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#acdc089f7e9f2dddcf2412615f90690a9">getImmOrMaterializedImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a> and <a href="#a7a1e046b8ad8a2f498a2c1fadbbe1edc">ST</a>.</p>


<p>Referenced by <a href="#a091988829e1f57d6a9710575591f4845">run</a>.</p>

</div>
</div>

### tryOptimizeAGPRPhis() {#a8562a883d9494266aca5d1b2f8b5dc5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::tryOptimizeAGPRPhis (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a7fcb99675ac619b90ab5d7c2eec0a482">getRegOpRC</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="#a7a1e046b8ad8a2f498a2c1fadbbe1edc">ST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a> and <a href="#a6917282da348ebaf7919a7c0e66b1c93">TRI</a>.</p>


<p>Referenced by <a href="#a091988829e1f57d6a9710575591f4845">run</a>.</p>

</div>
</div>

### tryToFoldACImm() {#acd13e2195957a8e92e36d055dde1ffb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::tryToFoldACImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; OpToFold, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * UseMI, unsigned UseOpIdx, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate">FoldCandidate</a> &gt; &amp; FoldList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#ae7219027f4e8fe1dea7fcce6cf4b5002">appendFoldCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a3cb505493f51b96cbb394d89b93f686e">getRegSeqInit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a1f8110d15ce3aad630ec2e52906226da">llvm::AMDGPU::isSISrcInlinableOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#aa137c30663832a1bffc5ef7eda4d60da">isUseMIInFoldList</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a02230ca194a9c8e52170cc7c426decb2">UseReg</a>.</p>


<p>Referenced by <a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a>.</p>

</div>
</div>

### updateOperand() {#a0c7d1732461b6f0d88e719eebadf9f2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFoldOperandsImpl::updateOperand (<a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate">FoldCandidate</a> &amp; Fold)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#aa577b8bdb7ed00babf58c076a4978f38">canUseImmWithOpSel</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a13b9c3d91aaffb22e0119f3467694b69">llvm::MachineOperand::ChangeToFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a83e996ed26eacbf3033314b3df58b133">llvm::MachineOperand::ChangeToGA</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a7b39ecfd6793534206dbb095b0d464c7">llvm::MachineOperand::ChangeToImmediate</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#ae0e241dda1a24eec0758f002f18a2a64">anonymous{SIFoldOperands.cpp}::FoldCandidate::Commuted</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#ae8eb1c3cccb529d65e835b33ea211156">anonymous{SIFoldOperands.cpp}::FoldCandidate::FrameIndexToFold</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5ff7467be99b93194854ce84b534f711">llvm::AMDGPU::getMFMAEarlyClobberOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab06dda088d3c7686f7dfcdb2b96323f5">llvm::MachineOperand::getTargetFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a2b28be2794e9b45d6a00a7ad0cb0c88e">anonymous{SIFoldOperands.cpp}::FoldCandidate::ImmToFold</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a4a93c1350ec8105e4be9ddaef180219c">anonymous{SIFoldOperands.cpp}::FoldCandidate::isFI</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a61248338d72ef691a8f1767a534f178f">anonymous{SIFoldOperands.cpp}::FoldCandidate::isGlobal</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a2e26fd696a0dc5122dea22f2858c40a0">anonymous{SIFoldOperands.cpp}::FoldCandidate::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a894030fbf6d0f6c70991f05fff650930">llvm::MachineOperand::isTied</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#af0288e181965a5ff9f0c7a75201fd142a092531ae27becd74d96d4a6fae76f863">llvm::MachineBasicBlock::LQR_Dead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac84cecb52ca09605285ef50620fdeb02">MRI</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a36eb7bfba2e00c3e8479dc191550b221">anonymous{SIFoldOperands.cpp}::FoldCandidate::needsShrink</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a122bc2c616a7f06545a745a2497735b2">anonymous{SIFoldOperands.cpp}::FoldCandidate::OpToFold</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab979122f21b7fa46d3d2d9b21983068b">llvm::MachineOperand::setIsUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#ae3e6a6882558cf755031282724b76bae">anonymous{SIFoldOperands.cpp}::FoldCandidate::ShrinkOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a13a5b2fd837189405f1b07a6c9249d4f">llvm::MachineOperand::substVirtReg</a>, <a href="#a6dca007c3b5ac306a3eb1fbb685ce397">TII</a>, <a href="#a6917282da348ebaf7919a7c0e66b1c93">TRI</a>, <a href="#a35b932e3e318fc132ddc4eba034d9a12">tryFoldImmWithOpSel</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#aa00fe1221e478602346344c7315f057a">anonymous{SIFoldOperands.cpp}::FoldCandidate::UseMI</a> and <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a67061b2f666f6aaacf5bf3dd623dc30e">anonymous{SIFoldOperands.cpp}::FoldCandidate::UseOpNo</a>.</p>


<p>Referenced by <a href="#a727184c28151d2b605686087351b8d7b">foldInstOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MFI {#a28b7d1f6255a7a32f8a5b0ebfa1debca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIMachineFunctionInfo* anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::MFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Referenced by <a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a>, <a href="#a7e62a05741edcd4375c97fd4906b419d">isOMod</a> and <a href="#a091988829e1f57d6a9710575591f4845">run</a>.</p>

</div>
</div>

### MRI {#ac84cecb52ca09605285ef50620fdeb02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Referenced by <a href="#a64c6eca16f58ce5cef19b84d78d3adb7">foldCopyToVGPROfScalarAddOfFrameIndex</a>, <a href="#a727184c28151d2b605686087351b8d7b">foldInstOperand</a>, <a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a>, <a href="#a66eb61143b269793cb50e67646375778">frameIndexMayFold</a>, <a href="#acdc089f7e9f2dddcf2412615f90690a9">getImmOrMaterializedImm</a>, <a href="#a3cb505493f51b96cbb394d89b93f686e">getRegSeqInit</a>, <a href="#a091988829e1f57d6a9710575591f4845">run</a>, <a href="#a1f87ab4ea0d4b9807d9a5318edcb205b">tryAddToFoldList</a>, <a href="#a1124ea4e69342296db6a2b6628121436">tryConstantFoldOp</a>, <a href="#a08bf0b055eab1a86300c18c2b0f9fc7e">tryFoldClamp</a>, <a href="#ac9ca747a6b6297f53d182bfe78514963">tryFoldFoldableCopy</a>, <a href="#aac5e465289c9bc7adb88b6b682fdf85b">tryFoldLoad</a>, <a href="#a5e1eb00d7eee7258726795f01822d491">tryFoldOMod</a>, <a href="#a17772fd1beeccd740ec6412abad098f9">tryFoldPhiAGPR</a>, <a href="#a553d8629e18f8acb82dbadd0a160b877">tryFoldRegSequence</a>, <a href="#acab876eafd3f522831a5d002faecc72b">tryFoldZeroHighBits</a>, <a href="#a8562a883d9494266aca5d1b2f8b5dc5e">tryOptimizeAGPRPhis</a>, <a href="#acd13e2195957a8e92e36d055dde1ffb8">tryToFoldACImm</a> and <a href="#a0c7d1732461b6f0d88e719eebadf9f2a">updateOperand</a>.</p>

</div>
</div>

### ST {#a7a1e046b8ad8a2f498a2c1fadbbe1edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget* anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Referenced by <a href="#aa577b8bdb7ed00babf58c076a4978f38">canUseImmWithOpSel</a>, <a href="#a475c646660977940514023300390c93a">convertToVALUOp</a>, <a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a>, <a href="#a091988829e1f57d6a9710575591f4845">run</a>, <a href="#aac5e465289c9bc7adb88b6b682fdf85b">tryFoldLoad</a>, <a href="#a17772fd1beeccd740ec6412abad098f9">tryFoldPhiAGPR</a>, <a href="#a553d8629e18f8acb82dbadd0a160b877">tryFoldRegSequence</a>, <a href="#acab876eafd3f522831a5d002faecc72b">tryFoldZeroHighBits</a> and <a href="#a8562a883d9494266aca5d1b2f8b5dc5e">tryOptimizeAGPRPhis</a>.</p>

</div>
</div>

### TII {#a6dca007c3b5ac306a3eb1fbb685ce397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo* anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Referenced by <a href="#aa577b8bdb7ed00babf58c076a4978f38">canUseImmWithOpSel</a>, <a href="#a64c6eca16f58ce5cef19b84d78d3adb7">foldCopyToVGPROfScalarAddOfFrameIndex</a>, <a href="#a727184c28151d2b605686087351b8d7b">foldInstOperand</a>, <a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a>, <a href="#a66eb61143b269793cb50e67646375778">frameIndexMayFold</a>, <a href="#a3cb505493f51b96cbb394d89b93f686e">getRegSeqInit</a>, <a href="#a6fbf0d819e9a71ced3199693268238ce">isClamp</a>, <a href="#a7e62a05741edcd4375c97fd4906b419d">isOMod</a>, <a href="#a51dc84de00cc6a5bf725b831737c8296">isUseSafeToFold</a>, <a href="#a091988829e1f57d6a9710575591f4845">run</a>, <a href="#a1f87ab4ea0d4b9807d9a5318edcb205b">tryAddToFoldList</a>, <a href="#a1124ea4e69342296db6a2b6628121436">tryConstantFoldOp</a>, <a href="#a08bf0b055eab1a86300c18c2b0f9fc7e">tryFoldClamp</a>, <a href="#a2929348b6b6f3ad543717d42b201640d">tryFoldCndMask</a>, <a href="#ac9ca747a6b6297f53d182bfe78514963">tryFoldFoldableCopy</a>, <a href="#a35b932e3e318fc132ddc4eba034d9a12">tryFoldImmWithOpSel</a>, <a href="#aac5e465289c9bc7adb88b6b682fdf85b">tryFoldLoad</a>, <a href="#a5e1eb00d7eee7258726795f01822d491">tryFoldOMod</a>, <a href="#a17772fd1beeccd740ec6412abad098f9">tryFoldPhiAGPR</a>, <a href="#a553d8629e18f8acb82dbadd0a160b877">tryFoldRegSequence</a>, <a href="#a8562a883d9494266aca5d1b2f8b5dc5e">tryOptimizeAGPRPhis</a>, <a href="#acd13e2195957a8e92e36d055dde1ffb8">tryToFoldACImm</a> and <a href="#a0c7d1732461b6f0d88e719eebadf9f2a">updateOperand</a>.</p>

</div>
</div>

### TRI {#a6917282da348ebaf7919a7c0e66b1c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIRegisterInfo* anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Referenced by <a href="#a64c6eca16f58ce5cef19b84d78d3adb7">foldCopyToVGPROfScalarAddOfFrameIndex</a>, <a href="#a727184c28151d2b605686087351b8d7b">foldInstOperand</a>, <a href="#a96e06941b1694e3eb5cfd4efb2d69b59">foldOperand</a>, <a href="#a091988829e1f57d6a9710575591f4845">run</a>, <a href="#a1124ea4e69342296db6a2b6628121436">tryConstantFoldOp</a>, <a href="#a08bf0b055eab1a86300c18c2b0f9fc7e">tryFoldClamp</a>, <a href="#aac5e465289c9bc7adb88b6b682fdf85b">tryFoldLoad</a>, <a href="#a17772fd1beeccd740ec6412abad098f9">tryFoldPhiAGPR</a>, <a href="#a553d8629e18f8acb82dbadd0a160b877">tryFoldRegSequence</a>, <a href="#a8562a883d9494266aca5d1b2f8b5dc5e">tryOptimizeAGPRPhis</a> and <a href="#a0c7d1732461b6f0d88e719eebadf9f2a">updateOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
