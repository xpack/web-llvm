---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-machineoutliner-cpp-/instructionmapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `InstructionMapper` Struct

<p>Maps <span class="doxyComputerOutput">MachineInstrs</span> to unsigned integers and stores the mappings. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{MachineOutliner.cpp}::InstructionMapper { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76ed047b551aad831e63f153678d6d85">InstructionMapper</a> (const MachineModuleInfo &amp;MMI_)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ad5905b935c2e08e68fa162f6950233">mapToLegalUnsigned</a> (MachineBasicBlock::iterator &amp;It, bool &amp;CanOutlineWithPrevInstr, bool &amp;HaveLegalRange, unsigned &amp;NumLegalInBlock, SmallVector&lt; unsigned &gt; &amp;UnsignedVecForMBB, SmallVector&lt; MachineBasicBlock::iterator &gt; &amp;InstrListForMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps <span class="doxyComputerOutput">*It</span> to a legal integer. <a href="#a0ad5905b935c2e08e68fa162f6950233">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f2bae254fbc6babdf14612c7b20b512">mapToIllegalUnsigned</a> (MachineBasicBlock::iterator &amp;It, bool &amp;CanOutlineWithPrevInstr, SmallVector&lt; unsigned &gt; &amp;UnsignedVecForMBB, SmallVector&lt; MachineBasicBlock::iterator &gt; &amp;InstrListForMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps <span class="doxyComputerOutput">*It</span> to an illegal integer. <a href="#a4f2bae254fbc6babdf14612c7b20b512">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab972a0bf71717b582043380f067148dc">convertToUnsignedVec</a> (MachineBasicBlock &amp;MBB, const TargetInstrInfo &amp;TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transforms a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a></span> into a <span class="doxyComputerOutput">vector</span> of <span class="doxyComputerOutput">unsigneds</span> and appends it to <span class="doxyComputerOutput">UnsignedVec</span> and <span class="doxyComputerOutput">InstrList</span>. <a href="#ab972a0bf71717b582043380f067148dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03d801e5580d7a721d94609f72b6c5cc">MMI</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e198f7621f46197f997f4cf42109b77">IllegalInstrNumber</a> = -3</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The next available integer to assign to a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a></span> that cannot be outlined. <a href="#a0e198f7621f46197f997f4cf42109b77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9a7ba9ac7797fd4e187259cb8c3a52d">LegalInstrNumber</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The next available integer to assign to a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a></span> that can be outlined. <a href="#ad9a7ba9ac7797fd4e187259cb8c3a52d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, unsigned, <a href="/web-llvm/docs/api/structs/llvm/machineinstrexpressiontrait">MachineInstrExpressionTrait</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1216dbec7ee83bf1056d1b76da88c573">InstructionIntegerMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Correspondence from <span class="doxyComputerOutput">MachineInstrs</span> to unsigned integers. <a href="#a1216dbec7ee83bf1056d1b76da88c573">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca781b005b26b74870c3aa3fb6e11624">MBBFlagsMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Correspondence between <span class="doxyComputerOutput">MachineBasicBlocks</span> and target-defined flags. <a href="#aca781b005b26b74870c3aa3fb6e11624">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ffe546b4199ea1edd45cc4f0f08e64d">UnsignedVec</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The vector of unsigned integers that the module is mapped to. <a href="#a5ffe546b4199ea1edd45cc4f0f08e64d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55ee9a3bf5f8e61cb90c7ff4ad0aef7c">InstrList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores the location of the instruction associated with the integer at index i in <span class="doxyComputerOutput">UnsignedVec</span> for each index i. <a href="#a55ee9a3bf5f8e61cb90c7ff4ad0aef7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa673286927fc074a3e5b5fc52939b54">AddedIllegalLastTime</a> = false</td>
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

## Description {#details}

<p>Maps <span class="doxyComputerOutput">MachineInstrs</span> to unsigned integers and stores the mappings.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstructionMapper() {#a76ed047b551aad831e63f153678d6d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachineOutliner.cpp}::InstructionMapper::InstructionMapper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI_)</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a1423601a8e4ec304e0756df4e761ebbb">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a9571e26b946751eaf015a9b8dc508be9">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getTombstoneKey</a> and <a href="#a03d801e5580d7a721d94609f72b6c5cc">MMI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertToUnsignedVec() {#ab972a0bf71717b582043380f067148dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachineOutliner.cpp}::InstructionMapper::convertToUnsignedVec (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII)</td>
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

<p>Transforms a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a></span> into a <span class="doxyComputerOutput">vector</span> of <span class="doxyComputerOutput">unsigneds</span> and appends it to <span class="doxyComputerOutput">UnsignedVec</span> and <span class="doxyComputerOutput">InstrList</span>.</p>


<p>Two instructions are assigned the same integer if they are identical. If an instruction is deemed unsafe to outline, then it will be assigned an unique integer. The resulting mapping is placed into a suffix tree and queried for candidates.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MBB</td>
<td class="doxyParamItemDescription"><p>The <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a></span> to be translated into integers.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TII</td>
<td class="doxyParamItemDescription"><p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a></span> for the function.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="#afa673286927fc074a3e5b5fc52939b54">AddedIllegalLastTime</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/outliner/#a0765e098fe7aae0f01b60ec890ac1b52a795f5ad85ed392b65a70b46dacaeef34">llvm::outliner::Illegal</a>, <a href="#a55ee9a3bf5f8e61cb90c7ff4ad0aef7c">InstrList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/outliner/#a0765e098fe7aae0f01b60ec890ac1b52add798e74afcdf046a9a39e477261ab0e">llvm::outliner::Invisible</a>, <a href="/web-llvm/docs/api/namespaces/llvm/outliner/#a0765e098fe7aae0f01b60ec890ac1b52a5b2760b5bb9cc62190d2ddfe563776b9">llvm::outliner::Legal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/outliner/#a0765e098fe7aae0f01b60ec890ac1b52a6adc06fdab039cdbfaaeda00060c5e63">llvm::outliner::LegalTerminator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a4f2bae254fbc6babdf14612c7b20b512">mapToIllegalUnsigned</a>, <a href="#a0ad5905b935c2e08e68fa162f6950233">mapToLegalUnsigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aca781b005b26b74870c3aa3fb6e11624">MBBFlagsMap</a>, <a href="#a03d801e5580d7a721d94609f72b6c5cc">MMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="#a5ffe546b4199ea1edd45cc4f0f08e64d">UnsignedVec</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#ac2358bb1fa4721b99f88e2149d6d127d">anonymous{MachineOutliner.cpp}::MachineOutliner::populateMapper</a>.</p>

</div>
</div>

### mapToIllegalUnsigned() {#a4f2bae254fbc6babdf14612c7b20b512}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MachineOutliner.cpp}::InstructionMapper::mapToIllegalUnsigned (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; It, bool &amp; CanOutlineWithPrevInstr, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned &gt; &amp; UnsignedVecForMBB, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &gt; &amp; InstrListForMBB)</td>
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

<p>Maps <span class="doxyComputerOutput">*It</span> to an illegal integer.</p>


<p>Updates <span class="doxyComputerOutput">InstrListForMBB</span>, <span class="doxyComputerOutput">UnsignedVecForMBB</span>, and <span class="doxyComputerOutput">IllegalInstrNumber</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The integer that <span class="doxyComputerOutput">*It</span> was mapped to.</p></dd>
</dl>


<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="#afa673286927fc074a3e5b5fc52939b54">AddedIllegalLastTime</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a1423601a8e4ec304e0756df4e761ebbb">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a9571e26b946751eaf015a9b8dc508be9">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getTombstoneKey</a>, <a href="#a0e198f7621f46197f997f4cf42109b77">IllegalInstrNumber</a>, <a href="#ad9a7ba9ac7797fd4e187259cb8c3a52d">LegalInstrNumber</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#ab972a0bf71717b582043380f067148dc">convertToUnsignedVec</a>.</p>

</div>
</div>

### mapToLegalUnsigned() {#a0ad5905b935c2e08e68fa162f6950233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MachineOutliner.cpp}::InstructionMapper::mapToLegalUnsigned (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; It, bool &amp; CanOutlineWithPrevInstr, bool &amp; HaveLegalRange, unsigned &amp; NumLegalInBlock, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned &gt; &amp; UnsignedVecForMBB, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &gt; &amp; InstrListForMBB)</td>
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

<p>Maps <span class="doxyComputerOutput">*It</span> to a legal integer.</p>


<p>Updates <span class="doxyComputerOutput">CanOutlineWithPrevInstr</span>, <span class="doxyComputerOutput">HaveLegalRange</span>, <span class="doxyComputerOutput">InstrListForMBB</span>, <span class="doxyComputerOutput">UnsignedVecForMBB</span>, <span class="doxyComputerOutput">InstructionIntegerMap</span>, and <span class="doxyComputerOutput">LegalInstrNumber</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The integer that <span class="doxyComputerOutput">*It</span> was mapped to.</p></dd>
</dl>


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="#afa673286927fc074a3e5b5fc52939b54">AddedIllegalLastTime</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a1423601a8e4ec304e0756df4e761ebbb">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a9571e26b946751eaf015a9b8dc508be9">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getTombstoneKey</a>, <a href="#a0e198f7621f46197f997f4cf42109b77">IllegalInstrNumber</a>, <a href="#a1216dbec7ee83bf1056d1b76da88c573">InstructionIntegerMap</a>, <a href="#ad9a7ba9ac7797fd4e187259cb8c3a52d">LegalInstrNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#ab972a0bf71717b582043380f067148dc">convertToUnsignedVec</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AddedIllegalLastTime {#afa673286927fc074a3e5b5fc52939b54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineOutliner.cpp}::InstructionMapper::AddedIllegalLastTime = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#ab972a0bf71717b582043380f067148dc">convertToUnsignedVec</a>, <a href="#a4f2bae254fbc6babdf14612c7b20b512">mapToIllegalUnsigned</a> and <a href="#a0ad5905b935c2e08e68fa162f6950233">mapToLegalUnsigned</a>.</p>

</div>
</div>

### IllegalInstrNumber {#a0e198f7621f46197f997f4cf42109b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MachineOutliner.cpp}::InstructionMapper::IllegalInstrNumber = -3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The next available integer to assign to a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a></span> that cannot be outlined.</p>


<p>Set to -3 for compatability with <span class="doxyComputerOutput">DenseMapInfo&lt;unsigned&gt;</span>.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#a4f2bae254fbc6babdf14612c7b20b512">mapToIllegalUnsigned</a> and <a href="#a0ad5905b935c2e08e68fa162f6950233">mapToLegalUnsigned</a>.</p>

</div>
</div>

### InstrList {#a55ee9a3bf5f8e61cb90c7ff4ad0aef7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock::iterator&gt; anonymous{MachineOutliner.cpp}::InstructionMapper::InstrList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores the location of the instruction associated with the integer at index i in <span class="doxyComputerOutput">UnsignedVec</span> for each index i.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#ab972a0bf71717b582043380f067148dc">convertToUnsignedVec</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a9ffe567aa54e3a2cf09da0fda0b7782b">anonymous{MachineOutliner.cpp}::MachineOutliner::findCandidates</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#abc198544930d8083eb7f18ddab232ce9">anonymous{MachineOutliner.cpp}::MachineOutliner::findGlobalCandidates</a>.</p>

</div>
</div>

### InstructionIntegerMap {#a1216dbec7ee83bf1056d1b76da88c573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineInstr *, unsigned, MachineInstrExpressionTrait&gt; anonymous{MachineOutliner.cpp}::InstructionMapper::InstructionIntegerMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Correspondence from <span class="doxyComputerOutput">MachineInstrs</span> to unsigned integers.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#a0ad5905b935c2e08e68fa162f6950233">mapToLegalUnsigned</a>.</p>

</div>
</div>

### LegalInstrNumber {#ad9a7ba9ac7797fd4e187259cb8c3a52d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MachineOutliner.cpp}::InstructionMapper::LegalInstrNumber = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The next available integer to assign to a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a></span> that can be outlined.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#a4f2bae254fbc6babdf14612c7b20b512">mapToIllegalUnsigned</a> and <a href="#a0ad5905b935c2e08e68fa162f6950233">mapToLegalUnsigned</a>.</p>

</div>
</div>

### MBBFlagsMap {#aca781b005b26b74870c3aa3fb6e11624}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineBasicBlock *, unsigned&gt; anonymous{MachineOutliner.cpp}::InstructionMapper::MBBFlagsMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Correspondence between <span class="doxyComputerOutput">MachineBasicBlocks</span> and target-defined flags.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#ab972a0bf71717b582043380f067148dc">convertToUnsignedVec</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a9ffe567aa54e3a2cf09da0fda0b7782b">anonymous{MachineOutliner.cpp}::MachineOutliner::findCandidates</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#abc198544930d8083eb7f18ddab232ce9">anonymous{MachineOutliner.cpp}::MachineOutliner::findGlobalCandidates</a>.</p>

</div>
</div>

### MMI {#a03d801e5580d7a721d94609f72b6c5cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineModuleInfo&amp; anonymous{MachineOutliner.cpp}::InstructionMapper::MMI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#ab972a0bf71717b582043380f067148dc">convertToUnsignedVec</a> and <a href="#a76ed047b551aad831e63f153678d6d85">InstructionMapper</a>.</p>

</div>
</div>

### UnsignedVec {#a5ffe546b4199ea1edd45cc4f0f08e64d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned&gt; anonymous{MachineOutliner.cpp}::InstructionMapper::UnsignedVec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The vector of unsigned integers that the module is mapped to.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#ab972a0bf71717b582043380f067148dc">convertToUnsignedVec</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a9ffe567aa54e3a2cf09da0fda0b7782b">anonymous{MachineOutliner.cpp}::MachineOutliner::findCandidates</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a1ac412f2e4cc981d3b9d3f6cf6d5988a">anonymous{MachineOutliner.cpp}::MachineOutliner::outline</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#ac2358bb1fa4721b99f88e2149d6d127d">anonymous{MachineOutliner.cpp}::MachineOutliner::populateMapper</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
