---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/passmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PassManager` Class Template Reference

<p>Manages a sequence of passes over a particular unit of IR. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename IRUnitT, typename AnalysisManagerT = AnalysisManager&lt;IRUnitT&gt;, typename... ExtraArgTs&gt;
class llvm::PassManager&lt;IRUnitT, AnalysisManagerT, ExtraArgTs&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9a39a976ec31bf0cf6b8fd2da0327b66">PassConceptT</a> = <a href="/web-llvm/docs/api/structs/llvm/detail/passconcept">detail::PassConcept</a>&lt; IRUnitT, AnalysisManagerT, ExtraArgTs... &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8feea6425d71b06eb9eea6dfb60dcf4e">PassManager</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a pass manager. <a href="#a8feea6425d71b06eb9eea6dfb60dcf4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a02a2435b416a0e0c35d455b8634a4dbb">PassManager</a> (PassManager &amp;&amp;Arg)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3983ddbc27744d1423b2bad268869caa">operator=</a> (PassManager &amp;&amp;RHS)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a155889188eb0c299a1b2c69930bc9e2b">printPipeline</a> (raw_ostream &amp;OS, function_ref&lt; StringRef(StringRef)&gt; MapClassName2PassName)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aef5d9142acafceffd14c76b8ddd0fd4e">run</a> (IRUnitT &amp;IR, AnalysisManagerT &amp;AM, ExtraArgTs... ExtraArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run all of the passes in this manager over the given unit of IR. <a href="#aef5d9142acafceffd14c76b8ddd0fd4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3b988beeca0390fa8fa653d17bded384">addPass</a> (PassT &amp;&amp;Pass) -&gt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ac2ac12f478def782d8c823536e7ebcf7">LLVM_ATTRIBUTE_MINSIZE</a> std::enable_if_t&lt;!std::is_same_v&lt; PassT, <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa3e132679321009293a0289913d8b15b">addPass</a> (PassT &amp;&amp;Pass) -&gt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ac2ac12f478def782d8c823536e7ebcf7">LLVM_ATTRIBUTE_MINSIZE</a> std::enable_if_t&lt; std::is_same_v&lt; PassT, <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a> &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When adding a pass manager pass that has the same type as this pass manager, simply move the passes over. <a href="#aa3e132679321009293a0289913d8b15b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afdd422a60efda415b943a1c35dcd7de2">isEmpty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns if the pass manager contains any passes. <a href="#afdd422a60efda415b943a1c35dcd7de2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6d74effaad77f6ecb91e1806993cda8f">run</a> (LazyCallGraph::SCC &amp;InitialC, CGSCCAnalysisManager &amp;AM, LazyCallGraph &amp;G, CGSCCUpdateResult &amp;UR)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26223c50cd4a92948d2ac2a0d0e4eefd">run</a> (MachineFunction &amp;, AnalysisManager&lt; MachineFunction &gt; &amp;)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6d74effaad77f6ecb91e1806993cda8f">run</a> (LazyCallGraph::SCC &amp;InitialC, CGSCCAnalysisManager &amp;AM, LazyCallGraph &amp;G, CGSCCUpdateResult &amp;UR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Explicitly specialize the pass manager run method to handle call graph updates. <a href="#a6d74effaad77f6ecb91e1806993cda8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="#a9a39a976ec31bf0cf6b8fd2da0327b66">PassConceptT</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8bd144cba90e4ead30e5ee59165c4ee5">Passes</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa7a79037ff31d737403027e38d65e2d4">isRequired</a> ()</td>
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

<p>Manages a sequence of passes over a particular unit of IR.</p>


<p>A pass manager contains a sequence of passes to run over a particular unit of IR (e.g. Functions, Modules). It is itself a valid pass over that unit of IR, and when run over some given IR will run each of its contained passes in sequence. <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> managers are the primary and most basic building block of a pass pipeline.</p>


<p>When you run a pass manager, you provide an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager&lt;IRUnitT&gt;</a></span> argument. The pass manager will propagate that analysis manager to each pass it runs, and will call the analysis manager's invalidation routine with the <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> of each pass it runs.</p>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### PassConceptT {#a9a39a976ec31bf0cf6b8fd2da0327b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT = AnalysisManager&lt;IRUnitT&gt;, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::PassConceptT = 
      detail::PassConcept&lt;IRUnitT, AnalysisManagerT, ExtraArgTs...&gt;</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PassManager() {#a8feea6425d71b06eb9eea6dfb60dcf4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT = AnalysisManager&lt;IRUnitT&gt;, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::PassManager ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a pass manager.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### PassManager() {#a02a2435b416a0e0c35d455b8634a4dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT = AnalysisManager&lt;IRUnitT&gt;, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::PassManager (<a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a> &amp;&amp; Arg)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a3983ddbc27744d1423b2bad268869caa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT = AnalysisManager&lt;IRUnitT&gt;, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassManager &amp; llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addPass() {#a3b988beeca0390fa8fa653d17bded384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_MINSIZE std::enable_if_t&lt;!std::is_same_v&lt; PassT, PassManager &gt; &gt; llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass (PassT &amp;&amp; Pass)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a38315765eaec2665ca76556b908a593d">addAnnotationRemarksPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#aeee6e6170878c432ee2b1faffc755b4c">llvm::PassBuilder::addPGOInstrPassesForO0</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad4548cd9e4b6358214f2e34e5e56112e">llvm::PassBuilder::buildFatLTODefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9501d22da3319c387a0a617fc4ffcc31">llvm::PassBuilder::buildFunctionSimplificationPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a08240a2eba496a292cec022c5093f621">llvm::PassBuilder::buildInlinerPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab319565ffed9e4cb2aff1aa78847ec2d">llvm::PassBuilder::buildLTODefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab53586b47722fa95d93ae8b06f734742">llvm::PassBuilder::buildModuleInlinerPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adf20f88f2a71fd5cd08708b9da72979a">llvm::PassBuilder::buildModuleOptimizationPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad6f258d31ffa2d2e4dfaf990ba596d0d">llvm::PassBuilder::buildModuleSimplificationPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a94e03b8856e739853a1419da126f1758">llvm::PassBuilder::buildO0DefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a546f4259efb4e1629d1d14b8757c52c4">llvm::PassBuilder::buildPerModuleDefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab7d260f2f928c81a2d225f2d1aafad0e">llvm::PassBuilder::buildThinLTODefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a2832cb00a6c94208b4a06696eeeabf99">llvm::PassBuilder::buildThinLTOPreLinkDefaultPipeline</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp/#a740b270dfd80a81a0765fb1d31930828">eliminateDeadCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ac80362d592aa56ce616f030fbc3a0bd0">if</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a16b9126d671cbce7e45e877cc583d405">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::insertPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f5ff058df930ce88aba780fa5191562">llvm::parseAnalysisUtilityPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a50e2c161ce287abb803123ade461704a">llvm::AArch64TargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ab727dbb342900913787fc58840a3c002">llvm::AMDGPUTargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetmachine/#a4d46609394256ee755db3484c4eb6639">llvm::BPFTargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine/#a301180369f0e5f22cceb79f2f7c9220e">llvm::NVPTXTargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/structs/llvm/corocleanuppass/#ad94b3bcb5dea38b6b7d891fa9344322c">llvm::CoroCleanupPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ae1dadcf6ee688f96abb563274e620f44">llvm::AMDGPUTargetMachine::splitModule</a> and <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass/#a6ba71a875e2f1102b6f3dbaf3d17b75d">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::AddMachinePass::~AddMachinePass</a>.</p>

</div>
</div>

### addPass() {#aa3e132679321009293a0289913d8b15b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_MINSIZE std::enable_if_t&lt; std::is_same_v&lt; PassT, PassManager &gt; &gt; llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass (PassT &amp;&amp; Pass)</td>
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

<p>When adding a pass manager pass that has the same type as this pass manager, simply move the passes over.</p>


<p>This is because we don't have use cases rely on executing nested pass managers. Doing this could reduce implementation complexity and avoid potential invalidation issues that may happen with nested pass managers of the same type.</p>


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### isEmpty() {#afdd422a60efda415b943a1c35dcd7de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT = AnalysisManager&lt;IRUnitT&gt;, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::isEmpty ()</td>
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

<p>Returns if the pass manager contains any passes.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a94e03b8856e739853a1419da126f1758">llvm::PassBuilder::buildO0DefaultPipeline</a>.</p>

</div>
</div>

### printPipeline() {#a155889188eb0c299a1b2c69930bc9e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT = AnalysisManager&lt;IRUnitT&gt;, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::printPipeline (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; MapClassName2PassName)</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### run() {#aef5d9142acafceffd14c76b8ddd0fd4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT = AnalysisManager&lt;IRUnitT&gt;, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run (IRUnitT &amp; IR, AnalysisManagerT &amp; AM, ExtraArgTs... ExtraArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run all of the passes in this manager over the given unit of IR.</p>


<p>ExtraArgs are passed to each pass.</p>


<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerimpl-h">PassManagerImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#a1258a1ff55557c27684010ebd7283712">llvm::PreservedAnalyses::all</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#abd2eb0563df3078fb91a47d6203fe1d6">llvm::detail::getAnalysisResult</a>, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation/#a79b8b2488fca01c969f40f133c416e99">llvm::PassInstrumentation::getPassNameForClassName</a>, <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#a5f5dc18d0b2c71cba501f12975188e40">llvm::PreservedAnalyses::intersect</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a8bd144cba90e4ead30e5ee59165c4ee5">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::Passes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>, <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#a937c42f77e161349ce0f999e448c7027">llvm::PreservedAnalyses::preserveSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e747628bd3eea8ba888d3615c900c9f">llvm::printIRUnitNameForStackTrace</a>, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation/#acec038dce9072b64301f6e5226c5579a">llvm::PassInstrumentation::runAfterPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation/#aead32b9af4b66a742d37585c6d6b4cbc">llvm::PassInstrumentation::runBeforePass</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerimpl-h/#a926189935285d6e5df83fc0f45bf9b36">UseNewDbgInfoFormat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp/#a740b270dfd80a81a0765fb1d31930828">eliminateDeadCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ac80362d592aa56ce616f030fbc3a0bd0">if</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="/web-llvm/docs/api/structs/llvm/corocleanuppass/#ad94b3bcb5dea38b6b7d891fa9344322c">llvm::CoroCleanupPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ae1dadcf6ee688f96abb563274e620f44">llvm::AMDGPUTargetMachine::splitModule</a>.</p>

</div>
</div>

### run() {#a6d74effaad77f6ecb91e1806993cda8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT = AnalysisManager&lt;IRUnitT&gt;, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> &amp; InitialC, <a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp; G, <a href="/web-llvm/docs/api/structs/llvm/cgsccupdateresult">CGSCCUpdateResult</a> &amp; UR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>

</div>
</div>

### run() {#a26223c50cd4a92948d2ac2a0d0e4eefd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT = AnalysisManager&lt;IRUnitT&gt;, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses llvm::PassManager&lt; MachineFunction &gt;::run (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &gt; &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepassmanager-h">MachinePassManager.h</a>.</p>

</div>
</div>

### run() {#a6d74effaad77f6ecb91e1806993cda8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT = AnalysisManager&lt;IRUnitT&gt;, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> &amp; InitialC, <a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp; G, <a href="/web-llvm/docs/api/structs/llvm/cgsccupdateresult">CGSCCUpdateResult</a> &amp; UR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Explicitly specialize the pass manager run method to handle call graph updates.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp">CGSCCPassManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Passes {#a8bd144cba90e4ead30e5ee59165c4ee5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT = AnalysisManager&lt;IRUnitT&gt;, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;PassConceptT&gt; &gt; llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::Passes</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<p>Referenced by <a href="#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isRequired() {#aa7a79037ff31d737403027e38d65e2d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT = AnalysisManager&lt;IRUnitT&gt;, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::isRequired ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepassmanager-h">MachinePassManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerimpl-h">PassManagerImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp">CGSCCPassManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
