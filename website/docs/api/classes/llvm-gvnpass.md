---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gvnpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GVNPass` Class

<p>The core GVN pass object. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GVNPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">llvm/Transforms/Scalar/GVN.h</a>"
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063f1fae9025ed4f9d7186c26d8ed532">LoadDepVect</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/nonlocaldepresult">NonLocalDepResult</a>, 64 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f60d95a30f6b03ac0444e402430ba86">AvailValInBlkVect</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalueinblock">gvn::AvailableValueInBlock</a>, 64 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3305b0655234e9925523630033bfe0">UnavailBlkVect</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 64 &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bd68f76e3641c20dfa1dec36e41cf61">gvn::GVNLegacyPass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f1b6c33b018570dddad6adfde31870a">DenseMapInfo&lt; Expression &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b9ab672829302405b735225d5e20b6">GVNPass</a> (GVNOptions Options={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25dcf17194b012b2b35388798cac2da7">run</a> (Function &amp;F, FunctionAnalysisManager &amp;AM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the pass over the function. <a href="#a25dcf17194b012b2b35388798cac2da7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6796eb8a0e27f209321cbeff6a6faee8">printPipeline</a> (raw_ostream &amp;OS, function_ref&lt; StringRef(StringRef)&gt; MapClassName2PassName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abefca2348c563ac9ceaab87ff2f2152f">markInstructionForDeletion</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This removes the specified instruction from our various maps and marks it for deletion. <a href="#abefca2348c563ac9ceaab87ff2f2152f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82ed0f5454537781dd2949146821f7a1">getDominatorTree</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a465c9577ba88345e23a496d47e185e2b">getAliasAnalysis</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults">MemoryDependenceResults</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb3aabd952dd6fc744032b003a67ec5d">getMemDep</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc0652ed25618b41f317c0bae461e16">isPREEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5046bdddf55a6ad3fd2ad7640b4f8d0c">isLoadPREEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9449bef29f49a1b4be0ba63609317a34">isLoadInLoopPREEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac8394f15fa6e03d02344993ef4a15df">isLoadPRESplitBackedgeEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf1278a3accfd7d0207e37273e4229d2">isMemDepEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75b7cd0e780b19141e601e75a706fb5c">isMemorySSAEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a570ea6443fd6d50edbc44b69ee2e1bea">runImpl</a> (Function &amp;F, AssumptionCache &amp;RunAC, DominatorTree &amp;RunDT, const TargetLibraryInfo &amp;RunTLI, AAResults &amp;RunAA, MemoryDependenceResults *RunMD, LoopInfo &amp;LI, OptimizationRemarkEmitter *ORE, MemorySSA *MSSA=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnFunction - This is the main transformation entry point for a function. <a href="#a570ea6443fd6d50edbc44b69ee2e1bea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a774d11f023c46f5ef42b95684cc538a5">processLoad</a> (LoadInst *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to eliminate a load, first by eliminating it locally, and then attempting non-local elimination if that fails. <a href="#a774d11f023c46f5ef42b95684cc538a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6fe145bf27fa72c40dacb2354a2639a">processNonLocalLoad</a> (LoadInst *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to eliminate a load whose dependencies are non-local by performing PHI construction. <a href="#af6fe145bf27fa72c40dacb2354a2639a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a2d0007c1e09679867cebfff73029ce">processAssumeIntrinsic</a> (AssumeInst *II)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue">gvn::AvailableValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab449cc343665eeb9c96de359159002a9">AnalyzeLoadAvailability</a> (LoadInst *Load, MemDepResult DepInfo, Value *Address)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a local dependency (Def or Clobber) determine if a value is available for the load. <a href="#ab449cc343665eeb9c96de359159002a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36768091a495c346736e5357279c1fbb">AnalyzeLoadAvailability</a> (LoadInst *Load, LoadDepVect &amp;Deps, AvailValInBlkVect &amp;ValuesPerBlock, UnavailBlkVect &amp;UnavailableBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a list of non-local dependencies, determine if a value is available for the load in each specified block. <a href="#a36768091a495c346736e5357279c1fbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a554ab06dfc88e09773e4edf1ae6b9757">findLoadToHoistIntoPred</a> (BasicBlock *Pred, BasicBlock *LoadBB, LoadInst *Load)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a critical edge from Pred to LoadBB, find a load instruction which is identical to Load from another successor of Pred. <a href="#a554ab06dfc88e09773e4edf1ae6b9757">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1273ce1e1a4d4da230f67d20c070f8d3">PerformLoadPRE</a> (LoadInst *Load, AvailValInBlkVect &amp;ValuesPerBlock, UnavailBlkVect &amp;UnavailableBlocks)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f3629df4a98210b6695a2a871c3840">performLoopLoadPRE</a> (LoadInst *Load, AvailValInBlkVect &amp;ValuesPerBlock, UnavailBlkVect &amp;UnavailableBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to replace a load which executes on each loop iteraiton with Phi translation of load in preheader and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumarklastscratchload-cpp/#a8a3fe89940744b94ffe5dacd6704c2be">load(s)</a> in conditionally executed paths. <a href="#a08f3629df4a98210b6695a2a871c3840">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6b697d2d71d8acdcae306ad8c5a3a4f">eliminatePartiallyRedundantLoad</a> (LoadInst *Load, AvailValInBlkVect &amp;ValuesPerBlock, MapVector&lt; BasicBlock *, Value * &gt; &amp;AvailableLoads, MapVector&lt; BasicBlock *, LoadInst * &gt; *CriticalEdgePredAndLoad)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Eliminates partially redundant <span class="doxyComputerOutput">Load</span>, replacing it with <span class="doxyComputerOutput">AvailableLoads</span> (connected by Phis if needed). <a href="#ae6b697d2d71d8acdcae306ad8c5a3a4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a409c568a0cf6d1eadc338748c0f876ac">processInstruction</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When calculating availability, handle an instruction by inserting it into the appropriate sets. <a href="#a409c568a0cf6d1eadc338748c0f876ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab26e913f0b539a84fd05f0d8243ef89">processBlock</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d90fab8b539080c87c13ee5a2a35f3f">dump</a> (DenseMap&lt; uint32_t, Value * &gt; &amp;d) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a034bd384b4685148a356acb369148a51">iterateOnFunction</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Executes one iteration of GVN. <a href="#a034bd384b4685148a356acb369148a51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3ca257196732c65fdb55de2347d1fb0">performPRE</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a purely local form of PRE that looks for diamond control flow patterns and attempts to perform simple PRE at the join point. <a href="#aa3ca257196732c65fdb55de2347d1fb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac72ed47b852b5ec16b4c619209d3229c">performScalarPRE</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3faf4456489aa4307899493442a9263">performScalarPREInsertion</a> (Instruction *Instr, BasicBlock *Pred, BasicBlock *Curr, unsigned int ValNo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a999d7a6981d35fd4d415649745867980">findLeader</a> (const BasicBlock *BB, uint32_t num)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3df96476b5a72c0bf919cf678b68e8da">cleanupGlobalSets</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e25b780908a0ad31bf6a6c467b2ff8">removeInstruction</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae478cd0afce5f665b903e666c72026de">verifyRemoved</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that the specified instruction does not occur in our internal data structures. <a href="#ae478cd0afce5f665b903e666c72026de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c05580ee80ec2e52f8031fb648c0eaf">splitCriticalEdges</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split critical edges found during the previous iteration that may enable further optimization. <a href="#a2c05580ee80ec2e52f8031fb648c0eaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d3103d094e02c45bd85d9c490e5122b">splitCriticalEdges</a> (BasicBlock *Pred, BasicBlock *Succ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split the critical edge connecting the given two blocks, and return the block inserted to the critical edge. <a href="#a1d3103d094e02c45bd85d9c490e5122b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8caf8e3f67e0a9bfb78e50f12ad5a55a">replaceOperandsForInBlockEquality</a> (Instruction *I) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a287167c47f398d7ddc96aa28c9b31a18">propagateEquality</a> (Value *LHS, Value *RHS, const BasicBlockEdge &amp;Root, bool DominatesByEdge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The given values are known to be equal in every block dominated by 'Root'. <a href="#a287167c47f398d7ddc96aa28c9b31a18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed917f4a3c4e968a2eb05a56281c594c">processFoldableCondBr</a> (BranchInst *BI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d37c07cd1ce7d0d66294524213a67a">addDeadBlock</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BB is declared dead, which implied other blocks become dead as well. <a href="#ad9d37c07cd1ce7d0d66294524213a67a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac98a1d35be5317a325419bce193b7a8b">assignValNumForDeadCode</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8802138a750fc42622dcdc18e3a6c697">assignBlockRPONumber</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gvnoptions">GVNOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4872dd95e1b2e12a67b93f2d1f3f8e8d">Options</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults">MemoryDependenceResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b51549c2f13824b682f99bdf1cc2b30">MD</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84d4b8769beeb7c6fa4f6cb6d5096072">DT</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f4615b38281e1dc8e0bb7dee2d21075">TLI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59611f7431a9eb927d926eb8159c0304">AC</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade3873d950dffe8120470545656ff8e8">DeadBlocks</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45487bff9c9c5b57b59276fa645f8a59">ORE</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/implicitcontrolflowtracking">ImplicitControlFlowTracking</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31dfde3ecc7d57315577784362eaf68c">ICF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89e347a318825b56dd54bd6ddab7517b">LI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8825e7a8754152284c6b8357b1dfd230">MSSAU</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gvnpass/valuetable">ValueTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dbeb2bb2219628221836b087a7717fc">VN</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">LeaderMap</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9998ed2d8f7a097fd16abb2fc453254">LeaderTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/smallmapvector">SmallMapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5fdd7023ac99bf2e1e6d6a27c7f523a">ReplaceOperandsWithMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36703c1bcffea599057b99920e6fc3f6">InstrsToErase</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79c365aa18fca1a6533c0660186cd924">BlockRPONumber</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a691dc30a9468424c1e3d926ab0abfd3c">InvalidBlockRPONumbers</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, unsigned &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a898fe350cb5c5bc4aef93e35e9017d33">toSplit</a></td>
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

<p>The core GVN pass object.</p>


<p>FIXME: We should have a good summary of the GVN algorithm implemented by this particular pass here.</p>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AvailValInBlkVect {#a3f60d95a30f6b03ac0444e402430ba86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GVNPass::AvailValInBlkVect =  SmallVector&lt;gvn::AvailableValueInBlock, 64&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### LoadDepVect {#a063f1fae9025ed4f9d7186c26d8ed532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GVNPass::LoadDepVect =  SmallVector&lt;NonLocalDepResult, 64&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### UnavailBlkVect {#a9e3305b0655234e9925523630033bfe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GVNPass::UnavailBlkVect =  SmallVector&lt;BasicBlock *, 64&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DenseMapInfo&lt; Expression &gt; {#a8f1b6c33b018570dddad6adfde31870a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gvnpass/expression">Expression</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### gvn::GVNLegacyPass {#a1bd68f76e3641c20dfa1dec36e41cf61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/gvn/gvnlegacypass">gvn::GVNLegacyPass</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aaa43409c7dab66be0480defab2d17687">llvm::createGVNPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GVNPass() {#a62b9ab672829302405b735225d5e20b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GVNPass::GVNPass (<a href="/web-llvm/docs/api/structs/llvm/gvnoptions">GVNOptions</a> Options={})</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gvnpass/valuetable/#a5b8ab87af8cabbd0686f6e2e5c3a13ae">llvm::GVNPass::ValueTable::operator=</a> and <a href="/web-llvm/docs/api/classes/llvm/gvnpass/valuetable/#aa65e06a8ebf36de45b4859c5e3a52b03">llvm::GVNPass::ValueTable::phiTranslate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAliasAnalysis() {#a465c9577ba88345e23a496d47e185e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults * llvm::GVNPass::getAliasAnalysis ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### getDominatorTree() {#a82ed0f5454537781dd2949146821f7a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree &amp; llvm::GVNPass::getDominatorTree ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### getMemDep() {#aeb3aabd952dd6fc744032b003a67ec5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryDependenceResults &amp; llvm::GVNPass::getMemDep ()</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### isLoadInLoopPREEnabled() {#a9449bef29f49a1b4be0ba63609317a34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::isLoadInLoopPREEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 812 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a4088aff9f92891762f4ea3007c825296">GVNEnableLoadInLoopPRE</a>.</p>

</div>
</div>

### isLoadPREEnabled() {#a5046bdddf55a6ad3fd2ad7640b4f8d0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::isLoadPREEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#af6be18dc177c25396a20c8b0598befae">GVNEnableLoadPRE</a>.</p>

</div>
</div>

### isLoadPRESplitBackedgeEnabled() {#aac8394f15fa6e03d02344993ef4a15df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::isLoadPRESplitBackedgeEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 816 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#ab7d05d78d66adecbabb55b12bbcf2156">GVNEnableSplitBackedgeInLoadPRE</a>.</p>

</div>
</div>

### isMemDepEnabled() {#adf1278a3accfd7d0207e37273e4229d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::isMemDepEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 821 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a339391b287bf908cc66970a90f41da5b">GVNEnableMemDep</a>.</p>


<p>Referenced by <a href="#a25dcf17194b012b2b35388798cac2da7">run</a>.</p>

</div>
</div>

### isMemorySSAEnabled() {#a75b7cd0e780b19141e601e75a706fb5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::isMemorySSAEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 825 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a6d813a7562c8c6b0bfe4e730856c7ded">GVNEnableMemorySSA</a>.</p>


<p>Referenced by <a href="#a25dcf17194b012b2b35388798cac2da7">run</a>.</p>

</div>
</div>

### isPREEnabled() {#a1cc0652ed25618b41f317c0bae461e16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::isPREEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#aecfdc57f16d44724e335d66f1e811b95">GVNEnablePRE</a>.</p>

</div>
</div>

### markInstructionForDeletion() {#abefca2348c563ac9ceaab87ff2f2152f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GVNPass::markInstructionForDeletion (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>This removes the specified instruction from our various maps and marks it for deletion.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### printPipeline() {#a6796eb8a0e27f209321cbeff6a6faee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GVNPass::printPipeline (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; MapClassName2PassName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Reference <a href="#a6796eb8a0e27f209321cbeff6a6faee8">printPipeline</a>.</p>


<p>Referenced by <a href="#a6796eb8a0e27f209321cbeff6a6faee8">printPipeline</a>.</p>

</div>
</div>

### run() {#a25dcf17194b012b2b35388798cac2da7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses GVNPass::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run the pass over the function.</p>

<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 829 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#a828ff8185f881fca9e3d534781244041">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getCachedResult</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a>, <a href="#adf1278a3accfd7d0207e37273e4229d2">isMemDepEnabled</a> and <a href="#a75b7cd0e780b19141e601e75a706fb5c">isMemorySSAEnabled</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addDeadBlock() {#ad9d37c07cd1ce7d0d66294524213a67a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GVNPass::addDeadBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BB is declared dead, which implied other blocks become dead as well.</p>


<p>This function is to add all these blocks to "DeadBlocks". For the dead blocks' live successors, update their phi nodes by replacing the operands corresponding to dead blocks with UndefVal.</p>


<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 3181 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### AnalyzeLoadAvailability() {#ab449cc343665eeb9c96de359159002a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; AvailableValue &gt; GVNPass::AnalyzeLoadAvailability (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load, <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> DepInfo, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a local dependency (Def or Clobber) determine if a value is available for the load.</p>

<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 1257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### AnalyzeLoadAvailability() {#a36768091a495c346736e5357279c1fbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GVNPass::AnalyzeLoadAvailability (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load, <a href="/web-llvm/docs/api/classes/llvm/smallvector">LoadDepVect</a> &amp; Deps, <a href="/web-llvm/docs/api/classes/llvm/smallvector">AvailValInBlkVect</a> &amp; ValuesPerBlock, <a href="/web-llvm/docs/api/classes/llvm/smallvector">UnavailBlkVect</a> &amp; UnavailableBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a list of non-local dependencies, determine if a value is available for the load in each specified block.</p>


<p>If it is, add it to ValuesPerBlock. If not, add it to UnavailableBlocks.</p>


<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 1397 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### assignBlockRPONumber() {#a8802138a750fc42622dcdc18e3a6c697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GVNPass::assignBlockRPONumber (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 2394 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### assignValNumForDeadCode() {#ac98a1d35be5317a325419bce193b7a8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GVNPass::assignValNumForDeadCode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 3297 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### cleanupGlobalSets() {#a3df96476b5a72c0bf919cf678b68e8da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GVNPass::cleanupGlobalSets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 3151 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### dump() {#a4d90fab8b539080c87c13ee5a2a35f3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void GVNPass::dump (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint32_t, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 882 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### eliminatePartiallyRedundantLoad() {#ae6b697d2d71d8acdcae306ad8c5a3a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GVNPass::eliminatePartiallyRedundantLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load, <a href="/web-llvm/docs/api/classes/llvm/smallvector">AvailValInBlkVect</a> &amp; ValuesPerBlock, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; AvailableLoads, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * &gt; * CriticalEdgePredAndLoad)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Eliminates partially redundant <span class="doxyComputerOutput">Load</span>, replacing it with <span class="doxyComputerOutput">AvailableLoads</span> (connected by Phis if needed).</p>

<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 1495 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### findLeader() {#a999d7a6981d35fd4d415649745867980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * GVNPass::findLeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, uint32_t num)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 2361 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### findLoadToHoistIntoPred() {#a554ab06dfc88e09773e4edf1ae6b9757}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst * GVNPass::findLoadToHoistIntoPred (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Pred, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LoadBB, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a critical edge from Pred to LoadBB, find a load instruction which is identical to Load from another successor of Pred.</p>


<p>Given the following code, v1 is partially available on some edges, but not available on the edge from PredBB.</p>


<p>This function tries to find if there is another identical load in the other successor of PredBB.</p>



<pre><code> v0 = load %addr
 br %LoadBB
</code></pre>


<p>LoadBB: v1 = load addr ...</p>


<p>PredBB: ... br cond, label LoadBB, label SuccBB</p>


<p>SuccBB: v2 = load addr ...</p>


<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 1457 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### iterateOnFunction() {#a034bd384b4685148a356acb369148a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::iterateOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Executes one iteration of GVN.</p>

<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 3135 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### PerformLoadPRE() {#a1273ce1e1a4d4da230f67d20c070f8d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::PerformLoadPRE (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load, <a href="/web-llvm/docs/api/classes/llvm/smallvector">AvailValInBlkVect</a> &amp; ValuesPerBlock, <a href="/web-llvm/docs/api/classes/llvm/smallvector">UnavailBlkVect</a> &amp; UnavailableBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 1581 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### performLoopLoadPRE() {#a08f3629df4a98210b6695a2a871c3840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::performLoopLoadPRE (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load, <a href="/web-llvm/docs/api/classes/llvm/smallvector">AvailValInBlkVect</a> &amp; ValuesPerBlock, <a href="/web-llvm/docs/api/classes/llvm/smallvector">UnavailBlkVect</a> &amp; UnavailableBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to replace a load which executes on each loop iteraiton with Phi translation of load in preheader and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumarklastscratchload-cpp/#a8a3fe89940744b94ffe5dacd6704c2be">load(s)</a> in conditionally executed paths.</p>

<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 1835 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### performPRE() {#aa3ca257196732c65fdb55de2347d1fb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::performPRE (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a purely local form of PRE that looks for diamond control flow patterns and attempts to perform simple PRE at the join point.</p>

<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 3072 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### performScalarPRE() {#ac72ed47b852b5ec16b4c619209d3229c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::performScalarPRE (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 2908 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### performScalarPREInsertion() {#ae3faf4456489aa4307899493442a9263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::performScalarPREInsertion (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Instr, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Pred, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Curr, unsigned int ValNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 2859 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### processAssumeIntrinsic() {#a2a2d0007c1e09679867cebfff73029ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::processAssumeIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/assumeinst">AssumeInst</a> * II)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 2023 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### processBlock() {#aab26e913f0b539a84fd05f0d8243ef89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::processBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 2798 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### processFoldableCondBr() {#aed917f4a3c4e968a2eb05a56281c594c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::processFoldableCondBr (<a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> * BI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 3269 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### processInstruction() {#a409c568a0cf6d1eadc338748c0f876ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::processInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When calculating availability, handle an instruction by inserting it into the appropriate sets.</p>

<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 2585 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### processLoad() {#a774d11f023c46f5ef42b95684cc538a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::processLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to eliminate a load, first by eliminating it locally, and then attempting non-local elimination if that fails.</p>

<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 2170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### processNonLocalLoad() {#af6fe145bf27fa72c40dacb2354a2639a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::processNonLocalLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to eliminate a load whose dependencies are non-local by performing PHI construction.</p>

<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 1926 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### propagateEquality() {#a287167c47f398d7ddc96aa28c9b31a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::propagateEquality (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblockedge">BasicBlockEdge</a> &amp; Root, bool DominatesByEdge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The given values are known to be equal in every block dominated by 'Root'.</p>


<p>Exploit this, for example by replacing 'LHS' with 'RHS' everywhere in the scope. Returns whether a change was made. If DominatesByEdge is false, then it means that we will propagate the RHS value starting from the end of Root.Start.</p>


<p>Declaration at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 2423 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### removeInstruction() {#a39e25b780908a0ad31bf6a6c467b2ff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GVNPass::removeInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 3159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### replaceOperandsForInBlockEquality() {#a8caf8e3f67e0a9bfb78e50f12ad5a55a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::replaceOperandsForInBlockEquality (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 2403 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### runImpl() {#a570ea6443fd6d50edbc44b69ee2e1bea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::runImpl (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; RunAC, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; RunDT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; RunTLI, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; RunAA, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults">MemoryDependenceResults</a> * RunMD, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE, <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> * MSSA=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>runOnFunction - This is the main transformation entry point for a function.</p>

<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 2728 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### splitCriticalEdges() {#a2c05580ee80ec2e52f8031fb648c0eaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GVNPass::splitCriticalEdges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split critical edges found during the previous iteration that may enable further optimization.</p>

<p>Declaration at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 3115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### splitCriticalEdges() {#a1d3103d094e02c45bd85d9c490e5122b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * GVNPass::splitCriticalEdges (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Pred, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Succ)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split the critical edge connecting the given two blocks, and return the block inserted to the critical edge.</p>

<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 3099 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

### verifyRemoved() {#ae478cd0afce5f665b903e666c72026de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GVNPass::verifyRemoved (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that the specified instruction does not occur in our internal data structures.</p>

<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>, definition at line 3172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#a59611f7431a9eb927d926eb8159c0304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* llvm::GVNPass::AC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### BlockRPONumber {#a79c365aa18fca1a6533c0660186cd924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AssertingVH&lt;BasicBlock&gt;, uint32_t&gt; llvm::GVNPass::BlockRPONumber</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### DeadBlocks {#ade3873d950dffe8120470545656ff8e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;BasicBlock *&gt; llvm::GVNPass::DeadBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### DT {#a84d4b8769beeb7c6fa4f6cb6d5096072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::GVNPass::DT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### ICF {#a31dfde3ecc7d57315577784362eaf68c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImplicitControlFlowTracking* llvm::GVNPass::ICF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### InstrsToErase {#a36703c1bcffea599057b99920e6fc3f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 8&gt; llvm::GVNPass::InstrsToErase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### InvalidBlockRPONumbers {#a691dc30a9468424c1e3d926ab0abfd3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GVNPass::InvalidBlockRPONumbers = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### LeaderTable {#ac9998ed2d8f7a097fd16abb2fc453254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LeaderMap llvm::GVNPass::LeaderTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### LI {#a89e347a318825b56dd54bd6ddab7517b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::GVNPass::LI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### MD {#a6b51549c2f13824b682f99bdf1cc2b30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryDependenceResults* llvm::GVNPass::MD = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### MSSAU {#a8825e7a8754152284c6b8357b1dfd230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSAUpdater* llvm::GVNPass::MSSAU = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### Options {#a4872dd95e1b2e12a67b93f2d1f3f8e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GVNOptions llvm::GVNPass::Options</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### ORE {#a45487bff9c9c5b57b59276fa645f8a59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter* llvm::GVNPass::ORE = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### ReplaceOperandsWithMap {#ab5fdd7023ac99bf2e1e6d6a27c7f523a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallMapVector&lt;Value *, Value *, 4&gt; llvm::GVNPass::ReplaceOperandsWithMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### TLI {#a4f4615b38281e1dc8e0bb7dee2d21075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* llvm::GVNPass::TLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### toSplit {#a898fe350cb5c5bc4aef93e35e9017d33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;Instruction *, unsigned&gt;, 4&gt; llvm::GVNPass::toSplit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

### VN {#a8dbeb2bb2219628221836b087a7717fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueTable llvm::GVNPass::VN</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
