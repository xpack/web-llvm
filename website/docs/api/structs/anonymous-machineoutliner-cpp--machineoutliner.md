---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-machineoutliner-cpp-/machineoutliner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MachineOutliner` Struct Reference

<p>An interprocedural pass which finds repeated sequences of instructions and replaces them with calls to functions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{MachineOutliner.cpp}::MachineOutliner { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a> class - This class is used to implement unstructured interprocedural optimizations and analyses. <a href="/web-llvm/docs/api/classes/llvm/modulepass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8390acb69c9afa4044e5d8f3ffec7d12">MachineOutliner</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b35d6ec3793e1cb5abc7c0eff4dce2">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a61b35d6ec3793e1cb5abc7c0eff4dce2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91bb84179044c30641f066d505ac80cc">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a91bb84179044c30641f066d505ac80cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf5dcc48f205ab98bbdd968a23d10e93">emitNotOutliningCheaperRemark</a> (unsigned StringLen, std::vector&lt; Candidate &gt; &amp;CandidatesForRepeatedSeq, OutlinedFunction &amp;OF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remark output explaining that not outlining a set of candidates would be better than outlining that set. <a href="#adf5dcc48f205ab98bbdd968a23d10e93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f5104a534795f587fc2e9ec2e6a0c03">emitOutlinedFunctionRemark</a> (OutlinedFunction &amp;OF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remark output explaining that a function was outlined. <a href="#a9f5104a534795f587fc2e9ec2e6a0c03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ffe567aa54e3a2cf09da0fda0b7782b">findCandidates</a> (InstructionMapper &amp;Mapper, std::vector&lt; std::unique_ptr&lt; OutlinedFunction &gt; &gt; &amp;FunctionList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find all repeated substrings that satisfy the outlining cost model by constructing a suffix tree. <a href="#a9ffe567aa54e3a2cf09da0fda0b7782b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc198544930d8083eb7f18ddab232ce9">findGlobalCandidates</a> (InstructionMapper &amp;Mapper, std::vector&lt; std::unique_ptr&lt; OutlinedFunction &gt; &gt; &amp;FunctionList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find all repeated substrings that match in the global outlined hash tree built from the previous codegen. <a href="#abc198544930d8083eb7f18ddab232ce9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ac412f2e4cc981d3b9d3f6cf6d5988a">outline</a> (Module &amp;M, std::vector&lt; std::unique_ptr&lt; OutlinedFunction &gt; &gt; &amp;FunctionList, InstructionMapper &amp;Mapper, unsigned &amp;OutlinedFunctionNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the sequences of instructions represented by <span class="doxyComputerOutput">OutlinedFunctions</span> with calls to functions. <a href="#a1ac412f2e4cc981d3b9d3f6cf6d5988a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a272487247e40605fc8a0ee848d4dcf44">createOutlinedFunction</a> (Module &amp;M, OutlinedFunction &amp;OF, InstructionMapper &amp;Mapper, unsigned Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a function for <span class="doxyComputerOutput">OF</span> and inserts it into the module. <a href="#a272487247e40605fc8a0ee848d4dcf44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab79e380b2ff4d4653bc9a766e1a59220">computeAndPublishHashSequence</a> (MachineFunction &amp;MF, unsigned CandSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute and publish the stable hash sequence of instructions in the outlined function, <span class="doxyComputerOutput">MF</span>. <a href="#ab79e380b2ff4d4653bc9a766e1a59220">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4636655f10db66966895ea366108f1e5">initializeOutlinerMode</a> (const Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the outliner mode. <a href="#a4636655f10db66966895ea366108f1e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fe992f3a0f55c247f1f27cb09755ab5">emitOutlinedHashTree</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the outlined hash tree into __llvm_outline section. <a href="#a7fe992f3a0f55c247f1f27cb09755ab5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a847c562b6cc1fea696bcf695257cd6fb">runOnModule</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calls '<a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline()</a>' 1 + OutlinerReruns times. <a href="#a847c562b6cc1fea696bcf695257cd6fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a> (Module &amp;M, unsigned &amp;OutlinedFunctionNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a suffix tree on the instructions in <span class="doxyComputerOutput">M</span> and outline repeated strings from that tree. <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ce342d09daa9a2d58bad8dad2018e33">getSubprogramOrNull</a> (const OutlinedFunction &amp;OF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> for OF if one exists, and null otherwise. <a href="#a8ce342d09daa9a2d58bad8dad2018e33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2358bb1fa4721b99f88e2149d6d127d">populateMapper</a> (InstructionMapper &amp;Mapper, Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper">InstructionMapper</a></span> with instruction-to-integer mappings. <a href="#ac2358bb1fa4721b99f88e2149d6d127d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf198225ba8d393e81757caf3ddae1f">initSizeRemarkInfo</a> (const Module &amp;M, StringMap&lt; unsigned &gt; &amp;FunctionToInstrCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize information necessary to output a size remark. <a href="#adbf198225ba8d393e81757caf3ddae1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a474b6a5a9e0e575d9d21d20e8b810ee7">emitInstrCountChangedRemark</a> (const Module &amp;M, const StringMap&lt; unsigned &gt; &amp;FunctionToInstrCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the remark. <a href="#a474b6a5a9e0e575d9d21d20e8b810ee7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a126665c6052902ccd0e3287aca52a499">MMI</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45c2e1dd74ff36083e927139a76cc651">OutlineFromLinkOnceODRs</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to true if the outliner should consider functions with linkonceodr linkage. <a href="#a45c2e1dd74ff36083e927139a76cc651">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98cbe4fb24d1ca4e8e4a2f747d5f3841">OutlineRepeatedNum</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current repeat number of machine outlining. <a href="#a98cbe4fb24d1ca4e8e4a2f747d5f3841">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3998e6676cd05bb1150ba9b85a3a4b3">RunOnAllFunctions</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to true if the outliner should run on all functions in the module considered safe for outlining. <a href="#ad3998e6676cd05bb1150ba9b85a3a4b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7f0d14fbfba3488e48618a1aeb03372">LocalHashTree</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a compact representation of hash sequences of outlined functions. <a href="#ad7f0d14fbfba3488e48618a1aeb03372">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facf">CGDataMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac926a3be74c8922d14e6bfae65b4d00c">OutlinerMode</a> = CGDataMode::None</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The mode of the outliner. <a href="#ac926a3be74c8922d14e6bfae65b4d00c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1fca7d10d37a4c6d1e3261e727f5186">ID</a> = 0</td>
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

<p>An interprocedural pass which finds repeated sequences of instructions and replaces them with calls to functions.</p>


<p>Each instruction is mapped to an unsigned integer and placed in a string. The resulting mapping is then placed in a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/suffixtree">SuffixTree</a></span>. The <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/suffixtree">SuffixTree</a></span> is then repeatedly queried for repeated sequences of instructions. Each non-overlapping repeated sequence is then placed in its own <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a></span> and each instance is then replaced with a call to that function.</p>


<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineOutliner() {#a8390acb69c9afa4044e5d8f3ffec7d12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachineOutliner.cpp}::MachineOutliner::MachineOutliner ()</td>
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



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#ae1fca7d10d37a4c6d1e3261e727f5186">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e112d124be486708eaa596339ad1f69">llvm::initializeMachineOutlinerPass</a> and <a href="/web-llvm/docs/api/classes/llvm/modulepass/#a723659a08d210f4f566887bda3f9f976">llvm::ModulePass::ModulePass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeAndPublishHashSequence() {#ab79e380b2ff4d4653bc9a766e1a59220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOutliner::computeAndPublishHashSequence (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned CandSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute and publish the stable hash sequence of instructions in the outlined function, <span class="doxyComputerOutput">MF</span>.</p>


<p>The parameter <span class="doxyComputerOutput">CandSize</span> represents the number of candidates that have identical instruction sequences to <span class="doxyComputerOutput">MF</span>.</p>


<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#ab06ba58a3ef4bc703433979d60cb1817">AppendContentHashToOutlinedName</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="#ad7f0d14fbfba3488e48618a1aeb03372">LocalHashTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#ac926a3be74c8922d14e6bfae65b4d00c">OutlinerMode</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae12d768edcecd309ab9fa48c23f9bc07">llvm::stable_hash_combine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa738b693496ce85aba70051f0aa8722bd">llvm::Write</a>.</p>


<p>Referenced by <a href="#a272487247e40605fc8a0ee848d4dcf44">createOutlinedFunction</a> and <a href="#adf5dcc48f205ab98bbdd968a23d10e93">emitNotOutliningCheaperRemark</a>.</p>

</div>
</div>

### createOutlinedFunction() {#a272487247e40605fc8a0ee848d4dcf44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction * MachineOutliner::createOutlinedFunction (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">OutlinedFunction</a> &amp; OF, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper">InstructionMapper</a> &amp; Mapper, unsigned Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a function for <span class="doxyComputerOutput">OF</span> and inserts it into the module.</p>

<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3e4e67777edb24fac492ef4ae15e69ba">llvm::MachineInstrBuilder::addCFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a247230f547064b27022d70c0aeb86682">llvm::MachineFunction::addFrameInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af9a1ca470b2b9c8e97304f5be5448422">llvm::addLiveIns</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#abb67d4b6f48395a5aca25fc32e042928">llvm::LivePhysRegs::addLiveOuts</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#adbf2afbb346e40106f344191309324fc">llvm::LivePhysRegs::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#afaa7ed984d2671729752893984eb85a3">llvm::outliner::OutlinedFunction::Candidates</a>, <a href="#ab79e380b2ff4d4653bc9a766e1a59220">computeAndPublishHashSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa6536556982b7e6e2e5884e471f3ce6b">llvm::IRBuilderBase::CreateRetVoid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a6e05e3bfe64497149a8800b1830c4001">llvm::MachineInstr::dropMemRefs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a30815e557d36373557a052fbf84263c7">llvm::MachineRegisterInfo::freezeReservedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aeedc2554f9637d1e27befa7a85c70ec9">llvm::MachineBasicBlock::front</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate/#a16c39dfa2a8b341bb2448fd032c58b64">llvm::outliner::Candidate::front</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3b0b8ca2d88fcbdbc726bb4293c06a59">llvm::MachineFunction::getFrameInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate/#a71a2623cadc4c0ef543d25d1c6f2a07a">llvm::outliner::Candidate::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac1f888bba00f32cb4f9a0010c958f397">llvm::MachineFunction::getProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="#a8ce342d09daa9a2d58bad8dad2018e33">getSubprogramOrNull</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a4cc6684df7b4a92b1dec6fce3264fac8">llvm::GlobalValue::Global</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a4fc3b812627e58da17a703f73013db96">llvm::MachineFunctionProperties::IsSSA</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a126665c6052902ccd0e3287aca52a499">MMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a76eece0bfd57256980609b66faaef22c">llvm::MachineFunctionProperties::NoPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a>, <a href="#a98cbe4fb24d1ca4e8e4a2f747d5f3841">OutlineRepeatedNum</a>, <a href="#ac926a3be74c8922d14e6bfae65b4d00c">OutlinerMode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#af2f789465ed765ac2795381e8b91b902">llvm::MachineFunctionProperties::reset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#af2641f071128da26317fab5b9594ec71">llvm::MachineInstr::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa2c7c5b384c76cec2bfb10c27be020f5">llvm::MachineFunction::setIsOutlined</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#a683d33b7b0ca1cf29e61a3dc4614a046">llvm::LivePhysRegs::stepBackward</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a0020348b08bb4cccecf3241eac999d8a">llvm::MachineFunctionProperties::TracksLiveness</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a1ac412f2e4cc981d3b9d3f6cf6d5988a">outline</a>.</p>

</div>
</div>

### doOutline() {#a0bd4f3a42f41a70b7226a5e7fb253b14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineOutliner::doOutline (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, unsigned &amp; OutlinedFunctionNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a suffix tree on the instructions in <span class="doxyComputerOutput">M</span> and outline repeated strings from that tree.</p>

<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a474b6a5a9e0e575d9d21d20e8b810ee7">emitInstrCountChangedRemark</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#ade1acda7a523b43168150e03af875ef4">EnableLinkOnceODROutlining</a>, <a href="#a9ffe567aa54e3a2cf09da0fda0b7782b">findCandidates</a>, <a href="#abc198544930d8083eb7f18ddab232ce9">findGlobalCandidates</a>, <a href="#adbf198225ba8d393e81757caf3ddae1f">initSizeRemarkInfo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a126665c6052902ccd0e3287aca52a499">MMI</a>, <a href="#a1ac412f2e4cc981d3b9d3f6cf6d5988a">outline</a>, <a href="#a45c2e1dd74ff36083e927139a76cc651">OutlineFromLinkOnceODRs</a>, <a href="#a98cbe4fb24d1ca4e8e4a2f747d5f3841">OutlineRepeatedNum</a>, <a href="#ac926a3be74c8922d14e6bfae65b4d00c">OutlinerMode</a>, <a href="#ac2358bb1fa4721b99f88e2149d6d127d">populateMapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa33af1aad55fa136e2ab54409f4b4891f">llvm::Read</a> and <a href="#ad3998e6676cd05bb1150ba9b85a3a4b3">RunOnAllFunctions</a>.</p>


<p>Referenced by <a href="#adf5dcc48f205ab98bbdd968a23d10e93">emitNotOutliningCheaperRemark</a> and <a href="#a847c562b6cc1fea696bcf695257cd6fb">runOnModule</a>.</p>

</div>
</div>

### emitInstrCountChangedRemark() {#a474b6a5a9e0e575d9d21d20e8b810ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOutliner::emitInstrCountChangedRemark (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; unsigned &gt; &amp; FunctionToInstrCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the remark.</p>

<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a16e5eaf2df56249e87019be23ee07695">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a49e68e4c86fe0b96c633adea0c366d74">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac8ca28de0f4dcee651340e7ef0c45233">llvm::MachineFunction::front</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a0892015643ec782f2fce58af100fbd6e">llvm::MachineFunction::getInstructionCount</a>, <a href="#a126665c6052902ccd0e3287aca52a499">MMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ace441594c4bd8da94fd64b1c612ca948">MORE</a>.</p>


<p>Referenced by <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a>.</p>

</div>
</div>

### emitNotOutliningCheaperRemark() {#adf5dcc48f205ab98bbdd968a23d10e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachineOutliner.cpp}::MachineOutliner::emitNotOutliningCheaperRemark (unsigned StringLen, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate">Candidate</a> &gt; &amp; CandidatesForRepeatedSeq, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">OutlinedFunction</a> &amp; OF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remark output explaining that not outlining a set of candidates would be better than outlining that set.</p>

<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="#ab79e380b2ff4d4653bc9a766e1a59220">computeAndPublishHashSequence</a>, <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a>, <a href="#a9f5104a534795f587fc2e9ec2e6a0c03">emitOutlinedFunctionRemark</a>, <a href="#a7fe992f3a0f55c247f1f27cb09755ab5">emitOutlinedHashTree</a>, <a href="#a9ffe567aa54e3a2cf09da0fda0b7782b">findCandidates</a>, <a href="#abc198544930d8083eb7f18ddab232ce9">findGlobalCandidates</a>, <a href="#a4636655f10db66966895ea366108f1e5">initializeOutlinerMode</a>, <a href="#a1ac412f2e4cc981d3b9d3f6cf6d5988a">outline</a> and <a href="#a847c562b6cc1fea696bcf695257cd6fb">runOnModule</a>.</p>


<p>Referenced by <a href="#a9ffe567aa54e3a2cf09da0fda0b7782b">findCandidates</a>.</p>

</div>
</div>

### emitOutlinedFunctionRemark() {#a9f5104a534795f587fc2e9ec2e6a0c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOutliner::emitOutlinedFunctionRemark (<a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">OutlinedFunction</a> &amp; OF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remark output explaining that a function was outlined.</p>

<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#afaa7ed984d2671729752893984eb85a3">llvm::outliner::OutlinedFunction::Candidates</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#a2b7d852cc4d557d60abf54e6c67badd6">llvm::outliner::OutlinedFunction::getBenefit</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#aa25ba2c1c77be50fed1cacfd48b91215">llvm::outliner::OutlinedFunction::getNumInstrs</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#a0081f20622492dac85cd60d330e9673c">llvm::outliner::OutlinedFunction::getOccurrenceCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#a6c6c3c632ddf4fca7933bd1d2617187e">llvm::outliner::OutlinedFunction::MF</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ace441594c4bd8da94fd64b1c612ca948">MORE</a>.</p>


<p>Referenced by <a href="#adf5dcc48f205ab98bbdd968a23d10e93">emitNotOutliningCheaperRemark</a> and <a href="#a1ac412f2e4cc981d3b9d3f6cf6d5988a">outline</a>.</p>

</div>
</div>

### emitOutlinedHashTree() {#a7fe992f3a0f55c247f1f27cb09755ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOutliner::emitOutlinedHashTree (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the outlined hash tree into __llvm_outline section.</p>

<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae744a53dbb2720e5678fb879156761e9">llvm::embedBufferInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff79775a78397e420bbe8bbed80f2a21">llvm::getCodeGenDataSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ad7f0d14fbfba3488e48618a1aeb03372">LocalHashTree</a> and <a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord/#a74ae6e240a1760c68a807fd885606fe6">llvm::OutlinedHashTreeRecord::serialize</a>.</p>


<p>Referenced by <a href="#adf5dcc48f205ab98bbdd968a23d10e93">emitNotOutliningCheaperRemark</a> and <a href="#a847c562b6cc1fea696bcf695257cd6fb">runOnModule</a>.</p>

</div>
</div>

### findCandidates() {#a9ffe567aa54e3a2cf09da0fda0b7782b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOutliner::findCandidates (<a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper">InstructionMapper</a> &amp; Mapper, std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">OutlinedFunction</a> &gt; &gt; &amp; FunctionList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find all repeated substrings that satisfy the outlining cost model by constructing a suffix tree.</p>


<p>If a substring appears at least twice, then it must be represented by an internal node which appears in at least two suffixes. Each suffix is represented by a leaf node. To do this, we visit each internal node in the tree, using the leaf children of each internal node. If an internal node represents a beneficial substring, then we use each of its leaf children to find the locations of its substring.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mapper</td>
<td class="doxyParamItemDescription"><p>Contains outlining mapping information.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] FunctionList</td>
<td class="doxyParamItemDescription"><p>Filled with a list of <span class="doxyComputerOutput">OutlinedFunctions</span> each type of candidate.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adf4e7878fc0b3b8dcde545178564190d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#adf5dcc48f205ab98bbdd968a23d10e93">emitNotOutliningCheaperRemark</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#a55ee9a3bf5f8e61cb90c7ff4ad0aef7c">anonymous{MachineOutliner.cpp}::InstructionMapper::InstrList</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#aca781b005b26b74870c3aa3fb6e11624">anonymous{MachineOutliner.cpp}::InstructionMapper::MBBFlagsMap</a>, <a href="#a126665c6052902ccd0e3287aca52a499">MMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#a5a026c03ac103404db8d3be46b1b6c49">OutlinerBenefitThreshold</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#ab04e0eb540a588f835f9088d621f1382">OutlinerLeafDescendants</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#a5ffe546b4199ea1edd45cc4f0f08e64d">anonymous{MachineOutliner.cpp}::InstructionMapper::UnsignedVec</a>.</p>


<p>Referenced by <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a> and <a href="#adf5dcc48f205ab98bbdd968a23d10e93">emitNotOutliningCheaperRemark</a>.</p>

</div>
</div>

### findGlobalCandidates() {#abc198544930d8083eb7f18ddab232ce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOutliner::findGlobalCandidates (<a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper">InstructionMapper</a> &amp; Mapper, std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">OutlinedFunction</a> &gt; &gt; &amp; FunctionList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find all repeated substrings that match in the global outlined hash tree built from the previous codegen.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mapper</td>
<td class="doxyParamItemDescription"><p>Contains outlining mapping information.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] FunctionList</td>
<td class="doxyParamItemDescription"><p>Filled with a list of <span class="doxyComputerOutput">OutlinedFunctions</span> each type of candidate.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#af08090d2b358f57cbf6b3448a5ff2676">getMatchedEntries</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#a55ee9a3bf5f8e61cb90c7ff4ad0aef7c">anonymous{MachineOutliner.cpp}::InstructionMapper::InstrList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#aca781b005b26b74870c3aa3fb6e11624">anonymous{MachineOutliner.cpp}::InstructionMapper::MBBFlagsMap</a>, <a href="#a126665c6052902ccd0e3287aca52a499">MMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a> and <a href="#adf5dcc48f205ab98bbdd968a23d10e93">emitNotOutliningCheaperRemark</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a91bb84179044c30641f066d505ac80cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachineOutliner.cpp}::MachineOutliner::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae9356b720f6fbab112d809738dcc4f2a">llvm::AnalysisUsage::addPreserved</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#aaeddaf79040291b6f3e0db57943aac39">llvm::AnalysisUsage::addUsedIfAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a6590d0486104165ca40c7df0707f7b9e">llvm::Pass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af22b06a6a4f9df80454071685a0d6a02">llvm::AnalysisUsage::setPreservesAll</a>.</p>

</div>
</div>

### getPassName() {#a61b35d6ec3793e1cb5abc7c0eff4dce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{MachineOutliner.cpp}::MachineOutliner::getPassName ()</td>
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


<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>

</div>
</div>

### getSubprogramOrNull() {#a8ce342d09daa9a2d58bad8dad2018e33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram * anonymous{MachineOutliner.cpp}::MachineOutliner::getSubprogramOrNull (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">OutlinedFunction</a> &amp; OF)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> for OF if one exists, and null otherwise.</p>


<p>Helper function for remark emission.</p>


<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#afaa7ed984d2671729752893984eb85a3">llvm::outliner::OutlinedFunction::Candidates</a> and <a href="/web-llvm/docs/api/classes/llvm/dilocalscope/#a0e0b4a5906e0bc2a7fa033548c59a220">llvm::DILocalScope::getSubprogram</a>.</p>


<p>Referenced by <a href="#a272487247e40605fc8a0ee848d4dcf44">createOutlinedFunction</a>.</p>

</div>
</div>

### initializeOutlinerMode() {#a4636655f10db66966895ea366108f1e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOutliner::initializeOutlinerMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize the outliner mode.</p>

<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#a03b22d4b0f515d7609603d5bda5eb5ff">DisableGlobalOutlining</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#ad1a6f1d892a1ed8390de8835209b023b">llvm::cgdata::emitCGData</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#af94c014e968489e96c7d4353a84ad7f5">llvm::Pass::getAnalysisIfAvailable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a429cd542137f6930d904d70bc864c451">llvm::cgdata::hasOutlinedHashTree</a>, <a href="#ad7f0d14fbfba3488e48618a1aeb03372">LocalHashTree</a>, <a href="#ac926a3be74c8922d14e6bfae65b4d00c">OutlinerMode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa33af1aad55fa136e2ab54409f4b4891f">llvm::Read</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa738b693496ce85aba70051f0aa8722bd">llvm::Write</a>.</p>


<p>Referenced by <a href="#adf5dcc48f205ab98bbdd968a23d10e93">emitNotOutliningCheaperRemark</a> and <a href="#a847c562b6cc1fea696bcf695257cd6fb">runOnModule</a>.</p>

</div>
</div>

### initSizeRemarkInfo() {#adbf198225ba8d393e81757caf3ddae1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOutliner::initSizeRemarkInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; unsigned &gt; &amp; FunctionToInstrCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize information necessary to output a size remark.</p>


<p>FIXME: This should be handled by the pass manager, not the outliner. FIXME: This is nearly identical to the initSizeRemarkInfo in the legacy pass manager.</p>


<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a0892015643ec782f2fce58af100fbd6e">llvm::MachineFunction::getInstructionCount</a> and <a href="#a126665c6052902ccd0e3287aca52a499">MMI</a>.</p>


<p>Referenced by <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a>.</p>

</div>
</div>

### outline() {#a1ac412f2e4cc981d3b9d3f6cf6d5988a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineOutliner::outline (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">OutlinedFunction</a> &gt; &gt; &amp; FunctionList, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper">InstructionMapper</a> &amp; Mapper, unsigned &amp; OutlinedFunctionNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace the sequences of instructions represented by <span class="doxyComputerOutput">OutlinedFunctions</span> with calls to functions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p>The module we are outlining from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FunctionList</td>
<td class="doxyParamItemDescription"><p>A list of functions to be inserted into the module.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mapper</td>
<td class="doxyParamItemDescription"><p>Contains the instruction mappings for the module.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] OutlinedFunctionNum</td>
<td class="doxyParamItemDescription"><p>The outlined function number.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a2a98f19750ba941ce791b75ca6d77e48">llvm::SmallSet&lt; T, N, C &gt;::count</a>, <a href="#a272487247e40605fc8a0ee848d4dcf44">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a9f5104a534795f587fc2e9ec2e6a0c03">emitOutlinedFunctionRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a75a2d2ad3b3dce6702750d570ee8f343">llvm::SmallSet&lt; T, N, C &gt;::erase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a7de5a04920954ac964059cfc428ad">llvm::erase_if</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator/#a13dd64c40d9f175e578ade3ef60ea351">llvm::MachineInstrBundleIterator&lt; Ty, IsReverse &gt;::getReverse</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#a5a026c03ac103404db8d3be46b1b6c49">OutlinerBenefitThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a0020348b08bb4cccecf3241eac999d8a">llvm::MachineFunctionProperties::TracksLiveness</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#a5ffe546b4199ea1edd45cc4f0f08e64d">anonymous{MachineOutliner.cpp}::InstructionMapper::UnsignedVec</a>.</p>


<p>Referenced by <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a> and <a href="#adf5dcc48f205ab98bbdd968a23d10e93">emitNotOutliningCheaperRemark</a>.</p>

</div>
</div>

### populateMapper() {#ac2358bb1fa4721b99f88e2149d6d127d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOutliner::populateMapper (<a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper">InstructionMapper</a> &amp; Mapper, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper">InstructionMapper</a></span> with instruction-to-integer mappings.</p>


<p>These are used to construct a suffix tree.</p>


<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#ab972a0bf71717b582043380f067148dc">anonymous{MachineOutliner.cpp}::InstructionMapper::convertToUnsignedVec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a126665c6052902ccd0e3287aca52a499">MMI</a>, <a href="#a45c2e1dd74ff36083e927139a76cc651">OutlineFromLinkOnceODRs</a>, <a href="#ad3998e6676cd05bb1150ba9b85a3a4b3">RunOnAllFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#a5ffe546b4199ea1edd45cc4f0f08e64d">anonymous{MachineOutliner.cpp}::InstructionMapper::UnsignedVec</a>.</p>


<p>Referenced by <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a>.</p>

</div>
</div>

### runOnModule() {#a847c562b6cc1fea696bcf695257cd6fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineOutliner::runOnModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Calls '<a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline()</a>' 1 + OutlinerReruns times.</p>

<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a>, <a href="#a7fe992f3a0f55c247f1f27cb09755ab5">emitOutlinedHashTree</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a4636655f10db66966895ea366108f1e5">initializeOutlinerMode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a126665c6052902ccd0e3287aca52a499">MMI</a>, <a href="#a98cbe4fb24d1ca4e8e4a2f747d5f3841">OutlineRepeatedNum</a>, <a href="#ac926a3be74c8922d14e6bfae65b4d00c">OutlinerMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#ad5066198a91aa174b4ed26be49e1c69c">OutlinerReruns</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa738b693496ce85aba70051f0aa8722bd">llvm::Write</a>.</p>


<p>Referenced by <a href="#adf5dcc48f205ab98bbdd968a23d10e93">emitNotOutliningCheaperRemark</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LocalHashTree {#ad7f0d14fbfba3488e48618a1aeb03372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;OutlinedHashTree&gt; anonymous{MachineOutliner.cpp}::MachineOutliner::LocalHashTree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is a compact representation of hash sequences of outlined functions.</p>


<p>It is used when OutlinerMode = CGDataMode::Write. The resulting hash tree will be emitted into __llvm_outlined section which will be dead-stripped not going to the final binary. A post-process using llvm-cgdata, lld, or ThinLTO can merge them into a global oulined hash tree for the subsequent codegen.</p>


<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#ab79e380b2ff4d4653bc9a766e1a59220">computeAndPublishHashSequence</a>, <a href="#a7fe992f3a0f55c247f1f27cb09755ab5">emitOutlinedHashTree</a> and <a href="#a4636655f10db66966895ea366108f1e5">initializeOutlinerMode</a>.</p>

</div>
</div>

### MMI {#a126665c6052902ccd0e3287aca52a499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfo* anonymous{MachineOutliner.cpp}::MachineOutliner::MMI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#a272487247e40605fc8a0ee848d4dcf44">createOutlinedFunction</a>, <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a>, <a href="#a474b6a5a9e0e575d9d21d20e8b810ee7">emitInstrCountChangedRemark</a>, <a href="#a9ffe567aa54e3a2cf09da0fda0b7782b">findCandidates</a>, <a href="#abc198544930d8083eb7f18ddab232ce9">findGlobalCandidates</a>, <a href="#adbf198225ba8d393e81757caf3ddae1f">initSizeRemarkInfo</a>, <a href="#ac2358bb1fa4721b99f88e2149d6d127d">populateMapper</a> and <a href="#a847c562b6cc1fea696bcf695257cd6fb">runOnModule</a>.</p>

</div>
</div>

### OutlineFromLinkOnceODRs {#a45c2e1dd74ff36083e927139a76cc651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineOutliner.cpp}::MachineOutliner::OutlineFromLinkOnceODRs = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set to true if the outliner should consider functions with linkonceodr linkage.</p>

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a> and <a href="#ac2358bb1fa4721b99f88e2149d6d127d">populateMapper</a>.</p>

</div>
</div>

### OutlineRepeatedNum {#a98cbe4fb24d1ca4e8e4a2f747d5f3841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MachineOutliner.cpp}::MachineOutliner::OutlineRepeatedNum = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current repeat number of machine outlining.</p>

<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#a272487247e40605fc8a0ee848d4dcf44">createOutlinedFunction</a>, <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a> and <a href="#a847c562b6cc1fea696bcf695257cd6fb">runOnModule</a>.</p>

</div>
</div>

### OutlinerMode {#ac926a3be74c8922d14e6bfae65b4d00c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CGDataMode anonymous{MachineOutliner.cpp}::MachineOutliner::OutlinerMode = CGDataMode::None</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The mode of the outliner.</p>


<p>When is's CGDataMode::None, candidates are populated with the suffix tree within a module and outlined. When it's CGDataMode::Write, in addition to CGDataMode::None, the hash sequences of outlined functions are published into LocalHashTree. When it's CGDataMode::Read, candidates are populated with the global outlined hash tree that has been built by the previous codegen.</p>


<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#ab79e380b2ff4d4653bc9a766e1a59220">computeAndPublishHashSequence</a>, <a href="#a272487247e40605fc8a0ee848d4dcf44">createOutlinedFunction</a>, <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a>, <a href="#a4636655f10db66966895ea366108f1e5">initializeOutlinerMode</a> and <a href="#a847c562b6cc1fea696bcf695257cd6fb">runOnModule</a>.</p>

</div>
</div>

### RunOnAllFunctions {#ad3998e6676cd05bb1150ba9b85a3a4b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineOutliner.cpp}::MachineOutliner::RunOnAllFunctions = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set to true if the outliner should run on all functions in the module considered safe for outlining.</p>


<p>Set to true by default for compatibility with llc's -run-pass option. Set when the pass is constructed in <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a>.</p>


<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#a0bd4f3a42f41a70b7226a5e7fb253b14">doOutline</a> and <a href="#ac2358bb1fa4721b99f88e2149d6d127d">populateMapper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#ae1fca7d10d37a4c6d1e3261e727f5186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char MachineOutliner::ID = 0</td>
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



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a>.</p>


<p>Referenced by <a href="#a8390acb69c9afa4044e5d8f3ffec7d12">MachineOutliner</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp">MachineOutliner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
