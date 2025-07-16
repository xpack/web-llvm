---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/passbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PassBuilder` Class Reference

<p>This class provides access to building LLVM's passes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PassBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">llvm/Passes/PassBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a322fc14d985cd25592d641ab24cc787e">PassBuilder</a> (TargetMachine *TM=nullptr, PipelineTuningOptions PTO=PipelineTuningOptions(), std::optional&lt; PGOOptions &gt; PGOOpt=std::nullopt, PassInstrumentationCallbacks *PIC=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c2e12459e81e47a53dc49484af24bc2">crossRegisterProxies</a> (LoopAnalysisManager &amp;LAM, FunctionAnalysisManager &amp;FAM, CGSCCAnalysisManager &amp;CGAM, ModuleAnalysisManager &amp;MAM, MachineFunctionAnalysisManager *MFAM=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cross register the analysis managers through their proxies. <a href="#a3c2e12459e81e47a53dc49484af24bc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acba45c16e3934023f1fe17627951b5b8">registerModuleAnalyses</a> (ModuleAnalysisManager &amp;MAM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers all available module analysis passes. <a href="#acba45c16e3934023f1fe17627951b5b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2d3999ee96b77c4c40f4d747609f205">registerCGSCCAnalyses</a> (CGSCCAnalysisManager &amp;CGAM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers all available CGSCC analysis passes. <a href="#ad2d3999ee96b77c4c40f4d747609f205">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9903a32cb913723bc7608f6544995d1">registerFunctionAnalyses</a> (FunctionAnalysisManager &amp;FAM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers all available function analysis passes. <a href="#af9903a32cb913723bc7608f6544995d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32a8612a117894df2f1f35c72dce226e">registerLoopAnalyses</a> (LoopAnalysisManager &amp;LAM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers all available loop analysis passes. <a href="#a32a8612a117894df2f1f35c72dce226e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add26afb1d231a436e197b8e73ae72079">registerMachineFunctionAnalyses</a> (MachineFunctionAnalysisManager &amp;MFAM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers all available machine function analysis passes. <a href="#add26afb1d231a436e197b8e73ae72079">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9501d22da3319c387a0a617fc4ffcc31">buildFunctionSimplificationPipeline</a> (OptimizationLevel Level, ThinOrFullLTOPhase Phase)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct the core LLVM function canonicalization and simplification pipeline. <a href="#a9501d22da3319c387a0a617fc4ffcc31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6f258d31ffa2d2e4dfaf990ba596d0d">buildModuleSimplificationPipeline</a> (OptimizationLevel Level, ThinOrFullLTOPhase Phase)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct the core LLVM module canonicalization and simplification pipeline. <a href="#ad6f258d31ffa2d2e4dfaf990ba596d0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/moduleinlinerwrapperpass">ModuleInlinerWrapperPass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08240a2eba496a292cec022c5093f621">buildInlinerPipeline</a> (OptimizationLevel Level, ThinOrFullLTOPhase Phase)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct the module pipeline that performs inlining as well as the inlining-driven cleanups. <a href="#a08240a2eba496a292cec022c5093f621">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab53586b47722fa95d93ae8b06f734742">buildModuleInlinerPipeline</a> (OptimizationLevel Level, ThinOrFullLTOPhase Phase)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct the module pipeline that performs inlining with module inliner pass. <a href="#ab53586b47722fa95d93ae8b06f734742">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf20f88f2a71fd5cd08708b9da72979a">buildModuleOptimizationPipeline</a> (OptimizationLevel Level, ThinOrFullLTOPhase LTOPhase)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct the core LLVM module optimization pipeline. <a href="#adf20f88f2a71fd5cd08708b9da72979a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a546f4259efb4e1629d1d14b8757c52c4">buildPerModuleDefaultPipeline</a> (OptimizationLevel Level, ThinOrFullLTOPhase Phase=ThinOrFullLTOPhase::None)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a per-module default optimization pipeline. <a href="#a546f4259efb4e1629d1d14b8757c52c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4548cd9e4b6358214f2e34e5e56112e">buildFatLTODefaultPipeline</a> (OptimizationLevel Level, bool ThinLTO, bool EmitSummary)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a fat object default optimization pipeline. <a href="#ad4548cd9e4b6358214f2e34e5e56112e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2832cb00a6c94208b4a06696eeeabf99">buildThinLTOPreLinkDefaultPipeline</a> (OptimizationLevel Level)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a pre-link, ThinLTO-targeting default optimization pipeline to a pass manager. <a href="#a2832cb00a6c94208b4a06696eeeabf99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d260f2f928c81a2d225f2d1aafad0e">buildThinLTODefaultPipeline</a> (OptimizationLevel Level, const ModuleSummaryIndex *ImportSummary)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a ThinLTO default optimization pipeline to a pass manager. <a href="#ab7d260f2f928c81a2d225f2d1aafad0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7de51d7cbb98b83f2c01faf23b72472">buildLTOPreLinkDefaultPipeline</a> (OptimizationLevel Level)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a pre-link, LTO-targeting default optimization pipeline to a pass manager. <a href="#af7de51d7cbb98b83f2c01faf23b72472">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab319565ffed9e4cb2aff1aa78847ec2d">buildLTODefaultPipeline</a> (OptimizationLevel Level, ModuleSummaryIndex *ExportSummary)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build an LTO default optimization pipeline to a pass manager. <a href="#ab319565ffed9e4cb2aff1aa78847ec2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94e03b8856e739853a1419da126f1758">buildO0DefaultPipeline</a> (OptimizationLevel Level, ThinOrFullLTOPhase Phase=ThinOrFullLTOPhase::None)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build an O0 pipeline with the minimal semantically required passes. <a href="#a94e03b8856e739853a1419da126f1758">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aamanager">AAManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d045f9463f65181b84ac5dc7eafafe8">buildDefaultAAPipeline</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build the default <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/aamanager">AAManager</a></span> with the default alias analysis pipeline registered. <a href="#a1d045f9463f65181b84ac5dc7eafafe8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca0e57e6445ab2fe568e53ba29cc0fd">parsePassPipeline</a> (ModulePassManager &amp;MPM, StringRef PipelineText)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a textual pass pipeline description into a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></span>. <a href="#a9ca0e57e6445ab2fe568e53ba29cc0fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a581197bc2dbbef326892f5ff08761f54">parsePassPipeline</a> (CGSCCPassManager &amp;CGPM, StringRef PipelineText)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>{{@ Parse a textual pass pipeline description into a specific <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a> <a href="#a581197bc2dbbef326892f5ff08761f54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3231081094bc7fdda779c6b73f9f706">parsePassPipeline</a> (FunctionPassManager &amp;FPM, StringRef PipelineText)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c60ec47f90dce41d2bbc71a913c696e">parsePassPipeline</a> (LoopPassManager &amp;LPM, StringRef PipelineText)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088814462db14cd89651bd90f390e30d">parsePassPipeline</a> (MachineFunctionPassManager &amp;MFPM, StringRef PipelineText)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a textual MIR pipeline into the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></span> manager. <a href="#a088814462db14cd89651bd90f390e30d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d4e2a477b2b896adfdec5e55638b725">parseAAPipeline</a> (AAManager &amp;AA, StringRef PipelineText)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a textual alias analysis pipeline into the provided <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> manager. <a href="#a1d4e2a477b2b896adfdec5e55638b725">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a0ab9dba764b528b15e89f9c443b2e202">RegAllocFilterFunc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f205775871eede46d8dc00413cbf3f">parseRegAllocFilter</a> (StringRef RegAllocFilterName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse RegAllocFilterName to get <a href="/web-llvm/docs/api/namespaces/llvm/#a0ab9dba764b528b15e89f9c443b2e202">RegAllocFilterFunc</a>. <a href="#a35f205775871eede46d8dc00413cbf3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bcf38a395ef95aeb79b647a85a427ee">printPassNames</a> (raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print pass names. <a href="#a0bcf38a395ef95aeb79b647a85a427ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac5d2f0e7a33e8ba20e5f7f28f60791">registerPeepholeEPCallback</a> (const std::function&lt; void(FunctionPassManager &amp;, OptimizationLevel)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point. <a href="#a5ac5d2f0e7a33e8ba20e5f7f28f60791">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a37b41d4336528168634988528da584">registerLateLoopOptimizationsEPCallback</a> (const std::function&lt; void(LoopPassManager &amp;, OptimizationLevel)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point. <a href="#a3a37b41d4336528168634988528da584">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41a2daec8ce577e45502b430f5e190d3">registerLoopOptimizerEndEPCallback</a> (const std::function&lt; void(LoopPassManager &amp;, OptimizationLevel)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point. <a href="#a41a2daec8ce577e45502b430f5e190d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f680e4b9b66bf942083addab4886aa1">registerScalarOptimizerLateEPCallback</a> (const std::function&lt; void(FunctionPassManager &amp;, OptimizationLevel)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point. <a href="#a6f680e4b9b66bf942083addab4886aa1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a983eb9382d100af683d80513869f36c4">registerCGSCCOptimizerLateEPCallback</a> (const std::function&lt; void(CGSCCPassManager &amp;, OptimizationLevel)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point. <a href="#a983eb9382d100af683d80513869f36c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b4af342809d2b24844972dae47d201">registerVectorizerStartEPCallback</a> (const std::function&lt; void(FunctionPassManager &amp;, OptimizationLevel)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point. <a href="#a50b4af342809d2b24844972dae47d201">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c79d6634d4333b578eee9468600545f">registerPipelineStartEPCallback</a> (const std::function&lt; void(ModulePassManager &amp;, OptimizationLevel)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point. <a href="#a2c79d6634d4333b578eee9468600545f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267c74c52d09d66146ce289acb4ba3be">registerPipelineEarlySimplificationEPCallback</a> (const std::function&lt; void(ModulePassManager &amp;, OptimizationLevel, ThinOrFullLTOPhase)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point. <a href="#a267c74c52d09d66146ce289acb4ba3be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add1e5f9adbdfe781825eeb0e4e0925ba">registerOptimizerEarlyEPCallback</a> (const std::function&lt; void(ModulePassManager &amp;, OptimizationLevel, ThinOrFullLTOPhase Phase)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point. <a href="#add1e5f9adbdfe781825eeb0e4e0925ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41abe02ceef34a89fd73bf8e85987bcd">registerOptimizerLastEPCallback</a> (const std::function&lt; void(ModulePassManager &amp;, OptimizationLevel, ThinOrFullLTOPhase)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point. <a href="#a41abe02ceef34a89fd73bf8e85987bcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abca5690a1a0abc98824d0f15ce3f4a93">registerFullLinkTimeOptimizationEarlyEPCallback</a> (const std::function&lt; void(ModulePassManager &amp;, OptimizationLevel)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point. <a href="#abca5690a1a0abc98824d0f15ce3f4a93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2d03850eda381e9418b90eca468dda7">registerFullLinkTimeOptimizationLastEPCallback</a> (const std::function&lt; void(ModulePassManager &amp;, OptimizationLevel)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point. <a href="#ad2d03850eda381e9418b90eca468dda7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44e4fe174172d86171cde9a67ea19d38">registerParseAACallback</a> (const std::function&lt; bool(StringRef Name, AAManager &amp;AA)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for parsing an <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> Name to populate the given <a href="/web-llvm/docs/api/classes/llvm/aamanager">AAManager</a> <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span>. <a href="#a44e4fe174172d86171cde9a67ea19d38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78c148ed6b206155773e9262a71c61f8">registerAnalysisRegistrationCallback</a> (const std::function&lt; void(CGSCCAnalysisManager &amp;)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>{{@ <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> callbacks for analysis registration with this <a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a> instance. <a href="#a78c148ed6b206155773e9262a71c61f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f2c24753d0095be3183dcf27e7ed10a">registerAnalysisRegistrationCallback</a> (const std::function&lt; void(FunctionAnalysisManager &amp;)&gt; &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5119b687767244844ee692505b41e4a8">registerAnalysisRegistrationCallback</a> (const std::function&lt; void(LoopAnalysisManager &amp;)&gt; &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a285d4112f73fb910b3d8d79dd4886471">registerAnalysisRegistrationCallback</a> (const std::function&lt; void(ModuleAnalysisManager &amp;)&gt; &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a18fef11307bda3a292ec8c74470d48">registerAnalysisRegistrationCallback</a> (const std::function&lt; void(MachineFunctionAnalysisManager &amp;)&gt; &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9268c557f7572dc641ac05aaff0c2ac">registerPipelineParsingCallback</a> (const std::function&lt; bool(StringRef Name, CGSCCPassManager &amp;, ArrayRef&lt; PipelineElement &gt;)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>{{@ <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> pipeline parsing callbacks with this pass builder instance. <a href="#ab9268c557f7572dc641ac05aaff0c2ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac57131cc89f11b1e31859a0a9e420d60">registerPipelineParsingCallback</a> (const std::function&lt; bool(StringRef Name, FunctionPassManager &amp;, ArrayRef&lt; PipelineElement &gt;)&gt; &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fb9d712436059b253d38b22775ef225">registerPipelineParsingCallback</a> (const std::function&lt; bool(StringRef Name, LoopPassManager &amp;, ArrayRef&lt; PipelineElement &gt;)&gt; &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf4745be1d8c37779f3ba1451d182e1">registerPipelineParsingCallback</a> (const std::function&lt; bool(StringRef Name, ModulePassManager &amp;, ArrayRef&lt; PipelineElement &gt;)&gt; &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada980b5fa41be687b6ada7ad11e7a7c0">registerPipelineParsingCallback</a> (const std::function&lt; bool(StringRef Name, MachineFunctionPassManager &amp;, ArrayRef&lt; PipelineElement &gt;)&gt; &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1e097b85fd09a6964448e5e95761fcc">registerRegClassFilterParsingCallback</a> (const std::function&lt; RegAllocFilterFunc(StringRef)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> callbacks to parse target specific filter field if regalloc pass needs it. <a href="#ab1e097b85fd09a6964448e5e95761fcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf6d945d01a37f386a86d80d1072d01a">registerParseTopLevelPipelineCallback</a> (const std::function&lt; bool(ModulePassManager &amp;, ArrayRef&lt; PipelineElement &gt;)&gt; &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a top-level pipeline entry. <a href="#adf6d945d01a37f386a86d80d1072d01a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee6e6170878c432ee2b1faffc755b4c">addPGOInstrPassesForO0</a> (ModulePassManager &amp;MPM, bool RunProfileGen, bool IsCS, bool AtomicCounterUpdate, std::string ProfileFile, std::string ProfileRemappingFile, IntrusiveRefCntPtr&lt; vfs::FileSystem &gt; FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add PGOInstrumenation passes for O0 only. <a href="#aeee6e6170878c432ee2b1faffc755b4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e1471d80ab41f6c9748a5d10b91303">getPassInstrumentationCallbacks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns PIC. <a href="#a38e1471d80ab41f6c9748a5d10b91303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a992749181a4f666d5192eda4300b70cc">invokePeepholeEPCallbacks</a> (FunctionPassManager &amp;FPM, OptimizationLevel Level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2b1153446499aae16b90ea6bda946e4">invokeLateLoopOptimizationsEPCallbacks</a> (LoopPassManager &amp;LPM, OptimizationLevel Level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa30bda56b0554c3925dba6626fd9fff6">invokeLoopOptimizerEndEPCallbacks</a> (LoopPassManager &amp;LPM, OptimizationLevel Level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e0e9b1cc99f7bbf615c9a7513938a0c">invokeScalarOptimizerLateEPCallbacks</a> (FunctionPassManager &amp;FPM, OptimizationLevel Level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24bbb807c0f1667d9dca483258747a59">invokeCGSCCOptimizerLateEPCallbacks</a> (CGSCCPassManager &amp;CGPM, OptimizationLevel Level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bd4ee77dc2e2e93591e982a816ffe44">invokeVectorizerStartEPCallbacks</a> (FunctionPassManager &amp;FPM, OptimizationLevel Level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a17ea5b5ceb7624eec6f9dd79f36a4">invokeOptimizerEarlyEPCallbacks</a> (ModulePassManager &amp;MPM, OptimizationLevel Level, ThinOrFullLTOPhase Phase)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2f3b63161e415605292b1cc40b08ac1">invokeOptimizerLastEPCallbacks</a> (ModulePassManager &amp;MPM, OptimizationLevel Level, ThinOrFullLTOPhase Phase)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a19c4dfd315d77ffb14a769cf583af">invokeFullLinkTimeOptimizationEarlyEPCallbacks</a> (ModulePassManager &amp;MPM, OptimizationLevel Level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a079790ccc6b6d4fd34df68c5c500a46f">invokeFullLinkTimeOptimizationLastEPCallbacks</a> (ModulePassManager &amp;MPM, OptimizationLevel Level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7be5d1c757e25b6be1bd5634f159ceab">invokePipelineStartEPCallbacks</a> (ModulePassManager &amp;MPM, OptimizationLevel Level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a94759ace31aca9af485567995189ba">invokePipelineEarlySimplificationEPCallbacks</a> (ModulePassManager &amp;MPM, OptimizationLevel Level, ThinOrFullLTOPhase Phase)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab79f4e990c7d7952ea240decf070632f">buildO1FunctionSimplificationPipeline</a> (OptimizationLevel Level, ThinOrFullLTOPhase Phase)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9638052437a3d6da96be24fb03709827">addRequiredLTOPreLinkPasses</a> (ModulePassManager &amp;MPM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bb4673c43fc983cb08ed2af51567e54">addVectorPasses</a> (OptimizationLevel Level, FunctionPassManager &amp;FPM, bool IsFullLTO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TODO: Should LTO cause any differences to this set of passes? <a href="#a6bb4673c43fc983cb08ed2af51567e54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13ab776e0142ba221bba7677898efc88">parseModulePass</a> (ModulePassManager &amp;MPM, const PipelineElement &amp;E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9384aa2cc31d8453ab77d4260fb6a13a">parseCGSCCPass</a> (CGSCCPassManager &amp;CGPM, const PipelineElement &amp;E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb399928be5d7edf3615289fa78a43f6">parseFunctionPass</a> (FunctionPassManager &amp;FPM, const PipelineElement &amp;E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8513015025c73e6a6aaeac2de2279489">parseLoopPass</a> (LoopPassManager &amp;LPM, const PipelineElement &amp;E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74307702dfde39c25eec711e61305798">parseMachinePass</a> (MachineFunctionPassManager &amp;MFPM, const PipelineElement &amp;E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01caaefbe78c1697aabe3deb5a717e4c">parseAAPassName</a> (AAManager &amp;AA, StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a495b9d65d8ce8d6fcdb122ca5f81bfdd">parseMachinePassPipeline</a> (MachineFunctionPassManager &amp;MFPM, ArrayRef&lt; PipelineElement &gt; Pipeline)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cad940c7d9abf7471a163e9abc6e122">parseLoopPassPipeline</a> (LoopPassManager &amp;LPM, ArrayRef&lt; PipelineElement &gt; Pipeline)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cb4f113e1b6af04eebbacb1f833985f">parseFunctionPassPipeline</a> (FunctionPassManager &amp;FPM, ArrayRef&lt; PipelineElement &gt; Pipeline)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d54d7e4f3e27a71260c54e9171612a6">parseCGSCCPassPipeline</a> (CGSCCPassManager &amp;CGPM, ArrayRef&lt; PipelineElement &gt; Pipeline)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a831a5e63b1d2a455a8ce7769897cbff5">parseModulePassPipeline</a> (ModulePassManager &amp;MPM, ArrayRef&lt; PipelineElement &gt; Pipeline)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a039ef994baa5f61aa77db6eb04659f86">addPreInlinerPasses</a> (ModulePassManager &amp;MPM, OptimizationLevel Level, ThinOrFullLTOPhase LTOPhase)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ee27cbc56e740cbf25ff0757fa2b9b6">addPGOInstrPasses</a> (ModulePassManager &amp;MPM, OptimizationLevel Level, bool RunProfileGen, bool IsCS, bool AtomicCounterUpdate, std::string ProfileFile, std::string ProfileRemappingFile, IntrusiveRefCntPtr&lt; vfs::FileSystem &gt; FS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08e01c7433fc141447a80e1b234a2742">addPostPGOLoopRotation</a> (ModulePassManager &amp;MPM, OptimizationLevel Level)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4078492b9944119369a94390651a08f">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pipelinetuningoptions">PipelineTuningOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb75e46f0a8722b988934fee5607c9fd">PTO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/pgooptions">PGOOptions</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad595335c2b920f227a2835498cb7fa90">PGOOpt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6892617cd08e50c4a9e3e6c53f2582b">PIC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4cde43a30fb87989de4f6644d3d3e77">PeepholeEPCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a613892f4c1a570fd3747f2b6b1bf9b75">LoopPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af824c04d38b63ab6ed9ca7c6fe989c69">LateLoopOptimizationsEPCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a613892f4c1a570fd3747f2b6b1bf9b75">LoopPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6302dfa286f2267aebf58132c24194ed">LoopOptimizerEndEPCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b1c2af7df8c7056f42cd5b363456bc">ScalarOptimizerLateEPCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a4ded4558d2b58dcdd7a1736aa69a8bc4">CGSCCPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addfde929bf0d30cbc8df7a7499f16b9b">CGSCCOptimizerLateEPCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8985498403ab26c6521b11f1f4f07a63">VectorizerStartEPCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a>)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a218ccb8bab03982ac91dbf3cc5d0091f">OptimizerEarlyEPCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a>)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8fe7ed3ff3605e79cab87201dc527a8">OptimizerLastEPCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a848db2f749386f664711241c00d3c991">FullLinkTimeOptimizationEarlyEPCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dfd4723160dfbdd5fdff57429b63d8d">FullLinkTimeOptimizationLastEPCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c0e0ddbc25926a0584f0f8c2feb9f29">PipelineStartEPCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a>)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4596fd37c0422714997e3236c961ef02">PipelineEarlySimplificationEPCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp;)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56af268c419014c240961fdffa32c2c">ModuleAnalysisRegistrationCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt;)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af006beea2252e92d20431478269d5416">ModulePipelineParsingCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; bool(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt;)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c48972132e4f26014adb5d985d3f015">TopLevelPipelineParsingCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> &amp;)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac05d7c083726335e69f0498e17475dcf">CGSCCAnalysisRegistrationCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ded4558d2b58dcdd7a1736aa69a8bc4">CGSCCPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt;)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad858a6fa7d4df75114fb4b94906bacc6">CGSCCPipelineParsingCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp;)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5da6f00fcf4eb04140ee3476d42584a">FunctionAnalysisRegistrationCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt;)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6228bdcec0c6c7126bbf3f7cbe2040b9">FunctionPipelineParsingCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a> &amp;)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d97d9feb91bca950e9cc460e44471c5">LoopAnalysisRegistrationCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a613892f4c1a570fd3747f2b6b1bf9b75">LoopPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt;)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ee3557be559a185b98db7a38a79ef99">LoopPipelineParsingCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/aamanager">AAManager</a> &amp;AA)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ce053e76c1daf981ab1be4fc338df7">AAParsingCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a> &amp;)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8f4d51ae98fac2fa4b856e198c6c5c1">MachineFunctionAnalysisRegistrationCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4d6ff2181c8f2a8d4dabd70e55f2ba2">MachineFunctionPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt;)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d8b5378310abd0999cb9fdda1eaab54">MachineFunctionPipelineParsingCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a0ab9dba764b528b15e89f9c443b2e202">RegAllocFilterFunc</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e3d8d3c0f45550c9d8c97019cb2cef3">RegClassFilterParsingCallbacks</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d95457b7af7593624ad31405198d59d">checkParametrizedPassName</a> (StringRef Name, StringRef PassName)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParametersParseCallableT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad552dcd2825d0f59fae310931b7813bb">parsePassParameters</a> (ParametersParseCallableT &amp;&amp;Parser, StringRef Name, StringRef PassName) -&gt; decltype(Parser(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>{}))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This performs customized parsing of pass name with parameters. <a href="#ad552dcd2825d0f59fae310931b7813bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc2db790282de50547f17992a5dece6b">parseSinglePassOption</a> (StringRef Params, StringRef OptionName, StringRef PassName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle passes only accept one bool-valued parameter. <a href="#adc2db790282de50547f17992a5dece6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f7c19a0944e326653958887c447595">parsePipelineText</a> (StringRef Text)</td>
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

<p>This class provides access to building LLVM's passes.</p>


<p>Its members provide the baseline state available to passes during their construction. The <span class="doxyComputerOutput">PassRegistry.def</span> file specifies how to construct all of the built-in passes, and those may reference these members during construction.</p>


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PassBuilder() {#a322fc14d985cd25592d641ab24cc787e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassBuilder::PassBuilder (<a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM=nullptr, <a href="/web-llvm/docs/api/classes/llvm/pipelinetuningoptions">PipelineTuningOptions</a> PTO=<a href="/web-llvm/docs/api/classes/llvm/pipelinetuningoptions">PipelineTuningOptions</a>(), std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/pgooptions">PGOOptions</a> &gt; PGOOpt=std::nullopt, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> * PIC=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addPGOInstrPassesForO0() {#aeee6e6170878c432ee2b1faffc755b4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::addPGOInstrPassesForO0 (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, bool RunProfileGen, bool IsCS, bool AtomicCounterUpdate, std::string ProfileFile, std::string ProfileRemappingFile, <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &gt; FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add PGOInstrumenation passes for O0 only.</p>

<p>Declaration at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 868 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a405905ea235b6f5793566aa1411d2b85a9222f28c4f27830f496c4de2b5150733">llvm::CSFDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a405905ea235b6f5793566aa1411d2b85ad4ad311ebee92dc0993538d111f45b15">llvm::FDO</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="#a94e03b8856e739853a1419da126f1758">buildO0DefaultPipeline</a>.</p>

</div>
</div>

### buildDefaultAAPipeline() {#a1d045f9463f65181b84ac5dc7eafafe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAManager PassBuilder::buildDefaultAAPipeline ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build the default <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/aamanager">AAManager</a></span> with the default alias analysis pipeline registered.</p>


<p>This also adds target-specific alias analyses registered via <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab7caacf1b6625cc8fce9e8e9f5c95268">TargetMachine::registerDefaultAliasAnalyses()</a>.</p>


<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2266 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a07068e2ce7a7e26efcbd160d919131e0">EnableGlobalAnalyses</a>.</p>


<p>Referenced by <a href="#a1d4e2a477b2b896adfdec5e55638b725">parseAAPipeline</a> and <a href="#af9903a32cb913723bc7608f6544995d1">registerFunctionAnalyses</a>.</p>

</div>
</div>

### buildFatLTODefaultPipeline() {#ad4548cd9e4b6358214f2e34e5e56112e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePassManager PassBuilder::buildFatLTODefaultPipeline (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, bool ThinLTO, bool EmitSummary)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a fat object default optimization pipeline.</p>


<p>This builds a pipeline that runs the LTO/ThinLTO pre-link pipeline, and emits a section containing the pre-link bitcode along side the object code generated in non-LTO compilation.</p>


<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1643 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a38315765eaec2665ca76556b908a593d">addAnnotationRemarksPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lowertypetests/#a28baf2df0f23eab12b60755416e83adaab1c94ca2fbc3e78fc30069c8d0f01680">llvm::lowertypetests::All</a>, <a href="#af7de51d7cbb98b83f2c01faf23b72472">buildLTOPreLinkDefaultPipeline</a>, <a href="#adf20f88f2a71fd5cd08708b9da72979a">buildModuleOptimizationPipeline</a>, <a href="#ab7d260f2f928c81a2d225f2d1aafad0e">buildThinLTODefaultPipeline</a>, <a href="#a2832cb00a6c94208b4a06696eeeabf99">buildThinLTOPreLinkDefaultPipeline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6383dc1a150ac7cd92979a80681a71af">llvm::createModuleToPostOrderCGSCCPassAdaptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a6ca9e4f5478a77fa91fc56e1f1f6ba24">llvm::OptimizationLevel::O0</a> and <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">llvm::PGOOptions::SampleUse</a>.</p>

</div>
</div>

### buildFunctionSimplificationPipeline() {#a9501d22da3319c387a0a617fc4ffcc31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPassManager PassBuilder::buildFunctionSimplificationPipeline (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> Phase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct the core LLVM function canonicalization and simplification pipeline.</p>


<p>This is a long pipeline and uses most of the per-function optimization passes in LLVM to canonicalize and simplify the IR. It is suitable to run repeatedly over the IR and is not expected to destroy important information about the semantics of the IR.</p>


<p>Note that <span class="doxyComputerOutput">Level</span> cannot be <span class="doxyComputerOutput">O0</span> here. The pipelines produced are only intended for use when attempting to optimize code. If frontends require some transformations for semantic reasons, they should explicitly build them.</p>


<p><span class="doxyComputerOutput">Phase</span> indicates the current ThinLTO phase.</p>


<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/extralooppassmanager/#a1318d1386fce979589897f80c46f6102">llvm::ExtraLoopPassManager&lt; MarkerTy &gt;::addPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a846137dc22b3b399b62f606698f3ed59">llvm::AreStatisticsEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc70c26b79aeaaca89ad7e74474c3cca">llvm::createFunctionToLoopPassAdaptor</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#afd19b715cb1f5c8367c22f83d7e67074">EnableConstraintElimination</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a60609c67166415de63f7367a9b0f22c8">EnableDFAJumpThreading</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a53eae0026e1e39f98f02d1a9cb213abf">EnableGVNHoist</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a47a81cb8f842b4e3e1f78700ea2d151b">EnableGVNSink</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#ae9a5c9f225f123cd31f939d2cbc85aec">EnableJumpTableToSwitch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a003a8220a88ef0de2b308cae4791aac6">llvm::EnableKnowledgeRetention</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#aff2b9f098207a078c00b48f1b7d84c7c">EnableLoopFlatten</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a96ecb8d5f449a43f6e74d393bd07afd4">EnableLoopHeaderDuplication</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a6b47f3111c117e5ecf66de241383ace0">EnableLoopInterchange</a>, <a href="#ac2b1153446499aae16b90ea6bda946e4">invokeLateLoopOptimizationsEPCallbacks</a>, <a href="#aa30bda56b0554c3925dba6626fd9fff6">invokeLoopOptimizerEndEPCallbacks</a>, <a href="#a992749181a4f666d5192eda4300b70cc">invokePeepholeEPCallbacks</a>, <a href="#a2e0e9b1cc99f7bbf615c9a7513938a0c">invokeScalarOptimizerLateEPCallbacks</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a0c03d67d2ee41484066dade662f2fca5">llvm::PGOOptions::IRUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#acaebc8d799e882b2896fcee54e070388">isLTOPreLink</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af4e437674a39417056e3028415053139acaaa9d6e801d3edf358e569e31d9f59c">llvm::ModifyCFG</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a6ca9e4f5478a77fa91fc56e1f1f6ba24">llvm::OptimizationLevel::O0</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a097296a5feaefc188dafa71b19204714">llvm::OptimizationLevel::O3</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a1e916712888d6a2d3952834c126460e7">llvm::OptimizationLevel::Oz</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a174f40086d77810c7576da30090256c7">RunNewGVN</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">llvm::PGOOptions::SampleUse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49ad94cc56b0a9155d607f2609b0f5c39d3">llvm::ThinLTOPreLink</a>.</p>


<p>Referenced by <a href="#a08240a2eba496a292cec022c5093f621">buildInlinerPipeline</a> and <a href="#ab53586b47722fa95d93ae8b06f734742">buildModuleInlinerPipeline</a>.</p>

</div>
</div>

### buildInlinerPipeline() {#a08240a2eba496a292cec022c5093f621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleInlinerWrapperPass PassBuilder::buildInlinerPipeline (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> Phase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct the module pipeline that performs inlining as well as the inlining-driven cleanups.</p>

<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerwrapperpass/#a2b62feb6bba2102fd3de281a7bb39643">llvm::ModuleInlinerWrapperPass::addModulePass</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#aaaa594268ee5559702b52d2407d79e97">AttributorRun</a>, <a href="#a9501d22da3319c387a0a617fc4ffcc31">buildFunctionSimplificationPipeline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51e547c2283920aa77da2650a8ee3a7aaa705a97e17b5651633fcbb938bb1f79f">llvm::CGSCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a051cd0cc5f9d159ee0960b13051e5939a183b8bf4eb650f78f82c0aad756b6d96">llvm::CGSCCInliner</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a705c81498da25a438c1c2f8e802e6229">llvm::createCGSCCToFunctionPassAdaptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2386b882f14e23230b0065b7a3617f08">llvm::createModuleToFunctionPassAdaptor</a>, <a href="/web-llvm/docs/api/structs/llvm/inlineparams/#ab296684f357b92a4ab37fe27c4367358">llvm::InlineParams::EnableDeferral</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a07068e2ce7a7e26efcbd160d919131e0">EnableGlobalAnalyses</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#ae0a0ad2772eaf276be6d60566679ddc5">EnablePGOInlineDeferral</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba7063dea024346c7b70099c63703f50">llvm::getInlineParams</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a47144f1542bc8c796ab5f24db367b532">getInlineParamsFromOptLevel</a>, <a href="/web-llvm/docs/api/structs/llvm/inlineparams/#a75e7c36ed7f71d0c4afca48f835a098b">llvm::InlineParams::HotCallSiteThreshold</a>, <a href="#a24bbb807c0f1667d9dca483258747a59">invokeCGSCCOptimizerLateEPCallbacks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec6409a70645bde7c81ab78a13ddbf62">llvm::MaxDevirtIterations</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a6ca9e4f5478a77fa91fc56e1f1f6ba24">llvm::OptimizationLevel::O0</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a9c0836ff9219a0b737a11979991c3389">llvm::OptimizationLevel::O2</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a097296a5feaefc188dafa71b19204714">llvm::OptimizationLevel::O3</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a47fac5b18f0e4f22a34c200f1719b9f4">PerformMandatoryInliningsFirst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">llvm::PGOOptions::SampleUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49ad94cc56b0a9155d607f2609b0f5c39d3">llvm::ThinLTOPreLink</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#aecf596ddba11c5164c5952d85904091a">UseInlineAdvisor</a>.</p>


<p>Referenced by <a href="#ad6f258d31ffa2d2e4dfaf990ba596d0d">buildModuleSimplificationPipeline</a>.</p>

</div>
</div>

### buildLTODefaultPipeline() {#ab319565ffed9e4cb2aff1aa78847ec2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePassManager PassBuilder::buildLTODefaultPipeline (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ExportSummary)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build an LTO default optimization pipeline to a pass manager.</p>


<p>This provides a good default optimization pipeline for link-time optimization and code generation. It is particularly tuned to fit well when IR coming into the LTO phase was first run through <span class="doxyComputerOutput">buildLTOPreLinkDefaultPipeline</span>, and the two coordinate closely.</p>


<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1815 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a38315765eaec2665ca76556b908a593d">addAnnotationRemarksPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lowertypetests/#a28baf2df0f23eab12b60755416e83adaa4822c96fc1eebe031cde975d10a29e12">llvm::lowertypetests::Assume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a051cd0cc5f9d159ee0960b13051e5939a183b8bf4eb650f78f82c0aad756b6d96">llvm::CGSCCInliner</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a705c81498da25a438c1c2f8e802e6229">llvm::createCGSCCToFunctionPassAdaptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc70c26b79aeaaca89ad7e74474c3cca">llvm::createFunctionToLoopPassAdaptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2386b882f14e23230b0065b7a3617f08">llvm::createModuleToFunctionPassAdaptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6383dc1a150ac7cd92979a80681a71af">llvm::createModuleToPostOrderCGSCCPassAdaptor</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#acf3f319824303e495d7326e35538b250ad626f6abde9ca8fb0a8e97125114f11c">llvm::PGOOptions::CSIRInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#acf3f319824303e495d7326e35538b250a0003b9f9d3be4b2a2bef9c7ceec1d77b">llvm::PGOOptions::CSIRUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#afd19b715cb1f5c8367c22f83d7e67074">EnableConstraintElimination</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a07068e2ce7a7e26efcbd160d919131e0">EnableGlobalAnalyses</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a677d33a7278b4e353580d0d3d1f753f5">EnableHotColdSplit</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#aff2b9f098207a078c00b48f1b7d84c7c">EnableLoopFlatten</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa7e093749a47a0dd581e5b2bb37e53fa">llvm::EnableMemProfContextDisambiguation</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#aa556c7cc4c95543e35c32420d9054a06">EnableModuleInliner</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a7757dfb07e9ac64f8c7076644e2deac1">llvm::FullLTOPostLink</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a47144f1542bc8c796ab5f24db367b532">getInlineParamsFromOptLevel</a>, <a href="#ad3a19c4dfd315d77ffb14a769cf583af">invokeFullLinkTimeOptimizationEarlyEPCallbacks</a>, <a href="#a079790ccc6b6d4fd34df68c5c500a46f">invokeFullLinkTimeOptimizationLastEPCallbacks</a>, <a href="#a992749181a4f666d5192eda4300b70cc">invokePeepholeEPCallbacks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af4e437674a39417056e3028415053139acaaa9d6e801d3edf358e569e31d9f59c">llvm::ModifyCFG</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a6ca9e4f5478a77fa91fc56e1f1f6ba24">llvm::OptimizationLevel::O0</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#acfab17afad8d19eb90de02e684900ccd">llvm::OptimizationLevel::O1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4981871ea1a597d1b8aa1a8ac9326e76a8346db516e5f3aa534827e7d6c166744">llvm::Optimize</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a73679792a87ec44543a1cc09a5d8c3cc">llvm::OptimizationLevel::Os</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a1e916712888d6a2d3952834c126460e7">llvm::OptimizationLevel::Oz</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a174f40086d77810c7576da30090256c7">RunNewGVN</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">llvm::PGOOptions::SampleUse</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#aecf596ddba11c5164c5952d85904091a">UseInlineAdvisor</a>.</p>

</div>
</div>

### buildLTOPreLinkDefaultPipeline() {#af7de51d7cbb98b83f2c01faf23b72472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePassManager PassBuilder::buildLTOPreLinkDefaultPipeline (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a pre-link, LTO-targeting default optimization pipeline to a pass manager.</p>


<p>This adds the pre-link optimizations tuned to work well with a later LTO run. It works to minimize the IR which needs to be analyzed without making irreversible decisions which could be made better during the LTO run.</p>


<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1808 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="#a546f4259efb4e1629d1d14b8757c52c4">buildPerModuleDefaultPipeline</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a123c9da36c4ea6b13da1c4dd2e955c3b">llvm::FullLTOPreLink</a>.</p>


<p>Referenced by <a href="#ad4548cd9e4b6358214f2e34e5e56112e">buildFatLTODefaultPipeline</a>.</p>

</div>
</div>

### buildModuleInlinerPipeline() {#ab53586b47722fa95d93ae8b06f734742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePassManager PassBuilder::buildModuleInlinerPipeline (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> Phase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct the module pipeline that performs inlining with module inliner pass.</p>

<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="#a9501d22da3319c387a0a617fc4ffcc31">buildFunctionSimplificationPipeline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2386b882f14e23230b0065b7a3617f08">llvm::createModuleToFunctionPassAdaptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6383dc1a150ac7cd92979a80681a71af">llvm::createModuleToPostOrderCGSCCPassAdaptor</a>, <a href="/web-llvm/docs/api/structs/llvm/inlineparams/#ab296684f357b92a4ab37fe27c4367358">llvm::InlineParams::EnableDeferral</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#ae0a0ad2772eaf276be6d60566679ddc5">EnablePGOInlineDeferral</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a47144f1542bc8c796ab5f24db367b532">getInlineParamsFromOptLevel</a>, <a href="/web-llvm/docs/api/structs/llvm/inlineparams/#a75e7c36ed7f71d0c4afca48f835a098b">llvm::InlineParams::HotCallSiteThreshold</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a6ca9e4f5478a77fa91fc56e1f1f6ba24">llvm::OptimizationLevel::O0</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">llvm::PGOOptions::SampleUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a5c0973ae3fdda34daff394f30f81f19b">llvm::ThinLTOPostLink</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49ad94cc56b0a9155d607f2609b0f5c39d3">llvm::ThinLTOPreLink</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp/#ae2b2c87a52448d91bf5be603cc14acc5">UseCtxProfile</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#aecf596ddba11c5164c5952d85904091a">UseInlineAdvisor</a>.</p>


<p>Referenced by <a href="#ad6f258d31ffa2d2e4dfaf990ba596d0d">buildModuleSimplificationPipeline</a> and <a href="#ab7d260f2f928c81a2d225f2d1aafad0e">buildThinLTODefaultPipeline</a>.</p>

</div>
</div>

### buildModuleOptimizationPipeline() {#adf20f88f2a71fd5cd08708b9da72979a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePassManager PassBuilder::buildModuleOptimizationPipeline (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> LTOPhase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct the core LLVM module optimization pipeline.</p>


<p>This pipeline focuses on optimizing the execution speed of the IR. It uses cost modeling and thresholds to balance code growth against runtime improvements. It includes vectorization and other information destroying transformations. It also cannot generally be run repeatedly on a module without potentially seriously regressing either runtime performance of the code or serious code size growth.</p>


<p>Note that <span class="doxyComputerOutput">Level</span> cannot be <span class="doxyComputerOutput">O0</span> here. The pipelines produced are only intended for use when attempting to optimize code. If frontends require some transformations for semantic reasons, they should explicitly build them.</p>


<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1414 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc70c26b79aeaaca89ad7e74474c3cca">llvm::createFunctionToLoopPassAdaptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2386b882f14e23230b0065b7a3617f08">llvm::createModuleToFunctionPassAdaptor</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#acf3f319824303e495d7326e35538b250ad626f6abde9ca8fb0a8e97125114f11c">llvm::PGOOptions::CSIRInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#acf3f319824303e495d7326e35538b250a0003b9f9d3be4b2a2bef9c7ceec1d77b">llvm::PGOOptions::CSIRUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a62062994dbc7f2620661b2754f56e77f">EnableCHR</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a07068e2ce7a7e26efcbd160d919131e0">EnableGlobalAnalyses</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a677d33a7278b4e353580d0d3d1f753f5">EnableHotColdSplit</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a147973e09ae9cccd4c6535ac4715e57b">EnableIROutliner</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a96ecb8d5f449a43f6e74d393bd07afd4">EnableLoopHeaderDuplication</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#aa8deaf695ec0d3236d60155a49886675">EnableMatrix</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#ab014a9dea3bd22a84ce6f9013e29c9a5">EnableOrderFileInstrumentation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a7757dfb07e9ac64f8c7076644e2deac1">llvm::FullLTOPostLink</a>, <a href="#a17a17ea5b5ceb7624eec6f9dd79f36a4">invokeOptimizerEarlyEPCallbacks</a>, <a href="#af2f3b63161e415605292b1cc40b08ac1">invokeOptimizerLastEPCallbacks</a>, <a href="#a1bd4ee77dc2e2e93591e982a816ffe44">invokeVectorizerStartEPCallbacks</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#acaebc8d799e882b2896fcee54e070388">isLTOPreLink</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a097296a5feaefc188dafa71b19204714">llvm::OptimizationLevel::O3</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a1e916712888d6a2d3952834c126460e7">llvm::OptimizationLevel::Oz</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a556f58c089a2d5bf23d908286807155d">RunPartialInlining</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a5c0973ae3fdda34daff394f30f81f19b">llvm::ThinLTOPostLink</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#abb43570bd79eef6f5949838628de6dc6">UseLoopVersioningLICM</a>.</p>


<p>Referenced by <a href="#ad4548cd9e4b6358214f2e34e5e56112e">buildFatLTODefaultPipeline</a>, <a href="#a546f4259efb4e1629d1d14b8757c52c4">buildPerModuleDefaultPipeline</a> and <a href="#ab7d260f2f928c81a2d225f2d1aafad0e">buildThinLTODefaultPipeline</a>.</p>

</div>
</div>

### buildModuleSimplificationPipeline() {#ad6f258d31ffa2d2e4dfaf990ba596d0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePassManager PassBuilder::buildModuleSimplificationPipeline (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> Phase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct the core LLVM module canonicalization and simplification pipeline.</p>


<p>This pipeline focuses on canonicalizing and simplifying the entire module of IR. Much like the function simplification pipeline above, it is suitable to run repeatedly over the IR and is not expected to destroy important information. It does, however, perform inlining and other heuristic based simplifications that are not strictly reversible.</p>


<p>Note that <span class="doxyComputerOutput">Level</span> cannot be <span class="doxyComputerOutput">O0</span> here. The pipelines produced are only intended for use when attempting to optimize code. If frontends require some transformations for semantic reasons, they should explicitly build them.</p>


<p><span class="doxyComputerOutput">Phase</span> indicates the current ThinLTO phase.</p>


<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1048 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lowertypetests/#a28baf2df0f23eab12b60755416e83adaa4822c96fc1eebe031cde975d10a29e12">llvm::lowertypetests::Assume</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#aaaa594268ee5559702b52d2407d79e97">AttributorRun</a>, <a href="#a08240a2eba496a292cec022c5093f621">buildInlinerPipeline</a>, <a href="#ab53586b47722fa95d93ae8b06f734742">buildModuleInlinerPipeline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2386b882f14e23230b0065b7a3617f08">llvm::createModuleToFunctionPassAdaptor</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#acf3f319824303e495d7326e35538b250ad626f6abde9ca8fb0a8e97125114f11c">llvm::PGOOptions::CSIRInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a405905ea235b6f5793566aa1411d2b85a5f4727eb0c55bc39f1f9a91a3f802d0c">llvm::CTXPROF</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#aa556c7cc4c95543e35c32420d9054a06">EnableModuleInliner</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a7e8e8fe3e8dec1b07d818835eb176097">EnableSampledInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a91498eeffa9ef283e2b3f09ce5aecdad">FlattenedProfileUsed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a7757dfb07e9ac64f8c7076644e2deac1">llvm::FullLTOPostLink</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a9f330a9fae040126d941e0a823328fb0">InstrumentColdFuncOnlyPath</a>, <a href="#a992749181a4f666d5192eda4300b70cc">invokePeepholeEPCallbacks</a>, <a href="#a9a94759ace31aca9af485567995189ba">invokePipelineEarlySimplificationEPCallbacks</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a0ee4f7584b41e663a274753a6e9a9c34">llvm::PGOOptions::IRInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a0c03d67d2ee41484066dade662f2fca5">llvm::PGOOptions::IRUse</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofloweringpass/#af8baa6687d12e279c27946d31e6ba9cf">llvm::PGOCtxProfLoweringPass::isCtxIRPGOInstrEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#acaebc8d799e882b2896fcee54e070388">isLTOPreLink</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af4e437674a39417056e3028415053139acaaa9d6e801d3edf358e569e31d9f59c">llvm::ModifyCFG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51e547c2283920aa77da2650a8ee3a7aa6b7748115db77a5a98a54363b6c74203">llvm::MODULE</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a6ca9e4f5478a77fa91fc56e1f1f6ba24">llvm::OptimizationLevel::O0</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a097296a5feaefc188dafa71b19204714">llvm::OptimizationLevel::O3</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a73679792a87ec44543a1cc09a5d8c3cc">llvm::OptimizationLevel::Os</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a1e916712888d6a2d3952834c126460e7">llvm::OptimizationLevel::Oz</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#aa0425acc737a4cb44fe7563204bf72f1">PGOInstrumentColdFunctionOnly</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">llvm::PGOOptions::SampleUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a5c0973ae3fdda34daff394f30f81f19b">llvm::ThinLTOPostLink</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49ad94cc56b0a9155d607f2609b0f5c39d3">llvm::ThinLTOPreLink</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp/#ae2b2c87a52448d91bf5be603cc14acc5">UseCtxProfile</a>.</p>


<p>Referenced by <a href="#a546f4259efb4e1629d1d14b8757c52c4">buildPerModuleDefaultPipeline</a>, <a href="#ab7d260f2f928c81a2d225f2d1aafad0e">buildThinLTODefaultPipeline</a> and <a href="#a2832cb00a6c94208b4a06696eeeabf99">buildThinLTOPreLinkDefaultPipeline</a>.</p>

</div>
</div>

### buildO0DefaultPipeline() {#a94e03b8856e739853a1419da126f1758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePassManager PassBuilder::buildO0DefaultPipeline (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> Phase=<a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a6adf97f83acf6453d4a6a4b1070f3754">ThinOrFullLTOPhase::None</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build an O0 pipeline with the minimal semantically required passes.</p>


<p>This should only be used for non-LTO and LTO pre-link pipelines.</p>


<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2149 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="#aeee6e6170878c432ee2b1faffc755b4c">addPGOInstrPassesForO0</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc70c26b79aeaaca89ad7e74474c3cca">llvm::createFunctionToLoopPassAdaptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2386b882f14e23230b0065b7a3617f08">llvm::createModuleToFunctionPassAdaptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6383dc1a150ac7cd92979a80681a71af">llvm::createModuleToPostOrderCGSCCPassAdaptor</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#aa8deaf695ec0d3236d60155a49886675">EnableMatrix</a>, <a href="#a24bbb807c0f1667d9dca483258747a59">invokeCGSCCOptimizerLateEPCallbacks</a>, <a href="#ac2b1153446499aae16b90ea6bda946e4">invokeLateLoopOptimizationsEPCallbacks</a>, <a href="#aa30bda56b0554c3925dba6626fd9fff6">invokeLoopOptimizerEndEPCallbacks</a>, <a href="#a17a17ea5b5ceb7624eec6f9dd79f36a4">invokeOptimizerEarlyEPCallbacks</a>, <a href="#af2f3b63161e415605292b1cc40b08ac1">invokeOptimizerLastEPCallbacks</a>, <a href="#a9a94759ace31aca9af485567995189ba">invokePipelineEarlySimplificationEPCallbacks</a>, <a href="#a7be5d1c757e25b6be1bd5634f159ceab">invokePipelineStartEPCallbacks</a>, <a href="#a2e0e9b1cc99f7bbf615c9a7513938a0c">invokeScalarOptimizerLateEPCallbacks</a>, <a href="#a1bd4ee77dc2e2e93591e982a816ffe44">invokeVectorizerStartEPCallbacks</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a0ee4f7584b41e663a274753a6e9a9c34">llvm::PGOOptions::IRInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a0c03d67d2ee41484066dade662f2fca5">llvm::PGOOptions::IRUse</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#afdd422a60efda415b943a1c35dcd7de2">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::isEmpty</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#acaebc8d799e882b2896fcee54e070388">isLTOPreLink</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a6ca9e4f5478a77fa91fc56e1f1f6ba24">llvm::OptimizationLevel::O0</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a> and <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">llvm::PGOOptions::SampleUse</a>.</p>


<p>Referenced by <a href="#a546f4259efb4e1629d1d14b8757c52c4">buildPerModuleDefaultPipeline</a> and <a href="#a2832cb00a6c94208b4a06696eeeabf99">buildThinLTOPreLinkDefaultPipeline</a>.</p>

</div>
</div>

### buildPerModuleDefaultPipeline() {#a546f4259efb4e1629d1d14b8757c52c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePassManager PassBuilder::buildPerModuleDefaultPipeline (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> Phase=<a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a6adf97f83acf6453d4a6a4b1070f3754">ThinOrFullLTOPhase::None</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a per-module default optimization pipeline.</p>


<p>This provides a good default optimization pipeline for per-module optimization and code generation without any link-time optimization. It typically correspond to frontend "-O[123]" options for optimization levels <span class="doxyComputerOutput">O1</span>, <span class="doxyComputerOutput">O2</span> and <span class="doxyComputerOutput">O3</span> resp.</p>


<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1605 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a38315765eaec2665ca76556b908a593d">addAnnotationRemarksPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="#adf20f88f2a71fd5cd08708b9da72979a">buildModuleOptimizationPipeline</a>, <a href="#ad6f258d31ffa2d2e4dfaf990ba596d0d">buildModuleSimplificationPipeline</a>, <a href="#a94e03b8856e739853a1419da126f1758">buildO0DefaultPipeline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2386b882f14e23230b0065b7a3617f08">llvm::createModuleToFunctionPassAdaptor</a>, <a href="#a7be5d1c757e25b6be1bd5634f159ceab">invokePipelineStartEPCallbacks</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#acaebc8d799e882b2896fcee54e070388">isLTOPreLink</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a6ca9e4f5478a77fa91fc56e1f1f6ba24">llvm::OptimizationLevel::O0</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a> and <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">llvm::PGOOptions::SampleUse</a>.</p>


<p>Referenced by <a href="#af7de51d7cbb98b83f2c01faf23b72472">buildLTOPreLinkDefaultPipeline</a>.</p>

</div>
</div>

### buildThinLTODefaultPipeline() {#ab7d260f2f928c81a2d225f2d1aafad0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePassManager PassBuilder::buildThinLTODefaultPipeline (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ImportSummary)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a ThinLTO default optimization pipeline to a pass manager.</p>


<p>This provides a good default optimization pipeline for link-time optimization and code generation. It is particularly tuned to fit well when IR coming into the LTO phase was first run through <span class="doxyComputerOutput">buildThinLTOPreLinkDefaultPipeline</span>, and the two coordinate closely.</p>


<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1747 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a38315765eaec2665ca76556b908a593d">addAnnotationRemarksPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lowertypetests/#a28baf2df0f23eab12b60755416e83adaa4822c96fc1eebe031cde975d10a29e12">llvm::lowertypetests::Assume</a>, <a href="#ab53586b47722fa95d93ae8b06f734742">buildModuleInlinerPipeline</a>, <a href="#adf20f88f2a71fd5cd08708b9da72979a">buildModuleOptimizationPipeline</a>, <a href="#ad6f258d31ffa2d2e4dfaf990ba596d0d">buildModuleSimplificationPipeline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa7e093749a47a0dd581e5b2bb37e53fa">llvm::EnableMemProfContextDisambiguation</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a6ca9e4f5478a77fa91fc56e1f1f6ba24">llvm::OptimizationLevel::O0</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">llvm::PGOOptions::SampleUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a5c0973ae3fdda34daff394f30f81f19b">llvm::ThinLTOPostLink</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp/#ae2b2c87a52448d91bf5be603cc14acc5">UseCtxProfile</a>.</p>


<p>Referenced by <a href="#ad4548cd9e4b6358214f2e34e5e56112e">buildFatLTODefaultPipeline</a>.</p>

</div>
</div>

### buildThinLTOPreLinkDefaultPipeline() {#a2832cb00a6c94208b4a06696eeeabf99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePassManager PassBuilder::buildThinLTOPreLinkDefaultPipeline (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a pre-link, ThinLTO-targeting default optimization pipeline to a pass manager.</p>


<p>This adds the pre-link optimizations tuned to prepare a module for a ThinLTO run. It works to minimize the IR which needs to be analyzed without making irreversible decisions which could be made better during the LTO run.</p>


<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1686 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a38315765eaec2665ca76556b908a593d">addAnnotationRemarksPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="#ad6f258d31ffa2d2e4dfaf990ba596d0d">buildModuleSimplificationPipeline</a>, <a href="#a94e03b8856e739853a1419da126f1758">buildO0DefaultPipeline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2386b882f14e23230b0065b7a3617f08">llvm::createModuleToFunctionPassAdaptor</a>, <a href="#a17a17ea5b5ceb7624eec6f9dd79f36a4">invokeOptimizerEarlyEPCallbacks</a>, <a href="#af2f3b63161e415605292b1cc40b08ac1">invokeOptimizerLastEPCallbacks</a>, <a href="#a7be5d1c757e25b6be1bd5634f159ceab">invokePipelineStartEPCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a6ca9e4f5478a77fa91fc56e1f1f6ba24">llvm::OptimizationLevel::O0</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a556f58c089a2d5bf23d908286807155d">RunPartialInlining</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">llvm::PGOOptions::SampleUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49ad94cc56b0a9155d607f2609b0f5c39d3">llvm::ThinLTOPreLink</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp/#ae2b2c87a52448d91bf5be603cc14acc5">UseCtxProfile</a>.</p>


<p>Referenced by <a href="#ad4548cd9e4b6358214f2e34e5e56112e">buildFatLTODefaultPipeline</a>.</p>

</div>
</div>

### crossRegisterProxies() {#a3c2e12459e81e47a53dc49484af24bc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::crossRegisterProxies (<a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a> &amp; LAM, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM, <a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> &amp; CGAM, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; MAM, <a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a> * MFAM=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cross register the analysis managers through their proxies.</p>


<p>This is an interface that can be used to cross register each <a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager</a> with all the others analysis managers.</p>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2211 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a13293a681188ed79fb799b7f9c173b83">CGAM</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a7cfe61417446ebb812e81293bde22a29">LAM</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a> and <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#a91ff894f756175a693c85bf73f79de9e">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::registerPass</a>.</p>

</div>
</div>

### getPassInstrumentationCallbacks() {#a38e1471d80ab41f6c9748a5d10b91303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassInstrumentationCallbacks * llvm::PassBuilder::getPassInstrumentationCallbacks ()</td>
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

<p>Returns PIC.</p>


<p>External libraries can use this to register pass instrumentation callbacks.</p>


<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### invokeCGSCCOptimizerLateEPCallbacks() {#a24bbb807c0f1667d9dca483258747a59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::invokeCGSCCOptimizerLateEPCallbacks (<a href="/web-llvm/docs/api/namespaces/llvm/#a4ded4558d2b58dcdd7a1736aa69a8bc4">CGSCCPassManager</a> &amp; CGPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a08240a2eba496a292cec022c5093f621">buildInlinerPipeline</a> and <a href="#a94e03b8856e739853a1419da126f1758">buildO0DefaultPipeline</a>.</p>

</div>
</div>

### invokeFullLinkTimeOptimizationEarlyEPCallbacks() {#ad3a19c4dfd315d77ffb14a769cf583af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::invokeFullLinkTimeOptimizationEarlyEPCallbacks (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#ab319565ffed9e4cb2aff1aa78847ec2d">buildLTODefaultPipeline</a>.</p>

</div>
</div>

### invokeFullLinkTimeOptimizationLastEPCallbacks() {#a079790ccc6b6d4fd34df68c5c500a46f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::invokeFullLinkTimeOptimizationLastEPCallbacks (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#ab319565ffed9e4cb2aff1aa78847ec2d">buildLTODefaultPipeline</a>.</p>

</div>
</div>

### invokeLateLoopOptimizationsEPCallbacks() {#ac2b1153446499aae16b90ea6bda946e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::invokeLateLoopOptimizationsEPCallbacks (<a href="/web-llvm/docs/api/namespaces/llvm/#a613892f4c1a570fd3747f2b6b1bf9b75">LoopPassManager</a> &amp; LPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a9501d22da3319c387a0a617fc4ffcc31">buildFunctionSimplificationPipeline</a> and <a href="#a94e03b8856e739853a1419da126f1758">buildO0DefaultPipeline</a>.</p>

</div>
</div>

### invokeLoopOptimizerEndEPCallbacks() {#aa30bda56b0554c3925dba6626fd9fff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::invokeLoopOptimizerEndEPCallbacks (<a href="/web-llvm/docs/api/namespaces/llvm/#a613892f4c1a570fd3747f2b6b1bf9b75">LoopPassManager</a> &amp; LPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a9501d22da3319c387a0a617fc4ffcc31">buildFunctionSimplificationPipeline</a> and <a href="#a94e03b8856e739853a1419da126f1758">buildO0DefaultPipeline</a>.</p>

</div>
</div>

### invokeOptimizerEarlyEPCallbacks() {#a17a17ea5b5ceb7624eec6f9dd79f36a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::invokeOptimizerEarlyEPCallbacks (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> Phase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>.</p>


<p>Referenced by <a href="#adf20f88f2a71fd5cd08708b9da72979a">buildModuleOptimizationPipeline</a>, <a href="#a94e03b8856e739853a1419da126f1758">buildO0DefaultPipeline</a> and <a href="#a2832cb00a6c94208b4a06696eeeabf99">buildThinLTOPreLinkDefaultPipeline</a>.</p>

</div>
</div>

### invokeOptimizerLastEPCallbacks() {#af2f3b63161e415605292b1cc40b08ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::invokeOptimizerLastEPCallbacks (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> Phase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>.</p>


<p>Referenced by <a href="#adf20f88f2a71fd5cd08708b9da72979a">buildModuleOptimizationPipeline</a>, <a href="#a94e03b8856e739853a1419da126f1758">buildO0DefaultPipeline</a> and <a href="#a2832cb00a6c94208b4a06696eeeabf99">buildThinLTOPreLinkDefaultPipeline</a>.</p>

</div>
</div>

### invokePeepholeEPCallbacks() {#a992749181a4f666d5192eda4300b70cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::invokePeepholeEPCallbacks (<a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp; FPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a9501d22da3319c387a0a617fc4ffcc31">buildFunctionSimplificationPipeline</a>, <a href="#ab319565ffed9e4cb2aff1aa78847ec2d">buildLTODefaultPipeline</a> and <a href="#ad6f258d31ffa2d2e4dfaf990ba596d0d">buildModuleSimplificationPipeline</a>.</p>

</div>
</div>

### invokePipelineEarlySimplificationEPCallbacks() {#a9a94759ace31aca9af485567995189ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::invokePipelineEarlySimplificationEPCallbacks (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> Phase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>.</p>


<p>Referenced by <a href="#ad6f258d31ffa2d2e4dfaf990ba596d0d">buildModuleSimplificationPipeline</a> and <a href="#a94e03b8856e739853a1419da126f1758">buildO0DefaultPipeline</a>.</p>

</div>
</div>

### invokePipelineStartEPCallbacks() {#a7be5d1c757e25b6be1bd5634f159ceab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::invokePipelineStartEPCallbacks (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a94e03b8856e739853a1419da126f1758">buildO0DefaultPipeline</a>, <a href="#a546f4259efb4e1629d1d14b8757c52c4">buildPerModuleDefaultPipeline</a> and <a href="#a2832cb00a6c94208b4a06696eeeabf99">buildThinLTOPreLinkDefaultPipeline</a>.</p>

</div>
</div>

### invokeScalarOptimizerLateEPCallbacks() {#a2e0e9b1cc99f7bbf615c9a7513938a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::invokeScalarOptimizerLateEPCallbacks (<a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp; FPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a9501d22da3319c387a0a617fc4ffcc31">buildFunctionSimplificationPipeline</a> and <a href="#a94e03b8856e739853a1419da126f1758">buildO0DefaultPipeline</a>.</p>

</div>
</div>

### invokeVectorizerStartEPCallbacks() {#a1bd4ee77dc2e2e93591e982a816ffe44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::invokeVectorizerStartEPCallbacks (<a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp; FPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#adf20f88f2a71fd5cd08708b9da72979a">buildModuleOptimizationPipeline</a> and <a href="#a94e03b8856e739853a1419da126f1758">buildO0DefaultPipeline</a>.</p>

</div>
</div>

### parseAAPipeline() {#a1d4e2a477b2b896adfdec5e55638b725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parseAAPipeline (<a href="/web-llvm/docs/api/classes/llvm/aamanager">AAManager</a> &amp; AA, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PipelineText)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a textual alias analysis pipeline into the provided <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> manager.</p>


<p>The format of the textual <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> pipeline is a comma separated list of <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> pass names:</p>


<p>basic-aa,globals-aa,...</p>


<p>The <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> manager is set up such that the provided alias analyses are tried in the order specified. See the <span class="doxyComputerOutput">AAManaager</span> documentation for details about the logic used. This routine just provides the textual mapping between <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> names and the analyses to register with the manager.</p>


<p>Returns false if the text cannot be parsed cleanly. The specific state of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span> manager is unspecified if such an error is encountered and this returns false.</p>


<p>Declaration at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2371 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="#a1d045f9463f65181b84ac5dc7eafafe8">buildDefaultAAPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### parsePassPipeline() {#a9ca0e57e6445ab2fe568e53ba29cc0fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parsePassPipeline (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PipelineText)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a textual pass pipeline description into a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></span>.</p>


<p>The format of the textual pass pipeline description looks something like:</p>


<p>module(function(instcombine,sroa),dce,cgscc(inliner,function(...)),...)</p>


<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> managers have ()s describing the nest structure of passes. All passes are comma separated. As a special shortcut, if the very first pass is not a module pass (as a module pass manager is), this will automatically form the shortest stack of pass managers that allow inserting that first pass. So, assuming function passes 'fpassN', CGSCC passes 'cgpassN', and loop passes 'lpassN', all of these are valid:</p>


<p>fpass1,fpass2,fpass3 cgpass1,cgpass2,cgpass3 lpass1,lpass2,lpass3</p>


<p>And they are equivalent to the following (resp.):</p>


<p>module(function(fpass1,fpass2,fpass3)) module(cgscc(cgpass1,cgpass2,cgpass3)) module(function(loop(lpass1,lpass2,lpass3)))</p>


<p>This shortcut is especially useful for debugging and testing small pass combinations.</p>


<p>The sequence of passes aren't necessarily the exact same kind of pass. You can mix different levels implicitly if adaptor passes are defined to make them work. For example,</p>


<p>mpass1,fpass1,fpass2,mpass2,lpass1</p>


<p>This pipeline uses only one pass manager: the top-level module manager. fpass1,fpass2 and lpass1 are added into the top-level module manager using only adaptor passes. No nested function/loop pass managers are added. The purpose is to allow easy pass testing when the user specifically want the pass to run under a adaptor directly. This is preferred when a pipeline is largely of one type, but one or just a few passes are of different types(See <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a> for examples).</p>


<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2247 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#aac53000397de89cf36fbf956d1e18a44">isCGSCCPassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#ac5234ac115ac4f2c23622b4eede40d78">isFunctionPassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#a8130b07a44ca5c11ae1aac80d5129a7a">isLoopNestPassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#aa54f2a3ed5acad7fd2b7b55141319525">isLoopPassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#a83144269c5f447f53e524b0b5633c80a">isMachineFunctionPassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#a26572aa6efaea4ae6ce610c3b93f0210">isModulePassName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### parsePassPipeline() {#a581197bc2dbbef326892f5ff08761f54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parsePassPipeline (<a href="/web-llvm/docs/api/namespaces/llvm/#a4ded4558d2b58dcdd7a1736aa69a8bc4">CGSCCPassManager</a> &amp; CGPM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PipelineText)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>{{@ Parse a textual pass pipeline description into a specific <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a></p>


<p>Automatic deduction of an appropriate pass manager stack is not supported. For example, to insert a loop pass 'lpass' into a <a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a>, this is the valid pipeline text:</p>


<p>function(lpass)</p>


<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2298 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#aac53000397de89cf36fbf956d1e18a44">isCGSCCPassName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### parsePassPipeline() {#ac3231081094bc7fdda779c6b73f9f706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parsePassPipeline (<a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp; FPM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PipelineText)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2321 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#ac5234ac115ac4f2c23622b4eede40d78">isFunctionPassName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### parsePassPipeline() {#a2c60ec47f90dce41d2bbc71a913c696e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parsePassPipeline (<a href="/web-llvm/docs/api/namespaces/llvm/#a613892f4c1a570fd3747f2b6b1bf9b75">LoopPassManager</a> &amp; LPM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PipelineText)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2343 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### parsePassPipeline() {#a088814462db14cd89651bd90f390e30d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parsePassPipeline (<a href="/web-llvm/docs/api/namespaces/llvm/#ac4d6ff2181c8f2a8d4dabd70e55f2ba2">MachineFunctionPassManager</a> &amp; MFPM, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PipelineText)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a textual MIR pipeline into the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></span> manager.</p>


<p>The format of the textual machine pipeline is a comma separated list of machine pass names:</p>


<p>machine-funciton-pass,machine-module-pass,...</p>


<p>There is no need to specify the pass nesting, and this function currently cannot handle the pass nesting.</p>


<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2357 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### parseRegAllocFilter() {#a35f205775871eede46d8dc00413cbf3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; RegAllocFilterFunc &gt; PassBuilder::parseRegAllocFilter (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RegAllocFilterName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse RegAllocFilterName to get <a href="/web-llvm/docs/api/namespaces/llvm/#a0ab9dba764b528b15e89f9c443b2e202">RegAllocFilterFunc</a>.</p>

<p>Declaration at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2392 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### printPassNames() {#a0bcf38a395ef95aeb79b647a85a427ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::printPassNames (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print pass names.</p>

<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2409 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### registerAnalysisRegistrationCallback() {#a78c148ed6b206155773e9262a71c61f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerAnalysisRegistrationCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> &amp;)&gt; &amp; C)</td>
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

<p>{{@ <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> callbacks for analysis registration with this <a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a> instance.</p>


<p>Callees register their analyses with the given <a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager</a> objects.</p>


<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerAnalysisRegistrationCallback() {#a6f2c24753d0095be3183dcf27e7ed10a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerAnalysisRegistrationCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp;)&gt; &amp; C)</td>
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



<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerAnalysisRegistrationCallback() {#a5119b687767244844ee692505b41e4a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerAnalysisRegistrationCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a> &amp;)&gt; &amp; C)</td>
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



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerAnalysisRegistrationCallback() {#a285d4112f73fb910b3d8d79dd4886471}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerAnalysisRegistrationCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp;)&gt; &amp; C)</td>
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



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerAnalysisRegistrationCallback() {#a0a18fef11307bda3a292ec8c74470d48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerAnalysisRegistrationCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a> &amp;)&gt; &amp; C)</td>
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



<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerCGSCCAnalyses() {#ad2d3999ee96b77c4c40f4d747609f205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::registerCGSCCAnalyses (<a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> &amp; CGAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Registers all available CGSCC analysis passes.</p>


<p>This is an interface that can be used to populate a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a></span> with all registered CGSCC analyses. Callers can still manually register any additional analyses. Callers can also pre-register analyses and this will not override those.</p>


<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a13293a681188ed79fb799b7f9c173b83">CGAM</a>.</p>

</div>
</div>

### registerCGSCCOptimizerLateEPCallback() {#a983eb9382d100af683d80513869f36c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerCGSCCOptimizerLateEPCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a4ded4558d2b58dcdd7a1736aa69a8bc4">CGSCCPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point.</p>


<p>This extension point allows adding <a href="/web-llvm/docs/api/classes/llvm/callgraphscc">CallGraphSCC</a> passes at the end of the main <a href="/web-llvm/docs/api/classes/llvm/callgraphscc">CallGraphSCC</a> passes and before any function simplification passes run by CGPassManager.</p>


<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerFullLinkTimeOptimizationEarlyEPCallback() {#abca5690a1a0abc98824d0f15ce3f4a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerFullLinkTimeOptimizationEarlyEPCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point.</p>


<p>This extension point allows adding optimizations at the start of the full LTO pipeline.</p>


<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerFullLinkTimeOptimizationLastEPCallback() {#ad2d03850eda381e9418b90eca468dda7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerFullLinkTimeOptimizationLastEPCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point.</p>


<p>This extension point allows adding optimizations at the end of the full LTO pipeline.</p>


<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerFunctionAnalyses() {#af9903a32cb913723bc7608f6544995d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::registerFunctionAnalyses (<a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Registers all available function analysis passes.</p>


<p>This is an interface that can be used to populate a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a></span> with all registered function analyses. Callers can still manually register any additional analyses. Callers can also pre-register analyses and this will not override those.</p>


<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="#a1d045f9463f65181b84ac5dc7eafafe8">buildDefaultAAPipeline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>.</p>

</div>
</div>

### registerLateLoopOptimizationsEPCallback() {#a3a37b41d4336528168634988528da584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerLateLoopOptimizationsEPCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a613892f4c1a570fd3747f2b6b1bf9b75">LoopPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point.</p>


<p>This extension point allows adding late loop canonicalization and simplification passes. This is the last point in the loop optimization pipeline before loop deletion. Each pass added here must be an instance of <a href="/web-llvm/docs/api/classes/llvm/looppass">LoopPass</a>. This is the place to add passes that can remove loops, such as target- specific loop idiom recognition.</p>


<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerLoopAnalyses() {#a32a8612a117894df2f1f35c72dce226e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::registerLoopAnalyses (<a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a> &amp; LAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Registers all available loop analysis passes.</p>


<p>This is an interface that can be used to populate a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a></span> with all registered loop analyses. Callers can still manually register any additional analyses.</p>


<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a7cfe61417446ebb812e81293bde22a29">LAM</a>.</p>

</div>
</div>

### registerLoopOptimizerEndEPCallback() {#a41a2daec8ce577e45502b430f5e190d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerLoopOptimizerEndEPCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a613892f4c1a570fd3747f2b6b1bf9b75">LoopPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point.</p>


<p>This extension point allows adding loop passes to the end of the loop optimizer.</p>


<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerMachineFunctionAnalyses() {#add26afb1d231a436e197b8e73ae72079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::registerMachineFunctionAnalyses (<a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a> &amp; MFAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Registers all available machine function analysis passes.</p>


<p>This is an interface that can be used to populate a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a></span> with all registered function analyses. Callers can still manually register any additional analyses. Callers can also pre-register analyses and this will not override those.</p>


<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerModuleAnalyses() {#acba45c16e3934023f1fe17627951b5b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::registerModuleAnalyses (<a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; MAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Registers all available module analysis passes.</p>


<p>This is an interface that can be used to populate a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a></span> with all registered module analyses. Callers can still manually register any additional analyses. Callers can also pre-register analyses and this will not override those.</p>


<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a>.</p>

</div>
</div>

### registerOptimizerEarlyEPCallback() {#add1e5f9adbdfe781825eeb0e4e0925ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerOptimizerEarlyEPCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point.</p>


<p>This extension point allows adding optimizations before the function optimization pipeline.</p>


<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>.</p>

</div>
</div>

### registerOptimizerLastEPCallback() {#a41abe02ceef34a89fd73bf8e85987bcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerOptimizerLastEPCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a>)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point.</p>


<p>This extension point allows adding optimizations at the very end of the function optimization pipeline.</p>


<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerParseAACallback() {#a44e4fe174172d86171cde9a67ea19d38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerParseAACallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/aamanager">AAManager</a> &amp;AA)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for parsing an <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> Name to populate the given <a href="/web-llvm/docs/api/classes/llvm/aamanager">AAManager</a> <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span>.</p>

<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerParseTopLevelPipelineCallback() {#adf6d945d01a37f386a86d80d1072d01a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::registerParseTopLevelPipelineCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; bool(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt;)&gt; &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a top-level pipeline entry.</p>


<p>If the <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a> type is not given at the top level of the pipeline text, this Callback should be used to determine the appropriate stack of PassManagers and populate the passed <a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a>.</p>


<p>Declaration at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2489 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerPeepholeEPCallback() {#a5ac5d2f0e7a33e8ba20e5f7f28f60791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerPeepholeEPCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point.</p>


<p>This extension point allows adding passes that perform peephole optimizations similar to the instruction combiner. These passes will be inserted after each instance of the instruction combiner pass.</p>


<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerPipelineEarlySimplificationEPCallback() {#a267c74c52d09d66146ce289acb4ba3be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerPipelineEarlySimplificationEPCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a>)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point.</p>


<p>This extension point allows adding optimization right after passes that do basic simplification of the input IR.</p>


<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerPipelineParsingCallback() {#ab9268c557f7572dc641ac05aaff0c2ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerPipelineParsingCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ded4558d2b58dcdd7a1736aa69a8bc4">CGSCCPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt;)&gt; &amp; C)</td>
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

<p>{{@ <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> pipeline parsing callbacks with this pass builder instance.</p>


<p>Using these callbacks, callers can parse both a single pass name, as well as entire sub-pipelines, and populate the <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a> instance accordingly.</p>


<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerPipelineParsingCallback() {#ac57131cc89f11b1e31859a0a9e420d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerPipelineParsingCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt;)&gt; &amp; C)</td>
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



<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerPipelineParsingCallback() {#a2fb9d712436059b253d38b22775ef225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerPipelineParsingCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/#a613892f4c1a570fd3747f2b6b1bf9b75">LoopPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt;)&gt; &amp; C)</td>
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



<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerPipelineParsingCallback() {#a1cf4745be1d8c37779f3ba1451d182e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerPipelineParsingCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt;)&gt; &amp; C)</td>
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



<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerPipelineParsingCallback() {#ada980b5fa41be687b6ada7ad11e7a7c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerPipelineParsingCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4d6ff2181c8f2a8d4dabd70e55f2ba2">MachineFunctionPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt;)&gt; &amp; C)</td>
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



<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerPipelineStartEPCallback() {#a2c79d6634d4333b578eee9468600545f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerPipelineStartEPCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point.</p>


<p>This extension point allows adding optimization once at the start of the pipeline. This does not apply to 'backend' compiles (LTO and ThinLTO link-time pipelines).</p>


<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerRegClassFilterParsingCallback() {#ab1e097b85fd09a6964448e5e95761fcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerRegClassFilterParsingCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a0ab9dba764b528b15e89f9c443b2e202">RegAllocFilterFunc</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> callbacks to parse target specific filter field if regalloc pass needs it.</p>


<p>E.g. <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> requires regalloc passes can handle sgpr and vgpr separately.</p>


<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerScalarOptimizerLateEPCallback() {#a6f680e4b9b66bf942083addab4886aa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerScalarOptimizerLateEPCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point.</p>


<p>This extension point allows adding optimization passes after most of the main optimizations, but before the last cleanup-ish optimizations.</p>


<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### registerVectorizerStartEPCallback() {#a50b4af342809d2b24844972dae47d201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassBuilder::registerVectorizerStartEPCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a>)&gt; &amp; C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback for a default optimizer pipeline extension point.</p>


<p>This extension point allows adding optimization passes before the vectorizer and other highly target specific optimization passes are executed.</p>


<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addPGOInstrPasses() {#a3ee27cbc56e740cbf25ff0757fa2b9b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::addPGOInstrPasses (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, bool RunProfileGen, bool IsCS, bool AtomicCounterUpdate, std::string ProfileFile, std::string ProfileRemappingFile, <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &gt; FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 742 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 828 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>

</div>
</div>

### addPostPGOLoopRotation() {#a08e01c7433fc141447a80e1b234a2742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::addPostPGOLoopRotation (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>

</div>
</div>

### addPreInlinerPasses() {#a039ef994baa5f61aa77db6eb04659f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::addPreInlinerPasses (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> LTOPhase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 775 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>

</div>
</div>

### addRequiredLTOPreLinkPasses() {#a9638052437a3d6da96be24fb03709827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::addRequiredLTOPreLinkPasses (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 709 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>

</div>
</div>

### addVectorPasses() {#a6bb4673c43fc983cb08ed2af51567e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PassBuilder::addVectorPasses (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp; FPM, bool IsFullLTO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TODO: Should LTO cause any differences to this set of passes?</p>

<p>Declaration at line 711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1271 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>

</div>
</div>

### buildO1FunctionSimplificationPipeline() {#ab79f4e990c7d7952ea240decf070632f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPassManager PassBuilder::buildO1FunctionSimplificationPipeline (<a href="/web-llvm/docs/api/classes/llvm/optimizationlevel">OptimizationLevel</a> Level, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> Phase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>

</div>
</div>

### parseAAPassName() {#a01caaefbe78c1697aabe3deb5a717e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PassBuilder::parseAAPassName (<a href="/web-llvm/docs/api/classes/llvm/aamanager">AAManager</a> &amp; AA, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2154 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### parseCGSCCPass() {#a9384aa2cc31d8453ab77d4260fb6a13a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parseCGSCCPass (<a href="/web-llvm/docs/api/namespaces/llvm/#a4ded4558d2b58dcdd7a1736aa69a8bc4">CGSCCPassManager</a> &amp; CGPM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &amp; E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1816 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### parseCGSCCPassPipeline() {#a4d54d7e4f3e27a71260c54e9171612a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parseCGSCCPassPipeline (<a href="/web-llvm/docs/api/namespaces/llvm/#a4ded4558d2b58dcdd7a1736aa69a8bc4">CGSCCPassManager</a> &amp; CGPM, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt; Pipeline)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 731 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2202 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### parseFunctionPass() {#aeb399928be5d7edf3615289fa78a43f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parseFunctionPass (<a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp; FPM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &amp; E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1931 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### parseFunctionPassPipeline() {#a2cb4f113e1b6af04eebbacb1f833985f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parseFunctionPassPipeline (<a href="/web-llvm/docs/api/namespaces/llvm/#ab70ef138acbdb1c8278ecf41f5da400f">FunctionPassManager</a> &amp; FPM, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt; Pipeline)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2193 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### parseLoopPass() {#a8513015025c73e6a6aaeac2de2279489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parseLoopPass (<a href="/web-llvm/docs/api/namespaces/llvm/#a613892f4c1a570fd3747f2b6b1bf9b75">LoopPassManager</a> &amp; LPM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &amp; E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2039 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### parseLoopPassPipeline() {#a8cad940c7d9abf7471a163e9abc6e122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parseLoopPassPipeline (<a href="/web-llvm/docs/api/namespaces/llvm/#a613892f4c1a570fd3747f2b6b1bf9b75">LoopPassManager</a> &amp; LPM, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt; Pipeline)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2184 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### parseMachinePass() {#a74307702dfde39c25eec711e61305798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parseMachinePass (<a href="/web-llvm/docs/api/namespaces/llvm/#ac4d6ff2181c8f2a8d4dabd70e55f2ba2">MachineFunctionPassManager</a> &amp; MFPM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &amp; E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2106 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### parseMachinePassPipeline() {#a495b9d65d8ce8d6fcdb122ca5f81bfdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parseMachinePassPipeline (<a href="/web-llvm/docs/api/namespaces/llvm/#ac4d6ff2181c8f2a8d4dabd70e55f2ba2">MachineFunctionPassManager</a> &amp; MFPM, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt; Pipeline)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2175 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### parseModulePass() {#a13ab776e0142ba221bba7677898efc88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parseModulePass (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &amp; E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1638 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

### parseModulePassPipeline() {#a831a5e63b1d2a455a8ce7769897cbff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error PassBuilder::parseModulePassPipeline (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt; Pipeline)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 2235 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AAParsingCallbacks {#a39ce053e76c1daf981ab1be4fc338df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;bool(StringRef Name, AAManager &amp;AA)&gt;, 2&gt; llvm::PassBuilder::AAParsingCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### CGSCCAnalysisRegistrationCallbacks {#ac05d7c083726335e69f0498e17475dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(CGSCCAnalysisManager &amp;)&gt;, 2&gt; llvm::PassBuilder::CGSCCAnalysisRegistrationCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### CGSCCOptimizerLateEPCallbacks {#addfde929bf0d30cbc8df7a7499f16b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(CGSCCPassManager &amp;, OptimizationLevel)&gt;, 2&gt; llvm::PassBuilder::CGSCCOptimizerLateEPCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### CGSCCPipelineParsingCallbacks {#ad858a6fa7d4df75114fb4b94906bacc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;bool(StringRef, CGSCCPassManager &amp;, ArrayRef&lt;PipelineElement&gt;)&gt;, 2&gt; llvm::PassBuilder::CGSCCPipelineParsingCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### FullLinkTimeOptimizationEarlyEPCallbacks {#a848db2f749386f664711241c00d3c991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(ModulePassManager &amp;, OptimizationLevel)&gt;, 2&gt; llvm::PassBuilder::FullLinkTimeOptimizationEarlyEPCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### FullLinkTimeOptimizationLastEPCallbacks {#a2dfd4723160dfbdd5fdff57429b63d8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(ModulePassManager &amp;, OptimizationLevel)&gt;, 2&gt; llvm::PassBuilder::FullLinkTimeOptimizationLastEPCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### FunctionAnalysisRegistrationCallbacks {#ab5da6f00fcf4eb04140ee3476d42584a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(FunctionAnalysisManager &amp;)&gt;, 2&gt; llvm::PassBuilder::FunctionAnalysisRegistrationCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### FunctionPipelineParsingCallbacks {#a6228bdcec0c6c7126bbf3f7cbe2040b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;bool(StringRef, FunctionPassManager &amp;, ArrayRef&lt;PipelineElement&gt;)&gt;, 2&gt; llvm::PassBuilder::FunctionPipelineParsingCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### LateLoopOptimizationsEPCallbacks {#af824c04d38b63ab6ed9ca7c6fe989c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(LoopPassManager &amp;, OptimizationLevel)&gt;, 2&gt; llvm::PassBuilder::LateLoopOptimizationsEPCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### LoopAnalysisRegistrationCallbacks {#a3d97d9feb91bca950e9cc460e44471c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(LoopAnalysisManager &amp;)&gt;, 2&gt; llvm::PassBuilder::LoopAnalysisRegistrationCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### LoopOptimizerEndEPCallbacks {#a6302dfa286f2267aebf58132c24194ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(LoopPassManager &amp;, OptimizationLevel)&gt;, 2&gt; llvm::PassBuilder::LoopOptimizerEndEPCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### LoopPipelineParsingCallbacks {#a8ee3557be559a185b98db7a38a79ef99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;bool(StringRef, LoopPassManager &amp;, ArrayRef&lt;PipelineElement&gt;)&gt;, 2&gt; llvm::PassBuilder::LoopPipelineParsingCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 811 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### MachineFunctionAnalysisRegistrationCallbacks {#ac8f4d51ae98fac2fa4b856e198c6c5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(MachineFunctionAnalysisManager &amp;)&gt;, 2&gt; llvm::PassBuilder::MachineFunctionAnalysisRegistrationCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### MachineFunctionPipelineParsingCallbacks {#a4d8b5378310abd0999cb9fdda1eaab54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;bool(StringRef, MachineFunctionPassManager &amp;, ArrayRef&lt;PipelineElement&gt;)&gt;, 2&gt; llvm::PassBuilder::MachineFunctionPipelineParsingCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### ModuleAnalysisRegistrationCallbacks {#ae56af268c419014c240961fdffa32c2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(ModuleAnalysisManager &amp;)&gt;, 2&gt; llvm::PassBuilder::ModuleAnalysisRegistrationCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### ModulePipelineParsingCallbacks {#af006beea2252e92d20431478269d5416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;bool(StringRef, ModulePassManager &amp;, ArrayRef&lt;PipelineElement&gt;)&gt;, 2&gt; llvm::PassBuilder::ModulePipelineParsingCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### OptimizerEarlyEPCallbacks {#a218ccb8bab03982ac91dbf3cc5d0091f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(ModulePassManager &amp;, OptimizationLevel, ThinOrFullLTOPhase)&gt;, 2&gt; llvm::PassBuilder::OptimizerEarlyEPCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### OptimizerLastEPCallbacks {#ab8fe7ed3ff3605e79cab87201dc527a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(ModulePassManager &amp;, OptimizationLevel, ThinOrFullLTOPhase)&gt;, 2&gt; llvm::PassBuilder::OptimizerLastEPCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### PeepholeEPCallbacks {#ab4cde43a30fb87989de4f6644d3d3e77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(FunctionPassManager &amp;, OptimizationLevel)&gt;, 2&gt; llvm::PassBuilder::PeepholeEPCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### PGOOpt {#ad595335c2b920f227a2835498cb7fa90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;PGOOptions&gt; llvm::PassBuilder::PGOOpt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### PIC {#af6892617cd08e50c4a9e3e6c53f2582b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassInstrumentationCallbacks* llvm::PassBuilder::PIC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### PipelineEarlySimplificationEPCallbacks {#a4596fd37c0422714997e3236c961ef02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(ModulePassManager &amp;, OptimizationLevel, ThinOrFullLTOPhase)&gt;, 2&gt; llvm::PassBuilder::PipelineEarlySimplificationEPCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### PipelineStartEPCallbacks {#a5c0e0ddbc25926a0584f0f8c2feb9f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(ModulePassManager &amp;, OptimizationLevel)&gt;, 2&gt; llvm::PassBuilder::PipelineStartEPCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 776 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### PTO {#abb75e46f0a8722b988934fee5607c9fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PipelineTuningOptions llvm::PassBuilder::PTO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### RegClassFilterParsingCallbacks {#a5e3d8d3c0f45550c9d8c97019cb2cef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;RegAllocFilterFunc(StringRef)&gt;, 2&gt; llvm::PassBuilder::RegClassFilterParsingCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 824 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### ScalarOptimizerLateEPCallbacks {#a40b1c2af7df8c7056f42cd5b363456bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(FunctionPassManager &amp;, OptimizationLevel)&gt;, 2&gt; llvm::PassBuilder::ScalarOptimizerLateEPCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 757 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### TM {#aa4078492b9944119369a94390651a08f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetMachine* llvm::PassBuilder::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### TopLevelPipelineParsingCallbacks {#a2c48972132e4f26014adb5d985d3f015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; std::function&lt;bool(ModulePassManager &amp;, ArrayRef&lt;PipelineElement&gt;)&gt;, 2&gt; llvm::PassBuilder::TopLevelPipelineParsingCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### VectorizerStartEPCallbacks {#a8985498403ab26c6521b11f1f4f07a63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::function&lt;void(FunctionPassManager &amp;, OptimizationLevel)&gt;, 2&gt; llvm::PassBuilder::VectorizerStartEPCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### checkParametrizedPassName() {#a0d95457b7af7593624ad31405198d59d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PassBuilder::checkParametrizedPassName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
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



<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#a8130b07a44ca5c11ae1aac80d5129a7a">isLoopNestPassName</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#aa54f2a3ed5acad7fd2b7b55141319525">isLoopPassName</a>.</p>

</div>
</div>

### parsePassParameters() {#ad552dcd2825d0f59fae310931b7813bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParametersParseCallableT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">decltype(Parser(StringRef{})) llvm::PassBuilder::parsePassParameters (ParametersParseCallableT &amp;&amp; Parser, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
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

<p>This performs customized parsing of pass name with parameters.</p>


<p>We do not need parametrization of passes in textual pipeline very often, yet on a rare occasion ability to specify parameters right there can be useful.</p>


<p><span class="doxyComputerOutput">Name</span> - parameterized specification of a pass from a textual pipeline is a string in a form of : PassName '&lt;' parameter-list '&gt;'</p>


<p>Parameter list is being parsed by the parser callable argument, <span class="doxyComputerOutput">Parser</span>, It takes a string-ref of parameters and returns either <a href="/web-llvm/docs/api/classes/llvm/stringerror">StringError</a> or a parameter list in a form of a custom parameters type, all wrapped into <a href="/web-llvm/docs/api/classes/llvm/expected">Expected&lt;&gt;</a> template class.</p>


<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>

</div>
</div>

### parseSinglePassOption() {#adc2db790282de50547f17992a5dece6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; PassBuilder::parseSinglePassOption (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Params, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OptionName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
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

<p>Handle passes only accept one bool-valued parameter.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>false when Params is empty.</p></dd>
</dl>


<p>Declaration at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpftargetmachine-cpp/#a524f7c60f7fd528974c6de622ca45852">parseBPFPreserveStaticOffsetOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a65cb9528ef1e2eedb03cfea6203debf6">anonymous{PassBuilder.cpp}::parseCGProfilePassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a7646e26b0a79c452593b60ad9cb431a0">anonymous{PassBuilder.cpp}::parseCoroSplitPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a69936227b39fb92a056c55034df2ebdd">anonymous{PassBuilder.cpp}::parseDependenceAnalysisPrinterOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a440e330b977932a051f4302132112791">anonymous{PassBuilder.cpp}::parseEarlyCSEPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a44685204853fe2f3fca8b095651f1977">anonymous{PassBuilder.cpp}::parseEntryExitInstrumenterPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#abc7d8c4a46cd06c746e2d579eb1f01d4">anonymous{PassBuilder.cpp}::parseGlobalDCEPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a7033fdd0b0f3c79c443a83626fa8039b">anonymous{PassBuilder.cpp}::parseInlinerPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a370b24a222d1b29d2eb943f4cdfe1f43">anonymous{PassBuilder.cpp}::parseLoopExtractorPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a8ea1f78101b51276457167683b87383d">anonymous{PassBuilder.cpp}::parseLowerMatrixIntrinsicsPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a8e515f1691d8d47cc305643771fff4e6">anonymous{PassBuilder.cpp}::parseMemorySSAPrinterPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ae6e0e100c7619d7026f83047103fc78b">anonymous{PassBuilder.cpp}::parsePostOrderFunctionAttrsPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a8c84ba9898e81e2700b7f179fe6c0b85">anonymous{PassBuilder.cpp}::parseSeparateConstOffsetFromGEPPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#aaa79935d9287d58837e67db34c1de7e3">anonymous{PassBuilder.cpp}::parseSpeculativeExecutionPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#af512f0b9da1647e220d1722e96c63f39">anonymous{PassBuilder.cpp}::parseStructurizeCFGPassOptions</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a6b8480effcb5140e86c6c9e7dfcf8f30">anonymous{PassBuilder.cpp}::parseWinEHPrepareOptions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### parsePipelineText() {#a80f7c19a0944e326653958887c447595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::vector&lt; PassBuilder::PipelineElement &gt; &gt; PassBuilder::parsePipelineText (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Text)</td>
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



<p>Declaration at line 715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 1582 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp">PassBuilder.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
