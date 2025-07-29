---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-r600controlflowfinalizer-cpp-/r600controlflowfinalizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `R600ControlFlowFinalizer` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e773a311775b68cbc9b1188d8478631">ClauseFile</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ControlFlowInstruction { <a href="#a310370a3f7efd004f358e76eaf3389a8">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c635a591d103185cb191114397863fa">R600ControlFlowFinalizer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab0c0f47a6a686867561fa0275a393b1">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#aab0c0f47a6a686867561fa0275a393b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fdf4ca68127c31de34cdf395fb2f01b">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a2fdf4ca68127c31de34cdf395fb2f01b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61dfd7f75ed030087a4808719b61175b">IsTrivialInst</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa83decd8e03f0141b48f59b45601dcde">getHWInstrDesc</a> (ControlFlowInstruction CFI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af043977d1d071260d464421bfdb027c9">isCompatibleWithClause</a> (const MachineInstr &amp;MI, std::set&lt; unsigned &gt; &amp;DstRegs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">ClauseFile</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69bbe5b807db1d75a01cc4f6b116889c">MakeFetchClause</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator &amp;I) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a762721818df6e47005a0a8d6e05e0c30">getLiteral</a> (MachineInstr &amp;MI, std::vector&lt; MachineOperand * &gt; &amp;Lits) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75428a42659ad073ac1bf98b0a987080">insertLiterals</a> (MachineBasicBlock::iterator InsertPos, const std::vector&lt; unsigned &gt; &amp;Literals) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">ClauseFile</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeb0d6a6d72f930c2aeeb74dca2f2c98">MakeALUClause</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator &amp;I) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a597cd0720c2a2b3fddcf2dc172cabd2b">EmitFetchClause</a> (MachineBasicBlock::iterator InsertPos, const DebugLoc &amp;DL, ClauseFile &amp;Clause, unsigned &amp;CfCount)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf6da8f86ae0c7a940230ead4d241568">EmitALUClause</a> (MachineBasicBlock::iterator InsertPos, const DebugLoc &amp;DL, ClauseFile &amp;Clause, unsigned &amp;CfCount)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a70606cfa1831cd59eb33633a7ca02">CounterPropagateAddr</a> (MachineInstr &amp;MI, unsigned Addr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fae2af3e185f2a7055457dce5738256">CounterPropagateAddr</a> (const std::set&lt; MachineInstr * &gt; &amp;MIs, unsigned Addr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo">R600InstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2fa1b885fd6d69e35c3570e7bc93561">TII</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/r600registerinfo">R600RegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d50123e1201e4a460526d91d34eba3a">TRI</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad88aca75418b5a093b8aa2bbd96fbcd">MaxFetchInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/r600subtarget">R600Subtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a271f87213fa219d3b4fd30907b1b2d49">ST</a> = nullptr</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5040d3bb30a0dc74c4be66bddf853785">ID</a> = 0</td>
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


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ClauseFile {#a7e773a311775b68cbc9b1188d8478631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::ClauseFile =  std::pair&lt;MachineInstr *, std::vector&lt;MachineInstr *&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### ControlFlowInstruction {#a310370a3f7efd004f358e76eaf3389a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::ControlFlowInstruction </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CF_TC<a id="a310370a3f7efd004f358e76eaf3389a8a3c859eb7ba43e36da257ff01edce4655"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CF_VC<a id="a310370a3f7efd004f358e76eaf3389a8ac01cd43c65dd3bca8968af93bf539395"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CF_CALL_FS<a id="a310370a3f7efd004f358e76eaf3389a8ae23c0d9a2a5eb258639294c2f1f0c01a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CF_WHILE_LOOP<a id="a310370a3f7efd004f358e76eaf3389a8ad271d9b7b193a6f02a09af58255516fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CF_END_LOOP<a id="a310370a3f7efd004f358e76eaf3389a8a3586e7c97dcf7cfa7be46b0cfe7f0fe4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CF_LOOP_BREAK<a id="a310370a3f7efd004f358e76eaf3389a8aecacf50f62e22a8341faa89c5c710f4a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CF_LOOP_CONTINUE<a id="a310370a3f7efd004f358e76eaf3389a8a5ad7a3e5365ec09d1ac3e80afddc5a02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CF_JUMP<a id="a310370a3f7efd004f358e76eaf3389a8a398c88a1004ba27a1ffafa33d144e75a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CF_ELSE<a id="a310370a3f7efd004f358e76eaf3389a8aec76b97fbb4dd9fc37507f96eafef26d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CF_POP<a id="a310370a3f7efd004f358e76eaf3389a8af71cf50463d9664b11e9c2c7c7f0d8b9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CF_END<a id="a310370a3f7efd004f358e76eaf3389a8a92c57d66ae625d635312064328908a1f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### R600ControlFlowFinalizer() {#a8c635a591d103185cb191114397863fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::R600ControlFlowFinalizer ()</td>
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



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>References <a href="#a5040d3bb30a0dc74c4be66bddf853785">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abc2ce5a41f345524750d286c4284f9cf">llvm::createR600ControlFlowFinalizer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPassName() {#a2fdf4ca68127c31de34cdf395fb2f01b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### runOnMachineFunction() {#aab0c0f47a6a686867561fa0275a393b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca1a9f243b16678fc294567b72bbe87223">llvm::CallingConv::AMDGPU_VS</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/r600machinefunctioninfo/#a6501e3dc951f70a985684bc1cc2a9140">llvm::R600MachineFunctionInfo::CFStackSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#accc60d2019e9dff57bb0918a94422ebb">llvm::MachineInstr::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a9d017af749f76484cb9aec9ff6e4330c">llvm::MachineFunction::end</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/r600subtarget/#a4bb2269867e8aad484e06b810108b657">llvm::R600Subtarget::getTexVTXClauseSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/anonymous-r600controlflowfinalizer-cpp-/cfstack/#a3cbd8d5baba03b690bd10714597d7317">anonymous{R600ControlFlowFinalizer.cpp}::CFStack::MaxStackSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/anonymous-r600controlflowfinalizer-cpp-/cfstack/#a8cb00b7a7dd2c04b404cbb1c3d59102b">anonymous{R600ControlFlowFinalizer.cpp}::CFStack::popBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-r600controlflowfinalizer-cpp-/cfstack/#a258f83b2a91f1105db6188191b6983ee">anonymous{R600ControlFlowFinalizer.cpp}::CFStack::popLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-r600controlflowfinalizer-cpp-/cfstack/#af6ef55f76ee048b15e914278b184aea6">anonymous{R600ControlFlowFinalizer.cpp}::CFStack::pushBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-r600controlflowfinalizer-cpp-/cfstack/#ace0acee50018dfffbd3bd808cd72106f">anonymous{R600ControlFlowFinalizer.cpp}::CFStack::pushLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-r600controlflowfinalizer-cpp-/cfstack/#afb42fc4dd57f5e04e5b1520d1665aa58">anonymous{R600ControlFlowFinalizer.cpp}::CFStack::requiresWorkAroundForInst</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### CounterPropagateAddr() {#a20a70606cfa1831cd59eb33633a7ca02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::CounterPropagateAddr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Addr)</td>
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



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### CounterPropagateAddr() {#a0fae2af3e185f2a7055457dce5738256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::CounterPropagateAddr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; MIs, unsigned Addr)</td>
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



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### EmitALUClause() {#abf6da8f86ae0c7a940230ead4d241568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::EmitALUClause (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertPos, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, ClauseFile &amp; Clause, unsigned &amp; CfCount)</td>
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



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### EmitFetchClause() {#a597cd0720c2a2b3fddcf2dc172cabd2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::EmitFetchClause (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertPos, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, ClauseFile &amp; Clause, unsigned &amp; CfCount)</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### getHWInstrDesc() {#aa83decd8e03f0141b48f59b45601dcde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrDesc &amp; anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::getHWInstrDesc (ControlFlowInstruction CFI)</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### getLiteral() {#a762721818df6e47005a0a8d6e05e0c30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::getLiteral (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt; &amp; Lits)</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### insertLiterals() {#a75428a42659ad073ac1bf98b0a987080}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::insertLiterals (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertPos, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; unsigned &gt; &amp; Literals)</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### isCompatibleWithClause() {#af043977d1d071260d464421bfdb027c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::isCompatibleWithClause (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::set&lt; unsigned &gt; &amp; DstRegs)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### IsTrivialInst() {#a61dfd7f75ed030087a4808719b61175b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::IsTrivialInst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### MakeALUClause() {#adeb0d6a6d72f930c2aeeb74dca2f2c98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClauseFile anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::MakeALUClause (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; I)</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### MakeFetchClause() {#a69bbe5b807db1d75a01cc4f6b116889c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClauseFile anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::MakeFetchClause (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; I)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MaxFetchInst {#aad88aca75418b5a093b8aa2bbd96fbcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::MaxFetchInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### ST {#a271f87213fa219d3b4fd30907b1b2d49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const R600Subtarget* anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::ST = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### TII {#ac2fa1b885fd6d69e35c3570e7bc93561}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const R600InstrInfo* anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

### TRI {#a6d50123e1201e4a460526d91d34eba3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const R600RegisterInfo* anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a5040d3bb30a0dc74c4be66bddf853785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">R600 Control Flow false char R600ControlFlowFinalizer::ID = 0</td>
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



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a>.</p>


<p>Referenced by <a href="#a8c635a591d103185cb191114397863fa">R600ControlFlowFinalizer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600controlflowfinalizer-cpp">R600ControlFlowFinalizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
