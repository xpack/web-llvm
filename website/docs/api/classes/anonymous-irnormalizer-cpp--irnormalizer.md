---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-irnormalizer-cpp-/irnormalizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IRNormalizer` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-irnormalizer-cpp-/irnormalizer">IRNormalizer</a> aims to transform LLVM IR into normal form. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{IRNormalizer.cpp}::IRNormalizer { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ff04883b7477c97a6150fb1528c5f2d">runOnFunction</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Entry method to the <a href="/web-llvm/docs/api/classes/anonymous-irnormalizer-cpp-/irnormalizer">IRNormalizer</a>. <a href="#a6ff04883b7477c97a6150fb1528c5f2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b47bdab305c78760e89e5fb43dfb5e2">sortCommutativeOperands</a> (Instruction *I, T &amp;Operands) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86bf1ea57d453f800350ba5424c66b59">MagicHashConstant</a> = 0x6acaa36bef8325c5ULL</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5130cb329d1f5b07a833cb48e5f20ed0">NamedInstructions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f627b576a5a64d3822fa1121781bc6d">Outputs</a></td>
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

## Normalizer flags. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3a517f01ed0104bff058519dd163f3">PreserveOrder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b220486b5acfa4acac72303b353d5eb">RenameAll</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Renames all instructions (including user-named). <a href="#a8b220486b5acfa4acac72303b353d5eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93387b667d20ca3cd6307f21b549636a">FoldPreOutputs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Folds all regular instructions (including pre-outputs). <a href="#a93387b667d20ca3cd6307f21b549636a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eeb4c93470d693726fad1750141c6c3">ReorderOperands</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sorts and reorders operands in commutative instructions. <a href="#a3eeb4c93470d693726fad1750141c6c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Naming. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80c89a3f73dfd63cd5da1dc43af1bb8d">nameFunctionArguments</a> (Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Numbers arguments. <a href="#a80c89a3f73dfd63cd5da1dc43af1bb8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a171621aa370f3e139023478791aef7c6">nameBasicBlocks</a> (Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Names basic blocks using a generated hash for each basic block in a function considering the opcode and the order of output instructions. <a href="#a171621aa370f3e139023478791aef7c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabcf6258fa19c6e56d0646d94a6a6246">nameInstruction</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Names instructions graphically (recursive) in accordance with the def-use tree, starting from the initial instructions (defs), finishing at the output (top-most user) instructions (depth-first). <a href="#aabcf6258fa19c6e56d0646d94a6a6246">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137687412584c3815d30b20ff8a3fa77">nameAsInitialInstruction</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Names instruction following the scheme: vl00000Callee(Operands) <a href="#a137687412584c3815d30b20ff8a3fa77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76a70088a3d58525c470b2e7dadbf6b1">nameAsRegularInstruction</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Names instruction following the scheme: op00000Callee(Operands) <a href="#a76a70088a3d58525c470b2e7dadbf6b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7778d3996635b865b4f984a4c206cad">foldInstructionName</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Shortens instruction's name. <a href="#ae7778d3996635b865b4f984a4c206cad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Reordering. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f279ce9fe7b7fa5e3d2994253ef7d6">reorderInstructions</a> (Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reorders instructions by walking up the tree from each operand of an output instruction and reducing the def-use distance. <a href="#aa8f279ce9fe7b7fa5e3d2994253ef7d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af863f59a022cd3c77a9db7b4b9e9be80">reorderDefinition</a> (Instruction *Definition, std::stack&lt; Instruction * &gt; &amp;TopologicalSort, SmallPtrSet&lt; const Instruction *, 32 &gt; &amp;Visited) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade39e68d6b734c0bb620f639e213bd03">reorderInstructionOperandsByNames</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reorders instruction's operands alphabetically. <a href="#ade39e68d6b734c0bb620f639e213bd03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31ddbc365836dffba824dfbfdb8c3f0b">reorderPHIIncomingValues</a> (PHINode *Phi) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reorders PHI node's values according to the names of corresponding basic blocks. <a href="#a31ddbc365836dffba824dfbfdb8c3f0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Utility methods. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b47bdab305c78760e89e5fb43dfb5e2">sortCommutativeOperands</a> (Instruction *I, T &amp;Operands) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a457830d297e8ce441775a4702befb8f7">collectOutputInstructions</a> (Function &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a vector of output instructions. <a href="#a457830d297e8ce441775a4702befb8f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad34b1ba54a759e2afd1000e5b503c36c">isOutput</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper method checking whether the instruction may have side effects or is <a href="/web-llvm/docs/api/classes/llvm/returninst">ReturnInst</a>. <a href="#ad34b1ba54a759e2afd1000e5b503c36c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2967162a275530affcf2b1f2e102d22d">isInitialInstruction</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper method checking whether the instruction has users and only immediate operands. <a href="#a2967162a275530affcf2b1f2e102d22d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa61dc07914e983a914615b436e72608b">hasOnlyImmediateOperands</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper method checking whether the instruction has only immediate operands. <a href="#aa61dc07914e983a914615b436e72608b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa91dfeeb0f0b6cb429ff014daf9005ce">getOutputFootprint</a> (Instruction *I, SmallPtrSet&lt; const Instruction *, 32 &gt; &amp;Visited) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper method returning indices (distance from the beginning of the basic block) of outputs using the <span class="doxyComputerOutput">I</span> (eliminates repetitions). <a href="#aa91dfeeb0f0b6cb429ff014daf9005ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-irnormalizer-cpp-/irnormalizer">IRNormalizer</a> aims to transform LLVM IR into normal form.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### runOnFunction() {#a6ff04883b7477c97a6150fb1528c5f2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRNormalizer::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Entry method to the <a href="/web-llvm/docs/api/classes/anonymous-irnormalizer-cpp-/irnormalizer">IRNormalizer</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to normalize.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="#a8a3a517f01ed0104bff058519dd163f3">PreserveOrder</a> and <a href="#a3eeb4c93470d693726fad1750141c6c3">ReorderOperands</a>.</p>

</div>
</div>

### sortCommutativeOperands() {#a8b47bdab305c78760e89e5fb43dfb5e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{IRNormalizer.cpp}::IRNormalizer::sortCommutativeOperands (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, T &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MagicHashConstant {#a86bf1ea57d453f800350ba5424c66b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t anonymous{IRNormalizer.cpp}::IRNormalizer::MagicHashConstant = 0x6acaa36bef8325c5ULL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### NamedInstructions {#a5130cb329d1f5b07a833cb48e5f20ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;const Instruction *&gt; anonymous{IRNormalizer.cpp}::IRNormalizer::NamedInstructions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### Outputs {#a7f627b576a5a64d3822fa1121781bc6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 16&gt; anonymous{IRNormalizer.cpp}::IRNormalizer::Outputs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Normalizer flags.



<p>Preserves original order of instructions.</p>


### FoldPreOutputs {#a93387b667d20ca3cd6307f21b549636a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; IRNormalizer::FoldPreOutputs</td>
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

<p>Folds all regular instructions (including pre-outputs).</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### PreserveOrder {#a8a3a517f01ed0104bff058519dd163f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; IRNormalizer::PreserveOrder</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>


<p>Referenced by <a href="#a6ff04883b7477c97a6150fb1528c5f2d">runOnFunction</a>.</p>

</div>
</div>

### RenameAll {#a8b220486b5acfa4acac72303b353d5eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; IRNormalizer::RenameAll</td>
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

<p>Renames all instructions (including user-named).</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### ReorderOperands {#a3eeb4c93470d693726fad1750141c6c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; IRNormalizer::ReorderOperands</td>
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

<p>Sorts and reorders operands in commutative instructions.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>


<p>Referenced by <a href="#a6ff04883b7477c97a6150fb1528c5f2d">runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Naming.

### foldInstructionName {#ae7778d3996635b865b4f984a4c206cad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRNormalizer::foldInstructionName (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Shortens instruction's name.</p>


<p>This method removes called function name from the instruction name and substitutes the call chain with a corresponding list of operands.</p>


<p>Examples: op00000Callee(op00001Callee(...), vl00000Callee(1, 2), ...) -&gt; op00000(op00001, vl00000, ...) vl00000Callee(1, 2) -&gt; vl00000(1, 2)</p>


<p>This method omits output instructions and pre-output (instructions directly used by an output instruction) instructions (by default). By default it also does not affect user named instructions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> whose name will be folded.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### nameAsInitialInstruction {#a137687412584c3815d30b20ff8a3fa77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRNormalizer::nameAsInitialInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Names instruction following the scheme: vl00000Callee(Operands)</p>


<p>Where 00000 is a hash calculated considering instruction's opcode and output footprint. Callee's name is only included when instruction's type is <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a>. In cases where instruction is commutative, operands list is also sorted.</p>


<p>Renames instruction only when RenameAll flag is raised or instruction is unnamed.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>getOutputFootprint()</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to be renamed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### nameAsRegularInstruction {#a76a70088a3d58525c470b2e7dadbf6b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRNormalizer::nameAsRegularInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Names instruction following the scheme: op00000Callee(Operands)</p>


<p>Where 00000 is a hash calculated considering instruction's opcode, its operands' opcodes and order. Callee's name is only included when instruction's type is <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a>. In cases where instruction is commutative, operand list is also sorted.</p>


<p>Names instructions recursively in accordance with the def-use tree, starting from the initial instructions (defs), finishing at the output (top-most user) instructions (depth-first).</p>


<p>Renames instruction only when RenameAll flag is raised or instruction is unnamed.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>getOutputFootprint()</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to be renamed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### nameBasicBlocks {#a171621aa370f3e139023478791aef7c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRNormalizer::nameBasicBlocks (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Names basic blocks using a generated hash for each basic block in a function considering the opcode and the order of output instructions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> containing basic blocks to rename.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### nameFunctionArguments {#a80c89a3f73dfd63cd5da1dc43af1bb8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRNormalizer::nameFunctionArguments (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Numbers arguments.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> whose arguments will be renamed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### nameInstruction {#aabcf6258fa19c6e56d0646d94a6a6246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRNormalizer::nameInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Names instructions graphically (recursive) in accordance with the def-use tree, starting from the initial instructions (defs), finishing at the output (top-most user) instructions (depth-first).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to be renamed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Reordering.

### reorderDefinition {#af863f59a022cd3c77a9db7b4b9e9be80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRNormalizer::reorderDefinition (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Definition, std::stack&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; TopologicalSort, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 32 &gt; &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### reorderInstructionOperandsByNames {#ade39e68d6b734c0bb620f639e213bd03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRNormalizer::reorderInstructionOperandsByNames (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reorders instruction's operands alphabetically.</p>


<p>This method assumes that passed instruction is commutative. Changing the operand order in other instructions may change the semantics.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> whose operands will be reordered.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### reorderInstructions {#aa8f279ce9fe7b7fa5e3d2994253ef7d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRNormalizer::reorderInstructions (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reorders instructions by walking up the tree from each operand of an output instruction and reducing the def-use distance.</p>


<p>This method assumes that output instructions were collected top-down, otherwise the def-use chain may be broken. This method is a wrapper for recursive reorderInstruction().</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>reorderInstruction()</p></dd>
</dl>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### reorderPHIIncomingValues {#a31ddbc365836dffba824dfbfdb8c3f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRNormalizer::reorderPHIIncomingValues (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reorders PHI node's values according to the names of corresponding basic blocks.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Phi</td>
<td class="doxyParamItemDescription"><p>PHI node to normalize.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Utility methods.

### collectOutputInstructions {#a457830d297e8ce441775a4702befb8f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; Instruction *, 16 &gt; IRNormalizer::collectOutputInstructions (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a vector of output instructions.</p>


<p>An output is an instruction which has side-effects or is <a href="/web-llvm/docs/api/classes/llvm/returninst">ReturnInst</a>. Uses isOutput().</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>isOutput()</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to collect outputs from.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### getOutputFootprint {#aa91dfeeb0f0b6cb429ff014daf9005ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt; int &gt; IRNormalizer::getOutputFootprint (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 32 &gt; &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper method returning indices (distance from the beginning of the basic block) of outputs using the <span class="doxyComputerOutput">I</span> (eliminates repetitions).</p>


<p>Walks down the def-use tree recursively.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p>Considered instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Visited</td>
<td class="doxyParamItemDescription"><p>Set of visited instructions.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### hasOnlyImmediateOperands {#aa61dc07914e983a914615b436e72608b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRNormalizer::hasOnlyImmediateOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper method checking whether the instruction has only immediate operands.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p>Considered instruction.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### isInitialInstruction {#a2967162a275530affcf2b1f2e102d22d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRNormalizer::isInitialInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper method checking whether the instruction has users and only immediate operands.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p>Considered instruction.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### isOutput {#ad34b1ba54a759e2afd1000e5b503c36c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRNormalizer::isOutput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper method checking whether the instruction may have side effects or is <a href="/web-llvm/docs/api/classes/llvm/returninst">ReturnInst</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p>Considered instruction.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

### sortCommutativeOperands {#a8b47bdab305c78760e89e5fb43dfb5e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{IRNormalizer.cpp}::IRNormalizer::sortCommutativeOperands (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, T &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/irnormalizer-cpp">IRNormalizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
