---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-simemorylegalizer-cpp-/simemorylegalizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SIMemoryLegalizer` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer { ... }
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3278517f82c41fcf2c3482d645653c4f">SIMemoryLegalizer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10405db39963d1a6c70496c5ddccb210">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#a10405db39963d1a6c70496c5ddccb210">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a356735bd352aaf9f7ea6aa928d2299">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a0a356735bd352aaf9f7ea6aa928d2299">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a599c4517601e4b05d04b3093a7968a91">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#a599c4517601e4b05d04b3093a7968a91">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6db006d7a41b46dcbd3f46fef38f7aba">isAtomicRet</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true iff instruction <span class="doxyComputerOutput">MI</span> is a atomic instruction that returns a result. <a href="#a6db006d7a41b46dcbd3f46fef38f7aba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c1cd9abd99df528f5b336213150546f">removeAtomicPseudoMIs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes all processed atomic pseudo instructions from the current function. <a href="#a3c1cd9abd99df528f5b336213150546f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acce97b7ba71478a76f01c7038a191761">expandLoad</a> (const SIMemOpInfo &amp;MOI, MachineBasicBlock::iterator &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expands load operation <span class="doxyComputerOutput">MI</span>. <a href="#acce97b7ba71478a76f01c7038a191761">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f75732a19ee3df2250258bb32b843b7">expandStore</a> (const SIMemOpInfo &amp;MOI, MachineBasicBlock::iterator &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expands store operation <span class="doxyComputerOutput">MI</span>. <a href="#a6f75732a19ee3df2250258bb32b843b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd43610b0839f6d2389aa2ec32ed50b3">expandAtomicFence</a> (const SIMemOpInfo &amp;MOI, MachineBasicBlock::iterator &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expands atomic fence operation <span class="doxyComputerOutput">MI</span>. <a href="#afd43610b0839f6d2389aa2ec32ed50b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cee21aef20ea5abbed1f09ab59e8ad1">expandAtomicCmpxchgOrRmw</a> (const SIMemOpInfo &amp;MOI, MachineBasicBlock::iterator &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expands atomic cmpxchg or rmw operation <span class="doxyComputerOutput">MI</span>. <a href="#a3cee21aef20ea5abbed1f09ab59e8ad1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol">SICacheControl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35a9a510a116b62866db1ef224321dcc">CC</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache Control. <a href="#a35a9a510a116b62866db1ef224321dcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::list&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a303b559dc7a690e89873bba9c1ecc8f6">AtomicPseudoMIs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of atomic pseudo instructions. <a href="#a303b559dc7a690e89873bba9c1ecc8f6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeaa8eace70f2f21e4718d2b749ee942">ID</a> = 0</td>
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


<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIMemoryLegalizer() {#a3278517f82c41fcf2c3482d645653c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::SIMemoryLegalizer ()</td>
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



<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="#afeaa8eace70f2f21e4718d2b749ee942">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a10405db39963d1a6c70496c5ddccb210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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

<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this.</p>


<p>For MachineFunctionPasses, calling AU.preservesCFG() indicates that the pass does not modify the MachineBasicBlock CFG.</p>


<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af11a6ebf7ab3c388234cb6d5378439a3">llvm::AnalysisUsage::setPreservesCFG</a>.</p>

</div>
</div>

### getPassName() {#a0a356735bd352aaf9f7ea6aa928d2299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::getPassName ()</td>
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


<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/typepromotion-cpp/#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a599c4517601e4b05d04b3093a7968a91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIMemoryLegalizer::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sicachecontrol/#a52d080c45233af5a033d89cfd7dbef1f">anonymous{SIMemoryLegalizer.cpp}::SICacheControl::create</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopaccess/#aa3833cdce3bbe872457b464aac85063c">anonymous{SIMemoryLegalizer.cpp}::SIMemOpAccess::getAtomicCmpxchgOrRmwInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopaccess/#a5c04c83bc2a4fbb5e62eca984f4b978c">anonymous{SIMemoryLegalizer.cpp}::SIMemOpAccess::getAtomicFenceInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopaccess/#a2c9eaaf14f952bf7650b2b641dd189e1">anonymous{SIMemoryLegalizer.cpp}::SIMemOpAccess::getLoadInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo/#a92d88d2c22a932066d294be13e2baf55">llvm::MachineModuleInfo::getObjFileInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopaccess/#aa0ceca49cd13bf370627ce12620c1df5">anonymous{SIMemoryLegalizer.cpp}::SIMemOpAccess::getStoreInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca55d8f9babd910d3931296db01832f171">llvm::SIInstrFlags::maybeAtomic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### expandAtomicCmpxchgOrRmw() {#a3cee21aef20ea5abbed1f09ab59e8ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIMemoryLegalizer::expandAtomicCmpxchgOrRmw (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopinfo">SIMemOpInfo</a> &amp; MOI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expands atomic cmpxchg or rmw operation <span class="doxyComputerOutput">MI</span>.</p>


<p>Returns true if instructions are added/deleted or <span class="doxyComputerOutput">MI</span> is modified, false otherwise.</p>


<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

### expandAtomicFence() {#afd43610b0839f6d2389aa2ec32ed50b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIMemoryLegalizer::expandAtomicFence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopinfo">SIMemOpInfo</a> &amp; MOI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expands atomic fence operation <span class="doxyComputerOutput">MI</span>.</p>


<p>Returns true if instructions are added/deleted or <span class="doxyComputerOutput">MI</span> is modified, false otherwise.</p>


<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

### expandLoad() {#acce97b7ba71478a76f01c7038a191761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIMemoryLegalizer::expandLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopinfo">SIMemOpInfo</a> &amp; MOI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expands load operation <span class="doxyComputerOutput">MI</span>.</p>


<p>Returns true if instructions are added/deleted or <span class="doxyComputerOutput">MI</span> is modified, false otherwise.</p>


<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

### expandStore() {#a6f75732a19ee3df2250258bb32b843b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIMemoryLegalizer::expandStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/simemopinfo">SIMemOpInfo</a> &amp; MOI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expands store operation <span class="doxyComputerOutput">MI</span>.</p>


<p>Returns true if instructions are added/deleted or <span class="doxyComputerOutput">MI</span> is modified, false otherwise.</p>


<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

### isAtomicRet() {#a6db006d7a41b46dcbd3f46fef38f7aba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::isAtomicRet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return true iff instruction <span class="doxyComputerOutput">MI</span> is a atomic instruction that returns a result.</p>

<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

### removeAtomicPseudoMIs() {#a3c1cd9abd99df528f5b336213150546f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIMemoryLegalizer::removeAtomicPseudoMIs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes all processed atomic pseudo instructions from the current function.</p>


<p>Returns true if current function is modified, false otherwise.</p>


<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AtomicPseudoMIs {#a303b559dc7a690e89873bba9c1ecc8f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::list&lt;MachineBasicBlock::iterator&gt; anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::AtomicPseudoMIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of atomic pseudo instructions.</p>

<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

### CC {#a35a9a510a116b62866db1ef224321dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SICacheControl&gt; anonymous{SIMemoryLegalizer.cpp}::SIMemoryLegalizer::CC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache Control.</p>

<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#afeaa8eace70f2f21e4718d2b749ee942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char SIMemoryLegalizer::ID = 0</td>
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



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a>.</p>


<p>Referenced by <a href="#a3278517f82c41fcf2c3482d645653c4f">SIMemoryLegalizer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simemorylegalizer-cpp">SIMemoryLegalizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
