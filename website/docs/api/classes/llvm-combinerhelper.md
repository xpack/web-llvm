---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/combinerhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CombinerHelper` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::CombinerHelper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">llvm/CodeGen/GlobalISel/CombinerHelper.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper">AMDGPUCombinerHelper</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SelectPatternNaNBehaviour { <a href="#ad576ffcb68795d9fc4c9e9bf88c27744">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Behavior when a floating point min/max is given one NaN and one non-NaN as input. <a href="#ad576ffcb68795d9fc4c9e9bf88c27744">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab45ce737b2839bf39a18e22fbb502ca9">CombinerHelper</a> (GISelChangeObserver &amp;Observer, MachineIRBuilder &amp;B, bool IsPreLegalize, GISelKnownBits *KB=nullptr, MachineDominatorTree *MDT=nullptr, const LegalizerInfo *LI=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea850556148cb48cb6be849cd354e1c">getKnownBits</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf32918c9574aee808e6234d1a2eace9">getBuilder</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5d327beb13472a44f1999b5dfa79503">getMachineFunction</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d32dd5a2442e61e0904577f0d8369ce">getDataLayout</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c7d20188ce1e7c821f21c6a76f09df0">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dd411f52d902c7964a59b0f317d3797">isPreLegalize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9569ff6b4f769cb7a667ad4a986589e8">isLegal</a> (const LegalityQuery &amp;Query) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a> (const LegalityQuery &amp;Query) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d34744985da7b7a26c92f1b064851ea">isConstantLegalOrBeforeLegalizer</a> (const LLT Ty) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a> (MachineRegisterInfo &amp;MRI, Register FromReg, Register ToReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#af16c39ee36e4633f821b6820f8bd52ef">MachineRegisterInfo::replaceRegWith()</a> and inform the observer of the changes. <a href="#a28ea263eb2492e410f764fc705781c05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a290f07593ec0820655db5efe88422c44">replaceRegOpWith</a> (MachineRegisterInfo &amp;MRI, MachineOperand &amp;FromRegOp, Register ToReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace a single register operand with a new register and inform the observer of the changes. <a href="#a290f07593ec0820655db5efe88422c44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6711738d18f70c1843eac7255405df54">replaceOpcodeWith</a> (MachineInstr &amp;FromMI, unsigned ToOpcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the opcode in instruction with a new opcode and inform the observer of the changes. <a href="#a6711738d18f70c1843eac7255405df54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ae177a2136d1b90b767d57dbe6a419c">getRegBank</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the register bank of <span class="doxyComputerOutput">Reg</span>. <a href="#a0ae177a2136d1b90b767d57dbe6a419c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abefb646c754368c3ecc32c050c5bacd5">setRegBank</a> (Register Reg, const RegisterBank *RegBank) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the register bank of <span class="doxyComputerOutput">Reg</span>. <a href="#abefb646c754368c3ecc32c050c5bacd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77695e2fac4d7c37fd43e1d9a55e69ce">tryCombineCopy</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">MI</span> is COPY, try to combine it. <a href="#a77695e2fac4d7c37fd43e1d9a55e69ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc01df6a11c709c2e05f5ef212d239d">matchCombineCopy</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eeb3124ce1fe172f0e79b5f42be7f5c">applyCombineCopy</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a9969db0d864227c6955d383a7bbe45">isPredecessor</a> (const MachineInstr &amp;DefMI, const MachineInstr &amp;UseMI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">DefMI</span> precedes <span class="doxyComputerOutput">UseMI</span> or they are the same instruction. <a href="#a3a9969db0d864227c6955d383a7bbe45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad99c8ee849f72738dd718fec8d3a1d42">dominates</a> (const MachineInstr &amp;DefMI, const MachineInstr &amp;UseMI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">DefMI</span> dominates <span class="doxyComputerOutput">UseMI</span>. <a href="#ad99c8ee849f72738dd718fec8d3a1d42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa57157299174e74145361548452e45f9">tryCombineExtendingLoads</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">MI</span> is extend that consumes the result of a load, try to combine it. <a href="#aa57157299174e74145361548452e45f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5ece2e19fefdc8f1112b05d6274e649">matchCombineExtendingLoads</a> (MachineInstr &amp;MI, PreferredTuple &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00301689820a26a9f3b438f6dece6ef0">applyCombineExtendingLoads</a> (MachineInstr &amp;MI, PreferredTuple &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d600f23e7d301bfcf60b292eaba31ef">matchCombineLoadWithAndMask</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match (and (load x), mask) -&gt; zextload x. <a href="#a5d600f23e7d301bfcf60b292eaba31ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a0f1422b780a83a9632e5d46993dfc">matchCombineExtractedVectorLoad</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine a G_EXTRACT_VECTOR_ELT of a load into a narrowed load. <a href="#a28a0f1422b780a83a9632e5d46993dfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2591ea6476cd4c80dd7f0fc9be1d3d74">matchCombineIndexedLoadStore</a> (MachineInstr &amp;MI, IndexedLoadStoreMatchInfo &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72848dca494afcf56b2bc2bea4322dc1">applyCombineIndexedLoadStore</a> (MachineInstr &amp;MI, IndexedLoadStoreMatchInfo &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56afecdec991e6c14189691c37140ad1">matchSextTruncSextLoad</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2de464ca370d0adf592feedb983fce3">applySextTruncSextLoad</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f5dd5583d12f1c7dcf63b86ff444394">matchSextInRegOfLoad</a> (MachineInstr &amp;MI, std::tuple&lt; Register, unsigned &gt; &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match sext_inreg(load p), imm -&gt; sextload p. <a href="#a8f5dd5583d12f1c7dcf63b86ff444394">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75ae99f242b3954f52d12c85e53d5f41">applySextInRegOfLoad</a> (MachineInstr &amp;MI, std::tuple&lt; Register, unsigned &gt; &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea6814df78ae99e8a540fb4e8fc4ed1">matchCombineDivRem</a> (MachineInstr &amp;MI, MachineInstr *&amp;OtherMI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to combine G_[SU]DIV and G_[SU]REM into a single G_[SU]DIVREM when their source operands are identical. <a href="#a2ea6814df78ae99e8a540fb4e8fc4ed1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2377979438dcdab9e664ccd5f975dac">applyCombineDivRem</a> (MachineInstr &amp;MI, MachineInstr *&amp;OtherMI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab40d01e80ca225a11dcdb8adbf4e843a">matchOptBrCondByInvertingCond</a> (MachineInstr &amp;MI, MachineInstr *&amp;BrCond) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a brcond's true block is not the fallthrough, make it so by inverting the condition and swapping operands. <a href="#ab40d01e80ca225a11dcdb8adbf4e843a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa907eb6ba127a5f4167f5a1671efed0">applyOptBrCondByInvertingCond</a> (MachineInstr &amp;MI, MachineInstr *&amp;BrCond) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84bf6a20255406e9c9f6a52f5c4c7b34">matchCombineConcatVectors</a> (MachineInstr &amp;MI, SmallVector&lt; Register &gt; &amp;Ops) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">MI</span> is G_CONCAT_VECTORS, try to combine it. <a href="#a84bf6a20255406e9c9f6a52f5c4c7b34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c95f864b062fedecfd2c4fc32abf47e">applyCombineConcatVectors</a> (MachineInstr &amp;MI, SmallVector&lt; Register &gt; &amp;Ops) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace <span class="doxyComputerOutput">MI</span> with a flattened build_vector with <span class="doxyComputerOutput">Ops</span> or an implicit_def if <span class="doxyComputerOutput">Ops</span> is empty. <a href="#a1c95f864b062fedecfd2c4fc32abf47e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7474d0e2d570539a3e93b86c67b1bae9">matchCombineShuffleConcat</a> (MachineInstr &amp;MI, SmallVector&lt; Register &gt; &amp;Ops) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25bc0b47af5d0bcbb989180e1eb3f928">applyCombineShuffleConcat</a> (MachineInstr &amp;MI, SmallVector&lt; Register &gt; &amp;Ops) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace <span class="doxyComputerOutput">MI</span> with a flattened build_vector with <span class="doxyComputerOutput">Ops</span> or an implicit_def if <span class="doxyComputerOutput">Ops</span> is empty. <a href="#a25bc0b47af5d0bcbb989180e1eb3f928">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9de7f911f64078bdbf773007dc10997">tryCombineShuffleVector</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to combine G_SHUFFLE_VECTOR into G_CONCAT_VECTORS. <a href="#aa9de7f911f64078bdbf773007dc10997">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a620917cb45d142b76b1eb2dcd76ce689">matchCombineShuffleVector</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; Register &gt; &amp;Ops) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the G_SHUFFLE_VECTOR <span class="doxyComputerOutput">MI</span> can be replaced by a concat_vectors. <a href="#a620917cb45d142b76b1eb2dcd76ce689">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8b3f43a97b93dde8c791002d306f9">applyCombineShuffleVector</a> (MachineInstr &amp;MI, const ArrayRef&lt; Register &gt; Ops) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace <span class="doxyComputerOutput">MI</span> with a concat_vectors with <span class="doxyComputerOutput">Ops</span>. <a href="#a7ee8b3f43a97b93dde8c791002d306f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16130b5045fbc424c847795ec9bf17e5">matchShuffleToExtract</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae640b7329e9f881bfe0d4dc6bdddb642">applyShuffleToExtract</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1fd41e303fcb42122f8a0432efcd87d">tryCombineMemCpyFamily</a> (MachineInstr &amp;MI, unsigned MaxLen=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize memcpy intrinsics et al, e.g. <a href="#ae1fd41e303fcb42122f8a0432efcd87d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3acff99aeccfa086e7fbef44df8c0ce1">matchPtrAddImmedChain</a> (MachineInstr &amp;MI, PtrAddChain &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cd84da3b005d88c0f1b19d868e0a2b3">applyPtrAddImmedChain</a> (MachineInstr &amp;MI, PtrAddChain &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33c6405fe05b24b5d3f9c0ec0ed7f9ae">matchShiftImmedChain</a> (MachineInstr &amp;MI, RegisterImmPair &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fold (shift (shift base, x), y) -&gt; (shift base (x+y)) <a href="#a33c6405fe05b24b5d3f9c0ec0ed7f9ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6091fcf4f73ee6e61b585ff63df6b87d">applyShiftImmedChain</a> (MachineInstr &amp;MI, RegisterImmPair &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8434510d79fe87971bb903ab82cc1fc3">matchShiftOfShiftedLogic</a> (MachineInstr &amp;MI, ShiftOfShiftedLogic &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we have a shift-by-constant of a bitwise logic op that itself has a shift-by-constant operand with identical opcode, we may be able to convert that into 2 independent shifts followed by the logic op. <a href="#a8434510d79fe87971bb903ab82cc1fc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a483afeb99148394d2586c5601e441">applyShiftOfShiftedLogic</a> (MachineInstr &amp;MI, ShiftOfShiftedLogic &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0255cbf70d03b31784d719fb73637002">matchCommuteShift</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f6d05c3170477dae214b4f7ec6dc3fb">matchCombineMulToShl</a> (MachineInstr &amp;MI, unsigned &amp;ShiftVal) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform a multiply by a power-of-2 value to a left shift. <a href="#a6f6d05c3170477dae214b4f7ec6dc3fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaf0ebafd584479c2c6a1a782ff149f9">applyCombineMulToShl</a> (MachineInstr &amp;MI, unsigned &amp;ShiftVal) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82dc058091aed201fb1fbdd0ab8e5c3d">matchCombineSubToAdd</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50d554a59b9df6a88b36ed551c6e7903">matchCombineShlOfExtend</a> (MachineInstr &amp;MI, RegisterImmPair &amp;MatchData) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b8e5256d82c820e81d9c5b7fb3016ea">applyCombineShlOfExtend</a> (MachineInstr &amp;MI, const RegisterImmPair &amp;MatchData) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5709dda6e8778748a5159cb8ed2d37f6">matchCombineMergeUnmerge</a> (MachineInstr &amp;MI, Register &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fold away a merge of an unmerge of the corresponding values. <a href="#a5709dda6e8778748a5159cb8ed2d37f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb9e9ab4728e40478a30f57d57508f4e">matchCombineShiftToUnmerge</a> (MachineInstr &amp;MI, unsigned TargetShiftSize, unsigned &amp;ShiftVal) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reduce a shift by a constant to an unmerge and a shift on a half sized type. <a href="#adb9e9ab4728e40478a30f57d57508f4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae5d269529ade8f678f13c1dde831d1">applyCombineShiftToUnmerge</a> (MachineInstr &amp;MI, const unsigned &amp;ShiftVal) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f99a0f1d4b4f20f945a7cc8f7e1d65">tryCombineShiftToUnmerge</a> (MachineInstr &amp;MI, unsigned TargetShiftAmount) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc1c60085dd818c0586c87f44db3d10a">matchCombineUnmergeMergeToPlainValues</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; Register &gt; &amp;Operands) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform &lt;ty,...&gt; G_UNMERGE(G_MERGE ty X, Y, Z) -&gt; ty X, Y, Z. <a href="#afc1c60085dd818c0586c87f44db3d10a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcc62af19a5d1f2ea5f0e51b3e31893b">applyCombineUnmergeMergeToPlainValues</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; Register &gt; &amp;Operands) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad593882fdec13fdc1832fa224050666e">matchCombineUnmergeConstant</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; APInt &gt; &amp;Csts) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform G_UNMERGE <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> -&gt; Constant1, Constant2, ... <a href="#ad593882fdec13fdc1832fa224050666e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21bee05dda9718594fbfd89855272cd0">applyCombineUnmergeConstant</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; APInt &gt; &amp;Csts) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd7ed1e4ed0a6d0414dde08a4ef6935">matchCombineUnmergeUndef</a> (MachineInstr &amp;MI, std::function&lt; void(MachineIRBuilder &amp;)&gt; &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform G_UNMERGE G_IMPLICIT_DEF -&gt; G_IMPLICIT_DEF, G_IMPLICIT_DEF, ... <a href="#a6fd7ed1e4ed0a6d0414dde08a4ef6935">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7390ce20d98328a9fb3b2fe779e164">matchCombineUnmergeWithDeadLanesToTrunc</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform X, Y&lt;dead&gt; = G_UNMERGE Z -&gt; X = G_TRUNC Z. <a href="#abb7390ce20d98328a9fb3b2fe779e164">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a122b5e6289b7f7f787ea54fb607664b9">applyCombineUnmergeWithDeadLanesToTrunc</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19db4f1b27ef7d29e4c77f6f7dd0ec5d">matchCombineUnmergeZExtToZExt</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform X, Y = G_UNMERGE(G_ZEXT(Z)) -&gt; X = G_ZEXT(Z); Y = G_CONSTANT 0. <a href="#a19db4f1b27ef7d29e4c77f6f7dd0ec5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe9d6cb97689cb5efb1a5b8f9dc68ea0">applyCombineUnmergeZExtToZExt</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c5f97cf33a0913064c1ff1039b73c3">applyCombineConstantFoldFpUnary</a> (MachineInstr &amp;MI, const ConstantFP *Cst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform fp_instr(cst) to constant result of the fp operation. <a href="#a94c5f97cf33a0913064c1ff1039b73c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8269c100cbd38131124eb3c261193bfc">matchCombineI2PToP2I</a> (MachineInstr &amp;MI, Register &amp;Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform IntToPtr(PtrToInt(x)) to x if cast is in the same address space. <a href="#a8269c100cbd38131124eb3c261193bfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a346cb10c60061779896b022fb4f75a90">applyCombineI2PToP2I</a> (MachineInstr &amp;MI, Register &amp;Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0691f830cef4a0dadf0f0fbd41e7bca">applyCombineP2IToI2P</a> (MachineInstr &amp;MI, Register &amp;Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform PtrToInt(IntToPtr(x)) to x. <a href="#aa0691f830cef4a0dadf0f0fbd41e7bca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642669b9384277a3f5fc513928d6bee3">matchCombineAddP2IToPtrAdd</a> (MachineInstr &amp;MI, std::pair&lt; Register, bool &gt; &amp;PtrRegAndCommute) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform G_ADD (G_PTRTOINT x), y -&gt; G_PTRTOINT (G_PTR_ADD x, y) Transform G_ADD y, (G_PTRTOINT x) -&gt; G_PTRTOINT (G_PTR_ADD x, y) <a href="#a642669b9384277a3f5fc513928d6bee3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51abd9f22e4c8694c58d6719892bd27e">applyCombineAddP2IToPtrAdd</a> (MachineInstr &amp;MI, std::pair&lt; Register, bool &gt; &amp;PtrRegAndCommute) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd6113581071d7d586e82cf3454bc9a">matchCombineConstPtrAddToI2P</a> (MachineInstr &amp;MI, APInt &amp;NewCst) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6296facc7f8fdeb45406bf3b7ceac5e7">applyCombineConstPtrAddToI2P</a> (MachineInstr &amp;MI, APInt &amp;NewCst) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebbd8556be493cfb10fce51e933d7e2e">matchCombineAnyExtTrunc</a> (MachineInstr &amp;MI, Register &amp;Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform anyext(trunc(x)) to x. <a href="#aebbd8556be493cfb10fce51e933d7e2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade65624657027af925c73882186d00ed">matchCombineZextTrunc</a> (MachineInstr &amp;MI, Register &amp;Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform zext(trunc(x)) to x. <a href="#ade65624657027af925c73882186d00ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb530600a4235ed32fefcd44dbf454b4">matchCombineTruncOfShift</a> (MachineInstr &amp;MI, std::pair&lt; MachineInstr *, LLT &gt; &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform trunc (shl x, K) to shl (trunc x), K if K &lt; VT.getScalarSizeInBits(). <a href="#adb530600a4235ed32fefcd44dbf454b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac91aca84eade26acea192464a9cfcde8">applyCombineTruncOfShift</a> (MachineInstr &amp;MI, std::pair&lt; MachineInstr *, LLT &gt; &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8239ce43cefa777d1911c575cd961b9f">matchAnyExplicitUseIsUndef</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if any explicit use operand on <span class="doxyComputerOutput">MI</span> is defined by a G_IMPLICIT_DEF. <a href="#a8239ce43cefa777d1911c575cd961b9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36f9936f860062e89b32c9fdd84bfb08">matchAllExplicitUsesAreUndef</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all register explicit use operands on <span class="doxyComputerOutput">MI</span> are defined by a G_IMPLICIT_DEF. <a href="#a36f9936f860062e89b32c9fdd84bfb08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81b1ce0f10386f3b69d3b5f7c73b2d05">matchUndefShuffleVectorMask</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a G_SHUFFLE_VECTOR instruction <span class="doxyComputerOutput">MI</span> has an undef mask. <a href="#a81b1ce0f10386f3b69d3b5f7c73b2d05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ede1eaa682d8cb883fcbdfc3d894e70">matchUndefStore</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a G_STORE instruction <span class="doxyComputerOutput">MI</span> is storing an undef value. <a href="#a9ede1eaa682d8cb883fcbdfc3d894e70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac6f62bcef60abeb3f12a394f6e57ead">matchUndefSelectCmp</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a G_SELECT instruction <span class="doxyComputerOutput">MI</span> has an undef comparison. <a href="#aac6f62bcef60abeb3f12a394f6e57ead">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a881fab40a57c999ccf31ebc208f8d859">matchInsertExtractVecEltOutOfBounds</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a G_{EXTRACT,INSERT}_VECTOR_ELT has an out of range index. <a href="#a881fab40a57c999ccf31ebc208f8d859">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf78ec9a89c8134a3b9b6212184214fe">matchConstantSelectCmp</a> (MachineInstr &amp;MI, unsigned &amp;OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a G_SELECT instruction <span class="doxyComputerOutput">MI</span> has a constant comparison. <a href="#abf78ec9a89c8134a3b9b6212184214fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64af7868673efe2f150ab995a6c8c155">replaceInstWithFConstant</a> (MachineInstr &amp;MI, double C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace an instruction with a G_FCONSTANT with value <span class="doxyComputerOutput">C</span>. <a href="#a64af7868673efe2f150ab995a6c8c155">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a550ed89ae539e7dc552c77df4a05699e">replaceInstWithFConstant</a> (MachineInstr &amp;MI, ConstantFP *CFP) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace an instruction with an G_FCONSTANT with value <span class="doxyComputerOutput">CFP</span>. <a href="#a550ed89ae539e7dc552c77df4a05699e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad0b68c5dc4f76574c35800de2eee45">replaceInstWithConstant</a> (MachineInstr &amp;MI, int64_t C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace an instruction with a G_CONSTANT with value <span class="doxyComputerOutput">C</span>. <a href="#a4ad0b68c5dc4f76574c35800de2eee45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb1f75635e015ce0751b2053d061be9e">replaceInstWithConstant</a> (MachineInstr &amp;MI, APInt C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace an instruction with a G_CONSTANT with value <span class="doxyComputerOutput">C</span>. <a href="#acb1f75635e015ce0751b2053d061be9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca0b3013530db742551fd22ca8ff655">replaceInstWithUndef</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace an instruction with a G_IMPLICIT_DEF. <a href="#aaca0b3013530db742551fd22ca8ff655">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1ac0d7bbf4c5e4b5ed052554b54cf5c">replaceSingleDefInstWithOperand</a> (MachineInstr &amp;MI, unsigned OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete <span class="doxyComputerOutput">MI</span> and replace all of its uses with its <span class="doxyComputerOutput">OpIdx-th</span> operand. <a href="#af1ac0d7bbf4c5e4b5ed052554b54cf5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25ff4284ba96727747d6ceb7ef16b95d">replaceSingleDefInstWithReg</a> (MachineInstr &amp;MI, Register Replacement) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete <span class="doxyComputerOutput">MI</span> and replace all of its uses with <span class="doxyComputerOutput">Replacement</span>. <a href="#a25ff4284ba96727747d6ceb7ef16b95d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6766b5f9c46b6dd7bb3b45857ec23a0f">applyFunnelShiftConstantModulo</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replaces the shift amount in <span class="doxyComputerOutput">MI</span> with ShiftAmt % BW. <a href="#a6766b5f9c46b6dd7bb3b45857ec23a0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3bc0c5478dd84e0831b5d78a274b47">matchEqualDefs</a> (const MachineOperand &amp;MOP1, const MachineOperand &amp;MOP2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">MOP1</span> and <span class="doxyComputerOutput">MOP2</span> are register operands are defined by equivalent instructions. <a href="#a0f3bc0c5478dd84e0831b5d78a274b47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac975f07f5ebdceac6c93312485b74af2">matchConstantOp</a> (const MachineOperand &amp;MOP, int64_t C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">MOP</span> is defined by a G_CONSTANT or splat with a value equal to <span class="doxyComputerOutput">C</span>. <a href="#ac975f07f5ebdceac6c93312485b74af2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1cd7c807d2387bd9f8efe4a88cf1eb8">matchConstantFPOp</a> (const MachineOperand &amp;MOP, double C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">MOP</span> is defined by a G_FCONSTANT or splat with a value exactly equal to <span class="doxyComputerOutput">C</span>. <a href="#aa1cd7c807d2387bd9f8efe4a88cf1eb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cc9ea97355c96a953b9a6fc5ce2fcc2">matchConstantLargerBitWidth</a> (MachineInstr &amp;MI, unsigned ConstIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if constant at <span class="doxyComputerOutput">ConstIdx</span> is larger than <span class="doxyComputerOutput">MI</span> 's bitwidth. <a href="#a4cc9ea97355c96a953b9a6fc5ce2fcc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1561c4d75b24c0c46dcb05c8ec0bda65">matchSelectSameVal</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize (cond ? x : x) -&gt; x. <a href="#a1561c4d75b24c0c46dcb05c8ec0bda65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d378068adc2de015d79593557be7c37">matchBinOpSameVal</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize (x op x) -&gt; x. <a href="#a2d378068adc2de015d79593557be7c37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c4ed813faad031bd68547fc3b51244">matchOperandIsZero</a> (MachineInstr &amp;MI, unsigned OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if operand <span class="doxyComputerOutput">OpIdx</span> is zero. <a href="#a67c4ed813faad031bd68547fc3b51244">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf1110382dae21e5397a098cc5a08554">matchOperandIsUndef</a> (MachineInstr &amp;MI, unsigned OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if operand <span class="doxyComputerOutput">OpIdx</span> is undef. <a href="#adf1110382dae21e5397a098cc5a08554">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846bbee244f8b3e7ec21bc20f002ed9f">matchOperandIsKnownToBeAPowerOfTwo</a> (MachineInstr &amp;MI, unsigned OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if operand <span class="doxyComputerOutput">OpIdx</span> is known to be a power of 2. <a href="#a846bbee244f8b3e7ec21bc20f002ed9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b5112859e14388fc8e391b7f7de26c8">eraseInst</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase <span class="doxyComputerOutput">MI</span>. <a href="#a9b5112859e14388fc8e391b7f7de26c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a44e20b38fdd26858c54152cf52acc2">matchSimplifyAddToSub</a> (MachineInstr &amp;MI, std::tuple&lt; Register, Register &gt; &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if MI is a G_ADD which can be simplified to a G_SUB. <a href="#a4a44e20b38fdd26858c54152cf52acc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42edcf21dec07a1758316328df9216be">applySimplifyAddToSub</a> (MachineInstr &amp;MI, std::tuple&lt; Register, Register &gt; &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab86990eacd037e1c72749c3342d410e">matchHoistLogicOpWithSameOpcodeHands</a> (MachineInstr &amp;MI, InstructionStepsMatchInfo &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match (logic_op (op x...), (op y...)) -&gt; (op (logic_op x, y)) <a href="#aab86990eacd037e1c72749c3342d410e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dfd04f65a3e59e3ec45ac554aaf6234">applyBuildInstructionSteps</a> (MachineInstr &amp;MI, InstructionStepsMatchInfo &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace <span class="doxyComputerOutput">MI</span> with a series of instructions described in <span class="doxyComputerOutput">MatchInfo</span>. <a href="#a3dfd04f65a3e59e3ec45ac554aaf6234">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe660eb45c9320803ef32f88757a79c7">matchAshrShlToSextInreg</a> (MachineInstr &amp;MI, std::tuple&lt; Register, int64_t &gt; &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match ashr (shl x, C), C -&gt; sext_inreg (C) <a href="#afe660eb45c9320803ef32f88757a79c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab521134f26557f6178240bd7ddc7ab59">applyAshShlToSextInreg</a> (MachineInstr &amp;MI, std::tuple&lt; Register, int64_t &gt; &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeba19575c25ff51fe86cca1b6a3536a9">matchOverlappingAnd</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fold and(and(x, C1), C2) -&gt; C1&amp;C2 ? and(x, C1&amp;C2) : 0. <a href="#aeba19575c25ff51fe86cca1b6a3536a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9804726a37a620da474deef91f667eb">matchRedundantAnd</a> (MachineInstr &amp;MI, Register &amp;Replacement) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3416b258eb84253f8111ea33e0beeed">matchRedundantOr</a> (MachineInstr &amp;MI, Register &amp;Replacement) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66cc0cc249557274e026f892dbde2fd1">matchRedundantSExtInReg</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed1d04073cbd814c13097e138d462e6">matchNotCmp</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; Register &gt; &amp;RegsToNegate) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine inverting a result of a compare into the opposite cond code. <a href="#a8ed1d04073cbd814c13097e138d462e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a321f2dfbd709348cfd0e1ab66cf0b62c">applyNotCmp</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; Register &gt; &amp;RegsToNegate) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62065b49533b4287092563e507342296">matchXorOfAndWithSameReg</a> (MachineInstr &amp;MI, std::pair&lt; Register, Register &gt; &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fold (xor (and x, y), y) -&gt; (and (not x), y) {. <a href="#a62065b49533b4287092563e507342296">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc3f78b3eded52f46e9f47c03a00934">applyXorOfAndWithSameReg</a> (MachineInstr &amp;MI, std::pair&lt; Register, Register &gt; &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1abfcdfd643f1f81f3cf28cdfa5746b8">matchPtrAddZero</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a1abfcdfd643f1f81f3cf28cdfa5746b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dbebc83f6114ab6cee672147800c858">applyPtrAddZero</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198b2e1185e6d3b4eb5e68283a4b504a">applySimplifyURemByPow2</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine G_UREM x, (known power of 2) to an add and bitmasking. <a href="#a198b2e1185e6d3b4eb5e68283a4b504a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f4c3db433c1eb3e4feab24f3afb7db">matchFoldBinOpIntoSelect</a> (MachineInstr &amp;MI, unsigned &amp;SelectOpNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Push a binary operator through a select on constants. <a href="#aa3f4c3db433c1eb3e4feab24f3afb7db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70fac2d1e6e0b0c95591638ca99cae07">applyFoldBinOpIntoSelect</a> (MachineInstr &amp;MI, const unsigned &amp;SelectOpNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">SelectOperand</span> is the operand in binary operator <span class="doxyComputerOutput">MI</span> that is the select to fold. <a href="#a70fac2d1e6e0b0c95591638ca99cae07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a570b6dfed72efec6554e992d5afdd1e4">matchCombineInsertVecElts</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; Register &gt; &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb7bd8a1c290e9acba95192edd1be268">applyCombineInsertVecElts</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; Register &gt; &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a070e7ae88917971c8b99b3bb7f3d5942">matchLoadOrCombine</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match expression trees of the form. <a href="#a070e7ae88917971c8b99b3bb7f3d5942">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fd133d3cc0d8e1b33fe7ae34657d45c">matchExtendThroughPhis</a> (MachineInstr &amp;MI, MachineInstr *&amp;ExtMI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa09e8f13910a43ba1b8edc182c7a212c">applyExtendThroughPhis</a> (MachineInstr &amp;MI, MachineInstr *&amp;ExtMI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21a291953b9b99793faf8bea9286ebd7">matchExtractVecEltBuildVec</a> (MachineInstr &amp;MI, Register &amp;Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3bd6f239db6919e67236164cd0d840f">applyExtractVecEltBuildVec</a> (MachineInstr &amp;MI, Register &amp;Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bd2bb9d716a15d8d914b0236e32e2ee">matchExtractAllEltsFromBuildVector</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; std::pair&lt; Register, MachineInstr * &gt; &gt; &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecfc4a2e41e3c67c64ee64ed29103630">applyExtractAllEltsFromBuildVector</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; std::pair&lt; Register, MachineInstr * &gt; &gt; &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adad8e2cc6004250fe9f73534934363fb">applyBuildFn</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> a function which takes in a <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> to perform a combine. <a href="#adad8e2cc6004250fe9f73534934363fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cc535281480db1c2f9d8f0bec0f2c95">applyBuildFnNoErase</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> a function which takes in a <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> to perform a combine. <a href="#a9cc535281480db1c2f9d8f0bec0f2c95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3748ec69250bb09564362325c334c9ae">matchOrShiftToFunnelShift</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6618ef11a5296a1388144d2fdae9f6e3">matchFunnelShiftToRotate</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match an FSHL or FSHR that can be combined to a ROTR or ROTL rotate. <a href="#a6618ef11a5296a1388144d2fdae9f6e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad059815281df2717db5ad88dc3686a51">applyFunnelShiftToRotate</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe5511c3ea29fcdddf397489e2b3ba9c">matchRotateOutOfRange</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa191c1a15614a3cbf80f3eaf7ca935d">applyRotateOutOfRange</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e44e0e5bdc7526a1b299ae804752709">matchUseVectorTruncate</a> (MachineInstr &amp;MI, Register &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cbfa42d7993571ddbfe46d0c37abafb">applyUseVectorTruncate</a> (MachineInstr &amp;MI, Register &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98f00ea8e8ca7e8ce4888da5cb138b43">matchICmpToTrueFalseKnownBits</a> (MachineInstr &amp;MI, int64_t &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79ff9815398a2c3331b42832035f21c6">matchICmpToLHSKnownBits</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac73c9c9888dd26d04e2eeb87aca714c">matchAndOrDisjointMask</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac1fd587d596fe9aeb38b219966ebd3c">matchBitfieldExtractFromSExtInReg</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Form a G_SBFX from a G_SEXT_INREG fed by a right shift. <a href="#aac1fd587d596fe9aeb38b219966ebd3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab92d16362139d524a7012e2d29c9821">matchBitfieldExtractFromAnd</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match: and (lshr x, cst), mask -&gt; ubfx x, cst, width. <a href="#aab92d16362139d524a7012e2d29c9821">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16d6a69c22795ffc8819bc7bc0e1bae2">matchBitfieldExtractFromShr</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match: shr (shl x, n), k -&gt; sbfx/ubfx x, pos, width. <a href="#a16d6a69c22795ffc8819bc7bc0e1bae2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6aaf27c1306e54d433cd45f84ee74e5">matchBitfieldExtractFromShrAnd</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match: shr (and x, n), k -&gt; ubfx x, pos, width. <a href="#aa6aaf27c1306e54d433cd45f84ee74e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a169aab3da2c9763de9377694467eae61">matchReassocConstantInnerRHS</a> (GPtrAdd &amp;MI, MachineInstr *RHS, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab53ed6a166f868585b2a095c546edc">matchReassocFoldConstantsInSubTree</a> (GPtrAdd &amp;MI, MachineInstr *LHS, MachineInstr *RHS, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb0aa3738412a41ec60b41d08d849078">matchReassocConstantInnerLHS</a> (GPtrAdd &amp;MI, MachineInstr *LHS, MachineInstr *RHS, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c17b27587a29f1c02dbf942ed6fc808">matchReassocPtrAdd</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reassociate pointer calculations with G_ADD involved, to allow better addressing mode usage. <a href="#a7c17b27587a29f1c02dbf942ed6fc808">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a9739cf49c46adcb76ac7e2dc13545c">tryReassocBinOp</a> (unsigned Opc, Register DstReg, Register Op0, Register Op1, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to reassociate to reassociate operands of a commutative binop. <a href="#a9a9739cf49c46adcb76ac7e2dc13545c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2981a1ffe2c800e92ca997ada870ee6f">matchReassocCommBinOp</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reassociate commutative binary operations like G_ADD. <a href="#a2981a1ffe2c800e92ca997ada870ee6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ae6cc9d1541ff2e91dd25d1da665d4">matchConstantFoldCastOp</a> (MachineInstr &amp;MI, APInt &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do constant folding when opportunities are exposed after MIR building. <a href="#aa8ae6cc9d1541ff2e91dd25d1da665d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12106e55b2bdb2132757797665813f21">matchConstantFoldBinOp</a> (MachineInstr &amp;MI, APInt &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do constant folding when opportunities are exposed after MIR building. <a href="#a12106e55b2bdb2132757797665813f21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ba3e97ad5883fd02115afb289d2ccdd">matchConstantFoldFPBinOp</a> (MachineInstr &amp;MI, ConstantFP *&amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do constant FP folding when opportunities are exposed after MIR building. <a href="#a9ba3e97ad5883fd02115afb289d2ccdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add44d478a1c329e77659000039f6ae74">matchConstantFoldFMA</a> (MachineInstr &amp;MI, ConstantFP *&amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> fold G_FMA/G_FMAD. <a href="#add44d478a1c329e77659000039f6ae74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59e682863250eb07290a348d548eee0d">matchNarrowBinopFeedingAnd</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b3616540da1859ec9d030a76cad94f">buildUDivUsingMul</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an G_UDIV <span class="doxyComputerOutput">MI</span> expressing a divide by constant, return an expression that implements it by multiplying by a magic number. <a href="#af3b3616540da1859ec9d030a76cad94f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51f93c65cadd67241250f97598ab1358">matchUDivByConst</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine G_UDIV by constant into a multiply by magic constant. <a href="#a51f93c65cadd67241250f97598ab1358">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad67f36800bff5506b51d7eaa3259cd01">applyUDivByConst</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5d3388e53cb2767927dba7c18c64a00">buildSDivUsingMul</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an G_SDIV <span class="doxyComputerOutput">MI</span> expressing a signed divide by constant, return an expression that implements it by multiplying by a magic number. <a href="#af5d3388e53cb2767927dba7c18c64a00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23ff02c4dc0c7eb4bc173bc9af346765">matchSDivByConst</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49d52b12000c2c069a30b9b22809385d">applySDivByConst</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a575d0877b1d93fc6c416bf667876fb75">matchDivByPow2</a> (MachineInstr &amp;MI, bool IsSigned) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an G_SDIV <span class="doxyComputerOutput">MI</span> expressing a signed divided by a pow2 constant, return expressions that implements it by shifting. <a href="#a575d0877b1d93fc6c416bf667876fb75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41cebcf8d37086a913f6a5424e0bff66">applySDivByPow2</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4381e87d4240311eeff998ea33556263">applyUDivByPow2</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an G_UDIV <span class="doxyComputerOutput">MI</span> expressing an unsigned divided by a pow2 constant, return expressions that implements it by shifting. <a href="#a4381e87d4240311eeff998ea33556263">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd5de1d4698c082f674654d67b42f1ca">matchUMulHToLShr</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3012f3ba9714ad992670d388b7c70618">applyUMulHToLShr</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a094194cbf835d3ebeb1039b1ed575121">tryCombine</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to transform <span class="doxyComputerOutput">MI</span> by using all of the above combine functions. <a href="#a094194cbf835d3ebeb1039b1ed575121">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c12c2286b1a252d619bb618c8b5d356">tryEmitMemcpyInline</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit loads and stores that perform the given memcpy. <a href="#a4c12c2286b1a252d619bb618c8b5d356">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a5d3fcc788946d3383d547eac00eca">matchMulOBy2</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match: (G_UMULO x, 2) -&gt; (G_UADDO x, x) (G_SMULO x, 2) -&gt; (G_SADDO x, x) <a href="#a72a5d3fcc788946d3383d547eac00eca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad43afc169977548bbf11956b91156040">matchMulOBy0</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match: (G_*MULO x, 0) -&gt; 0 + no carry out. <a href="#ad43afc169977548bbf11956b91156040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15a55602a4ab55a9ae6ad194922d6f72">matchAddEToAddO</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match: (G_*ADDE x, y, 0) -&gt; (G_*ADDO x, y) (G_*SUBE x, y, 0) -&gt; (G_*SUBO x, y) <a href="#a15a55602a4ab55a9ae6ad194922d6f72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cd94b9d480eadb598a5125b9b294efe">matchRedundantNegOperands</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform (fadd x, fneg(y)) -&gt; (fsub x, y) (fadd fneg(x), y) -&gt; (fsub y, x) (fsub x, fneg(y)) -&gt; (fadd x, y) (fmul fneg(x), fneg(y)) -&gt; (fmul x, y) (fdiv fneg(x), fneg(y)) -&gt; (fdiv x, y) (fmad fneg(x), fneg(y), z) -&gt; (fmad x, y, z) (fma fneg(x), fneg(y), z) -&gt; (fma x, y, z) <a href="#a5cd94b9d480eadb598a5125b9b294efe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb80926c82768fa525eee40937db0d81">matchFsubToFneg</a> (MachineInstr &amp;MI, Register &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca173dc6e071e5c8c37b62f3d095eb5">applyFsubToFneg</a> (MachineInstr &amp;MI, Register &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e388c06478515344e2fce08b1357025">canCombineFMadOrFMA</a> (MachineInstr &amp;MI, bool &amp;AllowFusionGlobally, bool &amp;HasFMAD, bool &amp;Aggressive, bool CanReassociate=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fbed34899e8c323d738ef2eac96dd20">matchCombineFAddFMulToFMadOrFMA</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform (fadd (fmul x, y), z) -&gt; (fma x, y, z) (fadd (fmul x, y), z) -&gt; (fmad x, y, z) <a href="#a5fbed34899e8c323d738ef2eac96dd20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a246c328def50bbd9e892666ae3fb1947">matchCombineFAddFpExtFMulToFMadOrFMA</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform (fadd (fpext (fmul x, y)), z) -&gt; (fma (fpext x), (fpext y), z) (fadd (fpext (fmul x, y)), z) -&gt; (fmad (fpext x), (fpext y), z) <a href="#a246c328def50bbd9e892666ae3fb1947">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d65481969f8d9628b5ee128c99212b">matchCombineFAddFMAFMulToFMadOrFMA</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform (fadd (fma x, y, (fmul u, v)), z) -&gt; (fma x, y, (fma u, v, z)) (fadd (fmad x, y, (fmul u, v)), z) -&gt; (fmad x, y, (fmad u, v, z)) <a href="#a54d65481969f8d9628b5ee128c99212b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af73a2a8f01e0df7eb8908768292dd30e">matchCombineFAddFpExtFMulToFMadOrFMAAggressive</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a541aab24d54889f539ea0e41c6a00b2c">matchCombineFSubFMulToFMadOrFMA</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform (fsub (fmul x, y), z) -&gt; (fma x, y, -z) (fsub (fmul x, y), z) -&gt; (fmad x, y, -z) <a href="#a541aab24d54889f539ea0e41c6a00b2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade46635032e4ec34657bc9b237d37e0b">matchCombineFSubFNegFMulToFMadOrFMA</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform (fsub (fneg (fmul, x, y)), z) -&gt; (fma (fneg x), y, (fneg z)) (fsub (fneg (fmul, x, y)), z) -&gt; (fmad (fneg x), y, (fneg z)) <a href="#ade46635032e4ec34657bc9b237d37e0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9b7bf9027b6c116d92fbebd2ba8372">matchCombineFSubFpExtFMulToFMadOrFMA</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform (fsub (fpext (fmul x, y)), z) -&gt; (fma (fpext x), (fpext y), (fneg z)) (fsub (fpext (fmul x, y)), z) -&gt; (fmad (fpext x), (fpext y), (fneg z)) <a href="#a4c9b7bf9027b6c116d92fbebd2ba8372">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4a2ebe747c416cbe4efb4b77ba2b588">matchCombineFSubFpExtFNegFMulToFMadOrFMA</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform (fsub (fpext (fneg (fmul x, y))), z) -&gt; (fneg (fma (fpext x), (fpext y), z)) (fsub (fpext (fneg (fmul x, y))), z) -&gt; (fneg (fmad (fpext x), (fpext y), z)) <a href="#ac4a2ebe747c416cbe4efb4b77ba2b588">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac31ecf657d06f3e6f617cd4d6e035f1a">matchCombineFMinMaxNaN</a> (MachineInstr &amp;MI, unsigned &amp;Info) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5036bb5c5ecc303b0416937c6eb9d6e3">matchAddSubSameReg</a> (MachineInstr &amp;MI, Register &amp;Src) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform G_ADD(x, G_SUB(y, x)) to y. <a href="#a5036bb5c5ecc303b0416937c6eb9d6e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa654694a53f814ff3cb1b2d04513da6e">matchBuildVectorIdentityFold</a> (MachineInstr &amp;MI, Register &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6cad51d01e79fc7c77d3c58d58394da">matchTruncBuildVectorFold</a> (MachineInstr &amp;MI, Register &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a350580c34bfdfd93dbeb51e3f2b44fa4">matchTruncLshrBuildVectorFold</a> (MachineInstr &amp;MI, Register &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac793ece837d10b193280411783d33e">matchSubAddSameReg</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform: (x + y) - y -&gt; x (x + y) - x -&gt; y x - (y + x) -&gt; 0 - y x - (x + z) -&gt; 0 - z. <a href="#aeac793ece837d10b193280411783d33e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad133fd24c3d69592d832837ce6a24c75">matchSimplifySelectToMinMax</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf88f3025beeaebb5bd345ebe277711c">matchRedundantBinOpInEquality</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform: (X + Y) == X -&gt; Y == 0 (X - Y) == X -&gt; Y == 0 (X ^ Y) == X -&gt; Y == 0 (X + Y) != X -&gt; Y != 0 (X - Y) != X -&gt; Y != 0 (X ^ Y) != X -&gt; Y != 0. <a href="#aaf88f3025beeaebb5bd345ebe277711c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e1dc2aa53c4d2b688e9a1e5fe4a95b">matchShiftsTooBig</a> (MachineInstr &amp;MI, std::optional&lt; int64_t &gt; &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match shifts greater or equal to the range (the bitwidth of the result datatype, or the effective bitwidth of the source value). <a href="#a21e1dc2aa53c4d2b688e9a1e5fe4a95b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b4c477b0ac10183266094734941f417">matchCommuteConstantToRHS</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match constant LHS ops that should be commuted. <a href="#a2b4c477b0ac10183266094734941f417">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5036ae118b8d8b9debc1c596eff93259">matchSextOfTrunc</a> (const MachineOperand &amp;MO, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine sext of trunc. <a href="#a5036ae118b8d8b9debc1c596eff93259">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27942d2942b84e3453b75e3417def841">matchZextOfTrunc</a> (const MachineOperand &amp;MO, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine zext of trunc. <a href="#a27942d2942b84e3453b75e3417def841">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f87fb73ebb3f5d6d7e49e99fa478fa3">matchNonNegZext</a> (const MachineOperand &amp;MO, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine zext nneg to sext. <a href="#a2f87fb73ebb3f5d6d7e49e99fa478fa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1285dc5bae6f80f64a0d757b136279d">matchCommuteFPConstantToRHS</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match constant LHS FP ops that should be commuted. <a href="#ac1285dc5bae6f80f64a0d757b136279d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1832f2fdfaaea5fb0e64e8a4ea11ee0">applyCommuteBinOpOperands</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9098323777f98b3dd53bef412554961c">matchSelectIMinMax</a> (const MachineOperand &amp;MO, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine select to integer min/max. <a href="#a9098323777f98b3dd53bef412554961c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e6e1c84d8b84dbd2101236bca332d95">matchSimplifyNegMinMax</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tranform (neg (min/max x, (neg x))) into (max/min x, (neg x)). <a href="#a2e6e1c84d8b84dbd2101236bca332d95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab57fb15e1f069496b2fa0b372b9b0475">matchSelect</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine selects. <a href="#ab57fb15e1f069496b2fa0b372b9b0475">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc0e07192feecf6c110017414a96fa2d">matchAnd</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine ands. <a href="#adc0e07192feecf6c110017414a96fa2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a449f68393659418a84ad0369a8a37be0">matchOr</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine ors. <a href="#a449f68393659418a84ad0369a8a37be0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac58443a61bc007251b27585f5887c6d">matchNarrowBinop</a> (const MachineInstr &amp;TruncMI, const MachineInstr &amp;BinopMI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>trunc (binop X, C) --&gt; binop (trunc X, trunc C). <a href="#aac58443a61bc007251b27585f5887c6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb8af468cabe232d8d64944acf6930b7">matchCastOfInteger</a> (const MachineInstr &amp;CastMI, APInt &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab46d848f3726829246738eb9d78aebf9">matchAddOverflow</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine addos. <a href="#ab46d848f3726829246738eb9d78aebf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f83785782b043b22a617554b65b5f0a">matchExtractVectorElement</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine extract vector element. <a href="#a4f83785782b043b22a617554b65b5f0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7bcd2506b90a78c86a2ac061132783f">matchExtractVectorElementWithBuildVector</a> (const MachineInstr &amp;MI, const MachineInstr &amp;MI2, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine extract vector element with a build vector on the vector register. <a href="#af7bcd2506b90a78c86a2ac061132783f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a97e27cc61249c732f88ca2b63ce73f">matchExtractVectorElementWithBuildVectorTrunc</a> (const MachineOperand &amp;MO, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine extract vector element with a build vector trunc on the vector register. <a href="#a2a97e27cc61249c732f88ca2b63ce73f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89092e8630095ccf5b948def71d884f1">matchExtractVectorElementWithShuffleVector</a> (const MachineInstr &amp;MI, const MachineInstr &amp;MI2, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine extract vector element with a shuffle vector on the vector register. <a href="#a89092e8630095ccf5b948def71d884f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d2f7a0f835e800e04b1fae871054e01">matchExtractVectorElementWithDifferentIndices</a> (const MachineOperand &amp;MO, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine extract vector element with a insert vector element on the vector register and different indices. <a href="#a3d2f7a0f835e800e04b1fae871054e01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3df1d9d3afbfe5db4027289cf28d4726">matchShuffleUndefRHS</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove references to rhs if it is undef. <a href="#a3df1d9d3afbfe5db4027289cf28d4726">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d345595bdc1655f01d68419353184cf">matchShuffleDisjointMask</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn shuffle a, b, mask -&gt; shuffle undef, b, mask iff mask does not reference a. <a href="#a6d345595bdc1655f01d68419353184cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b46e1c0d91a5df6f3f45d573f833b1a">applyBuildFnMO</a> (const MachineOperand &amp;MO, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> a function which takes in a <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> to perform a combine. <a href="#a2b46e1c0d91a5df6f3f45d573f833b1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb504c8fdf12e04e71a4ea3f728ced62">matchFPowIExpansion</a> (MachineInstr &amp;MI, int64_t Exponent) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match FPOWI if it's safe to extend it into a series of multiplications. <a href="#afb504c8fdf12e04e71a4ea3f728ced62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe79b9729c8080bf59fa06703f4b3b39">applyExpandFPowI</a> (MachineInstr &amp;MI, int64_t Exponent) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expands FPOWI into a series of multiplications and a division if the exponent is negative. <a href="#abe79b9729c8080bf59fa06703f4b3b39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4726b2a74fcb79e35ec78c54ec7aa8ee">matchInsertVectorElementOOB</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine insert vector element OOB. <a href="#a4726b2a74fcb79e35ec78c54ec7aa8ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2bd5329e5726d560529de68df90503c">matchFreezeOfSingleMaybePoisonOperand</a> (MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a597eabfac4d80feedf71d122bbaf4e00">matchAddOfVScale</a> (const MachineOperand &amp;MO, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56ee7200c7a0fb8ed2b9f98288d83ff2">matchMulOfVScale</a> (const MachineOperand &amp;MO, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac88c813e35b6d1a4966b0ee24a5c8b9a">matchSubOfVScale</a> (const MachineOperand &amp;MO, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b5001e37af42df3e8202151fe08b3c9">matchShlOfVScale</a> (const MachineOperand &amp;MO, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a633b0486bab32c1b91cc923d82a72c2d">matchTruncateOfExt</a> (const MachineInstr &amp;Root, const MachineInstr &amp;ExtMI, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform trunc ([asz]ext x) to x or ([asz]ext x) or (trunc x). <a href="#a633b0486bab32c1b91cc923d82a72c2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaeb891d2410d3aaf4d95fc61028f7b4">matchCastOfSelect</a> (const MachineInstr &amp;Cast, const MachineInstr &amp;SelectMI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a207867c80e7ad2da595e7a9adedcb612">matchFoldAPlusC1MinusC2</a> (const MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05e094eb5ea044b72cda4473bc6d78fc">matchFoldC2MinusAPlusC1</a> (const MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71eafce3200f8a358c6855e3b6ee0a51">matchFoldAMinusC1MinusC2</a> (const MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b45fbac775c8ccd0b606e0a5ea671bf">matchFoldC1Minus2MinusC2</a> (const MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a183457f9d99bea5ee1a2fd06ceb9bb99">matchFoldAMinusC1PlusC2</a> (const MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b617a5a6a2773b70ea354e1dffceff7">matchExtOfExt</a> (const MachineInstr &amp;FirstMI, const MachineInstr &amp;SecondMI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88fdd4a40851c70c1f04282174034c2">matchCastOfBuildVector</a> (const MachineInstr &amp;CastMI, const MachineInstr &amp;BVMI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e76e88a680a8f2de889a6f6928fcc0">matchCanonicalizeICmp</a> (const MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c6878dbda903ec9201f83db42d93fdc">matchCanonicalizeFCmp</a> (const MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12794dfd41dd116d9e295524d932f6c0">matchUnmergeValuesAnyExtBuildVector</a> (const MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65bdadc254b269b10b7e67d39a9527dc">matchMergeXAndUndef</a> (const MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a518e2853dfbfd37675a14b6bf1ca6c90">matchMergeXAndZero</a> (const MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc129334a6d3d83eb003dd1a49540f80">matchSuboCarryOut</a> (const MachineInstr &amp;MI, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7aa30e08e6ec88a7c7d03d8eda4c23">isIndexedLoadStoreLegal</a> (GLoadStore &amp;LdSt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks for legality of an indexed variant of <span class="doxyComputerOutput">LdSt</span>. <a href="#a7e7aa30e08e6ec88a7c7d03d8eda4c23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2700f65ebe47d115d7df1b1fd68addd7">findPostIndexCandidate</a> (GLoadStore &amp;MI, Register &amp;Addr, Register &amp;Base, Register &amp;Offset, bool &amp;RematOffset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a non-indexed load or store instruction <span class="doxyComputerOutput">MI</span>, find an offset that can be usefully and legally folded into it as a post-indexing operation. <a href="#a2700f65ebe47d115d7df1b1fd68addd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38cee7ff8d64cc03ac43668943d5f184">findPreIndexCandidate</a> (GLoadStore &amp;MI, Register &amp;Addr, Register &amp;Base, Register &amp;Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a non-indexed load or store instruction <span class="doxyComputerOutput">MI</span>, find an offset that can be usefully and legally folded into it as a pre-indexing operation. <a href="#a38cee7ff8d64cc03ac43668943d5f184">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 8 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab94c04f9410ae544fc398a7c63a7f2ac">findCandidatesForLoadOrCombine</a> (const MachineInstr *Root) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function for matchLoadOrCombine. <a href="#ab94c04f9410ae544fc398a7c63a7f2ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/gzextload">GZExtLoad</a> *, int64_t, <a href="/web-llvm/docs/api/classes/llvm/gzextload">GZExtLoad</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a025805b8366e0c582e942f86d5dc516f">findLoadOffsetsForLoadOrCombine</a> (SmallDenseMap&lt; int64_t, int64_t, 8 &gt; &amp;MemOffset2Idx, const SmallVector&lt; Register, 8 &gt; &amp;RegsToVisit, const unsigned MemSizeInBits) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function for matchLoadOrCombine. <a href="#a025805b8366e0c582e942f86d5dc516f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e6706e6003a3f7b6184a73458132406">reassociationCanBreakAddressingModePattern</a> (MachineInstr &amp;PtrAdd) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examines the G_PTR_ADD instruction <span class="doxyComputerOutput">PtrAdd</span> and determines if performing a re-association of its operands would break an existing legal addressing mode that the address computation currently represents. <a href="#a4e6706e6003a3f7b6184a73458132406">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">SelectPatternNaNBehaviour</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e9632b4688c1ddb0fd9ec1ad4e973d2">computeRetValAgainstNaN</a> (Register LHS, Register RHS, bool IsOrderedComparison) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabe72346a2a7587fa74dfbd197065037">getFPMinMaxOpcForSelect</a> (CmpInst::Predicate Pred, LLT DstTy, SelectPatternNaNBehaviour VsNaNRetVal) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines the floating point min/max opcode which should be used for a G_SELECT fed by a G_FCMP with predicate <span class="doxyComputerOutput">Pred</span>. <a href="#aabe72346a2a7587fa74dfbd197065037">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d8f27a873dde4e150529c99fb41498c">matchFPSelectToMinMax</a> (Register Dst, Register Cond, Register TrueVal, Register FalseVal, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle floating point cases for matchSimplifySelectToMinMax. <a href="#a8d8f27a873dde4e150529c99fb41498c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadbbd31b2959872b72b4cde875b86bef">tryFoldBoolSelectToLogic</a> (GSelect *Select, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to fold selects to logical operations. <a href="#aadbbd31b2959872b72b4cde875b86bef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12dbac5fd74a23a5cc38c397ae4f8efc">tryFoldSelectOfConstants</a> (GSelect *Select, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aa63605494f148c2c7c193a6af180c9">isOneOrOneSplat</a> (Register Src, bool AllowUndefs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02c38d89f04cffc015c06bac29f1bd42">isZeroOrZeroSplat</a> (Register Src, bool AllowUndefs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43efec1114a284e3e5acfbe484ef75f6">isConstantSplatVector</a> (Register Src, int64_t SplatValue, bool AllowUndefs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a863e910fe7a06a014195c53b42560540">isConstantOrConstantVectorI</a> (Register Src) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac37a91643de0fa959d5a92f87dfccd52">getConstantOrConstantSplatVector</a> (Register Src) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7c87b77e10f706b166c22d0b0438b1f">tryFoldAndOrOrICmpsUsingRanges</a> (GLogicalBinOp *Logic, BuildFnTy &amp;MatchInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fold (icmp Pred1 V1, C1) &amp;&amp; (icmp Pred2 V2, C2) or (icmp Pred1 V1, C1) || (icmp Pred2 V2, C2) into a single comparison using range-based reasoning. <a href="#ac7c87b77e10f706b166c22d0b0438b1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bf69fcd7c631813e4f4b567a170d8af">tryFoldLogicOfFCmps</a> (GLogicalBinOp *Logic, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91accffdd4294ff1626fa0970160381c">isCastFree</a> (unsigned Opcode, LLT ToTy, LLT FromTy) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae69fd612c84de7f816d5653999ae9f03">constantFoldICmp</a> (const GICmp &amp;ICmp, const GIConstant &amp;LHSCst, const GIConstant &amp;RHSCst, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0174274d1fe6fbe4f9947be1b8849f6">constantFoldFCmp</a> (const GFCmp &amp;FCmp, const GFConstant &amp;LHSCst, const GFConstant &amp;RHSCst, BuildFnTy &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acebc61bc26bf037e13a22af30d10b071">MDT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7baaf2859fea3988241fef9589a47557">IsPreLegalize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca634f15887089866f5d88dac807786c">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad388844fc6e8318b52ee7cf5a88b8c91">RBI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8de57b7e86580531aec66fde618bef2">TRI</a></td>
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


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### SelectPatternNaNBehaviour {#ad576ffcb68795d9fc4c9e9bf88c27744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::CombinerHelper::SelectPatternNaNBehaviour </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Behavior when a floating point min/max is given one NaN and one non-NaN as input.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NOT_APPLICABLE<a id="ad576ffcb68795d9fc4c9e9bf88c27744aeb7295999e22b161fe9136ac2a60c0d5"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RETURNS_NAN<a id="ad576ffcb68795d9fc4c9e9bf88c27744ad5e656ef70423bc047b793349c5c7136"></a></td>
<td class="doxyEnumItemDescription">NaN behavior not applicable</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RETURNS_OTHER<a id="ad576ffcb68795d9fc4c9e9bf88c27744a537725fd629b2fe07fae43b8816b2a63"></a></td>
<td class="doxyEnumItemDescription">Given one NaN input, returns the NaN</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RETURNS_ANY<a id="ad576ffcb68795d9fc4c9e9bf88c27744a9b36a8964988bea38ffc58eada8fd120"></a></td>
<td class="doxyEnumItemDescription">Given one NaN input, returns the non-NaN</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1047 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CombinerHelper() {#ab45ce737b2839bf39a18e22fbb502ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CombinerHelper::CombinerHelper (<a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, bool IsPreLegalize, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> * KB=nullptr, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> * LI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="#a7baaf2859fea3988241fef9589a47557">IsPreLegalize</a>, <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="#aca634f15887089866f5d88dac807786c">LI</a>, <a href="#acebc61bc26bf037e13a22af30d10b071">MDT</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>, <a href="#ad388844fc6e8318b52ee7cf5a88b8c91">RBI</a> and <a href="#ad8de57b7e86580531aec66fde618bef2">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyAshShlToSextInreg() {#ab521134f26557f6178240bd7ddc7ab59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyAshShlToSextInreg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, int64_t &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3228 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### applyBuildFn() {#adad8e2cc6004250fe9f73534934363fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyBuildFn (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> a function which takes in a <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> to perform a combine.</p>


<p>By default, it erases the instruction <span class="doxyComputerOutput">MI</span> from the function.</p>


<p>Declaration at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4321 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#a9cc535281480db1c2f9d8f0bec0f2c95">applyBuildFnNoErase</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### applyBuildFnMO() {#a2b46e1c0d91a5df6f3f45d573f833b1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyBuildFnMO (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> a function which takes in a <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> to perform a combine.</p>


<p>By default, it erases the instruction def'd on <span class="doxyComputerOutput">MO</span> from the function.</p>


<p>Declaration at line 926 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7580 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b2430ab5e686b82f8cd6fd588d6de6f">llvm::getDefIgnoringCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### applyBuildFnNoErase() {#a9cc535281480db1c2f9d8f0bec0f2c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyBuildFnNoErase (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> a function which takes in a <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> to perform a combine.</p>


<p>This variant does not erase <span class="doxyComputerOutput">MI</span> after calling the build function.</p>


<p>Declaration at line 623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4328 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#adad8e2cc6004250fe9f73534934363fb">applyBuildFn</a>.</p>

</div>
</div>

### applyBuildInstructionSteps() {#a3dfd04f65a3e59e3ec45ac554aaf6234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyBuildInstructionSteps (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/instructionstepsmatchinfo">InstructionStepsMatchInfo</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace <span class="doxyComputerOutput">MI</span> with a series of instructions described in <span class="doxyComputerOutput">MatchInfo</span>.</p>

<p>Declaration at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/structs/llvm/instructionstepsmatchinfo/#ace6011e1decc6302ec866d0ad01fae35">llvm::InstructionStepsMatchInfo::InstrsToBuild</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### applyCombineAddP2IToPtrAdd() {#a51abd9f22e4c8694c58d6719892bd27e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineAddP2IToPtrAdd (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, bool &gt; &amp; PtrRegAndCommute)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2512 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### applyCombineConcatVectors() {#a1c95f864b062fedecfd2c4fc32abf47e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineConcatVectors (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace <span class="doxyComputerOutput">MI</span> with a flattened build_vector with <span class="doxyComputerOutput">Ops</span> or an implicit_def if <span class="doxyComputerOutput">Ops</span> is empty.</p>

<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>.</p>

</div>
</div>

### applyCombineConstantFoldFpUnary() {#a94c5f97cf33a0913064c1ff1039b73c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineConstantFoldFpUnary (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * Cst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform fp_instr(cst) to constant result of the fp operation.</p>

<p>Declaration at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1714 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a6aa7059c451076ac90510ca8a30e5dad">constantFoldFpUnary</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a1ab411da4fddde73bec70fd45762f2ad">llvm::ConstantFP::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### applyCombineConstPtrAddToI2P() {#a6296facc7f8fdeb45406bf3b7ceac5e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineConstPtrAddToI2P (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; NewCst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2551 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### applyCombineCopy() {#a4eeb3124ce1fe172f0e79b5f42be7f5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineCopy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>.</p>


<p>Referenced by <a href="#a77695e2fac4d7c37fd43e1d9a55e69ce">tryCombineCopy</a>.</p>

</div>
</div>

### applyCombineDivRem() {#ac2377979438dcdab9e664ccd5f975dac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineDivRem (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; OtherMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1561 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="#ad99c8ee849f72738dd718fec8d3a1d42">dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### applyCombineExtendingLoads() {#a00301689820a26a9f3b438f6dece6ef0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineExtendingLoads (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/preferredtuple">PreferredTuple</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/structs/llvm/preferredtuple/#ae846809b677f5cc759c2360d3fceed3a">llvm::PreferredTuple::ExtendOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#ab8a8668cff59b4eb557f0a7427cbe7bd">getExtLoadOpcForExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>, <a href="/web-llvm/docs/api/structs/llvm/preferredtuple/#a378eb202d00f304b374eab7585ce7b64">llvm::PreferredTuple::MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>, <a href="#a290f07593ec0820655db5efe88422c44">replaceRegOpWith</a>, <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>, <a href="/web-llvm/docs/api/structs/llvm/preferredtuple/#a1b183e97d50ba4c09e23118f4075fda5">llvm::PreferredTuple::Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>


<p>Referenced by <a href="#aa57157299174e74145361548452e45f9">tryCombineExtendingLoads</a>.</p>

</div>
</div>

### applyCombineI2PToP2I() {#a346cb10c60061779896b022fb4f75a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineI2PToP2I (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2471 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### applyCombineIndexedLoadStore() {#a72848dca494afcf56b2bc2bea4322dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineIndexedLoadStore (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/indexedloadstorematchinfo">IndexedLoadStoreMatchInfo</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1463 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/indexedloadstorematchinfo/#a97bfd306dc51ab54572e11569722c1db">llvm::IndexedLoadStoreMatchInfo::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/indexedloadstorematchinfo/#a3328011280e1c30771b17c673aa50214">llvm::IndexedLoadStoreMatchInfo::Base</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a59a04ccc4199cf2956dc306beec474f9">getIndexedOpc</a>, <a href="/web-llvm/docs/api/structs/llvm/indexedloadstorematchinfo/#a5e77493a41515a3d61869442c23a9085">llvm::IndexedLoadStoreMatchInfo::IsPre</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/indexedloadstorematchinfo/#a38e02f76019824d6efeb1362c85d1b00">llvm::IndexedLoadStoreMatchInfo::Offset</a> and <a href="/web-llvm/docs/api/structs/llvm/indexedloadstorematchinfo/#a188df9024d6812274403b293cbc7117b">llvm::IndexedLoadStoreMatchInfo::RematOffset</a>.</p>

</div>
</div>

### applyCombineInsertVecElts() {#afb7bd8a1c290e9acba95192edd1be268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineInsertVecElts (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3062 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### applyCombineMulToShl() {#acaf0ebafd584479c2c6a1a782ff149f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineMulToShl (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned &amp; ShiftVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2042 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a35384c47e5ca9690216b1aa8fed5a8c9">llvm::MachineIRBuilder::getTII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518aefc960a99fa4cefc28a0ea76de0a0535">llvm::MachineInstr::NoSWrap</a> and <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>.</p>

</div>
</div>

### applyCombineP2IToI2P() {#aa0691f830cef4a0dadf0f0fbd41e7bca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineP2IToI2P (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform PtrToInt(IntToPtr(x)) to x.</p>

<p>Declaration at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2479 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### applyCombineShiftToUnmerge() {#afae5d269529ade8f678f13c1dde831d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineShiftToUnmerge (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned &amp; ShiftVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2378 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#aa3f99a0f1d4b4f20f945a7cc8f7e1d65">tryCombineShiftToUnmerge</a>.</p>

</div>
</div>

### applyCombineShlOfExtend() {#a6b8e5256d82c820e81d9c5b7fb3016ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineShlOfExtend (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerimmpair">RegisterImmPair</a> &amp; MatchData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/structs/llvm/registerimmpair/#a15130db3b3cf5b29ae82d817f4ecdca1">llvm::RegisterImmPair::Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/structs/llvm/registerimmpair/#a0441320b16ae9242aca4afe9f8e511b3">llvm::RegisterImmPair::Reg</a>.</p>

</div>
</div>

### applyCombineShuffleConcat() {#a25bc0b47af5d0bcbb989180e1eb3f928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineShuffleConcat (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace <span class="doxyComputerOutput">MI</span> with a flattened build_vector with <span class="doxyComputerOutput">Ops</span> or an implicit_def if <span class="doxyComputerOutput">Ops</span> is empty.</p>

<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### applyCombineShuffleVector() {#a7ee8b3f43a97b93dde8c791002d306f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineShuffleVector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace <span class="doxyComputerOutput">MI</span> with a concat_vectors with <span class="doxyComputerOutput">Ops</span>.</p>

<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>.</p>


<p>Referenced by <a href="#aa9de7f911f64078bdbf773007dc10997">tryCombineShuffleVector</a>.</p>

</div>
</div>

### applyCombineTruncOfShift() {#ac91aca84eade26acea192464a9cfcde8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineTruncOfShift (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2666 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="#a9b5112859e14388fc8e391b7f7de26c8">eraseInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>.</p>

</div>
</div>

### applyCombineUnmergeConstant() {#a21bee05dda9718594fbfd89855272cd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineUnmergeConstant (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; &amp; Csts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2242 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### applyCombineUnmergeMergeToPlainValues() {#afcc62af19a5d1f2ea5f0e51b3e31893b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineUnmergeMergeToPlainValues (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>.</p>

</div>
</div>

### applyCombineUnmergeWithDeadLanesToTrunc() {#a122b5e6289b7f7f787ea54fb607664b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineUnmergeWithDeadLanesToTrunc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2287 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### applyCombineUnmergeZExtToZExt() {#afe9d6cb97689cb5efb1a5b8f9dc68ea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCombineUnmergeZExtToZExt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2321 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>.</p>

</div>
</div>

### applyCommuteBinOpOperands() {#af1832f2fdfaaea5fb0e64e8a4ea11ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyCommuteBinOpOperands (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 864 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6687 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>.</p>

</div>
</div>

### applyExpandFPowI() {#abe79b9729c8080bf59fa06703f4b3b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyExpandFPowI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int64_t Exponent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expands FPOWI into a series of multiplications and a division if the exponent is negative.</p>

<p>Declaration at line 933 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7593 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a403260df3a211e47e65f35fbfd9bee8faf5ccb8d51ca38e2f3329955fc0149cd4">llvm::Exponent</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### applyExtendThroughPhis() {#aa09e8f13910a43ba1b8edc182c7a212c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyExtendThroughPhis (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; ExtMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### applyExtractAllEltsFromBuildVector() {#aecfc4a2e41e3c67c64ee64ed29103630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyExtractAllEltsFromBuildVector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4309 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>.</p>

</div>
</div>

### applyExtractVecEltBuildVec() {#aa3bd6f239db6919e67236164cd0d840f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyExtractVecEltBuildVec (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4250 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#a25ff4284ba96727747d6ceb7ef16b95d">replaceSingleDefInstWithReg</a>.</p>

</div>
</div>

### applyFoldBinOpIntoSelect() {#a70fac2d1e6e0b0c95591638ca99cae07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyFoldBinOpIntoSelect (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned &amp; SelectOpNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><span class="doxyComputerOutput">SelectOperand</span> is the operand in binary operator <span class="doxyComputerOutput">MI</span> that is the select to fold.</p>

<p>Declaration at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3732 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select</a>.</p>

</div>
</div>

### applyFsubToFneg() {#a4ca173dc6e071e5c8c37b62f3d095eb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyFsubToFneg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 756 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5742 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="#a9b5112859e14388fc8e391b7f7de26c8">eraseInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### applyFunnelShiftConstantModulo() {#a6766b5f9c46b6dd7bb3b45857ec23a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyFunnelShiftConstantModulo (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replaces the shift amount in <span class="doxyComputerOutput">MI</span> with ShiftAmt % BW.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MI</td>
<td class="doxyParamItemDescription"></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2904 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a4e3a2187cacdec76028617a403c47d89">llvm::APInt::urem</a>.</p>

</div>
</div>

### applyFunnelShiftToRotate() {#ad059815281df2717db5ad88dc3686a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyFunnelShiftToRotate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 627 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4400 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>.</p>

</div>
</div>

### applyNotCmp() {#a321f2dfbd709348cfd0e1ab66cf0b62c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyNotCmp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; RegsToNegate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3563 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af0d32d967ac31c4e6149c2adb89aa947">llvm::MachineOperand::getPredicate</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>, <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab1d6b6ca5842fa071bf1cb3510e1d0ba">llvm::MachineOperand::setPredicate</a>.</p>

</div>
</div>

### applyOptBrCondByInvertingCond() {#afa907eb6ba127a5f4167f5a1671efed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyOptBrCondByInvertingCond (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; BrCond)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1627 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4e1bd1414b3f2093861f8f48e7a10a7">llvm::getICmpTrueVal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a98e9c9e8ef7cbb6c4aa89a38f21decfa">llvm::MachineOperand::setMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a>.</p>

</div>
</div>

### applyPtrAddImmedChain() {#a8cd84da3b005d88c0f1b19d868e0a2b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyPtrAddImmedChain (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/ptraddchain">PtrAddChain</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1784 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/ptraddchain/#adad7ccdce66c8fd0d1b572fa88571131">llvm::PtrAddChain::Bank</a>, <a href="/web-llvm/docs/api/structs/llvm/ptraddchain/#a84f563cdcef6bdb8b6e834d28cf8c83b">llvm::PtrAddChain::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/ptraddchain/#a8b7d4fd0bd46a8e074b8ceb031cf6bd3">llvm::PtrAddChain::Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a> and <a href="#abefb646c754368c3ecc32c050c5bacd5">setRegBank</a>.</p>

</div>
</div>

### applyPtrAddZero() {#a0dbebc83f6114ab6cee672147800c858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyPtrAddZero (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3658 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### applyRotateOutOfRange() {#aaa191c1a15614a3cbf80f3eaf7ca935d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyRotateOutOfRange (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4427 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>.</p>

</div>
</div>

### applySDivByConst() {#a49d52b12000c2c069a30b9b22809385d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applySDivByConst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5483 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#af5d3388e53cb2767927dba7c18c64a00">buildSDivUsingMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a25ff4284ba96727747d6ceb7ef16b95d">replaceSingleDefInstWithReg</a>.</p>

</div>
</div>

### applySDivByPow2() {#a41cebcf8d37086a913f6a5424e0bff66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applySDivByPow2 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5566 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeafa582b26e8bdbe677ef62af7bad169">llvm::TargetLoweringBase::getPreferredShiftAmountTy</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a5360139c6b31d85cf3e29e2e6b7cf873">llvm::LLT::vector</a>.</p>

</div>
</div>

### applySextInRegOfLoad() {#a75ae99f242b3954f52d12c85e53d5f41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applySextInRegOfLoad (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, unsigned &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1098 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a130e12a0a8b3fe8149fe7b5eecfa603e">llvm::GMemOperation::getMMO</a>, <a href="/web-llvm/docs/api/classes/llvm/gloadstore/#a0a7fb170c5d3165c1a9f3cf5fee5b4ca">llvm::GLoadStore::getPointerReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### applySextTruncSextLoad() {#af2de464ca370d0adf592feedb983fce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applySextTruncSextLoad (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1040 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### applyShiftImmedChain() {#a6091fcf4f73ee6e61b585ff63df6b87d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyShiftImmedChain (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/registerimmpair">RegisterImmPair</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1842 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/structs/llvm/registerimmpair/#a15130db3b3cf5b29ae82d817f4ecdca1">llvm::RegisterImmPair::Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a> and <a href="/web-llvm/docs/api/structs/llvm/registerimmpair/#a0441320b16ae9242aca4afe9f8e511b3">llvm::RegisterImmPair::Reg</a>.</p>

</div>
</div>

### applyShiftOfShiftedLogic() {#ad8a483afeb99148394d2586c5601e441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyShiftOfShiftedLogic (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/shiftofshiftedlogic">ShiftOfShiftedLogic</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1955 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/structs/llvm/shiftofshiftedlogic/#afcbc9e3d4ba39f4e104617f01392eef2">llvm::ShiftOfShiftedLogic::Logic</a>, <a href="/web-llvm/docs/api/structs/llvm/shiftofshiftedlogic/#a69db2b80712fe86683e0290173e569df">llvm::ShiftOfShiftedLogic::LogicNonShiftReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/shiftofshiftedlogic/#aceed3102b5bba500aec69509b30af283">llvm::ShiftOfShiftedLogic::Shift2</a> and <a href="/web-llvm/docs/api/structs/llvm/shiftofshiftedlogic/#a51b38312d459bb759771b781f71279df">llvm::ShiftOfShiftedLogic::ValSum</a>.</p>

</div>
</div>

### applyShuffleToExtract() {#ae640b7329e9f881bfe0d4dc6bdddb642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyShuffleToExtract (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### applySimplifyAddToSub() {#a42edcf21dec07a1758316328df9216be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applySimplifyAddToSub (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3080 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### applySimplifyURemByPow2() {#a198b2e1185e6d3b4eb5e68283a4b504a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applySimplifyURemByPow2 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine G_UREM x, (known power of 2) to an add and bitmasking.</p>


<p>The second source operand is known to be a power of 2.</p>


<p>Declaration at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3665 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### applyUDivByConst() {#ad67f36800bff5506b51d7eaa3259cd01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyUDivByConst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5450 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#af3b3616540da1859ec9d030a76cad94f">buildUDivUsingMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a25ff4284ba96727747d6ceb7ef16b95d">replaceSingleDefInstWithReg</a>.</p>

</div>
</div>

### applyUDivByPow2() {#a4381e87d4240311eeff998ea33556263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyUDivByPow2 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an G_UDIV <span class="doxyComputerOutput">MI</span> expressing an unsigned divided by a pow2 constant, return expressions that implements it by shifting.</p>

<p>Declaration at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5625 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeafa582b26e8bdbe677ef62af7bad169">llvm::TargetLoweringBase::getPreferredShiftAmountTy</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### applyUMulHToLShr() {#a3012f3ba9714ad992670d388b7c70618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyUMulHToLShr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5655 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#afc84382af091d9a0de9586212e16a195">buildLogBase2</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeafa582b26e8bdbe677ef62af7bad169">llvm::TargetLoweringBase::getPreferredShiftAmountTy</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### applyUseVectorTruncate() {#a6cbfa42d7993571ddbfe46d0c37abafb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyUseVectorTruncate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3459 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a4f404daab6050b7a8e95bb247d4aefb2">llvm::LLT::changeElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### applyXorOfAndWithSameReg() {#a1cc3f78b3eded52f46e9f47c03a00934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::applyXorOfAndWithSameReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3626 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### buildSDivUsingMul() {#af5d3388e53cb2767927dba7c18c64a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * CombinerHelper::buildSDivUsingMul (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an G_SDIV <span class="doxyComputerOutput">MI</span> expressing a signed divide by constant, return an expression that implements it by multiplying by a magic number.</p>


<p>Ref: "Hacker's Delight" or "The PowerPC Compiler Writer's Guide".</p>


<p>Declaration at line 706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5488 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a7e30b3aa214eba50eed018b5b19fc6aa">llvm::APInt::ashrInPlace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b2430ab5e686b82f8cd6fd588d6de6f">llvm::getDefIgnoringCopies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af9fe220013bab6cfd9c7bb1be42477">llvm::getIConstantSplatVal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeafa582b26e8bdbe677ef62af7bad169">llvm::TargetLoweringBase::getPreferredShiftAmountTy</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a1a2592a2154d9272614c7d626f3dd991">llvm::MachineInstr::IsExact</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf4f84c8a910409d92dd85e2b72953">llvm::matchUnaryPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aba59baafccd4c4796301b857df3c40c6">llvm::APInt::multiplicativeInverse</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a49d52b12000c2c069a30b9b22809385d">applySDivByConst</a>.</p>

</div>
</div>

### buildUDivUsingMul() {#af3b3616540da1859ec9d030a76cad94f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * CombinerHelper::buildUDivUsingMul (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an G_UDIV <span class="doxyComputerOutput">MI</span> expressing a divide by constant, return an expression that implements it by multiplying by a magic number.</p>


<p>Ref: "Hacker's Delight" or "The PowerPC Compiler Writer's Guide".</p>


<p>Declaration at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5245 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8bad27827f46bca6baf814cbd2b64e84">llvm::APInt::countl_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo/#a6a7ecd0f6bb250280a31e56173931e31">llvm::UnsignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b2430ab5e686b82f8cd6fd588d6de6f">llvm::getDefIgnoringCopies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af9fe220013bab6cfd9c7bb1be42477">llvm::getIConstantSplatVal</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeafa582b26e8bdbe677ef62af7bad169">llvm::TargetLoweringBase::getPreferredShiftAmountTy</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo/#a1b8b2eee90075caf0407679fb780f5c9">llvm::UnsignedDivisionByConstantInfo::IsAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a1a2592a2154d9272614c7d626f3dd991">llvm::MachineInstr::IsExact</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aea5f26deda5ef97e02f6afc57c0c3920">llvm::APInt::isOne</a>, <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af338e23a90c301183968435e80cd6a27">llvm::APInt::lshrInPlace</a>, <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo/#a890b63a18fc3e328809c691b17c776ed">llvm::UnsignedDivisionByConstantInfo::Magic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf4f84c8a910409d92dd85e2b72953">llvm::matchUnaryPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aba59baafccd4c4796301b857df3c40c6">llvm::APInt::multiplicativeInverse</a>, <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo/#aadab71767738ad10ccb7600fa732fd96">llvm::UnsignedDivisionByConstantInfo::PostShift</a>, <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo/#a1fe2f52cb1640befcb5c3da7d3e37c6d">llvm::UnsignedDivisionByConstantInfo::PreShift</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="#ad67f36800bff5506b51d7eaa3259cd01">applyUDivByConst</a>.</p>

</div>
</div>

### canCombineFMadOrFMA() {#a1e388c06478515344e2fce08b1357025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::canCombineFMadOrFMA (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool &amp; AllowFusionGlobally, bool &amp; HasFMAD, bool &amp; Aggressive, bool CanReassociate=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5766 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fpopfusion/#a9c71bae9f02af273833fde586d529fc5aa9dfaae1f5b7d4ebb31ccf9aee1aacce">llvm::FPOpFusion::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a9a1da4c7c2a2a2ed0d083327dd28277c">llvm::MachineInstr::FmContract</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a7e452f6e23b696b4701cb18790b32992">llvm::MachineInstr::FmReassoc</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="#a7dd411f52d902c7964a59b0f317d3797">isPreLegalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="#a54d65481969f8d9628b5ee128c99212b">matchCombineFAddFMAFMulToFMadOrFMA</a>, <a href="#a5fbed34899e8c323d738ef2eac96dd20">matchCombineFAddFMulToFMadOrFMA</a>, <a href="#a246c328def50bbd9e892666ae3fb1947">matchCombineFAddFpExtFMulToFMadOrFMA</a>, <a href="#af73a2a8f01e0df7eb8908768292dd30e">matchCombineFAddFpExtFMulToFMadOrFMAAggressive</a>, <a href="#a541aab24d54889f539ea0e41c6a00b2c">matchCombineFSubFMulToFMadOrFMA</a>, <a href="#ade46635032e4ec34657bc9b237d37e0b">matchCombineFSubFNegFMulToFMadOrFMA</a>, <a href="#a4c9b7bf9027b6c116d92fbebd2ba8372">matchCombineFSubFpExtFMulToFMadOrFMA</a> and <a href="#ac4a2ebe747c416cbe4efb4b77ba2b588">matchCombineFSubFpExtFNegFMulToFMadOrFMA</a>.</p>

</div>
</div>

### dominates() {#ad99c8ee849f72738dd718fec8d3a1d42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">DefMI</span> dominates <span class="doxyComputerOutput">UseMI</span>.</p>


<p>By definition an instruction dominates itself.</p>


<p>If we haven't been provided with a <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> during construction, this function returns a conservative result that tracks just a single basic block.</p>


<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1001 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="#a3a9969db0d864227c6955d383a7bbe45">isPredecessor</a>, <a href="#acebc61bc26bf037e13a22af30d10b071">MDT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="#ac2377979438dcdab9e664ccd5f975dac">applyCombineDivRem</a>.</p>

</div>
</div>

### eraseInst() {#a9b5112859e14388fc8e391b7f7de26c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::eraseInst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erase <span class="doxyComputerOutput">MI</span>.</p>

<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2751 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ac91aca84eade26acea192464a9cfcde8">applyCombineTruncOfShift</a> and <a href="#a4ca173dc6e071e5c8c37b62f3d095eb5">applyFsubToFneg</a>.</p>

</div>
</div>

### getBuilder() {#acf32918c9574aee808e6234d1a2eace9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineIRBuilder &amp; llvm::CombinerHelper::getBuilder ()</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>


<p>Reference <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>.</p>

</div>
</div>

### getContext() {#a8c7d20188ce1e7c821f21c6a76f09df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; CombinerHelper::getContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>Reference <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>.</p>

</div>
</div>

### getDataLayout() {#a2d32dd5a2442e61e0904577f0d8369ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout &amp; CombinerHelper::getDataLayout ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a> and <a href="#af5d327beb13472a44f1999b5dfa79503">getMachineFunction</a>.</p>

</div>
</div>

### getKnownBits() {#a4ea850556148cb48cb6be849cd354e1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GISelKnownBits * llvm::CombinerHelper::getKnownBits ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>


<p>Reference <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>.</p>

</div>
</div>

### getMachineFunction() {#af5d327beb13472a44f1999b5dfa79503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction &amp; CombinerHelper::getMachineFunction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>Reference <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>.</p>


<p>Referenced by <a href="#a2d32dd5a2442e61e0904577f0d8369ce">getDataLayout</a>.</p>

</div>
</div>

### getRegBank() {#a0ae177a2136d1b90b767d57dbe6a419c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBank * CombinerHelper::getRegBank (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the register bank of <span class="doxyComputerOutput">Reg</span>.</p>


<p>If Reg has not been assigned a register, a register class, or a register bank, then this returns nullptr.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>Reg.isValid()</p></dd>
</dl>


<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="#ad388844fc6e8318b52ee7cf5a88b8c91">RBI</a> and <a href="#ad8de57b7e86580531aec66fde618bef2">TRI</a>.</p>


<p>Referenced by <a href="#a3acff99aeccfa086e7fbef44df8c0ce1">matchPtrAddImmedChain</a>.</p>

</div>
</div>

### getTargetLowering() {#a3ba5b820868b659a7cd5717894ee3459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering &amp; CombinerHelper::getTargetLowering ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>Reference <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>.</p>


<p>Referenced by <a href="#afa907eb6ba127a5f4167f5a1671efed0">applyOptBrCondByInvertingCond</a>, <a href="#a41cebcf8d37086a913f6a5424e0bff66">applySDivByPow2</a>, <a href="#a4381e87d4240311eeff998ea33556263">applyUDivByPow2</a>, <a href="#a3012f3ba9714ad992670d388b7c70618">applyUMulHToLShr</a>, <a href="#af5d3388e53cb2767927dba7c18c64a00">buildSDivUsingMul</a>, <a href="#af3b3616540da1859ec9d030a76cad94f">buildUDivUsingMul</a>, <a href="#aab92d16362139d524a7012e2d29c9821">matchBitfieldExtractFromAnd</a>, <a href="#aac1fd587d596fe9aeb38b219966ebd3c">matchBitfieldExtractFromSExtInReg</a>, <a href="#a16d6a69c22795ffc8819bc7bc0e1bae2">matchBitfieldExtractFromShr</a>, <a href="#aa6aaf27c1306e54d433cd45f84ee74e5">matchBitfieldExtractFromShrAnd</a>, <a href="#a28a0f1422b780a83a9632e5d46993dfc">matchCombineExtractedVectorLoad</a>, <a href="#a50d554a59b9df6a88b36ed551c6e7903">matchCombineShlOfExtend</a>, <a href="#adb530600a4235ed32fefcd44dbf454b4">matchCombineTruncOfShift</a>, <a href="#a0255cbf70d03b31784d719fb73637002">matchCommuteShift</a>, <a href="#a21a291953b9b99793faf8bea9286ebd7">matchExtractVecEltBuildVec</a>, <a href="#af7bcd2506b90a78c86a2ac061132783f">matchExtractVectorElementWithBuildVector</a>, <a href="#a2a97e27cc61249c732f88ca2b63ce73f">matchExtractVectorElementWithBuildVectorTrunc</a>, <a href="#afb504c8fdf12e04e71a4ea3f728ced62">matchFPowIExpansion</a>, <a href="#aab86990eacd037e1c72749c3342d410e">matchHoistLogicOpWithSameOpcodeHands</a>, <a href="#a79ff9815398a2c3331b42832035f21c6">matchICmpToLHSKnownBits</a>, <a href="#a98f00ea8e8ca7e8ce4888da5cb138b43">matchICmpToTrueFalseKnownBits</a>, <a href="#a070e7ae88917971c8b99b3bb7f3d5942">matchLoadOrCombine</a>, <a href="#a59e682863250eb07290a348d548eee0d">matchNarrowBinopFeedingAnd</a>, <a href="#a2f87fb73ebb3f5d6d7e49e99fa478fa3">matchNonNegZext</a>, <a href="#a23ff02c4dc0c7eb4bc173bc9af346765">matchSDivByConst</a>, <a href="#adc129334a6d3d83eb003dd1a49540f80">matchSuboCarryOut</a>, <a href="#a51f93c65cadd67241250f97598ab1358">matchUDivByConst</a>, <a href="#acd5de1d4698c082f674654d67b42f1ca">matchUMulHToLShr</a> and <a href="#a9a9739cf49c46adcb76ac7e2dc13545c">tryReassocBinOp</a>.</p>

</div>
</div>

### isConstantLegalOrBeforeLegalizer() {#a8d34744985da7b7a26c92f1b064851ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::isConstantLegalOrBeforeLegalizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the combine is running prior to legalization, or if <span class="doxyComputerOutput">Ty</span> is a legal integer constant type on the target.</p></dd>
</dl>


<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#a9569ff6b4f769cb7a667ad4a986589e8">isLegal</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a> and <a href="#a7dd411f52d902c7964a59b0f317d3797">isPreLegalize</a>.</p>


<p>Referenced by <a href="#ab46d848f3726829246738eb9d78aebf9">matchAddOverflow</a>, <a href="#aeb8af468cabe232d8d64944acf6930b7">matchCastOfInteger</a>, <a href="#a82dc058091aed201fb1fbdd0ab8e5c3d">matchCombineSubToAdd</a>, <a href="#a89092e8630095ccf5b948def71d884f1">matchExtractVectorElementWithShuffleVector</a>, <a href="#ad43afc169977548bbf11956b91156040">matchMulOBy0</a> and <a href="#adc129334a6d3d83eb003dd1a49540f80">matchSuboCarryOut</a>.</p>

</div>
</div>

### isLegal() {#a9569ff6b4f769cb7a667ad4a986589e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::isLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> &amp; Query)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">Query</span> is legal on the target.</p></dd>
</dl>


<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a167074ba3b742859ff5dbe464381e107">llvm::LegalizeActions::Legal</a> and <a href="#aca634f15887089866f5d88dac807786c">LI</a>.</p>


<p>Referenced by <a href="#a8d34744985da7b7a26c92f1b064851ea">isConstantLegalOrBeforeLegalizer</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="#a2e6e1c84d8b84dbd2101236bca332d95">matchSimplifyNegMinMax</a> and <a href="#a9e44e0e5bdc7526a1b299ae804752709">matchUseVectorTruncate</a>.</p>

</div>
</div>

### isLegalOrBeforeLegalizer() {#aa6528d48a17e668c9ba2c8786df9d64b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::isLegalOrBeforeLegalizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> &amp; Query)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the combine is running prior to legalization, or if <span class="doxyComputerOutput">Query</span> is legal on the target.</p></dd>
</dl>


<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#a9569ff6b4f769cb7a667ad4a986589e8">isLegal</a> and <a href="#a7dd411f52d902c7964a59b0f317d3797">isPreLegalize</a>.</p>


<p>Referenced by <a href="#a1e388c06478515344e2fce08b1357025">canCombineFMadOrFMA</a>, <a href="#a8d34744985da7b7a26c92f1b064851ea">isConstantLegalOrBeforeLegalizer</a>, <a href="#ab46d848f3726829246738eb9d78aebf9">matchAddOverflow</a>, <a href="#afe660eb45c9320803ef32f88757a79c7">matchAshrShlToSextInreg</a>, <a href="#ae88fdd4a40851c70c1f04282174034c2">matchCastOfBuildVector</a>, <a href="#afaeb891d2410d3aaf4d95fc61028f7b4">matchCastOfSelect</a>, <a href="#a84bf6a20255406e9c9f6a52f5c4c7b34">matchCombineConcatVectors</a>, <a href="#a2ea6814df78ae99e8a540fb4e8fc4ed1">matchCombineDivRem</a>, <a href="#a28a0f1422b780a83a9632e5d46993dfc">matchCombineExtractedVectorLoad</a>, <a href="#a5d600f23e7d301bfcf60b292eaba31ef">matchCombineLoadWithAndMask</a>, <a href="#a50d554a59b9df6a88b36ed551c6e7903">matchCombineShlOfExtend</a>, <a href="#a7474d0e2d570539a3e93b86c67b1bae9">matchCombineShuffleConcat</a>, <a href="#a82dc058091aed201fb1fbdd0ab8e5c3d">matchCombineSubToAdd</a>, <a href="#adb530600a4235ed32fefcd44dbf454b4">matchCombineTruncOfShift</a>, <a href="#a7b617a5a6a2773b70ea354e1dffceff7">matchExtOfExt</a>, <a href="#a4f83785782b043b22a617554b65b5f0a">matchExtractVectorElement</a>, <a href="#a2a97e27cc61249c732f88ca2b63ce73f">matchExtractVectorElementWithBuildVectorTrunc</a>, <a href="#a89092e8630095ccf5b948def71d884f1">matchExtractVectorElementWithShuffleVector</a>, <a href="#a6618ef11a5296a1388144d2fdae9f6e3">matchFunnelShiftToRotate</a>, <a href="#aab86990eacd037e1c72749c3342d410e">matchHoistLogicOpWithSameOpcodeHands</a>, <a href="#a79ff9815398a2c3331b42832035f21c6">matchICmpToLHSKnownBits</a>, <a href="#a4726b2a74fcb79e35ec78c54ec7aa8ee">matchInsertVectorElementOOB</a>, <a href="#a070e7ae88917971c8b99b3bb7f3d5942">matchLoadOrCombine</a>, <a href="#a65bdadc254b269b10b7e67d39a9527dc">matchMergeXAndUndef</a>, <a href="#a518e2853dfbfd37675a14b6bf1ca6c90">matchMergeXAndZero</a>, <a href="#aac58443a61bc007251b27585f5887c6d">matchNarrowBinop</a>, <a href="#a59e682863250eb07290a348d548eee0d">matchNarrowBinopFeedingAnd</a>, <a href="#a2f87fb73ebb3f5d6d7e49e99fa478fa3">matchNonNegZext</a>, <a href="#a3748ec69250bb09564362325c334c9ae">matchOrShiftToFunnelShift</a>, <a href="#a5cd94b9d480eadb598a5125b9b294efe">matchRedundantNegOperands</a>, <a href="#a9098323777f98b3dd53bef412554961c">matchSelectIMinMax</a>, <a href="#a8f5dd5583d12f1c7dcf63b86ff444394">matchSextInRegOfLoad</a>, <a href="#a5036ae118b8d8b9debc1c596eff93259">matchSextOfTrunc</a>, <a href="#a5b5001e37af42df3e8202151fe08b3c9">matchShlOfVScale</a>, <a href="#a6d345595bdc1655f01d68419353184cf">matchShuffleDisjointMask</a>, <a href="#adc129334a6d3d83eb003dd1a49540f80">matchSuboCarryOut</a>, <a href="#ac88c813e35b6d1a4966b0ee24a5c8b9a">matchSubOfVScale</a>, <a href="#a633b0486bab32c1b91cc923d82a72c2d">matchTruncateOfExt</a>, <a href="#a51f93c65cadd67241250f97598ab1358">matchUDivByConst</a>, <a href="#acd5de1d4698c082f674654d67b42f1ca">matchUMulHToLShr</a>, <a href="#a12794dfd41dd116d9e295524d932f6c0">matchUnmergeValuesAnyExtBuildVector</a> and <a href="#a27942d2942b84e3453b75e3417def841">matchZextOfTrunc</a>.</p>

</div>
</div>

### isPredecessor() {#a3a9969db0d864227c6955d383a7bbe45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::isPredecessor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">DefMI</span> precedes <span class="doxyComputerOutput">UseMI</span> or they are the same instruction.</p>


<p>Both must be in the same basic block.</p>


<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 985 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="#ad99c8ee849f72738dd718fec8d3a1d42">dominates</a>.</p>

</div>
</div>

### isPreLegalize() {#a7dd411f52d902c7964a59b0f317d3797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::isPreLegalize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the combiner is running pre-legalization.</p></dd>
</dl>


<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>Reference <a href="#a7baaf2859fea3988241fef9589a47557">IsPreLegalize</a>.</p>


<p>Referenced by <a href="#a1e388c06478515344e2fce08b1357025">canCombineFMadOrFMA</a>, <a href="#a8d34744985da7b7a26c92f1b064851ea">isConstantLegalOrBeforeLegalizer</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="#ab5ece2e19fefdc8f1112b05d6274e649">matchCombineExtendingLoads</a> and <a href="#a0255cbf70d03b31784d719fb73637002">matchCommuteShift</a>.</p>

</div>
</div>

### matchAddEToAddO() {#a15a55602a4ab55a9ae6ad194922d6f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchAddEToAddO (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match: (G_*ADDE x, y, 0) -&gt; (G_*ADDO x, y) (G_*SUBE x, y, 0) -&gt; (G_*SUBO x, y)</p>

<p>Declaration at line 744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5167 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a089b46c767dd14f714c3edbdce14f3f6">llvm::MIPatternMatch::m_SpecificICstOrSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>.</p>

</div>
</div>

### matchAddOfVScale() {#a597eabfac4d80feedf71d122bbaf4e00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchAddOfVScale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 942 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpervectorops-cpp">CombinerHelperVectorOps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gvscale/#a7c67c8f218bb124662af98cc5a846e98">llvm::GVScale::getSrc</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchAddOverflow() {#ab46d848f3726829246738eb9d78aebf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchAddOverflow (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine addos.</p>

<p>Declaration at line 889 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7412 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ac5a96896a96f880fbd295aec85a81a87a9ac50ff0c308dad407db9f09e418363e">llvm::ConstantRange::AlwaysOverflowsHigh</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ac5a96896a96f880fbd295aec85a81a87ac8cc76d76703c81c16e939be370683c1">llvm::ConstantRange::AlwaysOverflowsLow</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a211874a1535ba321cab61942cde9398f">llvm::ConstantRange::fromKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a33365204be9cb132de322e3713253b57">llvm::MachineInstr::getFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#a16344f792b3875c54ea12aaaa8adc790">llvm::GBinOp::getLHSReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#ab4382d9d406beb612f27cd7e036f5c47">llvm::GBinOp::getRHSReg</a>, <a href="#a8d34744985da7b7a26c92f1b064851ea">isConstantLegalOrBeforeLegalizer</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ac5a96896a96f880fbd295aec85a81a87ad4d9862eafa015a05101d9f662bb153a">llvm::ConstantRange::MayOverflow</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ac5a96896a96f880fbd295aec85a81a87a56624a95592b438e05ab500a6a200a03">llvm::ConstantRange::NeverOverflows</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518aefc960a99fa4cefc28a0ea76de0a0535">llvm::MachineInstr::NoSWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a16996c70759af20709e11bec0f30a14b">llvm::MachineInstr::NoUWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ab1e4a3ec7de159965bcee94fae9df74b">llvm::ConstantRange::signedAddMayOverflow</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a2bf71829dbcdadbd24d3c22814113ebf">llvm::ConstantRange::unsignedAddMayOverflow</a>.</p>

</div>
</div>

### matchAddSubSameReg() {#a5036bb5c5ecc303b0416937c6eb9d6e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchAddSubSameReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform G_ADD(x, G_SUB(y, x)) to y.</p>


<p>Transform G_ADD(G_SUB(y, x), x) to y.</p>


<p>Declaration at line 813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6342 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa5f3b8a0a9eb440cd96a96245e238eba">llvm::MIPatternMatch::m_GSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchAllExplicitUsesAreUndef() {#a36f9936f860062e89b32c9fdd84bfb08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchAllExplicitUsesAreUndef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all register explicit use operands on <span class="doxyComputerOutput">MI</span> are defined by a G_IMPLICIT_DEF.</p>

<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2698 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### matchAnd() {#adc0e07192feecf6c110017414a96fa2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchAnd (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine ands.</p>

<p>Declaration at line 876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7388 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### matchAndOrDisjointMask() {#aac73c9c9888dd26d04e2eeb87aca714c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchAndOrDisjointMask (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if (and (or x, c1), c2) can be replaced with (and x, c2)</p></dd>
</dl>


<p>Declaration at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4529 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ad168e9806711429475c916e9b0d521c1">llvm::MIPatternMatch::m_all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#abcba8f4496d7495913d7d6a845183349">llvm::MIPatternMatch::m_GAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a61adc0538bc40b2709040c5284c5c719">llvm::MIPatternMatch::m_GOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a441b9fc17e390be4c8dc6a1f1dd3d424">llvm::MIPatternMatch::m_ICst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>.</p>

</div>
</div>

### matchAnyExplicitUseIsUndef() {#a8239ce43cefa777d1911c575cd961b9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchAnyExplicitUseIsUndef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if any explicit use operand on <span class="doxyComputerOutput">MI</span> is defined by a G_IMPLICIT_DEF.</p>

<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2691 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### matchAshrShlToSextInreg() {#afe660eb45c9320803ef32f88757a79c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchAshrShlToSextInreg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, int64_t &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match ashr (shl x, C), C -&gt; sext_inreg (C)</p>

<p>Declaration at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa6f48e445e3b4dfc8016669ecd7a720d">llvm::MIPatternMatch::m_GAShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ab4c34955698e6d89ced0a74e2bb14667">llvm::MIPatternMatch::m_GShl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a68c2ea2a2e9814694f42f72d974e0f45">llvm::MIPatternMatch::m_ICstOrSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchBinOpSameVal() {#a2d378068adc2de015d79593557be7c37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchBinOpSameVal (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimize (x op x) -&gt; x.</p>

<p>Declaration at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2936 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a708b9606a37961be41adad607c81c532">llvm::canReplaceReg</a>, <a href="#a0f3bc0c5478dd84e0831b5d78a274b47">matchEqualDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchBitfieldExtractFromAnd() {#aab92d16362139d524a7012e2d29c9821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchBitfieldExtractFromAnd (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match: and (lshr x, cst), mask -&gt; ubfx x, cst, width.</p>


<p>Form a G_UBFX from "(a srl b) &amp; mask", where b and mask are constants.</p>


<p>Declaration at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4595 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeafa582b26e8bdbe677ef62af7bad169">llvm::TargetLoweringBase::getPreferredShiftAmountTy</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="#aca634f15887089866f5d88dac807786c">LI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchBitfieldExtractFromSExtInReg() {#aac1fd587d596fe9aeb38b219966ebd3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchBitfieldExtractFromSExtInReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Form a G_SBFX from a G_SEXT_INREG fed by a right shift.</p>

<p>Declaration at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4565 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeafa582b26e8bdbe677ef62af7bad169">llvm::TargetLoweringBase::getPreferredShiftAmountTy</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="#aca634f15887089866f5d88dac807786c">LI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchBitfieldExtractFromShr() {#a16d6a69c22795ffc8819bc7bc0e1bae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchBitfieldExtractFromShr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match: shr (shl x, n), k -&gt; sbfx/ubfx x, pos, width.</p>

<p>Declaration at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4632 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeafa582b26e8bdbe677ef62af7bad169">llvm::TargetLoweringBase::getPreferredShiftAmountTy</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="#aca634f15887089866f5d88dac807786c">LI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchBitfieldExtractFromShrAnd() {#aa6aaf27c1306e54d433cd45f84ee74e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchBitfieldExtractFromShrAnd (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match: shr (and x, n), k -&gt; ubfx x, pos, width.</p>

<p>Declaration at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4682 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeafa582b26e8bdbe677ef62af7bad169">llvm::TargetLoweringBase::getPreferredShiftAmountTy</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="#aca634f15887089866f5d88dac807786c">LI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchBuildVectorIdentityFold() {#aa654694a53f814ff3cb1b2d04513da6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchBuildVectorIdentityFold (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6358 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#abb0025cff9b34811f8ce06ff14d4702c">llvm::MIPatternMatch::m_any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#abe5d216582c8bd8e0159b91beaf9046c">llvm::MIPatternMatch::m_GBitcast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a187d1464e826697bd2e8fec623e5071e">llvm::MIPatternMatch::m_GBuildVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac2cf284cf0dcaa006e82de2b916139b5">llvm::MIPatternMatch::m_GBuildVectorTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a216c309718ce74c83d72308da142af26">llvm::MIPatternMatch::m_GCst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a7555ded58a860b9a592e545c4e3c0322">llvm::MIPatternMatch::m_GImplicitDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ad7baea71af036277e3c15cee5c21351e">llvm::MIPatternMatch::m_GLShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aeaad33cb0fd8ffab79aab1414253854d">llvm::MIPatternMatch::m_GTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCanonicalizeFCmp() {#a7c6878dbda903ec9201f83db42d93fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCanonicalizeFCmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercompares-cpp">CombinerHelperCompares.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/gfconstant/#a304cce739b194957211dc0de7b088475">llvm::GFConstant::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a66c10680694a0184d50e7a8c0d1ea874">llvm::CmpInst::isFPPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### matchCanonicalizeICmp() {#ae7e76e88a680a8f2de889a6f6928fcc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCanonicalizeICmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 979 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercompares-cpp">CombinerHelperCompares.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/giconstant/#a7c1afa567716fafdd041dfb85d7f3773">llvm::GIConstant::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ad8c2100cae3093d71e65a48908158e22">llvm::CmpInst::isIntPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### matchCastOfBuildVector() {#ae88fdd4a40851c70c1f04282174034c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCastOfBuildVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; CastMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; BVMI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 975 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercasts-cpp">CombinerHelperCasts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/gmergelikeinstr/#a90d314382626dec7379b4d2ec02b7a4b">llvm::GMergeLikeInstr::getNumSources</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### matchCastOfInteger() {#aeb8af468cabe232d8d64944acf6930b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCastOfInteger (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; CastMI, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 886 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercasts-cpp">CombinerHelperCasts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6360a4c9f501f8ee60be165a4c9de7da">llvm::getIConstantFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/gcastop/#afd9f4526a055452535916c9c12810415">llvm::GCastOp::getSrcReg</a>, <a href="#a8d34744985da7b7a26c92f1b064851ea">isConstantLegalOrBeforeLegalizer</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCastOfSelect() {#afaeb891d2410d3aaf4d95fc61028f7b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCastOfSelect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Cast, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; SelectMI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 954 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercasts-cpp">CombinerHelperCasts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select</a>.</p>

</div>
</div>

### matchCombineAddP2IToPtrAdd() {#a642669b9384277a3f5fc513928d6bee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineAddP2IToPtrAdd (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, bool &gt; &amp; PtrRegAndCommute)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform G_ADD (G_PTRTOINT x), y -&gt; G_PTRTOINT (G_PTR_ADD x, y) Transform G_ADD y, (G_PTRTOINT x) -&gt; G_PTRTOINT (G_PTR_ADD x, y)</p>

<p>Declaration at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2487 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa1b47a718493d1b5ecdcfe7dd2d37000">llvm::MIPatternMatch::m_GPtrToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCombineAnyExtTrunc() {#aebbd8556be493cfb10fce51e933d7e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineAnyExtTrunc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform anyext(trunc(x)) to x.</p>

<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2560 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb39eef3d8e7cf19a9145c51a5e46253">llvm::getSrcRegIgnoringCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ad168e9806711429475c916e9b0d521c1">llvm::MIPatternMatch::m_all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aeaad33cb0fd8ffab79aab1414253854d">llvm::MIPatternMatch::m_GTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a7d91389d8f0afaf92996d2939202e87d">llvm::MIPatternMatch::m_SpecificType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCombineConcatVectors() {#a84bf6a20255406e9c9f6a52f5c4c7b34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineConcatVectors (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If <span class="doxyComputerOutput">MI</span> is G_CONCAT_VECTORS, try to combine it.</p>


<p>Returns true if MI changed. Right now, we support:</p>


<ul class="doxyList ">
<li>concat_vector(undef, undef) =&gt; undef</li>
<li>concat_vector(build_vector(A, B), build_vector(C, D)) =&gt;</li>
</ul>

## build\_vector(A, B, C, D) {#autotoc_md9}


<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the G_CONCAT_VECTORS <span class="doxyComputerOutput">MI</span> is undef or if it can be flattened into a build_vector. In the first case <span class="doxyComputerOutput">Ops</span> will be empty In the second case <span class="doxyComputerOutput">Ops</span> will contain the operands needed to produce the flattened build_vector.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI.getOpcode() == G_CONCAT_VECTORS.</p></dd>
</dl>


<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCombineConstPtrAddToI2P() {#a6fd6113581071d7d586e82cf3454bc9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineConstPtrAddToI2P (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; NewCst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2530 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19cdd6010b754ac90ebda5990b03cb40">llvm::getIConstantVRegVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a50bdc14d3225a415476d72caf456ae6c">llvm::MIPatternMatch::m_GIntToPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a441b9fc17e390be4c8dc6a1f1dd3d424">llvm::MIPatternMatch::m_ICst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a9b5fc98b47d44d1150d3610bdfab1430">llvm::APInt::sextOrTrunc</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a2ed912a28808268e35bd58e8f11251aa">llvm::APInt::zextOrTrunc</a>.</p>

</div>
</div>

### matchCombineCopy() {#a5fc01df6a11c709c2e05f5ef212d239d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineCopy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a708b9606a37961be41adad607c81c532">llvm::canReplaceReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>


<p>Referenced by <a href="#a77695e2fac4d7c37fd43e1d9a55e69ce">tryCombineCopy</a>.</p>

</div>
</div>

### matchCombineDivRem() {#a2ea6814df78ae99e8a540fb4e8fc4ed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineDivRem (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; OtherMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to combine G_[SU]DIV and G_[SU]REM into a single G_[SU]DIVREM when their source operands are identical.</p>

<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1498 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a0f3bc0c5478dd84e0831b5d78a274b47">matchEqualDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>

</div>
</div>

### matchCombineExtendingLoads() {#ab5ece2e19fefdc8f1112b05d6274e649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineExtendingLoads (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/preferredtuple">PreferredTuple</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/ganyload/#a4fe5ff0257f5b8749cbe223b848b2570">llvm::GAnyLoad::getDstReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#ab8a8668cff59b4eb557f0a7427cbe7bd">getExtLoadOpcForExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a130e12a0a8b3fe8149fe7b5eecfa603e">llvm::GMemOperation::getMMO</a>, <a href="/web-llvm/docs/api/classes/llvm/gloadstore/#a0a7fb170c5d3165c1a9f3cf5fee5b4ca">llvm::GLoadStore::getPointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a617c1c04cfa1325ad04eb69339d92188">llvm::has_single_bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a7dd411f52d902c7964a59b0f317d3797">isPreLegalize</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a167074ba3b742859ff5dbe464381e107">llvm::LegalizeActions::Legal</a>, <a href="#aca634f15887089866f5d88dac807786c">LI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="#aa57157299174e74145361548452e45f9">tryCombineExtendingLoads</a>.</p>

</div>
</div>

### matchCombineExtractedVectorLoad() {#a28a0f1422b780a83a9632e5d46993dfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineExtractedVectorLoad (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine a G_EXTRACT_VECTOR_ELT of a load into a narrowed load.</p>

<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1340 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd6aa057934751aaac54e5c18bcc18eb">llvm::commonAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a2788ec4ff3130471e24ab77dc08f7c50">llvm::MachinePointerInfo::getAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#abc15369ab4cc583332950b913e2ef1dd">llvm::MachineMemOperand::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19cdd6010b754ac90ebda5990b03cb40">llvm::getIConstantVRegVal</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaf6610b5b6565e4f1b56ca78c804654f">llvm::MachineMemOperand::getPointerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae91b4ff9d9c084c672f78adb9ed4006a">llvm::LegalizerHelper::getVectorElementPointer</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a9459055a98e20980521289e8d20fcc7e">llvm::MachinePointerInfo::getWithOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a8b8f5d788ec31cd57f429ce38b5e3bb7">llvm::LLT::isByteSized</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>

</div>
</div>

### matchCombineFAddFMAFMulToFMadOrFMA() {#a54d65481969f8d9628b5ee128c99212b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineFAddFMAFMulToFMadOrFMA (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform (fadd (fma x, y, (fmul u, v)), z) -&gt; (fma x, y, (fma u, v, z)) (fadd (fmad x, y, (fmul u, v)), z) -&gt; (fmad x, y, (fmad u, v, z))</p>

<p>Declaration at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5908 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a1e388c06478515344e2fce08b1357025">canCombineFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a3454a39a1e2c87adcca0ddf016f3ca20">hasMoreUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a44a6db3c826e566b50481c059c3b857e">isContractableFMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### matchCombineFAddFMulToFMadOrFMA() {#a5fbed34899e8c323d738ef2eac96dd20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineFAddFMulToFMadOrFMA (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform (fadd (fmul x, y), z) -&gt; (fma x, y, z) (fadd (fmul x, y), z) -&gt; (fmad x, y, z)</p>

<p>Declaration at line 764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5799 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a1e388c06478515344e2fce08b1357025">canCombineFMadOrFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a3454a39a1e2c87adcca0ddf016f3ca20">hasMoreUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a44a6db3c826e566b50481c059c3b857e">isContractableFMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### matchCombineFAddFpExtFMulToFMadOrFMA() {#a246c328def50bbd9e892666ae3fb1947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineFAddFpExtFMulToFMadOrFMA (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform (fadd (fpext (fmul x, y)), z) -&gt; (fma (fpext x), (fpext y), z) (fadd (fpext (fmul x, y)), z) -&gt; (fmad (fpext x), (fpext y), z)</p>

<p>Declaration at line 769 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5848 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a1e388c06478515344e2fce08b1357025">canCombineFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a3454a39a1e2c87adcca0ddf016f3ca20">hasMoreUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a44a6db3c826e566b50481c059c3b857e">isContractableFMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a3845794785db2b22c759f4cb7dbdd509">llvm::MIPatternMatch::m_GFPExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac48bb7526cd273b2dbeaabdc481d641f">llvm::MIPatternMatch::m_MInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### matchCombineFAddFpExtFMulToFMadOrFMAAggressive() {#af73a2a8f01e0df7eb8908768292dd30e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineFAddFpExtFMulToFMadOrFMAAggressive (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5974 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a1e388c06478515344e2fce08b1357025">canCombineFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a3454a39a1e2c87adcca0ddf016f3ca20">hasMoreUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a44a6db3c826e566b50481c059c3b857e">isContractableFMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a3845794785db2b22c759f4cb7dbdd509">llvm::MIPatternMatch::m_GFPExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac48bb7526cd273b2dbeaabdc481d641f">llvm::MIPatternMatch::m_MInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### matchCombineFMinMaxNaN() {#ac31ecf657d06f3e6f617cd4d6e035f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineFMinMaxNaN (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6314 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1175ca529ece1df77d922f75a8726f56">llvm::getConstantFPVRegVal</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a763d4ccd87f2c21d2079796c0c9cd51a">llvm::APFloat::isNaN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCombineFSubFMulToFMadOrFMA() {#a541aab24d54889f539ea0e41c6a00b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineFSubFMulToFMadOrFMA (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform (fsub (fmul x, y), z) -&gt; (fma x, y, -z) (fsub (fmul x, y), z) -&gt; (fmad x, y, -z)</p>

<p>Declaration at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a1e388c06478515344e2fce08b1357025">canCombineFMadOrFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a3454a39a1e2c87adcca0ddf016f3ca20">hasMoreUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a44a6db3c826e566b50481c059c3b857e">isContractableFMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCombineFSubFNegFMulToFMadOrFMA() {#ade46635032e4ec34657bc9b237d37e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineFSubFNegFMulToFMadOrFMA (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform (fsub (fneg (fmul, x, y)), z) -&gt; (fma (fneg x), y, (fneg z)) (fsub (fneg (fmul, x, y)), z) -&gt; (fmad (fneg x), y, (fneg z))</p>

<p>Declaration at line 792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a1e388c06478515344e2fce08b1357025">canCombineFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a44a6db3c826e566b50481c059c3b857e">isContractableFMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac58f55029dff0a1026f13b8b5ee80338">llvm::MIPatternMatch::m_GFNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac48bb7526cd273b2dbeaabdc481d641f">llvm::MIPatternMatch::m_MInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCombineFSubFpExtFMulToFMadOrFMA() {#a4c9b7bf9027b6c116d92fbebd2ba8372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineFSubFpExtFMulToFMadOrFMA (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform (fsub (fpext (fmul x, y)), z) -&gt; (fma (fpext x), (fpext y), (fneg z)) (fsub (fpext (fmul x, y)), z) -&gt; (fmad (fpext x), (fpext y), (fneg z))</p>

<p>Declaration at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a1e388c06478515344e2fce08b1357025">canCombineFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a44a6db3c826e566b50481c059c3b857e">isContractableFMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a3845794785db2b22c759f4cb7dbdd509">llvm::MIPatternMatch::m_GFPExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac48bb7526cd273b2dbeaabdc481d641f">llvm::MIPatternMatch::m_MInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCombineFSubFpExtFNegFMulToFMadOrFMA() {#ac4a2ebe747c416cbe4efb4b77ba2b588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineFSubFpExtFNegFMulToFMadOrFMA (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform (fsub (fpext (fneg (fmul x, y))), z) -&gt; (fneg (fma (fpext x), (fpext y), z)) (fsub (fpext (fneg (fmul x, y))), z) -&gt; (fneg (fmad (fpext x), (fpext y), z))</p>

<p>Declaration at line 806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6254 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a1e388c06478515344e2fce08b1357025">canCombineFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a44a6db3c826e566b50481c059c3b857e">isContractableFMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac58f55029dff0a1026f13b8b5ee80338">llvm::MIPatternMatch::m_GFNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a3845794785db2b22c759f4cb7dbdd509">llvm::MIPatternMatch::m_GFPExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac48bb7526cd273b2dbeaabdc481d641f">llvm::MIPatternMatch::m_MInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### matchCombineI2PToP2I() {#a8269c100cbd38131124eb3c261193bfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineI2PToP2I (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform IntToPtr(PtrToInt(x)) to x if cast is in the same address space.</p>

<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2461 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ad168e9806711429475c916e9b0d521c1">llvm::MIPatternMatch::m_all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa1b47a718493d1b5ecdcfe7dd2d37000">llvm::MIPatternMatch::m_GPtrToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a7d91389d8f0afaf92996d2939202e87d">llvm::MIPatternMatch::m_SpecificType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCombineIndexedLoadStore() {#a2591ea6476cd4c80dd7f0fc9be1d3d74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineIndexedLoadStore (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/indexedloadstorematchinfo">IndexedLoadStoreMatchInfo</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1446 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/indexedloadstorematchinfo/#a97bfd306dc51ab54572e11569722c1db">llvm::IndexedLoadStoreMatchInfo::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/indexedloadstorematchinfo/#a3328011280e1c30771b17c673aa50214">llvm::IndexedLoadStoreMatchInfo::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a9c309120c87f6a16704169f193bfc711">llvm::GMemOperation::isAtomic</a>, <a href="/web-llvm/docs/api/structs/llvm/indexedloadstorematchinfo/#a5e77493a41515a3d61869442c23a9085">llvm::IndexedLoadStoreMatchInfo::IsPre</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/indexedloadstorematchinfo/#a38e02f76019824d6efeb1362c85d1b00">llvm::IndexedLoadStoreMatchInfo::Offset</a> and <a href="/web-llvm/docs/api/structs/llvm/indexedloadstorematchinfo/#a188df9024d6812274403b293cbc7117b">llvm::IndexedLoadStoreMatchInfo::RematOffset</a>.</p>

</div>
</div>

### matchCombineInsertVecElts() {#a570b6dfed72efec6554e992d5afdd1e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineInsertVecElts (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3015 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3016e0f01ad96a198f81f74397b1c0e6">llvm::LLT::isScalableVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#acdfbe64f01ed402d968cecad283b215b">llvm::MIPatternMatch::m_GInsertVecElt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a441b9fc17e390be4c8dc6a1f1dd3d424">llvm::MIPatternMatch::m_ICst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac48bb7526cd273b2dbeaabdc481d641f">llvm::MIPatternMatch::m_MInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>.</p>

</div>
</div>

### matchCombineLoadWithAndMask() {#a5d600f23e7d301bfcf60b292eaba31ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineLoadWithAndMask (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match (and (load x), mask) -&gt; zextload x.</p>

<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 903 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af34a543ce8585d04c1ae22c78b3182dd">llvm::APInt::countr_one</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ganyload/#a4fe5ff0257f5b8749cbe223b848b2570">llvm::GAnyLoad::getDstReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#ac815a03646b3fcf26176feb2c669fb9e">llvm::GMemOperation::getMemSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a130e12a0a8b3fe8149fe7b5eecfa603e">llvm::GMemOperation::getMMO</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaf6610b5b6565e4f1b56ca78c804654f">llvm::MachineMemOperand::getPointerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/gloadstore/#a0a7fb170c5d3165c1a9f3cf5fee5b4ca">llvm::GLoadStore::getPointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac328c5d387ddf7d4a02afe9b669723c7">llvm::APInt::isMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#ae8c1a69379306b47f0302688d3427b60">llvm::GMemOperation::isSimple</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/memdesc/#a0f8389b50b7b92aaeb7f78099b1b531a">llvm::LegalityQuery::MemDesc::MemoryTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a9c374320ed4e895f9afa199987182bd2">RegSize</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### matchCombineMergeUnmerge() {#a5709dda6e8778748a5159cb8ed2d37f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineMergeUnmerge (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fold away a merge of an unmerge of the corresponding values.</p>

<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600clausemergepass-cpp/#aba99928790de45fa7aa12b47fbd828ff">Merge</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### matchCombineMulToShl() {#a6f6d05c3170477dae214b4f7ec6dc3fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineMulToShl (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned &amp; ShiftVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform a multiply by a power-of-2 value to a left shift.</p>

<p>Declaration at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2030 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCombineShiftToUnmerge() {#adb9e9ab4728e40478a30f57d57508f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineShiftToUnmerge (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TargetShiftSize, unsigned &amp; ShiftVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reduce a shift by a constant to an unmerge and a shift on a half sized type.</p>


<p>This will not produce a shift smaller than <span class="doxyComputerOutput">TargetShiftSize</span>.</p>


<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2353 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#aa3f99a0f1d4b4f20f945a7cc8f7e1d65">tryCombineShiftToUnmerge</a>.</p>

</div>
</div>

### matchCombineShlOfExtend() {#a50d554a59b9df6a88b36ed551c6e7903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineShlOfExtend (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/registerimmpair">RegisterImmPair</a> &amp; MatchData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2082 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeafa582b26e8bdbe677ef62af7bad169">llvm::TargetLoweringBase::getPreferredShiftAmountTy</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/structs/llvm/registerimmpair/#a15130db3b3cf5b29ae82d817f4ecdca1">llvm::RegisterImmPair::Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a496914f81c80c3adc8866dec3586859d">llvm::isConstantOrConstantSplatVector</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="#aca634f15887089866f5d88dac807786c">LI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ad93cf713aceed1711ddd0ccbe62c8277">llvm::MIPatternMatch::m_GAnyExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a32dcb8cba57833770e79dfe2fd395b49">llvm::MIPatternMatch::m_GSExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a2e06342dcfb65c2c40e4121eb688d4df">llvm::MIPatternMatch::m_GZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/structs/llvm/registerimmpair/#a0441320b16ae9242aca4afe9f8e511b3">llvm::RegisterImmPair::Reg</a>.</p>

</div>
</div>

### matchCombineShuffleConcat() {#a7474d0e2d570539a3e93b86c67b1bae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineShuffleConcat (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCombineShuffleVector() {#a620917cb45d142b76b1eb2dcd76ce689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineShuffleVector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the G_SHUFFLE_VECTOR <span class="doxyComputerOutput">MI</span> can be replaced by a concat_vectors.</p>


<p><span class="doxyComputerOutput">Ops</span> will contain the operands needed to produce the flattened concat_vectors.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI.getOpcode() == G_SHUFFLE_VECTOR.</p></dd>
</dl>


<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>


<p>Referenced by <a href="#aa9de7f911f64078bdbf773007dc10997">tryCombineShuffleVector</a>.</p>

</div>
</div>

### matchCombineSubToAdd() {#a82dc058091aed201fb1fbdd0ab8e5c3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineSubToAdd (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2056 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6360a4c9f501f8ee60be165a4c9de7da">llvm::getIConstantFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#ab4382d9d406beb612f27cd7e036f5c47">llvm::GBinOp::getRHSReg</a>, <a href="#a8d34744985da7b7a26c92f1b064851ea">isConstantLegalOrBeforeLegalizer</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a16996c70759af20709e11bec0f30a14b">llvm::MachineInstr::NoUWrap</a> and <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>.</p>

</div>
</div>

### matchCombineTruncOfShift() {#adb530600a4235ed32fefcd44dbf454b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineTruncOfShift (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform trunc (shl x, K) to shl (trunc x), K if K &lt; VT.getScalarSizeInBits().</p>


<p>Transforms trunc ([al]shr x, K) to (trunc ([al]shr (MidVT (trunc x)), K)) if K &lt;= (MidVT.getScalarSizeInBits() - VT.getScalarSizeInBits()) MidVT is obtained by finding a legal type between the trunc's src and dst types.</p>


<p>Declaration at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2605 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b2430ab5e686b82f8cd6fd588d6de6f">llvm::getDefIgnoringCopies</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a825476b2436eb817b735fdd34ee521c4">llvm::KnownBits::getMaxValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#ad38e4c590871c5419bce5648dd9a79e4">getMidVTForTruncRightShiftCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a46a7cbf3724080a5f4f4c7e7a4551e26">llvm::APInt::ugt</a>.</p>

</div>
</div>

### matchCombineUnmergeConstant() {#ad593882fdec13fdc1832fa224050666e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineUnmergeConstant (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; &amp; Csts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform G_UNMERGE <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> -&gt; Constant1, Constant2, ...</p>

<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2217 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a29e05cd075864928ae65e1751fdc346e">llvm::MachineOperand::getCImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aee59c647052fc9557561e596681da3c0">llvm::MachineOperand::getFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#af7e1934ed72a405ef073ea5f9bbe828e">llvm::ConstantInt::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af34549c39d6f741fbdaf9a795aa306e9">llvm::APInt::lshr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a>.</p>

</div>
</div>

### matchCombineUnmergeMergeToPlainValues() {#afc1c60085dd818c0586c87f44db3d10a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineUnmergeMergeToPlainValues (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform &lt;ty,...&gt; G_UNMERGE(G_MERGE ty X, Y, Z) -&gt; ty X, Y, Z.</p>

<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2162 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a78ed4247b51cb6ffdaedcc1ff8730246">peekThroughBitcast</a>.</p>

</div>
</div>

### matchCombineUnmergeUndef() {#a6fd7ed1e4ed0a6d0414dde08a4ef6935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineUnmergeUndef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp;)&gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform G_UNMERGE G_IMPLICIT_DEF -&gt; G_IMPLICIT_DEF, G_IMPLICIT_DEF, ...</p>

<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCombineUnmergeWithDeadLanesToTrunc() {#abb7390ce20d98328a9fb3b2fe779e164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineUnmergeWithDeadLanesToTrunc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform X, Y&lt;dead&gt; = G_UNMERGE Z -&gt; X = G_TRUNC Z.</p>

<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCombineUnmergeZExtToZExt() {#a19db4f1b27ef7d29e4c77f6f7dd0ec5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineUnmergeZExtToZExt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform X, Y = G_UNMERGE(G_ZEXT(Z)) -&gt; X = G_ZEXT(Z); Y = G_CONSTANT 0.</p>

<p>Declaration at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2295 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a2e06342dcfb65c2c40e4121eb688d4df">llvm::MIPatternMatch::m_GZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCombineZextTrunc() {#ade65624657027af925c73882186d00ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCombineZextTrunc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform zext(trunc(x)) to x.</p>

<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2573 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ad168e9806711429475c916e9b0d521c1">llvm::MIPatternMatch::m_all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aeaad33cb0fd8ffab79aab1414253854d">llvm::MIPatternMatch::m_GTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a7d91389d8f0afaf92996d2939202e87d">llvm::MIPatternMatch::m_SpecificType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCommuteConstantToRHS() {#a2b4c477b0ac10183266094734941f417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCommuteConstantToRHS (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match constant LHS ops that should be commuted.</p>

<p>Declaration at line 849 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6648 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a19cdd6010b754ac90ebda5990b03cb40">llvm::getIConstantVRegVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCommuteFPConstantToRHS() {#ac1285dc5bae6f80f64a0d757b136279d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCommuteFPConstantToRHS (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match constant LHS FP ops that should be commuted.</p>

<p>Declaration at line 861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6678 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ace1b96fff8a24df9e58d0b302e3a840e">llvm::MIPatternMatch::m_GFCstOrSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchCommuteShift() {#a0255cbf70d03b31784d719fb73637002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchCommuteShift (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1994 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="#a7dd411f52d902c7964a59b0f317d3797">isPreLegalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#abb0025cff9b34811f8ce06ff14d4702c">llvm::MIPatternMatch::m_any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a5a165ce6b90fa37c5cec47d02e329748">llvm::MIPatternMatch::m_GAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a61adc0538bc40b2709040c5284c5c719">llvm::MIPatternMatch::m_GOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a68c2ea2a2e9814694f42f72d974e0f45">llvm::MIPatternMatch::m_ICstOrSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a77620b0effc4f10230daef6ae22f5175">llvm::MIPatternMatch::m_OneNonDBGUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### matchConstantFoldBinOp() {#a12106e55b2bdb2132757797665813f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchConstantFoldBinOp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do constant folding when opportunities are exposed after MIR building.</p>

<p>Declaration at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4990 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a59a7ed1e5bfd8f5d0c66a7346ee5f87b">llvm::ConstantFoldBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchConstantFoldCastOp() {#aa8ae6cc9d1541ff2e91dd25d1da665d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchConstantFoldCastOp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do constant folding when opportunities are exposed after MIR building.</p>

<p>Declaration at line 680 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4977 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9d47901be0242bad9d2e085c3e9e73fe">llvm::ConstantFoldCastOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchConstantFoldFMA() {#add44d478a1c329e77659000039f6ae74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchConstantFoldFMA (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> *&amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> fold G_FMA/G_FMAD.</p>

<p>Declaration at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5013 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9180d9a8c1fc9693c4b0a50937e904e6">llvm::APFloat::fusedMultiplyAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1175ca529ece1df77d922f75a8726f56">llvm::getConstantFPVRegVal</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>.</p>

</div>
</div>

### matchConstantFoldFPBinOp() {#a9ba3e97ad5883fd02115afb289d2ccdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchConstantFoldFPBinOp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> *&amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do constant FP folding when opportunities are exposed after MIR building.</p>

<p>Declaration at line 686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5001 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2664741ca8fa0d154ef9e738aef0db7b">llvm::ConstantFoldFPBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchConstantFPOp() {#aa1cd7c807d2387bd9f8efe4a88cf1eb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchConstantFPOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MOP, double C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">MOP</span> is defined by a G_FCONSTANT or splat with a value exactly equal to <span class="doxyComputerOutput">C</span>.</p>

<p>Declaration at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2860 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ace1b96fff8a24df9e58d0b302e3a840e">llvm::MIPatternMatch::m_GFCstOrSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchConstantLargerBitWidth() {#a4cc9ea97355c96a953b9a6fc5ce2fcc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchConstantLargerBitWidth (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned ConstIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if constant at <span class="doxyComputerOutput">ConstIdx</span> is larger than <span class="doxyComputerOutput">MI</span> 's bitwidth.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ConstIdx</td>
<td class="doxyParamItemDescription"><p>Index of the constant</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2890 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchConstantOp() {#ac975f07f5ebdceac6c93312485b74af2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchConstantOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MOP, int64_t C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">MOP</span> is defined by a G_CONSTANT or splat with a value equal to <span class="doxyComputerOutput">C</span>.</p>

<p>Declaration at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2850 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a496914f81c80c3adc8866dec3586859d">llvm::isConstantOrConstantSplatVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>


<p>Referenced by <a href="#a67c4ed813faad031bd68547fc3b51244">matchOperandIsZero</a>.</p>

</div>
</div>

### matchConstantSelectCmp() {#abf78ec9a89c8134a3b9b6212184214fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchConstantSelectCmp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned &amp; OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if a G_SELECT instruction <span class="doxyComputerOutput">MI</span> has a constant comparison.</p>


<p>If true, <span class="doxyComputerOutput">OpIdx</span> will store the operand index of the known selected value.</p>


<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2740 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/gselect/#a6ef78494a917cd68f35d479588ec82dc">llvm::GSelect::getCondReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a496914f81c80c3adc8866dec3586859d">llvm::isConstantOrConstantSplatVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchDivByPow2() {#a575d0877b1d93fc6c416bf667876fb75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchDivByPow2 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an G_SDIV <span class="doxyComputerOutput">MI</span> expressing a signed divided by a pow2 constant, return expressions that implements it by shifting.</p>

<p>Declaration at line 712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5552 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf4f84c8a910409d92dd85e2b72953">llvm::matchUnaryPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchEqualDefs() {#a0f3bc0c5478dd84e0831b5d78a274b47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchEqualDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MOP1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MOP2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">MOP1</span> and <span class="doxyComputerOutput">MOP2</span> are register operands are defined by equivalent instructions.</p>

<p>Declaration at line 482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2753 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aeeed341d0f3c7220d070d766e3a0f584">llvm::MachineInstr::findRegisterDefOperandIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#accc8c4eb3eb2c7b4ceff04fc9a63c9da">llvm::getDefSrcRegIgnoringCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#ac815a03646b3fcf26176feb2c669fb9e">llvm::GMemOperation::getMemSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a2626405eab33f6bae29077772fd63115">llvm::MachineInstr::isDereferenceableInvariantLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a17f5d15a7320dec2cfefb6617f711ab7">llvm::MachineInstr::mayLoadOrStore</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>


<p>Referenced by <a href="#a2d378068adc2de015d79593557be7c37">matchBinOpSameVal</a>, <a href="#a2ea6814df78ae99e8a540fb4e8fc4ed1">matchCombineDivRem</a>, <a href="#aab86990eacd037e1c72749c3342d410e">matchHoistLogicOpWithSameOpcodeHands</a> and <a href="#a1561c4d75b24c0c46dcb05c8ec0bda65">matchSelectSameVal</a>.</p>

</div>
</div>

### matchExtendThroughPhis() {#a5fd133d3cc0d8e1b33fe7ae34657d45c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchExtendThroughPhis (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; ExtMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b2430ab5e686b82f8cd6fd588d6de6f">llvm::getDefIgnoringCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>.</p>

</div>
</div>

### matchExtOfExt() {#a7b617a5a6a2773b70ea354e1dffceff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchExtOfExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; FirstMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; SecondMI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 972 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercasts-cpp">CombinerHelperCasts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a33365204be9cb132de322e3713253b57">llvm::MachineInstr::getFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gcastop/#afd9f4526a055452535916c9c12810415">llvm::GCastOp::getSrcReg</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a75967179a013c48b7d5b1690cb0b47cc">llvm::MachineInstr::NoFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a3453657a772c3023f6ef942525db0d5d">llvm::MachineInstr::NonNeg</a>.</p>

</div>
</div>

### matchExtractAllEltsFromBuildVector() {#a8bd2bb9d716a15d8d914b0236e32e2ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchExtractAllEltsFromBuildVector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4267 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a8cfcd92a373cdd7deefb939dd76b83e3">llvm::SmallBitVector::all</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19cdd6010b754ac90ebda5990b03cb40">llvm::getIConstantVRegVal</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a18e2d7efe05987370dc6b5c54797fcf5">llvm::SmallBitVector::set</a>.</p>

</div>
</div>

### matchExtractVecEltBuildVec() {#a21a291953b9b99793faf8bea9286ebd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchExtractVecEltBuildVec (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4214 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38d317b55a165bcddde7bb58ab7b12f3">llvm::getMVTForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchExtractVectorElement() {#a4f83785782b043b22a617554b65b5f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchExtractVectorElement (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine extract vector element.</p>

<p>Declaration at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpervectorops-cpp">CombinerHelperVectorOps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractvectorelement/#ad8f4a9eb24c60d6e6d0102d17ae180ae">llvm::GExtractVectorElement::getIndexReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractvectorelement/#a9bdb58d595df6f79845de5cf0139ad8c">llvm::GExtractVectorElement::getVectorReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ad1db89614d919436714d099c99ff12a0">llvm::LLT::isFixedVector</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>

</div>
</div>

### matchExtractVectorElementWithBuildVector() {#af7bcd2506b90a78c86a2ac061132783f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchExtractVectorElementWithBuildVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI2, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine extract vector element with a build vector on the vector register.</p>

<p>Declaration at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpervectorops-cpp">CombinerHelperVectorOps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6360a4c9f501f8ee60be165a4c9de7da">llvm::getIConstantFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractvectorelement/#ad8f4a9eb24c60d6e6d0102d17ae180ae">llvm::GExtractVectorElement::getIndexReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38d317b55a165bcddde7bb58ab7b12f3">llvm::getMVTForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gmergelikeinstr/#a226d638a0e8ab52846285f8a24e3c9f5">llvm::GMergeLikeInstr::getSourceReg</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractvectorelement/#a9bdb58d595df6f79845de5cf0139ad8c">llvm::GExtractVectorElement::getVectorReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>

</div>
</div>

### matchExtractVectorElementWithBuildVectorTrunc() {#a2a97e27cc61249c732f88ca2b63ce73f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchExtractVectorElementWithBuildVectorTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine extract vector element with a build vector trunc on the vector register.</p>

<p>Declaration at line 902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpervectorops-cpp">CombinerHelperVectorOps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b2430ab5e686b82f8cd6fd588d6de6f">llvm::getDefIgnoringCopies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractvectorelement/#ad8f4a9eb24c60d6e6d0102d17ae180ae">llvm::GExtractVectorElement::getIndexReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38d317b55a165bcddde7bb58ab7b12f3">llvm::getMVTForLLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gmergelikeinstr/#a226d638a0e8ab52846285f8a24e3c9f5">llvm::GMergeLikeInstr::getSourceReg</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractvectorelement/#a9bdb58d595df6f79845de5cf0139ad8c">llvm::GExtractVectorElement::getVectorReg</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>

</div>
</div>

### matchExtractVectorElementWithDifferentIndices() {#a3d2f7a0f835e800e04b1fae871054e01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchExtractVectorElementWithDifferentIndices (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine extract vector element with a insert vector element on the vector register and different indices.</p>

<p>Declaration at line 914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpervectorops-cpp">CombinerHelperVectorOps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b2430ab5e686b82f8cd6fd588d6de6f">llvm::getDefIgnoringCopies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractvectorelement/#ad8f4a9eb24c60d6e6d0102d17ae180ae">llvm::GExtractVectorElement::getIndexReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractvectorelement/#a9bdb58d595df6f79845de5cf0139ad8c">llvm::GExtractVectorElement::getVectorReg</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>

</div>
</div>

### matchExtractVectorElementWithShuffleVector() {#a89092e8630095ccf5b948def71d884f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchExtractVectorElementWithShuffleVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI2, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine extract vector element with a shuffle vector on the vector register.</p>

<p>Declaration at line 907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpervectorops-cpp">CombinerHelperVectorOps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6360a4c9f501f8ee60be165a4c9de7da">llvm::getIConstantFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractvectorelement/#ad8f4a9eb24c60d6e6d0102d17ae180ae">llvm::GExtractVectorElement::getIndexReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gshufflevector/#accb4d1c10e950e995f808829b4f3a106">llvm::GShuffleVector::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gshufflevector/#a54b06a5a5effc72c6bc4b9b678f20be2">llvm::GShuffleVector::getSrc1Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/gshufflevector/#a4ae3c15df3186decf42fd763ef386c43">llvm::GShuffleVector::getSrc2Reg</a>, <a href="#a8d34744985da7b7a26c92f1b064851ea">isConstantLegalOrBeforeLegalizer</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### matchFoldAMinusC1MinusC2() {#a71eafce3200f8a358c6855e3b6ee0a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchFoldAMinusC1MinusC2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 962 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7683 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6360a4c9f501f8ee60be165a4c9de7da">llvm::getIConstantFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#a16344f792b3875c54ea12aaaa8adc790">llvm::GBinOp::getLHSReg</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#ab4382d9d406beb612f27cd7e036f5c47">llvm::GBinOp::getRHSReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchFoldAMinusC1PlusC2() {#a183457f9d99bea5ee1a2fd06ceb9bb99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchFoldAMinusC1PlusC2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 969 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7729 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6360a4c9f501f8ee60be165a4c9de7da">llvm::getIConstantFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#a16344f792b3875c54ea12aaaa8adc790">llvm::GBinOp::getLHSReg</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#ab4382d9d406beb612f27cd7e036f5c47">llvm::GBinOp::getRHSReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchFoldAPlusC1MinusC2() {#a207867c80e7ad2da595e7a9adedcb612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchFoldAPlusC1MinusC2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 956 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7637 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6360a4c9f501f8ee60be165a4c9de7da">llvm::getIConstantFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#a16344f792b3875c54ea12aaaa8adc790">llvm::GBinOp::getLHSReg</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#ab4382d9d406beb612f27cd7e036f5c47">llvm::GBinOp::getRHSReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchFoldBinOpIntoSelect() {#aa3f4c3db433c1eb3e4feab24f3afb7db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchFoldBinOpIntoSelect (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned &amp; SelectOpNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Push a binary operator through a select on constants.</p>


<p>binop (select cond, K0, K1), K2 -&gt; select cond, (binop K0, K2), (binop K1, K2)</p>


<p>Declaration at line 584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3678 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1c01bab26241e422526ad42b90397e89">llvm::isAllOnesOrAllOnesSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6554ecb0fa738e15c376785b315b8ebc">llvm::isConstantOrConstantVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b092db64f93b2bfae42cbd58449adeb">llvm::isNullOrNullSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select</a>.</p>

</div>
</div>

### matchFoldC1Minus2MinusC2() {#a6b45fbac775c8ccd0b606e0a5ea671bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchFoldC1Minus2MinusC2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 965 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7706 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6360a4c9f501f8ee60be165a4c9de7da">llvm::getIConstantFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#a16344f792b3875c54ea12aaaa8adc790">llvm::GBinOp::getLHSReg</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#ab4382d9d406beb612f27cd7e036f5c47">llvm::GBinOp::getRHSReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchFoldC2MinusAPlusC1() {#a05e094eb5ea044b72cda4473bc6d78fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchFoldC2MinusAPlusC1 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 959 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7660 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6360a4c9f501f8ee60be165a4c9de7da">llvm::getIConstantFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#a16344f792b3875c54ea12aaaa8adc790">llvm::GBinOp::getLHSReg</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#ab4382d9d406beb612f27cd7e036f5c47">llvm::GBinOp::getRHSReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchFPowIExpansion() {#afb504c8fdf12e04e71a4ea3f728ced62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchFPowIExpansion (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int64_t Exponent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match FPOWI if it's safe to extend it into a series of multiplications.</p>

<p>Declaration at line 929 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7587 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a403260df3a211e47e65f35fbfd9bee8faf5ccb8d51ca38e2f3329955fc0149cd4">llvm::Exponent</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aebf2d22447761e0a5e507f415e11fb9b">llvm::TargetLoweringBase::isBeneficialToExpandPowI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### matchFreezeOfSingleMaybePoisonOperand() {#ae2bd5329e5726d560529de68df90503c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchFreezeOfSingleMaybePoisonOperand (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c064bbaef44753bce38ba88b8ba7588">llvm::canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab692b90c6e0e9b450f407896cbbe4b02">llvm::MachineInstr::findRegisterUseOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8a7ef433279aabf7f30fa5504a4d4ef">llvm::isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad43bf1af480830a4d6604e969e3f38e9">llvm::MachineInstr::isPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>, <a href="#a290f07593ec0820655db5efe88422c44">replaceRegOpWith</a>, <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>, <a href="#ad8de57b7e86580531aec66fde618bef2">TRI</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3949f157e1034f6cb5d16ad708059aa3">llvm::MachineInstr::uses</a>.</p>

</div>
</div>

### matchFsubToFneg() {#abb80926c82768fa525eee40937db0d81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchFsubToFneg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5717 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518adc42a7d40f8bd9c7f1a9c2beb0135fdc">llvm::MachineInstr::FmNsz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939476ce45d751473d769ba9a1075faf">llvm::getFConstantSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab95f6a4ac21fe35521db7740bac1a4db">llvm::getFConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchFunnelShiftToRotate() {#a6618ef11a5296a1388144d2fdae9f6e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchFunnelShiftToRotate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match an FSHL or FSHR that can be combined to a ROTR or ROTL rotate.</p>

<p>Declaration at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4388 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### matchHoistLogicOpWithSameOpcodeHands() {#aab86990eacd037e1c72749c3342d410e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchHoistLogicOpWithSameOpcodeHands (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/instructionstepsmatchinfo">InstructionStepsMatchInfo</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match (logic_op (op x...), (op y...)) -&gt; (op (logic_op x, y))</p>

<p>Declaration at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3088 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b2430ab5e686b82f8cd6fd588d6de6f">llvm::getDefIgnoringCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6f992bc4ca89f1b5f0b34f5b29978c31">llvm::TargetLoweringBase::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a342be90695496b88a8854a775dfd030f">llvm::TargetLoweringBase::isZExtFree</a>, <a href="#a0f3bc0c5478dd84e0831b5d78a274b47">matchEqualDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### matchICmpToLHSKnownBits() {#a79ff9815398a2c3331b42832035f21c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchICmpToLHSKnownBits (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if a G_ICMP <span class="doxyComputerOutput">MI</span> can be replaced with its LHS based off of <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> information.</p></dd>
</dl>


<p>Declaration at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4485 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4e1bd1414b3f2093861f8f48e7a10a7">llvm::getICmpTrueVal</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a38d34fceda94c01af95b775632ba8299">llvm::CmpInst::isEquality</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a27f29a27e5d3b0d6222ade8ab95e2be5">llvm::MIPatternMatch::m_SpecificICst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchICmpToTrueFalseKnownBits() {#a98f00ea8e8ca7e8ce4888da5cb138b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchICmpToTrueFalseKnownBits (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int64_t &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if a G_ICMP instruction <span class="doxyComputerOutput">MI</span> can be replaced with a true or false constant based off of <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> information.</p></dd>
</dl>


<p>Declaration at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4441 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a5769f1da829d6f6400b486d8e34e317f">llvm::ICmpInst::compare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4e1bd1414b3f2093861f8f48e7a10a7">llvm::getICmpTrueVal</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchInsertExtractVecEltOutOfBounds() {#a881fab40a57c999ccf31ebc208f8d859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchInsertExtractVecEltOutOfBounds (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if a G_{EXTRACT,INSERT}_VECTOR_ELT has an out of range index.</p>

<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2723 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19cdd6010b754ac90ebda5990b03cb40">llvm::getIConstantVRegVal</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3016e0f01ad96a198f81f74397b1c0e6">llvm::LLT::isScalableVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchInsertVectorElementOOB() {#a4726b2a74fcb79e35ec78c54ec7aa8ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchInsertVectorElementOOB (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine insert vector element OOB.</p>

<p>Declaration at line 936 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpervectorops-cpp">CombinerHelperVectorOps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ad1db89614d919436714d099c99ff12a0">llvm::LLT::isFixedVector</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchLoadOrCombine() {#a070e7ae88917971c8b99b3bb7f3d5942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchLoadOrCombine (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match expression trees of the form.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">sN *a = ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">sM val = a[0] | (a[1] &lt;&lt; <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>) | (a[2] &lt;&lt; 2<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>) | (a[3] &lt;&lt; 3<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>) ...</span></span></div>

</div>


<p>And check if the tree can be replaced with a M-bit load + possibly a bswap.</p>


<p>Declaration at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4001 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a7bbce253a42111c59c6d5a9c89763697">bigEndianByteAt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a130e12a0a8b3fe8149fe7b5eecfa603e">llvm::GMemOperation::getMMO</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaf6610b5b6565e4f1b56ca78c804654f">llvm::MachineMemOperand::getPointerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/gloadstore/#a0a7fb170c5d3165c1a9f3cf5fee5b4ca">llvm::GLoadStore::getPointerReg</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#aad6842fbf58844d974611a4915a00aae">isBigEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a84c1d72001dd5f34d9a55b3a7bb8a474">llvm::DataLayout::isBigEndian</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#af36685438b34780c1b4612f8f7ae1e66">littleEndianByteAt</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/memdesc/#a0f8389b50b7b92aaeb7f78099b1b531a">llvm::LegalityQuery::MemDesc::MemoryTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### matchMergeXAndUndef() {#a65bdadc254b269b10b7e67d39a9527dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchMergeXAndUndef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 989 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelperartifacts-cpp">CombinerHelperArtifacts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600clausemergepass-cpp/#aba99928790de45fa7aa12b47fbd828ff">Merge</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchMergeXAndZero() {#a518e2853dfbfd37675a14b6bf1ca6c90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchMergeXAndZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 992 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelperartifacts-cpp">CombinerHelperArtifacts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600clausemergepass-cpp/#aba99928790de45fa7aa12b47fbd828ff">Merge</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchMulOBy0() {#ad43afc169977548bbf11956b91156040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchMulOBy0 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match: (G_*MULO x, 0) -&gt; 0 + no carry out.</p>

<p>Declaration at line 739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a8d34744985da7b7a26c92f1b064851ea">isConstantLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a089b46c767dd14f714c3edbdce14f3f6">llvm::MIPatternMatch::m_SpecificICstOrSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchMulOBy2() {#a72a5d3fcc788946d3383d547eac00eca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchMulOBy2 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match: (G_UMULO x, 2) -&gt; (G_UADDO x, x) (G_SMULO x, 2) -&gt; (G_SADDO x, x)</p>

<p>Declaration at line 735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5129 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a089b46c767dd14f714c3edbdce14f3f6">llvm::MIPatternMatch::m_SpecificICstOrSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>.</p>

</div>
</div>

### matchMulOfVScale() {#a56ee7200c7a0fb8ed2b9f98288d83ff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchMulOfVScale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 944 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpervectorops-cpp">CombinerHelperVectorOps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19cdd6010b754ac90ebda5990b03cb40">llvm::getIConstantVRegVal</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gvscale/#a7c67c8f218bb124662af98cc5a846e98">llvm::GVScale::getSrc</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>.</p>

</div>
</div>

### matchNarrowBinop() {#aac58443a61bc007251b27585f5887c6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchNarrowBinop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; TruncMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; BinopMI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>trunc (binop X, C) --&gt; binop (trunc X, trunc C).</p>

<p>Declaration at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercasts-cpp">CombinerHelperCasts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchNarrowBinopFeedingAnd() {#a59e682863250eb07290a348d548eee0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchNarrowBinopFeedingAnd (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it is possible to narrow the width of a scalar binop feeding a G_AND instruction <span class="doxyComputerOutput">MI</span>.</p></dd>
</dl>


<p>Declaration at line 693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5038 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b2430ab5e686b82f8cd6fd588d6de6f">llvm::getDefIgnoringCopies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### matchNonNegZext() {#a2f87fb73ebb3f5d6d7e49e99fa478fa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchNonNegZext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine zext nneg to sext.</p>

<p>Declaration at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercasts-cpp">CombinerHelperCasts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38d317b55a165bcddde7bb58ab7b12f3">llvm::getMVTForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gcastop/#afd9f4526a055452535916c9c12810415">llvm::GCastOp::getSrcReg</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchNotCmp() {#a8ed1d04073cbd814c13097e138d462e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchNotCmp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; RegsToNegate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine inverting a result of a compare into the opposite cond code.</p>

<p>Declaration at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3486 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb8e07230ebf4fd2ccca08750ad045dc">llvm::getIConstantSplatSExtVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#acf3846b9b546bf122044e2665480ddc5">isConstValidTrue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a2e383c64b4d0eb271195ee9133d81ee2">llvm::MIPatternMatch::m_GXor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a441b9fc17e390be4c8dc6a1f1dd3d424">llvm::MIPatternMatch::m_ICst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### matchOperandIsKnownToBeAPowerOfTwo() {#a846bbee244f8b3e7ec21bc20f002ed9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchOperandIsKnownToBeAPowerOfTwo (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if operand <span class="doxyComputerOutput">OpIdx</span> is known to be a power of 2.</p>

<p>Declaration at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2956 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4036c3c75bcee1206cd199548b87f9ae">llvm::isKnownToBeAPowerOfTwo</a>, <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchOperandIsUndef() {#adf1110382dae21e5397a098cc5a08554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchOperandIsUndef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if operand <span class="doxyComputerOutput">OpIdx</span> is undef.</p>

<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2949 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchOperandIsZero() {#a67c4ed813faad031bd68547fc3b51244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchOperandIsZero (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if operand <span class="doxyComputerOutput">OpIdx</span> is zero.</p>

<p>Declaration at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2942 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a708b9606a37961be41adad607c81c532">llvm::canReplaceReg</a>, <a href="#ac975f07f5ebdceac6c93312485b74af2">matchConstantOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchOptBrCondByInvertingCond() {#ab40d01e80ca225a11dcdb8adbf4e843a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchOptBrCondByInvertingCond (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; BrCond)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a brcond's true block is not the fallthrough, make it so by inverting the condition and swapping operands.</p>

<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1593 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### matchOr() {#a449f68393659418a84ad0369a8a37be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchOr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine ors.</p>

<p>Declaration at line 879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7400 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>.</p>

</div>
</div>

### matchOrShiftToFunnelShift() {#a3748ec69250bb09564362325c334c9ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchOrShiftToFunnelShift (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 625 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4334 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ad7baea71af036277e3c15cee5c21351e">llvm::MIPatternMatch::m_GLShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a61adc0538bc40b2709040c5284c5c719">llvm::MIPatternMatch::m_GOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ab4c34955698e6d89ced0a74e2bb14667">llvm::MIPatternMatch::m_GShl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa5f3b8a0a9eb440cd96a96245e238eba">llvm::MIPatternMatch::m_GSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a68c2ea2a2e9814694f42f72d974e0f45">llvm::MIPatternMatch::m_ICstOrSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a089b46c767dd14f714c3edbdce14f3f6">llvm::MIPatternMatch::m_SpecificICstOrSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchOverlappingAnd() {#aeba19575c25ff51fe86cca1b6a3536a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchOverlappingAnd (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fold and(and(x, C1), C2) -&gt; C1&amp;C2 ? and(x, C1&amp;C2) : 0.</p>


<p>and(and(x, C1), C2) -&gt; C1&amp;C2 ? and(x, C1&amp;C2) : 0</p>


<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3240 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#abcba8f4496d7495913d7d6a845183349">llvm::MIPatternMatch::m_GAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a441b9fc17e390be4c8dc6a1f1dd3d424">llvm::MIPatternMatch::m_ICst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>.</p>

</div>
</div>

### matchPtrAddImmedChain() {#a3acff99aeccfa086e7fbef44df8c0ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchPtrAddImmedChain (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/ptraddchain">PtrAddChain</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1722 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/ptraddchain/#adad7ccdce66c8fd0d1b572fa88571131">llvm::PtrAddChain::Bank</a>, <a href="/web-llvm/docs/api/structs/llvm/ptraddchain/#a84f563cdcef6bdb8b6e834d28cf8c83b">llvm::PtrAddChain::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a115ffe6d615735fbe8b1bf31877565ba">llvm::TargetLoweringBase::AddrMode::BaseOffs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a0ae177a2136d1b90b767d57dbe6a419c">getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a0911ef4a610d70c5104c1932fec0e1">llvm::getTypeForLLT</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8868c35de6c36dc0d57e84f256c4ffde">llvm::TargetLoweringBase::AddrMode::HasBaseReg</a>, <a href="/web-llvm/docs/api/structs/llvm/ptraddchain/#a8b7d4fd0bd46a8e074b8ceb031cf6bd3">llvm::PtrAddChain::Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>

</div>
</div>

### matchPtrAddZero() {#a1abfcdfd643f1f81f3cf28cdfa5746b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchPtrAddZero (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>


<p>Combine G_PTR_ADD with nullptr to G_INTTOPTR</p>


<p>Declaration at line 574 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3639 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19cdd6010b754ac90ebda5990b03cb40">llvm::getIConstantVRegVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0905ec01af203441d890c82574431329">llvm::isBuildVectorAllZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchReassocCommBinOp() {#a2981a1ffe2c800e92ca997ada870ee6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchReassocCommBinOp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reassociate commutative binary operations like G_ADD.</p>

<p>Declaration at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4961 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9a9739cf49c46adcb76ac7e2dc13545c">tryReassocBinOp</a>.</p>

</div>
</div>

### matchReassocConstantInnerLHS() {#aeb0aa3738412a41ec60b41d08d849078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchReassocConstantInnerLHS (<a href="/web-llvm/docs/api/classes/llvm/gptradd">GPtrAdd</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * RHS, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4829 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a216c309718ce74c83d72308da142af26">llvm::MIPatternMatch::m_GCst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aabc13e9685078919223b80faf25c4b4e">llvm::MIPatternMatch::m_GPtrAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a77620b0effc4f10230daef6ae22f5175">llvm::MIPatternMatch::m_OneNonDBGUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>.</p>


<p>Referenced by <a href="#a7c17b27587a29f1c02dbf942ed6fc808">matchReassocPtrAdd</a>.</p>

</div>
</div>

### matchReassocConstantInnerRHS() {#a169aab3da2c9763de9377694467eae61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchReassocConstantInnerRHS (<a href="/web-llvm/docs/api/classes/llvm/gptradd">GPtrAdd</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * RHS, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4805 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19cdd6010b754ac90ebda5990b03cb40">llvm::getIConstantVRegVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>.</p>


<p>Referenced by <a href="#a7c17b27587a29f1c02dbf942ed6fc808">matchReassocPtrAdd</a>.</p>

</div>
</div>

### matchReassocFoldConstantsInSubTree() {#aaab53ed6a166f868585b2a095c546edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchReassocFoldConstantsInSubTree (<a href="/web-llvm/docs/api/classes/llvm/gptradd">GPtrAdd</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * RHS, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4860 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19cdd6010b754ac90ebda5990b03cb40">llvm::getIConstantVRegVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>.</p>


<p>Referenced by <a href="#a7c17b27587a29f1c02dbf942ed6fc808">matchReassocPtrAdd</a>.</p>

</div>
</div>

### matchReassocPtrAdd() {#a7c17b27587a29f1c02dbf942ed6fc808}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchReassocPtrAdd (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reassociate pointer calculations with G_ADD involved, to allow better addressing mode usage.</p>

<p>Declaration at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4888 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aeb0aa3738412a41ec60b41d08d849078">matchReassocConstantInnerLHS</a>, <a href="#a169aab3da2c9763de9377694467eae61">matchReassocConstantInnerRHS</a>, <a href="#aaab53ed6a166f868585b2a095c546edc">matchReassocFoldConstantsInSubTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchRedundantAnd() {#ad9804726a37a620da474deef91f667eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchRedundantAnd (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Replacement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">MI</span> is a G_AND instruction whose operands are x and y where x &amp; y == x or x &amp; y == y. (E.g., one of operands is all-ones value.)</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MI</td>
<td class="doxyParamItemDescription"><p>- The G_AND instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] Replacement</td>
<td class="doxyParamItemDescription"><p>- A register the G_AND should be replaced with on success.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3267 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a708b9606a37961be41adad607c81c532">llvm::canReplaceReg</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a28cf355963391ab8781b2347d495553d">llvm::KnownBits::isUnknown</a>, <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>

</div>
</div>

### matchRedundantBinOpInEquality() {#aaf88f3025beeaebb5bd345ebe277711c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchRedundantBinOpInEquality (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform: (X + Y) == X -&gt; Y == 0 (X - Y) == X -&gt; Y == 0 (X ^ Y) == X -&gt; Y == 0 (X + Y) != X -&gt; Y != 0 (X - Y) != X -&gt; Y != 0 (X ^ Y) != X -&gt; Y != 0.</p>

<p>Declaration at line 840 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6561 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a0c27987ab3db5ef2125fd178e0ff21b2">llvm::CmpInst::isEquality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#abb0025cff9b34811f8ce06ff14d4702c">llvm::MIPatternMatch::m_any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#acaa11e6486fead6bca99e2cd215a9a3e">llvm::MIPatternMatch::m_c_GICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a5a165ce6b90fa37c5cec47d02e329748">llvm::MIPatternMatch::m_GAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa5f3b8a0a9eb440cd96a96245e238eba">llvm::MIPatternMatch::m_GSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a2e383c64b4d0eb271195ee9133d81ee2">llvm::MIPatternMatch::m_GXor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a2c078a98e9ff22b2193666dfb006dba2">llvm::MIPatternMatch::m_Pred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### matchRedundantNegOperands() {#a5cd94b9d480eadb598a5125b9b294efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchRedundantNegOperands (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform (fadd x, fneg(y)) -&gt; (fsub x, y) (fadd fneg(x), y) -&gt; (fsub y, x) (fsub x, fneg(y)) -&gt; (fadd x, y) (fmul fneg(x), fneg(y)) -&gt; (fmul x, y) (fdiv fneg(x), fneg(y)) -&gt; (fdiv x, y) (fmad fneg(x), fneg(y), z) -&gt; (fmad x, y, z) (fma fneg(x), fneg(y), z) -&gt; (fma x, y, z)</p>

<p>Declaration at line 753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5671 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a907c89efc16c03d1fecde8fe47dafbad">llvm::MIPatternMatch::m_GFAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac58f55029dff0a1026f13b8b5ee80338">llvm::MIPatternMatch::m_GFNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa2b5c5e725ef870849cd3ccf7585a266">llvm::MIPatternMatch::m_GFSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### matchRedundantOr() {#ac3416b258eb84253f8111ea33e0beeed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchRedundantOr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Replacement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">MI</span> is a G_OR instruction whose operands are x and y where x | y == x or x | y == y. (E.g., one of operands is all-zeros value.)</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MI</td>
<td class="doxyParamItemDescription"><p>- The G_OR instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] Replacement</td>
<td class="doxyParamItemDescription"><p>- A register the G_OR should be replaced with on success.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3323 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a708b9606a37961be41adad607c81c532">llvm::canReplaceReg</a>, <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>

</div>
</div>

### matchRedundantSExtInReg() {#a66cc0cc249557274e026f892dbde2fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchRedundantSExtInReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">MI</span> is a G_SEXT_INREG that can be erased.</p></dd>
</dl>


<p>Declaration at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3365 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchRotateOutOfRange() {#abe5511c3ea29fcdddf397489e2b3ba9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchRotateOutOfRange (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4412 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf4f84c8a910409d92dd85e2b72953">llvm::matchUnaryPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchSDivByConst() {#a23ff02c4dc0c7eb4bc173bc9af346765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchSDivByConst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5455 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9c2999836b5dd4ca2d272970cc0b9a0f">llvm::getApproximateEVTForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ac8d6f220fcf8f327c6c739813df8c4c9">llvm::AttributeList::getAttributes</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a1a2592a2154d9272614c7d626f3dd991">llvm::MachineInstr::IsExact</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf4f84c8a910409d92dd85e2b72953">llvm::matchUnaryPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchSelect() {#ab57fb15e1f069496b2fa0b372b9b0475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchSelect (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine selects.</p>

<p>Declaration at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select</a>.</p>

</div>
</div>

### matchSelectIMinMax() {#a9098323777f98b3dd53bef412554961c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchSelectIMinMax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine select to integer min/max.</p>

<p>Declaration at line 867 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7038 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a38d34fceda94c01af95b775632ba8299">llvm::CmpInst::isEquality</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### matchSelectSameVal() {#a1561c4d75b24c0c46dcb05c8ec0bda65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchSelectSameVal (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimize (cond ? x : x) -&gt; x.</p>

<p>Declaration at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2928 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a708b9606a37961be41adad607c81c532">llvm::canReplaceReg</a>, <a href="#a0f3bc0c5478dd84e0831b5d78a274b47">matchEqualDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchSextInRegOfLoad() {#a8f5dd5583d12f1c7dcf63b86ff444394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchSextInRegOfLoad (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, unsigned &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match sext_inreg(load p), imm -&gt; sextload p.</p>

<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1046 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/memdesc/#a0f8389b50b7b92aaeb7f78099b1b531a">llvm::LegalityQuery::MemDesc::MemoryTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### matchSextOfTrunc() {#a5036ae118b8d8b9debc1c596eff93259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchSextOfTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine sext of trunc.</p>

<p>Declaration at line 852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercasts-cpp">CombinerHelperCasts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b2430ab5e686b82f8cd6fd588d6de6f">llvm::getDefIgnoringCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/gcastop/#afd9f4526a055452535916c9c12810415">llvm::GCastOp::getSrcReg</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518aefc960a99fa4cefc28a0ea76de0a0535">llvm::MachineInstr::NoSWrap</a>.</p>

</div>
</div>

### matchSextTruncSextLoad() {#a56afecdec991e6c14189691c37140ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchSextTruncSextLoad (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1013 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aeaad33cb0fd8ffab79aab1414253854d">llvm::MIPatternMatch::m_GTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchShiftImmedChain() {#a33c6405fe05b24b5d3f9c0ec0ed7f9ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchShiftImmedChain (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/registerimmpair">RegisterImmPair</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fold (shift (shift base, x), y) -&gt; (shift base (x+y))</p>

<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1797 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/structs/llvm/registerimmpair/#a15130db3b3cf5b29ae82d817f4ecdca1">llvm::RegisterImmPair::Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/structs/llvm/registerimmpair/#a0441320b16ae9242aca4afe9f8e511b3">llvm::RegisterImmPair::Reg</a>.</p>

</div>
</div>

### matchShiftOfShiftedLogic() {#a8434510d79fe87971bb903ab82cc1fc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchShiftOfShiftedLogic (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/llvm/shiftofshiftedlogic">ShiftOfShiftedLogic</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we have a shift-by-constant of a bitwise logic op that itself has a shift-by-constant operand with identical opcode, we may be able to convert that into 2 independent shifts followed by the logic op.</p>

<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1874 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/structs/llvm/shiftofshiftedlogic/#afcbc9e3d4ba39f4e104617f01392eef2">llvm::ShiftOfShiftedLogic::Logic</a>, <a href="/web-llvm/docs/api/structs/llvm/shiftofshiftedlogic/#a69db2b80712fe86683e0290173e569df">llvm::ShiftOfShiftedLogic::LogicNonShiftReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/shiftofshiftedlogic/#aceed3102b5bba500aec69509b30af283">llvm::ShiftOfShiftedLogic::Shift2</a> and <a href="/web-llvm/docs/api/structs/llvm/shiftofshiftedlogic/#a51b38312d459bb759771b781f71279df">llvm::ShiftOfShiftedLogic::ValSum</a>.</p>

</div>
</div>

### matchShiftsTooBig() {#a21e1dc2aa53c4d2b688e9a1e5fe4a95b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchShiftsTooBig (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::optional&lt; int64_t &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match shifts greater or equal to the range (the bitwidth of the result datatype, or the effective bitwidth of the source value).</p>

<p>Declaration at line 845 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6628 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a7735bcf6952625dbe3ccc49f428feb09">getMinUselessShift</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf4f84c8a910409d92dd85e2b72953">llvm::matchUnaryPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchShlOfVScale() {#a5b5001e37af42df3e8202151fe08b3c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchShlOfVScale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 948 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpervectorops-cpp">CombinerHelperVectorOps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19cdd6010b754ac90ebda5990b03cb40">llvm::getIConstantVRegVal</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gshl/#aa8482d32667b4117740e52c87ff6c45a">llvm::GShl::getShiftReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gvscale/#a7c67c8f218bb124662af98cc5a846e98">llvm::GVScale::getSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/gshl/#af0470ee08a8edb0aea1b769274cf853d">llvm::GShl::getSrcReg</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#acb9c55b6986369948507ca5241b4e411">llvm::APInt::shl</a>.</p>

</div>
</div>

### matchShuffleDisjointMask() {#a6d345595bdc1655f01d68419353184cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchShuffleDisjointMask (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Turn shuffle a, b, mask -&gt; shuffle undef, b, mask iff mask does not reference a.</p>

<p>Declaration at line 922 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7878 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a8b92508b0d76cc16076ee837c56e377b">commuteMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchShuffleToExtract() {#a16130b5045fbc424c847795ec9bf17e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchShuffleToExtract (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### matchShuffleUndefRHS() {#a3df1d9d3afbfe5db4027289cf28d4726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchShuffleUndefRHS (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove references to rhs if it is undef.</p>

<p>Declaration at line 918 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7834 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### matchSimplifyAddToSub() {#a4a44e20b38fdd26858c54152cf52acc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchSimplifyAddToSub (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if MI is a G_ADD which can be simplified to a G_SUB.</p>

<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2995 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5d295dcffba83c3c5a17d2fb3273b434">llvm::PatternMatch::m_Neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchSimplifyNegMinMax() {#a2e6e1c84d8b84dbd2101236bca332d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchSimplifyNegMinMax (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tranform (neg (min/max x, (neg x))) into (max/min x, (neg x)).</p>

<p>Declaration at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa787aa2fd081c7ccdc981afa7ee45f83">llvm::getInverseGMinMaxOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="#a9569ff6b4f769cb7a667ad4a986589e8">isLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ad168e9806711429475c916e9b0d521c1">llvm::MIPatternMatch::m_all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#abb0025cff9b34811f8ce06ff14d4702c">llvm::MIPatternMatch::m_any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a809eac8eaab0d6c672e05a93fa04a834">llvm::MIPatternMatch::m_DeferredReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aee9fa4738364905e4cda048eeac81368">llvm::MIPatternMatch::m_GSMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ad359e033f169f1ea49c11a78b09c0d38">llvm::MIPatternMatch::m_GSMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a80c45a5b2fd5f4555b2d08fc7b277c74">llvm::MIPatternMatch::m_GUMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a2d340c3191e459e7b1545982b489960b">llvm::MIPatternMatch::m_GUMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5d295dcffba83c3c5a17d2fb3273b434">llvm::PatternMatch::m_Neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### matchSimplifySelectToMinMax() {#ad133fd24c3d69592d832837ce6a24c75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchSimplifySelectToMinMax (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it is possible to simplify a select instruction <span class="doxyComputerOutput">MI</span> to a min/max instruction of some sort.</p></dd>
</dl>


<p>Declaration at line 830 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6546 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aeaad33cb0fd8ffab79aab1414253854d">llvm::MIPatternMatch::m_GTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a77620b0effc4f10230daef6ae22f5175">llvm::MIPatternMatch::m_OneNonDBGUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchSubAddSameReg() {#aeac793ece837d10b193280411783d33e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchSubAddSameReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform: (x + y) - y -&gt; x (x + y) - x -&gt; y x - (y + x) -&gt; 0 - y x - (x + z) -&gt; 0 - z.</p>

<p>Declaration at line 826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5201 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a5a165ce6b90fa37c5cec47d02e329748">llvm::MIPatternMatch::m_GAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa5f3b8a0a9eb440cd96a96245e238eba">llvm::MIPatternMatch::m_GSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a68c2ea2a2e9814694f42f72d974e0f45">llvm::MIPatternMatch::m_ICstOrSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a089b46c767dd14f714c3edbdce14f3f6">llvm::MIPatternMatch::m_SpecificICstOrSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### matchSuboCarryOut() {#adc129334a6d3d83eb003dd1a49540f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchSuboCarryOut (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 995 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7930 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ac5a96896a96f880fbd295aec85a81a87a9ac50ff0c308dad407db9f09e418363e">llvm::ConstantRange::AlwaysOverflowsHigh</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ac5a96896a96f880fbd295aec85a81a87ac8cc76d76703c81c16e939be370683c1">llvm::ConstantRange::AlwaysOverflowsLow</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a211874a1535ba321cab61942cde9398f">llvm::ConstantRange::fromKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinopcarryout/#a0e39dc0b187ca4f38648326ee00e6ece">llvm::GBinOpCarryOut::getCarryOutReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4e1bd1414b3f2093861f8f48e7a10a7">llvm::getICmpTrueVal</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinopcarryout/#abc631c430bcd8a73482dd4ea8495a38a">llvm::GBinOpCarryOut::getLHSReg</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinopcarryout/#a9f92d09b678eb63420aade92877ee278">llvm::GBinOpCarryOut::getRHSReg</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="#a8d34744985da7b7a26c92f1b064851ea">isConstantLegalOrBeforeLegalizer</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/classes/llvm/gsubcarryout/#ac6455126213be6a5e2e7be0d2dd3bc91">llvm::GSubCarryOut::isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a73fb0011cd095655aa70f5e6e315b838">KB</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ac5a96896a96f880fbd295aec85a81a87ad4d9862eafa015a05101d9f662bb153a">llvm::ConstantRange::MayOverflow</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ac5a96896a96f880fbd295aec85a81a87a56624a95592b438e05ab500a6a200a03">llvm::ConstantRange::NeverOverflows</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518aefc960a99fa4cefc28a0ea76de0a0535">llvm::MachineInstr::NoSWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a16996c70759af20709e11bec0f30a14b">llvm::MachineInstr::NoUWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ae907195afbb8c9442691836e26ac0001">llvm::ConstantRange::signedSubMayOverflow</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a24a99adda34abba8c6988f8292a93815">llvm::ConstantRange::unsignedSubMayOverflow</a>.</p>

</div>
</div>

### matchSubOfVScale() {#ac88c813e35b6d1a4966b0ee24a5c8b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchSubOfVScale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpervectorops-cpp">CombinerHelperVectorOps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad73e18478cd951f76d35a88c4d43ef5a">llvm::MachineInstr::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#a16344f792b3875c54ea12aaaa8adc790">llvm::GBinOp::getLHSReg</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinop/#ab4382d9d406beb612f27cd7e036f5c47">llvm::GBinOp::getRHSReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gvscale/#a7c67c8f218bb124662af98cc5a846e98">llvm::GVScale::getSrc</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchTruncateOfExt() {#a633b0486bab32c1b91cc923d82a72c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchTruncateOfExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; ExtMI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform trunc ([asz]ext x) to x or ([asz]ext x) or (trunc x).</p>

<p>Declaration at line 951 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercasts-cpp">CombinerHelperCasts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchTruncBuildVectorFold() {#ac6cad51d01e79fc7c77d3c58d58394da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchTruncBuildVectorFold (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6404 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#abe5d216582c8bd8e0159b91beaf9046c">llvm::MIPatternMatch::m_GBitcast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a187d1464e826697bd2e8fec623e5071e">llvm::MIPatternMatch::m_GBuildVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchTruncLshrBuildVectorFold() {#a350580c34bfdfd93dbeb51e3f2b44fa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchTruncLshrBuildVectorFold (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6415 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#abe5d216582c8bd8e0159b91beaf9046c">llvm::MIPatternMatch::m_GBitcast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a187d1464e826697bd2e8fec623e5071e">llvm::MIPatternMatch::m_GBuildVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a216c309718ce74c83d72308da142af26">llvm::MIPatternMatch::m_GCst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ad7baea71af036277e3c15cee5c21351e">llvm::MIPatternMatch::m_GLShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchUDivByConst() {#a51f93c65cadd67241250f97598ab1358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchUDivByConst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine G_UDIV by constant into a multiply by magic constant.</p>

<p>Declaration at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5406 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aaa6f42b31892a929914872c879e4b365">llvm::LLT::changeElementSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9c2999836b5dd4ca2d272970cc0b9a0f">llvm::getApproximateEVTForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ac8d6f220fcf8f327c6c739813df8c4c9">llvm::AttributeList::getAttributes</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6554ecb0fa738e15c376785b315b8ebc">llvm::isConstantOrConstantVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a1a2592a2154d9272614c7d626f3dd991">llvm::MachineInstr::IsExact</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#aca634f15887089866f5d88dac807786c">LI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf4f84c8a910409d92dd85e2b72953">llvm::matchUnaryPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### matchUMulHToLShr() {#acd5de1d4698c082f674654d67b42f1ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchUMulHToLShr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 5639 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeafa582b26e8bdbe677ef62af7bad169">llvm::TargetLoweringBase::getPreferredShiftAmountTy</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf4f84c8a910409d92dd85e2b72953">llvm::matchUnaryPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchUndefSelectCmp() {#aac6f62bcef60abeb3f12a394f6e57ead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchUndefSelectCmp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if a G_SELECT instruction <span class="doxyComputerOutput">MI</span> has an undef comparison.</p>

<p>Declaration at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2717 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchUndefShuffleVectorMask() {#a81b1ce0f10386f3b69d3b5f7c73b2d05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchUndefShuffleVectorMask (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if a G_SHUFFLE_VECTOR instruction <span class="doxyComputerOutput">MI</span> has an undef mask.</p>

<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2705 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### matchUndefStore() {#a9ede1eaa682d8cb883fcbdfc3d894e70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchUndefStore (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if a G_STORE instruction <span class="doxyComputerOutput">MI</span> is storing an undef value.</p>

<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2711 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchUnmergeValuesAnyExtBuildVector() {#a12794dfd41dd116d9e295524d932f6c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchUnmergeValuesAnyExtBuildVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 985 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7752 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/gunmerge/#a2016607245da986216c5fa788412efbe">llvm::GUnmerge::getNumDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gunmerge/#a5f5a5fac10a0aadbff8eb0ec3cad5b60">llvm::GUnmerge::getSourceReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ad1db89614d919436714d099c99ff12a0">llvm::LLT::isFixedVector</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchUseVectorTruncate() {#a9e44e0e5bdc7526a1b299ae804752709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchUseVectorTruncate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3396 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a4f404daab6050b7a8e95bb247d4aefb2">llvm::LLT::changeElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a1618ca92d9fa0b2b577698fb006b84cc">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownMultipleOf</a>, <a href="#a9569ff6b4f769cb7a667ad4a986589e8">isLegal</a>, <a href="#a7baaf2859fea3988241fef9589a47557">IsPreLegalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>

</div>
</div>

### matchXorOfAndWithSameReg() {#a62065b49533b4287092563e507342296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchXorOfAndWithSameReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fold (xor (and x, y), y) -&gt; (and (not x), y) {.</p>

<p>Declaration at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3595 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#abcba8f4496d7495913d7d6a845183349">llvm::MIPatternMatch::m_GAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### matchZextOfTrunc() {#a27942d2942b84e3453b75e3417def841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchZextOfTrunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine zext of trunc.</p>

<p>Declaration at line 855 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercasts-cpp">CombinerHelperCasts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b2430ab5e686b82f8cd6fd588d6de6f">llvm::getDefIgnoringCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/gcastop/#afd9f4526a055452535916c9c12810415">llvm::GCastOp::getSrcReg</a>, <a href="#aa6528d48a17e668c9ba2c8786df9d64b">isLegalOrBeforeLegalizer</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a3453657a772c3023f6ef942525db0d5d">llvm::MachineInstr::NonNeg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a16996c70759af20709e11bec0f30a14b">llvm::MachineInstr::NoUWrap</a>.</p>

</div>
</div>

### replaceInstWithConstant() {#a4ad0b68c5dc4f76574c35800de2eee45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::replaceInstWithConstant (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int64_t C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace an instruction with a G_CONSTANT with value <span class="doxyComputerOutput">C</span>.</p>

<p>Declaration at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2969 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### replaceInstWithConstant() {#acb1f75635e015ce0751b2053d061be9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::replaceInstWithConstant (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace an instruction with a G_CONSTANT with value <span class="doxyComputerOutput">C</span>.</p>

<p>Declaration at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2976 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### replaceInstWithFConstant() {#a64af7868673efe2f150ab995a6c8c155}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::replaceInstWithFConstant (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, double C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace an instruction with a G_FCONSTANT with value <span class="doxyComputerOutput">C</span>.</p>

<p>Declaration at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2962 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### replaceInstWithFConstant() {#a550ed89ae539e7dc552c77df4a05699e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::replaceInstWithFConstant (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * CFP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace an instruction with an G_FCONSTANT with value <span class="doxyComputerOutput">CFP</span>.</p>

<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2982 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### replaceInstWithUndef() {#aaca0b3013530db742551fd22ca8ff655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::replaceInstWithUndef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace an instruction with a G_IMPLICIT_DEF.</p>

<p>Declaration at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2989 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### replaceOpcodeWith() {#a6711738d18f70c1843eac7255405df54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::replaceOpcodeWith (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; FromMI, unsigned ToOpcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace the opcode in instruction with a new opcode and inform the observer of the changes.</p>

<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9117508fb00fda14207e7f968389544c">llvm::MachineInstr::setDesc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#aa20f5e3d228e0f30d2f3c53c53cc6c93">llvm::AMDGPUCombinerHelper::applyFoldableFneg</a>.</p>

</div>
</div>

### replaceRegOpWith() {#a290f07593ec0820655db5efe88422c44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::replaceRegOpWith (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; FromRegOp, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ToReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace a single register operand with a new register and inform the observer of the changes.</p>

<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>, <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>


<p>Referenced by <a href="#a00301689820a26a9f3b438f6dece6ef0">applyCombineExtendingLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#aa20f5e3d228e0f30d2f3c53c53cc6c93">llvm::AMDGPUCombinerHelper::applyFoldableFneg</a> and <a href="#ae2bd5329e5726d560529de68df90503c">matchFreezeOfSingleMaybePoisonOperand</a>.</p>

</div>
</div>

### replaceRegWith() {#a28ea263eb2492e410f764fc705781c05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::replaceRegWith (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FromReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ToReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#af16c39ee36e4633f821b6820f8bd52ef">MachineRegisterInfo::replaceRegWith()</a> and inform the observer of the changes.</p>

<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#aee882972a50054d1a691edcc470e4dc8">Builder</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#ada82db26b18384aaa5d15440061bf5a3">Observer</a>.</p>


<p>Referenced by <a href="#a1c95f864b062fedecfd2c4fc32abf47e">applyCombineConcatVectors</a>, <a href="#a4eeb3124ce1fe172f0e79b5f42be7f5c">applyCombineCopy</a>, <a href="#a00301689820a26a9f3b438f6dece6ef0">applyCombineExtendingLoads</a>, <a href="#a7ee8b3f43a97b93dde8c791002d306f9">applyCombineShuffleVector</a>, <a href="#ac91aca84eade26acea192464a9cfcde8">applyCombineTruncOfShift</a>, <a href="#afcc62af19a5d1f2ea5f0e51b3e31893b">applyCombineUnmergeMergeToPlainValues</a>, <a href="#afe9d6cb97689cb5efb1a5b8f9dc68ea0">applyCombineUnmergeZExtToZExt</a>, <a href="#aecfc4a2e41e3c67c64ee64ed29103630">applyExtractAllEltsFromBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#aa20f5e3d228e0f30d2f3c53c53cc6c93">llvm::AMDGPUCombinerHelper::applyFoldableFneg</a>, <a href="#a321f2dfbd709348cfd0e1ab66cf0b62c">applyNotCmp</a>, <a href="#ae2bd5329e5726d560529de68df90503c">matchFreezeOfSingleMaybePoisonOperand</a>, <a href="#aeba19575c25ff51fe86cca1b6a3536a9">matchOverlappingAnd</a>, <a href="#af1ac0d7bbf4c5e4b5ed052554b54cf5c">replaceSingleDefInstWithOperand</a>, <a href="#a25ff4284ba96727747d6ceb7ef16b95d">replaceSingleDefInstWithReg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#af6dea6ab7fff2717e5813f576518e4f2">anonymous{AArch64PreLegalizerCombiner.cpp}::tryToSimplifyUADDO</a>.</p>

</div>
</div>

### replaceSingleDefInstWithOperand() {#af1ac0d7bbf4c5e4b5ed052554b54cf5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::replaceSingleDefInstWithOperand (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delete <span class="doxyComputerOutput">MI</span> and replace all of its uses with its <span class="doxyComputerOutput">OpIdx-th</span> operand.</p>

<p>Declaration at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2871 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a708b9606a37961be41adad607c81c532">llvm::canReplaceReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>.</p>

</div>
</div>

### replaceSingleDefInstWithReg() {#a25ff4284ba96727747d6ceb7ef16b95d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::replaceSingleDefInstWithReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Replacement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delete <span class="doxyComputerOutput">MI</span> and replace all of its uses with <span class="doxyComputerOutput">Replacement</span>.</p>

<p>Declaration at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2881 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a708b9606a37961be41adad607c81c532">llvm::canReplaceReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a> and <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>.</p>


<p>Referenced by <a href="#aa3bd6f239db6919e67236164cd0d840f">applyExtractVecEltBuildVec</a>, <a href="#a49d52b12000c2c069a30b9b22809385d">applySDivByConst</a> and <a href="#ad67f36800bff5506b51d7eaa3259cd01">applyUDivByConst</a>.</p>

</div>
</div>

### setRegBank() {#abefb646c754368c3ecc32c050c5bacd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CombinerHelper::setRegBank (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> * RegBank)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the register bank of <span class="doxyComputerOutput">Reg</span>.</p>


<p>Does nothing if the RegBank is null. This is the counterpart to getRegBank.</p>


<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>Reference <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>


<p>Referenced by <a href="#a8cd84da3b005d88c0f1b19d868e0a2b3">applyPtrAddImmedChain</a>.</p>

</div>
</div>

### tryCombine() {#a094194cbf835d3ebeb1039b1ed575121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CombinerHelper::tryCombine (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to transform <span class="doxyComputerOutput">MI</span> by using all of the above combine functions.</p>


<p>Returns true if changed.</p>


<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a403260df3a211e47e65f35fbfd9bee8faf5ccb8d51ca38e2f3329955fc0149cd4">llvm::Exponent</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### tryCombineCopy() {#a77695e2fac4d7c37fd43e1d9a55e69ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::tryCombineCopy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If <span class="doxyComputerOutput">MI</span> is COPY, try to combine it.</p>


<p>Returns true if MI changed.</p>


<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#a4eeb3124ce1fe172f0e79b5f42be7f5c">applyCombineCopy</a>, <a href="#a5fc01df6a11c709c2e05f5ef212d239d">matchCombineCopy</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### tryCombineExtendingLoads() {#aa57157299174e74145361548452e45f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::tryCombineExtendingLoads (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If <span class="doxyComputerOutput">MI</span> is extend that consumes the result of a load, try to combine it.</p>


<p>Returns true if MI changed.</p>


<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#a00301689820a26a9f3b438f6dece6ef0">applyCombineExtendingLoads</a>, <a href="#ab5ece2e19fefdc8f1112b05d6274e649">matchCombineExtendingLoads</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### tryCombineMemCpyFamily() {#ae1fd41e303fcb42122f8a0432efcd87d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::tryCombineMemCpyFamily (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned MaxLen=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimize memcpy intrinsics et al, e.g.</p>


<p>constant len calls. /p MaxLen if non-zero specifies the max length of a mem libcall to inline.</p>


<p>For example (pre-indexed):</p>



<pre><code>$addr = G_PTR_ADD $base, $offset
[...]
$val = G_LOAD $addr
[...]
$whatever = COPY $addr
</code></pre>


<p>--&gt;</p>



<pre><code>$val, $addr = G_INDEXED_LOAD $base, $offset, 1 (IsPre)
[...]
$whatever = COPY $addr
</code></pre>


<p>or (post-indexed):</p>



<pre><code>G_STORE $val, $base
[...]
$addr = G_PTR_ADD $base, $offset
[...]
$whatever = COPY $addr
</code></pre>


<p>--&gt;</p>



<pre><code>$addr = G_INDEXED_STORE $val, $base, $offset
[...]
$whatever = COPY $addr
</code></pre>


<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1660 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">llvm::LegalizerHelper::Legalized</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aca820b14c7ae2e658cefd8a3be4da035">llvm::LegalizerHelper::lowerMemCpyFamily</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### tryCombineShiftToUnmerge() {#aa3f99a0f1d4b4f20f945a7cc8f7e1d65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::tryCombineShiftToUnmerge (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TargetShiftAmount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 2450 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#afae5d269529ade8f678f13c1dde831d1">applyCombineShiftToUnmerge</a>, <a href="#adb9e9ab4728e40478a30f57d57508f4e">matchCombineShiftToUnmerge</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### tryCombineShuffleVector() {#aa9de7f911f64078bdbf773007dc10997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::tryCombineShuffleVector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to combine G_SHUFFLE_VECTOR into G_CONCAT_VECTORS.</p>


<p>Returns true if MI changed.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MI.getOpcode() == G_SHUFFLE_VECTOR.</p></dd>
</dl>


<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a7ee8b3f43a97b93dde8c791002d306f9">applyCombineShuffleVector</a>, <a href="#a620917cb45d142b76b1eb2dcd76ce689">matchCombineShuffleVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### tryEmitMemcpyInline() {#a4c12c2286b1a252d619bb618c8b5d356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::tryEmitMemcpyInline (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit loads and stores that perform the given memcpy.</p>


<p>Assumes <span class="doxyComputerOutput">MI</span> is a G_MEMCPY_INLINE TODO: implement dynamically sized inline memcpy, and rename: s/bool tryEmit/void emit/</p>


<p>Declaration at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1652 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">llvm::LegalizerHelper::Legalized</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### tryReassocBinOp() {#a9a9739cf49c46adcb76ac7e2dc13545c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::tryReassocBinOp (unsigned Opc, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Op0, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Op1, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to reassociate to reassociate operands of a commutative binop.</p>

<p>Declaration at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4920 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a496914f81c80c3adc8866dec3586859d">llvm::isConstantOrConstantSplatVector</a> and <a href="#a9fdbebed8efeedc9c2b5be88e2e33798">MRI</a>.</p>


<p>Referenced by <a href="#a2981a1ffe2c800e92ca997ada870ee6f">matchReassocCommBinOp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeRetValAgainstNaN() {#a6e9632b4688c1ddb0fd9ec1ad4e973d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CombinerHelper::SelectPatternNaNBehaviour CombinerHelper::computeRetValAgainstNaN (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RHS, bool IsOrderedComparison)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>which of <span class="doxyComputerOutput">LHS</span> and <span class="doxyComputerOutput">RHS</span> would be the result of a non-equality floating point comparison where one of <span class="doxyComputerOutput">LHS</span> and <span class="doxyComputerOutput">RHS</span> may be NaN.</p></dd>
</dl>


<p>If both <span class="doxyComputerOutput">LHS</span> and <span class="doxyComputerOutput">RHS</span> may be NaN, returns SelectPatternNaNBehaviour::NOT_APPLICABLE.</p>


<p>Declaration at line 1061 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6470 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### constantFoldFCmp() {#aa0174274d1fe6fbe4f9947be1b8849f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::constantFoldFCmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gfcmp">GFCmp</a> &amp; FCmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gfconstant">GFConstant</a> &amp; LHSCst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gfconstant">GFConstant</a> &amp; RHSCst, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercompares-cpp">CombinerHelperCompares.cpp</a>.</p>

</div>
</div>

### constantFoldICmp() {#ae69fd612c84de7f816d5653999ae9f03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::constantFoldICmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gicmp">GICmp</a> &amp; ICmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/giconstant">GIConstant</a> &amp; LHSCst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/giconstant">GIConstant</a> &amp; RHSCst, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercompares-cpp">CombinerHelperCompares.cpp</a>.</p>

</div>
</div>

### findCandidatesForLoadOrCombine() {#ab94c04f9410ae544fc398a7c63a7f2ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SmallVector&lt; Register, 8 &gt; &gt; CombinerHelper::findCandidatesForLoadOrCombine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function for matchLoadOrCombine.</p>


<p>Searches for Registers which may have been produced by a load instruction + some arithmetic.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] Root</td>
<td class="doxyParamItemDescription"><p>- The search root.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The Registers found during the search.</p></dd>
</dl>


<p>Declaration at line 1021 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3769 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### findLoadOffsetsForLoadOrCombine() {#a025805b8366e0c582e942f86d5dc516f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::tuple&lt; GZExtLoad *, int64_t, GZExtLoad * &gt; &gt; CombinerHelper::findLoadOffsetsForLoadOrCombine (<a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; int64_t, int64_t, 8 &gt; &amp; MemOffset2Idx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 8 &gt; &amp; RegsToVisit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned MemSizeInBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function for matchLoadOrCombine.</p>


<p>Checks if every register in <span class="doxyComputerOutput">RegsToVisit</span> is defined by a load instruction + some arithmetic.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] MemOffset2Idx</td>
<td class="doxyParamItemDescription"><p>- Maps the byte positions each load ends up at to the index of the load.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MemSizeInBits</td>
<td class="doxyParamItemDescription"><p>- The number of bits each load should produce.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>On success, a 3-tuple containing lowest-index load found, the lowest index, and the last load in the sequence.</p></dd>
</dl>


<p>Declaration at line 1035 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 3867 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### findPostIndexCandidate() {#a2700f65ebe47d115d7df1b1fd68addd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::findPostIndexCandidate (<a href="/web-llvm/docs/api/classes/llvm/gloadstore">GLoadStore</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Offset, bool &amp; RematOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a non-indexed load or store instruction <span class="doxyComputerOutput">MI</span>, find an offset that can be usefully and legally folded into it as a post-indexing operation.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if a candidate is found.</p></dd>
</dl>


<p>Declaration at line 1004 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### findPreIndexCandidate() {#a38cee7ff8d64cc03ac43668943d5f184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::findPreIndexCandidate (<a href="/web-llvm/docs/api/classes/llvm/gloadstore">GLoadStore</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Addr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a non-indexed load or store instruction <span class="doxyComputerOutput">MI</span>, find an offset that can be usefully and legally folded into it as a pre-indexing operation.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if a candidate is found.</p></dd>
</dl>


<p>Declaration at line 1011 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1283 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### getConstantOrConstantSplatVector() {#ac37a91643de0fa959d5a92f87dfccd52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; APInt &gt; CombinerHelper::getConstantOrConstantSplatVector (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1099 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6763 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### getFPMinMaxOpcForSelect() {#aabe72346a2a7587fa74dfbd197065037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CombinerHelper::getFPMinMaxOpcForSelect (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> DstTy, SelectPatternNaNBehaviour VsNaNRetVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determines the floating point min/max opcode which should be used for a G_SELECT fed by a G_FCMP with predicate <span class="doxyComputerOutput">Pred</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>0 if this G_SELECT should not be combined to a floating point min or max. If it should be combined, returns one of</p></dd>
</dl>


<ul class="doxyList ">
<li>G_FMAXNUM</li>
<li>G_FMAXIMUM</li>
<li>G_FMINNUM</li>
<li>G_FMINIMUM</li>
</ul>

<p>Helper function for matchFPSelectToMinMax.</p>


<p>Declaration at line 1076 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6430 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### isCastFree() {#a91accffdd4294ff1626fa0970160381c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::isCastFree (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> ToTy, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> FromTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercasts-cpp">CombinerHelperCasts.cpp</a>.</p>

</div>
</div>

### isConstantOrConstantVectorI() {#a863e910fe7a06a014195c53b42560540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::isConstantOrConstantVectorI (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1097 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6788 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### isConstantSplatVector() {#a43efec1114a284e3e5acfbe484ef75f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::isConstantSplatVector (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src, int64_t SplatValue, bool AllowUndefs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1095 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6737 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### isIndexedLoadStoreLegal() {#a7e7aa30e08e6ec88a7c7d03d8eda4c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::isIndexedLoadStoreLegal (<a href="/web-llvm/docs/api/classes/llvm/gloadstore">GLoadStore</a> &amp; LdSt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks for legality of an indexed variant of <span class="doxyComputerOutput">LdSt</span>.</p>

<p>Declaration at line 999 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 1163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### isOneOrOneSplat() {#a5aa63605494f148c2c7c193a6af180c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::isOneOrOneSplat (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src, bool AllowUndefs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1093 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6709 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### isZeroOrZeroSplat() {#a02c38d89f04cffc015c06bac29f1bd42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::isZeroOrZeroSplat (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src, bool AllowUndefs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1094 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6722 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### matchFPSelectToMinMax() {#a8d8f27a873dde4e150529c99fb41498c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::matchFPSelectToMinMax (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Cond, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> TrueVal, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FalseVal, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle floating point cases for matchSimplifySelectToMinMax.</p>


<p>E.g.</p>


<p>select (fcmp uge x, 1.0) x, 1.0 -&gt; fmax x, 1.0 select (fcmp uge x, 1.0) 1.0, x -&gt; fminnm x, 1.0</p>


<p>Declaration at line 1085 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6490 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### reassociationCanBreakAddressingModePattern() {#a4e6706e6003a3f7b6184a73458132406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::reassociationCanBreakAddressingModePattern (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; PtrAdd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Examines the G_PTR_ADD instruction <span class="doxyComputerOutput">PtrAdd</span> and determines if performing a re-association of its operands would break an existing legal addressing mode that the address computation currently represents.</p>

<p>Declaration at line 1043 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 4740 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### tryFoldAndOrOrICmpsUsingRanges() {#ac7c87b77e10f706b166c22d0b0438b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::tryFoldAndOrOrICmpsUsingRanges (<a href="/web-llvm/docs/api/classes/llvm/glogicalbinop">GLogicalBinOp</a> * Logic, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fold (icmp Pred1 V1, C1) &amp;&amp; (icmp Pred2 V2, C2) or (icmp Pred1 V1, C1) || (icmp Pred2 V2, C2) into a single comparison using range-based reasoning.</p>


<p>see InstCombinerImpl::foldAndOrOfICmpsUsingRanges.</p>


<p>Declaration at line 1104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### tryFoldBoolSelectToLogic() {#aadbbd31b2959872b72b4cde875b86bef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::tryFoldBoolSelectToLogic (<a href="/web-llvm/docs/api/classes/llvm/gselect">GSelect</a> * Select, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to fold selects to logical operations.</p>

<p>Declaration at line 1089 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6957 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### tryFoldLogicOfFCmps() {#a7bf69fcd7c631813e4f4b567a170d8af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::tryFoldLogicOfFCmps (<a href="/web-llvm/docs/api/classes/llvm/glogicalbinop">GLogicalBinOp</a> * Logic, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 7313 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

### tryFoldSelectOfConstants() {#a12dbac5fd74a23a5cc38c397ae4f8efc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CombinerHelper::tryFoldSelectOfConstants (<a href="/web-llvm/docs/api/classes/llvm/gselect">GSelect</a> * Select, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b7d179366307f01deb88ddf796eb82">BuildFnTy</a> &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1091 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>, definition at line 6808 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Builder {#aee882972a50054d1a691edcc470e4dc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineIRBuilder&amp; llvm::CombinerHelper::Builder</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>


<p>Referenced by <a href="#ab521134f26557f6178240bd7ddc7ab59">applyAshShlToSextInreg</a>, <a href="#a2b46e1c0d91a5df6f3f45d573f833b1a">applyBuildFnMO</a>, <a href="#a9cc535281480db1c2f9d8f0bec0f2c95">applyBuildFnNoErase</a>, <a href="#a3dfd04f65a3e59e3ec45ac554aaf6234">applyBuildInstructionSteps</a>, <a href="#a51abd9f22e4c8694c58d6719892bd27e">applyCombineAddP2IToPtrAdd</a>, <a href="#a1c95f864b062fedecfd2c4fc32abf47e">applyCombineConcatVectors</a>, <a href="#a94c5f97cf33a0913064c1ff1039b73c3">applyCombineConstantFoldFpUnary</a>, <a href="#a6296facc7f8fdeb45406bf3b7ceac5e7">applyCombineConstPtrAddToI2P</a>, <a href="#ac2377979438dcdab9e664ccd5f975dac">applyCombineDivRem</a>, <a href="#a00301689820a26a9f3b438f6dece6ef0">applyCombineExtendingLoads</a>, <a href="#a346cb10c60061779896b022fb4f75a90">applyCombineI2PToP2I</a>, <a href="#a72848dca494afcf56b2bc2bea4322dc1">applyCombineIndexedLoadStore</a>, <a href="#afb7bd8a1c290e9acba95192edd1be268">applyCombineInsertVecElts</a>, <a href="#aa0691f830cef4a0dadf0f0fbd41e7bca">applyCombineP2IToI2P</a>, <a href="#afae5d269529ade8f678f13c1dde831d1">applyCombineShiftToUnmerge</a>, <a href="#a6b8e5256d82c820e81d9c5b7fb3016ea">applyCombineShlOfExtend</a>, <a href="#a25bc0b47af5d0bcbb989180e1eb3f928">applyCombineShuffleConcat</a>, <a href="#a7ee8b3f43a97b93dde8c791002d306f9">applyCombineShuffleVector</a>, <a href="#ac91aca84eade26acea192464a9cfcde8">applyCombineTruncOfShift</a>, <a href="#a21bee05dda9718594fbfd89855272cd0">applyCombineUnmergeConstant</a>, <a href="#afcc62af19a5d1f2ea5f0e51b3e31893b">applyCombineUnmergeMergeToPlainValues</a>, <a href="#a122b5e6289b7f7f787ea54fb607664b9">applyCombineUnmergeWithDeadLanesToTrunc</a>, <a href="#afe9d6cb97689cb5efb1a5b8f9dc68ea0">applyCombineUnmergeZExtToZExt</a>, <a href="#abe79b9729c8080bf59fa06703f4b3b39">applyExpandFPowI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#af04d5efb4c01491738f47fb92325d238">llvm::AMDGPUCombinerHelper::applyExpandPromotedF16FMed3</a>, <a href="#aa09e8f13910a43ba1b8edc182c7a212c">applyExtendThroughPhis</a>, <a href="#aa3bd6f239db6919e67236164cd0d840f">applyExtractVecEltBuildVec</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#aa20f5e3d228e0f30d2f3c53c53cc6c93">llvm::AMDGPUCombinerHelper::applyFoldableFneg</a>, <a href="#a70fac2d1e6e0b0c95591638ca99cae07">applyFoldBinOpIntoSelect</a>, <a href="#a4ca173dc6e071e5c8c37b62f3d095eb5">applyFsubToFneg</a>, <a href="#a6766b5f9c46b6dd7bb3b45857ec23a0f">applyFunnelShiftConstantModulo</a>, <a href="#ad059815281df2717db5ad88dc3686a51">applyFunnelShiftToRotate</a>, <a href="#a321f2dfbd709348cfd0e1ab66cf0b62c">applyNotCmp</a>, <a href="#afa907eb6ba127a5f4167f5a1671efed0">applyOptBrCondByInvertingCond</a>, <a href="#a0dbebc83f6114ab6cee672147800c858">applyPtrAddZero</a>, <a href="#aaa191c1a15614a3cbf80f3eaf7ca935d">applyRotateOutOfRange</a>, <a href="#a41cebcf8d37086a913f6a5424e0bff66">applySDivByPow2</a>, <a href="#a75ae99f242b3954f52d12c85e53d5f41">applySextInRegOfLoad</a>, <a href="#af2de464ca370d0adf592feedb983fce3">applySextTruncSextLoad</a>, <a href="#a6091fcf4f73ee6e61b585ff63df6b87d">applyShiftImmedChain</a>, <a href="#ad8a483afeb99148394d2586c5601e441">applyShiftOfShiftedLogic</a>, <a href="#ae640b7329e9f881bfe0d4dc6bdddb642">applyShuffleToExtract</a>, <a href="#a42edcf21dec07a1758316328df9216be">applySimplifyAddToSub</a>, <a href="#a198b2e1185e6d3b4eb5e68283a4b504a">applySimplifyURemByPow2</a>, <a href="#a4381e87d4240311eeff998ea33556263">applyUDivByPow2</a>, <a href="#a3012f3ba9714ad992670d388b7c70618">applyUMulHToLShr</a>, <a href="#a6cbfa42d7993571ddbfe46d0c37abafb">applyUseVectorTruncate</a>, <a href="#a1cc3f78b3eded52f46e9f47c03a00934">applyXorOfAndWithSameReg</a>, <a href="#af5d3388e53cb2767927dba7c18c64a00">buildSDivUsingMul</a>, <a href="#af3b3616540da1859ec9d030a76cad94f">buildUDivUsingMul</a>, <a href="#ab45ce737b2839bf39a18e22fbb502ca9">CombinerHelper</a>, <a href="#acf32918c9574aee808e6234d1a2eace9">getBuilder</a>, <a href="#a8c7d20188ce1e7c821f21c6a76f09df0">getContext</a>, <a href="#af5d327beb13472a44f1999b5dfa79503">getMachineFunction</a>, <a href="#a3ba5b820868b659a7cd5717894ee3459">getTargetLowering</a>, <a href="#a84bf6a20255406e9c9f6a52f5c4c7b34">matchCombineConcatVectors</a>, <a href="#a6fd6113581071d7d586e82cf3454bc9a">matchCombineConstPtrAddToI2P</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a5d07561addd0b024b31991b0d09c6beb">llvm::AMDGPUCombinerHelper::matchCombineFmulWithSelectToFldexp</a>, <a href="#a620917cb45d142b76b1eb2dcd76ce689">matchCombineShuffleVector</a>, <a href="#a0f3bc0c5478dd84e0831b5d78a274b47">matchEqualDefs</a>, <a href="#a5fd133d3cc0d8e1b33fe7ae34657d45c">matchExtendThroughPhis</a>, <a href="#a72a5d3fcc788946d3383d547eac00eca">matchMulOBy2</a>, <a href="#a59e682863250eb07290a348d548eee0d">matchNarrowBinopFeedingAnd</a>, <a href="#a8ed1d04073cbd814c13097e138d462e6">matchNotCmp</a>, <a href="#a1abfcdfd643f1f81f3cf28cdfa5746b8">matchPtrAddZero</a>, <a href="#a169aab3da2c9763de9377694467eae61">matchReassocConstantInnerRHS</a>, <a href="#acb1f75635e015ce0751b2053d061be9e">replaceInstWithConstant</a>, <a href="#a4ad0b68c5dc4f76574c35800de2eee45">replaceInstWithConstant</a>, <a href="#a550ed89ae539e7dc552c77df4a05699e">replaceInstWithFConstant</a>, <a href="#a64af7868673efe2f150ab995a6c8c155">replaceInstWithFConstant</a>, <a href="#aaca0b3013530db742551fd22ca8ff655">replaceInstWithUndef</a>, <a href="#a6711738d18f70c1843eac7255405df54">replaceOpcodeWith</a> and <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>.</p>

</div>
</div>

### IsPreLegalize {#a7baaf2859fea3988241fef9589a47557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CombinerHelper::IsPreLegalize</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a18c1004eb8289cb0eb22a92785334aff">llvm::AMDGPUCombinerHelper::AMDGPUCombinerHelper</a>, <a href="#ab45ce737b2839bf39a18e22fbb502ca9">CombinerHelper</a>, <a href="#a7dd411f52d902c7964a59b0f317d3797">isPreLegalize</a> and <a href="#a9e44e0e5bdc7526a1b299ae804752709">matchUseVectorTruncate</a>.</p>

</div>
</div>

### KB {#a73fb0011cd095655aa70f5e6e315b838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GISelKnownBits* llvm::CombinerHelper::KB</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a18c1004eb8289cb0eb22a92785334aff">llvm::AMDGPUCombinerHelper::AMDGPUCombinerHelper</a>, <a href="#af3b3616540da1859ec9d030a76cad94f">buildUDivUsingMul</a>, <a href="#ab45ce737b2839bf39a18e22fbb502ca9">CombinerHelper</a>, <a href="#a4ea850556148cb48cb6be849cd354e1c">getKnownBits</a>, <a href="#ab46d848f3726829246738eb9d78aebf9">matchAddOverflow</a>, <a href="#a50d554a59b9df6a88b36ed551c6e7903">matchCombineShlOfExtend</a>, <a href="#adb530600a4235ed32fefcd44dbf454b4">matchCombineTruncOfShift</a>, <a href="#ade65624657027af925c73882186d00ed">matchCombineZextTrunc</a>, <a href="#a79ff9815398a2c3331b42832035f21c6">matchICmpToLHSKnownBits</a>, <a href="#a98f00ea8e8ca7e8ce4888da5cb138b43">matchICmpToTrueFalseKnownBits</a>, <a href="#a846bbee244f8b3e7ec21bc20f002ed9f">matchOperandIsKnownToBeAPowerOfTwo</a>, <a href="#ad9804726a37a620da474deef91f667eb">matchRedundantAnd</a>, <a href="#ac3416b258eb84253f8111ea33e0beeed">matchRedundantOr</a>, <a href="#a66cc0cc249557274e026f892dbde2fd1">matchRedundantSExtInReg</a>, <a href="#a21e1dc2aa53c4d2b688e9a1e5fe4a95b">matchShiftsTooBig</a> and <a href="#adc129334a6d3d83eb003dd1a49540f80">matchSuboCarryOut</a>.</p>

</div>
</div>

### LI {#aca634f15887089866f5d88dac807786c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LegalizerInfo* llvm::CombinerHelper::LI</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a18c1004eb8289cb0eb22a92785334aff">llvm::AMDGPUCombinerHelper::AMDGPUCombinerHelper</a>, <a href="#ab45ce737b2839bf39a18e22fbb502ca9">CombinerHelper</a>, <a href="#a9569ff6b4f769cb7a667ad4a986589e8">isLegal</a>, <a href="#aab92d16362139d524a7012e2d29c9821">matchBitfieldExtractFromAnd</a>, <a href="#aac1fd587d596fe9aeb38b219966ebd3c">matchBitfieldExtractFromSExtInReg</a>, <a href="#a16d6a69c22795ffc8819bc7bc0e1bae2">matchBitfieldExtractFromShr</a>, <a href="#aa6aaf27c1306e54d433cd45f84ee74e5">matchBitfieldExtractFromShrAnd</a>, <a href="#ab5ece2e19fefdc8f1112b05d6274e649">matchCombineExtendingLoads</a>, <a href="#a50d554a59b9df6a88b36ed551c6e7903">matchCombineShlOfExtend</a> and <a href="#a51f93c65cadd67241250f97598ab1358">matchUDivByConst</a>.</p>

</div>
</div>

### MDT {#acebc61bc26bf037e13a22af30d10b071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree* llvm::CombinerHelper::MDT</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a18c1004eb8289cb0eb22a92785334aff">llvm::AMDGPUCombinerHelper::AMDGPUCombinerHelper</a>, <a href="#ab45ce737b2839bf39a18e22fbb502ca9">CombinerHelper</a> and <a href="#ad99c8ee849f72738dd718fec8d3a1d42">dominates</a>.</p>

</div>
</div>

### MRI {#a9fdbebed8efeedc9c2b5be88e2e33798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::CombinerHelper::MRI</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>


<p>Referenced by <a href="#ab521134f26557f6178240bd7ddc7ab59">applyAshShlToSextInreg</a>, <a href="#a2b46e1c0d91a5df6f3f45d573f833b1a">applyBuildFnMO</a>, <a href="#a51abd9f22e4c8694c58d6719892bd27e">applyCombineAddP2IToPtrAdd</a>, <a href="#a1c95f864b062fedecfd2c4fc32abf47e">applyCombineConcatVectors</a>, <a href="#a94c5f97cf33a0913064c1ff1039b73c3">applyCombineConstantFoldFpUnary</a>, <a href="#a4eeb3124ce1fe172f0e79b5f42be7f5c">applyCombineCopy</a>, <a href="#a00301689820a26a9f3b438f6dece6ef0">applyCombineExtendingLoads</a>, <a href="#a72848dca494afcf56b2bc2bea4322dc1">applyCombineIndexedLoadStore</a>, <a href="#afb7bd8a1c290e9acba95192edd1be268">applyCombineInsertVecElts</a>, <a href="#acaf0ebafd584479c2c6a1a782ff149f9">applyCombineMulToShl</a>, <a href="#afae5d269529ade8f678f13c1dde831d1">applyCombineShiftToUnmerge</a>, <a href="#a6b8e5256d82c820e81d9c5b7fb3016ea">applyCombineShlOfExtend</a>, <a href="#a25bc0b47af5d0bcbb989180e1eb3f928">applyCombineShuffleConcat</a>, <a href="#a7ee8b3f43a97b93dde8c791002d306f9">applyCombineShuffleVector</a>, <a href="#ac91aca84eade26acea192464a9cfcde8">applyCombineTruncOfShift</a>, <a href="#afcc62af19a5d1f2ea5f0e51b3e31893b">applyCombineUnmergeMergeToPlainValues</a>, <a href="#afe9d6cb97689cb5efb1a5b8f9dc68ea0">applyCombineUnmergeZExtToZExt</a>, <a href="#abe79b9729c8080bf59fa06703f4b3b39">applyExpandFPowI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#af04d5efb4c01491738f47fb92325d238">llvm::AMDGPUCombinerHelper::applyExpandPromotedF16FMed3</a>, <a href="#aa09e8f13910a43ba1b8edc182c7a212c">applyExtendThroughPhis</a>, <a href="#aecfc4a2e41e3c67c64ee64ed29103630">applyExtractAllEltsFromBuildVector</a>, <a href="#aa3bd6f239db6919e67236164cd0d840f">applyExtractVecEltBuildVec</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#aa20f5e3d228e0f30d2f3c53c53cc6c93">llvm::AMDGPUCombinerHelper::applyFoldableFneg</a>, <a href="#a70fac2d1e6e0b0c95591638ca99cae07">applyFoldBinOpIntoSelect</a>, <a href="#a4ca173dc6e071e5c8c37b62f3d095eb5">applyFsubToFneg</a>, <a href="#a6766b5f9c46b6dd7bb3b45857ec23a0f">applyFunnelShiftConstantModulo</a>, <a href="#a321f2dfbd709348cfd0e1ab66cf0b62c">applyNotCmp</a>, <a href="#afa907eb6ba127a5f4167f5a1671efed0">applyOptBrCondByInvertingCond</a>, <a href="#a8cd84da3b005d88c0f1b19d868e0a2b3">applyPtrAddImmedChain</a>, <a href="#aaa191c1a15614a3cbf80f3eaf7ca935d">applyRotateOutOfRange</a>, <a href="#a41cebcf8d37086a913f6a5424e0bff66">applySDivByPow2</a>, <a href="#a75ae99f242b3954f52d12c85e53d5f41">applySextInRegOfLoad</a>, <a href="#a6091fcf4f73ee6e61b585ff63df6b87d">applyShiftImmedChain</a>, <a href="#ad8a483afeb99148394d2586c5601e441">applyShiftOfShiftedLogic</a>, <a href="#ae640b7329e9f881bfe0d4dc6bdddb642">applyShuffleToExtract</a>, <a href="#a198b2e1185e6d3b4eb5e68283a4b504a">applySimplifyURemByPow2</a>, <a href="#a4381e87d4240311eeff998ea33556263">applyUDivByPow2</a>, <a href="#a3012f3ba9714ad992670d388b7c70618">applyUMulHToLShr</a>, <a href="#a6cbfa42d7993571ddbfe46d0c37abafb">applyUseVectorTruncate</a>, <a href="#a1cc3f78b3eded52f46e9f47c03a00934">applyXorOfAndWithSameReg</a>, <a href="#af5d3388e53cb2767927dba7c18c64a00">buildSDivUsingMul</a>, <a href="#af3b3616540da1859ec9d030a76cad94f">buildUDivUsingMul</a>, <a href="#a1e388c06478515344e2fce08b1357025">canCombineFMadOrFMA</a>, <a href="#ab45ce737b2839bf39a18e22fbb502ca9">CombinerHelper</a>, <a href="#a0ae177a2136d1b90b767d57dbe6a419c">getRegBank</a>, <a href="#a15a55602a4ab55a9ae6ad194922d6f72">matchAddEToAddO</a>, <a href="#a597eabfac4d80feedf71d122bbaf4e00">matchAddOfVScale</a>, <a href="#ab46d848f3726829246738eb9d78aebf9">matchAddOverflow</a>, <a href="#a5036bb5c5ecc303b0416937c6eb9d6e3">matchAddSubSameReg</a>, <a href="#aac73c9c9888dd26d04e2eeb87aca714c">matchAndOrDisjointMask</a>, <a href="#afe660eb45c9320803ef32f88757a79c7">matchAshrShlToSextInreg</a>, <a href="#a2d378068adc2de015d79593557be7c37">matchBinOpSameVal</a>, <a href="#aab92d16362139d524a7012e2d29c9821">matchBitfieldExtractFromAnd</a>, <a href="#aac1fd587d596fe9aeb38b219966ebd3c">matchBitfieldExtractFromSExtInReg</a>, <a href="#a16d6a69c22795ffc8819bc7bc0e1bae2">matchBitfieldExtractFromShr</a>, <a href="#aa6aaf27c1306e54d433cd45f84ee74e5">matchBitfieldExtractFromShrAnd</a>, <a href="#aa654694a53f814ff3cb1b2d04513da6e">matchBuildVectorIdentityFold</a>, <a href="#a7c6878dbda903ec9201f83db42d93fdc">matchCanonicalizeFCmp</a>, <a href="#ae7e76e88a680a8f2de889a6f6928fcc0">matchCanonicalizeICmp</a>, <a href="#ae88fdd4a40851c70c1f04282174034c2">matchCastOfBuildVector</a>, <a href="#aeb8af468cabe232d8d64944acf6930b7">matchCastOfInteger</a>, <a href="#afaeb891d2410d3aaf4d95fc61028f7b4">matchCastOfSelect</a>, <a href="#a642669b9384277a3f5fc513928d6bee3">matchCombineAddP2IToPtrAdd</a>, <a href="#aebbd8556be493cfb10fce51e933d7e2e">matchCombineAnyExtTrunc</a>, <a href="#a84bf6a20255406e9c9f6a52f5c4c7b34">matchCombineConcatVectors</a>, <a href="#a6fd6113581071d7d586e82cf3454bc9a">matchCombineConstPtrAddToI2P</a>, <a href="#a5fc01df6a11c709c2e05f5ef212d239d">matchCombineCopy</a>, <a href="#a2ea6814df78ae99e8a540fb4e8fc4ed1">matchCombineDivRem</a>, <a href="#ab5ece2e19fefdc8f1112b05d6274e649">matchCombineExtendingLoads</a>, <a href="#a28a0f1422b780a83a9632e5d46993dfc">matchCombineExtractedVectorLoad</a>, <a href="#a54d65481969f8d9628b5ee128c99212b">matchCombineFAddFMAFMulToFMadOrFMA</a>, <a href="#a5fbed34899e8c323d738ef2eac96dd20">matchCombineFAddFMulToFMadOrFMA</a>, <a href="#a246c328def50bbd9e892666ae3fb1947">matchCombineFAddFpExtFMulToFMadOrFMA</a>, <a href="#af73a2a8f01e0df7eb8908768292dd30e">matchCombineFAddFpExtFMulToFMadOrFMAAggressive</a>, <a href="#ac31ecf657d06f3e6f617cd4d6e035f1a">matchCombineFMinMaxNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a5d07561addd0b024b31991b0d09c6beb">llvm::AMDGPUCombinerHelper::matchCombineFmulWithSelectToFldexp</a>, <a href="#a541aab24d54889f539ea0e41c6a00b2c">matchCombineFSubFMulToFMadOrFMA</a>, <a href="#ade46635032e4ec34657bc9b237d37e0b">matchCombineFSubFNegFMulToFMadOrFMA</a>, <a href="#a4c9b7bf9027b6c116d92fbebd2ba8372">matchCombineFSubFpExtFMulToFMadOrFMA</a>, <a href="#ac4a2ebe747c416cbe4efb4b77ba2b588">matchCombineFSubFpExtFNegFMulToFMadOrFMA</a>, <a href="#a8269c100cbd38131124eb3c261193bfc">matchCombineI2PToP2I</a>, <a href="#a570b6dfed72efec6554e992d5afdd1e4">matchCombineInsertVecElts</a>, <a href="#a5d600f23e7d301bfcf60b292eaba31ef">matchCombineLoadWithAndMask</a>, <a href="#a5709dda6e8778748a5159cb8ed2d37f6">matchCombineMergeUnmerge</a>, <a href="#a6f6d05c3170477dae214b4f7ec6dc3fb">matchCombineMulToShl</a>, <a href="#adb9e9ab4728e40478a30f57d57508f4e">matchCombineShiftToUnmerge</a>, <a href="#a50d554a59b9df6a88b36ed551c6e7903">matchCombineShlOfExtend</a>, <a href="#a7474d0e2d570539a3e93b86c67b1bae9">matchCombineShuffleConcat</a>, <a href="#a620917cb45d142b76b1eb2dcd76ce689">matchCombineShuffleVector</a>, <a href="#a82dc058091aed201fb1fbdd0ab8e5c3d">matchCombineSubToAdd</a>, <a href="#adb530600a4235ed32fefcd44dbf454b4">matchCombineTruncOfShift</a>, <a href="#ad593882fdec13fdc1832fa224050666e">matchCombineUnmergeConstant</a>, <a href="#afc1c60085dd818c0586c87f44db3d10a">matchCombineUnmergeMergeToPlainValues</a>, <a href="#a6fd7ed1e4ed0a6d0414dde08a4ef6935">matchCombineUnmergeUndef</a>, <a href="#abb7390ce20d98328a9fb3b2fe779e164">matchCombineUnmergeWithDeadLanesToTrunc</a>, <a href="#a19db4f1b27ef7d29e4c77f6f7dd0ec5d">matchCombineUnmergeZExtToZExt</a>, <a href="#ade65624657027af925c73882186d00ed">matchCombineZextTrunc</a>, <a href="#a2b4c477b0ac10183266094734941f417">matchCommuteConstantToRHS</a>, <a href="#ac1285dc5bae6f80f64a0d757b136279d">matchCommuteFPConstantToRHS</a>, <a href="#a0255cbf70d03b31784d719fb73637002">matchCommuteShift</a>, <a href="#a12106e55b2bdb2132757797665813f21">matchConstantFoldBinOp</a>, <a href="#aa8ae6cc9d1541ff2e91dd25d1da665d4">matchConstantFoldCastOp</a>, <a href="#add44d478a1c329e77659000039f6ae74">matchConstantFoldFMA</a>, <a href="#a9ba3e97ad5883fd02115afb289d2ccdd">matchConstantFoldFPBinOp</a>, <a href="#aa1cd7c807d2387bd9f8efe4a88cf1eb8">matchConstantFPOp</a>, <a href="#a4cc9ea97355c96a953b9a6fc5ce2fcc2">matchConstantLargerBitWidth</a>, <a href="#ac975f07f5ebdceac6c93312485b74af2">matchConstantOp</a>, <a href="#abf78ec9a89c8134a3b9b6212184214fe">matchConstantSelectCmp</a>, <a href="#a575d0877b1d93fc6c416bf667876fb75">matchDivByPow2</a>, <a href="#a0f3bc0c5478dd84e0831b5d78a274b47">matchEqualDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a78bf4f9ce583ccdc1b4dbaf6c56a0030">llvm::AMDGPUCombinerHelper::matchExpandPromotedF16FMed3</a>, <a href="#a5fd133d3cc0d8e1b33fe7ae34657d45c">matchExtendThroughPhis</a>, <a href="#a7b617a5a6a2773b70ea354e1dffceff7">matchExtOfExt</a>, <a href="#a8bd2bb9d716a15d8d914b0236e32e2ee">matchExtractAllEltsFromBuildVector</a>, <a href="#a21a291953b9b99793faf8bea9286ebd7">matchExtractVecEltBuildVec</a>, <a href="#a4f83785782b043b22a617554b65b5f0a">matchExtractVectorElement</a>, <a href="#af7bcd2506b90a78c86a2ac061132783f">matchExtractVectorElementWithBuildVector</a>, <a href="#a2a97e27cc61249c732f88ca2b63ce73f">matchExtractVectorElementWithBuildVectorTrunc</a>, <a href="#a3d2f7a0f835e800e04b1fae871054e01">matchExtractVectorElementWithDifferentIndices</a>, <a href="#a89092e8630095ccf5b948def71d884f1">matchExtractVectorElementWithShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#aca13b2618c4733bb6b46c2667fbd847b">llvm::AMDGPUCombinerHelper::matchFoldableFneg</a>, <a href="#a71eafce3200f8a358c6855e3b6ee0a51">matchFoldAMinusC1MinusC2</a>, <a href="#a183457f9d99bea5ee1a2fd06ceb9bb99">matchFoldAMinusC1PlusC2</a>, <a href="#a207867c80e7ad2da595e7a9adedcb612">matchFoldAPlusC1MinusC2</a>, <a href="#aa3f4c3db433c1eb3e4feab24f3afb7db">matchFoldBinOpIntoSelect</a>, <a href="#a6b45fbac775c8ccd0b606e0a5ea671bf">matchFoldC1Minus2MinusC2</a>, <a href="#a05e094eb5ea044b72cda4473bc6d78fc">matchFoldC2MinusAPlusC1</a>, <a href="#ae2bd5329e5726d560529de68df90503c">matchFreezeOfSingleMaybePoisonOperand</a>, <a href="#abb80926c82768fa525eee40937db0d81">matchFsubToFneg</a>, <a href="#a6618ef11a5296a1388144d2fdae9f6e3">matchFunnelShiftToRotate</a>, <a href="#aab86990eacd037e1c72749c3342d410e">matchHoistLogicOpWithSameOpcodeHands</a>, <a href="#a79ff9815398a2c3331b42832035f21c6">matchICmpToLHSKnownBits</a>, <a href="#a98f00ea8e8ca7e8ce4888da5cb138b43">matchICmpToTrueFalseKnownBits</a>, <a href="#a881fab40a57c999ccf31ebc208f8d859">matchInsertExtractVecEltOutOfBounds</a>, <a href="#a4726b2a74fcb79e35ec78c54ec7aa8ee">matchInsertVectorElementOOB</a>, <a href="#a070e7ae88917971c8b99b3bb7f3d5942">matchLoadOrCombine</a>, <a href="#a65bdadc254b269b10b7e67d39a9527dc">matchMergeXAndUndef</a>, <a href="#a518e2853dfbfd37675a14b6bf1ca6c90">matchMergeXAndZero</a>, <a href="#ad43afc169977548bbf11956b91156040">matchMulOBy0</a>, <a href="#a72a5d3fcc788946d3383d547eac00eca">matchMulOBy2</a>, <a href="#a56ee7200c7a0fb8ed2b9f98288d83ff2">matchMulOfVScale</a>, <a href="#aac58443a61bc007251b27585f5887c6d">matchNarrowBinop</a>, <a href="#a59e682863250eb07290a348d548eee0d">matchNarrowBinopFeedingAnd</a>, <a href="#a2f87fb73ebb3f5d6d7e49e99fa478fa3">matchNonNegZext</a>, <a href="#a8ed1d04073cbd814c13097e138d462e6">matchNotCmp</a>, <a href="#a846bbee244f8b3e7ec21bc20f002ed9f">matchOperandIsKnownToBeAPowerOfTwo</a>, <a href="#adf1110382dae21e5397a098cc5a08554">matchOperandIsUndef</a>, <a href="#a67c4ed813faad031bd68547fc3b51244">matchOperandIsZero</a>, <a href="#a3748ec69250bb09564362325c334c9ae">matchOrShiftToFunnelShift</a>, <a href="#aeba19575c25ff51fe86cca1b6a3536a9">matchOverlappingAnd</a>, <a href="#a3acff99aeccfa086e7fbef44df8c0ce1">matchPtrAddImmedChain</a>, <a href="#a1abfcdfd643f1f81f3cf28cdfa5746b8">matchPtrAddZero</a>, <a href="#aeb0aa3738412a41ec60b41d08d849078">matchReassocConstantInnerLHS</a>, <a href="#a169aab3da2c9763de9377694467eae61">matchReassocConstantInnerRHS</a>, <a href="#aaab53ed6a166f868585b2a095c546edc">matchReassocFoldConstantsInSubTree</a>, <a href="#a7c17b27587a29f1c02dbf942ed6fc808">matchReassocPtrAdd</a>, <a href="#ad9804726a37a620da474deef91f667eb">matchRedundantAnd</a>, <a href="#aaf88f3025beeaebb5bd345ebe277711c">matchRedundantBinOpInEquality</a>, <a href="#a5cd94b9d480eadb598a5125b9b294efe">matchRedundantNegOperands</a>, <a href="#ac3416b258eb84253f8111ea33e0beeed">matchRedundantOr</a>, <a href="#a66cc0cc249557274e026f892dbde2fd1">matchRedundantSExtInReg</a>, <a href="#abe5511c3ea29fcdddf397489e2b3ba9c">matchRotateOutOfRange</a>, <a href="#a23ff02c4dc0c7eb4bc173bc9af346765">matchSDivByConst</a>, <a href="#a9098323777f98b3dd53bef412554961c">matchSelectIMinMax</a>, <a href="#a1561c4d75b24c0c46dcb05c8ec0bda65">matchSelectSameVal</a>, <a href="#a8f5dd5583d12f1c7dcf63b86ff444394">matchSextInRegOfLoad</a>, <a href="#a5036ae118b8d8b9debc1c596eff93259">matchSextOfTrunc</a>, <a href="#a56afecdec991e6c14189691c37140ad1">matchSextTruncSextLoad</a>, <a href="#a33c6405fe05b24b5d3f9c0ec0ed7f9ae">matchShiftImmedChain</a>, <a href="#a8434510d79fe87971bb903ab82cc1fc3">matchShiftOfShiftedLogic</a>, <a href="#a21e1dc2aa53c4d2b688e9a1e5fe4a95b">matchShiftsTooBig</a>, <a href="#a5b5001e37af42df3e8202151fe08b3c9">matchShlOfVScale</a>, <a href="#a6d345595bdc1655f01d68419353184cf">matchShuffleDisjointMask</a>, <a href="#a3df1d9d3afbfe5db4027289cf28d4726">matchShuffleUndefRHS</a>, <a href="#a4a44e20b38fdd26858c54152cf52acc2">matchSimplifyAddToSub</a>, <a href="#a2e6e1c84d8b84dbd2101236bca332d95">matchSimplifyNegMinMax</a>, <a href="#ad133fd24c3d69592d832837ce6a24c75">matchSimplifySelectToMinMax</a>, <a href="#aeac793ece837d10b193280411783d33e">matchSubAddSameReg</a>, <a href="#adc129334a6d3d83eb003dd1a49540f80">matchSuboCarryOut</a>, <a href="#ac88c813e35b6d1a4966b0ee24a5c8b9a">matchSubOfVScale</a>, <a href="#a633b0486bab32c1b91cc923d82a72c2d">matchTruncateOfExt</a>, <a href="#ac6cad51d01e79fc7c77d3c58d58394da">matchTruncBuildVectorFold</a>, <a href="#a350580c34bfdfd93dbeb51e3f2b44fa4">matchTruncLshrBuildVectorFold</a>, <a href="#a51f93c65cadd67241250f97598ab1358">matchUDivByConst</a>, <a href="#acd5de1d4698c082f674654d67b42f1ca">matchUMulHToLShr</a>, <a href="#aac6f62bcef60abeb3f12a394f6e57ead">matchUndefSelectCmp</a>, <a href="#a9ede1eaa682d8cb883fcbdfc3d894e70">matchUndefStore</a>, <a href="#a12794dfd41dd116d9e295524d932f6c0">matchUnmergeValuesAnyExtBuildVector</a>, <a href="#a9e44e0e5bdc7526a1b299ae804752709">matchUseVectorTruncate</a>, <a href="#a62065b49533b4287092563e507342296">matchXorOfAndWithSameReg</a>, <a href="#a27942d2942b84e3453b75e3417def841">matchZextOfTrunc</a>, <a href="#a290f07593ec0820655db5efe88422c44">replaceRegOpWith</a>, <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>, <a href="#af1ac0d7bbf4c5e4b5ed052554b54cf5c">replaceSingleDefInstWithOperand</a>, <a href="#a25ff4284ba96727747d6ceb7ef16b95d">replaceSingleDefInstWithReg</a>, <a href="#abefb646c754368c3ecc32c050c5bacd5">setRegBank</a> and <a href="#a9a9739cf49c46adcb76ac7e2dc13545c">tryReassocBinOp</a>.</p>

</div>
</div>

### Observer {#ada82db26b18384aaa5d15440061bf5a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GISelChangeObserver&amp; llvm::CombinerHelper::Observer</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a18c1004eb8289cb0eb22a92785334aff">llvm::AMDGPUCombinerHelper::AMDGPUCombinerHelper</a>, <a href="#a00301689820a26a9f3b438f6dece6ef0">applyCombineExtendingLoads</a>, <a href="#acaf0ebafd584479c2c6a1a782ff149f9">applyCombineMulToShl</a>, <a href="#af1832f2fdfaaea5fb0e64e8a4ea11ee0">applyCommuteBinOpOperands</a>, <a href="#ad059815281df2717db5ad88dc3686a51">applyFunnelShiftToRotate</a>, <a href="#a321f2dfbd709348cfd0e1ab66cf0b62c">applyNotCmp</a>, <a href="#afa907eb6ba127a5f4167f5a1671efed0">applyOptBrCondByInvertingCond</a>, <a href="#a8cd84da3b005d88c0f1b19d868e0a2b3">applyPtrAddImmedChain</a>, <a href="#aaa191c1a15614a3cbf80f3eaf7ca935d">applyRotateOutOfRange</a>, <a href="#a6091fcf4f73ee6e61b585ff63df6b87d">applyShiftImmedChain</a>, <a href="#a1cc3f78b3eded52f46e9f47c03a00934">applyXorOfAndWithSameReg</a>, <a href="#ab45ce737b2839bf39a18e22fbb502ca9">CombinerHelper</a>, <a href="#a15a55602a4ab55a9ae6ad194922d6f72">matchAddEToAddO</a>, <a href="#aac73c9c9888dd26d04e2eeb87aca714c">matchAndOrDisjointMask</a>, <a href="#a82dc058091aed201fb1fbdd0ab8e5c3d">matchCombineSubToAdd</a>, <a href="#ae2bd5329e5726d560529de68df90503c">matchFreezeOfSingleMaybePoisonOperand</a>, <a href="#a72a5d3fcc788946d3383d547eac00eca">matchMulOBy2</a>, <a href="#a59e682863250eb07290a348d548eee0d">matchNarrowBinopFeedingAnd</a>, <a href="#aeb0aa3738412a41ec60b41d08d849078">matchReassocConstantInnerLHS</a>, <a href="#a169aab3da2c9763de9377694467eae61">matchReassocConstantInnerRHS</a>, <a href="#aaab53ed6a166f868585b2a095c546edc">matchReassocFoldConstantsInSubTree</a>, <a href="#a5cd94b9d480eadb598a5125b9b294efe">matchRedundantNegOperands</a>, <a href="#a6711738d18f70c1843eac7255405df54">replaceOpcodeWith</a>, <a href="#a290f07593ec0820655db5efe88422c44">replaceRegOpWith</a> and <a href="#a28ea263eb2492e410f764fc705781c05">replaceRegWith</a>.</p>

</div>
</div>

### RBI {#ad388844fc6e8318b52ee7cf5a88b8c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo* llvm::CombinerHelper::RBI</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>


<p>Referenced by <a href="#ab45ce737b2839bf39a18e22fbb502ca9">CombinerHelper</a> and <a href="#a0ae177a2136d1b90b767d57dbe6a419c">getRegBank</a>.</p>

</div>
</div>

### TRI {#ad8de57b7e86580531aec66fde618bef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::CombinerHelper::TRI</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a>.</p>


<p>Referenced by <a href="#ab45ce737b2839bf39a18e22fbb502ca9">CombinerHelper</a>, <a href="#a0ae177a2136d1b90b767d57dbe6a419c">getRegBank</a> and <a href="#ae2bd5329e5726d560529de68df90503c">matchFreezeOfSingleMaybePoisonOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerhelper-h">CombinerHelper.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelperartifacts-cpp">CombinerHelperArtifacts.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercasts-cpp">CombinerHelperCasts.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpercompares-cpp">CombinerHelperCompares.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelpervectorops-cpp">CombinerHelperVectorOps.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
