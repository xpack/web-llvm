---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-sifoldoperands-cpp-/foldcandidate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FoldCandidate` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{SIFoldOperands.cpp}::FoldCandidate { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22926b4547ee17e802fe12e69ca53915">FoldCandidate</a> (MachineInstr *MI, unsigned OpNo, MachineOperand *FoldOp, bool Commuted_=false, int ShrinkOp=-1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a93c1350ec8105e4be9ddaef180219c">isFI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e26fd696a0dc5122dea22f2858c40a0">isImm</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f71b49a6fc4c1fdd109a281b0831c5a">isReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61248338d72ef691a8f1767a534f178f">isGlobal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36eb7bfba2e00c3e8479dc191550b221">needsShrink</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa00fe1221e478602346344c7315f057a">UseMI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a122bc2c616a7f06545a745a2497735b2">OpToFold</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b28be2794e9b45d6a00a7ad0cb0c88e">ImmToFold</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8eb1c3cccb529d65e835b33ea211156">FrameIndexToFold</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{SIFoldOperands.cpp}<a href="#a22926b4547ee17e802fe12e69ca53915">::FoldCandidate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74030e0142779de51cf9872860c08310"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3e6a6882558cf755031282724b76bae">ShrinkOpcode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67061b2f666f6aaacf5bf3dd623dc30e">UseOpNo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639b">MachineOperand::MachineOperandType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16993322cfd11681e666d5d66fe07681">Kind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0e241dda1a24eec0758f002f18a2a64">Commuted</a></td>
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


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FoldCandidate() {#a22926b4547ee17e802fe12e69ca53915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIFoldOperands.cpp}::FoldCandidate::FoldCandidate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * FoldOp, bool Commuted_=false, int ShrinkOp=-1)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="#ae0e241dda1a24eec0758f002f18a2a64">Commuted</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7213433bd60dc33020246384dc18b9b">llvm::MachineOperand::isFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="#a16993322cfd11681e666d5d66fe07681">Kind</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a122bc2c616a7f06545a745a2497735b2">OpToFold</a>, <a href="#ae3e6a6882558cf755031282724b76bae">ShrinkOpcode</a>, <a href="#aa00fe1221e478602346344c7315f057a">UseMI</a> and <a href="#a67061b2f666f6aaacf5bf3dd623dc30e">UseOpNo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#ae7219027f4e8fe1dea7fcce6cf4b5002">appendFoldCandidate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isFI() {#a4a93c1350ec8105e4be9ddaef180219c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIFoldOperands.cpp}::FoldCandidate::isFI ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="#a16993322cfd11681e666d5d66fe07681">Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba97561985119c4a774e3ec6439240fa80">llvm::MachineOperand::MO_FrameIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### isGlobal() {#a61248338d72ef691a8f1767a534f178f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIFoldOperands.cpp}::FoldCandidate::isGlobal ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="#a16993322cfd11681e666d5d66fe07681">Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">llvm::MachineOperand::MO_GlobalAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### isImm() {#a2e26fd696a0dc5122dea22f2858c40a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIFoldOperands.cpp}::FoldCandidate::isImm ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="#a16993322cfd11681e666d5d66fe07681">Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">llvm::MachineOperand::MO_Immediate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#aa577b8bdb7ed00babf58c076a4978f38">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::canUseImmWithOpSel</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### isReg() {#a1f71b49a6fc4c1fdd109a281b0831c5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIFoldOperands.cpp}::FoldCandidate::isReg ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>References <a href="#a16993322cfd11681e666d5d66fe07681">Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">llvm::MachineOperand::MO_Register</a>.</p>

</div>
</div>

### needsShrink() {#a36eb7bfba2e00c3e8479dc191550b221}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIFoldOperands.cpp}::FoldCandidate::needsShrink ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Reference <a href="#ae3e6a6882558cf755031282724b76bae">ShrinkOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#a74030e0142779de51cf9872860c08310}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{SIFoldOperands.cpp}::FoldCandidate anonymous{SIFoldOperands.cpp}::FoldCandidate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>

</div>
</div>

### Commuted {#ae0e241dda1a24eec0758f002f18a2a64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIFoldOperands.cpp}::FoldCandidate::Commuted</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Referenced by <a href="#a22926b4547ee17e802fe12e69ca53915">FoldCandidate</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### FrameIndexToFold {#ae8eb1c3cccb529d65e835b33ea211156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{SIFoldOperands.cpp}::FoldCandidate::FrameIndexToFold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### ImmToFold {#a2b28be2794e9b45d6a00a7ad0cb0c88e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SIFoldOperands.cpp}::FoldCandidate::ImmToFold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a35b932e3e318fc132ddc4eba034d9a12">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldImmWithOpSel</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### Kind {#a16993322cfd11681e666d5d66fe07681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand::MachineOperandType anonymous{SIFoldOperands.cpp}::FoldCandidate::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Referenced by <a href="#a22926b4547ee17e802fe12e69ca53915">FoldCandidate</a>, <a href="#a4a93c1350ec8105e4be9ddaef180219c">isFI</a>, <a href="#a61248338d72ef691a8f1767a534f178f">isGlobal</a>, <a href="#a2e26fd696a0dc5122dea22f2858c40a0">isImm</a> and <a href="#a1f71b49a6fc4c1fdd109a281b0831c5a">isReg</a>.</p>

</div>
</div>

### OpToFold {#a122bc2c616a7f06545a745a2497735b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand* anonymous{SIFoldOperands.cpp}::FoldCandidate::OpToFold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Referenced by <a href="#a22926b4547ee17e802fe12e69ca53915">FoldCandidate</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### ShrinkOpcode {#ae3e6a6882558cf755031282724b76bae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{SIFoldOperands.cpp}::FoldCandidate::ShrinkOpcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Referenced by <a href="#a22926b4547ee17e802fe12e69ca53915">FoldCandidate</a>, <a href="#a36eb7bfba2e00c3e8479dc191550b221">needsShrink</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### UseMI {#aa00fe1221e478602346344c7315f057a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* anonymous{SIFoldOperands.cpp}::FoldCandidate::UseMI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#aa577b8bdb7ed00babf58c076a4978f38">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::canUseImmWithOpSel</a>, <a href="#a22926b4547ee17e802fe12e69ca53915">FoldCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a35b932e3e318fc132ddc4eba034d9a12">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldImmWithOpSel</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### UseOpNo {#a67061b2f666f6aaacf5bf3dd623dc30e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIFoldOperands.cpp}::FoldCandidate::UseOpNo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#aa577b8bdb7ed00babf58c076a4978f38">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::canUseImmWithOpSel</a>, <a href="#a22926b4547ee17e802fe12e69ca53915">FoldCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a35b932e3e318fc132ddc4eba034d9a12">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldImmWithOpSel</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp">SIFoldOperands.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
