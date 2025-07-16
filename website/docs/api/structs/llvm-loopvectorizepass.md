---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/loopvectorizepass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LoopVectorizePass` Struct Reference

<p>The LoopVectorize <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::LoopVectorizePass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">llvm/Transforms/Vectorize/LoopVectorize.h</a>"
</div>

## Base struct

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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51be961763c595602654e8d825f26b59">LoopVectorizePass</a> (LoopVectorizeOptions Opts={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b0e58cfdb2c6c663cd47a8808ba70a">run</a> (Function &amp;F, FunctionAnalysisManager &amp;AM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fa1898352e5014c447a589398c94595">printPipeline</a> (raw_ostream &amp;OS, function_ref&lt; StringRef(StringRef)&gt; MapClassName2PassName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopvectorizeresult">LoopVectorizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d3ab70393b799b3be4875c3334a4f42">runImpl</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a160afa01e95095aa0c8115b6e0e6f4a6">processLoop</a> (Loop *L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7c40b0a986979535eddeb2bb6eae05">SE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32cea93d587825e715e63f5d58834cd3">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af801c62acf781555151418001a6c5270">TTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4e171d085c0c20949584a32ee65acce">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5604ee7cd98afbb8b5a581e9c3dd7dff">BFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07ce98f749d234136ba025ecbf174b53">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/demandedbits">DemandedBits</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a427352f0eda31223a0b25d9f143ce0b1">DB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ba33b1dd671be4bc212c442516409f">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopaccessinfomanager">LoopAccessInfoManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38ff83df2a3ad17de50157ed09a1c259">LAIs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af494038e310bd942f44e66bee50ce632">ORE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1833d18292c92e20a003f7074e518060">PSI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a584d70403f3b2cce007cb1ad1f5fc5dd">InterleaveOnlyWhenForced</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If false, consider all loops for interleaving. <a href="#a584d70403f3b2cce007cb1ad1f5fc5dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a358650bf5ecaff6dd6313259bf5c23b7">VectorizeOnlyWhenForced</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If false, consider all loops for vectorization. <a href="#a358650bf5ecaff6dd6313259bf5c23b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The LoopVectorize <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a>.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopVectorizePass() {#a51be961763c595602654e8d825f26b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorizePass::LoopVectorizePass (<a href="/web-llvm/docs/api/structs/llvm/loopvectorizeoptions">LoopVectorizeOptions</a> Opts={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>, definition at line 10150 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af98e93062e9f33018307ffc64d4b009e">llvm::EnableLoopInterleaving</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f386d38a2c6c22a343243e9e48f7532">llvm::EnableLoopVectorization</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### printPipeline() {#a4fa1898352e5014c447a589398c94595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizePass::printPipeline (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; MapClassName2PassName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>, definition at line 10865 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="#a4fa1898352e5014c447a589398c94595">printPipeline</a>.</p>


<p>Referenced by <a href="#a4fa1898352e5014c447a589398c94595">printPipeline</a>.</p>

</div>
</div>

### processLoop() {#a160afa01e95095aa0c8115b6e0e6f4a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizePass::processLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>, definition at line 10327 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#ab9ba33b1dd671be4bc212c442516409f">AC</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a033bb363914fbd3c2cd990330959036c">addRuntimeUnrollDisableMetaData</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a21b6d9e2aa12c8c68d8e2f122ec7ecec">llvm::LoopVectorizeHints::allowVectorization</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo/#af587d7218fa15a456103c3d2125a1fc8">llvm::InterleavedAccessInfo::analyzeInterleaving</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a362f793f3254317c698e3560548788a5">areRuntimeChecksProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a2e066ef7bc9673cbb2a825189491577d">llvm::InnerLoopVectorizer::areSafetyChecksAdded</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5604ee7cd98afbb8b5a581e9c3dd7dff">BFI</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a3ce10d1174bdfcac2b73ed7efa352b7f">llvm::LoopVectorizationLegality::canVectorize</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a552a158f5a673da0a26461d1471cea41">llvm::LoopVectorizationLegality::canVectorizeFPMath</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af1fba45879c49d4839b11ec30afd7532">checkMixedPrecision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9da0a5c3a3ea2de39aa77f3e6da8de4d5bd">llvm::CM_ScalarEpilogueNotAllowedLowTripLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9da34c20b2dbd2edddfd1b013f073a32354">llvm::CM_ScalarEpilogueNotNeededUsePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a4adc69fc8f74164e990cce6afc1e061b">llvm::LoopVectorizationPlanner::computeBestVF</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#a048d568675a5cc69c3fb85206882316d">llvm::VectorizationFactor::Cost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a686506cbb75808c52247608065bc6596">llvm::LoopVectorizationCostModel::CostKind</a>, <a href="#a427352f0eda31223a0b25d9f143ce0b1">DB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="#af4e171d085c0c20949584a32ee65acce">DT</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#afadf7ae5a5fad2c0bde13e8b72bf7a71">llvm::VPlan::duplicate</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aa216c2cbc8d9610dc20db065aca671d3">llvm::LoopVectorizationPlanner::emitInvalidCostRemarks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a440979b6103588bef39bd2d62065d5ff">llvm::LoopVectorizeHints::emitRemarkWithHints</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af7af1b4bf03205c80dcba0a6324c4f21">EnableEarlyExitVectorization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ac3af17aa5bce5ef8c3aa82faeacfc456">EnableInterleavedMemAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ef0a19ea2267182eb0da4f6e191b59b">llvm::EnableVPlanNativePath</a>, <a href="/web-llvm/docs/api/structs/llvm/epilogueloopvectorizationinfo/#a6ec74a5afe1cfb93444b9f8988ed4c12">llvm::EpilogueLoopVectorizationInfo::EpilogueUF</a>, <a href="/web-llvm/docs/api/structs/llvm/epilogueloopvectorizationinfo/#a529385ab333b24f1f2c2dd8525ad52a8">llvm::EpilogueLoopVectorizationInfo::EpilogueVF</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a55ab1072c44295ad279535d714a0f33ea980c2c6e59ca5dcf413baa325d8bc385">llvm::LoopVectorizeHints::FK_Disabled</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a55ab1072c44295ad279535d714a0f33ea278ca681847fb2bad9707f76d899b231">llvm::LoopVectorizeHints::FK_Enabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#acb0b374f69dc6867357f0aa5e93ab33d">ForceOrderedReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a7a32abdcf9e80b2483aa55bc36f2840e">llvm::LoopVectorizationLegality::getCountableExitingBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationrequirements/#a2bb8d6e55fae2cbc8eead3d7d4d3af09">llvm::LoopVectorizationRequirements::getExactFPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a20ecacbd54e401685d798d86161af6cf">llvm::LoopVectorizeHints::getForce</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#ad98353127dbeb649d41ca07da5074b49">llvm::LoopVectorizeHints::getInterleave</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#ab5632546144c4db5bbe1f975aeebd9d2">llvm::LoopVectorizationLegality::getLAI</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a10f355c5a55dd7e98d31c2f7e0b590aa">llvm::LoopVectorizationPlanner::getPlanFor</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a12a8ac8838fb851a2de5dc5275307bb6">llvm::PredicatedScalarEvolution::getPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a8cde912cc23c18f493e4e5005c85748b">getScalarEpilogueLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a84375e6536d9214c7895013078055aff">getSmallBestKnownTC</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a35de654dc8297fa810c78922102bb696">llvm::InnerLoopVectorizer::getTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a50cae5c2df432357d50f182d310ce7b7">llvm::LoopVectorizeHints::getWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fce2ce0e32b20e41b0aa9f8ca70c2">llvm::hasBranchWeightMD</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#ab306c8094bdb8c7cbdbdfb9a05800007">llvm::LoopVectorizationLegality::hasHistograms</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#adce80172b05bc0a227fbd5e3d7bb80f2">llvm::LoopVectorizationPlanner::hasPlanWithVF</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a9ede4d70a86b91ae038a77c86b3f4aaa">llvm::LoopVectorizationLegality::hasStructVectorCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#ab22ff9e23f7f27234c8f6ec76db0c1f3">llvm::LoopVectorizationLegality::hasUncountableEarlyExit</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a475b1d2223ddab6c0ab44dfcea7dcba7">llvm::LoopVectorizeHints::isPotentiallyUnsafe</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>, <a href="#a38ff83df2a3ad17de50157ed09a1c259">LAIs</a>, <a href="#a32cea93d587825e715e63f5d58834cd3">LI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a3bf55ccbbeedcfb8cd2a1bd62c0ad91a">LLVMLoopVectorizeFollowupAll</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aadedae9de069f3bcef6fa7a90ce4a630">LLVMLoopVectorizeFollowupEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp/#a0eff4a8bccb143ae91e197e6a59d4692">LV_NAME</a>, <a href="/web-llvm/docs/api/structs/llvm/epilogueloopvectorizationinfo/#a18939d452d993dd7ddd465c5c11535a4">llvm::EpilogueLoopVectorizationInfo::MainLoopUF</a>, <a href="/web-llvm/docs/api/structs/llvm/epilogueloopvectorizationinfo/#a6d536d11651c11a778ea9fe9332a4a2e">llvm::EpilogueLoopVectorizationInfo::MainLoopVF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a368216c9c116e3f30d8dd352ce1370fc">llvm::makeFollowupLoopID</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#a0c1900dc8fe6b998c1de1880f300dcfa">llvm::VectorizationFactor::MinProfitableTripCount</a>, <a href="#af494038e310bd942f44e66bee50ce632">ORE</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aca6160bb3d669e9ce01f91b124e7e0a1">llvm::LoopVectorizationPlanner::plan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adeb41c907ebde15846bc643325909f95">processLoopInVPlanNativePath</a>, <a href="#a1833d18292c92e20a003f7074e518060">PSI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c19b37908311872f655348755e8d003">llvm::reportVectorization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab425bb10a0f4af749bbb29aa07fc6854">llvm::reportVectorizationFailure</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo/#a34ed64ff27fabc002da4047589142b02">llvm::InterleavedAccessInfo::requiresScalarEpilogue</a>, <a href="#a7e7c40b0a986979535eddeb2bb6eae05">SE</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#aa2f5ef2d522fb80de283a23d5bed6d86">llvm::LoopVectorizeHints::setAlreadyVectorized</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a9160ed9f749a9c4df711061181288e13">llvm::InnerLoopVectorizer::setTripCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a15320a2d7ced6e62766048ae7b6f8b13">TinyTripCountVectorThreshold</a>, <a href="#a07ce98f749d234136ba025ecbf174b53">TLI</a>, <a href="#af801c62acf781555151418001a6c5270">TTI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adf8d8fb6f39b9c0cf21d55b7229d35e2">useMaskedInterleavedAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#abcf8c2b35316773f1ab0ba70aeb2a6de">llvm::LoopVectorizeHints::vectorizeAnalysisPassName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26389c546573f058ad8ecbdc5c1933cf">llvm::verifyFunction</a> and <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#a3a4e23fea2c7cec4fd3c2bf27351679c">llvm::VectorizationFactor::Width</a>.</p>


<p>Referenced by <a href="#a0d3ab70393b799b3be4875c3334a4f42">runImpl</a>.</p>

</div>
</div>

### run() {#af3b0e58cfdb2c6c663cd47a8808ba70a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses LoopVectorizePass::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>, definition at line 10816 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#ab9ba33b1dd671be4bc212c442516409f">AC</a>, <a href="#a5604ee7cd98afbb8b5a581e9c3dd7dff">BFI</a>, <a href="#a427352f0eda31223a0b25d9f143ce0b1">DB</a>, <a href="#af4e171d085c0c20949584a32ee65acce">DT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9ef2dbd1b7ce921093f7d4a7bd4cc5c">llvm::isAssignmentTrackingEnabled</a>, <a href="#a38ff83df2a3ad17de50157ed09a1c259">LAIs</a>, <a href="#a32cea93d587825e715e63f5d58834cd3">LI</a>, <a href="#af494038e310bd942f44e66bee50ce632">ORE</a>, <a href="#a1833d18292c92e20a003f7074e518060">PSI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08f3f942afc0ee9115a8f9fa87e9191d">llvm::RemoveRedundantDbgInstrs</a>, <a href="#a0d3ab70393b799b3be4875c3334a4f42">runImpl</a>, <a href="#a7e7c40b0a986979535eddeb2bb6eae05">SE</a>, <a href="#a07ce98f749d234136ba025ecbf174b53">TLI</a> and <a href="#af801c62acf781555151418001a6c5270">TTI</a>.</p>

</div>
</div>

### runImpl() {#a0d3ab70393b799b3be4875c3334a4f42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorizeResult LoopVectorizePass::runImpl (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>, definition at line 10758 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#ab9ba33b1dd671be4bc212c442516409f">AC</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a00315ff11c9068aab97e5780bdfa5eef">collectSupportedLoops</a>, <a href="#af4e171d085c0c20949584a32ee65acce">DT</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a30e47ae014eb35bea24e45097c2bd731">llvm::formLCSSARecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="#a38ff83df2a3ad17de50157ed09a1c259">LAIs</a>, <a href="#a32cea93d587825e715e63f5d58834cd3">LI</a>, <a href="#af494038e310bd942f44e66bee50ce632">ORE</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="#a160afa01e95095aa0c8115b6e0e6f4a6">processLoop</a>, <a href="#a7e7c40b0a986979535eddeb2bb6eae05">SE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0083a69883e0f97e111dbff064c60f42">llvm::simplifyLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#af801c62acf781555151418001a6c5270">TTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4522d39270d83d73550a3777a2fca312">llvm::VerifySCEV</a>.</p>


<p>Referenced by <a href="#af3b0e58cfdb2c6c663cd47a8808ba70a">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AC {#ab9ba33b1dd671be4bc212c442516409f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* llvm::LoopVectorizePass::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>Referenced by <a href="#a160afa01e95095aa0c8115b6e0e6f4a6">processLoop</a>, <a href="#af3b0e58cfdb2c6c663cd47a8808ba70a">run</a> and <a href="#a0d3ab70393b799b3be4875c3334a4f42">runImpl</a>.</p>

</div>
</div>

### BFI {#a5604ee7cd98afbb8b5a581e9c3dd7dff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo* llvm::LoopVectorizePass::BFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>Referenced by <a href="#a160afa01e95095aa0c8115b6e0e6f4a6">processLoop</a> and <a href="#af3b0e58cfdb2c6c663cd47a8808ba70a">run</a>.</p>

</div>
</div>

### DB {#a427352f0eda31223a0b25d9f143ce0b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DemandedBits* llvm::LoopVectorizePass::DB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>Referenced by <a href="#a160afa01e95095aa0c8115b6e0e6f4a6">processLoop</a> and <a href="#af3b0e58cfdb2c6c663cd47a8808ba70a">run</a>.</p>

</div>
</div>

### DT {#af4e171d085c0c20949584a32ee65acce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::LoopVectorizePass::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>Referenced by <a href="#a160afa01e95095aa0c8115b6e0e6f4a6">processLoop</a>, <a href="#af3b0e58cfdb2c6c663cd47a8808ba70a">run</a> and <a href="#a0d3ab70393b799b3be4875c3334a4f42">runImpl</a>.</p>

</div>
</div>

### LAIs {#a38ff83df2a3ad17de50157ed09a1c259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopAccessInfoManager* llvm::LoopVectorizePass::LAIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>Referenced by <a href="#a160afa01e95095aa0c8115b6e0e6f4a6">processLoop</a>, <a href="#af3b0e58cfdb2c6c663cd47a8808ba70a">run</a> and <a href="#a0d3ab70393b799b3be4875c3334a4f42">runImpl</a>.</p>

</div>
</div>

### LI {#a32cea93d587825e715e63f5d58834cd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::LoopVectorizePass::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>Referenced by <a href="#a160afa01e95095aa0c8115b6e0e6f4a6">processLoop</a>, <a href="#af3b0e58cfdb2c6c663cd47a8808ba70a">run</a> and <a href="#a0d3ab70393b799b3be4875c3334a4f42">runImpl</a>.</p>

</div>
</div>

### ORE {#af494038e310bd942f44e66bee50ce632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter* llvm::LoopVectorizePass::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>Referenced by <a href="#a160afa01e95095aa0c8115b6e0e6f4a6">processLoop</a>, <a href="#af3b0e58cfdb2c6c663cd47a8808ba70a">run</a> and <a href="#a0d3ab70393b799b3be4875c3334a4f42">runImpl</a>.</p>

</div>
</div>

### PSI {#a1833d18292c92e20a003f7074e518060}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* llvm::LoopVectorizePass::PSI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>Referenced by <a href="#a160afa01e95095aa0c8115b6e0e6f4a6">processLoop</a> and <a href="#af3b0e58cfdb2c6c663cd47a8808ba70a">run</a>.</p>

</div>
</div>

### SE {#a7e7c40b0a986979535eddeb2bb6eae05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* llvm::LoopVectorizePass::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>Referenced by <a href="#a160afa01e95095aa0c8115b6e0e6f4a6">processLoop</a>, <a href="#af3b0e58cfdb2c6c663cd47a8808ba70a">run</a> and <a href="#a0d3ab70393b799b3be4875c3334a4f42">runImpl</a>.</p>

</div>
</div>

### TLI {#a07ce98f749d234136ba025ecbf174b53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo* llvm::LoopVectorizePass::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>Referenced by <a href="#a160afa01e95095aa0c8115b6e0e6f4a6">processLoop</a> and <a href="#af3b0e58cfdb2c6c663cd47a8808ba70a">run</a>.</p>

</div>
</div>

### TTI {#af801c62acf781555151418001a6c5270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo* llvm::LoopVectorizePass::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>Referenced by <a href="#a160afa01e95095aa0c8115b6e0e6f4a6">processLoop</a>, <a href="#af3b0e58cfdb2c6c663cd47a8808ba70a">run</a> and <a href="#a0d3ab70393b799b3be4875c3334a4f42">runImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InterleaveOnlyWhenForced {#a584d70403f3b2cce007cb1ad1f5fc5dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizePass::InterleaveOnlyWhenForced</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If false, consider all loops for interleaving.</p>


<p>If true, only loops that explicitly request interleaving are considered.</p>


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>

</div>
</div>

### VectorizeOnlyWhenForced {#a358650bf5ecaff6dd6313259bf5c23b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizePass::VectorizeOnlyWhenForced</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If false, consider all loops for vectorization.</p>


<p>If true, only loops that explicitly request vectorization are considered.</p>


<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
