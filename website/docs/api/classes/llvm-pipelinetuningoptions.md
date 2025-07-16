---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pipelinetuningoptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PipelineTuningOptions` Class Reference

<p>Tunable parameters for passes in the default pipelines. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PipelineTuningOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">llvm/Passes/PassBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb41cc3f45423b2af2334a6e2b0c087e">PipelineTuningOptions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor sets pipeline tuning defaults based on cl::opts. <a href="#acb41cc3f45423b2af2334a6e2b0c087e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca24b802a8802101b5f43ca52ae51c54">LoopInterleaving</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tuning option to set loop interleaving on/off, set based on opt level. <a href="#aca24b802a8802101b5f43ca52ae51c54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af94d30491218ab25314dbff8123a9de7">LoopVectorization</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tuning option to enable/disable loop vectorization, set based on opt level. <a href="#af94d30491218ab25314dbff8123a9de7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e37acc197f406344af4c2f1c94998dc">SLPVectorization</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tuning option to enable/disable slp loop vectorization, set based on opt level. <a href="#a2e37acc197f406344af4c2f1c94998dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5b2b612c2769e79040e34bc4be7a77f">LoopUnrolling</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tuning option to enable/disable loop unrolling. Its default value is true. <a href="#af5b2b612c2769e79040e34bc4be7a77f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4261b710708d3ffd351693d268dbc2b">ForgetAllSCEVInLoopUnroll</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tuning option to forget all <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> loops in LoopUnroll. <a href="#ac4261b710708d3ffd351693d268dbc2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6e1792333480127f9028e4aa6bd3b8c">LicmMssaOptCap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tuning option to cap the number of calls to retrive clobbering accesses in <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>, in LICM. <a href="#ac6e1792333480127f9028e4aa6bd3b8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b2d205f1603cc9f2695fd5aa74b2074">LicmMssaNoAccForPromotionCap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tuning option to disable promotion to scalars in LICM with <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>, if the number of access is too large. <a href="#a2b2d205f1603cc9f2695fd5aa74b2074">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02f5f300988ddd7c25206b663f59801">CallGraphProfile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tuning option to enable/disable call graph profile. <a href="#ab02f5f300988ddd7c25206b663f59801">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5462397dcc8c5c4e777914266a89b6">UnifiedLTO</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3297e2f307cf401f90f6f3d568aeaa4">MergeFunctions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tuning option to enable/disable function merging. <a href="#ac3297e2f307cf401f90f6f3d568aeaa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f21980b835884f614ce859110239cce">InlinerThreshold</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tuning option to override the default inliner threshold. <a href="#a7f21980b835884f614ce859110239cce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a914808bb0a6b45396e47d14b93a3c2a8">EagerlyInvalidateAnalyses</a></td>
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

<p>Tunable parameters for passes in the default pipelines.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PipelineTuningOptions() {#acb41cc3f45423b2af2334a6e2b0c087e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PipelineTuningOptions::PipelineTuningOptions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructor sets pipeline tuning defaults based on cl::opts.</p>


<p>Each option can be set in the <a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a> when using a LLVM as a library.</p>


<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>, definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a>.</p>


<p>References <a href="#ab02f5f300988ddd7c25206b663f59801">CallGraphProfile</a>, <a href="#a914808bb0a6b45396e47d14b93a3c2a8">EagerlyInvalidateAnalyses</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a2c2579919664d84b31b404d697d8ea5a">EnableEagerlyInvalidateAnalyses</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp/#a038daaefae1a34b95cd6f879efba8dac">EnableMergeFunctions</a>, <a href="#ac4261b710708d3ffd351693d268dbc2b">ForgetAllSCEVInLoopUnroll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74ac302e71a5bdbb6b2ab1e1d1266e6e">llvm::ForgetSCEVInLoopUnroll</a>, <a href="#a7f21980b835884f614ce859110239cce">InlinerThreshold</a>, <a href="#a2b2d205f1603cc9f2695fd5aa74b2074">LicmMssaNoAccForPromotionCap</a>, <a href="#ac6e1792333480127f9028e4aa6bd3b8c">LicmMssaOptCap</a>, <a href="#aca24b802a8802101b5f43ca52ae51c54">LoopInterleaving</a>, <a href="#af5b2b612c2769e79040e34bc4be7a77f">LoopUnrolling</a>, <a href="#af94d30491218ab25314dbff8123a9de7">LoopVectorization</a>, <a href="#ac3297e2f307cf401f90f6f3d568aeaa4">MergeFunctions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad9c3fae5a25cf9c407f7b07a86067ab5">llvm::SetLicmMssaNoAccForPromotionCap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0eea3fd894969f858eee273ba9f0b9b">llvm::SetLicmMssaOptCap</a>, <a href="#a2e37acc197f406344af4c2f1c94998dc">SLPVectorization</a> and <a href="#afd5462397dcc8c5c4e777914266a89b6">UnifiedLTO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CallGraphProfile {#ab02f5f300988ddd7c25206b663f59801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PipelineTuningOptions::CallGraphProfile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tuning option to enable/disable call graph profile.</p>


<p>Its default value is that of the flag: <span class="doxyComputerOutput">-enable-npm-call-graph-profile</span>.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Referenced by <a href="#acb41cc3f45423b2af2334a6e2b0c087e">PipelineTuningOptions</a>.</p>

</div>
</div>

### EagerlyInvalidateAnalyses {#a914808bb0a6b45396e47d14b93a3c2a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PipelineTuningOptions::EagerlyInvalidateAnalyses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Referenced by <a href="#acb41cc3f45423b2af2334a6e2b0c087e">PipelineTuningOptions</a>.</p>

</div>
</div>

### ForgetAllSCEVInLoopUnroll {#ac4261b710708d3ffd351693d268dbc2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PipelineTuningOptions::ForgetAllSCEVInLoopUnroll</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tuning option to forget all <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> loops in LoopUnroll.</p>


<p>Its default value is that of the flag: <span class="doxyComputerOutput">-forget-scev-loop-unroll</span>.</p>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Referenced by <a href="#acb41cc3f45423b2af2334a6e2b0c087e">PipelineTuningOptions</a>.</p>

</div>
</div>

### InlinerThreshold {#a7f21980b835884f614ce859110239cce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::PipelineTuningOptions::InlinerThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tuning option to override the default inliner threshold.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Referenced by <a href="#acb41cc3f45423b2af2334a6e2b0c087e">PipelineTuningOptions</a>.</p>

</div>
</div>

### LicmMssaNoAccForPromotionCap {#a2b2d205f1603cc9f2695fd5aa74b2074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PipelineTuningOptions::LicmMssaNoAccForPromotionCap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tuning option to disable promotion to scalars in LICM with <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>, if the number of access is too large.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Referenced by <a href="#acb41cc3f45423b2af2334a6e2b0c087e">PipelineTuningOptions</a>.</p>

</div>
</div>

### LicmMssaOptCap {#ac6e1792333480127f9028e4aa6bd3b8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PipelineTuningOptions::LicmMssaOptCap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tuning option to cap the number of calls to retrive clobbering accesses in <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>, in LICM.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Referenced by <a href="#acb41cc3f45423b2af2334a6e2b0c087e">PipelineTuningOptions</a>.</p>

</div>
</div>

### LoopInterleaving {#aca24b802a8802101b5f43ca52ae51c54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PipelineTuningOptions::LoopInterleaving</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tuning option to set loop interleaving on/off, set based on opt level.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Referenced by <a href="#acb41cc3f45423b2af2334a6e2b0c087e">PipelineTuningOptions</a>.</p>

</div>
</div>

### LoopUnrolling {#af5b2b612c2769e79040e34bc4be7a77f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PipelineTuningOptions::LoopUnrolling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tuning option to enable/disable loop unrolling. Its default value is true.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Referenced by <a href="#acb41cc3f45423b2af2334a6e2b0c087e">PipelineTuningOptions</a>.</p>

</div>
</div>

### LoopVectorization {#af94d30491218ab25314dbff8123a9de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PipelineTuningOptions::LoopVectorization</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tuning option to enable/disable loop vectorization, set based on opt level.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a> and <a href="#acb41cc3f45423b2af2334a6e2b0c087e">PipelineTuningOptions</a>.</p>

</div>
</div>

### MergeFunctions {#ac3297e2f307cf401f90f6f3d568aeaa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PipelineTuningOptions::MergeFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tuning option to enable/disable function merging.</p>


<p>Its default value is false.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Referenced by <a href="#acb41cc3f45423b2af2334a6e2b0c087e">PipelineTuningOptions</a>.</p>

</div>
</div>

### SLPVectorization {#a2e37acc197f406344af4c2f1c94998dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PipelineTuningOptions::SLPVectorization</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tuning option to enable/disable slp loop vectorization, set based on opt level.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a> and <a href="#acb41cc3f45423b2af2334a6e2b0c087e">PipelineTuningOptions</a>.</p>

</div>
</div>

### UnifiedLTO {#afd5462397dcc8c5c4e777914266a89b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PipelineTuningOptions::UnifiedLTO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<p>Referenced by <a href="#acb41cc3f45423b2af2334a6e2b0c087e">PipelineTuningOptions</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderpipelines-cpp">PassBuilderPipelines.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
